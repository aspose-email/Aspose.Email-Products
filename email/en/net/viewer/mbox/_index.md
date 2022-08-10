---
title: View MBOX File Formats via .NET 
weight: 3460
url: /net/viewer/mbox/ 
description: C# source code to load, render and display MBOX documents on .NET Framework, .NET Core, and Xamarin Platforms.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="MBOX File Viewer for .NET" h2="View MBOX without needing Microsoft Outlook or Thunderbird installed." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="MBOX" pfName="Aspose.Email" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MBOX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to View MBOX File Using C#" %}}

 In order to view MBOX file, we’ll use
 [Aspose.Email for .NET](https://products.aspose.com/email/net) 
 API which is a feature-rich, powerful and easy to use API for C# platform to be used with any Viewer. Open
 [NuGet](https://www.nuget.org/packages/aspose.email) 
 package manager, search for
 **Aspose.Email** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to View MBOX via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email makes it easy for the developers to view the MBOX file with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

1.  Load MBOX file in an instance of MailMessage via Load method
1.  Call the MailMessage.Save method to save MBOX in HTML format
1.  Call Process.Start with path to resultant HTML to load MBOX content in default browser

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email for .NET is supported on all major operating systems. Just make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, and Xamarin Platforms
-  Development environment like Microsoft Visual Studio
-  Aspose.Email for .NET referenced in your project

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code to view MBOX" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the MBOX file in an instance of MailMessage
using (var message = Aspose.Email.MailMessage.Load("template.mbox"))
{
    // save MBOX in HTML format
    message.Save(output, Aspose.Email.SaveOptions.DefaultHtml);
}
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Email for .NET API" %}}

 Aspose.Email is a Microsoft Outlook and Thunderbird formats parsing solution. One can easily create, manipulate, convert email and storage formats such as MSG, EMLX, EML and MHT. Handling of email attachments, customization of message headers and implementation of different network protocols like POP3, IMAP & SMTP to send & receive emails is much easier. Its a standalone API and does not require Microsoft Outlook or any other software installation. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to View MBOX" sectionDescription="Check our live demos to [View MBOX](https://products.aspose.app/email/viewer/mbox) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload MBOX file and hit the \"View\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download MBOX file from the link, if required" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MBOX" readMoreLink="https://docs.fileformat.com/email/mbox/" >}}
MBox file format is a generic term that represents a container for collection of electronic mail messages. The messages are stored inside the container along with their attachments. Messages from an entire folder are saved in a single database file and new messages are appended to the end of the file. Numerous applications and API provide support for MBox file format such as Apple Mail and Mozilla Thunderbird.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Viewer Formats" subTitle="Using C#, One can also view many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/eml/" name="EML" description="Outlook Email Messages" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/emlx/" name="EMLX" description="Apple EMLX Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/ics/" name="ICS" description="iCalendar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/msg/" name="MSG" description="Outlook & Exchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/oft/" name="OFT" description="Outlook Email Templates" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/ost/" name="OST" description="Offline Storage Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/pst/" name="PST" description="Outlook Personal Storage Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/vcf/" name="VCF" description="Virtual Card Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}