---
title: Converta MSG para PDF via C #
url: /pt/net/conversion/msg-to-pdf/
description: Código de exemplo para conversão de MSG para PDF C#. Use o código de exemplo da API para conversão de arquivos MSG em lote para PDF em VB.NET, Asp.NET ou qualquer aplicativo baseado em .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converta MSG para PDF via C #" h2="Converta MSG para PDF sem precisar do Microsoft® Outlook® ou Thunderbird® instalado." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="EMAIL" fileiconsmall4="XML" fileiconsmall5="MSG" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="para .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

Para converter MSG em PDF, usaremos <a href="https://products.aspose.com/email/net/">Aspose.Email para .NET</a> API que é uma API de manipulação e conversão de documentos rica em recursos, poderosa e fácil de usar para a plataforma C#. Abrir <a href="https://www.nuget.org/packages/aspose.email">NuGet</a> gerenciador de pacotes, procure por <b>Aspose.Email</b> e instale. Você também pode usar o seguinte comando no console do gerenciador de pacotes.

{{% blocks/products/pf/agp/code-block title="Comando do Console do Gerenciador de Pacotes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.EMAIL

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter MSG em PDF via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Os programadores .NET podem facilmente carregar e converter arquivos MSG para PDF em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregar arquivo MSG de origem usando MailMessage.Load
1. Salvar MSG como MHTML em MemoryStream usando o método MailMessage.Save
1. Carregar MHTML do MemoryStream com o construtor Aspose.Words.Document
1. Chame o método Document.Save ao especificar PdfSaveOptions


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código-fonte de conversão .NET, verifique se você possui os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um SO compatível com .NET Framework, .NET Core e PHP, VBScript, Delphi, C++ via COM Interop.
-  Ambiente de desenvolvimento como o Microsoft Visual Studio.
-  Aspose.EMAIL para .NET DLL referenciado em seu projeto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de exemplo mostra a conversão de MSG para PDF C#" offSpacer="" %}}

```cs
string dataDir = RunExamples.GetDataDir_KnowledgeBase();
MailMessage mailMsg = MailMessage.Load(dataDir + "message.msg");
MemoryStream ms = new MemoryStream();
mailMsg.Save(ms, Aspose.Email.SaveOptions.DefaultMhtml);

// create an instance of LoadOptions and set the LoadFormat to Mhtml
var loadOptions = new Aspose.Words.Loading.LoadOptions();
loadOptions.LoadFormat = LoadFormat.Mhtml;

// create an instance of Document and load the MTHML from MemoryStream
var document = new Aspose.Words.Document(ms, loadOptions);

// create an instance of HtmlSaveOptions and set the SaveFormat to Html
var saveOptions = new Aspose.Words.Saving.PdfSaveOptions();
document.Save(dataDir + "SaveEmailAsPDF_out.pdf", saveOptions);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Aplicativo gratuito para converter MSG para PDF" sectionDescription="Confira nossas demonstrações ao vivo para [Conversão de MSG para PDF](https://products.aspose.app/email/conversion/msg-to-pdf) com os seguintes benefícios." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta carregar seu arquivo MSG e clicar no botão \"Converter\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você obterá instantaneamente o link de download para o arquivo PDF resultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

Uma biblioteca de e-mail que facilita o trabalho com vários formatos do Microsoft Outlook e Mozilla Thunderbird, além de fornecer a capacidade de gerenciar arquivos de armazenamento de mensagens. A API também permite enviar e receber e-mails via POP3, IMAP e SMTP ou conectar-se ao Microsoft Exchange Server via WebDav e Exchange Web Services.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MSG" readMoreLink="https://docs.fileformat.com/email/msg/" >}}
MSG é um formato de arquivo usado pelo Microsoft Outlook e Exchange para armazenar mensagens de e-mail, contatos, compromissos ou outras tarefas. Essas mensagens podem conter um ou mais campos de e-mail, com remetente, destinatário, assunto, data e corpo da mensagem, ou informações de contato, detalhes de compromissos e uma ou mais especificações de tarefas. As propriedades que constituem o objeto Message, inclusive, também fazem parte do arquivo MSG. O arquivo MSG possui cabeçalhos, corpo da mensagem principal e hiperlinks como texto ASCII simples. Os arquivos MSG também são adequados aos programas que precisam da MAPI (Messaging Applications Programming Interface) da Microsoft.

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) é um tipo de documento criado pela Adobe na década de 1990. O objetivo desse formato de arquivo era introduzir um padrão para representação de documentos e outros materiais de referência em um formato independente do software aplicativo, hardware e sistema operacional. Os arquivos PDF podem ser abertos no Adobe Acrobat Reader/Writer, bem como na maioria dos navegadores modernos como Chrome, Safari, Firefox por meio de extensões/plug-ins. A maioria dos pacotes de software disponíveis comercialmente também oferece conversão de seus documentos para o formato de arquivo PDF sem a necessidade de qualquer componente de software adicional. Assim, o formato de arquivo PDF tem capacidade total para conter informações como texto, imagens, hiperlinks, campos de formulário, mídia avançada, assinaturas digitais, anexos, metadados, recursos geoespaciais e objetos 3D que podem se tornar parte do documento de origem.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões suportadas" subTitle="Você também pode converter MSG em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/msg-to-eml/" name="MSG TO EML" description="Mensagens de e-mail do Outlook" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/msg-to-emlx/" name="MSG TO EMLX" description="Formato Apple EMLX" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/msg-to-html/" name="MSG TO HTML" description="Linguagem de marcação de hipertexto" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/msg-to-ics/" name="MSG TO ICS" description="iCalendar" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/msg-to-mbox/" name="MSG TO MBOX" description="Mensagens de correio eletrônico" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/msg-to-mhtml/" name="MSG TO MHTML" description="Formato de arquivo da página da Web" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/msg-to-oft/" name="MSG TO OFT" description="Modelos de e-mail do Outlook" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/msg-to-ost/" name="MSG TO OST" description="Arquivos de armazenamento off-line" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/msg-to-pst/" name="MSG TO PST" description="Arquivos de armazenamento pessoal do Outlook" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/msg-to-vcf/" name="MSG TO VCF" description="Formato do cartão virtual" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}