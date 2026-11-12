---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "الفئة الأساسية لتشفير وفك تشفير النص المدمج في رمز MaxiCode للأنماط 2 و3."
type: docs
weight: 700
url: /ar/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

الفئة الأساسية لتشفير وفك تشفير النص المدمج في رمز MaxiCode للأنماط 2 و3.

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يعيد قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة محددة. |
| [getConstructedCodetext()](#getconstructedcodetext) | ينشئ نص الشيفرة |
| [getCountryCode()](#getcountrycode) | يحدد رمز الدولة المكوّن من 3 أرقام. |
| [getHashCode()](#gethashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [getPostalCode()](#getpostalcode) | يحدد الرمز البريدي. يجب أن يكون 9 أرقام في الوضع 2 أو 6 رموز أبجدية رقمية في الوضع 3. |
| [getSecondMessage()](#getsecondmessage) | يحدد الرسالة الثانية للباركود. |
| [getServiceCategory()](#getservicecategory) | يحدد فئة الخدمة المكوّنة من 3 أرقام. |
| [initFromString(constructedCodetext)](#initfromstring) | يُهيئ الحالة من نص الشيفرة المُنشأ. |
| [setCountryCode()](#setcountrycode) | يحدد رمز الدولة المكوّن من 3 أرقام. |
| [setPostalCode()](#setpostalcode) | يحدد الرمز البريدي. يجب أن يكون 9 أرقام في الوضع 2 أو 6 رموز أبجدية رقمية في الوضع 3. |
| [setSecondMessage()](#setsecondmessage) | يحدد الرسالة الثانية للباركود. |
| [setServiceCategory()](#setservicecategory) | يحدد فئة الخدمة المكوّنة من 3 أرقام. |

### equals(obj) {#equals}

يعيد قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة محددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة للمقارنة مع هذا الكائن |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

ينشئ نص الشيفرة

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

يحدد رمز الدولة المكوّن من 3 أرقام.

### getHashCode() {#gethashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

يحدد الرمز البريدي. يجب أن يكون 9 أرقام في الوضع 2 أو 6 رموز أبجدية رقمية في الوضع 3.

### getSecondMessage() {#getsecondmessage}

يحدد الرسالة الثانية للباركود.

### getServiceCategory() {#getservicecategory}

يحدد فئة الخدمة المكوّنة من 3 أرقام.

### initFromString(constructedCodetext) {#initfromstring}

يُهيئ الحالة من نص الشيفرة المُنشأ.

| معامل | الوصف |
| --- | --- |
| constructedCodetext | نص الشيفرة المُنشأ. |

### setCountryCode() {#setcountrycode}

يحدد رمز الدولة المكوّن من 3 أرقام.

### setPostalCode() {#setpostalcode}

يحدد الرمز البريدي. يجب أن يكون 9 أرقام في الوضع 2 أو 6 رموز أبجدية رقمية في الوضع 3.

### setSecondMessage() {#setsecondmessage}

يحدد الرسالة الثانية للباركود.

### setServiceCategory() {#setservicecategory}

يحدد فئة الخدمة المكوّنة من 3 أرقام.
