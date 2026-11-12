---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يخزن معلومات الإلحاق المهيكل QR للباركود المعترف به."
type: docs
weight: 810
url: /ar/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

يخزن معلومات الإلحاق المهيكل QR للباركود المعترف به.

```js
new QRExtendedParameters()
```

**Example:**

```js
//This sample shows how to get QR Structured Append data

let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
   console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
   console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يرجع قيمة تشير إلى ما إذا كانت هذه النسخة مساوية لقيمة QRExtendedParameters المحددة. |
| [getErrorLevel()](#geterrorlevel) | مستوى تصحيح الأخطاء ريـد-سولومون للباركود المُعترف به. من منخفض إلى عالي: LevelL، LevelM، LevelQ، LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | إصدار رمز MicroQR المعترف به. من M1 إلى M4. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | مستوى تصحيح الأخطاء ريـد-سولومون للباركود المُعترف به. من منخفض إلى عالي: LevelL، LevelM، LevelQ، LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | يحصل على فهرس الباركود في وضع الإلحاق المُنظم للـ QR. يبدأ الفهرس من 0. القيمة الافتراضية هي -1. القيمة: كمية |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | يحصل على عدد الباركودات في وضع الإلحاق المُنظم للـ QR. القيمة الافتراضية هي -1. القيمة: كمية الباركودات في وضع الإلحاق المُنظم للـ QR |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | يحصل على بيانات التوازن في وضع الإلحاق المُنظم للـ QR. القيمة الافتراضية هي -1. القيمة: فهرس وضع الإلحاق المُنظم للـ QR |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | إصدار رمز QR المعترف به. من Version1 إلى Version40. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | إصدار رمز RectMicroQR المعترف به. من R7x43 إلى R17x139. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | يحصل على فهرس الباركود في وضع الإلحاق المُنظم للـ QR. يبدأ الفهرس من 0. القيمة الافتراضية هي -1. القيمة: كمية |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | يحصل على عدد الباركودات في وضع الإلحاق المُنظم للـ QR. القيمة الافتراضية هي -1. القيمة: كمية الباركودات في وضع الإلحاق المُنظم للـ QR |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | يحصل على بيانات التوازن في وضع الإلحاق المُنظم للـ QR. القيمة الافتراضية هي -1. القيمة: فهرس وضع الإلحاق المُنظم للـ QR |
| [getVersion()](#getversion) | إصدار رمز QR المعترف به. من Version1 إلى Version40. |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [isEmpty()](#isempty) | يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية. القيمة |
| [toString()](#tostring) | يرجع تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا QRExtendedParameters. |

### equals(obj) {#equals}

يرجع قيمة تشير إلى ما إذا كانت هذه النسخة مساوية لقيمة QRExtendedParameters المحددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة كائن للمقارنة مع هذه النسخة. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

مستوى تصحيح الأخطاء ريـد-سولومون للباركود المُعترف به. من منخفض إلى عالي: LevelL، LevelM، LevelQ، LevelH.

### getMicroQRVersion() {#getmicroqrversion}

إصدار رمز MicroQR المعترف به. من M1 إلى M4.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

مستوى تصحيح الأخطاء ريـد-سولومون للباركود المُعترف به. من منخفض إلى عالي: LevelL، LevelM، LevelQ، LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

يحصل على فهرس الباركود بنمط الإلحاق الهيكلي للـ QR. يبدأ الفهرس من 0. القيمة الافتراضية هي -1. القيمة: عدد الباركود بنمط الإلحاق الهيكلي للـ QR.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

يحصل على عدد باركودات نمط الإلحاق الهيكلي للـ QR. القيمة الافتراضية هي -1. القيمة: عدد الباركود بنمط الإلحاق الهيكلي للـ QR.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

يحصل على بيانات التكافؤ لنمط الإلحاق الهيكلي للـ QR. القيمة الافتراضية هي -1. القيمة: فهرس الباركود بنمط الإلحاق الهيكلي للـ QR.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

إصدار رمز QR المعترف به. من Version1 إلى Version40.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

إصدار رمز RectMicroQR المعترف به. من R7x43 إلى R17x139.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

يحصل على فهرس الباركود بنمط الإلحاق الهيكلي للـ QR. يبدأ الفهرس من 0. القيمة الافتراضية هي -1. القيمة: عدد الباركود بنمط الإلحاق الهيكلي للـ QR.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

يحصل على عدد باركودات نمط الإلحاق الهيكلي للـ QR. القيمة الافتراضية هي -1. القيمة: عدد الباركود بنمط الإلحاق الهيكلي للـ QR.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

يحصل على بيانات التكافؤ لنمط الإلحاق الهيكلي للـ QR. القيمة الافتراضية هي -1. القيمة: فهرس الباركود بنمط الإلحاق الهيكلي للـ QR.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

إصدار رمز QR المعترف به. من Version1 إلى Version40.

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية. القيمة

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

يرجع تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا QRExtendedParameters.

**Returns:** A string that represents this QRExtendedParameters.
