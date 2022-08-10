---
title: Merge MSG Files via .NET 
url: /net/merger/msg/ 
description: C# source code to combine MSG documents on .NET Framework, .NET Core, and Xamarin Platforms.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Merge MSG Formats in C#" h2="Native and high performance MSG message merger using server-side Aspose.Email for .NET APIs, without the use of any software like Microsoft or Open Office, Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Email" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="MSG" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Merge MSG File Using C#" %}}

In order to merge MSG file, we’ll use <a href="https://products.aspose.com/email/net">Aspose.Email for .NET</a> API which is a feature-rich, powerful and easy to use document manipulation and merging API for C# platform. Open <a href="https://www.nuget.org/packages/aspose.email">NuGet</a> package manager, search for <b>Aspose.Email</b> and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps for Merging MSG Files in C#" %}}

{{% blocks/products/pf/agp/text %}}

 A basic document merging and concatenating with
 [Aspose.Email for .NET](https://products.aspose.com/email/net) 
 APIs can be done with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Load all the MSG files with full path.
1. Make one document as the base file
1. Call the relevant method for concatenating and merging files one by one.
1. Call the Save() method and pass the file name (full path) and format (MSG) as a parameter.
1. Now you can open and use the MSG file in Microsoft Office, Adobe PDF or any other compatible program.


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Our APIs are supported on all major platforms and Operating Systems. Before executing the code below, please make sure that you have the following prerequisites on your system.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms
-  Development environment like Microsoft Visual Studio
-  Aspose.Email for .NET DLL referenced in your project - Install from NuGet using the Download button above

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Merge MSG Files - C#" offSpacer="" %}}

```cs
string dataDir = RunExamples.GetDataDir_Outlook();
    string dst = dataDir + "Sub.pst";
    totalAdded = 0;
    using (PersonalStorage personalStorage = PersonalStorage.FromFile(dst)){
    // The events subscription is an optional step for the tracking process only.
    personalStorage.StorageProcessed += PstMerge_OnStorageProcessed;
    personalStorage.ItemMoved += PstMerge_OnItemMoved;
    // Merges with the pst files that are located in separate folder. 
    personalStorage.MergeWith(Directory.GetFiles(dataDir + @"MergePST\"));
    Console.WriteLine("Total messages added: {0}", totalAdded);
    }  

        

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Email is a Microsoft Outlook and Thunderbird formats parsing solution. One can easily create, manipulate, convert email and storage formats such as MSG, EMLX, EML and MHT. Handling of email attachments, customization of message headers and implementation of different network protocols like POP3, IMAP & SMTP to send & receive emails is much easier. Its a standalone API and does not require Microsoft Outlook or any other software installation.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online MSG Merger Live Demos" sectionDescription="Merge MSG documents right now by visiting our [Live Demos website](https://products.aspose.app/email/merger). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your MSG files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be merged and concatenated instantly." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MSG" readMoreLink="https://docs.fileformat.com/email/msg/" >}}
MSG is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks. Such messages may contain one or more email fields, with the sender, recipient, subject, date, and message body, or contact information, appointment particulars, and one or more task specifications. The properties that constitute the Message object, including are also a part of the MSG file.  MSG file has headers, main message body, and hyperlinks as plain ASCII text. MSG files are also suitable with the programs that need Microsoft's Messaging Applications Programming Interface (MAPI). 

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}