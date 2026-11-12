---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "معلمات PDF417."
type: docs
weight: 770
url: /ar/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

معلمات PDF417. يحتوي على معلمات PDF417 و MacroPDF417 و MicroPDF417 و GS1MicroPdf417. يتطلب MacroPDF417 حقلين: Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية. يتطلب MicroPDF417 في وضع الإلحاق المهيكل (نفس وضع MacroPDF417) حقلين: Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية. تُظهر هذه الأمثلة كيفية ترميز أوضاع UCC/EAN-128 غير المرتبطة في GS1MicroPdf417

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد. |
| [getColumns()](#getcolumns) | عدد الأعمدة. |
| [getECIEncoding()](#geteciencoding) | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لـ |
| [getEncodeMode()](#getencodemode) | يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto. |
| [getErrorLevel()](#geterrorlevel) | يحصل على نوع ترميز Pdf417 لمستوى تصحيح الأخطاء لباركود، يتراوح من level0 إلى level8، حيث يعني level0 عدم وجود تصحيح للأخطاء |
| [getMacroCharacters()](#getmacrocharacters) | يتم استخدام قيم أحرف الماكرو 05 و 06 للحصول على ترميز أكثر كثافة في أوضاع خاصة. يمكن استخدامها فقط مع Micro |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | اسم المستلم للباركود MacroPdf417 (حقل اختياري). اسم المستلم للباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل A |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | مجموع تحقق الباركود MacroPdf417 (حقل اختياري). مجموع تحقق الباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل) |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | معرفات تفسير القناة الموسعة. ينطبق على حقول النص Macro PDF417 |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | معرّف ملف الباركود MacroPdf417 (حقل مطلوب). معرّف ملف الباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المهيكل) |
| [getMacroPdf417FileName()](#getmacropdf417filename) | اسم ملف الباركود MacroPdf417 (حقل اختياري). اسم ملف الباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل) |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | حجم ملف MacroPdf417 (حقل اختياري). حجم ملف MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل) حجم الملف |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | معرّف الجزء للباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 إلى MacroSegmentsCount - 1. للباركود MicroPDF417 |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | عدد أجزاء الباركود MacroPdf417 (حقل اختياري). عدد أجزاء الباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل A |
| [getMacroPdf417Sender()](#getmacropdf417sender) | اسم المرسل للباركود MacroPdf417 (حقل اختياري). اسم المرسل للباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل) |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة مُنهي Macro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PD |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | الطابع الزمني للباركود MacroPdf417 (حقل اختياري). الطابع الزمني للباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل mo |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | نوع ترميز Pdf417 لوضع الضغط للباركود. القيمة الافتراضية: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لـ |
| [getPdf417EncodeMode()](#getpdf417encodemode) | يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | يحصل على نوع ترميز Pdf417 لمستوى تصحيح الأخطاء لباركود، يتراوح من level0 إلى level8، حيث يعني level0 عدم وجود تصحيح للأخطاء |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | يحصل على اسم المستلم للباركود macro Pdf417. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | يحصل على مجموع تحقق الباركود macro Pdf417. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | معرفات تفسير القناة الموسعة. ينطبق على حقول النص Macro PDF417 |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | يحصل على معرّف ملف الباركود macro Pdf417. يستخدم لـ MacroPdf417. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | يحصل على اسم ملف الباركود macro Pdf417. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | يحصل على حجم ملف macro Pdf417. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | يحصل على معرّف الجزء للباركود macro Pdf417، يبدأ من 0 إلى MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | يحصل على عدد أجزاء الباركود macro Pdf417. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | يحصل على اسم المرسل للباركود macro Pdf417. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة مُنهي Macro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PD |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | يحصل على الطابع الزمني للباركود macro Pdf417. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | ما إذا كان نوع ترميز Pdf417 للباركود مقطّعًا (لتقليل المساحة). |
| [getRows()](#getrows) | عدد الصفوف. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | يحدد معرّف الباركود في وضع الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو مساويًا للباركودات |
| [getTruncate()](#gettruncate) | ما إذا كان نوع ترميز Pdf417 للباركود مقطّعًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. مؤشر الصف الأيمن |
| [isCode128Emulation()](#iscode128emulation) | يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع محاكاة Code 128. يمكنها تشفير FNC1 في الوضع الثاني للأوضاع 908 و |
| [isLinked()](#islinked) | يحدد أوضاع الربط مع الباركودات GS1MicroPdf417 و MicroPdf417 و Pdf417. مع ترميز رموز GS1MicroPdf417 يشفّر 906، 907 |
| [isReaderInitialization()](#isreaderinitialization) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ |
| [setAspectRatio()](#setaspectratio) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد. |
| [setCode128Emulation()](#setcode128emulation) | يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع محاكاة Code 128. يمكنها تشفير FNC1 في الوضع الثاني للأوضاع 908 و |
| [setColumns()](#setcolumns) | عدد الأعمدة. |
| [setECIEncoding()](#seteciencoding) | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لـ |
| [setEncodeMode()](#setencodemode) | يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto. |
| [setErrorLevel(value)](#seterrorlevel) | يضبط نوع ترميز Pdf417 لمستوى تصحيح الأخطاء للباركود من المستوى0 إلى المستوى8، حيث يعني المستوى0 عدم وجود تصحيح أخطاء |
| [setLinked()](#setlinked) | يحدد أوضاع الربط مع الباركودات GS1MicroPdf417 و MicroPdf417 و Pdf417. مع ترميز رموز GS1MicroPdf417 يشفّر 906، 907 |
| [setMacroCharacters()](#setmacrocharacters) | يتم استخدام قيم أحرف الماكرو 05 و 06 للحصول على ترميز أكثر كثافة في أوضاع خاصة. يمكن استخدامها فقط مع Micro |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | اسم المستلم للباركود MacroPdf417 (حقل اختياري). اسم المستلم للباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل A |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | مجموع تحقق الباركود MacroPdf417 (حقل اختياري). مجموع تحقق الباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل) |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | معرفات تفسير القناة الموسعة. ينطبق على حقول النص Macro PDF417 |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | معرّف ملف الباركود MacroPdf417 (حقل مطلوب). معرّف ملف الباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المهيكل) |
| [setMacroPdf417FileName()](#setmacropdf417filename) | اسم ملف الباركود MacroPdf417 (حقل اختياري). اسم ملف الباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل) |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | حجم ملف MacroPdf417 (حقل اختياري). حجم ملف MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل) حجم الملف |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | معرّف الجزء للباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 إلى MacroSegmentsCount - 1. للباركود MicroPDF417 |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | عدد أجزاء الباركود MacroPdf417 (حقل اختياري). عدد أجزاء الباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل A |
| [setMacroPdf417Sender()](#setmacropdf417sender) | اسم المرسل للباركود MacroPdf417 (حقل اختياري). اسم المرسل للباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل) |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة مُنهي Macro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PD |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | الطابع الزمني للباركود MacroPdf417 (حقل اختياري). الطابع الزمني للباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل mo |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | نوع ترميز Pdf417 لوضع الضغط للباركود. القيمة الافتراضية: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لـ |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | يضبط نوع ترميز Pdf417 لمستوى تصحيح الأخطاء للباركود من المستوى0 إلى المستوى8، حيث يعني المستوى0 عدم وجود تصحيح أخطاء |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | يضبط اسم المستلم لباركود macro Pdf417. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | يضبط مجموع التحقق لباركود macro Pdf417. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | معرفات تفسير القناة الموسعة. ينطبق على حقول النص Macro PDF417 |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | يضبط معرف الملف لباركود macro Pdf417. يُستخدم لـ MacroPdf417. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | يضبط اسم ملف باركود macro Pdf417. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | يضبط حجم ملف macro Pdf417. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | يضبط معرف الجزء لباركود macro Pdf417، والذي يبدأ من 0 حتى MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | يضبط عدد أجزاء باركود macro Pdf417. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | يضبط اسم المرسل لباركود macro Pdf417. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة مُنهي Macro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PD |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | يضبط الطابع الزمني لباركود macro Pdf417. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | ما إذا كان نوع ترميز Pdf417 للباركود مقطّعًا (لتقليل المساحة). |
| [setReaderInitialization(value)](#setreaderinitialization) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ |
| [setRows()](#setrows) | عدد الصفوف. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | يحدد معرّف الباركود في وضع الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو مساويًا للباركودات |
| [setTruncate()](#settruncate) | ما إذا كان نوع ترميز Pdf417 للباركود مقطّعًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. مؤشر الصف الأيمن |
| [toString()](#tostring) | يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا الكائن Pdf417Parameters. |

### getAspectRatio() {#getaspectratio}

نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد.

### getColumns() {#getcolumns}

عدد الأعمدة.

### getECIEncoding() {#geteciencoding}

معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. لا تُطبق على حقول نص Macro PDF417. يتكون التنفيذ الحالي من جميع ترميزات مجموعة الأحرف المعروفة.

### getEncodeMode() {#getencodemode}

يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto.

### getErrorLevel() {#geterrorlevel}

يحصل على نوع ترميز Pdf417 لمستوى تصحيح الأخطاء للباركود من المستوى0 إلى المستوى8، حيث يعني المستوى0 عدم وجود معلومات تصحيح أخطاء، ويعني المستوى8 أفضل تصحيح أخطاء مما ينتج صورة أكبر.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر تكثيفًا في الأوضاع الخاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع 916 و917 في MicroPdf417. القيمة الافتراضية: MacroCharacters.None. تُظهر هذه الأمثلة كيفية ترميز أحرف الماكرو في MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

اسم المستلم لباركود MacroPdf417 (حقل اختياري). اسم المستلم لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل).

### getMacroPdf417Checksum() {#getmacropdf417checksum}

مجموع التحقق لباركود MacroPdf417 (حقل اختياري). مجموع التحقق لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل). يحتوي حقل مجموع التحقق على قيمة مجموع التحقق CRC 16‑بت (2 بايت) باستخدام كثير الحدود CCITT-16. x^16 + x^12 + x^5 + 1

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

معرفات تفسير القناة الموسعة. ينطبق على حقول النص Macro PDF417

### getMacroPdf417FileID() {#getmacropdf417fileid}

معرف الملف لباركود MacroPdf417 (حقل مطلوب). معرف الملف لباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المهيكل).

### getMacroPdf417FileName() {#getmacropdf417filename}

اسم ملف باركود MacroPdf417 (حقل اختياري). اسم ملف باركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل).

### getMacroPdf417FileSize() {#getmacropdf417filesize}

حجم ملف MacroPdf417 (حقل اختياري). حجم ملف MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل). يحتوي حقل حجم الملف على حجم الملف الأصلي بالكامل بالبايت.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

معرف الجزء لباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 حتى MacroSegmentsCount - 1. معرف الجزء لباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المهيكل).

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

عدد أجزاء باركود MacroPdf417 (حقل اختياري). عدد أجزاء باركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل).

### getMacroPdf417Sender() {#getmacropdf417sender}

اسم المرسل لباركود MacroPdf417 (حقل اختياري). اسم المرسل لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل).

### getMacroPdf417Terminator() {#getmacropdf417terminator}

يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة Terminator لMacro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PDF417.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

الطابع الزمني لباركود MacroPdf417 (حقل اختياري). الطابع الزمني لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المنظم)

### getPdf417CompactionMode() {#getpdf417compactionmode}

نوع ترميز Pdf417 لوضع الضغط للباركود. القيمة الافتراضية: Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. يتضمن التنفيذ الحالي جميع ترميزات مجموعات الأحرف المعروفة.

### getPdf417EncodeMode() {#getpdf417encodemode}

يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

يحصل على نوع ترميز Pdf417 لمستوى تصحيح الأخطاء للباركود من المستوى0 إلى المستوى8، حيث يعني المستوى0 عدم وجود معلومات تصحيح أخطاء، ويعني المستوى8 أفضل تصحيح أخطاء مما ينتج صورة أكبر.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

يحصل على اسم المستلم للباركود macro Pdf417.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

يحصل على مجموع تحقق الباركود macro Pdf417.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

معرفات تفسير القناة الموسعة. ينطبق على حقول النص Macro PDF417

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

يحصل على معرّف ملف الباركود macro Pdf417. يستخدم لـ MacroPdf417.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

يحصل على اسم ملف الباركود macro Pdf417.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

يحصل على حجم ملف macro Pdf417.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

يحصل على معرّف الجزء للباركود macro Pdf417، يبدأ من 0 إلى MacroSegmentsCount - 1.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

يحصل على عدد أجزاء الباركود macro Pdf417.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

يحصل على اسم المرسل للباركود macro Pdf417.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة Terminator لMacro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PDF417.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

يحصل على الطابع الزمني للباركود macro Pdf417.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

ما إذا كان نوع ترميز Pdf417 للباركود مقطّعًا (لتقليل المساحة).

### getRows() {#getrows}

عدد الصفوف.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

يحدد معرف (ID) باركود وضع الإلحاق المنظم DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

### getTruncate() {#gettruncate}

ما إذا كان نوع رموز Pdf417 للباركود مقصوصًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. يتم إزالة مؤشر الصف الأيمن ونمط الإيقاف الأيمن في هذا الوضع.

### isCode128Emulation() {#iscode128emulation}

يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير `FNC1` في الموضع الثاني للأنماط 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المُعترف به يمكن تفسيره كـ Code 128. تُظهر هذه الأمثلة كيفية تشفير أوضاع محاكاة Code 128 مع `FNC1` في الموضع الثاني وبدونه. بهذه الطريقة يمكن فك تشفير MicroPdf417 كباركود Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

يحدد أوضاع الربط مع باركودات GS1MicroPdf417 وMicroPdf417 وPdf417. مع رموز GS1MicroPdf417 يتم ترميز أوضاع “Linked” UCC/EAN-128 للأرقام 906 و907 و912 و913 و914 و915. مع رموز MicroPdf417 وPdf417 يتم ترميز علم الربط 918 للمكوّن الخطي المرتبط غير EAN.UCC. تُظهر هذه الأمثلة كيفية ترميز أوضاع “Linked” UCC/EAN-128 في GS1MicroPdf417 وعلم الربط (918) في باركودات MicroPdf417 وPdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

نسبة الارتفاع إلى العرض لوحدة الباركود ثنائي الأبعاد.

### setCode128Emulation() {#setcode128emulation}

يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير `FNC1` في الموضع الثاني للأنماط 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المُعترف به يمكن تفسيره كـ Code 128. تُظهر هذه الأمثلة كيفية تشفير أوضاع محاكاة Code 128 مع `FNC1` في الموضع الثاني وبدونه. بهذه الطريقة يمكن فك تشفير MicroPdf417 كباركود Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

عدد الأعمدة.

### setECIEncoding() {#seteciencoding}

معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. لا تُطبق على حقول نص Macro PDF417. يتكون التنفيذ الحالي من جميع ترميزات مجموعة الأحرف المعروفة.

### setEncodeMode() {#setencodemode}

يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto.

### setErrorLevel(value) {#seterrorlevel}

يضبط مستوى تصحيح الأخطاء لرمز Pdf417 للباركود، ويتراوح بين level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، ويعني level8 أفضل تصحيح أخطاء مما ينتج صورة أكبر.

| معامل | الوصف |
| --- | --- |
| القيمة | نوع تصحيح الأخطاء لرمز Pdf417 للباركود يتراوح بين level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، ويعني level8 أفضل تصحيح أخطاء مما ينتج صورة أكبر. |

### setLinked() {#setlinked}

يحدد أوضاع الربط مع باركودات GS1MicroPdf417 وMicroPdf417 وPdf417. مع رموز GS1MicroPdf417 يتم ترميز أوضاع “Linked” UCC/EAN-128 للأرقام 906 و907 و912 و913 و914 و915. مع رموز MicroPdf417 وPdf417 يتم ترميز علم الربط 918 للمكوّن الخطي المرتبط غير EAN.UCC. تُظهر هذه الأمثلة كيفية ترميز أوضاع “Linked” UCC/EAN-128 في GS1MicroPdf417 وعلم الربط (918) في باركودات MicroPdf417 وPdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر تكثيفًا في الأوضاع الخاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع 916 و917 في MicroPdf417. القيمة الافتراضية: MacroCharacters.None. تُظهر هذه الأمثلة كيفية ترميز أحرف الماكرو في MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

اسم المستلم لباركود MacroPdf417 (حقل اختياري). اسم المستلم لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل).

### setMacroPdf417Checksum() {#setmacropdf417checksum}

مجموع التحقق لباركود MacroPdf417 (حقل اختياري). مجموع التحقق لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل). يحتوي حقل مجموع التحقق على قيمة مجموع التحقق CRC 16‑بت (2 بايت) باستخدام كثير الحدود CCITT-16. x^16 + x^12 + x^5 + 1

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

معرفات تفسير القناة الموسعة. ينطبق على حقول النص Macro PDF417

### setMacroPdf417FileID() {#setmacropdf417fileid}

معرف الملف لباركود MacroPdf417 (حقل مطلوب). معرف الملف لباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المهيكل).

### setMacroPdf417FileName() {#setmacropdf417filename}

اسم ملف باركود MacroPdf417 (حقل اختياري). اسم ملف باركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل).

### setMacroPdf417FileSize() {#setmacropdf417filesize}

حجم ملف MacroPdf417 (حقل اختياري). حجم ملف MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل). يحتوي حقل حجم الملف على حجم الملف الأصلي بالكامل بالبايت.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

معرف الجزء لباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 حتى MacroSegmentsCount - 1. معرف الجزء لباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المهيكل).

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

عدد أجزاء باركود MacroPdf417 (حقل اختياري). عدد أجزاء باركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل).

### setMacroPdf417Sender() {#setmacropdf417sender}

اسم المرسل لباركود MacroPdf417 (حقل اختياري). اسم المرسل لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المهيكل).

### setMacroPdf417Terminator() {#setmacropdf417terminator}

يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة Terminator لMacro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PDF417.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

الطابع الزمني لباركود MacroPdf417 (حقل اختياري). الطابع الزمني لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المنظم)

### setPdf417CompactionMode() {#setpdf417compactionmode}

نوع ترميز Pdf417 لوضع الضغط للباركود. القيمة الافتراضية: Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. يتضمن التنفيذ الحالي جميع ترميزات مجموعات الأحرف المعروفة.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

يضبط مستوى تصحيح الأخطاء لرمز Pdf417 للباركود، ويتراوح بين level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، ويعني level8 أفضل تصحيح أخطاء مما ينتج صورة أكبر.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

يضبط اسم المستلم لباركود macro Pdf417.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

يضبط مجموع التحقق لباركود macro Pdf417.

| معامل | الوصف |
| --- | --- |
| القيمة | حقل المجموع الاختباري يحتوي على قيمة المجموع الاختباري CRC 16‑بت (2 بايت) باستخدام كثير الحدود CCITT-16. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

معرفات تفسير القناة الموسعة. ينطبق على حقول النص Macro PDF417

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

يضبط معرف الملف لباركود macro Pdf417. يُستخدم لـ MacroPdf417.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

يضبط اسم ملف باركود macro Pdf417.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

يضبط حجم ملف macro Pdf417.

| معامل | الوصف |
| --- | --- |
| القيمة | حقل حجم الملف يحتوي على حجم الملف بالكامل بالبايت. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

يضبط معرف الجزء لباركود macro Pdf417، والذي يبدأ من 0 حتى MacroSegmentsCount - 1.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

يضبط عدد أجزاء باركود macro Pdf417.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

يضبط اسم المرسل لباركود macro Pdf417.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة Terminator لMacro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PDF417.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

يضبط الطابع الزمني لباركود macro Pdf417.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

ما إذا كان نوع ترميز Pdf417 للباركود مقطّعًا (لتقليل المساحة).

### setReaderInitialization(value) {#setreaderinitialization}

يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ

| معامل | الوصف |
| --- | --- |
| القيمة |  |

### setRows() {#setrows}

عدد الصفوف.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

يحدد معرف (ID) باركود وضع الإلحاق المنظم DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

### setTruncate() {#settruncate}

ما إذا كان نوع رموز Pdf417 للباركود مقصوصًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. يتم إزالة مؤشر الصف الأيمن ونمط الإيقاف الأيمن في هذا الوضع.

### toString() {#tostring}

يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا الكائن Pdf417Parameters.

**Returns:** A string that represents this Pdf417Parameters.
