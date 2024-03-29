---
title: Converter OST para ICS via C#
weight: 1700
url: /pt/net/conversion/ost-to-ics/
description: Código de amostra para conversão de OST para ICS C#. Use o código de exemplo da API para arquivos OST em lote para conversão ICS em VB.NET, Asp.NET ou qualquer aplicativo baseado em .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter OST para ICS via C#" h2="Conversão de OST para ICS C# usando API .NET sem precisar de Outlook® ou Thunderbird®." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ICS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OST" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="para .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Como converter OST para ICS usando C #" %}}

 Para converter OST em ICS, usaremos
 [Aspose.Email para .NET](https://products.aspose.com/email/net/)
 API que é uma API de manipulação e conversão de documentos rica em recursos, poderosa e fácil de usar para a plataforma C#. Abrir
 [NuGet](https://www.nuget.org/packages/aspose.email)
 gerenciador de pacotes, procure por Aspose.Email e instale. Você também pode usar o seguinte comando no console do gerenciador de pacotes.

{{% blocks/products/pf/agp/code-block title="Comando do Console do Gerenciador de Pacotes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter OST para ICS via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Os programadores .NET podem facilmente carregar e converter arquivos OST para ICS em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

+  Carregue o arquivo OST com PersonalStorage.FromFile.
+  Chame o método SaveAs com dois parâmetros.
+  Arquivo ICS de saída e FileFormat.Ics como parâmetros.
+  O arquivo ICS será salvo no caminho especificado.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de conversão .NET, verifique se você possui os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

-  Carregue o arquivo OST com PersonalStorage.FromFile.
-  Chame o método SaveAs com dois parâmetros.
-  Arquivo ICS de saída e FileFormat.Ics como parâmetros.
-  O arquivo ICS será salvo no caminho especificado.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de exemplo mostra a conversão de OST para ICS C#" offSpacer="" %}}

```cs
// load the OST file
using (PersonalStorage personalStorage = PersonalStorage.FromFile("sourceFile.ost"))
{
    personalStorage.SaveAs("outputFile.ics", FileFormat.Ics);
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Aplicativo gratuito para converter OST para ICS" sectionDescription="Confira nossas demonstrações ao vivo para [Conversão de OST para ICS](https://products.aspose.app/email/conversion/ost-to-ics) com os seguintes benefícios." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar ou configurar nada." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta carregar seu arquivo OST e clicar no botão \"Converter\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você obterá instantaneamente o link de download para o arquivo ICS resultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 API de e-mail é uma solução de análise de formatos do Microsoft Outlook e Thunderbird. Pode-se facilmente criar, manipular, converter e-mail e formatos de armazenamento, como MSG, EMLX, EML e MHT. O manuseio de anexos de e-mail, personalização de cabeçalhos de mensagens e implementação de diferentes protocolos de rede como POP3, IMAP e SMTP para enviar e receber e-mails é muito mais fácil. É uma API independente e não requer o Microsoft Outlook ou qualquer outra instalação de software.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="OST" readMoreLink="https://docs.fileformat.com/email/ost/" >}}
OST ou arquivos de armazenamento offline representam os dados da caixa de correio do usuário no modo offline na máquina local após o registro no Exchange Server usando o Microsoft Outlook. Ele é criado automaticamente no primeiro uso do Microsoft Outlook após a conectividade com o servidor. Depois que o arquivo é criado, os dados são sincronizados com o servidor de e-mail para que estejam disponíveis off-line também em caso de desconexão do servidor de e-mail. Os arquivos OST podem usar itens de caixa de correio, como e-mails, contatos, informações de calendário, notas, tarefas e outros dados semelhantes. Os usuários podem criar e-mails e outros itens de dados no arquivo OST mesmo na ausência de conexão com o servidor, mas estes não serão sincronizados com o servidor. Uma vez estabelecida a conexão, o arquivo local é sincronizado com o servidor novamente para que tanto o servidor quanto a cópia local estejam no mesmo nível de informação.

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="ics" readMoreLink="https://docs.fileformat.com/email/ics/" >}}
especificação do objeto central de calendário e agendamento da Internet (iCalendar) é um padrão da Internet (RFC 2445) para troca e implantação de eventos de calendário e agendamento. O formato iCalendar é interoperável, garantindo assim a troca de informações de calendário entre os usuários que possuem diferentes aplicativos de e-mail. O iCalendar formata os dados de entrada como MIME (Multipurpose Internet Mail Extensions) e facilita a troca de objetos por meio de diferentes protocolos de transporte. Esses protocolos de transporte podem ser SMTP, HTTP, comunicação assíncrona ponto a ponto e transporte de rede baseado em mídia física. O iCalendar permite que os usuários compartilhem eventos, tarefas dependentes de data/hora e informações de disponibilidade por meio de e-mails para outros usuários que podem responder de volta. Os arquivos iCalendar são armazenados usando sufixos ".ics" ".iCalendar" ou ".ifb" com um tipo MIME de "texto/calendário".

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões suportadas" subTitle="Você também pode converter OST em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-eml/" name="OST TO EML" description="Mensagens de e-mail do Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-emlx/" name="OST TO EMLX" description="Formato Apple EMLX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-html/" name="OST TO HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-mbox/" name="OST TO MBOX" description="Mensagens de correio eletrônico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-mhtml/" name="OST TO MHTML" description="Formato de arquivo da página da Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-msg/" name="OST TO MSG" description="Formato Outlook e Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-oft/" name="OST TO OFT" description="Modelos de e-mail do Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-pst/" name="OST TO PST" description="Arquivos de armazenamento pessoal do Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-vcf/" name="OST TO VCF" description="Formato do cartão virtual" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}