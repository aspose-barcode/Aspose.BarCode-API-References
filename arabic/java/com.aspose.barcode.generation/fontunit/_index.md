---
title: "FontUnit"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "يحدد تنسيقًا معينًا للنص بما في ذلك حجم الخط ونمط الخصائص حيث يكون الحجم في خاصية قيمة الوحدة."
type: docs
weight: 42
url: /ar/java/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

يحدد تنسيقًا معينًا للنص، بما في ذلك نوع الخط والحجم وسمات النمط حيث يكون الحجم في خاصية قيمة الوحدة.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | يحصل على اسم الخط لهذا Font. |
| [getSize()](#getSize--) | يحصل على حجم هذا FontUnit في قيمة الوحدة. |
| [getStyle()](#getStyle--) | يحصل على معلومات النمط لهذا FontUnit. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | يضبط اسم الخط لهذا Font. |
| [setStyle(int value)](#setStyle-int-) | يضبط معلومات النمط لهذا FontUnit. |
| [toString()](#toString--) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


يحصل على اسم الخط لهذا Font.

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public Unit getSize()
```


يحصل على حجم هذا FontUnit في قيمة الوحدة.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getStyle() {#getStyle--}
```
public int getStyle()
```


يحصل على معلومات النمط لهذا FontUnit.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


يضبط اسم الخط لهذا Font.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


يضبط معلومات النمط لهذا FontUnit.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

