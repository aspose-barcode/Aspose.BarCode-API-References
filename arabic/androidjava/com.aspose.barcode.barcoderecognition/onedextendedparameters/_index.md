---
title: OneDExtendedParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يخزن بيانات خاصة لباركود 1D المعترف به مثل نص الرمز المنفصل ومجموع التحقق
type: docs
weight: 39
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/onedextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class OneDExtendedParameters extends BaseExtendedParameters
```

يخزن بيانات خاصة لباركود 1D المعترف به مثل نص الرمز المنفصل ومجموع التحقق

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
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كان هذا المثال مساويًا لقيمة OneDExtendedParameters المحددة. |
| [getCheckSum()](#getCheckSum--) | يحصل على قيمة التحقق للباركودات أحادية الأبعاد. |
| [getClass()](#getClass--) |  |
| [getValue()](#getValue--) | يحصل على نص الشيفرة للباركودات أحادية الأبعاد بدون قيمة التحقق. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع المعلمات لها القيم الافتراضية فقط. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يعيد تمثيل نصي قابل للقراءة للإنسان لهذا OneDExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كان هذا المثال مساويًا لقيمة OneDExtendedParameters المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذا الكائن. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### getCheckSum() {#getCheckSum--}
```
public String getCheckSum()
```


يحصل على قيمة التحقق للباركودات أحادية الأبعاد.

القيمة: قيمة التحقق للباركود أحادي الأبعاد.

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


يحصل على نص الشيفرة للباركودات أحادية الأبعاد بدون قيمة التحقق.

القيمة: نص الشيفرة للباركودات أحادية الأبعاد بدون قيمة التحقق.

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


يعيد تمثيل نصي قابل للقراءة للإنسان لهذا OneDExtendedParameters.

**Returns:**
java.lang.String - سلسلة تمثل هذا OneDExtendedParameters.
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

