---
title: USADriveIdCodetext.SubfileProperties
second_title: Aspose.BarCode for Android via Java API-referentie
description: USA DL subfile‑eigenschappen offset en lengte worden automatisch ingesteld.
type: docs
weight: 12
url: /nl/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

USA DL subbestandseigenschappen, offset en lengte worden automatisch ingesteld.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Deze bytes bevatten een 4‑cijferige numerieke waarde die de lengte van het Subfile in bytes specificeert.De segmentterminator moet worden meegenomen bij het berekenen van de lengte van het subfile.Een segmentterminator = 1. |
| [getOffset()](#getOffset--) | 4‑cijferige numerieke waarde die het aantal bytes aangeeft vanaf het begin van het bestand tot de locatie waar de gegevens die betrekking hebben op het specifieke sub‑file zich bevinden.De eerste byte in het bestand bevindt zich op offset 0. |
| [getType()](#getType--) | 2‑byte type van subfile, bijvoorbeeld "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Deze bytes bevatten een 4‑cijferige numerieke waarde die de lengte van het Subfile in bytes specificeert.De segmentterminator moet worden meegenomen bij het berekenen van de lengte van het subfile.Een segmentterminator = 1. |
| [setOffset(int value)](#setOffset-int-) | 4‑cijferige numerieke waarde die het aantal bytes aangeeft vanaf het begin van het bestand tot de locatie waar de gegevens die betrekking hebben op het specifieke sub‑file zich bevinden.De eerste byte in het bestand bevindt zich op offset 0. |
| [setType(String value)](#setType-java.lang.String-) | 2‑byte type van subfile, bijvoorbeeld "DL" |
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


4 Deze bytes bevatten een 4‑cijferige numerieke waarde die de lengte van het Subfile in bytes specificeert.De segmentterminator moet worden meegenomen bij het berekenen van de lengte van het subfile.Een segmentterminator = 1. Elk subfile moet beginnen met het twee‑karakter Subfile‑type en deze twee tekens moeten ook worden meegenomen in de lengte.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4‑cijferige numerieke waarde die het aantal bytes aangeeft vanaf het begin van het bestand tot de locatie waar de gegevens die betrekking hebben op het specifieke sub‑file zich bevinden.De eerste byte in het bestand bevindt zich op offset 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


2‑byte type van subfile, bijvoorbeeld "DL"

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


4 Deze bytes bevatten een 4‑cijferige numerieke waarde die de lengte van het Subfile in bytes specificeert.De segmentterminator moet worden meegenomen bij het berekenen van de lengte van het subfile.Een segmentterminator = 1. Elk subfile moet beginnen met het twee‑karakter Subfile‑type en deze twee tekens moeten ook worden meegenomen in de lengte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4‑cijferige numerieke waarde die het aantal bytes aangeeft vanaf het begin van het bestand tot de locatie waar de gegevens die betrekking hebben op het specifieke sub‑file zich bevinden.De eerste byte in het bestand bevindt zich op offset 0.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


2‑byte type van subfile, bijvoorbeeld "DL"

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

