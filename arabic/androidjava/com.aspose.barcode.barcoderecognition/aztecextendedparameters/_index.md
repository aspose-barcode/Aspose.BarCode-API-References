---
title: AztecExtendedParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يخزن البيانات الخاصة للباركود المعترف به من نوع Aztec
type: docs
weight: 12
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/aztecextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class AztecExtendedParameters extends BaseExtendedParameters
```

يخزن البيانات الخاصة للباركود المعترف به من نوع Aztec

--------------------

> ```
> This sample shows how to get Aztec raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.AZTEC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText());
>      System.out.println("Aztec barcode ID: " + result.getExtended.getAztec.getStructuredAppendBarcodeId());
>      System.out.println("Aztec barcodes count: " + result.getExtended.getAztec.getStructuredAppendBarcodesCount());
>      System.out.println("Aztec file ID: " + result.getExtended.getAztec.getStructuredAppendFileId());
>      System.out.println("Aztec is reader initialization: " + result.getExtended.getAztec.isReaderInitialization());
>  }
> ```
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة  AztecExtendedParameters  محددة. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | يحصل على معرف الباركود في وضع الإلحاق المهيكل Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | يحصل على عدد الباركودات في وضع الإلحاق المهيكل Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | يحصل على معرف الملف في وضع الإلحاق المهيكل Aztec. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع المعلمات لها القيم الافتراضية فقط. |
| [isReaderInitialization()](#isReaderInitialization--) | يشير إلى ما إذا كان يتم استخدام الشيفرة لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا  AztecExtendedParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة  AztecExtendedParameters  محددة.

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
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


يحصل على معرف الباركود في وضع الإلحاق المهيكل Aztec. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي 0.

القيمة: معرف الباركود في وضع الإلحاق المهيكل Aztec.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


يحصل على عدد الباركودات في وضع الإلحاق المهيكل Aztec. القيمة الافتراضية هي 0. يجب أن يكون العدد قيمة من 1 إلى 26.

القيمة: عدد الباركودات في وضع الإلحاق المهيكل Aztec.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public String getStructuredAppendFileId()
```


يحصل على معرف الملف في وضع الإلحاق المهيكل Aztec. القيمة الافتراضية هي سلسلة فارغة

القيمة: معرف الملف في وضع الإلحاق المهيكل Aztec.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - رمز تجزئة (hash code) عدد صحيح موقع 32 بت.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يفحص ما إذا كانت جميع المعلمات لها القيم الافتراضية فقط.

القيمة: يعيد  **true**  إذا كانت جميع المعلمات لها القيم الافتراضية فقط؛ وإلا،  **false** .

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


يشير إلى ما إذا كان يتم استخدام الشيفرة لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

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


يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا  AztecExtendedParameters .

**Returns:**
java.lang.String - سلسلة تمثل هذا  AztecExtendedParameters .
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

