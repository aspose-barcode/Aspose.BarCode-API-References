---
title: USADriveIdCodetext.SubfileProperties
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Die Offset- und Längeneigenschaften des USA-DL-Subfiles werden automatisch gesetzt.
type: docs
weight: 12
url: /de/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

USA-DL-Untertdateieigenschaften, Offset und Länge werden automatisch festgelegt.
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Diese Bytes enthalten einen 4-stelligen numerischen Wert, der die Länge des Subfiles in Bytes angibt. Der Segmentterminator muss bei der Berechnung der Subfile-Länge einbezogen werden. Ein Segmentterminator = 1. |
| [getOffset()](#getOffset--) | 4-stelliger numerischer Wert, der die Anzahl der Bytes vom Anfang der Datei bis zu dem Ort angibt, an dem die Daten der jeweiligen Subdatei gespeichert sind. Das erste Byte in der Datei befindet sich bei Offset 0. |
| [getType()](#getType--) | 2-Byte-Typ des Subfiles, z. B. \"DL\" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Diese Bytes enthalten einen 4-stelligen numerischen Wert, der die Länge des Subfiles in Bytes angibt. Der Segmentterminator muss bei der Berechnung der Subfile-Länge einbezogen werden. Ein Segmentterminator = 1. |
| [setOffset(int value)](#setOffset-int-) | 4-stelliger numerischer Wert, der die Anzahl der Bytes vom Anfang der Datei bis zu dem Ort angibt, an dem die Daten der jeweiligen Subdatei gespeichert sind. Das erste Byte in der Datei befindet sich bei Offset 0. |
| [setType(String value)](#setType-java.lang.String-) | 2-Byte-Typ des Subfiles, z. B. \"DL\" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Typ | java.lang.String |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
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


4 Diese Bytes enthalten einen 4-stelligen numerischen Wert, der die Länge des Subfiles in Bytes angibt. Der Segmentterminator muss bei der Berechnung der Subfile-Länge einbezogen werden. Ein Segmentterminator = 1. Jedes Subfile muss mit dem zweistelligen Subfile-Typ beginnen, und diese beiden Zeichen müssen ebenfalls in die Länge einbezogen werden.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4-stelliger numerischer Wert, der die Anzahl der Bytes vom Anfang der Datei bis zu dem Ort angibt, an dem die Daten der jeweiligen Subdatei gespeichert sind. Das erste Byte in der Datei befindet sich bei Offset 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


2-Byte-Typ des Subfiles, z. B. \"DL\"

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


4 Diese Bytes enthalten einen 4-stelligen numerischen Wert, der die Länge des Subfiles in Bytes angibt. Der Segmentterminator muss bei der Berechnung der Subfile-Länge einbezogen werden. Ein Segmentterminator = 1. Jedes Subfile muss mit dem zweistelligen Subfile-Typ beginnen, und diese beiden Zeichen müssen ebenfalls in die Länge einbezogen werden.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4-stelliger numerischer Wert, der die Anzahl der Bytes vom Anfang der Datei bis zu dem Ort angibt, an dem die Daten der jeweiligen Subdatei gespeichert sind. Das erste Byte in der Datei befindet sich bei Offset 0.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


2-Byte-Typ des Subfiles, z. B. \"DL\"

**Parameters:**
| Parameter | Type | Beschreibung |
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

