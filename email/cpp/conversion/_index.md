---
title: C++ Email API for Thunderbird and OutLook Formats Conversion
url: /cpp/conversion/
description: C++ code samples for Thunderbird and OutLook formats EML EMLX MBOX ICS MSG HTML OFT OLM OST PST and VCF conversion via Email library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Thunderbird and Outlook Formats Conversion Via C++" h2="Microsoft<sup>&reg;</sup> Outlook and Thunderbird email files and message archives parsing and conversion to build C++ applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
Use C++ Email API for parsing formats including MSG, EML, EMLX & MHT without knowing the detail of format specification to build mail processing solutions. Moreover, Developers can manage MIME messages, Outlook formats, produce and consume iCalendar (RFC 2445) recurrence patterns and more.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Save Email Formats to Different Formats" %}}

Conversion process is simple for mostly Outlook and Thunderbird formats. Discussing few cases here, **EML to MHTML** and **MSG to HTML** with header information and custom timezone. For the first case, load the required file [MailMessage](https://apireference.aspose.com/email/cpp/class/aspose.email.mail_message)::Load and call the Save mehtod with required extension and [SaveOptions](https://apireference.aspose.com/email/cpp/class/aspose.email.save_options). And for the second case we will set the custom time zone and use [HtmlSaveOptions](https://apireference.aspose.com/email/cpp/class/aspose.email.html_save_options) for setting header information.


{{% blocks/products/pf/feature-page-code h3="C++ Code for EML to MHTML Conversion" %}}

{{< gist "aspose-com-gists" "fe1d255cb80694067eacaca6eeb6dac9" "convert-eml-to-mhtml.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="C++ Code for MSG to HTML Conversion" %}}

{{< gist "aspose-com-gists" "fe1d255cb80694067eacaca6eeb6dac9" "convert-msg-to-html.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="eml-to-pdf eml-to-html eml-to-msg emlx-to-msg msg-to-pdf pst-to-eml" >}}