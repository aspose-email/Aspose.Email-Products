---
title: Gmail generator for C++
url: /cpp/gmail-generator/
description: How to generate fake Gmail addresses using C++
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="Generate Gmail address using C++" h2="Create your own temp Gmail generator with password using C++" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/headers/aspose_email-for-cpp.svg" pfName="Aspose.Email" subTitlepfName="for C++" downloadUrl="https://downloads.aspose.com/email/cpp" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email" subTitlepfName="for C++" >}}

{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" liveDemosLink="https://products.aspose.app/email/gmail-generator" codeSamplesLink="https://github.com/aspose-email/Aspose.Email-for-C" buyLink="https://purchase.aspose.com/buy" docsLink="https://docs.aspose.com/email/cpp/" nugetLink="https://www.nuget.org/packages/aspose.email.cpp.vc140/" nugetPackageName="Aspose.Email.Cpp.VC140" mavenRepoLink="" directDownloadLink="https://releases.aspose.com/email/cpp" >}}

{{% blocks/products/pf/feature-page-summary %}}

Gmail generator is a fairly common way to manage email subscriptions. In essence, this is an analogue of a provider of temporary email addresses, but much more flexible, reliable and secure.

The essence of the generator is to create additional Gmail addresses. You can use these additional addresses when registering on various websites. These websites will most likely send emails to the addresses you provide. Since the addresses are additional, all letters will go to your main address. But at the same time, an additional address generated by the application or prepared manually will be indicated as the recipient of the letter.

Searching for emails by recipient's address will allow you to filter out emails and perform automatic actions on them. One time or permanent. You can also catch websites sharing your address with third parties without your consent.

For example, let's say you generated an additional address username+for.spam.sender@gmail.com. You then passed it to the spam-sender.com website. After some time, you may receive an email from some other website, such as other-sender.com, but the recipient will be username+for.spam.sender@gmail.com. In any other situation, you wouldn't be able to figure out why other-sender.com is sending you promotional emails, but since you've used an alternate address, it's easy to see that spam-sender.com has shared your address with third parties. And if so, it makes no sense to unsubscribe from the mailing lists of these sites. Your additional address has probably already been included in some public base for sending unwanted emails. It will be much easier if you just block all mail coming to this additional address. It would be even better if you set up automatic movement of such emails to the spam folder. This setup will make life very difficult for these sites because Gmail will know that these sites are sending spam.

So let's figure out how to implement such a generator using Aspose.Email for C++.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Generate temp Gmail and operate with it" %}}

To generate an additional Gmail address, we don't actually need Aspose.Email, we don't need to interact with the Gmail service in any way. Any additional address that you make up manually or randomly, subject to certain rules, will work.

So what are these rules?

The points are not important. That is, in your address, before the ‘@’ symbol, you can both remove dots and add new ones between any pairs of letters.

Before the '@' character, you can add a '+' character with any set of letters and numbers after it.
Examples for the address “username@gmail.com”:
- u.ser.n.ame@gmail.com
- username+1@gmail.com
- username+facebook@gmail.com
- username+sfgdsr234@gmail.com

All these addresses can already be used when registering on websites. But on their own, they make little sense, because all messages coming to these addresses will end up in your main mailbox. Therefore, it is worth using our instructions for working with these addresses.

### Simple temp Gmail generator

So let's create a simple random sub address generator. To do this, we will add a random string between the '+' and '@' characters. First of all, we need to generate a random string of a certain length, consisting of a certain set of characters:

```cpp
const char16_t pattern[] = u"abcdefghijklmnopqrstuvwxyz0123456789";
auto patternLength = std::char_traits<char16_t>::length(pattern);
const int suffixLength = 10;
std::string generatedSuffix;
generatedSuffix.reserve(suffixLength);
srand(time(NULL));
for (int i = 0; i < suffixLength; i++)
{
    generatedSuffix += pattern[rand() % (patternLength - 1)];
}
```

Now we need to get the email address and add the generated random string to it. To do this, we will use the <a href="https://reference.aspose.com/email/cpp/class/aspose.email.mail_address/" rel="nofollow noopener" target="_blank">MailAdress</a> class from the Aspose.Email for C++ library:

```cpp
auto originalAddress = System::MakeObject<MailAddress>(System::String(u"some.address@gmail.com"));
auto generatedAddress = System::MakeObject<MailAddress>(
    originalAddress->get_User() + u"+" + generatedSuffix + u"@" + originalAddress->get_Host());
Console::WriteLine(generatedAddress);
```

Done! The received address can already be used when registering on websites. Websites will soon start sending messages to this address. Let's see what we can do with these messages.

### Use IMAP client to operate with messages received to the generated Gmail

First, in order to operate on messages received at an additional address, we need to connect to Gmail. IMAP is well suited for this. To connect using this protocol, don't forget to set your account to allow connection to it using this protocol. Also, you can simplify the IMAP connection with a dedicated application password. This will allow you to avoid the need to perform OAuth authorization if you do not want to implement it in your application. Just go to your Google account settings, open the Security section and add an App password. Don't forget to save the generated password in secure storage and try not to lose it, because it gives you full access to your mail!

So, let's use the <a rel="nofollow noopener" target="_blank" href="https://reference.aspose.com/email/cpp/class/aspose.email.clients.imap.imap_client/">ImapClient</a> class and connect to your Gmail account using the IMAP protocol:

```cpp
auto imapClient = System::MakeObject<Clients::Imap::ImapClient>(
    u"imap.gmail.com", 993, originalAddress->get_User(), u"password",
    SecurityOptions::SSLAuto);
```

Done, now we can, for example, get all the messages received at the generated Gmail address:

```cpp
imapClient->SelectFolder(u"INBOX");
auto queryBuilder = System::MakeObject<ImapQueryBuilder>();
queryBuilder->get_To()->Contains(generatedAddress->get_Address());

auto list = imapClient->ListMessages(queryBuilder->GetQuery());
```

And you will receive absolutely all such letters. It doesn't matter what site they came to you from. They could have come from the site to which you gave the generated email address. Could have come from another site. From any address. We screen emails not by sender, but by the recipient. And it's very convenient.

### Mark, remove, move messages received to the temp Gmail

Having received the list of letters, we can already perform various operations on it. Above all at once. You don't have to find them in your mailbox one by one. Literally, a couple of commands and all letters are marked as read, moved to another folder, or simply deleted. Just don't forget to check beforehand that the list of letters is not empty. You may have already deleted everything.

```cpp
if (list->get_Count() > 0)
{
    //Mark as read
    imapClient->AddMessageFlags(list, ImapMessageFlags::get_IsRead());
    //Move
    imapClient->MoveMessages(list, u"DestinationFolder");
    //Remove
    imapClient->DeleteMessages(list, true);
}
```

Done, your inbox has been cleared of spam.

### Subscribe to temp Gmail address

So what if you don't want to constantly delete or flag emails by manually calling the code above? What if you want to delete emails as soon as they are received? To do this, for example, you can subscribe to new messages and write a function that deletes messages as soon as they arrive at your email address.

```cpp
std::function<void(System::SharedPtr<System::Object> sender, System::SharedPtr<Clients::Imap::ImapMonitoringEventArgs> eventArgs)> subscribeCallback =
[&generatedAddress, &imapClient](System::SharedPtr<System::Object> sender, System::SharedPtr<ImapMonitoringEventArgs> eventArgs)
{
    auto newMessages = eventArgs->get_NewMessages();
    auto generated = System::MakeObject<ImapMessageInfoCollection>();
    for each (auto newMessage in newMessages)
    {
        for each (auto address in newMessage->get_To())
        {
            if (address->get_Address() == generatedAddress->get_Address())
            {
                generated->Add(newMessage);
                break;
            }
        }
    }
    if (generated->get_Count() == 0) return;

    imapClient->SelectFolder(u"INBOX");

    //Do something with the received messages. For example, mark them as read:
    imapClient->AddMessageFlags(generated, ImapMessageFlags::get_IsRead());

    //or delete them
    imapClient->DeleteMessages(generated, true);
};

std::function<void(System::SharedPtr<System::Object> sender, System::SharedPtr<Clients::Imap::ImapMonitoringErrorEventArgs> eventArgs)> errorCallback =
[](System::SharedPtr<System::Object> _, System::SharedPtr<ImapMonitoringErrorEventArgs> errorEventArgs)
{
    Console::WriteLine(errorEventArgs->get_Error()->get_Message());
};

imapClient->StartMonitoring(subscribeCallback, errorCallback, u"INBOX");
```

This algorithm is slightly simplified because, in case of an error, the subscription to new messages will be interrupted. You can greatly improve the algorithm. To do this, you need to refine the algorithm by improving error handling. For example, you can set up the resumption of monitoring in case of an error, for this, you can use the ImapClient.ResumeMonitoring function. This function will re-establish a connection to the IMAP server and resume monitoring for new messages.

Unfortunately, in order to use this algorithm, you have to keep the program constantly running anyway. As soon as you interrupt the execution of the program, new letters will no longer be automatically deleted. But in this case, there is another solution.

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Stop receiving messages to the generated Gmail address" %}}

Gmail provides algorithms for filtering incoming messages. These algorithms work on the service side and will never let through unwanted mail, if you, of course, configure them correctly. At the moment, unfortunately, we cannot provide you with the functionality to remotely configure such filters using C++, but we plan to add such an opportunity in the near future. Please follow our updates!

So, if you want to filter messages coming into the generated Gmail, you first need to create a search template for the filter. Here is the simplest code to get the template:

```cpp
//Generate Gmail search pattern
auto searchPattern = System::String(u"to:(") + generatedAddress->get_Address() + u")";
Console::WriteLine(searchPattern);
```

Here, the variable ```generatedAddress``` contains the generated Gmail that was created earlier in this article. The above code will create a search template and print it to the terminal. Copy this template because you will need it when creating the filter.

Now let's describe step by step how you can create a filter. To get started, open the Gmail email web interface, it's available at <a href="https://mail.google.com/mail" rel="nofollow noopener" target="_blank">the link</a>. In this interface, find the search bar:

![step1](/email/net/gmail-generator/step1.webp)

In this search bar, you need to insert the template generated earlier in this instruction. Next, you need to click on the “Show search options” button, which is indicated in the screenshot below:

![step2](/email/net/gmail-generator/step2.webp)

In the search options window that opens, you do not need to enter any additional data, the generated template has already configured the search. Just click on the "Create filter" button.

![step3](/email/net/gmail-generator/step3.webp)

As a result, the filter settings window will open:

![step4](/email/net/gmail-generator/step4.webp)

Here you can choose what the filter should do with emails received at the generated Gmail address. You can automatically archive them, mark them as read, delete them, and so on. As a rule, the best option is to delete emails. The volume of the mailbox is limited, it makes no sense to spend it on garbage storage. After you select the actions that suit you, click on the “Create filter” button again.

Done! The filter is fully configured, so no more junk mail will bother you.


{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Manage temp Gmail filters" %}}

Sometimes messages you receive from a particular website become unsolicited. They just become garbage in your mailbox and prevent you from finding in it what is really important and interesting to you. As a result, you create a filter that blocks unwanted messages from this website. But what if the messages from the website are no longer spam? For example, you want to recover your password. A website sends you an email with a link to a password reset form, but you can't receive it because the filter immediately deletes the email.

Fortunately, there is an elegant way out of this situation. You can temporarily reconfigure the filter so that it does not delete these emails. Or you can remove the filter altogether. Let's see how this can be done.

First, open the Gmail web interface. On the page that opens, click on the "Settings" button:

![step1](/email/net/gmail-generator/manage1.webp)

In the window that opens, click on the "See all settings" button:

![step2](/email/net/gmail-generator/manage2.webp)

The Gmail account settings window will open. It contains many tabs for fine-tuning your email experience. We are interested in the "Filters and Blocked Addresses" tab. Open this tab:

![step3](/email/net/gmail-generator/manage3.webp)

In the tab that opens, you will see a list of filters for the generated Gmails that you created earlier, as well as possibly other filters:

![step4](/email/net/gmail-generator/manage4.webp)

By the description of the filters, you can easily determine which one is responsible for the address you want to unblock. By clicking on the "delete" button, you can permanently disable the filter. If you click on the “edit” button, you can reconfigure the filter. For example, instead of deleting emails, you can flag them. This way you can save the filter and make it easier to turn it on in the future. By editing the filter, you will be able to receive the necessary emails from the website. As soon as you want to block generated Gmail back, open the filter again with the “edit” button and reconfigure the actions.

That's all. You are now a pro with generated Gmail addresses. You can create a huge number of addresses and masterfully manage the flow of emails coming to your Gmail. Using additional addresses, you will be able to track sites that transfer your data to third parties without your consent. You'll be able to block spam without having to retrain your anti-spam system or without having to hit the Unsubscribe buttons multiple times. You can automate spam removal using Aspose.Email .NET or manually through the settings and Gmail interface.

{{% /blocks/products/pf/feature-page-section %}}

{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}