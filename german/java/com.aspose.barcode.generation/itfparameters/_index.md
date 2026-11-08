---
title: "ITFParameters"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "ITF-Parameter."
type: docs
weight: 50
url: /de/java/com.aspose.barcode.generation/itfparameters/
---
**Inheritance:**
java.lang.Object
```
public class ITFParameters
```

ITF-Parameter.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBorderThickness()](#getBorderThickness--) | Gibt die Dicke einer ITF-Grenze (Bearer Bar) im Unit-Wert zurück. |
| [getBorderType()](#getBorderType--) | Grenztyp des ITF-Strichcodes. |
| [getClass()](#getClass--) |  |
| [getQuietZoneCoef()](#getQuietZoneCoef--) | Größe der Ruhebereiche in xDimension. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBorderThickness(Unit value)](#setBorderThickness-com.aspose.barcode.generation.Unit-) | Setzt die Dicke einer ITF-Grenze (Bearer Bar) im Unit-Wert. |
| [setBorderType(ITF14BorderType value)](#setBorderType-com.aspose.barcode.generation.ITF14BorderType-) | Grenztyp des ITF-Strichcodes. |
| [setQuietZoneCoef(int value)](#setQuietZoneCoef-int-) | Größe der Ruhebereiche in xDimension. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [ITFParameters](../../com.aspose.barcode.generation/itfparameters) zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolesch
### getBorderThickness() {#getBorderThickness--}
```
public final Unit getBorderThickness()
```


Liefert die Dicke des ITF-Rahmens (Trägerbalken) in Einheitwert. Standardwert: 12pt.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - an ITF border (bearer bar) thickness in Unit value.
### getBorderType() {#getBorderType--}
```
public final ITF14BorderType getBorderType()
```


Rahmentyp des ITF-Barcodes. Standardwert: ITF14BorderType.Bar.

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


Größe der Ruhebereiche in xDimension. Standardwert: 10, was bedeutet, dass bei xDimension = 2px die Ruhebereiche 20px betragen.

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


Setzt die Dicke eines ITF-Rahmens (Trägerbalken) in Einheitwert. Standardwert: 12pt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | eine ITF-Rahmen (Trägerbalken) Dicke im Einheitwert. |

### setBorderType(ITF14BorderType value) {#setBorderType-com.aspose.barcode.generation.ITF14BorderType-}
```
public final void setBorderType(ITF14BorderType value)
```


Rahmentyp des ITF-Barcodes. Standardwert: ITF14BorderType.Bar.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ITF14BorderType](../../com.aspose.barcode.generation/itf14bordertype) |  |

### setQuietZoneCoef(int value) {#setQuietZoneCoef-int-}
```
public final void setQuietZoneCoef(int value)
```


Größe der Ruhebereiche in xDimension. Standardwert: 10, was bedeutet, dass bei xDimension = 2px die Ruhebereiche 20px betragen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [ITFParameters](../../com.aspose.barcode.generation/itfparameters) zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses [ITFParameters](../../com.aspose.barcode.generation/itfparameters) darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

