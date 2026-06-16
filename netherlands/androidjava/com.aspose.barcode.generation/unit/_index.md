---
title: Unit
second_title: Aspose.BarCode for Android via Java API-referentie
description: Specificeert de groottewaarde in verschillende eenheden Pixel Inches enz..
type: docs
weight: 69
url: /nl/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Specificeert de groottewaarde in verschillende eenheden (pixel, inches, etc.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze instantie en een opgegeven object, dat ook een  Unit  object moet zijn, dezelfde waarde hebben. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Haalt de groottewaarde op in documenteenheden. |
| [getInches()](#getInches--) | Haalt de groottewaarde op in inches. |
| [getMillimeters()](#getMillimeters--) | Haalt de groottewaarde op in millimeters. |
| [getPixels()](#getPixels--) | Haalt de groottewaarde op in pixels. |
| [getPoint()](#getPoint--) | Haalt de groottewaarde op in punten. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor dit object. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Stelt de groottewaarde in in documenteenheden. |
| [setInches(float value)](#setInches-float-) | Stelt de groottewaarde in in inches. |
| [setMillimeters(float value)](#setMillimeters-float-) | Stelt de groottewaarde in in millimeters. |
| [setPixels(float value)](#setPixels-float-) | Stelt de groottewaarde in in pixels. |
| [setPoint(float value)](#setPoint-float-) | Stelt de groottewaarde in punten in. |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze  Unit . |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze instantie en een opgegeven object, dat ook een  Unit  object moet zijn, dezelfde waarde hebben.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De  Unit  om te vergelijken met deze instantie. |

**Returns:**
boolean - true als obj een  Unit  is en de waarde gelijk is aan deze instantie; anders false. Als obj null is, retourneert de methode false.
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


Haalt de groottewaarde op in documenteenheden.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


Haalt de groottewaarde op in inches.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Haalt de groottewaarde op in millimeters.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Haalt de groottewaarde op in pixels.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Haalt de groottewaarde op in punten.

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


Retourneert de hashcode voor dit object.

**Returns:**
int - Een 32-bits ondertekend geheel getal hashcode.
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


Stelt de groottewaarde in in documenteenheden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Stelt de groottewaarde in in inches.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Stelt de groottewaarde in in millimeters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Stelt de groottewaarde in in pixels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Stelt de groottewaarde in punten in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze  Unit .

**Returns:**
java.lang.String - Een tekenreeks die deze  Unit  vertegenwoordigt.
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

