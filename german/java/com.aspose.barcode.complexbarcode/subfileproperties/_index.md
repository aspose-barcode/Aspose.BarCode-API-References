---
title: "USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "USA DL-Subdateieigenschaften Versatz und Länge werden automatisch festgelegt."
type: docs
weight: 12
url: /de/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

USA‑DL-Unterdateieigenschaften, Offset und Länge werden automatisch gesetzt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
| [SubfileProperties()](#SubfileProperties--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Diese Bytes enthalten einen 4‑stelligen numerischen Wert, der die Länge der Subdatei in Bytes angibt. Der Segmentterminator muss bei der Berechnung der Länge der Subdatei einbezogen werden. Ein Segmentterminator = 1. |
| [getOffset()](#getOffset--) | 4‑stelliger numerischer Wert, der die Anzahl der Bytes vom Anfang der Datei bis zu dem Ort angibt, an dem die zu der jeweiligen Subdatei gehörenden Daten liegen. Das erste Byte in der Datei befindet sich bei Offset 0. |
| [getType()](#getType--) | 2‑Byte‑Typ der Subdatei, z. B. "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Diese Bytes enthalten einen 4‑stelligen numerischen Wert, der die Länge der Subdatei in Bytes angibt. Der Segmentterminator muss bei der Berechnung der Länge der Subdatei einbezogen werden. Ein Segmentterminator = 1. |
| [setOffset(int value)](#setOffset-int-) | 4‑stelliger numerischer Wert, der die Anzahl der Bytes vom Anfang der Datei bis zu dem Ort angibt, an dem die zu der jeweiligen Subdatei gehörenden Daten liegen. Das erste Byte in der Datei befindet sich bei Offset 0. |
| [setType(String value)](#setType-java.lang.String-) | 2‑Byte‑Typ der Subdatei, z. B. "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | java.lang.String |  |

### SubfileProperties() {#SubfileProperties--}
```
public SubfileProperties()
```


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


4 Diese Bytes enthalten einen 4‑stelligen numerischen Wert, der die Länge der Subdatei in Bytes angibt. Der Segmentterminator muss bei der Berechnung der Länge der Subdatei einbezogen werden. Ein Segmentterminator = 1. Jede Subdatei muss mit dem zweistelligen Subdatei‑Typ beginnen und diese beiden Zeichen müssen ebenfalls in die Länge einbezogen werden.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4‑stelliger numerischer Wert, der die Anzahl der Bytes vom Anfang der Datei bis zu dem Ort angibt, an dem die zu der jeweiligen Subdatei gehörenden Daten liegen. Das erste Byte in der Datei befindet sich bei Offset 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


2‑Byte‑Typ der Subdatei, z. B. "DL"

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


4 Diese Bytes enthalten einen 4‑stelligen numerischen Wert, der die Länge der Subdatei in Bytes angibt. Der Segmentterminator muss bei der Berechnung der Länge der Subdatei einbezogen werden. Ein Segmentterminator = 1. Jede Subdatei muss mit dem zweistelligen Subdatei‑Typ beginnen und diese beiden Zeichen müssen ebenfalls in die Länge einbezogen werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4‑stelliger numerischer Wert, der die Anzahl der Bytes vom Anfang der Datei bis zu dem Ort angibt, an dem die zu der jeweiligen Subdatei gehörenden Daten liegen. Das erste Byte in der Datei befindet sich bei Offset 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


2‑Byte‑Typ der Subdatei, z. B. "DL"

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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

