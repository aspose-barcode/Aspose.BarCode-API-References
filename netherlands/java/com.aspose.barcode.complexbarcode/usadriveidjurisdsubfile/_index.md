---
title: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Klasse voor jurisdictiespecifieke velden voor het Amerikaanse rijbewijs"
type: docs
weight: 38
url: /nl/java/com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
**Inheritance:**
java.lang.Object
```
public class USADriveIdJurisdSubfile
```

Klasse voor jurisdictiespecifieke velden voor het Amerikaanse rijbewijs
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [USADriveIdJurisdSubfile()](#USADriveIdJurisdSubfile--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addOrReplace(USADriveIdJurisdSubfile.DataElement node)](#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Voegt een nieuw DataElement toe of vervangt het als ElementID al bestaat. |
| [addOrReplace(String id, String value)](#addOrReplace-java.lang.String-java.lang.String-) | Voegt een nieuw DataElement toe met de opgegeven identifier en waarde, of vervangt het bestaande element als er al een item met dezelfde ElementID aanwezig is. |
| [clear()](#clear--) | Verwijdert alle data‑elementen |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findDataElement(String id, boolean isOpenOrCreate)](#findDataElement-java.lang.String-boolean-) | Zoekt naar data‑element op basis van een 3‑letterige id |
| [get(int index)](#get-int-) | Indexering op basis van indexnummer |
| [get(String id)](#get-java.lang.String-) | Indexering op basis van 3‑letterig element‑id |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [insert(int index, USADriveIdJurisdSubfile.DataElement node)](#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Voegt het opgegeven DataElement in op de opgegeven index. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(int index)](#remove-int-) | Probeert element op index te verwijderen |
| [remove(String id)](#remove-java.lang.String-) | Probeert element met 3-letterige id te verwijderen |
| [set(int index, USADriveIdJurisdSubfile.DataElement value)](#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexering op basis van indexnummer |
| [set(String id, USADriveIdJurisdSubfile.DataElement value)](#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexering op basis van 3‑letterig element‑id |
| [size()](#size--) | Retourneert het aantal data-elementen |
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


Voegt een nieuw DataElement toe of vervangt het als ElementID al bestaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | DataElement om toe te voegen |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Added/replaced data element
### addOrReplace(String id, String value) {#addOrReplace-java.lang.String-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(String id, String value)
```


Voegt een nieuw DataElement toe met de opgegeven identifier en waarde, of vervangt het bestaande element als er al een item met dezelfde ElementID aanwezig is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | java.lang.String | Een 3-letterige identifier die het jurisdictiegerelateerde data-element uniek specificeert. |
| waarde | java.lang.String | De tekstwaarde die aan het data-element is toegewezen; deze waarde zal de bestaande overschrijven als het element al bestaat. |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement instance that was added to the collection or updated in place.
### clear() {#clear--}
```
public final void clear()
```


Verwijdert alle data‑elementen

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
### findDataElement(String id, boolean isOpenOrCreate) {#findDataElement-java.lang.String-boolean-}
```
public final USADriveIdJurisdSubfile.DataElement findDataElement(String id, boolean isOpenOrCreate)
```


Zoekt naar data‑element op basis van een 3‑letterige id

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | java.lang.String | 3-letterige id |
| isOpenOrCreate | boolean | Indien true, wordt het aangemaakt als het niet wordt gevonden |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Found data element
### get(int index) {#get-int-}
```
public final USADriveIdJurisdSubfile.DataElement get(int index)
```


Indexering op basis van indexnummer

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Elementindex (int) |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### get(String id) {#get-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement get(String id)
```


Indexering op basis van 3‑letterig element‑id

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | java.lang.String | 3-letterige element-id |

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


Voegt het opgegeven DataElement in op de opgegeven index. Als er al een DataElement met dezelfde ElementID bestaat, wordt het vervangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het element moet worden ingevoegd. |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | De DataElement-instantie die moet worden ingevoegd of vervangen op de doelpositie. |

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


Probeert element op index te verwijderen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | indexnummer |

**Returns:**
boolean - true indien geslaagd, false indien buiten bereik
### remove(String id) {#remove-java.lang.String-}
```
public final boolean remove(String id)
```


Probeert element met 3-letterige id te verwijderen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | java.lang.String | 3-letterige id |

**Returns:**
boolean - true indien geslaagd, false indien geen dergelijk id
### set(int index, USADriveIdJurisdSubfile.DataElement value) {#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(int index, USADriveIdJurisdSubfile.DataElement value)
```


Indexering op basis van indexnummer

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Elementindex (int) |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### set(String id, USADriveIdJurisdSubfile.DataElement value) {#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(String id, USADriveIdJurisdSubfile.DataElement value)
```


Indexering op basis van 3‑letterig element‑id

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | java.lang.String | 3-letterige element-id |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### size() {#size--}
```
public final int size()
```


Retourneert het aantal data-elementen

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

