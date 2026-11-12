---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة لتشفير وفك تشفير النص المضمن في رمز HIBC PAS."
type: docs
weight: 480
url: /ar/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

فئة لتشفير وفك تشفير النص المضمن في رمز HIBC PAS.

```js
new HIBCPASCodetext()
```

**Example:**

```js
This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.

 let complexCodetext = new HIBCPASComplexCodetext();
 complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
 complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
 complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
 complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
 let generator = new ComplexBarcodeGenerator(complexCodetext);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(BarCodeImageFormat.PNG), null, DecodeType.HIBC_DATA_MATRIX_PAS);
 reader.readBarCodes();
 let codetext = reader.getFoundBarCodes()[0].getCodeText();
	let readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
 print("Data location: " + readCodetext.getDataLocation());
 print("Data type: " + readCodetext.getRecords()[0].getDataType());
 print("Data: " + readCodetext.getRecords()[0].getData());
 print("Data type: " + readCodetext.getRecords()[1].getDataType());
 print("Data: " + readCodetext.getRecords()[1].getData());
```

## طرق

| اسم | الوصف |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | منشئ HIBCPASRecord |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | إضافة سجل جديد |
| [addRecord(dataType, data)](#addrecord) | إضافة سجل جديد |
| [clear()](#clear) | يمسح قائمة السجلات |
| [equals(obj)](#equals) | يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة `HIBCPASCodetext` المحددة. |
| [getBarcodeType()](#getbarcodetype) | يحصل على نوع الباركود. |
| [getConstructedCodetext()](#getconstructedcodetext) | ينشئ نص الشيفرة |
| [getDataLocation()](#getdatalocation) | يحدد موقع البيانات. |
| [getRecords()](#getrecords) | يحصل على قائمة السجلات |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [initFromString(constructedCodetext)](#initfromstring) | يُهيئ الحالة من نص الشيفرة المُنشأ. |
| [setBarcodeType()](#setbarcodetype) | يحصل أو يعيّن نوع الباركود. يمكن ترميز نص رمز HIBC PAS باستخدام HIBCCode39PAS، HIBCCode128PAS، HIBCAztec:PAS، HIBCData |
| [setDataLocation()](#setdatalocation) | يحدد موقع البيانات. |

### _fromMwObject() (static) {#-frommwobject}

منشئ HIBCPASRecord

### addHIBCPASRecord(record) {#addhibcpasrecord}

إضافة سجل جديد

| معامل | الوصف |
| --- | --- |
| سجل | السجل المراد إضافته |

### addRecord(dataType, data) {#addrecord}

إضافة سجل جديد

| معامل | الوصف |
| --- | --- |
| dataType | نوع البيانات |
| البيانات | سلسلة البيانات |

### clear() {#clear}

يمسح قائمة السجلات

### equals(obj) {#equals}

يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة `HIBCPASCodetext` المحددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة `HIBCPASCodetext` للمقارنة مع هذه الحالة. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

يحصل على نوع الباركود.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

ينشئ نص الشيفرة

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

يحدد موقع البيانات.

### getRecords() {#getrecords}

يحصل على قائمة السجلات

**Returns:** List of records

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

يُهيئ الحالة من نص الشيفرة المُنشأ.

| معامل | الوصف |
| --- | --- |
| constructedCodetext | نص الشيفرة المُنشأ. |

### setBarcodeType() {#setbarcodetype}

يحصل أو يعيّن نوع الباركود. يمكن ترميز نص رمز HIBC PAS باستخدام أنواع الترميز HIBCCode39PAS، HIBCCode128PAS، HIBCAztec:PAS، HIBCDataMatrixPAS و HIBCQRPAS. القيمة الافتراضية: HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

يحدد موقع البيانات.
