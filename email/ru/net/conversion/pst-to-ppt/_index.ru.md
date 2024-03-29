---
title: Преобразование PST в PPT через C#
url: /ru/net/conversion/pst-to-ppt/
description: Пример кода для преобразования PST в PPT C#. Используйте пример кода API для пакетного преобразования файлов PST в PPT в VB.NET, Asp.NET или любом приложении на основе .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование PST в PPT через C#" h2="Преобразование PST в PPT без установки Microsoft® Outlook® или Thunderbird®." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="EMAIL" fileiconsmall4="XML" fileiconsmall5="PST" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

Чтобы преобразовать PST в PPT, мы будем использовать <a href="https://products.aspose.com/email/net/">Aspose.Email для .NET</a> API, который представляет собой многофункциональный, мощный и простой в использовании API для обработки и преобразования документов для платформы C#. Открытым <a href="https://www.nuget.org/packages/aspose.email">NuGet</a> менеджер пакетов, поиск <b>Aspose.Email</b> и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.EMAIL

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги по преобразованию PST в PPT через С#" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты .NET могут легко загружать и преобразовывать файлы PST в PPT, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл PST с помощью PersonalStorage.FromFile
1. Вызовите метод Сохранить как
1. Передайте выходной файл PPT и FileFormat.Ppt в качестве параметров
1. Файл PPT будет сохранен по указанному пути


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском исходного кода преобразования .NET убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с .NET Framework, .NET Core и PHP, VBScript, Delphi, C++ через COM Interop.
-  Среда разработки, такая как Microsoft Visual Studio.
-  Aspose.EMAIL для .NET DLL, на которую ссылается ваш проект.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В этом примере кода показано преобразование PST в PPT C#" offSpacer="" %}}

```cs
// load the PST file
using (PersonalStorage personalStorage = PersonalStorage.FromFile("sourceFile.pst"))
{
    personalStorage.SaveAs("outputFile.ppt", FileFormat.Ppt);
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Бесплатное приложение для преобразования PST в PPT" sectionDescription="Проверьте наши живые демонстрации для [Преобразование PST в PPT](https://products.aspose.app/email/conversion/pst-to-ppt) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл PST и нажмите кнопку «Конвертировать»." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего файла PPT." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

Библиотека электронной почты, упрощающая работу с рядом форматов Microsoft Outlook и Mozilla Thunderbird, а также предоставляющая возможность управлять файлами хранилища сообщений. API также позволяет отправлять и получать электронные письма через POP3, IMAP и SMTP или подключаться к Microsoft Exchange Server через WebDav и веб-службы Exchange.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PST" readMoreLink="https://docs.fileformat.com/email/pst/" >}}
Файлы с расширением .PST представляют собой файлы личного хранилища Outlook (также называемые таблицей личного хранилища), в которых хранится разнообразная информация о пользователе. Информация о пользователе хранится в папках разных типов, включая электронные письма, элементы календаря, заметки, контакты и несколько других форматов файлов. Файлы PST используются для архивирования данных электронной почты в автономном режиме, которые впоследствии можно загружать и просматривать в различных приложениях.

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="ppt" readMoreLink="https://docs.fileformat.com/presentation/ppt/" >}}
Файл с расширением PPT представляет собой файл PowerPoint, состоящий из набора слайдов для отображения в виде слайд-шоу. Он указывает формат двоичного файла, используемый Microsoft PowerPoint 97-2003. Файл PPT может содержать несколько различных типов информации, таких как текст, маркированные списки, изображения, мультимедиа и другие встроенные объекты OLE. Начиная с 2007 года Microsoft разработала новый формат файла для PowerPoint, известный как PPTX, который основан на Office OpenXML и отличается от этого двоичного формата файла. Некоторые другие прикладные программы, такие как OpenOffice Impress и Apple Keynote, также могут создавать файлы PPT.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать PST во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/pst-to-eml/" name="PST TO EML" description="Сообщения электронной почты Outlook" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/pst-to-emlx/" name="PST TO EMLX" description="Формат Apple EMLX" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/pst-to-html/" name="PST TO HTML" description="Язык гипертекстовой разметки" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/pst-to-ics/" name="PST TO ICS" description="iCalendar" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/pst-to-mbox/" name="PST TO MBOX" description="Электронные почтовые сообщения" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/pst-to-mhtml/" name="PST TO MHTML" description="Формат архива веб-страницы" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/pst-to-msg/" name="PST TO MSG" description="Формат Outlook и Exchange" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/pst-to-oft/" name="PST TO OFT" description="Шаблоны электронной почты Outlook" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/pst-to-ost/" name="PST TO OST" description="Файлы автономного хранилища" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/pst-to-vcf/" name="PST TO VCF" description="Формат виртуальной карты" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}