---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يخزن البيانات الخاصة لباركود Aztec المعترف به. يوضح هذا المثال كيفية الحصول على القيم الأولية لباركود Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /ar/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

يخزن البيانات الخاصة لباركود Aztec المعترف به. يوضح هذا المثال كيفية الحصول على القيم الأولية لباركود Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة `AztecExtendedParameters` المحددة. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | يحصل على معرف باركود وضع الإلحاق المهيكل لـ Aztec. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | يحصل على عدد باركودات وضع الإلحاق المهيكل لـ Aztec. القيمة الافتراضية هي 0. يجب أن يكون العدد بين 1 و 26. القيمة: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | يحصل على معرف الملف لوضع الإلحاق المهيكل لـ Aztec. القيمة الافتراضية هي سلسلة فارغة. القيمة: معرف الملف لـ Aztec stru |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [isReaderInitialization()](#isreaderinitialization) | يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو |
| [toString()](#tostring) | يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا `AztecExtendedParameters`. |

### equals(obj) {#equals}

يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة `AztecExtendedParameters` المحددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة System.Object للمقارنة مع هذه الحالة. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

يحصل على معرف باركود وضع الإلحاق المهيكل لـ Aztec. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي 0. القيمة: معرف الباركود لوضع الإلحاق المهيكل لـ Aztec.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

يحصل على عدد باركودات وضع الإلحاق المهيكل لـ Aztec. القيمة الافتراضية هي 0. يجب أن يكون العدد بين 1 و 26. القيمة: عدد الباركودات لوضع الإلحاق المهيكل لـ Aztec.

### getStructuredAppendFileId() {#getstructuredappendfileid}

يحصل على معرف الملف لوضع الإلحاق المهيكل لـ Aztec. القيمة الافتراضية هي سلسلة فارغة. القيمة: معرف الملف لوضع الإلحاق المهيكل لـ Aztec.

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

### toString() {#tostring}

يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا `AztecExtendedParameters`.

**Returns:** A string that represents this `AztecExtendedParameters`.
