---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يخزن معلومات بيانات تعريفية لـ MacroPdf417 للباركود المعترف به."
type: docs
weight: 760
url: /ar/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

يخزن معلومات بيانات تعريفية لـ MacroPdf417 للباركود المعترف به.

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة Pdf417ExtendedParameters المحددة. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | اسم المستلم في Macro PDF417 (اختياري). |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | المجموع الاختباري لـ Macro PDF417 (اختياري). |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | يحصل على معرف الملف للباركود، متاح فقط مع MacroPdf417. القيمة: معرف الملف لـ MacroPdf417 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | اسم ملف Macro PDF417 (اختياري). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | حجم ملف Macro PDF417 (اختياري). |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | يحصل على معرف الجزء من الباركود، متاح فقط مع MacroPdf417. القيمة: معرف الجزء من الباركود. |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | يحصل على عدد أقسام الباركود macro pdf417. القيمة الافتراضية هي -1. القيمة: عدد الأقسام. |
| [getMacroPdf417Sender()](#getmacropdf417sender) | اسم المرسل Macro PDF417 (اختياري). |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | الطابع الزمني Macro PDF417 (اختياري). |
| [hashCode()](#hashcode) | يرجع رمز التجزئة لهذه الحالة. |
| [isCode128Emulation()](#iscode128emulation) | علامة تشير إلى أن الباركود MicroPdf417 مشفر باستخدام كلمات شفرة محاكاة Code 128 908 أو 909 أو 910 أو 911. |
| [isLinked()](#islinked) | علامة تشير إلى أن الباركود يجب ربطه بباركود 1D. القيمة: علامة الربط |
| [isReaderInitialization()](#isreaderinitialization) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [toString()](#tostring) | يعيد تمثيل سلسلة قابلة للقراءة من قبل الإنسان لهذا الكائن Pdf417ExtendedParameters. |

### equals(obj) {#equals}

يعيد قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة Pdf417ExtendedParameters المحددة.

| معامل | الوصف |
| --- | --- |
| obj | قيمة System.Object للمقارنة مع هذه الحالة. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

اسم المستلم في Macro PDF417 (اختياري).

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

المجموع الاختباري لـ Macro PDF417 (اختياري).

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

يحصل على معرف الملف للباركود، متاح فقط مع MacroPdf417. القيمة: معرف الملف لـ MacroPdf417

### getMacroPdf417FileName() {#getmacropdf417filename}

اسم ملف Macro PDF417 (اختياري).

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

حجم ملف Macro PDF417 (اختياري).

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

يحصل على معرف الجزء من الباركود، متاح فقط مع MacroPdf417. القيمة: معرف الجزء من الباركود.

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

يحصل على عدد أقسام الباركود macro pdf417. القيمة الافتراضية هي -1. القيمة: عدد الأقسام.

### getMacroPdf417Sender() {#getmacropdf417sender}

اسم المرسل Macro PDF417 (اختياري).

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

الطابع الزمني Macro PDF417 (اختياري).

**Returns:** Time stamp.

### hashCode() {#hashcode}

يرجع رمز التجزئة لهذه الحالة.

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

علامة تشير إلى أن الباركود MicroPdf417 مشفر باستخدام كلمات شفرة محاكاة Code 128 908 أو 909 أو 910 أو 911.

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

علامة تشير إلى أن الباركود يجب ربطه بباركود 1D. القيمة: علامة الربط

### isReaderInitialization() {#isreaderinitialization}

يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

**Returns:** Reader initialization flag

### toString() {#tostring}

يعيد تمثيل سلسلة قابلة للقراءة من قبل الإنسان لهذا الكائن Pdf417ExtendedParameters.

**Returns:** A string that represents this Pdf417ExtendedParameters.
