---
title: "Unit"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "يحدد قيمة الحجم بوحدات مختلفة مثل Pixel و Inches وما إلى ذلك.."
type: docs
weight: 67
url: /ar/java/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

يحدد قيمة الحجم بوحدات مختلفة (بكسل، بوصات، إلخ).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان هذا الكائن والكيان المحدد، الذي يجب أن يكون أيضًا كائنًا من نوع  Unit ، لهما نفس القيمة. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | يحصل على قيمة الحجم بوحدات المستند. |
| [getInches()](#getInches--) | يحصل على قيمة الحجم بالبوصة. |
| [getMillimeters()](#getMillimeters--) | يحصل على قيمة الحجم بالمليمتر. |
| [getPixels()](#getPixels--) | يحصل على قيمة الحجم بالبكسل. |
| [getPoint()](#getPoint--) | يحصل على قيمة الحجم بالنقطة. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | يرجع رمز التجزئة لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | يضبط قيمة الحجم بوحدات المستند. |
| [setInches(float value)](#setInches-float-) | يضبط قيمة الحجم بالبوصة. |
| [setMillimeters(float value)](#setMillimeters-float-) | يضبط قيمة الحجم بالمليمتر. |
| [setPixels(float value)](#setPixels-float-) | يضبط قيمة الحجم بالبكسل. |
| [setPoint(float value)](#setPoint-float-) | يضبط قيمة الحجم بالنقطة. |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا  Unit . |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان هذا الكائن والكيان المحدد، الذي يجب أن يكون أيضًا كائنًا من نوع  Unit ، لهما نفس القيمة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ  Unit  للمقارنة مع هذا الكائن. |

**Returns:**
boolean - true إذا كان obj هو  Unit  وكانت قيمته هي نفسها هذا الكائن؛ وإلا false. إذا كان obj يساوي null، تُعيد الطريقة false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


يحصل على قيمة الحجم بوحدات المستند.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


يحصل على قيمة الحجم بالبوصة.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


يحصل على قيمة الحجم بالمليمتر.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


يحصل على قيمة الحجم بالبكسل.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


يحصل على قيمة الحجم بالنقطة.

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز التجزئة لهذا الكائن.

**Returns:**
int - رمز تجزئة عدد صحيح موقع 32-بت.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


يضبط قيمة الحجم بوحدات المستند.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


يضبط قيمة الحجم بالبوصة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


يضبط قيمة الحجم بالمليمتر.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


يضبط قيمة الحجم بالبكسل.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


يضبط قيمة الحجم بالنقطة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا  Unit .

**Returns:**
java.lang.String - سلسلة تمثل هذا  Unit .
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| dpi | float |  |

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

