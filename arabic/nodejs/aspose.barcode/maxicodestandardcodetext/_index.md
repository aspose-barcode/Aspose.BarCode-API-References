---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة لتشفير وفك تشفير نص MaxiCode للأنماط 4، 5 و6."
type: docs
weight: 670
url: /ar/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

فئة لتشفير وفك تشفير نص MaxiCode للأنماط 4، 5 و6.

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يعيد قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة محددة. |
| [getConstructedCodetext()](#getconstructedcodetext) | ينشئ نص الشيفرة |
| [getHashCode()](#gethashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [getMessage()](#getmessage) | يحصل على الرسالة. |
| [getMode()](#getmode) | يحصل على وضع MaxiCode. |
| [initFromString(constructedCodetext)](#initfromstring) | يُهيئ الحالة من نص الشيفرة المُنشأ. |
| [setMessage()](#setmessage) | يضبط الرسالة. |
| [setMode()](#setmode) | يضبط وضع MaxiCode. يمكن استخدام نص الترميز القياسي فقط مع الأوضاع 4 و 5 و 6. |

### equals(obj) {#equals}

يعيد قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة محددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة للمقارنة مع هذا المثيل. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

ينشئ نص الشيفرة

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

يحصل على الرسالة.

### getMode() {#getmode}

يحصل على وضع MaxiCode.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

يُهيئ الحالة من نص الشيفرة المُنشأ.

| معامل | الوصف |
| --- | --- |
| constructedCodetext | نص الشيفرة المُنشأ. |

### setMessage() {#setmessage}

يضبط الرسالة.

### setMode() {#setmode}

يضبط وضع MaxiCode. يمكن استخدام نص الترميز القياسي فقط مع الأوضاع 4 و 5 و 6.
