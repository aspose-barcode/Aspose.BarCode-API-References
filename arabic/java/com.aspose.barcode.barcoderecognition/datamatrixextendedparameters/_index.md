---
title: "DataMatrixExtendedParameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "يخزن بيانات خاصة لرمز DataMatrix المعترف به"
type: docs
weight: 29
url: /ar/java/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

يخزن بيانات خاصة لرمز DataMatrix المعترف به

--------------------

> ```
> This sample shows how to get DataMatrix raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATA_MATRIX);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText);
>      System.out.println("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId());
>      System.out.println("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount());
>      System.out.println("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId());
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming));
>  }
> ```
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة  DataMatrixExtendedParameters  المحددة. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | يحصل على معرف وضع إلحاق منظم لباركود DataMatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | يحصل على عدد الباركودات في وضع الإلحاق المهيكل لـ DataMatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | يحصل على معرف وضع إلحاق منظم لباركود DataMatrix. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية. |
| [isReaderProgramming()](#isReaderProgramming--) | يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا DataMatrixExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يرجع قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة  DataMatrixExtendedParameters  المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذه المثيلة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كهذه المثيلة؛ وإلا،  **false** .
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


يحصل على معرّف الباركود في وضع الإلحاق المهيكل لـ DataMatrix. يبدأ المعرّف من 1 ويجب أن يكون أقل أو مساويًا لعدد الباركودات. القيمة الافتراضية هي -1.

القيمة: معرّف الباركود في وضع الإلحاق المهيكل لـ DataMatrix.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


يحصل على عدد الباركودات في وضع الإلحاق المهيكل لـ DataMatrix. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

القيمة: عدد الباركودات في وضع الإلحاق المهيكل لـ DataMatrix.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


يحصل على معرّف الباركود في وضع الإلحاق المهيكل لـ DataMatrix. يبدأ المعرّف من 1 ويجب أن يكون أقل أو مساويًا لعدد الباركودات. القيمة الافتراضية هي -1.

القيمة: معرّف الباركود في وضع الإلحاق المهيكل لـ DataMatrix.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز التجزئة لهذه المثيلة.

**Returns:**
int - رمز تجزئة عدد صحيح موقع 32-بت.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية.

القيمة: تُعيد  **true**  إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية؛ وإلا،  **false** .

**Returns:**
boolean
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
```


يشير إلى ما إذا كان الكود يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

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


يعيد تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا DataMatrixExtendedParameters.

**Returns:**
java.lang.String - سلسلة تمثل هذا DataMatrixExtendedParameters.
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

