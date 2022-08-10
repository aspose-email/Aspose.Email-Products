---
title: Convert MHTML to EMLX via C# 
weight: 1680
url: /net/conversion/mhtml-to-emlx/ 
description: Sample code for MHTML to EMLX C# conversion. Use API example code for batch MHTML files to EMLX conversion within VB.NET, Asp.NET or any .NET based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert MHTML to EMLX via C#" h2="MHTML to EMLX C# conversion using .NET API without needing Outlook® or Thunderbird®." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMLX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert MHTML to EMLX Using C#" %}}

 In order to convert MHTML to EMLX, we’ll use
 [Aspose.Email for .NET](https://products.aspose.com/email/net) 
 API which is a feature-rich, powerful and easy to use document manipulation and conversion API for C# platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.email) 
 package manager, search for
 Aspose.Email 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert MHTML to EMLX via C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programmers can easily load & convert MHTML files to EMLX in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

+  Load MHTML file with MailMessage.Load.
+  Call the Save method.
+  Pass the output file path with EMLX file extension.
+  EMLX file will be saved at the specified path.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before running the .NET conversion code, make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop.
-  Development environment like Microsoft Visual Studio.
-  Aspose.Email for .NET DLL referenced in your project.
-  Include namespace in relevant class.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This sample code shows MHTML to EMLX C# Conversion" offSpacer="" %}}

```cs
// load the MHTML file to be converted
var message = MailMessage.Load("My File.mhtml");
// save MHTML as a EMLX 
message.Save("Saved File.emlx", SaveOptions.CreateSaveOptions(MailMessageSaveType.EmlxFormat));  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert MHTML to EMLX" sectionDescription="Check our live demos for [MHTML to EMLX conversion](https://products.aspose.app/email/conversion/mhtml-to-emlx) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your MHTML file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant EMLX file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Email API is a Microsoft Outlook and Thunderbird formats parsing solution. One can easily create, manipulate, convert email and storage formats such as MSG, EMLX, EML and MHT. Handling of email attachments, customization of message headers and implementation of different network protocols like POP3, IMAP & SMTP to send & receive emails is much easier. Its a standalone API and does not require Microsoft Outlook or any other software installation. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}
Files with MHTML extension represent a web page archive format that can be created by a number of different applications. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. Microsoft Windows uses MHTML file format for recording scenarios of problems observed during the usage of any application on Windows that raises issues. The MHTML file format encodes the page contents similar to specifications defined in message/rfc822 which is plain text email related specifications. The actual specifications of the format are as detailed by RFC 2557.

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="emlx" readMoreLink="https://docs.fileformat.com/email/emlx/" >}}
The EMLX file format is implemented and developed by Apple. The Apple Mail application uses the EMLX file format for exporting the emails. There are other applications as well that can open the EMLX files and convert these to other file formats.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="You can also convert MHTML into many other file formats including few listed below." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/mhtml-to-eml/" name="MHTML TO EML" description="Outlook Email Messages" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/mhtml-to-html/" name="MHTML TO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/mhtml-to-ics/" name="MHTML TO ICS" description="iCalendar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/mhtml-to-mbox/" name="MHTML TO MBOX" description="Electronic Mail Messages" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/mhtml-to-msg/" name="MHTML TO MSG" description="Outlook & Exchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/mhtml-to-oft/" name="MHTML TO OFT" description="Outlook Email Templates" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/mhtml-to-ost/" name="MHTML TO OST" description="Offline Storage Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/mhtml-to-pst/" name="MHTML TO PST" description="Outlook Personal Storage Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/mhtml-to-vcf/" name="MHTML TO VCF" description="Virtual Card Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}