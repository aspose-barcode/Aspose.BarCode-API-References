---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "مولد النص الموسع للباركودات QR ثنائية الأبعاد لوضع ExtendedCodetext في QREncodeMode. استخدم خاصية Display2DText في BarCodeBuilder لتعيين النص الظاهر إلى rem"
type: docs
weight: 820
url: /ar/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

مولد النص الموسع للباركودات QR ثنائية الأبعاد لوضع ExtendedCodetext في QREncodeMode. استخدم خاصية Display2DText في BarCodeBuilder لتعيين النص الظاهر إلى إزالة الأحرف الإدارية.

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## طرق

| اسم | الوصف |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | يضيف النص المشفر مع وضع QR compaction mode المحدد إلى عناصر النص الموسع. |
| [addFNC1FirstPosition()](#addfnc1firstposition) | يضيف FNC1 في الموضع الأول إلى عناصر النص الموسع. |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | يضيف فاصل المجموعة (GS - '\\u001D') إلى عناصر النص الموسع. |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | يضيف FNC1 في الموضع الثاني إلى عناصر النص الموسع. |
| [clear()](#clear) | يمسح عناصر النص الشيفري الموسعة |
| [getExtendedCodetext()](#getextendedcodetext) | ينشئ النص المشفر الموسع من قائمة النص المشفر الموسع. |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

يضيف النص المشفر مع وضع QR compaction mode المحدد إلى عناصر النص الموسع.

| معامل | الوصف |
| --- | --- |
| الوضع | وضع ضغط QR للنص المشفر. |
| codetext | النص المشفر في Unicode لإضافته كعنصر نص موسع. |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

يضيف FNC1 في الموضع الأول إلى عناصر النص الموسع.

### addFNC1GroupSeparator() {#addfnc1groupseparator}

يضيف فاصل المجموعة (GS - '\\u001D') إلى عناصر النص الموسع.

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

يضيف FNC1 في الموضع الثاني إلى عناصر النص الموسع.

| معامل | الوصف |
| --- | --- |
| codetext | قيمة FNC1 في الموضع الثاني |

### clear() {#clear}

يمسح عناصر النص الشيفري الموسعة

### getExtendedCodetext() {#getextendedcodetext}

ينشئ النص المشفر الموسع من قائمة النص المشفر الموسع.

**Returns:** Extended codetext as string
