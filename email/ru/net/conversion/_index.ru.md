---
title: C# Email API для преобразования форматов OutLook и Thunderbird
url: /ru/net/conversion/
description: Преобразование форматов Thunderbird и OutLook EML, EMLX, HTML, MBOX, ICS, MSG, OFT, OLM, OST, PST и VCF с помощью нескольких строк кода C# через библиотеку электронной почты .NET.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование форматов электронной почты Thunderbird и Outlook с помощью C#" h2="Microsoft<sup>&reg;</sup> Преобразование и анализ файлов Outlook и Thunderbird для создания кроссплатформенных приложений .NET" >}}

{{% blocks/products/pf/feature-page-summary %}}
.NET Email API для создания кросс-платформенных решений для обработки почты с возможностью создания, управления, обработки, преобразования и передачи сообщений без установки Microsoft Outlook.<sup>&reg;</sup>. Разработчики могут легко улучшать приложения для таких функций, как добавление, получение или удаление вложений из объекта сообщения, настройка заголовков сообщений путем изменения темы, добавление или удаление получателей и многое другое.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование форматов электронной почты в различные форматы" %}}
Разработчики могут легко преобразовывать форматы электронной почты, интегрируя API, не вникая во внутренние детали базовых спецификаций формата. Процесс преобразования прост: сначала загружается источник с помощью [MailMessage.Load](https://reference.aspose.com/email/net/aspose.email/mailmessage/load#load_2) и вызов [Сохранить метод](https://reference.aspose.com/email/net/aspose.email/mailmessage/save#save_3) имея выходной файл и [SaveOptions.DefaultFormat](https://reference.aspose.com/email/net/aspose.email/saveoptions/) как параметры.
{{% blocks/products/pf/feature-page-code h3="Код С# для преобразования MSG в EML" %}}

{{< gist "aspose-com-gists" "c8c0a43b7094f6f1c61ea8bae48428a5" "msg-to-eml.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Код С# для преобразования MSG в HTML" %}}

{{< gist "aspose-com-gists" "c8c0a43b7094f6f1c61ea8bae48428a5" "msg-to-html.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Код С# для преобразования MSG в MHTML" %}}

{{< gist "aspose-com-gists" "c8c0a43b7094f6f1c61ea8bae48428a5" "msg-to-mhtml.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="eml-to-pdf eml-to-html eml-to-msg emlx-to-msg ics-to-html mbox-to-xps msg-to-pdf oft-to-html olm-to-mbox ost-to-pst pst-to-eml vcf-to-emlx" >}}