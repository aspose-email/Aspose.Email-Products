---
title: Converter MSG para PST via Java
weight: 3910
url: /pt/java/conversion/msg-to-pst/
description: Exemplo de código de conversão Java para formato MSG em arquivo PST. Use este código de exemplo para exportar a mensagem para PST em qualquer aplicativo Web ou desktop baseado em Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converter MSG para PST em Java" h2="Conversão nativa de MSG para PST usando a biblioteca Java Email, sem a necessidade de nenhum software adicional." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PST" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MSG" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="para Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/java" installationsDocsLink="https://docs.aspose.com/email/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/java" learnAsLink="https://docs.aspose.com/email/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-email" >}}

{{% blocks/products/pf/agp/content h2="Como converter MSG para PST usando Java" %}}

 Para renderizar MSG para PST, usaremos
 [Aspose.Email para Java](https://products.aspose.com/email/java)
 API que é uma API de conversão rica em recursos, poderosa e fácil de usar para a plataforma Java. Você pode baixar sua versão mais recente diretamente de
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-email)
 e instale-o em seu projeto baseado em Maven adicionando as seguintes configurações ao pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-email</artifactId>
<version>version of aspose-email API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter MSG para PST via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Os programadores Java podem facilmente converter arquivos MSG para PST em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

+  Carregue o arquivo MSG com Aspose.Email para Java MailMessage.load.
+  Chame o método save().
+  Passe o caminho do arquivo de saída com a extensão de arquivo (PST).
+  Abra o arquivo PST em um programa compatível.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de executar o código de conversão Java, verifique se você possui os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows ou um sistema operacional compatível com Java Runtime Environment para aplicativos JSP/JSF e aplicativos de desktop.
-  Obtenha a versão mais recente do Aspose.Email para Java diretamente de
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-email)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Converter MSG para PST - Java" offSpacer="" %}}

```cs
MailMessage message = MailMessage.load("sourceFile.msg");

PersonalStorage pst = PersonalStorage.create("outputFile.pst", FileFormatVersion.Unicode);

FolderInfo inbox = pst.getRootFolder().addSubFolder("Inbox");

inbox.addMessage(MapiMessage.fromMailMessage(message, MapiConversionOptions.getUnicodeFormat()));   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Demonstrações ao vivo de conversão de MSG para PST" sectionDescription="[Converter MSG para PST](https://products.aspose.app/email/conversion/msg-to-pst) agora mesmo, visitando nosso site de demonstrações ao vivo. A demonstração ao vivo tem os seguintes benefícios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Não há necessidade de baixar a API Aspose." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Não há necessidade de escrever nenhum código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta carregar seu arquivo MSG, ele será convertido instantaneamente em PST." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Você receberá o link para download." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 API de e-mail é uma solução de análise de formatos do Microsoft Outlook e Thunderbird. Pode-se facilmente criar, manipular, converter e-mail e formatos de armazenamento, como MSG, EMLX, EML e MHT. O manuseio de anexos de e-mail, personalização de cabeçalhos de mensagens e implementação de diferentes protocolos de rede como POP3, IMAP e SMTP para enviar e receber e-mails é muito mais fácil. É uma API independente e não requer o Microsoft Outlook ou qualquer outra instalação de software.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MSG" readMoreLink="https://docs.fileformat.com/email/msg/" >}}

MSG é um formato de arquivo usado pelo Microsoft Outlook e Exchange para armazenar mensagens de e-mail, contatos, compromissos ou outras tarefas. Essas mensagens podem conter um ou mais campos de e-mail, com remetente, destinatário, assunto, data e corpo da mensagem, ou informações de contato, detalhes de compromissos e uma ou mais especificações de tarefas. As propriedades que constituem o objeto Message, inclusive, também fazem parte do arquivo MSG. O arquivo MSG possui cabeçalhos, corpo da mensagem principal e hiperlinks como texto ASCII simples. Os arquivos MSG também são adequados aos programas que precisam da MAPI (Messaging Applications Programming Interface) da Microsoft.


        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PST" readMoreLink="https://docs.fileformat.com/email/pst/" >}}

Arquivos com extensão .PST representam arquivos de armazenamento pessoal do Outlook (também chamados de tabela de armazenamento pessoal) que armazenam várias informações do usuário. As informações do usuário são armazenadas em pastas de diferentes tipos que incluem e-mails, itens de calendário, notas, contatos e vários outros formatos de arquivo. Os arquivos PST são usados para arquivar dados de e-mail offline que podem ser carregados e visualizados posteriormente em vários aplicativos.


        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões suportadas" subTitle="Você também pode converter MSG em muitos outros formatos de arquivo, incluindo alguns listados abaixo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/msg-to-eml/" name="MSG TO EML" description="Mensagens de e-mail do Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/msg-to-emlx/" name="MSG TO EMLX" description="Formato Apple EMLX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/msg-to-html/" name="MSG TO HTML" description="Linguagem de marcação de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/msg-to-ics/" name="MSG TO ICS" description="iCalendar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/msg-to-mbox/" name="MSG TO MBOX" description="Mensagens de correio eletrônico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/msg-to-mhtml/" name="MSG TO MHTML" description="Formato de arquivo da página da Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/msg-to-oft/" name="MSG TO OFT" description="Modelos de e-mail do Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/msg-to-ost/" name="MSG TO OST" description="Arquivos de armazenamento off-line" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/msg-to-vcf/" name="MSG TO VCF" description="Formato do cartão virtual" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}