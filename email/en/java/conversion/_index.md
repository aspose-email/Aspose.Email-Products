---
title: Java Email API for Thunderbird and OutLook Formats Conversion
url: /java/conversion/
description: Java code examples for converting Thunderbird and OutLook formats EML EMLX MBOX ICS MSG HTML OFT OLM OST PST and VCF via Email library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Thunderbird and Outlook Email Formats Conversion Via Java" h2="Microsoft<sup>&reg;</sup> Outlook and Thunderbird files conversion and parsing to build cross-platform Java applications" >}}

{{% blocks/products/pf/feature-page-summary %}}
Java Email API to build cross-platform mail processing solutions having the ability to generate, manipulate, process and convert messages without the installation of Microsoft Outlook<sup>&reg;</sup>. Developers can easily enhance applications for adding custom headers, attachments, validating email addresses and conversion between formats such as EML, MSG, MBOX, OST, PST and MHT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Email Formats to Different Formats" %}}

Developers can easily convert supported message formats using Java library. It simply loads the source file into API object model and call the save method having the relevant parameters. e.g For converting EML to MSG, There is [MailMessage](https://apireference.aspose.com/email/java/com.aspose.email/MailMessage) Load function for getting source file and calling the save method having output file and [SaveOptions](https://apireference.aspose.com/email/java/com.aspose.email/SaveOptions) as relevant parameters.

Considering another scenario of Mbox to HTML conversion, Process is, read the Mbox file using [MboxrdStorageReader](https://apireference.aspose.com/email/java/com.aspose.email/MboxrdStorageReader), Iterate through each message, and save it to into HTML file by providing file path and [MailMessageSaveType](https://apireference.aspose.com/email/java/com.aspose.email/MailMessageSaveType) as parameters into save method.


{{% blocks/products/pf/feature-page-code h3="Java Code for EML to MSG Conversion" %}}

{{< gist "aspose-com-gists" "9e945d8deb696f51f3b130113f186b01" "convert-eml-to-msg.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java Code for Mbox to HTML Conversion" %}}

{{< gist "aspose-com-gists" "9e945d8deb696f51f3b130113f186b01" "convert-mbox-to-html.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="eml-to-pdf eml-to-html eml-to-msg emlx-to-msg msg-to-pdf pst-to-eml" >}}