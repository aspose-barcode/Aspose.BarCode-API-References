---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يخزن بيانات خاصة للباركود DataMatrix المعترف به. يوضح هذا المثال كيفية الحصول على القيم الأولية لـ DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /ar/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

يخزن بيانات خاصة للباركود DataMatrix المعترف به. يوضح هذا المثال كيفية الحصول على القيم الأولية لـ DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | إرجاع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة `DataMatrixExtendedParameters` المحددة. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | يحصل على معرف الباركود في وضع الإلحاق المنظم DataMatrix. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات cou |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | يحصل على عدد الباركودات في وضع الإلحاق المنظم DataMatrix. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35. Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | يحصل على معرف الباركود في وضع الإلحاق المنظم DataMatrix. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات cou |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [isReaderProgramming()](#isreaderprogramming) | يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو |
| [toString()](#tostring) | إرجاع تمثيل نصي قابل للقراءة البشرية لهذا `DataMatrixExtendedParameters`. |

### equals(obj) {#equals}

إرجاع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة `DataMatrixExtendedParameters` المحددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة System.Object للمقارنة مع هذه الحالة. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

يحصل على معرف الباركود في وضع الإلحاق المنظم DataMatrix. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. القيمة: معرف الباركود في وضع الإلحاق المنظم DataMatrix.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

يحصل على عدد الباركودات في وضع الإلحاق المهيكل لـ DataMatrix. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35. القيمة: عدد الباركود في وضع الإلحاق المهيكل لـ DataMatrix.

### getStructuredAppendFileId() {#getstructuredappendfileid}

يحصل على معرف الباركود في وضع الإلحاق المنظم DataMatrix. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. القيمة: معرف الباركود في وضع الإلحاق المنظم DataMatrix.

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

### toString() {#tostring}

إرجاع تمثيل نصي قابل للقراءة البشرية لهذا `DataMatrixExtendedParameters`.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
