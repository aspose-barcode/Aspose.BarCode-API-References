---
title: USADriveIdJurisdSubfile
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Klasse für gerichtsstandsspezifische Felder für USA-DL
type: docs
weight: 39
url: /de/androidjava/com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
**Inheritance:**
java.lang.Object
```
public class USADriveIdJurisdSubfile
```

Klasse für gerichtsstandsspezifische Felder für USA-DL
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [USADriveIdJurisdSubfile()](#USADriveIdJurisdSubfile--) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [addOrReplace(USADriveIdJurisdSubfile.DataElement node)](#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Fügt ein neues DataElement hinzu oder ersetzt es, wenn ElementID bereits existiert. |
| [addOrReplace(String id, String value)](#addOrReplace-java.lang.String-java.lang.String-) | Fügt ein neues DataElement mit dem angegebenen Bezeichner und Wert hinzu oder ersetzt das vorhandene Element, wenn ein Eintrag mit derselben ElementID bereits vorhanden ist. |
| [clear()](#clear--) | Löscht alle DataElements |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findDataElement(String id, boolean isOpenOrCreate)](#findDataElement-java.lang.String-boolean-) | Sucht nach Datenelement anhand einer 3‑Buchstaben‑ID |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gibt die Anzahl der Datenelemente zurück |
| [get_Item(int index)](#get-Item-int-) | Indexierung nach Indexnummer |
| [get_Item(String id)](#get-Item-java.lang.String-) | Indexierung nach 3‑Buchstaben‑Element‑ID |
| [hashCode()](#hashCode--) |  |
| [insert(int index, USADriveIdJurisdSubfile.DataElement node)](#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Fügt das angegebene DataElement an dem angegebenen Index ein. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int index)](#removeAt-int-) | Versucht, das Element am Index zu entfernen |
| [removeAt(String id)](#removeAt-java.lang.String-) | Versucht, das Element mit einer 3‑Buchstaben‑ID zu entfernen |
| [set_Item(int index, USADriveIdJurisdSubfile.DataElement value)](#set-Item-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexierung nach Indexnummer |
| [set_Item(String id, USADriveIdJurisdSubfile.DataElement value)](#set-Item-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexierung nach 3‑Buchstaben‑Element‑ID |
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
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| ID | java.lang.String | Ein 3‑Buchstaben‑Bezeichner, der das jurisdictionsbezogene Datenelement eindeutig spezifiziert. |
| Wert | java.lang.String | Der Textwert, der dem Datenelement zugewiesen wird; dieser Wert überschreibt den bestehenden, falls das Element bereits existiert. |

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findDataElement(String id, boolean isOpenOrCreate) {#findDataElement-java.lang.String-boolean-}
```
public final USADriveIdJurisdSubfile.DataElement findDataElement(String id, boolean isOpenOrCreate)
```


Sucht nach Datenelement anhand einer 3‑Buchstaben‑ID

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| ID | java.lang.String | 3‑Buchstaben‑ID |
| isOpenOrCreate | boolean | Wenn true, wird es erstellt, falls es nicht gefunden wird |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Found data element
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public final int getCount()
```


Gibt die Anzahl der Datenelemente zurück

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final USADriveIdJurisdSubfile.DataElement get_Item(int index)
```


Indexierung nach Indexnummer

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Index | int | Elementindex (int) |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### get_Item(String id) {#get-Item-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement get_Item(String id)
```


Indexierung nach 3‑Buchstaben‑Element‑ID

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| ID | java.lang.String | 3‑Buchstaben‑Element‑ID |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Index | int | Der nullbasierte Index, an dem das Element eingefügt werden soll. |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | Die DataElement‑Instanz, die an der Zielposition eingefügt oder ersetzt werden soll. |

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




### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Versucht, das Element am Index zu entfernen

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Index | int | Indexnummer |

**Returns:**
boolesch - true, wenn erfolgreich, false, wenn außerhalb des Bereichs
### removeAt(String id) {#removeAt-java.lang.String-}
```
public final boolean removeAt(String id)
```


Versucht, das Element mit einer 3‑Buchstaben‑ID zu entfernen

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| ID | java.lang.String | 3‑Buchstaben‑ID |

**Returns:**
boolesch - true, wenn erfolgreich, false, wenn keine solche ID existiert
### set_Item(int index, USADriveIdJurisdSubfile.DataElement value) {#set-Item-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set_Item(int index, USADriveIdJurisdSubfile.DataElement value)
```


Indexierung nach Indexnummer

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Index | int | Elementindex (int) |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### set_Item(String id, USADriveIdJurisdSubfile.DataElement value) {#set-Item-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set_Item(String id, USADriveIdJurisdSubfile.DataElement value)
```


Indexierung nach 3‑Buchstaben‑Element‑ID

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| ID | java.lang.String | 3‑Buchstaben‑Element‑ID |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

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

