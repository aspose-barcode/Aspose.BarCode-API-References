---
title: XDimensionMode
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: 
type: docs
weight: 58
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/xdimensionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum XDimensionMode extends Enum<XDimensionMode>
```

وضع التعرف الذي يحدد حجم (من 1 إلى ما لا نهاية) العنصر الأدنى للباركود: خلية المصفوفة أو الشريط.

--------------------

> ```
> This sample shows how to use XDimension mode
>   
>   BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println(result.getCodeText());
> ```
## الحقول

| حقل | الوصف |
| --- | --- |
| [AUTO](#AUTO) | قيمة XDimension يتم اكتشافها بواسطة الذكاء الاصطناعي (SVM). |
| [LARGE](#LARGE) | يكشف عن الباركودات ذات XDimension الكبيرة بجودة من BarcodeQuality تم التقاطها بكاميرات عالية الدقة. |
| [NORMAL](#NORMAL) | يكشف عن الباركودات ذات XDimension الكلاسيكية في 2 بكسل أو أكثر بجودة من BarcodeQuality أو باركودات عالية الجودة. |
| [SMALL](#SMALL) | يكشف عن الباركودات ذات XDimension الصغيرة في بكسل واحد أو أكثر بجودة من BarcodeQuality. |
| [USE_MINIMAL_X_DIMENSION](#USE-MINIMAL-X-DIMENSION) | يكشف عن الباركودات بحجم محدد في MinimalXDimension بجودة من BarcodeQuality. |
## Methods

| Method | الوصف |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final XDimensionMode AUTO
```


قيمة XDimension يتم اكتشافها بواسطة الذكاء الاصطناعي (SVM). في الوقت الحالي هي نفسها كـ Normal.

### LARGE {#LARGE}
```
public static final XDimensionMode LARGE
```


يكشف عن الباركودات ذات XDimension الكبيرة بجودة من BarcodeQuality تم التقاطها بكاميرات عالية الدقة.

### NORMAL {#NORMAL}
```
public static final XDimensionMode NORMAL
```


يكشف عن الباركودات ذات XDimension الكلاسيكية في 2 بكسل أو أكثر بجودة من BarcodeQuality أو باركودات عالية الجودة.

### SMALL {#SMALL}
```
public static final XDimensionMode SMALL
```


يكشف عن الباركودات ذات XDimension الصغيرة في بكسل واحد أو أكثر بجودة من BarcodeQuality.

### USE_MINIMAL_X_DIMENSION {#USE-MINIMAL-X-DIMENSION}
```
public static final XDimensionMode USE_MINIMAL_X_DIMENSION
```


يكشف عن الباركودات بحجم محدد في MinimalXDimension بجودة من BarcodeQuality.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static XDimensionMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static XDimensionMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
### values() {#values--}
```
public static XDimensionMode[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.XDimensionMode[]
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

