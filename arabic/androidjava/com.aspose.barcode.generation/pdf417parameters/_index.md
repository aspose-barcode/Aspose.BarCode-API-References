---
title: Pdf417Parameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: معلمات PDF417.
type: docs
weight: 60
url: /ar/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

معلمات PDF417. يحتوي على معلمات PDF417 وMacroPDF417 وMicroPDF417 وGS1MicroPdf417. يتطلب MacroPDF417 حقلين: Pdf417MacroFileID وPdf417MacroSegmentID. جميع الحقول الأخرى اختيارية. يتطلب MicroPDF417 في وضع الإلحاق المنظم (نفس وضع MacroPDF417) حقلين: Pdf417MacroFileID وPdf417MacroSegmentID. جميع الحقول الأخرى اختيارية.

تظهر هذه العينات كيفية تشفير أوضاع UCC/EAN-128 غير المرتبطة في GS1MicroPdf417

```

 [C#]
 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | عدد الأعمدة. |
| [getECIEncoding()](#getECIEncoding--) | معرفات تفسير القناة الموسعة. |
| [getEncodeMode()](#getEncodeMode--) | يحدد وضع تشفير Pdf417. |
| [getErrorLevel()](#getErrorLevel--) | يحصل على نوع ترميز Pdf417 لمستوى تصحيح الأخطاء لباركود، والذي يتراوح من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، ويعني level8 أفضل تصحيح أخطاء مما ينتج صورة أكبر. |
| [getMacroCharacters()](#getMacroCharacters--) | تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر كثافة في الأوضاع الخاصة. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | اسم المستلم لباركود MacroPdf417 (حقل اختياري). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | مجموع تحقق باركود MacroPdf417 (حقل اختياري). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | معرفات تفسير القناة الموسعة. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | معرف ملف باركود MacroPdf417 (حقل مطلوب). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | اسم ملف الباركود MacroPdf417 (حقل اختياري). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | حجم ملف MacroPdf417 (حقل اختياري). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | معرف الجزء (segment ID) للباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 إلى MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | عدد أقسام الباركود MacroPdf417 (حقل اختياري). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | اسم مرسل الباركود MacroPdf417 (حقل اختياري). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | يُستخدم لإخبار المشفر ما إذا كان يجب إضافة ماكرو PDF417 Terminator (كلمة الشيفرة 922) إلى الجزء. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | الطابع الزمني للباركود MacroPdf417 (حقل اختياري). |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | نوع ترميز Pdf417 لوضع الضغط في BarCode. |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | معرفات تفسير القناة الموسعة. |
| [getPdf417EncodeMode()](#getPdf417EncodeMode--) | يحدد وضع تشفير Pdf417. |
| [getPdf417ErrorLevel()](#getPdf417ErrorLevel--) | يحصل على نوع ترميز Pdf417 لمستوى تصحيح الأخطاء لباركود، والذي يتراوح من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، ويعني level8 أفضل تصحيح أخطاء مما ينتج صورة أكبر. |
| [getPdf417MacroAddressee()](#getPdf417MacroAddressee--) | اسم المستلم لباركود MacroPdf417 (حقل اختياري). |
| [getPdf417MacroChecksum()](#getPdf417MacroChecksum--) | مجموع تحقق باركود MacroPdf417 (حقل اختياري). |
| [getPdf417MacroECIEncoding()](#getPdf417MacroECIEncoding--) | معرفات تفسير القناة الموسعة. |
| [getPdf417MacroFileID()](#getPdf417MacroFileID--) | معرف ملف باركود MacroPdf417 (حقل مطلوب). |
| [getPdf417MacroFileName()](#getPdf417MacroFileName--) | اسم ملف الباركود MacroPdf417 (حقل اختياري). |
| [getPdf417MacroFileSize()](#getPdf417MacroFileSize--) | حجم ملف MacroPdf417 (حقل اختياري). |
| [getPdf417MacroSegmentID()](#getPdf417MacroSegmentID--) | معرف الجزء (segment ID) للباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 إلى MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getPdf417MacroSegmentsCount--) | عدد أقسام الباركود MacroPdf417 (حقل اختياري). |
| [getPdf417MacroSender()](#getPdf417MacroSender--) | اسم مرسل الباركود MacroPdf417 (حقل اختياري). |
| [getPdf417MacroTerminator()](#getPdf417MacroTerminator--) | يُستخدم لإخبار المشفر ما إذا كان يجب إضافة ماكرو PDF417 Terminator (كلمة الشيفرة 922) إلى الجزء. |
| [getPdf417MacroTimeStamp()](#getPdf417MacroTimeStamp--) | الطابع الزمني للباركود MacroPdf417 (حقل اختياري). |
| [getPdf417Truncate()](#getPdf417Truncate--) | ما إذا كان نوع ترميز Pdf417 في BarCode مقطوعًا (لتقليل المساحة). |
| [getRows()](#getRows--) | عدد الصفوف. |
| [getTruncate()](#getTruncate--) | ما إذا كان نوع ترميز Pdf417 في BarCode مقطوعًا (لتقليل المساحة). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير FNC1 في الوضع الثاني للأوضاع 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128. |
| [isLinked()](#isLinked--) | يحدد أوضاع الربط مع الباركودات GS1MicroPdf417 وMicroPdf417 وPdf417. مع ترميز GS1MicroPdf417 يتم ترميز الأوضاع 906، 907، 912، 913، 914، 915 “Linked” UCC/EAN-128. ومع ترميزات MicroPdf417 وPdf417 يتم ترميز علامة الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير FNC1 في الوضع الثاني للأوضاع 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128. |
| [setColumns(int value)](#setColumns-int-) | عدد الأعمدة. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | معرفات تفسير القناة الموسعة. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | يحدد وضع تشفير Pdf417. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | يضبط مستوى تصحيح الأخطاء لنوع ترميز Pdf417 في BarCode من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، وlevel8 يعني أفضل تصحيح أخطاء مما ينتج صورة أكبر. |
| [setLinked(boolean value)](#setLinked-boolean-) | يحدد أوضاع الربط مع الباركودات GS1MicroPdf417 وMicroPdf417 وPdf417. مع ترميز GS1MicroPdf417 يتم ترميز الأوضاع 906، 907، 912، 913، 914، 915 “Linked” UCC/EAN-128. ومع ترميزات MicroPdf417 وPdf417 يتم ترميز علامة الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر كثافة في الأوضاع الخاصة. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | اسم المستلم لباركود MacroPdf417 (حقل اختياري). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | مجموع تحقق باركود MacroPdf417 (حقل اختياري). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | معرفات تفسير القناة الموسعة. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | معرف ملف باركود MacroPdf417 (حقل مطلوب). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | اسم ملف الباركود MacroPdf417 (حقل اختياري). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | حجم ملف MacroPdf417 (حقل اختياري). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | معرف الجزء (segment ID) للباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 إلى MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | عدد أقسام الباركود MacroPdf417 (حقل اختياري). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | اسم مرسل الباركود MacroPdf417 (حقل اختياري). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | يُستخدم لإخبار المشفر ما إذا كان يجب إضافة ماكرو PDF417 Terminator (كلمة الشيفرة 922) إلى الجزء. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | الطابع الزمني للباركود MacroPdf417 (حقل اختياري). |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | نوع ترميز Pdf417 لوضع الضغط في BarCode. |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | معرفات تفسير القناة الموسعة. |
| [setPdf417EncodeMode(Pdf417EncodeMode value)](#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | يحدد وضع تشفير Pdf417. |
| [setPdf417ErrorLevel(Pdf417ErrorLevel value)](#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | يضبط مستوى تصحيح الأخطاء لنوع ترميز Pdf417 في BarCode من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، وlevel8 يعني أفضل تصحيح أخطاء مما ينتج صورة أكبر. |
| [setPdf417MacroAddressee(String value)](#setPdf417MacroAddressee-java.lang.String-) | اسم المستلم لباركود MacroPdf417 (حقل اختياري). |
| [setPdf417MacroChecksum(int value)](#setPdf417MacroChecksum-int-) | مجموع تحقق باركود MacroPdf417 (حقل اختياري). |
| [setPdf417MacroECIEncoding(int value)](#setPdf417MacroECIEncoding-int-) | معرفات تفسير القناة الموسعة. |
| [setPdf417MacroFileID(int value)](#setPdf417MacroFileID-int-) | معرف ملف باركود MacroPdf417 (حقل مطلوب). |
| [setPdf417MacroFileName(String value)](#setPdf417MacroFileName-java.lang.String-) | اسم ملف الباركود MacroPdf417 (حقل اختياري). |
| [setPdf417MacroFileSize(int value)](#setPdf417MacroFileSize-int-) | حجم ملف MacroPdf417 (حقل اختياري). |
| [setPdf417MacroSegmentID(int value)](#setPdf417MacroSegmentID-int-) | معرف الجزء (segment ID) للباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 إلى MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount(int value)](#setPdf417MacroSegmentsCount-int-) | عدد أقسام الباركود MacroPdf417 (حقل اختياري). |
| [setPdf417MacroSender(String value)](#setPdf417MacroSender-java.lang.String-) | اسم مرسل الباركود MacroPdf417 (حقل اختياري). |
| [setPdf417MacroTerminator(Pdf417MacroTerminator value)](#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | يُستخدم لإخبار المشفر ما إذا كان يجب إضافة ماكرو PDF417 Terminator (كلمة الشيفرة 922) إلى الجزء. |
| [setPdf417MacroTimeStamp(LocalDateTime value)](#setPdf417MacroTimeStamp-java.time.LocalDateTime-) | الطابع الزمني للباركود MacroPdf417 (حقل اختياري). |
| [setPdf417Truncate(boolean value)](#setPdf417Truncate-boolean-) | ما إذا كان نوع ترميز Pdf417 في BarCode مقطوعًا (لتقليل المساحة). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [setRows(int value)](#setRows-int-) | عدد الصفوف. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | ما إذا كان نوع ترميز Pdf417 في BarCode مقطوعًا (لتقليل المساحة). |
| [toString()](#toString--) | يعيد تمثيل سلسلة مقروءة للبشر لهذا [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


عدد الأعمدة.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


معرفات تفسير القناة الموسعة. تُستخدم لإخبار قارئ الباركود بتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. لا تُطبق على حقول نص Macro PDF417. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


يحدد وضع الترميز Pdf417. القيمة الافتراضية: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


يحصل على نوع ترميز Pdf417 لمستوى تصحيح الأخطاء لباركود، والذي يتراوح من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، ويعني level8 أفضل تصحيح أخطاء مما ينتج صورة أكبر.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر ضغطًا في الأوضاع الخاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع MicroPdf417 916 و917. القيمة الافتراضية: MacroCharacters.None.

تُظهر هذه العينات كيفية ترميز الأحرف الماكرو في MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


اسم المستلم للباركود MacroPdf417 (حقل اختياري). اسم المستلم للباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


مجموع تحقق (checksum) للباركود MacroPdf417 (حقل اختياري). مجموع تحقق (checksum) للباركود MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل مجموع التحقق على قيمة مجموع CRC 16‑bit (2 بايت) باستخدام كثير الحدود CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


معرفات تفسير القناة الموسعة. تُطبق على حقول نص Macro PDF417.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


معرف ملف الباركود MacroPdf417 (حقل مطلوب). معرف ملف الباركود MicroPDF417 (حقل مطلوب لوضع Structured Append).

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


اسم ملف الباركود MacroPdf417 (حقل اختياري). اسم ملف الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


حجم ملف MacroPdf417 (حقل اختياري). حجم ملف MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل حجم الملف على الحجم بالبايت للملف المصدر بالكامل.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


معرف الجزء (segment ID) للباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 إلى MacroSegmentsCount - 1. معرف الجزء (segment ID) للباركود MicroPDF417 (حقل مطلوب لوضع Structured Append).

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


عدد أقسام الباركود MacroPdf417 (حقل اختياري). عدد أقسام الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


اسم مرسل الباركود MacroPdf417 (حقل اختياري). اسم مرسل الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


يُستخدم لإخبار المشفر ما إذا كان يجب إضافة إنهاء Macro PDF417 (كلمة الترميز 922) إلى الجزء. يُطبق فقط على Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


طابع زمني لباركود MacroPdf417 (حقل اختياري). طابع زمني لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المُنظم)

**Returns:**
java.time.LocalDateTime
### getPdf417CompactionMode() {#getPdf417CompactionMode--}
```
public final Pdf417CompactionMode getPdf417CompactionMode()
```


نوع الترميز Pdf417 لوضع ضغط الباركود. القيمة الافتراضية: Pdf417CompactionMode.Auto.

**Returns:**
[Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode)
### getPdf417ECIEncoding() {#getPdf417ECIEncoding--}
```
public final int getPdf417ECIEncoding()
```


معرفات تفسير القناة الموسعة. تُستخدم لإخبار قارئ الباركود بتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. لا تُطبق على حقول نص Macro PDF417. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة.

**Returns:**
int
### getPdf417EncodeMode() {#getPdf417EncodeMode--}
```
public final Pdf417EncodeMode getPdf417EncodeMode()
```


يحدد وضع الترميز Pdf417. القيمة الافتراضية: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getPdf417ErrorLevel() {#getPdf417ErrorLevel--}
```
public final Pdf417ErrorLevel getPdf417ErrorLevel()
```


يحصل على نوع ترميز Pdf417 لمستوى تصحيح الأخطاء لباركود، والذي يتراوح من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، ويعني level8 أفضل تصحيح أخطاء مما ينتج صورة أكبر.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getPdf417MacroAddressee() {#getPdf417MacroAddressee--}
```
public final String getPdf417MacroAddressee()
```


اسم المستلم للباركود MacroPdf417 (حقل اختياري). اسم المستلم للباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroChecksum() {#getPdf417MacroChecksum--}
```
public final int getPdf417MacroChecksum()
```


مجموع تحقق (checksum) للباركود MacroPdf417 (حقل اختياري). مجموع تحقق (checksum) للباركود MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل مجموع التحقق على قيمة مجموع CRC 16‑bit (2 بايت) باستخدام كثير الحدود CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getPdf417MacroECIEncoding() {#getPdf417MacroECIEncoding--}
```
public final int getPdf417MacroECIEncoding()
```


معرفات تفسير القناة الموسعة. تُطبق على حقول نص Macro PDF417.

**Returns:**
int
### getPdf417MacroFileID() {#getPdf417MacroFileID--}
```
public final int getPdf417MacroFileID()
```


معرف ملف الباركود MacroPdf417 (حقل مطلوب). معرف ملف الباركود MicroPDF417 (حقل مطلوب لوضع Structured Append).

**Returns:**
int
### getPdf417MacroFileName() {#getPdf417MacroFileName--}
```
public final String getPdf417MacroFileName()
```


اسم ملف الباركود MacroPdf417 (حقل اختياري). اسم ملف الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroFileSize() {#getPdf417MacroFileSize--}
```
public final int getPdf417MacroFileSize()
```


حجم ملف MacroPdf417 (حقل اختياري). حجم ملف MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل حجم الملف على الحجم بالبايت للملف المصدر بالكامل.

**Returns:**
int
### getPdf417MacroSegmentID() {#getPdf417MacroSegmentID--}
```
public final int getPdf417MacroSegmentID()
```


معرف الجزء (segment ID) للباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 إلى MacroSegmentsCount - 1. معرف الجزء (segment ID) للباركود MicroPDF417 (حقل مطلوب لوضع Structured Append).

**Returns:**
int
### getPdf417MacroSegmentsCount() {#getPdf417MacroSegmentsCount--}
```
public final int getPdf417MacroSegmentsCount()
```


عدد أقسام الباركود MacroPdf417 (حقل اختياري). عدد أقسام الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Returns:**
int
### getPdf417MacroSender() {#getPdf417MacroSender--}
```
public final String getPdf417MacroSender()
```


اسم مرسل الباركود MacroPdf417 (حقل اختياري). اسم مرسل الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroTerminator() {#getPdf417MacroTerminator--}
```
public final Pdf417MacroTerminator getPdf417MacroTerminator()
```


يُستخدم لإخبار المشفر ما إذا كان يجب إضافة إنهاء Macro PDF417 (كلمة الترميز 922) إلى الجزء. يُطبق فقط على Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getPdf417MacroTimeStamp() {#getPdf417MacroTimeStamp--}
```
public final LocalDateTime getPdf417MacroTimeStamp()
```


طابع زمني لباركود MacroPdf417 (حقل اختياري). طابع زمني لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المُنظم)

**Returns:**
java.time.LocalDateTime
### getPdf417Truncate() {#getPdf417Truncate--}
```
public final boolean getPdf417Truncate()
```


ما إذا كان نوع الترميز Pdf417 للباركود مقصوصًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. يتم إزالة مؤشر الصف الأيمن ونمط الإيقاف الأيمن في هذا الوضع.

**Returns:**
boolean
### getRows() {#getRows--}
```
public final int getRows()
```


عدد الصفوف.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


ما إذا كان نوع الترميز Pdf417 للباركود مقصوصًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. يتم إزالة مؤشر الصف الأيمن ونمط الإيقاف الأيمن في هذا الوضع.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير FNC1 في الوضع الثاني للأوضاع 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128.

تُظهر هذه الأمثلة كيفية ترميز أوضاع محاكاة Code 128 مع FNC1 في الموضع الثاني وبدونه. بهذه الطريقة يمكن فك ترميز MicroPdf417 كباركود Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


يحدد أوضاع الربط مع الباركودات GS1MicroPdf417 وMicroPdf417 وPdf417. مع ترميز GS1MicroPdf417 يتم ترميز الأوضاع 906، 907، 912، 913، 914، 915 “Linked” UCC/EAN-128. ومع ترميزات MicroPdf417 وPdf417 يتم ترميز علامة الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC.

تُظهر هذه الأمثلة كيفية ترميز أوضاع \"Linked\" UCC/EAN-128 في GS1MicroPdf417 وعلم الربط (Linkage Flag) (918) في باركودات MicroPdf417 وPdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير FNC1 في الوضع الثاني للأوضاع 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128.

تُظهر هذه الأمثلة كيفية ترميز أوضاع محاكاة Code 128 مع FNC1 في الموضع الثاني وبدونه. بهذه الطريقة يمكن فك ترميز MicroPdf417 كباركود Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


عدد الأعمدة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


معرفات تفسير القناة الموسعة. تُستخدم لإخبار قارئ الباركود بتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. لا تُطبق على حقول نص Macro PDF417. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


يحدد وضع الترميز Pdf417. القيمة الافتراضية: Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


يضبط مستوى تصحيح الأخطاء لنوع ترميز Pdf417 في BarCode من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، وlevel8 يعني أفضل تصحيح أخطاء مما ينتج صورة أكبر.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | نوع الترميز Pdf417 لمستوى تصحيح الأخطاء للباركود يتراوح من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، ويعني level8 أفضل تصحيح أخطاء مما ينتج صورة أكبر. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


يحدد أوضاع الربط مع الباركودات GS1MicroPdf417 وMicroPdf417 وPdf417. مع ترميز GS1MicroPdf417 يتم ترميز الأوضاع 906، 907، 912، 913، 914، 915 “Linked” UCC/EAN-128. ومع ترميزات MicroPdf417 وPdf417 يتم ترميز علامة الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC.

تُظهر هذه الأمثلة كيفية ترميز أوضاع \"Linked\" UCC/EAN-128 في GS1MicroPdf417 وعلم الربط (Linkage Flag) (918) في باركودات MicroPdf417 وPdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر ضغطًا في الأوضاع الخاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع MicroPdf417 916 و917. القيمة الافتراضية: MacroCharacters.None.

تُظهر هذه العينات كيفية ترميز الأحرف الماكرو في MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


اسم المستلم للباركود MacroPdf417 (حقل اختياري). اسم المستلم للباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


مجموع تحقق (checksum) للباركود MacroPdf417 (حقل اختياري). مجموع تحقق (checksum) للباركود MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل مجموع التحقق على قيمة مجموع CRC 16‑bit (2 بايت) باستخدام كثير الحدود CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


معرفات تفسير القناة الموسعة. تُطبق على حقول نص Macro PDF417.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


معرف ملف الباركود MacroPdf417 (حقل مطلوب). معرف ملف الباركود MicroPDF417 (حقل مطلوب لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


اسم ملف الباركود MacroPdf417 (حقل اختياري). اسم ملف الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


حجم ملف MacroPdf417 (حقل اختياري). حجم ملف MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل حجم الملف على الحجم بالبايت للملف المصدر بالكامل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


معرف الجزء (segment ID) للباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 إلى MacroSegmentsCount - 1. معرف الجزء (segment ID) للباركود MicroPDF417 (حقل مطلوب لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


عدد أقسام الباركود MacroPdf417 (حقل اختياري). عدد أقسام الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


اسم مرسل الباركود MacroPdf417 (حقل اختياري). اسم مرسل الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


يُستخدم لإخبار المشفر ما إذا كان يجب إضافة إنهاء Macro PDF417 (كلمة الترميز 922) إلى الجزء. يُطبق فقط على Macro PDF417.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


طابع زمني لباركود MacroPdf417 (حقل اختياري). طابع زمني لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المُنظم)

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.time.LocalDateTime |  |

### setPdf417CompactionMode(Pdf417CompactionMode value) {#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-}
```
public final void setPdf417CompactionMode(Pdf417CompactionMode value)
```


نوع الترميز Pdf417 لوضع ضغط الباركود. القيمة الافتراضية: Pdf417CompactionMode.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode) |  |

### setPdf417ECIEncoding(int value) {#setPdf417ECIEncoding-int-}
```
public final void setPdf417ECIEncoding(int value)
```


معرفات تفسير القناة الموسعة. تُستخدم لإخبار قارئ الباركود بتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. لا تُطبق على حقول نص Macro PDF417. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPdf417EncodeMode(Pdf417EncodeMode value) {#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setPdf417EncodeMode(Pdf417EncodeMode value)
```


