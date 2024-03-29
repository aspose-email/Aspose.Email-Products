---
title: Преобразование EMLX в VCF через C#
weight: 1390
url: /ru/net/conversion/emlx-to-vcf/
description: Пример кода для преобразования EMLX в VCF C#. Используйте пример кода API для пакетного преобразования файлов EMLX в VCF в VB.NET, Asp.NET или любом приложении на основе .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование EMLX в VCF через C#" h2="Преобразование EMLX в VCF C# с использованием .NET API без использования Outlook® или Thunderbird®." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="VCF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EMLX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать EMLX в VCF с помощью C#" %}}

 Чтобы преобразовать EMLX в VCF, мы будем использовать
 [Aspose.Email для .NET](https://products.aspose.com/email/net/)
 API, который представляет собой многофункциональный, мощный и простой в использовании API для обработки и преобразования документов для платформы C#. Открытым
 [NuGet](https://www.nuget.org/packages/aspose.email)
 менеджер пакетов, найдите Aspose.Email и установите. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги по преобразованию EMLX в VCF через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты .NET могут легко загружать и преобразовывать файлы EMLX в VCF всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

+  Загрузите файл EMLX с помощью MailMessage.Load.
+  Вызовите метод Сохранить.
+  Передайте путь к выходному файлу с расширением VCF.
+  Файл VCF будет сохранен по указанному пути.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования .NET убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с .NET Framework, .NET Core и PHP, VBScript, Delphi, C++ через COM Interop.
-  Среда разработки, такая как Microsoft Visual Studio.
-  Aspose.Email для .NET DLL, на которую ссылается ваш проект.
-  Включить пространство имен в соответствующий класс.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В этом примере кода показано преобразование EMLX в VCF C#" offSpacer="" %}}

```cs
// load the EMLX file to be converted
var message = MailMessage.Load("My File.emlx");
// save EMLX as a VCF
message.Save("Saved File.vcf", SaveOptions.DefaultVcf); 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Бесплатное приложение для преобразования EMLX в VCF" sectionDescription="Проверьте наши живые демонстрации для [Преобразование EMLX в VCF](https://products.aspose.app/email/conversion/emlx-to-vcf) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл EMLX и нажмите кнопку «Конвертировать»." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего файла VCF." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Email API — это решение для парсинга форматов Microsoft Outlook и Thunderbird. Можно легко создавать, манипулировать, конвертировать электронную почту и форматы хранения, такие как MSG, EMLX, EML и MHT. Обработка вложений электронной почты, настройка заголовков сообщений и реализация различных сетевых протоколов, таких как POP3, IMAP и SMTP, для отправки и получения электронных писем стали намного проще. Это автономный API, не требующий установки Microsoft Outlook или любого другого программного обеспечения.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EMLX" readMoreLink="https://docs.fileformat.com/email/emlx/" >}}
Формат файла EMLX реализован и разработан Apple. Приложение Apple Mail использует формат файла EMLX для экспорта электронных писем. Существуют и другие приложения, которые могут открывать файлы EMLX и преобразовывать их в другие форматы файлов.

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="vcf" readMoreLink="https://docs.fileformat.com/email/vcf/" >}}
VCF (формат виртуальной карты) или vCard — это цифровой формат файла для хранения контактной информации. Формат широко используется для обмена данными между популярными приложениями обмена информацией. Большинство операционных систем, таких как Windows и MacOS, поставляются с приложениями по умолчанию для создания и открытия этих файлов. Один файл VCF может содержать контактную информацию для одного или нескольких контактов. Файл VCF обычно содержит такую информацию, как имя контакта, адрес, номер телефона, адрес электронной почты, день рождения, фотографии и аудио, а также ряд других полей. Благодаря поддержке почтовых клиентов и сервисов при передаче контактов через формат vCard не происходит потери данных. Тип носителя для формата файла VCF — text/vcard.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать EMLX во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/emlx-to-eml/" name="EMLX TO EML" description="Сообщения электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/emlx-to-html/" name="EMLX TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/emlx-to-ics/" name="EMLX TO ICS" description="iCalendar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/emlx-to-mbox/" name="EMLX TO MBOX" description="Электронные почтовые сообщения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/emlx-to-mhtml/" name="EMLX TO MHTML" description="Формат архива веб-страницы" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/emlx-to-msg/" name="EMLX TO MSG" description="Формат Outlook и Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/emlx-to-oft/" name="EMLX TO OFT" description="Шаблоны электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/emlx-to-ost/" name="EMLX TO OST" description="Файлы автономного хранилища" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/conversion/emlx-to-pst/" name="EMLX TO PST" description="Файлы личного хранилища Outlook" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}