---
title: "USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode for Java API-referentie"
description: "De offset en lengte van de subbestandseigenschappen van de Amerikaanse rijbewijs‑subfile worden automatisch ingesteld."
type: docs
weight: 12
url: /nl/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

Eigenschappen van het subbestand van het Amerikaanse rijbewijs, offset en lengte worden automatisch ingesteld.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
| [SubfileProperties()](#SubfileProperties--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Deze bytes bevatten een 4‑cijferige numerieke waarde die de lengte van het subbestand in bytes specificeert. De segmentterminator moet worden meegenomen bij het berekenen van de lengte van het subbestand. Een segmentterminator = 1. |
| [getOffset()](#getOffset--) | 4‑cijferige numerieke waarde die het aantal bytes aangeeft vanaf het begin van het bestand tot de locatie van de gegevens die bij het betreffende sub‑bestand horen. Het eerste byte in het bestand bevindt zich op offset 0. |
| [getType()](#getType--) | 2‑byte type van subbestand, bijvoorbeeld \"DL\" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Deze bytes bevatten een 4‑cijferige numerieke waarde die de lengte van het subbestand in bytes specificeert. De segmentterminator moet worden meegenomen bij het berekenen van de lengte van het subbestand. Een segmentterminator = 1. |
| [setOffset(int value)](#setOffset-int-) | 4‑cijferige numerieke waarde die het aantal bytes aangeeft vanaf het begin van het bestand tot de locatie van de gegevens die bij het betreffende sub‑bestand horen. Het eerste byte in het bestand bevindt zich op offset 0. |
| [setType(String value)](#setType-java.lang.String-) | 2‑byte type van subbestand, bijvoorbeeld \"DL\" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | java.lang.String |  |

### SubfileProperties() {#SubfileProperties--}
```
public SubfileProperties()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
### getLength() {#getLength--}
```
public final int getLength()
```


4 Deze bytes bevatten een 4‑cijferige numerieke waarde die de lengte van het subbestand in bytes specificeert. De segmentterminator moet worden meegenomen bij het berekenen van de lengte van het subbestand. Een segmentterminator = 1. Elk subbestand moet beginnen met het twee‑karakter Subfile‑type en deze twee tekens moeten ook in de lengte worden meegerekend.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4‑cijferige numerieke waarde die het aantal bytes aangeeft vanaf het begin van het bestand tot de locatie van de gegevens die bij het betreffende sub‑bestand horen. Het eerste byte in het bestand bevindt zich op offset 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


2‑byte type van subbestand, bijvoorbeeld \"DL\"

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
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




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 Deze bytes bevatten een 4‑cijferige numerieke waarde die de lengte van het subbestand in bytes specificeert. De segmentterminator moet worden meegenomen bij het berekenen van de lengte van het subbestand. Een segmentterminator = 1. Elk subbestand moet beginnen met het twee‑karakter Subfile‑type en deze twee tekens moeten ook in de lengte worden meegerekend.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4‑cijferige numerieke waarde die het aantal bytes aangeeft vanaf het begin van het bestand tot de locatie van de gegevens die bij het betreffende sub‑bestand horen. Het eerste byte in het bestand bevindt zich op offset 0.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


2‑byte type van subbestand, bijvoorbeeld \"DL\"

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

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

