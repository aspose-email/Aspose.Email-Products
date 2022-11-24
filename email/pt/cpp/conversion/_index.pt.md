---
title: API de e-mail C++ para conversão de formatos Thunderbird e Outlook
url: /pt/cpp/conversion/
description: Amostras de código C++ para os formatos Thunderbird e OutLook EML EMLX MBOX ICS MSG HTML OFT OLM OST PST e conversão VCF via biblioteca de e-mail.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversão de Formatos Thunderbird e Outlook Via C++" h2="Microsoft<sup>&reg;</sup> Análise e conversão de arquivos de e-mail Outlook e Thunderbird e arquivos de mensagens para criar aplicativos C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
Use a API de e-mail C++ para analisar formatos, incluindo MSG, EML, EMLX e MHT, sem conhecer os detalhes da especificação do formato para criar soluções de processamento de e-mail. Além disso, os desenvolvedores podem gerenciar mensagens MIME, formatos do Outlook, produzir e consumir padrões de recorrência do iCalendar (RFC 2445) e muito mais.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Salvar formatos de e-mail em formatos diferentes" %}}

O processo de conversão é simples principalmente para os formatos Outlook e Thunderbird. Discutindo alguns casos aqui, **EML para MHTML** and **MSG para HTML** com informações de cabeçalho e fuso horário personalizado. Para o primeiro caso, carregue o arquivo necessário [MailMessage](https://apireference.aspose.com/email/cpp/class/aspose.email.mail_message)::Carregue e chame o método Salvar com a extensão necessária e [SaveOptions](https://apireference.aspose.com/email/cpp/class/aspose.email.save_options). E para o segundo caso, definiremos o fuso horário personalizado e usaremos [HtmlSaveOptions](https://apireference.aspose.com/email/cpp/class/aspose.email.html_save_options) para definir as informações do cabeçalho.


{{% blocks/products/pf/feature-page-code h3="Código C++ para conversão de EML para MHTML" %}}

{{< gist "aspose-com-gists" "fe1d255cb80694067eacaca6eeb6dac9" "convert-eml-to-mhtml.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Código C++ para conversão de MSG para HTML" %}}

{{< gist "aspose-com-gists" "fe1d255cb80694067eacaca6eeb6dac9" "convert-msg-to-html.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="eml-to-pdf eml-to-html eml-to-msg emlx-to-msg msg-to-pdf pst-to-eml" >}}