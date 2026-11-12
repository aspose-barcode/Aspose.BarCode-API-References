---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يخزن بيانات الباركود المعترف بها مثل النوع SingleDecodeType، `string` codetext، BarCodeRegionParameters region وغيرها من المعاملات"
type: docs
weight: 110
url: /ar/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

يخزن بيانات الباركود المعترف بها مثل النوع SingleDecodeType، `string` codetext، BarCodeRegionParameters region وغيرها من المعاملات

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

## طرق

| اسم | الوصف |
| --- | --- |
| [deepClone()](#deepclone) | ينشئ نسخة من الفئة BarCodeResult. |
| [equals(other)](#equals) | يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة BarCodeResult المحددة. |
| [getCodeBytes()](#getcodebytes) | يحصل على بايتات الكود المشفرة القيمة: بايتات الكود للباركود |
| [getCodeText(encoding)](#getcodetext) | يحصل على نص الكود مع الترميز. يوضح هذا المثال كيفية استخدام `getCodeText`: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | يحصل على نوع الباركود القيمة: معلومات النوع للباركود المعترف به |
| [getCodeTypeName()](#getcodetypename) | يحصل على اسم نوع الباركود القيمة: اسم النوع للباركود المعترف به |
| [getConfidence()](#getconfidence) | يحصل على مستوى ثقة التعرف للباركود المعترف به القيمة: BarCodeConfidence.Strong لا يحتوي على مزيفات أو أخطاء في التعرف |
| [getExtended()](#getextended) | يحصل على المعاملات الموسعة للباركود المعترف به القيمة: المعاملات الموسعة للباركود المعترف به |
| [getReadingQuality()](#getreadingquality) | يحصل على جودة القراءة. يعمل مع باركودات 1D والبريدية. القيمة: نسبة جودة القراءة |
| [getRegion()](#getregion) | يحصل على منطقة الباركود القيمة: منطقة الباركود المعترف به |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [toString()](#tostring) | يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا BarCodeResult. |

### deepClone() {#deepclone}

ينشئ نسخة من الفئة BarCodeResult.

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة BarCodeResult المحددة.

| معامل | الوصف |
| --- | --- |
| أخرى | قيمة BarCodeResult للمقارنة مع هذه الحالة. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

يحصل على بايتات الكود المشفرة القيمة: بايتات الكود للباركود

### getCodeText(encoding) {#getcodetext}

يحصل على نص الكود مع الترميز. يوضح هذا المثال كيفية استخدام `getCodeText`: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| معامل | الوصف |
| --- | --- |
| الترميز | الترميز للنص المشفر. |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

يحصل على نوع الباركود القيمة: معلومات النوع للباركود المعترف به

### getCodeTypeName() {#getcodetypename}

يحصل على اسم نوع الباركود القيمة: اسم النوع للباركود المعترف به

### getConfidence() {#getconfidence}

يحصل على مستوى ثقة التعرف للباركود المعترف به القيمة: BarCodeConfidence.Strong لا يحتوي على مزيفات أو أخطاء في التعرف، BarCodeConfidence.Moderate قد يحتوي أحيانًا على مزيفات أو نص مشفر غير صحيح لأن هذا المستوى من الثقة للباركودات ذات المجموع الاختباري الضعيف أو حتى بدونها، BarCodeConfidence.NONE دائمًا يحتوي على نص مشفر غير صحيح وقد يكون تعارفًا مزيفًا

### getExtended() {#getextended}

يحصل على المعاملات الموسعة للباركود المعترف به القيمة: المعاملات الموسعة للباركود المعترف به

### getReadingQuality() {#getreadingquality}

يحصل على جودة القراءة. يعمل مع باركودات 1D والبريدية. القيمة: نسبة جودة القراءة

### getRegion() {#getregion}

يحصل على منطقة الباركود القيمة: منطقة الباركود المعترف به

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا BarCodeResult.

**Returns:** A string that represents this BarCodeResult.
