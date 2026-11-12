---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "معلمات Codetext."
type: docs
weight: 270
url: /ar/nodejs/aspose.barcode/codetextparameters/
---

## CodetextParameters class

معلمات Codetext.

```js
new CodetextParameters()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getAlignment()](#getalignment) | يحصل على محاذاة نص الرمز. القيمة الافتراضية: TextAlignment.CENTER. |
| [getColor()](#getcolor) | حدد لون عرض CodeText. القيمة الافتراضية BLACK. |
| [getFont()](#getfont) | حدد خط عرض CodeText. القيمة الافتراضية: Arial 5pt regular. يتم تجاهلها إذا تم تعيين FontMode إلى FontMode.AUTO. |
| [getFontMode()](#getfontmode) | حدد FontMode. إذا تم تعيين FontMode إلى Auto، سيتم حساب حجم الخط تلقائيًا بناءً على قيمة xDimension. It i |
| [getLocation()](#getlocation) | حدد موقع عرض CodeText، عيّن CodeLocation.NONE لإخفاء CodeText. القيمة الافتراضية: CodeLocation.BELOW. |
| [getNoWrap()](#getnowrap) | حدد التفاف الكلمات (فواصل الأسطر) داخل النص. القيمة الافتراضية: false. |
| [getSpace()](#getspace) | المسافة بين CodeText والباركود بوحدة القيمة. القيمة الافتراضية: 2pt. يتم تجاهلها بالنسبة إلى EAN8, EAN13, UPCE, UPCA, ISBN, |
| [getTwoDDisplayText()](#gettwoddisplaytext) | النص الذي سيُعرض بدلاً من النص المشفر في باركودات 2D. يُستخدم لـ: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [setAlignment()](#setalignment) | يضبط محاذاة نص الرمز. القيمة الافتراضية: TextAlignment.CENTER. |
| [setColor()](#setcolor) | حدد لون عرض CodeText. القيمة الافتراضية BLACK. |
| [setFont()](#setfont) | حدد خط عرض CodeText. القيمة الافتراضية: Arial 5pt regular. يتم تجاهلها إذا تم تعيين FontMode إلى FontMode.AUTO. |
| [setFontMode()](#setfontmode) | حدد FontMode. إذا تم تعيين FontMode إلى Auto، سيتم حساب حجم الخط تلقائيًا بناءً على قيمة xDimension. It i |
| [setLocation()](#setlocation) | حدد موقع عرض CodeText، عيّن CodeLocation.NONE لإخفاء CodeText. القيمة الافتراضية: CodeLocation.NONE. |
| [setNoWrap()](#setnowrap) | حدد التفاف الكلمات (فواصل الأسطر) داخل النص. القيمة الافتراضية: false. |
| [setSpace()](#setspace) | المسافة بين CodeText والباركود بوحدة القيمة. القيمة الافتراضية: 2pt. يتم تجاهلها بالنسبة إلى EAN8, EAN13, UPCE, UPCA, ISBN, |
| [setTwoDDisplayText()](#settwoddisplaytext) | النص الذي سيُعرض بدلاً من النص المشفر في باركودات 2D. يُستخدم لـ: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [toString()](#tostring) | يعيد تمثيل سلسلة قابل للقراءة للإنسان لهذا CodetextParameters. |

### getAlignment() {#getalignment}

يحصل على محاذاة نص الرمز. القيمة الافتراضية: TextAlignment.CENTER.

### getColor() {#getcolor}

حدد لون عرض CodeText. القيمة الافتراضية BLACK.

### getFont() {#getfont}

حدد خط عرض CodeText. القيمة الافتراضية: Arial 5pt regular. يتم تجاهلها إذا تم تعيين FontMode إلى FontMode.AUTO.

### getFontMode() {#getfontmode}

حدد FontMode. إذا تم تعيين FontMode إلى Auto، سيتم حساب حجم الخط تلقائيًا بناءً على قيمة xDimension. يُنصح باستخدام FontMode.AUTO خاصةً في AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. القيمة الافتراضية: FontMode.AUTO.

### getLocation() {#getlocation}

حدد موقع عرض CodeText، عيّن CodeLocation.NONE لإخفاء CodeText. القيمة الافتراضية: CodeLocation.BELOW.

### getNoWrap() {#getnowrap}

حدد التفاف الكلمات (فواصل الأسطر) داخل النص. القيمة الافتراضية: false.

### getSpace() {#getspace}

المسافة بين CodeText والباركود بوحدة القيمة. القيمة الافتراضية: 2pt. يتم تجاهلها بالنسبة إلى EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### getTwoDDisplayText() {#gettwoddisplaytext}

النص الذي سيُعرض بدلاً من codetext في الباركود ثنائي الأبعاد. يُستخدم لـ: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### setAlignment() {#setalignment}

يضبط محاذاة نص الرمز. القيمة الافتراضية: TextAlignment.CENTER.

### setColor() {#setcolor}

حدد لون عرض CodeText. القيمة الافتراضية BLACK.

### setFont() {#setfont}

حدد خط عرض CodeText. القيمة الافتراضية: Arial 5pt regular. يتم تجاهلها إذا تم تعيين FontMode إلى FontMode.AUTO.

### setFontMode() {#setfontmode}

حدد FontMode. إذا تم تعيين FontMode إلى Auto، سيتم حساب حجم الخط تلقائيًا بناءً على قيمة xDimension. يُنصح باستخدام FontMode.AUTO خاصةً في AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. القيمة الافتراضية: FontMode.AUTO.

### setLocation() {#setlocation}

حدد موقع عرض CodeText، عيّن CodeLocation.NONE لإخفاء CodeText. القيمة الافتراضية: CodeLocation.NONE.

### setNoWrap() {#setnowrap}

حدد التفاف الكلمات (فواصل الأسطر) داخل النص. القيمة الافتراضية: false.

### setSpace() {#setspace}

المسافة بين CodeText والباركود بوحدة القيمة. القيمة الافتراضية: 2pt. يتم تجاهلها بالنسبة إلى EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### setTwoDDisplayText() {#settwoddisplaytext}

النص الذي سيُعرض بدلاً من codetext في الباركود ثنائي الأبعاد. يُستخدم لـ: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### toString() {#tostring}

يعيد تمثيل سلسلة قابل للقراءة للإنسان لهذا CodetextParameters.

**Returns:** A string that represents this CodetextParameters.
