---
title: Редактировать или просматривать метаданные файлов MSG через Java
weight: 340
url: /ru/java/metadata/msg/
description: Пример кода Java для редактирования или просмотра метаданных формата MSG в среде выполнения Java для приложений JSP/JSF и настольных приложений.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Извлечение метаданных MSG через Java" h2="Создавайте собственные приложения Java для добавления, редактирования, удаления или извлечения метаданных из файлов MSG с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="MSG" pfName="Aspose.Email" subTitlepfName="для Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/java" installationsDocsLink="https://docs.aspose.com/email/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/java" learnAsLink="https://docs.aspose.com/email/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-email" >}}

{{% blocks/products/pf/agp/content h2="Как извлечь метаданные MSG с помощью Java" %}}

 Чтобы получить метаданные файла MSG, мы будем использовать
 [Aspose.Email для Java](https://products.aspose.com/email/java)
 API, который представляет собой многофункциональный, мощный и простой в использовании API метаданных для платформы Java. Вы можете скачать его последнюю версию прямо с
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-email)
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

{{% blocks/products/pf/agp/feature-section-col title="Шаги по извлечению метаданных MSG через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Получите тип сообщения при использовании GetProperties, что, в свою очередь, позволяет получить всю информацию о метаданных через простой цикл.

{{% /blocks/products/pf/agp/text %}}

+  Загрузите файл MSG, используя MapiMessage.fromFile.
+  Получить коллекцию свойств с помощью getProperties()
+  Получите доступ к соответствующему свойству, такому как Subject, используя get_Item()

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email для Java поддерживается на всех основных платформах и операционных системах. Пожалуйста, убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС со средой выполнения Java для приложений JSP/JSF и настольных приложений.
-  Получите последнюю версию Aspose.Email для Java прямо из
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-email)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Извлечение метаданных MSG — Java" offSpacer="" %}}

```cs

MapiMessage outlookMessageFile = MapiMessage.fromFile(dataDir + "messageMapi.msg");

//Get the MapiProperties collection
MapiPropertyCollection coll = outlookMessageFile.getProperties();

//Access the MapiPropertyTag.PR_SUBJECT property
MapiProperty prop = (MapiProperty) coll.get_Item((Object) MapiPropertyTag.PR_SUBJECT);

//If the MapiProperty is not found, check the MapiProperty.PR_SUBJECT_W
//which is a unicode peer of MapiPropertyTag.PR_SUBJECT
if (prop == null) {
	prop = (MapiProperty) coll.get_Item(MapiPropertyTag.PR_SUBJECT_W);
}

//If it cannot be found
if (prop == null) {
	System.out.println("Mapi property could not be found.");
} else {
	//Get the property data as string
	String strSubject = prop.getString();
	System.out.println("Subject: " + strSubject);
}

//Read internet code page property
prop = (MapiProperty) coll.get_Item(MapiPropertyTag.PR_INTERNET_CPID);
if (prop != null) {
	System.out.println("Code page: " + prop.getLong());
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="О Aspose.Email для Java API" %}}

 Aspose.Email — это решение для парсинга форматов Microsoft Outlook и Thunderbird. Можно легко создавать, манипулировать, конвертировать электронную почту и форматы хранения, такие как MSG, EMLX, EML и MHT. Обработка вложений электронной почты, настройка заголовков сообщений и реализация различных сетевых протоколов, таких как POP3, IMAP и SMTP, для отправки и получения электронных писем стали намного проще. Это автономный API, не требующий установки Microsoft Outlook или любого другого программного обеспечения.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Извлечение метаданных MSG через онлайн-приложение" sectionDescription="Просматривайте и редактируйте метаданные в документах MSG с помощью нашего [Живые демонстрации](https://products.aspose.app/email/metadata) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл MSG и отредактируйте свойства документа." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Мгновенно получить ссылку для скачивания результирующего файла" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MSG" readMoreLink="https://docs.fileformat.com/email/msg/" >}}
MSG — это формат файла, используемый Microsoft Outlook и Exchange для хранения сообщений электронной почты, контактов, встреч или других задач. Такие сообщения могут содержать одно или несколько полей электронной почты с указанием отправителя, получателя, темы, даты и тела сообщения или контактной информации, сведений о встрече и одной или нескольких спецификаций задачи. Свойства, составляющие объект Message, в том числе также являются частью файла MSG. Файл MSG имеет заголовки, основное тело сообщения и гиперссылки в виде простого текста ASCII. Файлы MSG также подходят для программ, которым требуется интерфейс программирования приложений обмена сообщениями Microsoft (MAPI).

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы метаданных" subTitle="Используя Java, можно также манипулировать метаданными многих других форматов, включая" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/metadata/eml/" name="EML" description="Сообщения электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/metadata/mbox/" name="MBOX" description="Электронные почтовые сообщения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/metadata/ost/" name="OST" description="Файлы автономного хранилища" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/java/metadata/pst/" name="PST" description="Файлы личного хранилища Outlook" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}