---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يخزن بيانات خاصة لباركود DotCode المعترف به. هذا المثال يوضح كيفية الحصول على القيم الخام لـ DotCode"
type: docs
weight: 380
url: /ar/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

يخزن بيانات خاصة لباركود DotCode المعترف به. هذا المثال يوضح كيفية الحصول على القيم الخام لـ DotCode

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة `DotCodeExtendedParameters` المحددة. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | يحصل على معرف الباركود بنمط الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | يحصل على عدد الباركودات بنمط الإلحاق المهيكل DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35. القيمة: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | يحصل على معرف الباركود بنمط الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | يحصل على عدد الباركودات بنمط الإلحاق المهيكل DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35. القيمة: |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [isReaderInitialization()](#isreaderinitialization) | يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو |
| [toString()](#tostring) | يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا `DotCodeExtendedParameters`. |

### equals(obj) {#equals}

يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة `DotCodeExtendedParameters` المحددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة System.Object للمقارنة مع هذه الحالة. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

يحصل على معرف الباركود بنمط الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. القيمة: معرف الباركود بنمط الإلحاق المهيكل DotCode.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

يحصل على عدد الباركودات بنمط الإلحاق المهيكل DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35. القيمة: عدد الباركودات بنمط الإلحاق المهيكل DotCode.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

يحصل على معرف الباركود بنمط الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. القيمة: معرف الباركود بنمط الإلحاق المهيكل DotCode.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

يحصل على عدد الباركودات بنمط الإلحاق المهيكل DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35. القيمة: عدد الباركودات بنمط الإلحاق المهيكل DotCode.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

### toString() {#tostring}

يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا `DotCodeExtendedParameters`.

**Returns:** A string that represents this `DotCodeExtendedParameters`.
