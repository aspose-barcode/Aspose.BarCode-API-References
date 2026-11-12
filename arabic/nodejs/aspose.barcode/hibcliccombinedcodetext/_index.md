---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة لتشفير وفك تشفير النص المضمّن في رمز HIBC LIC الذي يخزن البيانات الأولية والثانوية."
type: docs
weight: 440
url: /ar/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

فئة لتشفير وفك تشفير النص المضمّن في رمز HIBC LIC الذي يخزن البيانات الأولية والثانوية. تُظهر هذه العينة كيفية تشفير وفك تشفير HIBC LIC باستخدام HIBCLICCombinedCodetext.

```js
new HIBCLICCombinedCodetext()
```

**Example:**

```js
let combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
combinedCodetext.setPrimaryData(new PrimaryData());
combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
print("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
print("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
print("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
print("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
print("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يرجع قيمة تشير إلى ما إذا كان هذا الكائن يساوي قيمة `HIBCLICCombinedCodetext` المحددة. |
| [getConstructedCodetext()](#getconstructedcodetext) | ينشئ نص الشيفرة |
| [getPrimaryData()](#getprimarydata) | يحدد البيانات الأولية. |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | يحدد البيانات الثانوية والبيانات الإضافية المكملة. |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [initFromString(constructedCodetext)](#initfromstring) | يُهيئ الحالة من نص الشيفرة المُنشأ. |
| [setPrimaryData()](#setprimarydata) | يحدد البيانات الأولية. |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | يحدد البيانات الثانوية والبيانات الإضافية المكملة. |

### equals(obj) {#equals}

يرجع قيمة تشير إلى ما إذا كان هذا الكائن يساوي قيمة `HIBCLICCombinedCodetext` المحددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة `HIBCLICCombinedCodetext` للمقارنة مع هذا الكائن. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

ينشئ نص الشيفرة

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

يحدد البيانات الأولية.

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

يحدد البيانات الثانوية والبيانات الإضافية المكملة.

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

يُهيئ الحالة من نص الشيفرة المُنشأ.

| معامل | الوصف |
| --- | --- |
| constructedCodetext | نص الشيفرة المُنشأ. |

### setPrimaryData() {#setprimarydata}

يحدد البيانات الأولية.

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

يحدد البيانات الثانوية والبيانات الإضافية المكملة.
