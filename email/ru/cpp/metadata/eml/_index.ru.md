---
title: Редактировать или просматривать метаданные документа EML через C++
weight: 3360
url: /ru/cpp/metadata/eml/
description: Пример кода C++ для редактирования или просмотра метаданных файла EML в среде выполнения C++ для 32-разрядной версии Windows, 64-разрядной версии Windows и 64-разрядной версии Linux.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Извлечение метаданных EML через C++" h2="Создавайте собственные приложения C++ для добавления, редактирования, удаления или извлечения метаданных из файлов EML с помощью серверных API." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="EML" pfName="Aspose.Email" subTitlepfName="для С++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Email " subTitlepfName="для С++" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/email/aspose_email-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-email" liveDemosLink="https://products.aspose.app/email/family" docsLink="https://docs.aspose.com/email/cpp" installationsDocsLink="https://docs.aspose.com/email/cpp" nugetLink="https://www.nuget.org/packages/aspose.email" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/email/cpp" learnAsLink="https://docs.aspose.com/email/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как получить метаданные EML с помощью C++" %}}

 Чтобы извлечь метаданные EML, мы будем использовать
 [Aspose.Email для C++](https://products.aspose.com/email/cpp)
 API, который представляет собой многофункциональный, мощный и простой в использовании API извлечения метаданных документов для платформы C++. Вы можете загрузить его последнюю версию напрямую, просто открыв
 [NuGet](https://www.nuget.org/packages/aspose.email)
 менеджер пакетов, поиск
 **Aspose.Email.Cpp**
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Email.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги по извлечению метаданных EML через C++" %}}

{{% blocks/products/pf/agp/text %}}

 Получите тип сообщения при использовании GetProperties, что, в свою очередь, позволяет получить всю информацию о метаданных через простой цикл.

{{% /blocks/products/pf/agp/text %}}

+  Загрузите файл EML через MapiMessage::FromFile
+  Получить коллекцию свойств с помощью get_Properties()
+  Получите соответствующее свойство, используя idx_get

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Email для C++ поддерживается на всех основных платформах и операционных системах. Пожалуйста, убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС со средой выполнения C++ для 32-разрядной версии Windows, 64-разрядной версии Windows и 64-разрядной версии Linux.
-  Aspose.Email для C++ DLL, на которую ссылается ваш проект.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Извлечение метаданных EML — C++" offSpacer="" %}}

```cs

// Load from file
System::SharedPtr<MapiMessage> eml = MapiMessage::FromFile(dataDir + L"message.eml");
   
System::String subject;
   
// Access the MapiPropertyTag.PR_SUBJECT property
System::SharedPtr<MapiProperty> prop = eml->get_Properties()->idx_get(MapiPropertyTag::PR_SUBJECT);
   
// If the property is not found, check the MapiPropertyTag.PR_SUBJECT_W (which is a // Unicode peer of the MapiPropertyTag.PR_SUBJECT)
if (prop == nullptr){
    prop = eml->get_Properties()->idx_get(MapiPropertyTag::PR_SUBJECT_W);
}
   
// Cannot found
if (prop == nullptr){
    System::Console::WriteLine(L"No property found!");
    return;
}
   
// Get the property data as string
subject = prop->GetString();
   
System::Console::WriteLine(System::String(L"Subject:") + subject);
// Read internet code page property
prop = msg->get_Properties()->idx_get(MapiPropertyTag::PR_INTERNET_CPID);
if (prop != nullptr){
    System::Console::WriteLine(System::String(L"CodePage:") + prop->GetLong());
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Об Aspose.Email для C++ API" %}}

 Aspose.Email — это решение для парсинга форматов Microsoft Outlook и Thunderbird. Можно легко создавать, манипулировать, конвертировать электронную почту и форматы хранения, такие как MSG, EMLX, EML и MHT. Обработка вложений электронной почты, настройка заголовков сообщений и реализация различных сетевых протоколов, таких как POP3, IMAP и SMTP, для отправки и получения электронных писем стали намного проще. Это автономный API, не требующий установки Microsoft Outlook или любого другого программного обеспечения.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Извлечение метаданных EML через онлайн-приложение" sectionDescription="Просматривайте и редактируйте метаданные в документах EML с помощью нашего [Живые демонстрации](https://products.aspose.app/email/metadata) со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл EML и отредактируйте свойства документа." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Мгновенно получить ссылку для скачивания результирующего файла" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EML" readMoreLink="https://docs.fileformat.com/email/eml/" >}}
Формат файла EML представляет собой сообщения электронной почты, сохраненные с помощью Outlook и других соответствующих приложений. Почти все клиенты электронной почты поддерживают этот формат файла из-за его соответствия стандарту формата интернет-сообщений RFC-822. Microsoft Outlook — это программное обеспечение по умолчанию для открытия типов сообщений EML. Файлы EML можно использовать для сохранения на диск, а также для отправки получателям с использованием протоколов связи.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы метаданных" subTitle="Используя C++, можно также манипулировать метаданными многих других форматов, включая" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/metadata/mbox/" name="MBOX" description="Электронные почтовые сообщения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/metadata/msg/" name="MSG" description="Формат Outlook и Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/metadata/ost/" name="OST" description="Файлы автономного хранилища" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/email/cpp/metadata/pst/" name="PST" description="Файлы личного хранилища Outlook" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
   
{{< /blocks/products/pf/main-wrap-class >}}