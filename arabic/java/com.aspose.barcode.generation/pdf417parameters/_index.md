---
title: "Pdf417Parameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "معلمات PDF417."
type: docs
weight: 58
url: /ar/java/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

معلمات PDF417. يحتوي على معلمات PDF417 و MacroPDF417 و MicroPDF417 و GS1MicroPdf417. يتطلب MacroPDF417 حقلين: Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية. يتطلب MicroPDF417 في وضع الإلحاق المنظم (نفس وضع MacroPDF417) حقلين: Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية.

تظهر هذه العينات كيفية ترميز أوضاع UCC/EAN-128 غير المرتبطة في GS1MicroPdf417

```

 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | عدد الأعمدة. |
| [getECIEncoding()](#getECIEncoding--) | معرفات تفسير القناة الموسعة. |
| [getEncodeMode()](#getEncodeMode--) | يحدد وضع ترميز Pdf417. |
| [getErrorLevel()](#getErrorLevel--) | يحصل على نوع ترميز Pdf417 لمستوى تصحيح الأخطاء للباركود، يتراوح من level0 إلى level8، level0 يعني عدم وجود معلومات تصحيح الأخطاء، level8 يعني أفضل تصحيح الأخطاء مما ينتج صورة أكبر. |
| [getMacroCharacters()](#getMacroCharacters--) | يتم استخدام قيم Macro Characters 05 و 06 للحصول على ترميز أكثر كثافة في الأنماط الخاصة. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | اسم المستلم لباركود MacroPdf417 (حقل اختياري). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | مجموع التحقق لباركود MacroPdf417 (حقل اختياري). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | معرفات تفسير القناة الموسعة. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | معرف ملف الباركود MacroPdf417 (حقل مطلوب). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | اسم ملف باركود MacroPdf417 (حقل اختياري). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | حجم ملف MacroPdf417 (حقل اختياري). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | معرف مقطع الباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 حتى MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | عدد مقاطع الباركود MacroPdf417 (حقل اختياري). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | اسم المرسل لباركود MacroPdf417 (حقل اختياري). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | يُستخدم لإخبار المشفر ما إذا كان يجب إضافة Macro PDF417 Terminator (codeword 922) إلى الجزء. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | الطابع الزمني لباركود MacroPdf417 (حقل اختياري). |
| [getRows()](#getRows--) | عدد الصفوف. |
| [getTruncate()](#getTruncate--) | ما إذا كان نوع ترميز Pdf417 للباركود مقطوعًا (لتقليل المساحة). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير FNC1 في الوضع الثاني للأوضاع 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128. |
| [isLinked()](#isLinked--) | يحدد أوضاع الربط مع باركودات GS1MicroPdf417 و MicroPdf417 و Pdf417. مع ترميز GS1MicroPdf417 يتم تشفير 906، 907، 912، 913، 914، 915 \"Linked\" أوضاع UCC/EAN-128. مع ترميزات MicroPdf417 و Pdf417 يتم تشفير علم الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير FNC1 في الوضع الثاني للأوضاع 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128. |
| [setColumns(int value)](#setColumns-int-) | عدد الأعمدة. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | معرفات تفسير القناة الموسعة. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | يحدد وضع ترميز Pdf417. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | يضبط نوع ترميز Pdf417 لمستوى تصحيح الأخطاء للباركود، يتراوح من level0 إلى level8، level0 يعني عدم وجود معلومات تصحيح الأخطاء، level8 يعني أفضل تصحيح الأخطاء مما ينتج صورة أكبر. |
| [setLinked(boolean value)](#setLinked-boolean-) | يحدد أوضاع الربط مع باركودات GS1MicroPdf417 و MicroPdf417 و Pdf417. مع ترميز GS1MicroPdf417 يتم تشفير 906، 907، 912، 913، 914، 915 \"Linked\" أوضاع UCC/EAN-128. مع ترميزات MicroPdf417 و Pdf417 يتم تشفير علم الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | يتم استخدام قيم Macro Characters 05 و 06 للحصول على ترميز أكثر كثافة في الأنماط الخاصة. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | اسم المستلم لباركود MacroPdf417 (حقل اختياري). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | مجموع التحقق لباركود MacroPdf417 (حقل اختياري). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | معرفات تفسير القناة الموسعة. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | معرف ملف الباركود MacroPdf417 (حقل مطلوب). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | اسم ملف باركود MacroPdf417 (حقل اختياري). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | حجم ملف MacroPdf417 (حقل اختياري). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | معرف مقطع الباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 حتى MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | عدد مقاطع الباركود MacroPdf417 (حقل اختياري). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | اسم المرسل لباركود MacroPdf417 (حقل اختياري). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | يُستخدم لإخبار المشفر ما إذا كان يجب إضافة Macro PDF417 Terminator (codeword 922) إلى الجزء. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | الطابع الزمني لباركود MacroPdf417 (حقل اختياري). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [setRows(int value)](#setRows-int-) | عدد الصفوف. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | ما إذا كان نوع ترميز Pdf417 للباركود مقطوعًا (لتقليل المساحة). |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد.

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


معرفات تفسير القناة الموسعة. تُستخدم لإخبار قارئ الباركود بالتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. لا تُطبق على حقول نص Macro PDF417. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


يحصل على نوع ترميز Pdf417 لمستوى تصحيح الأخطاء للباركود، يتراوح من level0 إلى level8، level0 يعني عدم وجود معلومات تصحيح الأخطاء، level8 يعني أفضل تصحيح الأخطاء مما ينتج صورة أكبر.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


تُستخدم قيم Macro Characters 05 و06 للحصول على ترميز أكثر ضغطًا في أوضاع خاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع MicroPdf417 916 و917. القيمة الافتراضية: MacroCharacters.None.

تظهر هذه العينات كيفية ترميز الأحرف الماكرو في MicroPdf417

```

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
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


