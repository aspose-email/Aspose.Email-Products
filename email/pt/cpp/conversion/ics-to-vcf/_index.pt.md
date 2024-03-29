---
title: Converter ICS para VCF via aplicativo C++
weight: 3180
url: /pt/cpp/conversion/ics-to-vcf/
description: Exemplo de código de conversão C++ para documento ICS em formato VCF. Use o código de exemplo para conversão de ICS em VCF em lote em qualquer aplicativo C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter ICS para VCF em C++" h2="Conversão de ICS para VCF de alto desempenho usando a biblioteca C++ Email." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="VCF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ICS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="para C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/cpp" installationsDocsLink="https://docs.aspose.com/email/cpp" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/cpp" learnAsLink="https://docs.aspose.com/email/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como converter ICS para VCF usando C++" %}}

 Para converter ICS em VCF, usaremos
 [Aspose.Email para C++](https://products.aspose.com/email/cpp/)
 API que é uma API de manipulação e conversão de documentos rica em recursos, poderosa e fácil de usar para a plataforma C++. Você pode baixar sua versão mais recente diretamente, basta abrir
 [NuGet](https://www.nuget.org/packages/aspose.email)
 gerenciador de pacotes, procure por Aspose.Email.Cpp e instale. Você também pode usar o seguinte comando no console do gerenciador de pacotes.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter ICS em VCF via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Os programadores C++ podem facilmente converter arquivos ICS em VCF em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

+  Carregue o arquivo ICS com Aspose.Email para C++.
+  Chame o método Save().
+  Passe o caminho do arquivo de saída com a extensão de arquivo (VCF).
+  O arquivo VCF será salvo no caminho especificado.
+  Abra o arquivo VCF em um programa compatível.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de conversão C++, verifique se você possui os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.
-  Aspose.Email para C++ DLL referenciado em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Converter ICS para VCF - C++" offSpacer="" %}}

```cs
// Load the ICS.
System::SharedPtr<MailMessage> ics = MailMessage::Load(u"sourceFile.ics");
// Save in VCF
ics->Save(u"convertedFile.vcf", SaveOptions::get_DefaultVcf()); 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de conversão de ICS para VCF" sectionDescription="[Converter ICS para VCF](https://products.aspose.app/email/conversion/ics-to-vcf) agora mesmo, visitando nosso site de demonstrações ao vivo. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar a API Aspose." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta carregar seu arquivo ICS, ele será convertido instantaneamente em VCF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link para download." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 API de e-mail é uma solução de análise de formatos do Microsoft Outlook e Thunderbird. Pode-se facilmente criar, manipular, converter e-mail e formatos de armazenamento, como MSG, EMLX, EML e MHT. O manuseio de anexos de e-mail, personalização de cabeçalhos de mensagens e implementação de diferentes protocolos de rede como POP3, IMAP e SMTP para enviar e receber e-mails é muito mais fácil. É uma API independente e não requer o Microsoft Outlook ou qualquer outra instalação de software.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="ICS" readMoreLink="https://docs.fileformat.com/email/ics/" >}}

especificação do objeto central de calendário e agendamento da Internet (iCalendar) é um padrão da Internet (RFC 2445) para troca e implantação de eventos de calendário e agendamento. O formato iCalendar é interoperável, garantindo assim a troca de informações de calendário entre os usuários que possuem diferentes aplicativos de e-mail. O iCalendar formata os dados de entrada como MIME (Multipurpose Internet Mail Extensions) e facilita a troca de objetos por meio de diferentes protocolos de transporte. Esses protocolos de transporte podem ser SMTP, HTTP, comunicação assíncrona ponto a ponto e transporte de rede baseado em mídia física. O iCalendar permite que os usuários compartilhem eventos, tarefas dependentes de data/hora e informações de disponibilidade por meio de e-mails para outros usuários que podem responder de volta. Os arquivos iCalendar são armazenados usando sufixos ".ics" ".iCalendar" ou ".ifb" com um tipo MIME de "texto/calendário".


        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="VCF" readMoreLink="https://docs.fileformat.com/email/vcf/" >}}

VCF (Virtual Card Format) ou vCard é um formato de arquivo digital para armazenar informações de contato. O formato é amplamente utilizado para intercâmbio de dados entre aplicativos populares de troca de informações. A maioria dos sistemas operacionais, como Windows e MacOS, vem com aplicativos padrão para criar e abrir esses arquivos. Um único arquivo VCF pode conter informações de contato para um ou vários contatos. Um arquivo VCF geralmente contém informações como nome do contato, endereço, número de telefone, e-mail, aniversário, fotografias e áudio, além de vários outros campos. Sendo suportado por clientes e serviços de e-mail, não há perda de dados durante a transferência de contatos usando o formato vCard. O tipo de mídia para o formato de arquivo VCF é text/vcard.


        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões suportadas" subTitle="Você também pode converter ICS em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/ics-to-eml/" name="ICS TO EML" description="Mensagens de e-mail do Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/ics-to-emlx/" name="ICS TO EMLX" description="Formato Apple EMLX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/ics-to-html/" name="ICS TO HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/ics-to-mbox/" name="ICS TO MBOX" description="Mensagens de correio eletrônico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/ics-to-mhtml/" name="ICS TO MHTML" description="Formato de arquivo da página da Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/ics-to-msg/" name="ICS TO MSG" description="Formato Outlook e Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/ics-to-oft/" name="ICS TO OFT" description="Modelos de e-mail do Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/ics-to-ost/" name="ICS TO OST" description="Arquivos de armazenamento off-line" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/ics-to-pst/" name="ICS TO PST" description="Arquivos de armazenamento pessoal do Outlook" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}