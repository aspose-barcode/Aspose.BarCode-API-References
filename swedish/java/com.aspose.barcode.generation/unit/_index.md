---
title: "Unit"
second_title: "Aspose.BarCode för Java API-referens"
description: "Anger storleksvärdet i olika enheter Pixel Inches etc.."
type: docs
weight: 67
url: /sv/java/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Anger storleksvärdet i olika enheter (pixel, tum osv.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om detta objekt och ett angivet objekt, som också måste vara ett  Unit  objekt, har samma värde. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Hämtar storleksvärdet i dokumentenheter. |
| [getInches()](#getInches--) | Hämtar storleksvärdet i tum. |
| [getMillimeters()](#getMillimeters--) | Hämtar storleksvärdet i millimeter. |
| [getPixels()](#getPixels--) | Hämtar storleksvärdet i pixlar. |
| [getPoint()](#getPoint--) | Hämtar storleksvärdet i punkt. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Returnerar hashkoden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Ställer in storleksvärdet i dokumentenheter. |
| [setInches(float value)](#setInches-float-) | Ställer in storleksvärdet i tum. |
| [setMillimeters(float value)](#setMillimeters-float-) | Ställer in storleksvärdet i millimeter. |
| [setPixels(float value)](#setPixels-float-) | Ställer in storleksvärdet i pixlar. |
| [setPoint(float value)](#setPoint-float-) | Ställer in storleksvärdet i punkt. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av denna  Unit . |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om detta objekt och ett angivet objekt, som också måste vara ett  Unit  objekt, har samma värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den  Unit  att jämföra med detta objekt. |

**Returns:**
boolean - sant om obj är en  Unit  och dess värde är detsamma som detta objekt; annars falskt. Om obj är null returnerar metoden falskt.
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


Hämtar storleksvärdet i punkt.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Ställer in storleksvärdet i tum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Ställer in storleksvärdet i millimeter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Ställer in storleksvärdet i pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Ställer in storleksvärdet i punkt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av denna  Unit .

**Returns:**
java.lang.String - En sträng som representerar denna  Unit .
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

