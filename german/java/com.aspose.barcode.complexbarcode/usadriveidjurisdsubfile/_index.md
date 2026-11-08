---
title: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Klasse für jurisdictionsspezifische Felder des US-Führerscheins."
type: docs
weight: 38
url: /de/java/com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
**Inheritance:**
java.lang.Object
```
public class USADriveIdJurisdSubfile
```

Klasse für jurisdictionsspezifische Felder des US-Führerscheins.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [USADriveIdJurisdSubfile()](#USADriveIdJurisdSubfile--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addOrReplace(USADriveIdJurisdSubfile.DataElement node)](#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Fügt ein neues DataElement hinzu oder ersetzt es, wenn ElementID bereits existiert. |
| [addOrReplace(String id, String value)](#addOrReplace-java.lang.String-java.lang.String-) | Fügt ein neues DataElement mit dem angegebenen Bezeichner und Wert hinzu oder ersetzt das vorhandene Element, wenn ein Eintrag mit derselben ElementID bereits vorhanden ist. |
| [clear()](#clear--) | Löscht alle DataElements |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findDataElement(String id, boolean isOpenOrCreate)](#findDataElement-java.lang.String-boolean-) | Sucht nach DataElement anhand einer 3‑Buchstaben‑ID |
| [get(int index)](#get-int-) | Indexierung nach Indexnummer |
| [get(String id)](#get-java.lang.String-) | Indexierung nach 3‑Buchstaben‑Element‑ID |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [insert(int index, USADriveIdJurisdSubfile.DataElement node)](#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Fügt das angegebene DataElement am angegebenen Index ein. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(int index)](#remove-int-) | Versucht, das Element am Index zu entfernen |
| [remove(String id)](#remove-java.lang.String-) | Versucht, das Element mit einer 3‑Buchstaben‑ID zu entfernen |
| [set(int index, USADriveIdJurisdSubfile.DataElement value)](#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexierung nach Indexnummer |
| [set(String id, USADriveIdJurisdSubfile.DataElement value)](#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexierung nach 3‑Buchstaben‑Element‑ID |
| [size()](#size--) | Gibt die Anzahl der DataElements zurück |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdJurisdSubfile() {#USADriveIdJurisdSubfile--}
```
public USADriveIdJurisdSubfile()
```


### addOrReplace(USADriveIdJurisdSubfile.DataElement node) {#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(USADriveIdJurisdSubfile.DataElement node)
```


Fügt ein neues DataElement hinzu oder ersetzt es, wenn ElementID bereits existiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | DataElement zum Hinzufügen |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Added/replaced data element
### addOrReplace(String id, String value) {#addOrReplace-java.lang.String-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(String id, String value)
```


Fügt ein neues DataElement mit dem angegebenen Bezeichner und Wert hinzu oder ersetzt das vorhandene Element, wenn ein Eintrag mit derselben ElementID bereits vorhanden ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ID | java.lang.String | Ein 3‑Buchstaben‑Bezeichner, der das jurisdictionsbezogene DataElement eindeutig spezifiziert. |
| Wert | java.lang.String | Der Textwert, der dem DataElement zugewiesen wird; dieser Wert überschreibt den vorhandenen, falls das Element bereits existiert. |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement instance that was added to the collection or updated in place.
### clear() {#clear--}
```
public final void clear()
```


Löscht alle DataElements

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
### findDataElement(String id, boolean isOpenOrCreate) {#findDataElement-java.lang.String-boolean-}
```
public final USADriveIdJurisdSubfile.DataElement findDataElement(String id, boolean isOpenOrCreate)
```


Sucht nach DataElement anhand einer 3‑Buchstaben‑ID

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ID | java.lang.String | 3‑Buchstaben‑ID |
| isOpenOrCreate | boolesch | Wenn true, wird es erstellt, falls nicht gefunden |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Found data element
### get(int index) {#get-int-}
```
public final USADriveIdJurisdSubfile.DataElement get(int index)
```


Indexierung nach Indexnummer

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Elementindex (int) |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### get(String id) {#get-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement get(String id)
```


Indexierung nach 3‑Buchstaben‑Element‑ID

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ID | java.lang.String | 3-Buchstaben-Element-ID |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### insert(int index, USADriveIdJurisdSubfile.DataElement node) {#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final USADriveIdJurisdSubfile.DataElement insert(int index, USADriveIdJurisdSubfile.DataElement node)
```


Fügt das angegebene DataElement an dem angegebenen Index ein. Wenn bereits ein DataElement mit derselben ElementID existiert, wird es ersetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Der nullbasierte Index, an dem das Element eingefügt werden soll. |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | Die DataElement-Instanz, die an der Zielposition eingefügt oder ersetzt werden soll. |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement that was inserted or used to replace an existing entry.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(int index) {#remove-int-}
```
public final boolean remove(int index)
```


Versucht, das Element am Index zu entfernen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Indexnummer |

**Returns:**
boolesch - true, wenn erfolgreich, false, wenn außerhalb des Bereichs
### remove(String id) {#remove-java.lang.String-}
```
public final boolean remove(String id)
```


Versucht, das Element mit einer 3‑Buchstaben‑ID zu entfernen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ID | java.lang.String | 3‑Buchstaben‑ID |

**Returns:**
boolesch - true, wenn erfolgreich, false, wenn keine solche ID vorhanden ist
### set(int index, USADriveIdJurisdSubfile.DataElement value) {#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(int index, USADriveIdJurisdSubfile.DataElement value)
```


Indexierung nach Indexnummer

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Elementindex (int) |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### set(String id, USADriveIdJurisdSubfile.DataElement value) {#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(String id, USADriveIdJurisdSubfile.DataElement value)
```


Indexierung nach 3‑Buchstaben‑Element‑ID

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ID | java.lang.String | 3-Buchstaben-Element-ID |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### size() {#size--}
```
public final int size()
```


Gibt die Anzahl der DataElements zurück

**Returns:**
int
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

