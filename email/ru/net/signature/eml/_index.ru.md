---
title: Файлы eSign EML через .NET
weight: 2050
url: /ru/net/signature/eml/
description: Исходный код C# для документов EML e-Sgin на платформах .NET Framework, .NET Core и Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Форматы eSign EML в C#" h2="Нативная и высокопроизводительная электронная подпись сообщений EML с использованием серверных API-интерфейсов Aspose.Email для .NET без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Email" subTitlepfName="для .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="EML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как подписать EML-файл цифровой подписью с помощью C#" %}}

 Чтобы подписать файл EML электронной подписью, мы будем использовать
 [Aspose.Email для .NET](https://products.aspose.com/email/net/)
 API, который представляет собой многофункциональный, мощный и простой в использовании API цифровой подписи для платформы C#. Открытым
 [NuGet](https://www.nuget.org/packages/aspose.email)
 менеджер пакетов, поиск
 **Aspose.Email**
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги для электронной подписи файлов EML в C#" %}}

{{% blocks/products/pf/agp/text %}}

 Базовая цифровая подпись сообщения с
 [Aspose.Email для .NET](https://products.aspose.com/email/net/)
 API можно реализовать всего несколькими строками кода. Можно подписывать документы обработки электронной почты, добавляя текст, изображение или рисуя профессиональную цифровую подпись к файлам электронной почты, а также сохранять результат в форматах MSG и EML.

{{% /blocks/products/pf/agp/text %}}

+  Загрузите все файлы EML с полным путем.
+  Установите стиль текста, такой как шрифт, размер шрифта, цвет и т. д.
+  Установите текст подписи.
+  Сохраните файл EML, вы получите документ с вставленной подписью.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Наши API поддерживаются на всех основных платформах и операционных системах. Перед выполнением приведенного ниже кода убедитесь, что в вашей системе выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core и Xamarin.
-  Среда разработки, такая как Microsoft Visual Studio
-  Aspose.Email для .NET DLL, на который есть ссылка в вашем проекте. Установите из NuGet, нажав кнопку «Загрузить» выше.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="EML-файлы электронной подписи — C#" offSpacer="" %}}

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

mail.Save(Path.Combine(outputFolderPath, Path.GetFileNameWithoutExtension(inputFilePath) + " Signed.eml"), new EmlSaveOptions(MailMessageSaveType.EmlFormat)); 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Об Aspose.Email для .NET API" %}}

 Aspose.Email — это решение для парсинга форматов Microsoft Outlook и Thunderbird. Можно легко создавать, манипулировать, конвертировать электронную почту и форматы хранения, такие как MSG, EMLX, EML и MHT. Обработка вложений электронной почты, настройка заголовков сообщений и реализация различных сетевых протоколов, таких как POP3, IMAP и SMTP, для отправки и получения электронных писем стали намного проще. Это автономный API, не требующий установки Microsoft Outlook или любого другого программного обеспечения.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Онлайн-демонстрации электронных подписей EML" sectionDescription="Электронная подпись документов EML прямо сейчас, посетив наш [Веб-сайт живых демонстраций](https://products.aspose.app/email/signature). Живая демонстрация имеет следующие преимущества" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости скачивать Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Просто загрузите файл EML." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Он будет мгновенно подписан электронной подписью." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EML" readMoreLink="https://docs.fileformat.com/email/eml/" >}}
Формат файла EML представляет собой сообщения электронной почты, сохраненные с помощью Outlook и других соответствующих приложений. Почти все клиенты электронной почты поддерживают этот формат файла из-за его соответствия стандарту формата интернет-сообщений RFC-822. Microsoft Outlook — это программное обеспечение по умолчанию для открытия типов сообщений EML. Файлы EML можно использовать для сохранения на диск, а также для отправки получателям с использованием протоколов связи.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые файлы для электронных подписей" subTitle="Используя C#, можно также использовать цифровую подпись во многих других форматах, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/signature/mbox/" name="MBOX" description="Электронные почтовые сообщения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/signature/msg/" name="MSG" description="Формат Outlook и Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/signature/ost/" name="OST" description="Файлы автономного хранилища" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/signature/pst/" name="PST" description="Файлы личного хранилища Outlook" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}