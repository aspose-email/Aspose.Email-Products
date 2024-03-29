---
title: Преобразование EMLX в OST через Java
weight: 3390
url: /ru/java/conversion/emlx-to-ost/
description: Пример кода преобразования Java для формата EMLX в файл OST. Используйте этот пример кода для экспорта сообщения в OST в любом веб-приложении или приложении для рабочего стола на основе Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование EMLX в OST в Java" h2="Нативное преобразование EMLX в OST с использованием библиотеки электронной почты Java без необходимости в каком-либо дополнительном программном обеспечении." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="OST" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EMLX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/java" installationsDocsLink="https://docs.aspose.com/email/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/java" learnAsLink="https://docs.aspose.com/email/java" apiReference="" mavenRepoLink="https://releases.aspose.com/java/repo/com/aspose/aspose-email/" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать EMLX в OST с помощью Java" %}}

 Чтобы преобразовать EMLX в OST, мы будем использовать
 [Aspose.Email для Java](https://products.aspose.com/email/java/)
 API, который представляет собой многофункциональный, мощный и простой в использовании API преобразования для платформы Java. Вы можете скачать его последнюю версию прямо с
 [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-email/)
 и установите его в своем проекте на основе Maven, добавив следующие конфигурации в файл pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Шаги для преобразования EMLX в OST через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты Java могут легко преобразовать файл EMLX в OST всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

+  Загрузите файл EMLX с помощью Aspose.Email для Java MailMessage.load.
+  Вызовите метод save().
+  Передайте путь к выходному файлу с расширением (OST).
+  Откройте файл OST в совместимой программе.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования Java убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС со средой выполнения Java для приложений JSP/JSF и настольных приложений.
-  Получите последнюю версию Aspose.Email для Java прямо из
 [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-email/)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Преобразование EMLX в OST — Java" offSpacer="" %}}

```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx");
// save EMLX as a OST
message.save("Saved File.ost", SaveOptions.DefaultOst);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Преобразование EMLX в OST Живые демонстрации" sectionDescription="[Конвертировать EMLX в OST](https://products.aspose.app/email/conversion/emlx-to-ost) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости скачивать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл EMLX, и он будет мгновенно преобразован в OST." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Email API — это решение для парсинга форматов Microsoft Outlook и Thunderbird. Можно легко создавать, манипулировать, конвертировать электронную почту и форматы хранения, такие как MSG, EMLX, EML и MHT. Обработка вложений электронной почты, настройка заголовков сообщений и реализация различных сетевых протоколов, таких как POP3, IMAP и SMTP, для отправки и получения электронных писем стали намного проще. Это автономный API, не требующий установки Microsoft Outlook или любого другого программного обеспечения.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EMLX" readMoreLink="https://docs.fileformat.com/email/emlx/" >}}

Формат файла EMLX реализован и разработан Apple. Приложение Apple Mail использует формат файла EMLX для экспорта электронных писем. Существуют и другие приложения, которые могут открывать файлы EMLX и преобразовывать их в другие форматы файлов.


        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="OST" readMoreLink="https://docs.fileformat.com/email/ost/" >}}

OST или файлы автономного хранилища представляют данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с использованием Microsoft Outlook. Он автоматически создается при первом использовании Microsoft Outlook при подключении к серверу. После создания файла данные синхронизируются с сервером электронной почты, чтобы они были доступны в автономном режиме, а также в случае отключения от сервера электронной почты. Файлы OST могут использовать элементы почтового ящика, такие как электронные письма, контакты, информацию календаря, заметки, задачи и другие подобные данные. Пользователи могут создавать электронные письма и другие элементы данных в файле OST даже при отсутствии подключения к серверу, но они не будут синхронизированы с сервером. После установления соединения локальный файл снова синхронизируется с сервером, так что и сервер, и локальная копия находятся на одном уровне информации.


        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать EMLX во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/emlx-to-eml/" name="EMLX TO EML" description="Сообщения электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/emlx-to-html/" name="EMLX TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/emlx-to-ics/" name="EMLX TO ICS" description="iCalendar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/emlx-to-mbox/" name="EMLX TO MBOX" description="Электронные почтовые сообщения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/emlx-to-mhtml/" name="EMLX TO MHTML" description="Формат архива веб-страницы" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/emlx-to-msg/" name="EMLX TO MSG" description="Формат Outlook и Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/emlx-to-oft/" name="EMLX TO OFT" description="Шаблоны электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/emlx-to-pst/" name="EMLX TO PST" description="Файлы личного хранилища Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/emlx-to-vcf/" name="EMLX TO VCF" description="Формат виртуальной карты" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}