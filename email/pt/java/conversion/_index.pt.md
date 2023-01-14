---
title: API de e-mail Java para conversão de formatos Thunderbird e Outlook
url: /pt/java/conversion/
description: Exemplos de código Java para converter os formatos Thunderbird e OutLook EML EMLX MBOX ICS MSG HTML OFT OLM OST PST e VCF via biblioteca de e-mail.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversão de Formatos de E-mail Thunderbird e Outlook Via Java" h2="Microsoft<sup>&reg;</sup> Conversão e análise de arquivos Outlook e Thunderbird para criar aplicativos Java de plataforma cruzada" >}}

{{% blocks/products/pf/feature-page-summary %}}
Java Email API para construir soluções de processamento de correio de plataforma cruzada com a capacidade de gerar, manipular, processar e converter mensagens sem a instalação do Microsoft Outlook<sup>&reg;</sup>. Os desenvolvedores podem aprimorar facilmente os aplicativos para adicionar cabeçalhos personalizados, anexos, validação de endereços de e-mail e conversão entre formatos como EML, MSG, MBOX, OST, PST e MHT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Converter formatos de e-mail para formatos diferentes" %}}

Os desenvolvedores podem facilmente converter formatos de mensagem suportados usando a biblioteca Java. Ele simplesmente carrega o arquivo de origem no modelo de objeto da API e chama o método save com os parâmetros relevantes. por exemplo, para converter EML para MSG, há [MailMessage](/email/java/com.aspose.email/mailmessage) Função de carregamento para obter o arquivo de origem e chamar o método salvar com arquivo de saída e [SaveOptions](/email/java/com.aspose.email/saveoptions) como parâmetros relevantes.

Considerando outro cenário de conversão de Mbox para HTML, o processo é ler o arquivo Mbox usando [MboxrdStorageReader](/email/java/com.aspose.email/mboxrdstoragereader), Percorra cada mensagem e salve-a em um arquivo HTML fornecendo o caminho do arquivo e [MailMessageSaveType](/email/java/com.aspose.email/mailmessagesavetype) como parâmetros no método de salvamento.


{{% blocks/products/pf/feature-page-code h3="Código Java para conversão de EML para MSG" %}}

{{< gist "aspose-com-gists" "9e945d8deb696f51f3b130113f186b01" "convert-eml-to-msg.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Código Java para conversão de Mbox para HTML" %}}

{{< gist "aspose-com-gists" "9e945d8deb696f51f3b130113f186b01" "convert-mbox-to-html.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="eml-to-pdf eml-to-html eml-to-msg emlx-to-msg msg-to-pdf pst-to-eml" >}}