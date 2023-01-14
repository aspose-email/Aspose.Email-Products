---
title: API электронной почты Java для преобразования форматов Thunderbird и OutLook
url: /ru/java/conversion/
description: Примеры кода Java для преобразования форматов Thunderbird и OutLook EML EMLX MBOX ICS MSG HTML OFT OLM OST PST и VCF через библиотеку электронной почты.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование форматов электронной почты Thunderbird и Outlook через Java" h2="Microsoft<sup>&reg;</sup> Преобразование и анализ файлов Outlook и Thunderbird для создания кроссплатформенных Java-приложений" >}}

{{% blocks/products/pf/feature-page-summary %}}
Java Email API для создания кросс-платформенных решений для обработки почты, позволяющих генерировать, манипулировать, обрабатывать и преобразовывать сообщения без установки Microsoft Outlook.<sup>&reg;</sup>Разработчики могут легко улучшать приложения для добавления пользовательских заголовков, вложений, проверки адресов электронной почты и преобразования между такими форматами, как EML, MSG, MBOX, OST, PST и MHT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование форматов электронной почты в другие форматы" %}}

Разработчики могут легко конвертировать поддерживаемые форматы сообщений с помощью библиотеки Java. Он просто загружает исходный файл в объектную модель API и вызывает метод сохранения с соответствующими параметрами. например, для преобразования EML в MSG существует [MailMessage](/email/java/com.aspose.email/mailmessage) Функция загрузки для получения исходного файла и вызова метода сохранения с выходным файлом и [SaveOptions](/email/java/com.aspose.email/saveoptions) как релевантные параметры.

Рассматривая другой сценарий преобразования Mbox в HTML, процесс заключается в чтении файла Mbox с помощью [MboxrdStorageReader](/email/java/com.aspose.email/mboxrdstoragereader), Переберите каждое сообщение и сохраните его в файле HTML, указав путь к файлу и [MailMessageSaveType](/email/java/com.aspose.email/mailmessagesavetype) в качестве параметров в метод сохранения.


{{% blocks/products/pf/feature-page-code h3="Код Java для преобразования EML в MSG" %}}

{{< gist "aspose-com-gists" "9e945d8deb696f51f3b130113f186b01" "convert-eml-to-msg.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Код Java для преобразования Mbox в HTML" %}}

{{< gist "aspose-com-gists" "9e945d8deb696f51f3b130113f186b01" "convert-mbox-to-html.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="eml-to-pdf eml-to-html eml-to-msg emlx-to-msg msg-to-pdf pst-to-eml" >}}