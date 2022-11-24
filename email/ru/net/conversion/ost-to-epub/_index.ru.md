---
title: Конвертировать OST в EPUB через C#
url: /ru/net/conversion/ost-to-epub/
description: Пример кода для преобразования OST в EPUB C#. Используйте пример кода API для пакетного преобразования файлов OST в EPUB в VB.NET, Asp.NET или любом приложении на основе .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Конвертировать OST в EPUB через C#" h2="Преобразование OST в EPUB без установки Microsoft® Outlook® или Thunderbird®." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="EPUB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="EMAIL" fileiconsmall4="XML" fileiconsmall5="OST" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="" %}}

Чтобы преобразовать OST в EPUB, мы будем использовать <a href="https://products.aspose.com/email/net">Aspose.Email для .NET</a> API, который представляет собой многофункциональный, мощный и простой в использовании API для обработки и преобразования документов для платформы C#. Открытым <a href="https://www.nuget.org/packages/aspose.email">NuGet</a> менеджер пакетов, поиск <b>Aspose.Email</b> и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.EMAIL

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги по преобразованию OST в EPUB через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты .NET могут легко загружать и конвертировать файлы OST в EPUB, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл OST с помощью PersonalStorage.FromFile
1. Вызовите метод Сохранить как
1. Передайте выходной файл EPUB и FileFormat.Epub в качестве параметров
1. EPUB-файл будет сохранен по указанному пути


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском исходного кода преобразования .NET убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с .NET Framework, .NET Core и PHP, VBScript, Delphi, C++ через COM Interop.
-  Среда разработки, такая как Microsoft Visual Studio.
-  Aspose.EMAIL для .NET DLL, на которую ссылается ваш проект.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Этот пример кода показывает преобразование OST в EPUB C#" offSpacer="" %}}

```cs
// load the OST file
using (PersonalStorage personalStorage = PersonalStorage.FromFile("sourceFile.ost"))
{
    personalStorage.SaveAs("outputFile.epub", FileFormat.Epub);
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Бесплатное приложение для преобразования OST в EPUB" sectionDescription="Проверьте наши живые демонстрации для [Преобразование OST в EPUB](https://products.aspose.app/email/conversion/ost-to-epub) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл OST и нажмите кнопку «Конвертировать»." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего файла EPUB." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

Библиотека электронной почты, упрощающая работу с рядом форматов Microsoft Outlook и Mozilla Thunderbird, а также предоставляющая возможность управлять файлами хранилища сообщений. API также позволяет отправлять и получать электронные письма через POP3, IMAP и SMTP или подключаться к Microsoft Exchange Server через WebDav и веб-службы Exchange.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="OST" readMoreLink="https://docs.fileformat.com/email/ost/" >}}
OST или файлы автономного хранилища представляют данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с использованием Microsoft Outlook. Он автоматически создается при первом использовании Microsoft Outlook при подключении к серверу. После создания файла данные синхронизируются с сервером электронной почты, чтобы они были доступны в автономном режиме, а также в случае отключения от сервера электронной почты. Файлы OST могут использовать элементы почтового ящика, такие как электронные письма, контакты, информацию календаря, заметки, задачи и другие подобные данные. Пользователи могут создавать электронные письма и другие элементы данных в файле OST даже при отсутствии подключения к серверу, но они не будут синхронизированы с сервером. После установления соединения локальный файл снова синхронизируется с сервером, так что и сервер, и локальная копия находятся на одном уровне информации.

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="epub" readMoreLink="https://docs.fileformat.com/ebook/epub/" >}}
Файлы с расширением .EPUB представляют собой формат файлов электронных книг, который представляет собой стандартный формат цифровых публикаций для издателей и потребителей. К настоящему времени этот формат стал настолько распространенным, что поддерживается многими электронными книгами и программными приложениями. Например, в Mac OS предустановленное программное обеспечение Books поддерживает открытие таких файлов. Кроме того, существует множество совместимых программ для смартфонов, планшетов и компьютеров. Стандарты файлов EPUB поддерживаются Международным форумом цифровых публикаций (IDPF). Версия EPUB 3 также одобрена Исследовательской группой книжной индустрии (BISG), ведущей ассоциацией книжной торговли для стандартизированных передовых практик, исследований, информации и мероприятий для упаковки контента.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать OST во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-eml/" name="OST TO EML" description="Сообщения электронной почты Outlook" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-emlx/" name="OST TO EMLX" description="Формат Apple EMLX" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-html/" name="OST TO HTML" description="Язык гипертекстовой разметки" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-ics/" name="OST TO ICS" description="iCalendar" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-mbox/" name="OST TO MBOX" description="Электронные почтовые сообщения" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-mhtml/" name="OST TO MHTML" description="Формат архива веб-страницы" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-msg/" name="OST TO MSG" description="Формат Outlook и Exchange" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-oft/" name="OST TO OFT" description="Шаблоны электронной почты Outlook" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-pst/" name="OST TO PST" description="Файлы личного хранилища Outlook" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/ost-to-vcf/" name="OST TO VCF" description="Формат виртуальной карты" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}