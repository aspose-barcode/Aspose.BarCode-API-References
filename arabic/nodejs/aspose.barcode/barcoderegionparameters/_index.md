---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يمثل منطقة الباركود الذي تم التعرف عليه وزاوية الباركود"
type: docs
weight: 100
url: /ar/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

يمثل منطقة الباركود الذي تم التعرف عليه وزاوية الباركود

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة BarCodeRegionParameters المحددة. |
| [getAngle()](#getangle) | يحصل على زاوية الباركود (0-360). القيمة: الزاوية للباركود (0-360). |
| [getPoints()](#getpoints) | يحصل على مصفوفة Points التي تحدد منطقة الباركود القيمة: يرجع مصفوفة Points التي تحدد منطقة الباركود |
| [getQuadrangle()](#getquadrangle) | يحصل على Quadrangle التي تحدد منطقة الباركود القيمة: يرجع Quadrangle التي تحدد منطقة الباركود |
| [getRectangle()](#getrectangle) | يحصل على Rectangle التي تحدد منطقة الباركود القيمة: يرجع Rectangle التي تحدد منطقة الباركود |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [toString()](#tostring) | يرجع تمثيلًا نصيًا قابلاً للقراءة البشرية لهذا BarCodeRegionParameters. |

### equals(obj) {#equals}

يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة BarCodeRegionParameters المحددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة System.Object للمقارنة مع هذه الحالة. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

يحصل على زاوية الباركود (0-360). القيمة: الزاوية للباركود (0-360).

### getPoints() {#getpoints}

يحصل على مصفوفة Points التي تحدد منطقة الباركود القيمة: يرجع مصفوفة Points التي تحدد منطقة الباركود

### getQuadrangle() {#getquadrangle}

يحصل على Quadrangle التي تحدد منطقة الباركود القيمة: يرجع Quadrangle التي تحدد منطقة الباركود

### getRectangle() {#getrectangle}

يحصل على Rectangle التي تحدد منطقة الباركود القيمة: يرجع Rectangle التي تحدد منطقة الباركود

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

يرجع تمثيلًا نصيًا قابلاً للقراءة البشرية لهذا BarCodeRegionParameters.

**Returns:** A string that represents this BarCodeRegionParameters.