يحدد وضع الترميز Pdf417. القيمة الافتراضية: Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setPdf417ErrorLevel(Pdf417ErrorLevel value) {#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setPdf417ErrorLevel(Pdf417ErrorLevel value)
```


يضبط مستوى تصحيح الأخطاء لنوع ترميز Pdf417 في BarCode من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، وlevel8 يعني أفضل تصحيح أخطاء مما ينتج صورة أكبر.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | نوع الترميز Pdf417 لمستوى تصحيح الأخطاء للباركود يتراوح من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، ويعني level8 أفضل تصحيح أخطاء مما ينتج صورة أكبر. |

### setPdf417MacroAddressee(String value) {#setPdf417MacroAddressee-java.lang.String-}
```
public final void setPdf417MacroAddressee(String value)
```


اسم المستلم للباركود MacroPdf417 (حقل اختياري). اسم المستلم للباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPdf417MacroChecksum(int value) {#setPdf417MacroChecksum-int-}
```
public final void setPdf417MacroChecksum(int value)
```


مجموع تحقق (checksum) للباركود MacroPdf417 (حقل اختياري). مجموع تحقق (checksum) للباركود MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل مجموع التحقق على قيمة مجموع CRC 16‑bit (2 بايت) باستخدام كثير الحدود CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPdf417MacroECIEncoding(int value) {#setPdf417MacroECIEncoding-int-}
```
public final void setPdf417MacroECIEncoding(int value)
```


معرفات تفسير القناة الموسعة. تُطبق على حقول نص Macro PDF417.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPdf417MacroFileID(int value) {#setPdf417MacroFileID-int-}
```
public final void setPdf417MacroFileID(int value)
```


معرف ملف الباركود MacroPdf417 (حقل مطلوب). معرف ملف الباركود MicroPDF417 (حقل مطلوب لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPdf417MacroFileName(String value) {#setPdf417MacroFileName-java.lang.String-}
```
public final void setPdf417MacroFileName(String value)
```


اسم ملف الباركود MacroPdf417 (حقل اختياري). اسم ملف الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPdf417MacroFileSize(int value) {#setPdf417MacroFileSize-int-}
```
public final void setPdf417MacroFileSize(int value)
```


حجم ملف MacroPdf417 (حقل اختياري). حجم ملف MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل حجم الملف على الحجم بالبايت للملف المصدر بالكامل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPdf417MacroSegmentID(int value) {#setPdf417MacroSegmentID-int-}
```
public final void setPdf417MacroSegmentID(int value)
```


معرف الجزء (segment ID) للباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 إلى MacroSegmentsCount - 1. معرف الجزء (segment ID) للباركود MicroPDF417 (حقل مطلوب لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPdf417MacroSegmentsCount(int value) {#setPdf417MacroSegmentsCount-int-}
```
public final void setPdf417MacroSegmentsCount(int value)
```


عدد أقسام الباركود MacroPdf417 (حقل اختياري). عدد أقسام الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setPdf417MacroSender(String value) {#setPdf417MacroSender-java.lang.String-}
```
public final void setPdf417MacroSender(String value)
```


اسم مرسل الباركود MacroPdf417 (حقل اختياري). اسم مرسل الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPdf417MacroTerminator(Pdf417MacroTerminator value) {#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setPdf417MacroTerminator(Pdf417MacroTerminator value)
```


يُستخدم لإخبار المشفر ما إذا كان يجب إضافة إنهاء Macro PDF417 (كلمة الترميز 922) إلى الجزء. يُطبق فقط على Macro PDF417.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setPdf417MacroTimeStamp(LocalDateTime value) {#setPdf417MacroTimeStamp-java.time.LocalDateTime-}
```
public final void setPdf417MacroTimeStamp(LocalDateTime value)
```


طابع زمني لباركود MacroPdf417 (حقل اختياري). طابع زمني لباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المُنظم)

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.time.LocalDateTime |  |

### setPdf417Truncate(boolean value) {#setPdf417Truncate-boolean-}
```
public final void setPdf417Truncate(boolean value)
```


ما إذا كان نوع الترميز Pdf417 للباركود مقصوصًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. يتم إزالة مؤشر الصف الأيمن ونمط الإيقاف الأيمن في هذا الوضع.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


عدد الصفوف.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


ما إذا كان نوع الترميز Pdf417 للباركود مقصوصًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. يتم إزالة مؤشر الصف الأيمن ونمط الإيقاف الأيمن في هذا الوضع.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### toString() {#toString--}
```
public String toString()
```


يعيد تمثيل سلسلة مقروءة للبشر لهذا [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

