---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

Параметры PDF417. Содержит параметры PDF417, MacroPDF417, MicroPDF417 и GS1MicroPdf417.<br/>            MacroPDF417 требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными.<br/>            MicroPDF417 в режиме Structured Append (тот же, что и режим MacroPDF417) требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными.

Тип Pdf417Parameters раскрывает следующие члены:
## Properties
| Name | Описание |
| :- | :- |
| encode_mode | Определяет режим кодирования Pdf417. <br/>            Значение по умолчанию: Auto. |
| error_level | Получает или задает тип символьной системы Pdf417 уровня коррекции ошибок штрих‑кода<br/>            в диапазоне от level0 до level8, level0 означает отсутствие информации о коррекции ошибок,<br/>            level8 означает лучшую коррекцию, что приводит к более крупному изображению. |
| truncate | Указывает, является ли тип символьной системы Pdf417 штрих‑кода усечённым (для экономии места). <br/>            Также известен как CompactPDF417. В этом режиме удаляются правый индикатор строки и правый стоп‑шаблон. |
| columns | Количество столбцов. |
| rows | Количество строк. |
| aspect_ratio | Соотношение высоты к ширине модуля 2D BarCode. |
| macro_pdf_417_file_id | Идентификатор файла штрих‑кода MacroPdf417 (обязательное поле).<br/>            Идентификатор файла штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append) |
| macro_pdf_417_segment_id | Идентификатор сегмента штрих‑кода MacroPdf417 (обязательное поле), начинается с 0 и до MacroSegmentsCount - 1.<br/>            Идентификатор сегмента штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append) |
| macro_pdf_417_segments_count | Количество сегментов штрих‑кода MacroPdf417 (необязательное поле).<br/>            Количество сегментов штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append) |
| macro_pdf_417_file_name | Имя файла штрих‑кода MacroPdf417 (необязательное поле).<br/>            Имя файла штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append) |
| macro_pdf_417_time_stamp | Метка времени штрих‑кода MacroPdf417 (необязательное поле).<br/>            Метка времени штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append) |
| macro_pdf_417_sender | Имя отправителя штрих‑кода MacroPdf417 (необязательное поле).<br/>            Имя отправителя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append) |
| macro_pdf_417_addressee | Имя получателя штрих‑кода MacroPdf417 (необязательное поле).<br/>            Имя получателя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append) |
| macro_pdf_417_file_size | Размер файла MacroPdf417 (необязательное поле).<br/>            Размер файла MicroPDF417 (необязательное поле для режима Structured Append)<br/>            Поле размера файла содержит размер в байтах всего исходного файла. |
| macro_pdf_417_checksum | Контрольная сумма штрих‑кода MacroPdf417 (необязательное поле).<br/>            Контрольная сумма штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append)<br/>            Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT-16. x^16 + x^12 + x^5 + 1 |
| eci_encoding | Extended Channel Interpretation Identifiers. Он используется для передачи сканеру штрих‑кода деталей<br/>            о используемых ссылках для кодирования данных в символе. Не применяется к текстовым полям Macro PDF417.<br/>            Текущая реализация включает все известные кодировки наборов символов. |
| macro_pdf_417eci_encoding | Extended Channel Interpretation Identifiers. Применяется к текстовым полям Macro PDF417. |
| macro_pdf_417_terminator | Используется, чтобы указать кодировщику, добавлять ли терминатор Macro PDF417 (кодовое слово 922) к сегменту.<br/>            Применяется только для Macro PDF417. |
| is_reader_initialization | Используется для указания считывателю интерпретировать данные, содержащиеся в символе<br/>            как программирование для инициализации считывателя. |
| macro_characters | Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах.<br/>            Может использоваться только с MicroPdf417 и кодирует режимы 916 и 917 MicroPdf417<br/>            Значение по умолчанию: MacroCharacters.None. |
| is_linked | Определяет связанные режимы с штрих‑кодами GS1MicroPdf417, MicroPdf417 и Pdf417<br/>            При использовании символогии GS1MicroPdf417 кодирует режимы 906, 907, 912, 913, 914, 915 «Linked» UCC/EAN-128<br/>            При использовании символогий MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC |
| is_code_128_emulation | Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128<br/>            Может кодировать FNC1 во втором положении в режимах 908 и 909, а также может кодировать 910 и 911, которые просто указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128 |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

