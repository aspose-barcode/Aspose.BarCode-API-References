---
title: "Code128EncodeMode"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "وضع الترميز لباركودات Code128."
type: docs
weight: 78
url: /ar/java/com.aspose.barcode.generation/code128encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Code128EncodeMode extends Enum<Code128EncodeMode>
```

وضع الترميز لباركودات Code128. مواصفات Code 128.

--------------------

> ```
> Thos code demonstrates how to generate code 128 with different encodings
>  
> 
>  //Generate code 128 with ISO 15417 encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO);
>  generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG);
> 
>  //Generate code 128 only with Codeset A encoding
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890");
>  generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A);
>  generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);
> ```
## الحقول

| حقل | الوصف |
| --- | --- |
| [AUTO](#AUTO) | ترميز نص الشيفرة في وضع ISO 15417 الكلاسيكي. |
| [CODE_A](#CODE-A) | ترميز نص الشيفرة فقط في مجموعة الرموز 128A. |
| [CODE_AB](#CODE-AB) | ترميز نص الشيفرة فقط في مجموعتي الرموز 128A و128B. |
| [CODE_AC](#CODE-AC) | ترميز نص الشيفرة فقط في مجموعتي الرموز 128A و128C. |
| [CODE_B](#CODE-B) | ترميز نص الشيفرة فقط في مجموعة الرموز 128B. |
| [CODE_BC](#CODE-BC) | ترميز نص الشيفرة فقط في مجموعتي الرموز 128B و128C. |
| [CODE_C](#CODE-C) | ترميز نص الشيفرة فقط في مجموعة الرموز 128C. |
## الدوال

| دالة | الوصف |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
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
| [valueOf(int value)](#valueOf-int-) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final Code128EncodeMode AUTO
```


ترميز نص الشيفرة في وضع ISO 15417 الكلاسيكي. يجب استخدام هذا الوضع في جميع الحالات العادية.

### CODE_A {#CODE-A}
```
public static final Code128EncodeMode CODE_A
```


ترميز نص الشيفرة فقط في مجموعة الرموز 128A.

### CODE_AB {#CODE-AB}
```
public static final Code128EncodeMode CODE_AB
```


ترميز نص الشيفرة فقط في مجموعتي الرموز 128A و128B.

### CODE_AC {#CODE-AC}
```
public static final Code128EncodeMode CODE_AC
```


ترميز نص الشيفرة فقط في مجموعتي الرموز 128A و128C.

### CODE_B {#CODE-B}
```
public static final Code128EncodeMode CODE_B
```


ترميز نص الشيفرة فقط في مجموعة الرموز 128B.

### CODE_BC {#CODE-BC}
```
public static final Code128EncodeMode CODE_BC
```


ترميز نص الشيفرة فقط في مجموعتي الرموز 128B و128C.

### CODE_C {#CODE-C}
```
public static final Code128EncodeMode CODE_C
```


ترميز نص الشيفرة فقط في مجموعة الرموز 128C.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
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
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static Code128EncodeMode fromValue(int value)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
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
### valueOf(int value) {#valueOf-int-}
```
public static Code128EncodeMode valueOf(int value)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Code128EncodeMode valueOf(String name)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[Code128EncodeMode](../../com.aspose.barcode.generation/code128encodemode)
### values() {#values--}
```
public static Code128EncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.Code128EncodeMode[]
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

