---
title: Mesclar arquivos MHTML via .NET
url: /pt/net/merger/mhtml/
description: Código-fonte C# para combinar documentos MHTML em plataformas .NET Framework, .NET Core e Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Mesclar formatos MHTML em C #" h2="Fusão de mensagens MHTML nativas e de alto desempenho usando Aspose.Email do lado do servidor para APIs .NET, sem o uso de qualquer software como Microsoft ou Open Office, Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Email" subTitlepfName="para .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="MHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="para .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como mesclar arquivo MHTML usando C #" %}}

Para mesclar o arquivo MHTML, usaremos <a href="https://products.aspose.com/email/net/">Aspose.Email para .NET</a> API que é uma API de manipulação de documentos e fusão rica em recursos, poderosa e fácil de usar para a plataforma C#. Abrir <a href="https://www.nuget.org/packages/aspose.email">NuGet</a> gerenciador de pacotes, procure por <b>Aspose.Email</b> e instale. Você também pode usar o seguinte comando no console do gerenciador de pacotes.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para mesclar arquivos MHTML em C#" %}}

{{% blocks/products/pf/agp/text %}}

 Um documento básico mesclando e concatenando com
 [Aspose.Email para .NET](https://products.aspose.com/email/net/)
 As APIs podem ser feitas com apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

1. Carregue todos os arquivos MHTML com o caminho completo.
1. Faça um documento como o arquivo base
1. Chame o método relevante para concatenar e mesclar arquivos um por um.
1. Chame o método Save() e passe o nome do arquivo (caminho completo) e o formato (MHTML) como parâmetro.
1. Agora você pode abrir e usar o arquivo MHTML no Microsoft Office, Adobe PDF ou qualquer outro programa compatível.


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Nossas APIs são suportadas em todas as principais plataformas e sistemas operacionais. Antes de executar o código abaixo, verifique se você possui os seguintes pré-requisitos em seu sistema.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um sistema operacional compatível com plataformas .NET Framework, .NET Core, Windows Azure, Mono ou Xamarin
-  Ambiente de desenvolvimento como o Microsoft Visual Studio
-  Aspose.Email para .NET DLL referenciado em seu projeto - Instale a partir do NuGet usando o botão Download acima

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mesclar arquivos MHTML - C#" offSpacer="" %}}

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

Aspose.Email é uma solução de análise de formatos do Microsoft Outlook e Thunderbird. Pode-se facilmente criar, manipular, converter e-mail e formatos de armazenamento, como MSG, EMLX, EML e MHT. O manuseio de anexos de e-mail, personalização de cabeçalhos de mensagens e implementação de diferentes protocolos de rede como POP3, IMAP e SMTP para enviar e receber e-mails é muito mais fácil. É uma API independente e não requer o Microsoft Outlook ou qualquer outra instalação de software. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo da fusão MHTML online" sectionDescription="Mescle documentos MHTML agora mesmo visitando nosso [Site de Demonstrações ao Vivo](https://products.aspose.app/email/merger). A demonstração ao vivo tem os seguintes benefícios" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar a API Aspose." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Basta carregar seus arquivos MHTML." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ele será mesclado e concatenado instantaneamente." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}
Arquivos com extensão MHTML representam um formato de arquivo de página da web que pode ser criado por vários aplicativos diferentes. O formato é conhecido como formato de arquivo porque salva o código HTML da Web e os recursos associados em um único arquivo. Esses recursos incluem qualquer coisa vinculada à página da Web, como imagens, applets, animações, arquivos de áudio e assim por diante. Os arquivos MHTML podem ser abertos em vários aplicativos, como Internet Explorer e Microsoft Word. O Microsoft Windows usa o formato de arquivo MHTML para registrar cenários de problemas observados durante o uso de qualquer aplicativo no Windows que gere problemas. O formato de arquivo MHTML codifica o conteúdo da página semelhante às especificações definidas em message/rfc822, que são especificações relacionadas a e-mail de texto simples. As especificações reais do formato são detalhadas pela RFC 2557.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}