---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Сохраняет метаданные MacroPdf417 распознанного штрихкода."
type: docs
weight: 760
url: /ru/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

Сохраняет метаданные MacroPdf417 распознанного штрихкода.

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению Pdf417ExtendedParameters. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Имя получателя Macro PDF417 (необязательно). |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Контрольная сумма Macro PDF417 (необязательно). |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | Получает идентификатор файла штрихкода, доступный только с MacroPdf417. Значение: Идентификатор файла для MacroPdf417 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Имя файла Macro PDF417 (необязательно). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Размер файла Macro PDF417 (необязательно). |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | Получает идентификатор сегмента штрихкода, доступно только с MacroPdf417. Значение: идентификатор сегмента штрихкода. |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Получает количество сегментов штрихкода macro pdf417. Значение по умолчанию — -1. Значение: количество сегментов. |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Имя отправителя Macro PDF417 (необязательно). |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Временная метка Macro PDF417 (необязательно). |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [isCode128Emulation()](#iscode128emulation) | Флаг, указывающий, что штрихкод MicroPdf417 закодирован с помощью кодовых слов эмуляции Code 128 908, 909, 910 или 911. |
| [isLinked()](#islinked) | Флаг, указывающий, что штрихкод должен быть связан с 1D‑штрихкодом. Значение: флаг связи. |
| [isReaderInitialization()](#isreaderinitialization) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого Pdf417ExtendedParameters. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли данный экземпляр указанному значению Pdf417ExtendedParameters.

| Параметр | Описание |
| --- | --- |
| obj | Значение System.Object для сравнения с этим экземпляром. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Имя получателя Macro PDF417 (необязательно).

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Контрольная сумма Macro PDF417 (необязательно).

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

Получает идентификатор файла штрихкода, доступный только с MacroPdf417. Значение: Идентификатор файла для MacroPdf417

### getMacroPdf417FileName() {#getmacropdf417filename}

Имя файла Macro PDF417 (необязательно).

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Размер файла Macro PDF417 (необязательно).

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

Получает идентификатор сегмента штрихкода, доступно только с MacroPdf417. Значение: идентификатор сегмента штрихкода.

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Получает количество сегментов штрихкода macro pdf417. Значение по умолчанию — -1. Значение: количество сегментов.

### getMacroPdf417Sender() {#getmacropdf417sender}

Имя отправителя Macro PDF417 (необязательно).

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя.

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Временная метка Macro PDF417 (необязательно).

**Returns:** Time stamp.

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

Флаг, указывающий, что штрихкод MicroPdf417 закодирован с помощью кодовых слов эмуляции Code 128 908, 909, 910 или 911.

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

Флаг, указывающий, что штрихкод должен быть связан с 1D‑штрихкодом. Значение: флаг связи.

### isReaderInitialization() {#isreaderinitialization}

Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя.

**Returns:** Reader initialization flag

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого Pdf417ExtendedParameters.

**Returns:** A string that represents this Pdf417ExtendedParameters.
