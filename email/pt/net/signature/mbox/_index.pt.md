---
title: Assinar arquivos MBOX via .NET
weight: 240
url: /pt/net/signature/mbox/
description: Código-fonte C# para documentos e-Sgin MBOX em plataformas .NET Framework, .NET Core e Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Formatos eSign MBOX em C #" h2="Assinatura eletrônica de mensagem MBOX nativa e de alto desempenho usando Aspose.Email do lado do servidor para APIs .NET, sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Email" subTitlepfName="para .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="MBOX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="para .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como assinar digitalmente o arquivo MBOX usando C #" %}}

 Para assinar eletronicamente o arquivo MBOX, usaremos
 [Aspose.Email para .NET](https://products.aspose.com/email/net/)
 API que é uma API de assinatura digital rica em recursos, poderosa e fácil de usar para a plataforma C#. Abrir
 [NuGet](https://www.nuget.org/packages/aspose.email)
 gerenciador de pacotes, procure por
 **Aspose.Email**
 e instale. Você também pode usar o seguinte comando no console do gerenciador de pacotes.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para assinatura eletrônica de arquivos MBOX em C#" %}}

{{% blocks/products/pf/agp/text %}}

 Uma assinatura digital de mensagem básica com
 [Aspose.Email para .NET](https://products.aspose.com/email/net/)
 As APIs podem ser feitas com apenas algumas linhas de código. Pode-se assinar documentos de processamento de e-mail adicionando texto, imagem ou desenhar assinatura digital profissional aos arquivos de e-mail, bem como salvar o resultado nos formatos MSG e EML.

{{% /blocks/products/pf/agp/text %}}

+  Carregue todos os arquivos MBOX com o caminho completo.
+  Defina o estilo do texto como fonte, tamanho da fonte, cor etc.
+  Defina o texto da assinatura.
+  Salve o arquivo MBOX, você receberá o documento com a assinatura inserida.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Nossas APIs são suportadas em todas as principais plataformas e sistemas operacionais. Antes de executar o código abaixo, verifique se você possui os seguintes pré-requisitos em seu sistema.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um sistema operacional compatível com plataformas .NET Framework, .NET Core e Xamarin
-  Ambiente de desenvolvimento como o Microsoft Visual Studio
-  Aspose.Email para .NET DLL referenciado em seu projeto - Instale a partir do NuGet usando o botão Download acima

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Arquivos MBOX de assinatura eletrônica - C#" offSpacer="" %}}

```cs
var mail = MapiHelper.GetMapiMessageFromFile(inputFilePath);

var htmlDocument = new Aspose.Html.HTMLDocument(mail.BodyHtml, "");

var element = htmlDocument.CreateElement("Signature");
element.InnerHTML = "Signature Text (Style it with css)";
htmlDocument.Body.AppendChild(element);

var folderPath = "directorypath";
var filePath = folderPath + "Merged.html";
htmlDocument.Save(filePath);
var content = System.IO.File.ReadAllText(filePath);
System.IO.File.Delete(filePath);
Directory.Delete(folderPath);
mail.SetBodyContent(content, BodyContentType.Html);

mail.Save(Path.Combine(outputFolderPath, Path.GetFileNameWithoutExtension(inputFilePath) + " Signed.mbox"), new EmlSaveOptions(MailMessageSaveType.MboxFormat)); 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre Aspose.Email para API .NET" %}}

 Aspose.Email é uma solução de análise de formatos do Microsoft Outlook e Thunderbird. Pode-se facilmente criar, manipular, converter e-mail e formatos de armazenamento, como MSG, EMLX, EML e MHT. O manuseio de anexos de e-mail, personalização de cabeçalhos de mensagens e implementação de diferentes protocolos de rede como POP3, IMAP e SMTP para enviar e receber e-mails é muito mais fácil. É uma API independente e não requer o Microsoft Outlook ou qualquer outra instalação de software.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de assinatura eletrônica MBOX on-line" sectionDescription="Assine documentos MBOX agora mesmo, visitando nosso [Site de Demonstrações ao Vivo](https://products.aspose.app/email/signature). A demonstração ao vivo tem os seguintes benefícios" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar a API Aspose." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Basta carregar seu arquivo MBOX." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ele será assinado eletronicamente instantaneamente." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MBOX" readMoreLink="https://docs.fileformat.com/email/mbox/" >}}
formato de arquivo MBox é um termo genérico que representa um contêiner para coleta de mensagens de correio eletrônico. As mensagens são armazenadas dentro do contêiner junto com seus anexos. As mensagens de uma pasta inteira são salvas em um único arquivo de banco de dados e as novas mensagens são anexadas ao final do arquivo. Numerosos aplicativos e API fornecem suporte para o formato de arquivo MBox, como Apple Mail e Mozilla Thunderbird.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros arquivos suportados para assinaturas eletrônicas" subTitle="Usando C #, também é possível assinar digitalmente muitos outros formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/signature/eml/" name="EML" description="Mensagens de e-mail do Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/signature/msg/" name="MSG" description="Formato Outlook e Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/signature/ost/" name="OST" description="Arquivos de armazenamento off-line" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/signature/pst/" name="PST" description="Arquivos de armazenamento pessoal do Outlook" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}