---
title: API электронной почты C++ для преобразования форматов Thunderbird и OutLook
url: /ru/cpp/conversion/
description: Примеры кода C++ для форматов Thunderbird и OutLook EML EMLX MBOX ICS MSG HTML OFT OLM OST Преобразование PST и VCF через библиотеку электронной почты.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование форматов Thunderbird и Outlook через C++" h2="Microsoft<sup>&reg;</sup> Анализ и преобразование файлов электронной почты и архивов сообщений Outlook и Thunderbird для создания приложений C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
Используйте API электронной почты C++ для анализа форматов, включая MSG, EML, EMLX и MHT, не зная деталей спецификации формата для создания решений для обработки почты. Кроме того, разработчики могут управлять сообщениями MIME, форматами Outlook, создавать и использовать шаблоны повторения iCalendar (RFC 2445) и многое другое.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Сохранение форматов электронной почты в разных форматах" %}}

Процесс преобразования прост для большинства форматов Outlook и Thunderbird. Обсуждая несколько случаев здесь, **EML в MHTML** and **MSG в HTML** с информацией заголовка и пользовательским часовым поясом. В первом случае загрузите нужный файл [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message)::Загрузить и вызвать метод сохранения с требуемым расширением и [SaveOptions](https://reference.aspose.com/email/cpp/class/aspose.email.save_options). А для второго случая мы установим пользовательский часовой пояс и будем использовать [HtmlSaveOptions](https://reference.aspose.com/email/cpp/class/aspose.email.html_save_options) для установки информации заголовка.


{{% blocks/products/pf/feature-page-code h3="Код C++ для преобразования EML в MHTML" %}}

{{< gist "aspose-com-gists" "fe1d255cb80694067eacaca6eeb6dac9" "convert-eml-to-mhtml.cpp" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Код C++ для преобразования MSG в HTML" %}}

{{< gist "aspose-com-gists" "fe1d255cb80694067eacaca6eeb6dac9" "convert-msg-to-html.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="eml-to-pdf eml-to-html eml-to-msg emlx-to-msg msg-to-pdf pst-to-eml" >}}