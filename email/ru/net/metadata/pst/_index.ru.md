---
title: Просмотр или редактирование метаданных файлов PST через .NET
weight: 3100
url: /ru/net/metadata/pst/
description: Исходный код C# для редактирования или просмотра метаданных формата PST на платформах .NET Framework, .NET Core и Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Извлечение метаданных PST через .NET" h2="Создавайте собственные приложения .NET для добавления, редактирования, удаления или извлечения метаданных из файлов PST с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PST" pfName="Aspose.Email" subTitlepfName="для .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как извлечь метаданные PST с помощью C#" %}}

 Чтобы извлечь метаданные PST, мы будем использовать
 [Aspose.Email для .NET](https://products.aspose.com/email/net/)
 API, который представляет собой многофункциональный, мощный и простой в использовании API метаданных документов для платформы C#. Открытым
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

{{% blocks/products/pf/agp/feature-section-col title="Шаги по извлечению метаданных PST через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Получите тип сообщения при использовании GetProperties, что, в свою очередь, позволяет получить всю информацию о метаданных через простой цикл.

{{% /blocks/products/pf/agp/text %}}

+  Загрузите файл PST через объект MapiMessage
+  Получить тип сообщения для доступа ко всем свойствам
+  Переберите каждое свойство, чтобы получить доступ к его значению

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email для .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core и Xamarin.
-  Среда разработки, такая как Microsoft Visual Studio.
-  Aspose.Email для .NET, указанный в вашем проекте.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Извлечение метаданных PST — C#" offSpacer="" %}}

```cs

// load the message in with MapiMessage.Load
var mail = Aspose.Email.Mapi.MapiMessage.Load("template.pst", new Aspose.Email.PstLoadOptions());
Type type = mail.GetType();
// iterate over all properties to display the values
foreach (var prop in type.GetProperties())
{
    Console.WriteLine("Name: " + prop.Name + " Value: " + prop.GetValue(mail).ToString());
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Об Aspose.Email для .NET API" %}}

 Aspose.Email — это решение для парсинга форматов Microsoft Outlook и Thunderbird. Можно легко создавать, манипулировать, конвертировать электронную почту и форматы хранения, такие как MSG, EMLX, EML и MHT. Обработка вложений электронной почты, настройка заголовков сообщений и реализация различных сетевых протоколов, таких как POP3, IMAP и SMTP, для отправки и получения электронных писем стали намного проще. Это автономный API, не требующий установки Microsoft Outlook или любого другого программного обеспечения.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Извлечение метаданных PST через онлайн-приложение" sectionDescription="Просматривайте и редактируйте метаданные в документах PST с помощью нашего [Живые демонстрации](https://products.aspose.app/email/metadata) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл PST и отредактируйте свойства документа." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Мгновенно получить ссылку для скачивания результирующего файла" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PST" readMoreLink="https://docs.fileformat.com/email/pst/" >}}
Файлы с расширением .PST представляют собой файлы личного хранилища Outlook (также называемые таблицей личного хранилища), в которых хранится разнообразная информация о пользователе. Информация о пользователе хранится в папках разных типов, включая электронные письма, элементы календаря, заметки, контакты и несколько других форматов файлов. Файлы PST используются для архивирования данных электронной почты в автономном режиме, которые впоследствии можно загружать и просматривать в различных приложениях.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы метаданных" subTitle="Используя C#, можно также манипулировать метаданными многих других форматов, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/metadata/eml/" name="EML" description="Сообщения электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/metadata/mbox/" name="MBOX" description="Электронные почтовые сообщения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/metadata/msg/" name="MSG" description="Формат Outlook и Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/metadata/ost/" name="OST" description="Файлы автономного хранилища" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}