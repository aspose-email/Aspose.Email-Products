---
title: Просмотр форматов файлов OST через .NET
weight: 3430
url: /ru/net/viewer/ost/
description: Исходный код C# для загрузки, обработки и отображения документов OST на платформах .NET Framework, .NET Core и Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Средство просмотра файлов OST для .NET" h2="Просмотр OST без установки Microsoft Outlook или Thunderbird." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OST" pfName="Aspose.Email" subTitlepfName="для .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OST" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как просмотреть файл OST с помощью C#" %}}

 Для просмотра файла OST мы будем использовать
 [Aspose.Email для .NET](https://products.aspose.com/email/net)
 API, который представляет собой многофункциональный, мощный и простой в использовании API для платформы C#, который можно использовать с любым средством просмотра. Открытым
 [NuGet](https://www.nuget.org/packages/aspose.email)
 менеджер пакетов, поиск
 **Aspose.Email**
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги для просмотра OST через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email позволяет разработчикам легко просматривать файл OST всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1.  Загрузите файл OST в экземпляр MailMessage с помощью метода Load
1.  Вызовите метод MailMessage.Save, чтобы сохранить OST в формате HTML.
1.  Вызовите Process.Start с путем к результирующему HTML для загрузки содержимого OST в браузере по умолчанию.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email для .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core и Xamarin.
-  Среда разработки, такая как Microsoft Visual Studio
-  Aspose.Email для .NET, указанный в вашем проекте

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Код C# для просмотра OST" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// load the OST file in an instance of MailMessage
using (var message = Aspose.Email.MailMessage.Load("template.ost"))
{
    // save OST in HTML format
    message.Save(output, Aspose.Email.SaveOptions.DefaultHtml);
}
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Об Aspose.Email для .NET API" %}}

 Aspose.Email — это решение для парсинга форматов Microsoft Outlook и Thunderbird. Можно легко создавать, манипулировать, конвертировать электронную почту и форматы хранения, такие как MSG, EMLX, EML и MHT. Обработка вложений электронной почты, настройка заголовков сообщений и реализация различных сетевых протоколов, таких как POP3, IMAP и SMTP, для отправки и получения электронных писем стали намного проще. Это автономный API, не требующий установки Microsoft Outlook или любого другого программного обеспечения.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Бесплатное приложение для просмотра OST" sectionDescription="Проверьте наши живые демонстрации, чтобы [Посмотреть саундтрек](https://products.aspose.app/email/viewer/ost) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать или компилировать код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл OST и нажмите кнопку «Просмотреть»." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Скачать OST-файл по ссылке, если требуется" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="OST" readMoreLink="https://docs.fileformat.com/email/ost/" >}}
OST или файлы автономного хранилища представляют данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с использованием Microsoft Outlook. Он автоматически создается при первом использовании Microsoft Outlook при подключении к серверу. После создания файла данные синхронизируются с сервером электронной почты, чтобы они были доступны в автономном режиме, а также в случае отключения от сервера электронной почты. Файлы OST могут использовать элементы почтового ящика, такие как электронные письма, контакты, информацию календаря, заметки, задачи и другие подобные данные. Пользователи могут создавать электронные письма и другие элементы данных в файле OST даже при отсутствии подключения к серверу, но они не будут синхронизированы с сервером. После установления соединения локальный файл снова синхронизируется с сервером, так что и сервер, и локальная копия находятся на одном уровне информации.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы просмотра" subTitle="Используя C#, можно также просматривать многие другие форматы файлов, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/eml/" name="EML" description="Сообщения электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/emlx/" name="EMLX" description="Формат Apple EMLX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/ics/" name="ICS" description="iCalendar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/mbox/" name="MBOX" description="Электронные почтовые сообщения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/msg/" name="MSG" description="Формат Outlook и Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/oft/" name="OFT" description="Шаблоны электронной почты Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/pst/" name="PST" description="Файлы личного хранилища Outlook" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/net/viewer/vcf/" name="VCF" description="Формат виртуальной карты" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}