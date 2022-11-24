---
title: Converter VCF para EMLX via aplicativo C++
weight: 290
url: /pt/cpp/conversion/vcf-to-emlx/
description: Exemplo de código de conversão C++ para documento VCF em formato EMLX. Use o código de exemplo para conversão em lote de VCF para EMLX em qualquer aplicativo C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter VCF para EMLX em C++" h2="Conversão de VCF para EMLX de alto desempenho usando a biblioteca C++ Email." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMLX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="VCF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="para C++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/cpp" installationsDocsLink="https://docs.aspose.com/email/cpp" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/cpp" learnAsLink="https://docs.aspose.com/email/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como converter VCF para EMLX usando C++" %}}

 Para converter VCF para EMLX, usaremos
 [Aspose.Email para C++](https://products.aspose.com/email/cpp)
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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter VCF para EMLX via C++" %}}

{{% blocks/products/pf/agp/text %}}

 Os programadores C++ podem facilmente converter arquivos VCF para EMLX em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

+  Carregue o arquivo VCF com Aspose.Email para C++.
+  Chame o método Save().
+  Passe o caminho do arquivo de saída com a extensão de arquivo (EMLX).
+  O arquivo EMLX será salvo no caminho especificado.
+  Abra o arquivo EMLX em um programa compatível.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de conversão C++, verifique se você possui os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um sistema operacional compatível com C++ Runtime Environment para Windows de 32 bits, Windows de 64 bits e Linux de 64 bits.
-  Aspose.Email para C++ DLL referenciado em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Converter VCF para EMLX - C++" offSpacer="" %}}

```cs
// Load the VCF.
System::SharedPtr<MailMessage> vcf = MailMessage::Load(u"sourceFile.vcf");
// Save in EMLX
vcf->Save(u"convertedFile.emlx", SaveOptions::CreateSaveOptions(MailMessageSaveType::get_EmlxFormat())); 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de conversão de VCF para EMLX" sectionDescription="[Converter VCF para EMLX](https://products.aspose.app/email/conversion/vcf-to-emlx) agora mesmo, visitando nosso site de demonstrações ao vivo. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar a API Aspose." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta carregar seu arquivo VCF, ele será convertido instantaneamente para EMLX." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link para download." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 API de e-mail é uma solução de análise de formatos do Microsoft Outlook e Thunderbird. Pode-se facilmente criar, manipular, converter e-mail e formatos de armazenamento, como MSG, EMLX, EML e MHT. O manuseio de anexos de e-mail, personalização de cabeçalhos de mensagens e implementação de diferentes protocolos de rede como POP3, IMAP e SMTP para enviar e receber e-mails é muito mais fácil. É uma API independente e não requer o Microsoft Outlook ou qualquer outra instalação de software.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="VCF" readMoreLink="https://docs.fileformat.com/email/vcf/" >}}

VCF (Virtual Card Format) ou vCard é um formato de arquivo digital para armazenar informações de contato. O formato é amplamente utilizado para intercâmbio de dados entre aplicativos populares de troca de informações. A maioria dos sistemas operacionais, como Windows e MacOS, vem com aplicativos padrão para criar e abrir esses arquivos. Um único arquivo VCF pode conter informações de contato para um ou vários contatos. Um arquivo VCF geralmente contém informações como nome do contato, endereço, número de telefone, e-mail, aniversário, fotografias e áudio, além de vários outros campos. Sendo suportado por clientes e serviços de e-mail, não há perda de dados durante a transferência de contatos usando o formato vCard. O tipo de mídia para o formato de arquivo VCF é text/vcard.


        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EMLX" readMoreLink="https://docs.fileformat.com/email/emlx/" >}}

O formato de arquivo EMLX é implementado e desenvolvido pela Apple. O aplicativo Apple Mail usa o formato de arquivo EMLX para exportar os e-mails. Existem outros aplicativos também que podem abrir os arquivos EMLX e convertê-los em outros formatos de arquivo.


        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões suportadas" subTitle="Você também pode converter VCF em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/vcf-to-eml/" name="VCF TO EML" description="Mensagens de e-mail do Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/vcf-to-html/" name="VCF TO HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/vcf-to-ics/" name="VCF TO ICS" description="iCalendar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/vcf-to-mbox/" name="VCF TO MBOX" description="Mensagens de correio eletrônico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/vcf-to-mhtml/" name="VCF TO MHTML" description="Formato de arquivo da página da Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/vcf-to-msg/" name="VCF TO MSG" description="Formato Outlook e Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/vcf-to-oft/" name="VCF TO OFT" description="Modelos de e-mail do Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/vcf-to-ost/" name="VCF TO OST" description="Arquivos de armazenamento off-line" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/vcf-to-pst/" name="VCF TO PST" description="Arquivos de armazenamento pessoal do Outlook" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}