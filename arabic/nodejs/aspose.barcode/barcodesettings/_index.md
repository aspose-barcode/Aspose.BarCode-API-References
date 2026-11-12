---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "معلمات فك ترميز BarCode الرئيسية."
type: docs
weight: 150
url: /ar/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

معلمات فك ترميز الباركود الرئيسية. تحتوي على معلمات تؤثر على البيانات المعترف بها.

```js
new BarcodeSettings(settings)
```

منشئ النسخ BarcodeSettings

| معامل | الوصف |
| --- | --- |
| الإعدادات | مصدر البيانات |

## طرق

| اسم | الوصف |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | يحصل على معلمات فك ترميز AustraliaPost |
| [getChecksumValidation()](#getchecksumvalidation) | تمكين التحقق من المجموع الاختباري أثناء التعرف على الباركود أحادي الأبعاد والبريد. يُعامل الافتراضي على أنه نعم للأنماط التي |
| [getDetectEncoding()](#getdetectencoding) | العلم الذي يجبر المحرك على اكتشاف ترميز نص الرمز لمجموعات Unicode. القيمة الافتراضية هي true. |
| [getStripFNC()](#getstripfnc) | إزالة أحرف FNC1 وFNC2 وFNC3 من نص الرمز. القيمة الافتراضية هي false. |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | إرجاع فقط أنواع الباركود المحددة صراحةً للتعرف. عند التفعيل، يتم تجاهل الباركود المعترف به من الأنواع المتوافقة الأخرى |
| [setChecksumValidation(value)](#setchecksumvalidation) | تمكين التحقق من المجموع الاختباري أثناء التعرف على الباركود أحادي الأبعاد والبريد. يُعامل الافتراضي على أنه نعم للأنماط التي |
| [setDetectEncoding()](#setdetectencoding) | العلم الذي يجبر المحرك على اكتشاف ترميز نص الرمز لمجموعات Unicode. القيمة الافتراضية هي true. |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | إرجاع فقط أنواع الباركود المحددة صراحةً للتعرف. عند التفعيل، يتم تجاهل الباركود المعترف به من الأنواع المتوافقة الأخرى |
| [setStripFNC(value)](#setstripfnc) | إزالة أحرف FNC1 وFNC2 وFNC3 من نص الرمز. القيمة الافتراضية هي false. |

### getAustraliaPost() {#getaustraliapost}

يحصل على معلمات فك ترميز AustraliaPost

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

تمكين التحقق من المجموع الاختباري أثناء التعرف على الباركود أحادي الأبعاد والبريد. يُعامل الافتراضي على أنه نعم للأنماط التي يجب أن تحتوي على المجموع الاختباري، وعلى أنه لا حيث يكون المجموع الاختباري ممكنًا فقط. المجموع الاختباري غير مستخدم أبداً: Codabar, PatchCode, Pharmacode, DataLogic2of5. المجموع الاختباري ممكن: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. المجموع الاختباري مستخدم دائماً: باقي الأنماط.

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

العلم الذي يجبر المحرك على اكتشاف ترميز نص الرمز لمجموعات Unicode. القيمة الافتراضية هي true.

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

إزالة أحرف FNC1 وFNC2 وFNC3 من نص الرمز. القيمة الافتراضية هي false.

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

إرجاع فقط أنواع الباركود المحددة صراحةً للتعرف. عند التفعيل، يتم تصفية الباركود المعترف به من الأنواع المتوافقة أو المكافئة. القيمة الافتراضية هي false. مثال: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

تمكين التحقق من المجموع الاختباري أثناء التعرف على الباركود أحادي الأبعاد والبريد. يُعامل الافتراضي على أنه نعم للأنماط التي يجب أن تحتوي على المجموع الاختباري، وعلى أنه لا حيث يكون المجموع الاختباري ممكنًا فقط. المجموع الاختباري غير مستخدم أبداً: Codabar, PatchCode, Pharmacode, DataLogic2of5. المجموع الاختباري ممكن: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. المجموع الاختباري مستخدم دائماً: باقي الأنماط.

| معامل | الوصف |
| --- | --- |
| القيمة | تمكين التحقق من المجموع الاختباري أثناء التعرف على الباركود أحادي الأبعاد والبريد. |

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

العلم الذي يجبر المحرك على اكتشاف ترميز نص الرمز لمجموعات Unicode. القيمة الافتراضية هي true.

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

إرجاع فقط أنواع الباركود المحددة صراحةً للتعرف. عند التفعيل، يتم تصفية الباركود المعترف به من الأنواع المتوافقة أو المكافئة. القيمة الافتراضية هي false. مثال: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

إزالة أحرف FNC1 وFNC2 وFNC3 من نص الرمز. القيمة الافتراضية هي false.

| معامل | الوصف |
| --- | --- |
| القيمة | إزالة أحرف FNC1 وFNC2 وFNC3 من نص الرمز. القيمة الافتراضية هي false. |

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