مجموع التحقق للباركود MacroPdf417 (حقل اختياري). مجموع التحقق للباركود MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل مجموع التحقق على قيمة مجموع التحقق CRC 16‑بت (2 بايت) باستخدام كثير الحدود CCITT-16. x^16 + x^12 + x^5 + 1

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


معرف ملف الباركود MacroPdf417 (حقل مطلوب). معرف ملف الباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المنظم)

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


معرف مقطع الباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 حتى MacroSegmentsCount - 1. معرف مقطع الباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المنظم)

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


عدد مقاطع الباركود MacroPdf417 (حقل اختياري). عدد مقاطع الباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المنظم)

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


اسم المرسل للباركود MacroPdf417 (حقل اختياري). اسم المرسل للباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة Terminator Macro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


الطابع الزمني للباركود MacroPdf417 (حقل اختياري). الطابع الزمني للباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Returns:**
java.time.LocalDateTime
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


ما إذا كان نوع ترميز Pdf417 للباركود مقصوصًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. يتم إزالة مؤشر الصف الأيمن ونمط الإيقاف الأيمن في هذا الوضع.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير FNC1 في الوضع الثاني للأوضاع 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128.

تظهر هذه العينات كيفية ترميز أوضاع محاكاة Code 128 مع FNC1 في الموضع الثاني وبدونه. بهذه الطريقة يمكن فك ترميز MicroPdf417 كباركود Code 128

```

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


يحدد أوضاع الربط مع باركودات GS1MicroPdf417 و MicroPdf417 و Pdf417. مع ترميز GS1MicroPdf417 يتم تشفير 906، 907، 912، 913، 914، 915 \"Linked\" أوضاع UCC/EAN-128. مع ترميزات MicroPdf417 و Pdf417 يتم تشفير علم الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC.

تظهر هذه العينات كيفية ترميز أوضاع \"Linked\" UCC/EAN-128 في GS1MicroPdf417 وعلم الربط (918) في باركودات MicroPdf417 و Pdf417

```

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


نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


يمكن استخدامه فقط مع MicroPdf417 ويشفّر أوضاع محاكاة Code 128. يمكنه تشفير FNC1 في الوضع الثاني للأوضاع 908 و909، كما يمكنه تشفير 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128.

تظهر هذه العينات كيفية ترميز أوضاع محاكاة Code 128 مع FNC1 في الموضع الثاني وبدونه. بهذه الطريقة يمكن فك ترميز MicroPdf417 كباركود Code 128

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
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


