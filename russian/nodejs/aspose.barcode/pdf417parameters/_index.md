---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Параметры PDF417."
type: docs
weight: 770
url: /ru/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

Параметры PDF417. Содержит параметры PDF417, MacroPDF417, MicroPDF417 и GS1MicroPdf417. MacroPDF417 требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными. MicroPDF417 в режиме Structured Append (тот же, что и режим MacroPDF417) требует два поля: Pdf417MacroFileID и Pdf417MacroSegmentID. Все остальные поля являются необязательными. Эти примеры показывают, как кодировать режимы UCC/EAN-128 non Linked в GS1MicroPdf417

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## Методы

| Имя | Описание |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Соотношение высоты к ширине модуля 2D штрихкода. |
| [getColumns()](#getcolumns) | Количество столбцов. |
| [getECIEncoding()](#geteciencoding) | Идентификаторы расширенной интерпретации каналов. Используется для передачи сканеру штрихкода деталей о используемых ссылках для |
| [getEncodeMode()](#getencodemode) | Определяет режим кодирования Pdf417. Значение по умолчанию: Auto. |
| [getErrorLevel()](#geterrorlevel) | Получает тип символьного набора Pdf417 уровня коррекции ошибок штрих‑кода, варьирующийся от level0 до level8, level0 означает отсутствие коррекции ошибок. |
| [getMacroCharacters()](#getmacrocharacters) | Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с Micro |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Имя получателя штрихкода MacroPdf417 (необязательное поле). Имя получателя штрихкода MicroPDF417 (необязательное поле для Structured A |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Контрольная сумма штрихкода MacroPdf417 (необязательное поле). Контрольная сумма штрихкода MicroPDF417 (необязательное поле для режима Structured Append) |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417. |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | Идентификатор файла штрихкода MacroPdf417 (обязательное поле). Идентификатор файла штрихкода MicroPDF417 (обязательное поле для режима Structured Append) |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Имя файла штрихкода MacroPdf417 (необязательное поле). Имя файла штрихкода MicroPDF417 (необязательное поле для режима Structured Append) |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Размер файла MacroPdf417 (необязательное поле). Размер файла MicroPDF417 (необязательное поле для режима Structured Append). Размер файла |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | Идентификатор сегмента штрихкода MacroPdf417 (обязательное поле), который начинается с 0 и до MacroSegmentsCount - 1. Штрихкод MicroPDF417 |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Количество сегментов штрихкода MacroPdf417 (необязательное поле). Количество сегментов штрихкода MicroPDF417 (необязательное поле для Structured A |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Имя отправителя штрихкода MacroPdf417 (необязательное поле). Имя отправителя штрихкода MicroPDF417 (необязательное поле для Structured Append) |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Используется, чтобы указать кодеру, добавлять ли Terminator Macro PDF417 (codeword 922) к сегменту. Применяется только для Macro PD. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Метка времени штрихкода MacroPdf417 (необязательное поле). Метка времени штрихкода MicroPDF417 (необязательное поле для Structured Append mo |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | Тип символьной системы Pdf417 для режима уплотнения штрихкода. Значение по умолчанию: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | Идентификаторы расширенной интерпретации каналов. Используется для передачи сканеру штрихкода деталей о используемых ссылках для |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Определяет режим кодирования Pdf417. Значение по умолчанию: Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | Получает тип символьного набора Pdf417 уровня коррекции ошибок штрих‑кода, варьирующийся от level0 до level8, level0 означает отсутствие коррекции ошибок. |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | Получает имя получателя макросимвола штрихкода Pdf417. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | Получает контрольную сумму макросимвола штрихкода Pdf417. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417. |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Получает идентификатор файла макросимвола штрихкода Pdf417. Используется для MacroPdf417. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | Получает имя файла макросимвола штрихкода Pdf417. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | Получает размер файла макросимвола штрихкода Pdf417. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | Получает идентификатор сегмента макросимвола штрихкода Pdf417, который начинается с 0 и до MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | Получает количество сегментов макросимвола штрихкода Pdf417. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | Получает имя отправителя макросимвола штрихкода Pdf417. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | Используется, чтобы указать кодеру, добавлять ли Terminator Macro PDF417 (codeword 922) к сегменту. Применяется только для Macro PD. |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | Получает метку времени макросимвола штрихкода Pdf417. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | Определяет, является ли тип символьной системы Pdf417 штрихкода усечённым (для экономии места). |
| [getRows()](#getrows) | Количество строк. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Определяет идентификатор штрихкода режима Structured Append для DotCode. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. |
| [getTruncate()](#gettruncate) | Определяет, является ли тип символьной системы Pdf417 штрихкода усечённым (для экономии места). Также известен как CompactPDF417. Правый ряд indicato |
| [isCode128Emulation()](#iscode128emulation) | Может использоваться только с MicroPdf417 и кодирует режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции режимов 908 и |
| [isLinked()](#islinked) | Определяет связанные режимы с штрих‑кодами GS1MicroPdf417, MicroPdf417 и Pdf417. Символика GS1MicroPdf417 кодирует 906, 907 |
| [isReaderInitialization()](#isreaderinitialization) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя |
| [setAspectRatio()](#setaspectratio) | Соотношение высоты к ширине модуля 2D штрихкода. |
| [setCode128Emulation()](#setcode128emulation) | Может использоваться только с MicroPdf417 и кодирует режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции режимов 908 и |
| [setColumns()](#setcolumns) | Количество столбцов. |
| [setECIEncoding()](#seteciencoding) | Идентификаторы расширенной интерпретации каналов. Используется для передачи сканеру штрихкода деталей о используемых ссылках для |
| [setEncodeMode()](#setencodemode) | Определяет режим кодирования Pdf417. Значение по умолчанию: Auto. |
| [setErrorLevel(value)](#seterrorlevel) | Устанавливает тип символьной системы Pdf417 уровня коррекции ошибок штрих‑кода в диапазоне от level0 до level8, level0 означает отсутствие коррекции ошибок |
| [setLinked()](#setlinked) | Определяет связанные режимы с штрих‑кодами GS1MicroPdf417, MicroPdf417 и Pdf417. Символика GS1MicroPdf417 кодирует 906, 907 |
| [setMacroCharacters()](#setmacrocharacters) | Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Может использоваться только с Micro |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | Имя получателя штрихкода MacroPdf417 (необязательное поле). Имя получателя штрихкода MicroPDF417 (необязательное поле для Structured A |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | Контрольная сумма штрихкода MacroPdf417 (необязательное поле). Контрольная сумма штрихкода MicroPDF417 (необязательное поле для режима Structured Append) |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417. |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | Идентификатор файла штрихкода MacroPdf417 (обязательное поле). Идентификатор файла штрихкода MicroPDF417 (обязательное поле для режима Structured Append) |
| [setMacroPdf417FileName()](#setmacropdf417filename) | Имя файла штрихкода MacroPdf417 (необязательное поле). Имя файла штрихкода MicroPDF417 (необязательное поле для режима Structured Append) |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | Размер файла MacroPdf417 (необязательное поле). Размер файла MicroPDF417 (необязательное поле для режима Structured Append). Размер файла |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | Идентификатор сегмента штрихкода MacroPdf417 (обязательное поле), который начинается с 0 и до MacroSegmentsCount - 1. Штрихкод MicroPDF417 |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | Количество сегментов штрихкода MacroPdf417 (необязательное поле). Количество сегментов штрихкода MicroPDF417 (необязательное поле для Structured A |
| [setMacroPdf417Sender()](#setmacropdf417sender) | Имя отправителя штрихкода MacroPdf417 (необязательное поле). Имя отправителя штрихкода MicroPDF417 (необязательное поле для Structured Append) |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | Используется, чтобы указать кодеру, добавлять ли Terminator Macro PDF417 (codeword 922) к сегменту. Применяется только для Macro PD. |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | Метка времени штрихкода MacroPdf417 (необязательное поле). Метка времени штрихкода MicroPDF417 (необязательное поле для Structured Append mo |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | Тип символьной системы Pdf417 для режима уплотнения штрихкода. Значение по умолчанию: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | Идентификаторы расширенной интерпретации каналов. Используется для передачи сканеру штрихкода деталей о используемых ссылках для |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Определяет режим кодирования Pdf417. Значение по умолчанию: Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Устанавливает тип символьной системы Pdf417 уровня коррекции ошибок штрих‑кода в диапазоне от level0 до level8, level0 означает отсутствие коррекции ошибок |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | Устанавливает имя получателя макро‑штрих‑кода Pdf417. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | Устанавливает контрольную сумму макро‑штрих‑кода Pdf417. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417. |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | Устанавливает идентификатор файла макро‑штрих‑кода Pdf417. Используется для MacroPdf417. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | Устанавливает имя файла макро‑штрих‑кода Pdf417. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | Устанавливает размер файла макро‑штрих‑кода Pdf417. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | Устанавливает идентификатор сегмента макро‑штрих‑кода Pdf417, который начинается с 0 и до MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | Устанавливает количество сегментов макро‑штрих‑кода Pdf417. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | Устанавливает имя отправителя макро‑штрих‑кода Pdf417. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | Используется, чтобы указать кодеру, добавлять ли Terminator Macro PDF417 (codeword 922) к сегменту. Применяется только для Macro PD. |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | Устанавливает временную метку макро‑штрих‑кода Pdf417. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | Определяет, является ли тип символьной системы Pdf417 штрихкода усечённым (для экономии места). |
| [setReaderInitialization(value)](#setreaderinitialization) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя |
| [setRows()](#setrows) | Количество строк. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Определяет идентификатор штрихкода режима Structured Append для DotCode. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. |
| [setTruncate()](#settruncate) | Определяет, является ли тип символьной системы Pdf417 штрихкода усечённым (для экономии места). Также известен как CompactPDF417. Правый ряд indicato |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого Pdf417Parameters. |

### getAspectRatio() {#getaspectratio}

Соотношение высоты к ширине модуля 2D штрихкода.

### getColumns() {#getcolumns}

Количество столбцов.

### getECIEncoding() {#geteciencoding}

Идентификаторы расширенной интерпретации каналов. Они используются для передачи считывателю штрих‑кода сведений о используемых ссылках для кодирования данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки наборов символов.

### getEncodeMode() {#getencodemode}

Определяет режим кодирования Pdf417. Значение по умолчанию: Auto.

### getErrorLevel() {#geterrorlevel}

Получает тип символьной системы Pdf417 уровня коррекции ошибок штрих‑кода в диапазоне от level0 до level8, level0 означает отсутствие информации о коррекции ошибок, level8 означает лучшую коррекцию, что приводит к более крупному изображению.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

Значения макро‑символов 05 и 06 используются для получения более компактного кодирования в специальных режимах. Могут использоваться только с MicroPdf417 и кодируют режимы 916 и 917 MicroPdf417. Значение по умолчанию: MacroCharacters.None. Эти примеры показывают, как кодировать макро‑символы в MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Имя получателя макро‑штрих‑кода MacroPdf417 (необязательное поле). Имя получателя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Контрольная сумма макро‑штрих‑кода MacroPdf417 (необязательное поле). Контрольная сумма штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT‑16: x^16 + x^12 + x^5 + 1.

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417.

### getMacroPdf417FileID() {#getmacropdf417fileid}

Идентификатор файла макро‑штрих‑кода MacroPdf417 (обязательное поле). Идентификатор файла штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

### getMacroPdf417FileName() {#getmacropdf417filename}

Имя файла макро‑штрих‑кода MacroPdf417 (необязательное поле). Имя файла штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Размер файла MacroPdf417 (необязательное поле). Размер файла MicroPDF417 (необязательное поле для режима Structured Append). Поле размера файла содержит размер всего исходного файла в байтах.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

Идентификатор сегмента макро‑штрих‑кода MacroPdf417 (обязательное поле), который начинается с 0 и до MacroSegmentsCount - 1. Идентификатор сегмента штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Количество сегментов макро‑штрих‑кода MacroPdf417 (необязательное поле). Количество сегментов штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

### getMacroPdf417Sender() {#getmacropdf417sender}

Имя отправителя макро‑штрих‑кода MacroPdf417 (необязательное поле). Имя отправителя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Используется для указания кодировщику, следует ли добавлять терминатор Macro PDF417 (кодовое слово 922) к сегменту. Применяется только для Macro PDF417.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Метка времени штрихкода MacroPdf417 (необязательное поле). Метка времени штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

### getPdf417CompactionMode() {#getpdf417compactionmode}

Тип символьной системы Pdf417 для режима уплотнения штрихкода. Значение по умолчанию: Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Идентификаторы расширенной интерпретации каналов (Extended Channel Interpretation Identifiers). Они используются для передачи считывателю штрих‑кода сведений о используемых ссылках для кодирования данных в символе. Текущая реализация состоит из всех известных кодировок наборов символов.

### getPdf417EncodeMode() {#getpdf417encodemode}

Определяет режим кодирования Pdf417. Значение по умолчанию: Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Получает тип символьной системы Pdf417 уровня коррекции ошибок штрих‑кода в диапазоне от level0 до level8, level0 означает отсутствие информации о коррекции ошибок, level8 означает лучшую коррекцию, что приводит к более крупному изображению.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Получает имя получателя макросимвола штрихкода Pdf417.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Получает контрольную сумму макросимвола штрихкода Pdf417.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417.

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Получает идентификатор файла макросимвола штрихкода Pdf417. Используется для MacroPdf417.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Получает имя файла макросимвола штрихкода Pdf417.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Получает размер файла макросимвола штрихкода Pdf417.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Получает идентификатор сегмента макросимвола штрихкода Pdf417, который начинается с 0 и до MacroSegmentsCount - 1.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Получает количество сегментов макросимвола штрихкода Pdf417.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

Получает имя отправителя макросимвола штрихкода Pdf417.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Используется для указания кодировщику, следует ли добавлять терминатор Macro PDF417 (кодовое слово 922) к сегменту. Применяется только для Macro PDF417.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Получает метку времени макросимвола штрихкода Pdf417.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

Определяет, является ли тип символьной системы Pdf417 штрихкода усечённым (для экономии места).

### getRows() {#getrows}

Количество строк.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Определяет ID штрихкода DotCode в режиме структурированного добавления. ID начинается с 1 и должно быть меньше или равно количеству штрихкодов. Значение по умолчанию — -1.

### getTruncate() {#gettruncate}

Указывает, усечён ли тип символьной схемы Pdf417 штрихкода (для экономии места). Также известен как CompactPDF417. В этом режиме удалены правый индикатор строки и правый стоп‑шаблон.

### isCode128Emulation() {#iscode128emulation}

Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции в режимах 908 и 909, а также может кодировать 910 и 911, которые лишь указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128. Эти примеры показывают, как кодировать режимы эмуляции Code 128 с FNC1 во второй позиции и без него. Таким образом MicroPdf417 может быть декодирован как штрихкод Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

Определяет связанные режимы с штрихкодами GS1MicroPdf417, MicroPdf417 и Pdf417. При символьной схеме GS1MicroPdf417 кодирует режимы “Linked” UCC/EAN-128: 906, 907, 912, 913, 914, 915. При символьных схемах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC. Эти примеры показывают, как кодировать режимы "Linked" UCC/EAN-128 в GS1MicroPdf417 и флаг связи (918) в штрихкодах MicroPdf417 и Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

Соотношение высоты к ширине модуля 2D штрихкода.

### setCode128Emulation() {#setcode128emulation}

Можно использовать только с MicroPdf417 и кодировать режимы эмуляции Code 128. Может кодировать FNC1 во второй позиции в режимах 908 и 909, а также может кодировать 910 и 911, которые лишь указывают, что распознанный MicroPdf417 может интерпретироваться как Code 128. Эти примеры показывают, как кодировать режимы эмуляции Code 128 с FNC1 во второй позиции и без него. Таким образом MicroPdf417 может быть декодирован как штрихкод Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

Количество столбцов.

### setECIEncoding() {#seteciencoding}

Идентификаторы расширенной интерпретации каналов. Они используются для передачи считывателю штрих‑кода сведений о используемых ссылках для кодирования данных в символе. Не применяется к текстовым полям Macro PDF417. Текущая реализация включает все известные кодировки наборов символов.

### setEncodeMode() {#setencodemode}

Определяет режим кодирования Pdf417. Значение по умолчанию: Auto.

### setErrorLevel(value) {#seterrorlevel}

Устанавливает уровень коррекции ошибок символьной схемы Pdf417 штрихкода от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению.

| Параметр | Описание |
| --- | --- |
| значение | Уровень коррекции ошибок символьной схемы Pdf417 штрихкода варьируется от level0 до level8; level0 — без коррекции ошибок, level8 — лучшая коррекция, что означает более крупное изображение. |

### setLinked() {#setlinked}

Определяет связанные режимы с штрихкодами GS1MicroPdf417, MicroPdf417 и Pdf417. При символьной схеме GS1MicroPdf417 кодирует режимы “Linked” UCC/EAN-128: 906, 907, 912, 913, 914, 915. При символьных схемах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC. Эти примеры показывают, как кодировать режимы "Linked" UCC/EAN-128 в GS1MicroPdf417 и флаг связи (918) в штрихкодах MicroPdf417 и Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

Значения макро‑символов 05 и 06 используются для получения более компактного кодирования в специальных режимах. Могут использоваться только с MicroPdf417 и кодируют режимы 916 и 917 MicroPdf417. Значение по умолчанию: MacroCharacters.None. Эти примеры показывают, как кодировать макро‑символы в MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

Имя получателя макро‑штрих‑кода MacroPdf417 (необязательное поле). Имя получателя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

### setMacroPdf417Checksum() {#setmacropdf417checksum}

Контрольная сумма макро‑штрих‑кода MacroPdf417 (необязательное поле). Контрольная сумма штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append). Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT‑16: x^16 + x^12 + x^5 + 1.

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417.

### setMacroPdf417FileID() {#setmacropdf417fileid}

Идентификатор файла макро‑штрих‑кода MacroPdf417 (обязательное поле). Идентификатор файла штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

### setMacroPdf417FileName() {#setmacropdf417filename}

Имя файла макро‑штрих‑кода MacroPdf417 (необязательное поле). Имя файла штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

### setMacroPdf417FileSize() {#setmacropdf417filesize}

Размер файла MacroPdf417 (необязательное поле). Размер файла MicroPDF417 (необязательное поле для режима Structured Append). Поле размера файла содержит размер всего исходного файла в байтах.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

Идентификатор сегмента макро‑штрих‑кода MacroPdf417 (обязательное поле), который начинается с 0 и до MacroSegmentsCount - 1. Идентификатор сегмента штрих‑кода MicroPDF417 (обязательное поле для режима Structured Append).

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

Количество сегментов макро‑штрих‑кода MacroPdf417 (необязательное поле). Количество сегментов штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

### setMacroPdf417Sender() {#setmacropdf417sender}

Имя отправителя макро‑штрих‑кода MacroPdf417 (необязательное поле). Имя отправителя штрих‑кода MicroPDF417 (необязательное поле для режима Structured Append).

### setMacroPdf417Terminator() {#setmacropdf417terminator}

Используется для указания кодировщику, следует ли добавлять терминатор Macro PDF417 (кодовое слово 922) к сегменту. Применяется только для Macro PDF417.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

Метка времени штрихкода MacroPdf417 (необязательное поле). Метка времени штрихкода MicroPDF417 (необязательное поле для режима Structured Append)

### setPdf417CompactionMode() {#setpdf417compactionmode}

Тип символьной системы Pdf417 для режима уплотнения штрихкода. Значение по умолчанию: Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Идентификаторы расширенной интерпретации каналов (Extended Channel Interpretation Identifiers). Они используются для передачи считывателю штрих‑кода сведений о используемых ссылках для кодирования данных в символе. Текущая реализация состоит из всех известных кодировок наборов символов.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Определяет режим кодирования Pdf417. Значение по умолчанию: Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Устанавливает уровень коррекции ошибок символьной схемы Pdf417 штрихкода от level0 до level8; level0 означает отсутствие информации о коррекции ошибок, level8 — лучшую коррекцию, что приводит к более крупному изображению.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Устанавливает имя получателя макро‑штрих‑кода Pdf417.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Устанавливает контрольную сумму макро‑штрих‑кода Pdf417.

| Параметр | Описание |
| --- | --- |
| значение | Поле контрольной суммы содержит значение 16‑битной (2‑байтовой) CRC‑контрольной суммы, вычисленной по полиному CCITT-16. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Идентификаторы расширенной интерпретации канала. Применяется к текстовым полям Macro PDF417.

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Устанавливает идентификатор файла макро‑штрих‑кода Pdf417. Используется для MacroPdf417.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Устанавливает имя файла макро‑штрих‑кода Pdf417.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Устанавливает размер файла макро‑штрих‑кода Pdf417.

| Параметр | Описание |
| --- | --- |
| значение | Поле размера файла содержит размер всего исходного файла в байтах. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Устанавливает идентификатор сегмента макро‑штрих‑кода Pdf417, который начинается с 0 и до MacroSegmentsCount - 1.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Устанавливает количество сегментов макро‑штрих‑кода Pdf417.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

Устанавливает имя отправителя макро‑штрих‑кода Pdf417.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Используется для указания кодировщику, следует ли добавлять терминатор Macro PDF417 (кодовое слово 922) к сегменту. Применяется только для Macro PDF417.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Устанавливает временную метку макро‑штрих‑кода Pdf417.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

Определяет, является ли тип символьной системы Pdf417 штрихкода усечённым (для экономии места).

### setReaderInitialization(value) {#setreaderinitialization}

Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя

| Параметр | Описание |
| --- | --- |
| значение |  |

### setRows() {#setrows}

Количество строк.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Определяет ID штрихкода DotCode в режиме структурированного добавления. ID начинается с 1 и должно быть меньше или равно количеству штрихкодов. Значение по умолчанию — -1.

### setTruncate() {#settruncate}

Указывает, усечён ли тип символьной схемы Pdf417 штрихкода (для экономии места). Также известен как CompactPDF417. В этом режиме удалены правый индикатор строки и правый стоп‑шаблон.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого Pdf417Parameters.

**Returns:** A string that represents this Pdf417Parameters.
