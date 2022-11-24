---
title: Преобразование OFT в VCF через приложение C++
weight: 3600
url: /ru/cpp/conversion/oft-to-vcf/
description: Пример кода преобразования C++ для документа OFT в формат VCF. Используйте пример кода для пакетного преобразования OFT в VCF в любом приложении C++.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование OFT в VCF на C++" h2="Высокопроизводительное преобразование OFT в VCF с использованием библиотеки электронной почты C++." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="VCF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OFT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для С++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/cpp" installationsDocsLink="https://docs.aspose.com/email/cpp" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/cpp" learnAsLink="https://docs.aspose.com/email/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как конвертировать OFT в VCF с помощью C++" %}}

 Чтобы преобразовать OFT в VCF, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Шаги по преобразованию OFT в VCF через C++" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты на C++ могут легко преобразовать файл OFT в VCF всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

+  Загрузите файл OFT с помощью Aspose.Email для C++.
+  Вызовите метод Сохранить().
+  Передайте путь к выходному файлу с расширением (VCF).
+  Файл VCF будет сохранен по указанному пути.
+  Откройте файл VCF в совместимой программе.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования C++ убедитесь, что выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС со средой выполнения C++ для 32-разрядной версии Windows, 64-разрядной версии Windows и 64-разрядной версии Linux.
-  Aspose.Email для C++ DLL, на которую ссылается ваш проект.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Преобразование OFT в VCF — C++" offSpacer="" %}}

```cs
// Load the OFT.
System::SharedPtr<MailMessage> oft = MailMessage::Load(u"sourceFile.oft");
// Save in VCF
oft->Save(u"convertedFile.vcf", SaveOptions::get_DefaultVcf()); 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Преобразование OFT в VCF Live Demo" sectionDescription="[Конвертировать OFT в VCF](https://products.aspose.app/email/conversion/oft-to-vcf) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости скачивать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл OFT, и он будет мгновенно преобразован в формат VCF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Email API — это решение для парсинга форматов Microsoft Outlook и Thunderbird. Можно легко создавать, манипулировать, конвертировать электронную почту и форматы хранения, такие как MSG, EMLX, EML и MHT. Обработка вложений электронной почты, настройка заголовков сообщений и реализация различных сетевых протоколов, таких как POP3, IMAP и SMTP, для отправки и получения электронных писем стали намного проще. Это автономный API, не требующий установки Microsoft Outlook или любого другого программного обеспечения.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="OFT" readMoreLink="https://docs.fileformat.com/email/oft/" >}}

Файлы с расширением .OFT представляют собой файлы шаблонов сообщений, созданные с помощью Microsoft Outlook. Предварительно отформатированный макет, установленный для шаблонов сообщений, затем используется для отправки электронных писем с общей информацией для экономии времени. Такие файлы можно создать, создав новое электронное письмо, добавив необходимую информацию, а затем используя раскрывающийся список «Сохранить как шаблон Office» (*.oft) в Microsoft Outlook. Пользователи могут открывать файлы OFT, дважды щелкнув по ним, и они откроются в соответствующем приложении в этой конкретной системе.


        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="VCF" readMoreLink="https://docs.fileformat.com/email/vcf/" >}}

VCF (формат виртуальной карты) или vCard — это цифровой формат файла для хранения контактной информации. Формат широко используется для обмена данными между популярными приложениями обмена информацией. Большинство операционных систем, таких как Windows и MacOS, поставляются с приложениями по умолчанию для создания и открытия этих файлов. Один файл VCF может содержать контактную информацию для одного или нескольких контактов. Файл VCF обычно содержит такую информацию, как имя контакта, адрес, номер телефона, адрес электронной почты, день рождения, фотографии и аудио, а также ряд других полей. Благодаря поддержке почтовых клиентов и сервисов при передаче контактов через формат vCard не происходит потери данных. Тип носителя для формата файла VCF — text/vcard.


        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать OFT во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/oft-to-eml/" name="OFT TO EML" description="Сообщения электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/oft-to-emlx/" name="OFT TO EMLX" description="Формат Apple EMLX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/oft-to-html/" name="OFT TO HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/oft-to-ics/" name="OFT TO ICS" description="iCalendar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/oft-to-mbox/" name="OFT TO MBOX" description="Электронные почтовые сообщения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/oft-to-mhtml/" name="OFT TO MHTML" description="Формат архива веб-страницы" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/oft-to-msg/" name="OFT TO MSG" description="Формат Outlook и Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/oft-to-ost/" name="OFT TO OST" description="Файлы автономного хранилища" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/conversion/oft-to-pst/" name="OFT TO PST" description="Файлы личного хранилища Outlook" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}