عدد الأعمدة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


معرفات تفسير القناة الموسعة. تُستخدم لإخبار قارئ الباركود بالتفاصيل حول المراجع المستخدمة لتشفير البيانات في الرمز. لا تُطبق على حقول نص Macro PDF417. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


يحدد وضع ترميز Pdf417. القيمة الافتراضية: Auto.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


يضبط نوع ترميز Pdf417 لمستوى تصحيح الأخطاء للباركود، يتراوح من level0 إلى level8، level0 يعني عدم وجود معلومات تصحيح الأخطاء، level8 يعني أفضل تصحيح الأخطاء مما ينتج صورة أكبر.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | نوع الترميز Pdf417 لمستوى تصحيح الأخطاء في BarCode يتراوح من level0 إلى level8، حيث يعني level0 عدم وجود معلومات تصحيح أخطاء، ويعني level8 أفضل تصحيح أخطاء مما ينتج صورة أكبر. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


يحدد أوضاع الربط مع باركودات GS1MicroPdf417 و MicroPdf417 و Pdf417. مع ترميز GS1MicroPdf417 يتم تشفير 906، 907، 912، 913، 914، 915 \"Linked\" أوضاع UCC/EAN-128. مع ترميزات MicroPdf417 و Pdf417 يتم تشفير علم الربط 918 إلى المكوّن الخطي المرتبط غير EAN.UCC.

تظهر هذه العينات كيفية ترميز أوضاع \"Linked\" UCC/EAN-128 في GS1MicroPdf417 وعلم الربط (918) في باركودات MicroPdf417 و Pdf417

```

 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked modes 906, 907 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());
 
```

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


تُستخدم قيم Macro Characters 05 و06 للحصول على ترميز أكثر ضغطًا في أوضاع خاصة. يمكن استخدامها فقط مع MicroPdf417 وتشفّر أوضاع MicroPdf417 916 و917. القيمة الافتراضية: MacroCharacters.None.

تظهر هذه العينات كيفية ترميز الأحرف الماكرو في MicroPdf417

```

```

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


اسم المستلم للباركود MacroPdf417 (حقل اختياري). اسم المستلم للباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


مجموع التحقق للباركود MacroPdf417 (حقل اختياري). مجموع التحقق للباركود MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل مجموع التحقق على قيمة مجموع التحقق CRC 16‑بت (2 بايت) باستخدام كثير الحدود CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


معرفات تفسير القناة الموسعة. تُطبق على حقول نص Macro PDF417.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


معرف ملف الباركود MacroPdf417 (حقل مطلوب). معرف ملف الباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المنظم)

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


اسم ملف الباركود MacroPdf417 (حقل اختياري). اسم ملف الباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


حجم ملف MacroPdf417 (حقل اختياري). حجم ملف MicroPDF417 (حقل اختياري لوضع Structured Append). يحتوي حقل حجم الملف على الحجم بالبايت للملف المصدر بالكامل.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


معرف مقطع الباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 حتى MacroSegmentsCount - 1. معرف مقطع الباركود MicroPDF417 (حقل مطلوب لوضع الإلحاق المنظم)

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


عدد مقاطع الباركود MacroPdf417 (حقل اختياري). عدد مقاطع الباركود MicroPDF417 (حقل اختياري لوضع الإلحاق المنظم)

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


اسم المرسل للباركود MacroPdf417 (حقل اختياري). اسم المرسل للباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


يُستخدم لإخبار المُشفّر ما إذا كان يجب إضافة Terminator Macro PDF417 (كلمة الشيفرة 922) إلى الجزء. يُطبق فقط على Macro PDF417.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


الطابع الزمني للباركود MacroPdf417 (حقل اختياري). الطابع الزمني للباركود MicroPDF417 (حقل اختياري لوضع Structured Append).

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


عدد الصفوف.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


ما إذا كان نوع ترميز Pdf417 للباركود مقصوصًا (لتقليل المساحة). يُعرف أيضًا باسم CompactPDF417. يتم إزالة مؤشر الصف الأيمن ونمط الإيقاف الأيمن في هذا الوضع.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

