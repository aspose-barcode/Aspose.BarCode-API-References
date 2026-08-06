---
title: Unit
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يحدد قيمة الحجم بوحدات مختلفة مثل البكسل والبوصة إلخ..
type: docs
weight: 69
url: /ar/androidjava/com.aspose.barcode.generation/unit/
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
## Constructors

| Constructor | الوصف |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة والكائن المحدد، الذي يجب أن يكون أيضًا كائن  Unit ، لهما نفس القيمة. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | يحصل على قيمة الحجم بوحدات المستند. |
| [getInches()](#getInches--) | يحصل على قيمة الحجم بالبوصة. |
| [getMillimeters()](#getMillimeters--) | يحصل على قيمة الحجم بالمليمتر. |
| [getPixels()](#getPixels--) | يحصل على قيمة الحجم بالبكسل. |
| [getPoint()](#getPoint--) | يحصل على قيمة الحجم بالنقطة. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | يضبط قيمة الحجم بوحدات المستند. |
| [setInches(float value)](#setInches-float-) | يضبط قيمة الحجم بالبوصة. |
| [setMillimeters(float value)](#setMillimeters-float-) | يضبط قيمة الحجم بالمليمتر. |
| [setPixels(float value)](#setPixels-float-) | يضبط قيمة الحجم بالبكسل. |
| [setPoint(float value)](#setPoint-float-) | Sets size value in point. |
| [toString()](#toString--) | Returns a human-readable string representation of this  Unit . |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة والكائن المحدد، الذي يجب أن يكون أيضًا كائن  Unit ، لهما نفس القيمة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | The  Unit  to compare to this instance. |

**Returns:**
boolean - true if obj is a  Unit  and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.
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


يعيد رمز التجزئة لهذا الكائن.

**Returns:**
int - رمز تجزئة (hash code) عدد صحيح موقع 32 بت.
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
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


يضبط قيمة الحجم بالبوصة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


يضبط قيمة الحجم بالمليمتر.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


يضبط قيمة الحجم بالبكسل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Sets size value in point.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  Unit .

**Returns:**
java.lang.String - A string that represents this  Unit .
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| dpi | float |  |

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

