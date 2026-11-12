---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يخزن بيانات خاصة للباركود أحادي الأبعاد المعترف به مثل نص منفصل ومجموع التحقق."
type: docs
weight: 720
url: /ar/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

يخزن بيانات خاصة للباركود أحادي الأبعاد المعترف به مثل نص منفصل ومجموع التحقق.

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة OneDExtendedParameters المحددة. |
| [getCheckSum()](#getchecksum) | يحصل على المجموع الاختباري للباركودات أحادية البعد. القيمة: المجموع الاختباري للباركود أحادي البعد. |
| [getValue()](#getvalue) | يحصل على نص الرمز للباركودات أحادية البعد بدون المجموع الاختباري. القيمة: نص الرمز للباركودات أحادية البعد بدون المجموع الاختباري. |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [isEmpty()](#isempty) | يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية. القيمة: يُعيد `true ` إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية؛ o |
| [toString()](#tostring) | يعيد تمثيل سلسلة قابل للقراءة للبشر لهذا الكائن OneDExtendedParameters. |

### equals(obj) {#equals}

يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة OneDExtendedParameters المحددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة System.Object للمقارنة مع هذه الحالة. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

يحصل على المجموع الاختباري للباركودات أحادية البعد. القيمة: المجموع الاختباري للباركود أحادي البعد.

### getValue() {#getvalue}

يحصل على نص الرمز للباركودات أحادية البعد بدون المجموع الاختباري. القيمة: نص الرمز للباركودات أحادية البعد بدون المجموع الاختباري.

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية. القيمة: يُعيد `true` إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية؛ وإلا، `false`.

### toString() {#tostring}

يعيد تمثيل سلسلة قابل للقراءة للبشر لهذا الكائن OneDExtendedParameters.

**Returns:** A string that represents this OneDExtendedParameters.
