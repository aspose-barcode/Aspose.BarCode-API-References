---
title: Pdf417ExtendedParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يخزن معلومات بيانات تعريفية لباركود MacroPdf417 المعترف به
type: docs
weight: 40
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

يخزن معلومات بيانات تعريفية لباركود MacroPdf417 المعترف به

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | إرجاع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة Pdf417ExtendedParameters محددة. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | اسم المستلم في Macro PDF417 (اختياري). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | قيمة التحقق في Macro PDF417 (اختياري). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | يحصل على معرف الملف للباركود، متاح فقط مع MacroPdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | اسم الملف في Macro PDF417 (اختياري). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | حجم الملف في Macro PDF417 (اختياري). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | يحصل على معرف الجزء للباركود، متاح فقط مع MacroPdf417. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | يحصل على عدد أجزاء باركود macro pdf417. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | اسم المرسل في Macro PDF417 (اختياري). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | يشير إلى ما إذا كان الجزء هو الجزء الأخير من ملف Macro PDF417. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | الطابع الزمني في Macro PDF417 (اختياري). |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [isCode128Emulation()](#isCode128Emulation--) | علامة تشير إلى أن باركود MicroPdf417 مشفر باستخدام كلمات شفرة محاكاة Code 128 رقم 908 أو 909 أو 910 أو 911. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع المعلمات لها القيم الافتراضية فقط. |
| [isLinked()](#isLinked--) | علامة تشير إلى أن الباركود يجب ربطه بباركود 1D. |
| [isReaderInitialization()](#isReaderInitialization--) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | إرجاع تمثيل نصي قابل للقراءة للإنسان لهذا Pdf417ExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


إرجاع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة Pdf417ExtendedParameters محددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذا الكائن. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


اسم المستلم في Macro PDF417 (اختياري).

**Returns:**
java.lang.String - اسم المستلم.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


قيمة التحقق في Macro PDF417 (اختياري).

**Returns:**
int - قيمة التحقق.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


يحصل على معرف الملف للباركود، متاح فقط مع MacroPdf417.

القيمة: معرف الملف لـ MacroPdf417

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


اسم الملف في Macro PDF417 (اختياري).

**Returns:**
java.lang.String - اسم الملف.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


حجم الملف في Macro PDF417 (اختياري).

**Returns:**
int - حجم الملف.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


يحصل على معرف الجزء للباركود، متاح فقط مع MacroPdf417.

القيمة: معرف الجزء للباركود.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


يحصل على عدد أجزاء باركود macro pdf417. القيمة الافتراضية هي -1.

القيمة: عدد الأجزاء.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


اسم المرسل في Macro PDF417 (اختياري).

**Returns:**
java.lang.String - اسم المرسل
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


يشير إلى ما إذا كان الجزء هو الجزء الأخير من ملف Macro PDF417.

**Returns:**
boolean - محدد النهاية.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


الطابع الزمني في Macro PDF417 (اختياري).

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - رمز تجزئة (hash code) عدد صحيح موقع 32 بت.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


علامة تشير إلى أن باركود MicroPdf417 مشفر باستخدام كلمات شفرة محاكاة Code 128 رقم 908 أو 909 أو 910 أو 911.

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يفحص ما إذا كانت جميع المعلمات لها القيم الافتراضية فقط.

القيمة: يعيد  **true**  إذا كانت جميع المعلمات لها القيم الافتراضية فقط؛ وإلا،  **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


علامة تشير إلى أن الباركود يجب ربطه بباركود 1D.

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

Value: Reader initialization flag

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




### toString() {#toString--}
```
public String toString()
```


إرجاع تمثيل نصي قابل للقراءة للإنسان لهذا Pdf417ExtendedParameters.

**Returns:**
java.lang.String - A string that represents this  Pdf417ExtendedParameters .
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

