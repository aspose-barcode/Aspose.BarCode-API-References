---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Сохраняет распознанные данные штрихкода, такие как тип SingleDecodeType, `string` codetext, BarCodeRegionParameters region и другие параметры"
type: docs
weight: 110
url: /ru/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

Сохраняет распознанные данные штрихкода, такие как тип SingleDecodeType, `string` codetext, BarCodeRegionParameters region и другие параметры

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## Методы

| Имя | Описание |
| --- | --- |
| [deepClone()](#deepclone) | Создаёт копию класса BarCodeResult. |
| [equals(other)](#equals) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению BarCodeResult. |
| [getCodeBytes()](#getcodebytes) | Получает закодированные байты кода. Значение: байты кода штрихкода |
| [getCodeText(encoding)](#getcodetext) | Получает текст кода с кодировкой. Этот пример показывает, как использовать `getCodeText`: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | Получает тип штрихкода. Значение: информация о типе распознанного штрихкода |
| [getCodeTypeName()](#getcodetypename) | Получает название типа штрихкода. Значение: название типа распознанного штрихкода |
| [getConfidence()](#getconfidence) | Получает уровень уверенности распознавания распознанного штрихкода. Значение: BarCodeConfidence.Strong не имеет подделок или ошибок распознавания |
| [getExtended()](#getextended) | Получает расширенные параметры распознанного штрихкода. Значение: расширенные параметры распознанного штрихкода |
| [getReadingQuality()](#getreadingquality) | Получает качество чтения. Работает для 1D и почтовых штрихкодов. Значение: процент качества чтения |
| [getRegion()](#getregion) | Получает регион штрихкода. Значение: регион распознанного штрихкода |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого BarCodeResult. |

### deepClone() {#deepclone}

Создаёт копию класса BarCodeResult.

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

Возвращает значение, указывающее, равен ли этот экземпляр указанному значению BarCodeResult.

| Параметр | Описание |
| --- | --- |
| другое | Значение BarCodeResult для сравнения с этим экземпляром. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

Получает закодированные байты кода. Значение: байты кода штрихкода

### getCodeText(encoding) {#getcodetext}

Получает текст кода с кодировкой. Этот пример показывает, как использовать `getCodeText`: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| Параметр | Описание |
| --- | --- |
| кодировка | Кодировка для codetext. |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

Получает тип штрихкода. Значение: информация о типе распознанного штрихкода

### getCodeTypeName() {#getcodetypename}

Получает название типа штрихкода. Значение: название типа распознанного штрихкода

### getConfidence() {#getconfidence}

Получает уровень уверенности распознавания распознанного штрихкода. Значение: BarCodeConfidence.Strong не имеет подделок или ошибок распознавания, BarCodeConfidence.Moderate иногда может иметь подделки или некорректный codetext, потому что этот уровень уверенности применяется к штрихкодам с слабой контрольной суммой или без неё, BarCodeConfidence.NONE всегда имеет некорректный codetext и может быть поддельным распознаванием

### getExtended() {#getextended}

Получает расширенные параметры распознанного штрихкода. Значение: расширенные параметры распознанного штрихкода

### getReadingQuality() {#getreadingquality}

Получает качество чтения. Работает для 1D и почтовых штрихкодов. Значение: процент качества чтения

### getRegion() {#getregion}

Получает регион штрихкода. Значение: регион распознанного штрихкода

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого BarCodeResult.

**Returns:** A string that represents this BarCodeResult.
