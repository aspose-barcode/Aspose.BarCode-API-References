---
title: Pdf417Parameters
second_title: Справочник по API Aspose.BarCode для .NET
description: Параметры PDF417. Содержит параметры PDF417 MacroPDF417 и MicroPDF417. MacroPDF417 требует два поляPdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными. MicroPDF417 в режиме структурированного добавления аналогично режиму MacroPDF417 требует наличия двух полейPdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными.
type: docs
weight: 860
url: /ru/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

Параметры PDF417. Содержит параметры PDF417, MacroPDF417 и MicroPDF417. MacroPDF417 требует два поля:Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными. MicroPDF417 в режиме структурированного добавления (аналогично режиму MacroPDF417) требует наличия двух полей:Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными.

```csharp
public class Pdf417Parameters
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio) { get; set; } | Соотношение высоты и ширины модуля 2D BarCode. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation) { get; set; } | Кодовое слово функции для эмуляции Code 128. Применяется только для MicroPDF417. Игнорируется для штрих-кодов PDF417 и MacroPDF417. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding) { get; set; } | Получает или задает кодировку кодового текста. Значение по умолчанию:UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns) { get; set; } | Количество столбцов. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization) { get; set; } | Используется для указания считывателю интерпретировать данные, содержащиеся в символе как программирование для инициализации считывателя. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode) { get; set; } | Тип символики Pdf417 режима уплотнения штрих-кода. Значение по умолчанию:Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding) { get; set; } | Идентификаторы расширенной интерпретации канала. Он используется, чтобы сообщить считывателю штрих-кода подробности об используемых ссылках для кодирования данных в символе. Не применяется для текстовых полей Macro PDF417. Текущая реализация состоит из всех известных кодировок. |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel) { get; set; } | Получает или устанавливает тип символики Pdf417 уровня исправления ошибок штрих-кода в диапазоне от level0 до level8, level0 означает отсутствие информации об исправлении ошибок, level8 означает наилучшее исправление ошибок, что означает большую картинку. |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee) { get; set; } | Имя адресата штрих-кода MacroPdf417 (необязательное поле). Имя получателя штрих-кода MicroPDF417 (необязательное поле для режима структурированного добавления) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum) { get; set; } | Контрольная сумма штрих-кода MacroPdf417 (необязательное поле). Контрольная сумма штрих-кода MicroPDF417 (необязательное поле для режима структурированного добавления) Поле контрольной суммы содержит значение 16-битной (2 байта) контрольной суммы CRC с использованием полинома CCITT-16. х^16 + х^12 + х^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding) { get; set; } | Идентификаторы расширенной интерпретации канала. Применяется для текстовых полей Macro PDF417. |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid) { get; set; } | Идентификатор файла штрих-кода MacroPdf417 (Обязательное поле). Идентификатор файла штрих-кода MicroPDF417 (обязательное поле для режима структурированного добавления) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename) { get; set; } | Имя файла штрих-кода MacroPdf417 (необязательное поле). Имя файла штрих-кода MicroPDF417 (необязательное поле для режима структурированного добавления) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize) { get; set; } | Размер файла MacroPdf417 (необязательное поле). Размер файла MicroPDF417 (необязательное поле для режима структурированного добавления) Поле размера файла содержит размер в байтах всего исходного файла. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid) { get; set; } | Идентификатор сегмента штрих-кода MacroPdf417 (Обязательное поле), которое начинается с 0 до MacroSegmentsCount - 1. Идентификатор сегмента штрих-кода MicroPDF417 (Обязательное поле для структурированного Режим добавления) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount) { get; set; } | Количество сегментов штрих-кода MacroPdf417 (необязательное поле). Количество сегментов штрих-кода MicroPDF417 (необязательное поле для режима структурированного добавления) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender) { get; set; } | Имя отправителя штрих-кода MacroPdf417 (необязательное поле). Имя отправителя штрих-кода MicroPDF417 (необязательное поле для режима структурированного добавления) |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp) { get; set; } | Отметка времени штрих-кода MacroPdf417 (необязательное поле). Временная метка штрих-кода MicroPDF417 (необязательное поле для режима структурированного добавления) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate) { get; set; } | Усекается ли символьный тип штрих-кода Pdf417 (для уменьшения пространства). Также известен как CompactPDF417. Индикатор правого ряда и правый стоп-шаблон в этом режиме удаляются. |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows) { get; set; } | Количество строк. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring)() | Возвращает удобочитаемое строковое представление этого[`Pdf417Parameters`](../pdf417parameters). |

### Смотрите также

* пространство имен [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
