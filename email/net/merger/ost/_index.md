---
title: Merge OST Files via .NET 
url: /net/merger/ost/ 
description: Try our On-Premise message merger APIs to combine OST documents on .NET Framework, .NET Core, and Xamarin Platforms.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Merge OST Formats in C#" h2="Native and high performance OST message merger using server-side Aspose.Email for .NET APIs, without the use of any software like Microsoft or Open Office, Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Email" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="OST" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="https://products.aspose.app/email/family" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Merge OST File Using C#" %}}

In order to merge OST file, we’ll use <a href="https://products.aspose.com/email/net">Aspose.Email for .NET</a> API which is a feature-rich, powerful and easy to use document manipulation and merging API for C# platform. Open <a href="https://www.nuget.org/packages/aspose.email">NuGet</a> package manager, search for <b>Aspose.Email</b> and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps for Merging OST Files in C#" %}}

{{% blocks/products/pf/agp/text %}}

 A basic document merging and concatenating with
 [Aspose.Email for .NET](https://products.aspose.com/email/net) 
 APIs can be done with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Load all the OST files with full path.
1. Make one document as the base file
1. Call the relevant method for concatenating and merging files one by one.
1. Call the Save() method and pass the file name (full path) and format (OST) as a parameter.
1. Now you can open and use the OST file in Microsoft Office, Adobe PDF or any other compatible program.


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Our APIs are supported on all major platforms and Operating Systems. Before executing the code below, please make sure that you have the following prerequisites on your system.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, Windows Azure, Mono or Xamarin Platforms
-  Development environment like Microsoft Visual Studio
-  Aspose.Email for .NET DLL referenced in your project - Install from NuGet using the Download button above

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Merge OST Files - C#" offSpacer="" %}}

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

Aspose.Email is a Microsoft Outlook and Thunderbird formats parsing solution. One can easily create, manipulate, convert email and storage formats such as MSG, EMLX, EML and MHT. Handling of email attachments, customization of message headers and implementation of different network protocols like POP3, IMAP & SMTP to send & receive emails is much easier. Its a standalone API and does not require Microsoft Outlook or any other software installation. ‎ ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online OST Merger Live Demos" sectionDescription="Merge OST documents right now by visiting our [Live Demos website](https://products.aspose.app/email/merger). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your OST files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be merged and concatenated instantly." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="OST" readMoreLink="https://docs.fileformat.com/email/ost/" >}}
OST or Offline Storage Files represent user's mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. It is automatically created on the first use of Microsoft Outlook upon connectivity with server. Once the file is created, the data is synchronized with the email server so that it is available offline as well in case of disconnectivity from email server. OST files can user mailbox items such as emails, contacts, calendar information, notes, tasks and other similar data. Users can create emails and other data items in OST file even in the absence of connection to the server, but these will not be synchronized with the server. Once the connection is established, the local file is synchronized with the server again so that both the server and the local copy are at the same level of information. Read More

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}