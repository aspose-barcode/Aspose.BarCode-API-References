---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يخزن بيانات خاصة لباركود Code128 المعترف به، يمثل منطقة الباركود المعترف به وزاوية الباركود"
type: docs
weight: 240
url: /ar/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

يخزن بيانات خاصة لباركود Code128 المعترف به، يمثل منطقة الباركود المعترف به وزاوية الباركود

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة Code128ExtendedParameters المحددة. |
| [getCode128DataPortions()](#getcode128dataportions) | يحصل على مصفوفة Code128DataPortion للباركود Code128 المعترف به. قيمة Code128DataPortion. |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [toString()](#tostring) | يعيد تمثيل نصي قابل للقراءة البشرية لهذا Code128ExtendedParameters. |

### equals(obj) {#equals}

يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة Code128ExtendedParameters المحددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة System.Object للمقارنة مع هذه الحالة. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

يحصل على مصفوفة Code128DataPortion للباركود Code128 المعترف به. قيمة Code128DataPortion.

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

يعيد تمثيل نصي قابل للقراءة البشرية لهذا Code128ExtendedParameters.

**Returns:** A string that represents this Code128ExtendedParameters.
