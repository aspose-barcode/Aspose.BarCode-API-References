---
title: Enhet
second_title: Aspose.BarCode for Android via Java API-referens
description: Anger storleksvärdet i olika enheter Pixel Inches etc..
type: docs
weight: 69
url: /sv/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Anger storleksvärdet i olika enheter (Pixel, tum, etc.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om detta objekt och ett specificerat objekt, som också måste vara ett  Unit  objekt, har samma värde. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Hämtar storleksvärdet i dokumentenheter. |
| [getInches()](#getInches--) | Hämtar storleksvärdet i tum. |
| [getMillimeters()](#getMillimeters--) | Hämtar storleksvärdet i millimeter. |
| [getPixels()](#getPixels--) | Hämtar storleksvärdet i pixlar. |
| [getPoint()](#getPoint--) | Hämtar storleksvärdet i punkter. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Returnerar hashkoden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Ställer in storleksvärdet i dokumentenheter. |
| [setInches(float value)](#setInches-float-) | Ställer in storleksvärdet i tum. |
| [setMillimeters(float value)](#setMillimeters-float-) | Ställer in storleksvärdet i millimeter. |
| [setPixels(float value)](#setPixels-float-) | Ställer in storleksvärdet i pixlar. |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om detta objekt och ett specificerat objekt, som också måste vara ett  Unit  objekt, har samma värde.

**Parameters:**
| Parameter | Type | Beskrivning |
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


Hämtar storleksvärdet i dokumentenheter.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


Hämtar storleksvärdet i tum.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Hämtar storleksvärdet i millimeter.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Hämtar storleksvärdet i pixlar.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Hämtar storleksvärdet i punkter.

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


Returnerar hashkoden för detta objekt.

**Returns:**
int - En 32‑bitars signerad heltals‑hashkod.
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


Ställer in storleksvärdet i dokumentenheter.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Ställer in storleksvärdet i tum.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Ställer in storleksvärdet i millimeter.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Ställer in storleksvärdet i pixlar.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Sets size value in point.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

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
| Parameter | Type | Beskrivning |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

