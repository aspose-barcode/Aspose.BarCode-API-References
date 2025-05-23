---
title: Unit
second_title: Aspose.BarCode for Java API Reference
description: Specifies the size value in different units Pixel Inches etc..
type: docs
weight: 69
url: /java/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Specifies the size value in different units (Pixel, Inches, etc.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance and a specified object, which must also be a  Unit  object, have the same value. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Gets size value in document units. |
| [getInches()](#getInches--) | Gets size value in inches. |
| [getMillimeters()](#getMillimeters--) | Gets size value in millimeters. |
| [getPixels()](#getPixels--) | Gets size value in pixels. |
| [getPoint()](#getPoint--) | Gets size value in point. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Returns the hash code for this object. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Sets size value in document units. |
| [setInches(float value)](#setInches-float-) | Sets size value in inches. |
| [setMillimeters(float value)](#setMillimeters-float-) | Sets size value in millimeters. |
| [setPixels(float value)](#setPixels-float-) | Sets size value in pixels. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance and a specified object, which must also be a  Unit  object, have the same value.

**Parameters:**
| Parameter | Type | Description |
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


Gets size value in document units.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


Gets size value in inches.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Gets size value in millimeters.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Gets size value in pixels.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Gets size value in point.

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


Returns the hash code for this object.

**Returns:**
int - A 32-bit signed integer hash code.
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


Sets size value in document units.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Sets size value in inches.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Sets size value in millimeters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Sets size value in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Sets size value in point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

