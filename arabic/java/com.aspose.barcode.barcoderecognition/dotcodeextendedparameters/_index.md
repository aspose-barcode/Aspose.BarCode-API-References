---
title: "DotCodeExtendedParameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "يخزن بيانات خاصة لرمز DotCode المعترف به"
type: docs
weight: 31
url: /ar/java/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

يخزن بيانات خاصة لرمز DotCode المعترف به

يعرض هذا المثال كيفية الحصول على القيم الأولية لـ DotCode

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");
 
 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) المحددة. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | يحصل على معرف وضع الإلحاق المهيكل لباركود DotCode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | يحصل على عدد باركودات وضع الإلحاق المهيكل ل DotCode. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية. |
| [isReaderInitialization()](#isReaderInitialization--) | يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يعيد تمثيلًا نصيًا قابلًا للقراءة البشرية لهذا [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) المحددة.

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
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


يحصل على معرف باركود وضع الإلحاق المهيكل ل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو مساويًا لعدد الباركودات. القيمة الافتراضية هي -1.

القيمة: معرف باركود وضع الإلحاق المهيكل ل DotCode.

**Returns:**
int - معرف باركود وضع الإلحاق المهيكل ل DotCode.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


يحصل على عدد باركودات وضع الإلحاق المهيكل ل DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

القيمة: عدد شريط الكود DotCode في وضع الإلحاق المهيكل.

**Returns:**
int - عدد شفرات DotCode في وضع الإلحاق المهيكل.
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
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
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


يعيد تمثيلًا نصيًا قابلًا للقراءة البشرية لهذا [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).
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

