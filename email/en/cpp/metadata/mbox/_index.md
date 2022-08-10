---
title: Edit or View MBOX Document Metadata via C++ 
weight: 930
url: /cpp/metadata/mbox/ 
description: C++ example code to edit or view MBOX file metadata on C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extract MBOX Metadata via C++" h2="Build your own C++ apps to add, edit, remove or extract metadata from MBOX files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="MBOX" pfName="Aspose.Email" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="for C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/cpp" installationsDocsLink="https://docs.aspose.com/email/cpp" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/cpp" learnAsLink="https://docs.aspose.com/email/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Get MBOX Metadata Using C++" %}}

 In order to extract MBOX metadata, we’ll use
 [Aspose.Email for C++](https://products.aspose.com/email/cpp) 
 API which is a feature-rich, powerful and easy to use document metadata extraction API for C++ platform. You can download its latest version directly, just open
 [NuGet](https://www.nuget.org/packages/aspose.email) 
 package manager, search for
 **Aspose.Email.Cpp** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Extract Metadata of MBOX via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Get the type of the message while using GetProperties which in turn allows getting all metadata information via a simple loop.

{{% /blocks/products/pf/agp/text %}}

+  Load the MBOX file via MapiMessage::FromFile
+  Get properties collection using get\_Properties()
+  Get the respective property using idx\_get

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email for C++ supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
-  Aspose.Email for C++ DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extract Metadata of MBOX - C++" offSpacer="" %}}

```cs

// Load from file
System::SharedPtr<MapiMessage> mbox = MapiMessage::FromFile(dataDir + L"message.mbox");
    
System::String subject;
    
// Access the MapiPropertyTag.PR_SUBJECT property
System::SharedPtr<MapiProperty> prop = mbox->get_Properties()->idx_get(MapiPropertyTag::PR_SUBJECT);
    
// If the property is not found, check the MapiPropertyTag.PR_SUBJECT_W (which is a // Unicode peer of the MapiPropertyTag.PR_SUBJECT)
if (prop == nullptr){
    prop = mbox->get_Properties()->idx_get(MapiPropertyTag::PR_SUBJECT_W);
}
    
// Cannot found
if (prop == nullptr){
    System::Console::WriteLine(L"No property found!");
    return;
}
    
// Get the property data as string
subject = prop->GetString();
    
System::Console::WriteLine(System::String(L"Subject:") + subject);
// Read internet code page property
prop = msg->get_Properties()->idx_get(MapiPropertyTag::PR_INTERNET_CPID);
if (prop != nullptr){
    System::Console::WriteLine(System::String(L"CodePage:") + prop->GetLong());
}  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Email for C++ API" %}}

 Aspose.Email is a Microsoft Outlook and Thunderbird formats parsing solution. One can easily create, manipulate, convert email and storage formats such as MSG, EMLX, EML and MHT. Handling of email attachments, customization of message headers and implementation of different network protocols like POP3, IMAP & SMTP to send & receive emails is much easier. Its a standalone API and does not require Microsoft Outlook or any other software installation. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of MBOX via Online App" sectionDescription="View & edit Metadata to MBOX documents by using our [Live Demos](https://products.aspose.app/email/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your MBOX file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MBOX" readMoreLink="https://docs.fileformat.com/email/mbox/" >}}
MBox file format is a generic term that represents a container for collection of electronic mail messages. The messages are stored inside the container along with their attachments. Messages from an entire folder are saved in a single database file and new messages are appended to the end of the file. Numerous applications and API provide support for MBox file format such as Apple Mail and Mozilla Thunderbird.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Metadata Formats" subTitle="Using C++, One can also manipulate metadata of many other formats including" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/metadata/eml/" name="EML" description="Outlook Email Messages" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/metadata/msg/" name="MSG" description="Outlook & Exchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/metadata/ost/" name="OST" description="Offline Storage Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/metadata/pst/" name="PST" description="Outlook Personal Storage Files" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}