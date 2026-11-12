---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "فئة لتشفير وفك تشفير النص المضمن في رمز 4-state Royal Mailmark."
type: docs
weight: 580
url: /ar/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

فئة لتشفير وفك تشفير النص المضمن في رمز 4-state Royal Mailmark.

```js
new MailmarkCodetext()
```

يقوم بإنشاء نسخة جديدة من الفئة `MailmarkCodetext`.

## طرق

| اسم | الوصف |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | يحصل على نوع الباركود. |
| [getClass_()](#getclass-) | "0" - فارغ أو اختبار "1" - 1C (تجزئة) "2" - 2C (تجزئة) "3" - 3C (تجزئة) "4" - مميز (نشر البريد التجزئة) (لـ pote |
| [getConstructedCodetext()](#getconstructedcodetext) | إنشاء نص الترميز من بيانات Mailmark. |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | يجب أن يتوافق كل من PC و DP مع تنسيق PAF. سلسلة مكونة من تسعة أحرف تمثل "XY11 " دوليًا (لاحظ الأحرف الخمسة المتبقية s |
| [getFormat()](#getformat) | "0" – فارغ أو اختبار "1" – حرف "2" – حرف كبير |
| [getItemID()](#getitemid) | القيمة القصوى هي 99999999. |
| [getSupplychainID()](#getsupplychainid) | القيم القصوى هي 99 لباركود C و 999999 لباركود L. |
| [getVersionID()](#getversionid) | حاليًا "1" – لباركود Mailmark (0 و 2 إلى 9 و A إلى Z محجوز للاستخدام المستقبلي) |
| [initFromString(constructedCodetext)](#initfromstring) | يقوم بتهيئة بيانات Mailmark من نص الترميز المُنشأ. |
| [setClass_()](#setclass-) | "0" - فارغ أو اختبار "1" - 1C (تجزئة) "2" - 2C (تجزئة) "3" - 3C (تجزئة) "4" - مميز (نشر البريد التجزئة) (لـ pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | يجب أن يتوافق كل من PC و DP مع تنسيق PAF. سلسلة مكونة من تسعة أحرف تمثل "XY11 " دوليًا (لاحظ الأحرف الخمسة المتبقية s |
| [setFormat()](#setformat) | "0" – فارغ أو اختبار "1" – LetterN "2" – حرف كبير |
| [setItemID()](#setitemid) | القيمة القصوى هي 99999999. |
| [setSupplychainID()](#setsupplychainid) | القيم القصوى هي 99 لباركود C و 999999 لباركود L. |
| [setVersionID()](#setversionid) | حاليًا "1" – لباركود Mailmark (0 و 2 إلى 9 و A إلى Z محجوز للاستخدام المستقبلي) |

### getBarcodeType() {#getbarcodetype}

يحصل على نوع الباركود.

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - فارغ أو اختبار "1" - 1C (تجزئة) "2" - 2C (تجزئة) "3" - 3C (تجزئة) "4" - مميز (نشر البريد التجزئة) (للاستخدام المستقبلي المحتمل) "5" - مؤجل (تجزئة) "6" - هوائي (تجزئة) (للاستخدام المستقبلي المحتمل) "7" - سطحي (تجزئة) (للاستخدام المستقبلي المحتمل) "8" - مميز (الوصول إلى الشبكة) "9" - قياسي (الوصول إلى الشبكة)

### getConstructedCodetext() {#getconstructedcodetext}

إنشاء نص الترميز من بيانات Mailmark.

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

يجب أن يتوافق كل من PC و DP مع تنسيق PAF. سلسلة مكونة من تسعة أحرف تمثل "XY11 " دوليًا (لاحظ الخمس مسافات المتبقية) أو نمط من الأحرف يرمز إلى رمز فرز محلي. يتكون رمز الفرز المحلي من رمز بريد خارجي، ورمز بريد داخلي، ولاحقة نقطة التسليم.

### getFormat() {#getformat}

"0" – فارغ أو اختبار "1" – حرف "2" – حرف كبير

### getItemID() {#getitemid}

القيمة القصوى هي 99999999.

### getSupplychainID() {#getsupplychainid}

القيم القصوى هي 99 لباركود C و 999999 لباركود L.

### getVersionID() {#getversionid}

حاليًا "1" – لباركود Mailmark (0 و 2 إلى 9 و A إلى Z محجوز للاستخدام المستقبلي)

### initFromString(constructedCodetext) {#initfromstring}

يقوم بتهيئة بيانات Mailmark من نص الترميز المُنشأ.

| معامل | الوصف |
| --- | --- |
| constructedCodetext | نص الشيفرة المُنشأ. |

### setClass_() {#setclass-}

"0" - فارغ أو اختبار "1" - 1C (تجزئة) "2" - 2C (تجزئة) "3" - 3C (تجزئة) "4" - مميز (نشر البريد التجزئة) (للاستخدام المستقبلي المحتمل) "5" - مؤجل (تجزئة) "6" - هوائي (تجزئة) (للاستخدام المستقبلي المحتمل) "7" - سطحي (تجزئة) (للاستخدام المستقبلي المحتمل) "8" - مميز (الوصول إلى الشبكة) "9" - قياسي (الوصول إلى الشبكة)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

يجب أن يتوافق كل من PC و DP مع تنسيق PAF. سلسلة مكونة من تسعة أحرف تمثل "XY11 " دوليًا (لاحظ الخمس مسافات المتبقية) أو نمط من الأحرف يرمز إلى رمز فرز محلي. يتكون رمز الفرز المحلي من رمز بريد خارجي، ورمز بريد داخلي، ولاحقة نقطة التسليم.

### setFormat() {#setformat}

"0" – فارغ أو اختبار "1" – LetterN "2" – حرف كبير

### setItemID() {#setitemid}

القيمة القصوى هي 99999999.

### setSupplychainID() {#setsupplychainid}

القيم القصوى هي 99 لباركود C و 999999 لباركود L.

### setVersionID() {#setversionid}

حاليًا "1" – لباركود Mailmark (0 و 2 إلى 9 و A إلى Z محجوز للاستخدام المستقبلي)
