---
title: Объединение файлов ICS через .NET
url: /ru/net/merger/ics/
description: Исходный код C# для объединения документов ICS на платформах .NET Framework, .NET Core и Xamarin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Объединение форматов ICS в C#" h2="Встроенное и высокопроизводительное слияние сообщений ICS с использованием серверных API Aspose.Email для .NET без использования какого-либо программного обеспечения, такого как Microsoft или Open Office, Adobe PDF." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.Email" subTitlepfName="для .NET" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="ICS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/net" installationsDocsLink="https://docs.aspose.com/email/net" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/net" learnAsLink="https://docs.aspose.com/email/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как объединить файл ICS с помощью C#" %}}

Чтобы объединить файл ICS, мы будем использовать <a href="https://products.aspose.com/email/net/">Aspose.Email для .NET</a> API, который представляет собой многофункциональный, мощный и простой в использовании API для работы с документами и слияния для платформы C#. Открытым <a href="https://www.nuget.org/packages/aspose.email">NuGet</a> менеджер пакетов, поиск <b>Aspose.Email</b> и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги по слиянию файлов ICS в C#" %}}

{{% blocks/products/pf/agp/text %}}

 Базовый документ сливается и объединяется с
 [Aspose.Email для .NET](https://products.aspose.com/email/net/)
 API можно реализовать всего несколькими строками кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите все файлы ICS с полным путем.
1. Сделайте один документ в качестве базового файла
1. Вызовите соответствующий метод для объединения и объединения файлов один за другим.
1. Вызовите метод Save() и передайте имя файла (полный путь) и формат (ICS) в качестве параметра.
1. Теперь вы можете открыть и использовать файл ICS в Microsoft Office, Adobe PDF или любой другой совместимой программе.


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Наши API поддерживаются на всех основных платформах и операционных системах. Перед выполнением приведенного ниже кода убедитесь, что в вашей системе выполнены следующие предварительные условия.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core, Windows Azure, Mono или Xamarin.
-  Среда разработки, такая как Microsoft Visual Studio
-  Aspose.Email для .NET DLL, на который есть ссылка в вашем проекте. Установите из NuGet, нажав кнопку «Загрузить» выше.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Объединение файлов ICS — C#" offSpacer="" %}}

```cs
string dataDir = RunExamples.GetDataDir_Outlook();
    string dst = dataDir + "Sub.pst";
    totalAdded = 0;
    using (PersonalStorage personalStorage = PersonalStorage.FromFile(dst)){
    // The events subscription is an optional step for the tracking process only.
    personalStorage.StorageProcessed += PstMerge_OnStorageProcessed;
    personalStorage.ItemMoved += PstMerge_OnItemMoved;
    // Merges with the pst files that are located in separate folder.
    personalStorage.MergeWith(Directory.GetFiles(dataDir + @"MergePST\"));
    Console.WriteLine("Total messages added: {0}", totalAdded);
    } 

       

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Email — это решение для парсинга форматов Microsoft Outlook и Thunderbird. Можно легко создавать, манипулировать, конвертировать электронную почту и форматы хранения, такие как MSG, EMLX, EML и MHT. Обработка вложений электронной почты, настройка заголовков сообщений и реализация различных сетевых протоколов, таких как POP3, IMAP и SMTP, для отправки и получения электронных писем стали намного проще. Это автономный API, не требующий установки Microsoft Outlook или любого другого программного обеспечения. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Онлайн-демонстрации слияния ICS" sectionDescription="Объедините документы ICS прямо сейчас, посетив наш [Веб-сайт живых демонстраций](https://products.aspose.app/email/merger). Живая демонстрация имеет следующие преимущества" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости скачивать Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Просто загрузите файлы ICS." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Он будет объединен и объединен мгновенно." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="ICS" readMoreLink="https://docs.fileformat.com/email/ics/" >}}
Спецификация основных объектов календаря и планирования Интернета (iCalendar) — это интернет-стандарт (RFC 2445) для обмена и развертывания событий календаря и планирования. Формат iCalendar является интероперабельным, что обеспечивает обмен информацией календаря между пользователями, использующими различные приложения электронной почты. iCalendar форматирует входные данные как многоцелевые расширения почты Интернета (MIME) и облегчает обмен объектами через различные транспортные протоколы. Эти транспортные протоколы могут быть SMTP, HTTP, двухточечной асинхронной связью и сетевым транспортом на основе физических носителей. iCalendar позволяет пользователям обмениваться событиями, задачами, зависящими от даты/времени, и информацией о занятости по электронной почте другим пользователям, которые могут ответить. Файлы iCalendar хранятся с использованием суффиксов «.ics», «.iCalendar» или «.ifb» с типом MIME «текст/календарь».

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}