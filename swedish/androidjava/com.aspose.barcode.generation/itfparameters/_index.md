---
title: "ITFParameters"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "ITF-parametrar."
type: docs
weight: 50
url: /sv/androidjava/com.aspose.barcode.generation/itfparameters/
---
**Inheritance:**
java.lang.Object
```
public class ITFParameters
```

ITF-parametrar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBorderThickness()](#getBorderThickness--) | Hämtar tjockleken på en ITF‑kant (bärarbjälke) i enhetsvärde. |
| [getBorderType()](#getBorderType--) | Kanttyp för ITF-streckkod. |
| [getClass()](#getClass--) |  |
| [getQuietZoneCoef()](#getQuietZoneCoef--) | Storlek på de tysta zonerna i xDimension. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBorderThickness(Unit value)](#setBorderThickness-com.aspose.barcode.generation.Unit-) | Ställer in en ITF-kant (bärare) tjocklek i enhetsvärde. |
| [setBorderType(ITF14BorderType value)](#setBorderType-com.aspose.barcode.generation.ITF14BorderType-) | Kanttyp för ITF-streckkod. |
| [setQuietZoneCoef(int value)](#setQuietZoneCoef-int-) | Storlek på de tysta zonerna i xDimension. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [ITFParameters](../../com.aspose.barcode.generation/itfparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBorderThickness() {#getBorderThickness--}
```
public final Unit getBorderThickness()
```


Hämtar en ITF-kant (bärare) tjocklek i enhetsvärde. Standardvärde: 12pt.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - an ITF border (bearer bar) thickness in Unit value.
### getBorderType() {#getBorderType--}
```
public final ITF14BorderType getBorderType()
```


Kanttyp för ITF-streckkod. Standardvärde: ITF14BorderType.Bar.

**Returns:**
[ITF14BorderType](../../com.aspose.barcode.generation/itf14bordertype)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getQuietZoneCoef() {#getQuietZoneCoef--}
```
public final int getQuietZoneCoef()
```


Storlek på de tysta zonerna i xDimension. Standardvärde: 10, vilket betyder att om xDimension = 2px så blir de tysta zonerna 20px.

**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
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




### setBorderThickness(Unit value) {#setBorderThickness-com.aspose.barcode.generation.Unit-}
```
public final void setBorderThickness(Unit value)
```


Ställer in en ITF-kant (bärare) tjocklek i enhetsvärde. Standardvärde: 12pt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | en ITF-kant (bärare) tjocklek i enhetsvärde. |

### setBorderType(ITF14BorderType value) {#setBorderType-com.aspose.barcode.generation.ITF14BorderType-}
```
public final void setBorderType(ITF14BorderType value)
```


Kanttyp för ITF-streckkod. Standardvärde: ITF14BorderType.Bar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ITF14BorderType](../../com.aspose.barcode.generation/itf14bordertype) |  |

### setQuietZoneCoef(int value) {#setQuietZoneCoef-int-}
```
public final void setQuietZoneCoef(int value)
```


Storlek på de tysta zonerna i xDimension. Standardvärde: 10, vilket betyder att om xDimension = 2px så blir de tysta zonerna 20px.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta [ITFParameters](../../com.aspose.barcode.generation/itfparameters).

**Returns:**
java.lang.String - En sträng som representerar detta [ITFParameters](../../com.aspose.barcode.generation/itfparameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

