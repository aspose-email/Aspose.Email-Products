---
title: Преобразование PST в ICS через Java
weight: 1470
url: /ru/java/conversion/pst-to-ics/
description: Пример кода преобразования Java для формата PST в файл ICS. Используйте этот пример кода для экспорта сообщения в ICS в любом веб-приложении или приложении для рабочего стола на основе Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование PST в ICS в Java" h2="Нативное преобразование PST в ICS с использованием библиотеки электронной почты Java без необходимости в каком-либо дополнительном программном обеспечении." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="ICS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PST" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/java" installationsDocsLink="https://docs.aspose.com/email/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/java" learnAsLink="https://docs.aspose.com/email/java" apiReference="" mavenRepoLink="https://releases.aspose.com/java/repo/com/aspose/aspose-email/" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать PST в ICS с помощью Java" %}}

 Чтобы отобразить PST в ICS, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Шаги для преобразования PST в ICS через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты Java могут легко преобразовать файл PST в ICS всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

+  Загрузите файл PST с PersonalStorage.fromFile.
+  Вызовите метод saveAs() с двумя параметрами.
+  Выходной файл ICS и FileFormat.Pst в качестве параметров.
+  Откройте файл ICS в совместимой программе.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования Java убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС со средой выполнения Java для приложений JSP/JSF и настольных приложений.
-  Получите последнюю версию Aspose.Email для Java прямо из
 [Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-email/)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Преобразование PST в ICS — Java" offSpacer="" %}}

```cs
PersonalStorage sFile = PersonalStorage.fromFile("sourceFile.pst");

sFile.saveAs("outputFile.ics", FileFormat.Ics);   

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Преобразование PST в ICS Live Demo" sectionDescription="[Преобразование PST в ICS](https://products.aspose.app/email/conversion/pst-to-ics) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости скачивать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл PST, и он будет мгновенно преобразован в ICS." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Email API — это решение для парсинга форматов Microsoft Outlook и Thunderbird. Можно легко создавать, манипулировать, конвертировать электронную почту и форматы хранения, такие как MSG, EMLX, EML и MHT. Обработка вложений электронной почты, настройка заголовков сообщений и реализация различных сетевых протоколов, таких как POP3, IMAP и SMTP, для отправки и получения электронных писем стали намного проще. Это автономный API, не требующий установки Microsoft Outlook или любого другого программного обеспечения.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PST" readMoreLink="https://docs.fileformat.com/email/pst/" >}}

Файлы с расширением .PST представляют собой файлы личного хранилища Outlook (также называемые таблицей личного хранилища), в которых хранится разнообразная информация о пользователе. Информация о пользователе хранится в папках разных типов, включая электронные письма, элементы календаря, заметки, контакты и несколько других форматов файлов. Файлы PST используются для архивирования данных электронной почты в автономном режиме, которые впоследствии можно загружать и просматривать в различных приложениях.


        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="ICS" readMoreLink="https://docs.fileformat.com/email/ics/" >}}

Спецификация основных объектов календаря и планирования Интернета (iCalendar) — это интернет-стандарт (RFC 2445) для обмена и развертывания событий календаря и планирования. Формат iCalendar является интероперабельным, что обеспечивает обмен информацией календаря между пользователями, использующими различные приложения электронной почты. iCalendar форматирует входные данные как многоцелевые расширения почты Интернета (MIME) и облегчает обмен объектами через различные транспортные протоколы. Эти транспортные протоколы могут быть SMTP, HTTP, двухточечной асинхронной связью и сетевым транспортом на основе физических носителей. iCalendar позволяет пользователям обмениваться событиями, задачами, зависящими от даты/времени, и информацией о занятости по электронной почте другим пользователям, которые могут ответить. Файлы iCalendar хранятся с использованием суффиксов «.ics», «.iCalendar» или «.ifb» с типом MIME «текст/календарь».


        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PST во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/pst-to-eml/" name="PST TO EML" description="Сообщения электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/pst-to-emlx/" name="PST TO EMLX" description="Формат Apple EMLX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/pst-to-html/" name="PST TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/pst-to-mbox/" name="PST TO MBOX" description="Электронные почтовые сообщения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/pst-to-mhtml/" name="PST TO MHTML" description="Формат архива веб-страницы" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/pst-to-msg/" name="PST TO MSG" description="Формат Outlook и Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/pst-to-oft/" name="PST TO OFT" description="Шаблоны электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/pst-to-ost/" name="PST TO OST" description="Файлы автономного хранилища" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/conversion/pst-to-vcf/" name="PST TO VCF" description="Формат виртуальной карты" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}