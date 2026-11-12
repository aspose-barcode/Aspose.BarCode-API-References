---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية."
type: docs
weight: 460
url: /ar/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية. يوضح هذا المثال كيفية تشفير وفك تشفير HIBC LIC باستخدام HIBCLICPrimaryCodetext.

```js
new HIBCLICPrimaryDataCodetext()
```

**Example:**

```js
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة `HIBCLICPrimaryDataCodetext` المحددة. |
| [getConstructedCodetext()](#getconstructedcodetext) | ينشئ نص الشيفرة |
| [getData()](#getdata) | يحدد البيانات الأولية. |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [initFromString(constructedCodetext)](#initfromstring) | يُهيئ الحالة من نص الشيفرة المُنشأ. |
| [setData()](#setdata) | يحدد البيانات الأولية. |

### equals(obj) {#equals}

يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة `HIBCLICPrimaryDataCodetext` المحددة.

| معامل | الوصف |
| --- | --- |
| obj | `HIBCLICPrimaryDataCodetext` قيمة للمقارنة مع هذه المثيلة. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

ينشئ نص الشيفرة

**Returns:** Constructed codetext

### getData() {#getdata}

يحدد البيانات الأولية.

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

يُهيئ الحالة من نص الشيفرة المُنشأ.

| معامل | الوصف |
| --- | --- |
| constructedCodetext | نص الشيفرة المُنشأ. |

### setData() {#setdata}

يحدد البيانات الأولية.
