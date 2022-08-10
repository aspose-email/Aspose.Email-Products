---
title: Search PST document without opening via .NET 
weight: 3200
url: /net/search/pst/ 
description: C# source code to search words with pattern in PST file on .NET Framework, .NET Core, and Xamarin Platforms.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Search PST Formats in C#" h2="Native and high performance PST message search using server-side Aspose.Email for .NET APIs, without the use of any software like Microsoft or Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Email" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="PST" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Search PST File Using C#" %}}

 In order to search PST file, we’ll use
 [Aspose.Email for .NET](https://products.aspose.com/email/net) 
 API which is a feature-rich, powerful and easy to use document searching API for C# platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.email) 
 package manager, search for
 **Aspose.Email** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Search PST Files in C#" %}}

{{% blocks/products/pf/agp/text %}}

 A basic message search with
 [Aspose.Email for .NET](https://products.aspose.com/email/net) 
 APIs can be done with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

+  Load PST file.
+  Use Replace method of message Body.
+  Save message

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Our APIs are supported on all major platforms and Operating Systems. Before executing the code below, please make sure that you have the following prerequisites on your system.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, and Xamarin Platforms
-  Development environment like Microsoft Visual Studio
-  Aspose.Email for .NET DLL referenced in your project - Install from NuGet using the Download button above

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Search PST Files - C#" offSpacer="" %}}

```cs
MailMessage m = MailMessage.Load("GenerateMessage.pst");
m.Body = m.Body.Replace("[@@FullName@@", "Name to Replace");
m.Save("GenerateMessage.pst");
//In case BodyType of message is HTML. Then replacement would be in HtmlBody rather than Body alone.
//To filter messages with specific criteria https://docs.aspose.com/email/net/filter-messages-from-server-using-imap-client/  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Email for .NET API" %}}

 Aspose.Email is a Microsoft Outlook and Thunderbird formats parsing solution. One can easily create, manipulate, convert email and storage formats such as MSG, EMLX, EML and MHT. Handling of email attachments, customization of message headers and implementation of different network protocols like POP3, IMAP & SMTP to send & receive emails is much easier. Its a standalone API and does not require Microsoft Outlook or any other software installation. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online PST Search Live Demos" sectionDescription="Search text, words, phrases within PST documents right now by visiting our [Live Demos website](https://products.aspose.app/email/search). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your PST files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Search result appears instantly." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PST " readMoreLink="https://docs.fileformat.com/email/pst/" >}}
Files with .PST extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information. User information is stored in folders of different types that include emails, calendar items, notes, contacts, and several other file formats. PST files are used for archiving emailing data offline that can be later loaded and viewed in various applications. 

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Search Formats" subTitle="Using C#, one can also search other formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/search/eml/" name="EML" description="Outlook Email Messages" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/search/mbox/" name="MBOX" description="Electronic Mail Messages" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/search/msg/" name="MSG" description="Outlook & Exchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/search/ost/" name="OST" description="Offline Storage Files" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}