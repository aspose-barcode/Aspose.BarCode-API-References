---
title: "OneDExtendedParameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "يخزن بيانات خاصة لرمز 1D المعترف به مثل نص الرمز المنفصل ومجموع التحقق"
type: docs
weight: 35
url: /ar/java/com.aspose.barcode.barcoderecognition/onedextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class OneDExtendedParameters extends BaseExtendedParameters
```

يخزن بيانات خاصة لرمز 1D المعترف به مثل نص الرمز المنفصل ومجموع التحقق

--------------------

> ```
> This sample shows how to get 1D barcode value and checksum
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.EAN_13);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Value: " + result.getExtended().getOneD().getValue());
>     System.out.println("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
>  }
> ```
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | إرجاع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة  OneDExtendedParameters  محددة. |
| [getCheckSum()](#getCheckSum--) | يحصل على قيمة التحقق للباركودات أحادية البعد (1D). |
| [getClass()](#getClass--) |  |
| [getValue()](#getValue--) | يحصل على نص الرمز للباركودات أحادية البعد (1D) بدون قيمة التحقق. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | إرجاع تمثيل نصي قابل للقراءة للإنسان لهذا OneDExtendedParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


إرجاع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة  OneDExtendedParameters  محددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذه المثيلة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كهذه المثيلة؛ وإلا،  **false** .
### getCheckSum() {#getCheckSum--}
```
public String getCheckSum()
```


يحصل على قيمة التحقق للباركودات أحادية البعد (1D).

القيمة: المجموع الاختباري للباركود 1D.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getValue() {#getValue--}
```
public String getValue()
```


يحصل على نص الرمز للباركودات أحادية البعد (1D) بدون قيمة التحقق.

القيمة: نص الشيفرة للباركودات 1D بدون المجموع الاختباري.

**Returns:**
java.lang.String
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


إرجاع تمثيل نصي قابل للقراءة للإنسان لهذا OneDExtendedParameters .

**Returns:**
java.lang.String - سلسلة تمثل هذا OneDExtendedParameters .
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

