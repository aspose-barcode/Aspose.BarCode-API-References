---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "الفئة الأساسية للترميز وفك الترميز للنص المضمن في رمز HIBC LIC."
type: docs
weight: 450
url: /ar/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

الفئة الأساسية للترميز وفك الترميز للنص المضمن في رمز HIBC LIC. يوضح هذا المثال كيفية فك ترميز نص HIBC LIC الخام إلى كائن HIBCLICComplexCodetext.

```js
new HIBCLICComplexCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.HIBC_AZTEC_LIC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
   let resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
   print("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
   print("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | يحصل أو يضبط نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataM |
| [getConstructedCodetext()](#getconstructedcodetext) | ينشئ نص الشيفرة |
| [initFromString(constructedCodetext)](#initfromstring) | يُهيئ الحالة من نص الشيفرة المُنشأ. |
| [setBarcodeType()](#setbarcodetype) | يحصل أو يضبط نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataM |

### getBarcodeType() {#getbarcodetype}

يحصل أو يضبط نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام أنواع الترميز HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

ينشئ نص الشيفرة

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

يُهيئ الحالة من نص الشيفرة المُنشأ.

| معامل | الوصف |
| --- | --- |
| constructedCodetext | نص الشيفرة المُنشأ. |

### setBarcodeType() {#setbarcodetype}

يحصل أو يضبط نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام أنواع الترميز HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC.

**Returns:** Barcode type.
