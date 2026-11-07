---
title: "Класс Aspose::BarCode::Generation::Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::Generation::Pdf417Parameters. Параметры PDF417. Содержит параметры PDF417, MacroPDF417, MicroPDF417 и GS1MicroPdf417. MacroPDF417 требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными. MicroPDF417 в режиме Structured Append (тот же, что режим MacroPDF417) требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными в C++."
type: docs
weight: 4000
url: /ru/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


Параметры PDF417. Содержит параметры PDF417, MacroPDF417, MicroPDF417 и GS1MicroPdf417. MacroPDF417 требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными. MicroPDF417 в режиме Structured Append (тот же, что режим MacroPDF417) требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными.

```cpp
class Pdf417Parameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [get_Columns](./get_columns/)() const | Количество столбцов. |
| [get_ECIEncoding](./get_eciencoding/)() const | Идентификаторы расширенной интерпретации канала (Extended Channel Interpretation). Они используются для передачи считывателю штрихкода деталей о используемых ссылках при кодировании данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки наборов символов. |
| [get_EncodeMode](./get_encodemode/)() const | Определяет режим кодирования Pdf417. Значение по умолчанию: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Получает тип символьной системы Pdf417 уровня коррекции ошибок [BarCode](../../aspose.barcode/), варьирующийся от level0 до level8, level0 означает отсутствие информации о коррекции ошибок, level8 означает наилучшую коррекцию, что приводит к более крупному изображению. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во втором положении в режимах 908 и 909, а также может кодировать 910 и 911, что просто указывает, что распознанный MicroPdf417 может интерпретироваться как Code 128. |
| [get_IsLinked](./get_islinked/)() const | Определяет связанные режимы с штрихкодами GS1MicroPdf417, MicroPdf417 и Pdf417. Символика GS1MicroPdf417 кодирует режимы 906, 907, 912, 913, 914, 915 «Linked» UCC/EAN-128. Символика MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [get_MacroCharacters](./get_macrocharacters/)() const | Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Можно использовать только с MicroPdf417 и кодировать режимы 916 и 917 MicroPdf417. Значение по умолчанию: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Имя получателя штрихкода MacroPdf417 (необязательное поле). Имя получателя штрихкода MicroPDF417 (необязательное поле для режима Structured Append). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Контрольная сумма штрихкода MacroPdf417 (необязательное поле). Контрольная сумма штрихкода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT‑16: x^16 + x^12 + x^5 + 1. |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Идентификаторы расширенной интерпретации канала (Extended Channel Interpretation). Применяется к текстовым полям Macro PDF417. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | Идентификатор файла штрихкода MacroPdf417 (обязательное поле). Идентификатор файла штрихкода MicroPDF417 (обязательное поле для режима Structured Append). |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Имя файла штрихкода MacroPdf417 (необязательное поле). Имя файла штрихкода MicroPDF417 (необязательное поле для режима Structured Append). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Размер файла MacroPdf417 (необязательное поле). Размер файла MicroPDF417 (необязательное поле для режима Structured Append). Поле размера файла содержит размер всего исходного файла в байтах. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | Идентификатор сегмента штрихкода MacroPdf417 (обязательное поле), который начинается с 0 и до MacroSegmentsCount - 1. Идентификатор сегмента штрихкода MicroPDF417 (обязательное поле для режима Structured Append). |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Количество сегментов штрихкода MacroPdf417 (необязательное поле). Количество сегментов штрихкода MicroPDF417 (необязательное поле для режима Structured Append). |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Имя отправителя штрихкода MacroPdf417 (необязательное поле). Имя отправителя штрихкода MicroPDF417 (необязательное поле для режима Structured Append). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Используется, чтобы указать кодировщику, добавлять ли терминатор Macro PDF417 (кодовое слово 922) к сегменту. Применяется только для Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Метка времени штрихкода MacroPdf417 (необязательное поле). Метка времени штрихкода MicroPDF417 (необязательное поле для режима Structured Append). |
| [get_Rows](./get_rows/)() const | Количество строк. |
| [get_Truncate](./get_truncate/)() const | Указывает, является ли тип символьной системы Pdf417 у [BarCode](../../aspose.barcode/) усечённым (для экономии места). Также известен как CompactPDF417. В этом режиме правый индикатор строки и правый стоп‑шаблон удаляются. |
| [set_AspectRatio](./set_aspectratio/)(float) | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [set_Columns](./set_columns/)(int32_t) | Количество столбцов. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Идентификаторы расширенной интерпретации канала (Extended Channel Interpretation). Они используются для передачи считывателю штрихкода деталей о используемых ссылках при кодировании данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки наборов символов. |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Определяет режим кодирования Pdf417. Значение по умолчанию: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | Устанавливает тип символьной системы Pdf417 для уровня коррекции ошибок [BarCode](../../aspose.barcode/), диапазон от level0 до level8, level0 означает отсутствие информации о коррекции ошибок, level8 означает лучшую коррекцию, что приводит к более крупному изображению. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во втором положении в режимах 908 и 909, а также может кодировать 910 и 911, что просто указывает, что распознанный MicroPdf417 может интерпретироваться как Code 128. |
| [set_IsLinked](./set_islinked/)(bool) | Определяет связанные режимы с штрихкодами GS1MicroPdf417, MicroPdf417 и Pdf417. Символика GS1MicroPdf417 кодирует режимы 906, 907, 912, 913, 914, 915 «Linked» UCC/EAN-128. Символика MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Можно использовать только с MicroPdf417 и кодировать режимы 916 и 917 MicroPdf417. Значение по умолчанию: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | Имя получателя штрихкода MacroPdf417 (необязательное поле). Имя получателя штрихкода MicroPDF417 (необязательное поле для режима Structured Append). |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | Контрольная сумма штрихкода MacroPdf417 (необязательное поле). Контрольная сумма штрихкода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT‑16: x^16 + x^12 + x^5 + 1. |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Идентификаторы расширенной интерпретации канала (Extended Channel Interpretation). Применяется к текстовым полям Macro PDF417. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | Идентификатор файла штрихкода MacroPdf417 (обязательное поле). Идентификатор файла штрихкода MicroPDF417 (обязательное поле для режима Structured Append). |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | Имя файла штрихкода MacroPdf417 (необязательное поле). Имя файла штрихкода MicroPDF417 (необязательное поле для режима Structured Append). |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | Размер файла MacroPdf417 (необязательное поле). Размер файла MicroPDF417 (необязательное поле для режима Structured Append). Поле размера файла содержит размер всего исходного файла в байтах. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | Идентификатор сегмента штрихкода MacroPdf417 (обязательное поле), который начинается с 0 и до MacroSegmentsCount - 1. Идентификатор сегмента штрихкода MicroPDF417 (обязательное поле для режима Structured Append). |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | Количество сегментов штрихкода MacroPdf417 (необязательное поле). Количество сегментов штрихкода MicroPDF417 (необязательное поле для режима Structured Append). |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | Имя отправителя штрихкода MacroPdf417 (необязательное поле). Имя отправителя штрихкода MicroPDF417 (необязательное поле для режима Structured Append). |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | Используется, чтобы указать кодировщику, добавлять ли терминатор Macro PDF417 (кодовое слово 922) к сегменту. Применяется только для Macro PDF417. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | Метка времени штрихкода MacroPdf417 (необязательное поле). Метка времени штрихкода MicroPDF417 (необязательное поле для режима Structured Append). |
| [set_Rows](./set_rows/)(int32_t) | Количество строк. |
| [set_Truncate](./set_truncate/)(bool) | Указывает, является ли тип символьной системы Pdf417 у [BarCode](../../aspose.barcode/) усечённым (для экономии места). Также известен как CompactPDF417. В этом режиме правый индикатор строки и правый стоп‑шаблон удаляются. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [Pdf417Parameters](./). |
## Примечания


Эти примеры показывают, как кодировать режимы UCC/EAN-128 без связи в GS1MicroPdf417
```cpp
[C#]
//Кодирует режим GS1 UCC/EAN-128 без связи 905 с AI 01 (GTIN)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Кодирует режимы GS1 UCC/EAN-128 без связи 903, 904 с любой AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
