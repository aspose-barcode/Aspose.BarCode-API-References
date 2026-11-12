---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Основные параметры декодирования BarCode."
type: docs
weight: 150
url: /ru/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

Основные параметры декодирования BarCode. Содержит параметры, влияющие на распознанные данные.

```js
new BarcodeSettings(settings)
```

Конструктор копирования BarcodeSettings

| Параметр | Описание |
| --- | --- |
| настройки | Источник данных |

## Методы

| Имя | Описание |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | Получает параметры декодирования AustraliaPost |
| [getChecksumValidation()](#getchecksumvalidation) | Включить проверку контрольной суммы во время распознавания 1D и почтовых штрихкодов. По умолчанию считается Yes для символогий, которые |
| [getDetectEncoding()](#getdetectencoding) | Флаг, заставляющий движок определять кодировку текста кода для наборов Unicode. Значение по умолчанию — true. |
| [getStripFNC()](#getstripfnc) | Удалять символы FNC1, FNC2, FNC3 из текста кода. Значение по умолчанию — false. |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | Возвращает только типы штрихкодов, явно указанные для распознавания. Когда включено, распознанные штрихкоды других совместимых |
| [setChecksumValidation(value)](#setchecksumvalidation) | Включить проверку контрольной суммы во время распознавания 1D и почтовых штрихкодов. По умолчанию считается Yes для символогий, которые |
| [setDetectEncoding()](#setdetectencoding) | Флаг, заставляющий движок определять кодировку текста кода для наборов Unicode. Значение по умолчанию — true. |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | Возвращает только типы штрихкодов, явно указанные для распознавания. Когда включено, распознанные штрихкоды других совместимых |
| [setStripFNC(value)](#setstripfnc) | Удалять символы FNC1, FNC2, FNC3 из текста кода. Значение по умолчанию — false. |

### getAustraliaPost() {#getaustraliapost}

Получает параметры декодирования AustraliaPost

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

Включить проверку контрольной суммы во время распознавания 1D и почтовых штрихкодов. По умолчанию считается Yes для символогий, которые обязаны содержать контрольную сумму, и No там, где контрольная сумма возможна только. Контрольная сумма никогда не используется: Codabar, PatchCode, Pharmacode, DataLogic2of5. Контрольная сумма возможна: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Контрольная сумма всегда используется: остальные символогии.

**Returns:** Enable checksum validation during recognition for 1D and Postal barcodes.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### getDetectEncoding() {#getdetectencoding}

Флаг, заставляющий движок определять кодировку текста кода для наборов Unicode. Значение по умолчанию — true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### getStripFNC() {#getstripfnc}

Удалять символы FNC1, FNC2, FNC3 из текста кода. Значение по умолчанию — false.

**Returns:** Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### isOnlyRequestedTypes() {#isonlyrequestedtypes}

Возвращает только типы штрихкодов, явно указанные для распознавания. Когда включено, распознанные штрихкоды других совместимых или эквивалентных типов отфильтровываются. Значение по умолчанию — false. Пример: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

Включить проверку контрольной суммы во время распознавания 1D и почтовых штрихкодов. По умолчанию считается Yes для символогий, которые обязаны содержать контрольную сумму, и No там, где контрольная сумма возможна только. Контрольная сумма никогда не используется: Codabar, PatchCode, Pharmacode, DataLogic2of5. Контрольная сумма возможна: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Контрольная сумма всегда используется: остальные символогии.

| Параметр | Описание |
| --- | --- |
| значение | Включить проверку контрольной суммы во время распознавания 1D и почтовых штрихкодов. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### setDetectEncoding() {#setdetectencoding}

Флаг, заставляющий движок определять кодировку текста кода для наборов Unicode. Значение по умолчанию — true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### setOnlyRequestedTypes() {#setonlyrequestedtypes}

Возвращает только типы штрихкодов, явно указанные для распознавания. Когда включено, распознанные штрихкоды других совместимых или эквивалентных типов отфильтровываются. Значение по умолчанию — false. Пример: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

Удалять символы FNC1, FNC2, FNC3 из текста кода. Значение по умолчанию — false.

| Параметр | Описание |
| --- | --- |
| значение | Удалять символы FNC1, FNC2, FNC3 из текста кода. Значение по умолчанию — false. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```
