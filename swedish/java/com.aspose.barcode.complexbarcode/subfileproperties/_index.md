---
title: "USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode för Java API-referens"
description: "USA DL-underfilens egenskaper för offset och längd sätts automatiskt."
type: docs
weight: 12
url: /sv/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

USA DL-underfilens egenskaper, offset och längd sätts automatiskt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
| [SubfileProperties()](#SubfileProperties--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Dessa byte innehåller ett 4-siffrigt numeriskt värde som specificerar subfilens längd i byte. Segmentavslutaren måste inkluderas vid beräkning av subfilens längd. En segmentavslutare = 1. |
| [getOffset()](#getOffset--) | 4-siffrigt numeriskt värde som specificerar antalet byte från filens början till där data relaterad till den specifika underfilen är placerad. Den första byten i filen ligger på offset 0. |
| [getType()](#getType--) | 2-byte typ av underfil, exempelvis \"DL\" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Dessa byte innehåller ett 4-siffrigt numeriskt värde som specificerar subfilens längd i byte. Segmentavslutaren måste inkluderas vid beräkning av subfilens längd. En segmentavslutare = 1. |
| [setOffset(int value)](#setOffset-int-) | 4-siffrigt numeriskt värde som specificerar antalet byte från filens början till där data relaterad till den specifika underfilen är placerad. Den första byten i filen ligger på offset 0. |
| [setType(String value)](#setType-java.lang.String-) | 2-byte typ av underfil, exempelvis \"DL\" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | java.lang.String |  |

### SubfileProperties() {#SubfileProperties--}
```
public SubfileProperties()
```


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


4 Dessa byte innehåller ett 4-siffrigt numeriskt värde som specificerar subfilens längd i byte. Segmentavslutaren måste inkluderas vid beräkning av subfilens längd. En segmentavslutare = 1. Varje underfil måste börja med den tvåtecken långa Subfile-typen och dessa två tecken måste också räknas med i längden.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4-siffrigt numeriskt värde som specificerar antalet byte från filens början till där data relaterad till den specifika underfilen är placerad. Den första byten i filen ligger på offset 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


2-byte typ av underfil, exempelvis \"DL\"

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


4 Dessa byte innehåller ett 4-siffrigt numeriskt värde som specificerar subfilens längd i byte. Segmentavslutaren måste inkluderas vid beräkning av subfilens längd. En segmentavslutare = 1. Varje underfil måste börja med den tvåtecken långa Subfile-typen och dessa två tecken måste också räknas med i längden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4-siffrigt numeriskt värde som specificerar antalet byte från filens början till där data relaterad till den specifika underfilen är placerad. Den första byten i filen ligger på offset 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


2-byte typ av underfil, exempelvis \"DL\"

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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

