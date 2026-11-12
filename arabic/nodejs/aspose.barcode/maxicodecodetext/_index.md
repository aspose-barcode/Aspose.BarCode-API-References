---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "الفئة الأساسية لتشفير وفك تشفير النص المضمّن في رمز MaxiCode."
type: docs
weight: 600
url: /ar/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

الفئة الأساسية لتشفير وفك تشفير النص المضمّن في رمز MaxiCode. تُظهر هذه العينة كيفية فك تشفير نص MaxiCode الخام إلى كائن MaxiCodeCodetext.

```js
new MaxiCodeCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
     console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
     console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | يحصل على نوع الباركود. |
| [getECIEncoding()](#geteciencoding) | يحصل على ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode هو AUTO. |
| [getEncodeMode()](#getencodemode) | يحصل على وضع ترميز MaxiCode. القيمة الافتراضية: Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | يحصل على وضع ترميز MaxiCode. |
| [getMode()](#getmode) | يحصل على وضع MaxiCode. |
| [setECIEncoding()](#seteciencoding) | يضبط ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode هو AUTO. |
| [setEncodeMode(value)](#setencodemode) | يضبط وضع ترميز MaxiCode. القيمة الافتراضية: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | يضبط وضع ترميز MaxiCode. |

### getBarcodeType() {#getbarcodetype}

يحصل على نوع الباركود.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

يحصل على ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode هو AUTO.

### getEncodeMode() {#getencodemode}

يحصل على وضع ترميز MaxiCode. القيمة الافتراضية: Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

يحصل على وضع ترميز MaxiCode.

### getMode() {#getmode}

يحصل على وضع MaxiCode.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

يضبط ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode هو AUTO.

### setEncodeMode(value) {#setencodemode}

يضبط وضع ترميز MaxiCode. القيمة الافتراضية: Auto.

| معامل | الوصف |
| --- | --- |
| القيمة | وضع ترميز MaxiCode. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

يضبط وضع ترميز MaxiCode.
