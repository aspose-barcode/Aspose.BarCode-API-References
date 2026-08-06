---
title: Unit
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Gibt den Größenwert in verschiedenen Einheiten an, z. B. Pixel, Zoll usw..
type: docs
weight: 69
url: /de/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Gibt den Größenwert in verschiedenen Einheiten an (Pixel, Zoll usw.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Instanz und ein angegebenes Objekt, das ebenfalls ein  Unit  Objekt sein muss, denselben Wert haben. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Liefert den Größenwert in Dokumenteinheiten. |
| [getInches()](#getInches--) | Liefert den Größenwert in Zoll. |
| [getMillimeters()](#getMillimeters--) | Liefert den Größenwert in Millimetern. |
| [getPixels()](#getPixels--) | Liefert den Größenwert in Pixeln. |
| [getPoint()](#getPoint--) | Liefert den Größenwert in Punkten. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Gibt den Hashcode für dieses Objekt zurück. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Setzt den Größenwert in Dokumenteinheiten. |
| [setInches(float value)](#setInches-float-) | Setzt den Größenwert in Zoll. |
| [setMillimeters(float value)](#setMillimeters-float-) | Setzt den Größenwert in Millimetern. |
| [setPixels(float value)](#setPixels-float-) | Setzt den Größenwert in Pixeln. |
| [setPoint(float value)](#setPoint-float-) | Setzt den Größenwert in Punkt. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser  Unit  zurück. |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Instanz und ein angegebenes Objekt, das ebenfalls ein  Unit  Objekt sein muss, denselben Wert haben.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Die  Unit , die mit dieser Instanz verglichen wird. |

**Returns:**
boolean - true, wenn obj eine  Unit  ist und ihr Wert dem dieser Instanz entspricht; andernfalls false. Wenn obj null ist, gibt die Methode false zurück.
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


Liefert den Größenwert in Dokumenteinheiten.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


Liefert den Größenwert in Zoll.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Liefert den Größenwert in Millimetern.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Liefert den Größenwert in Pixeln.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Liefert den Größenwert in Punkten.

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


Gibt den Hashcode für dieses Objekt zurück.

**Returns:**
int - Ein 32-Bit vorzeichenbehafteter Ganzzahl-Hashcode.
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


Setzt den Größenwert in Dokumenteinheiten.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Setzt den Größenwert in Zoll.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Setzt den Größenwert in Millimetern.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Setzt den Größenwert in Pixeln.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Setzt den Größenwert in Punkt.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser  Unit  zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die diese  Unit  darstellt.
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

