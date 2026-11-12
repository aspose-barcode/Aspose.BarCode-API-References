---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يخزن معلومات إضافية عن DataBar للباركود المعترف به"
type: docs
weight: 310
url: /ar/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

يخزن معلومات إضافية عن DataBar للباركود المعترف به

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة DataBarExtendedParameters المحددة. |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [is2DCompositeComponent()](#is2dcompositecomponent) | يحصل على علامة مكوّن DataBar 2D المركب. القيمة الافتراضية هي false. |
| [toString()](#tostring) | يعيد تمثيل نصي قابل للقراءة البشرية لهذا. |

### equals(obj) {#equals}

يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة DataBarExtendedParameters المحددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة DataBarExtendedParameters للمقارنة مع هذه المثيلة. |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

يحصل على علامة مكوّن DataBar 2D المركب. القيمة الافتراضية هي false.

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

يعيد تمثيل نصي قابل للقراءة البشرية لهذا.

**Returns:** A string that represents this .
