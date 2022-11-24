---
title: Преобразование EMLX в MHTML через приложение C++
weight: 420
url: /ru/cpp/conversion/emlx-to-mhtml/
description: Пример кода преобразования C++ для документа EMLX в формат MHTML. Используйте пример кода для пакетного преобразования EMLX в MHTML в любом приложении C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование EMLX в MHTML на C++" h2="Высокопроизводительное преобразование EMLX в MHTML с использованием библиотеки электронной почты C++." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EMLX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для С++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/cpp" installationsDocsLink="https://docs.aspose.com/email/cpp" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/cpp" learnAsLink="https://docs.aspose.com/email/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать EMLX в MHTML с помощью C++" %}}

 Чтобы преобразовать EMLX в MHTML, мы будем использовать
 [Aspose.Email для C++](https://products.aspose.com/email/cpp)
 API, который представляет собой многофункциональный, мощный и простой в использовании API для обработки и преобразования документов для платформы C++. Вы можете загрузить его последнюю версию напрямую, просто открыв
 [NuGet](https://www.nuget.org/packages/aspose.email)
 диспетчер пакетов, найдите Aspose.Email.Cpp и установите. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги по преобразованию EMLX в MHTML через C++" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты на C++ могут легко преобразовать файл EMLX в MHTML, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

+  Загрузите файл EMLX с помощью Aspose.Email для C++.
+  Вызовите метод Сохранить().
+  Передайте путь к выходному файлу с расширением (MHTML).
+  Файл MHTML будет сохранен по указанному пути.
+  Откройте файл MHTML в совместимой программе.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования C++ убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС со средой выполнения C++ для 32-разрядной версии Windows, 64-разрядной версии Windows и 64-разрядной версии Linux.
-  Aspose.Email для C++ DLL, на которую ссылается ваш проект.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Преобразование EMLX в MHTML — C++" offSpacer="" %}}

```cs
// Load the EMLX.
System::SharedPtr<MailMessage> emlx = MailMessage::Load(u"sourceFile.emlx");
// Save in MHTML
emlx->Save(u"convertedFile.mhtml", SaveOptions::get_DefaultMhtml()); 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Преобразование EMLX в MHTML Live Demo" sectionDescription="[Конвертировать EMLX в MHTML](https://products.aspose.app/email/conversion/emlx-to-mhtml) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости скачивать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл EMLX, и он будет мгновенно преобразован в MHTML." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Email API — это решение для парсинга форматов Microsoft Outlook и Thunderbird. Можно легко создавать, манипулировать, конвертировать электронную почту и форматы хранения, такие как MSG, EMLX, EML и MHT. Обработка вложений электронной почты, настройка заголовков сообщений и реализация различных сетевых протоколов, таких как POP3, IMAP и SMTP, для отправки и получения электронных писем стали намного проще. Это автономный API, не требующий установки Microsoft Outlook или любого другого программного обеспечения.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EMLX" readMoreLink="https://docs.fileformat.com/email/emlx/" >}}

Формат файла EMLX реализован и разработан Apple. Приложение Apple Mail использует формат файла EMLX для экспорта электронных писем. Существуют и другие приложения, которые могут открывать файлы EMLX и преобразовывать их в другие форматы файлов.


        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}

Файлы с расширением MHTML представляют собой формат архива веб-страницы, который может быть создан рядом различных приложений. Этот формат известен как формат архива, поскольку он сохраняет веб-код HTML и связанные ресурсы в одном файле. Эти ресурсы включают все, что связано с веб-страницей, например изображения, апплеты, анимацию, аудиофайлы и так далее. Файлы MHTML можно открывать в различных приложениях, таких как Internet Explorer и Microsoft Word. Microsoft Windows использует формат файла MHTML для записи сценариев проблем, наблюдаемых при использовании любого приложения в Windows, которое вызывает проблемы. Формат файла MHTML кодирует содержимое страницы аналогично спецификациям, определенным в message/rfc822, который представляет собой спецификации, связанные с электронной почтой в виде обычного текста. Фактические спецификации формата подробно описаны в RFC 2557.


        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать EMLX во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/emlx-to-eml/" name="EMLX TO EML" description="Сообщения электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/emlx-to-html/" name="EMLX TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/emlx-to-ics/" name="EMLX TO ICS" description="iCalendar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/emlx-to-mbox/" name="EMLX TO MBOX" description="Электронные почтовые сообщения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/emlx-to-msg/" name="EMLX TO MSG" description="Формат Outlook и Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/emlx-to-oft/" name="EMLX TO OFT" description="Шаблоны электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/emlx-to-ost/" name="EMLX TO OST" description="Файлы автономного хранилища" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/emlx-to-pst/" name="EMLX TO PST" description="Файлы личного хранилища Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/emlx-to-vcf/" name="EMLX TO VCF" description="Формат виртуальной карты" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}