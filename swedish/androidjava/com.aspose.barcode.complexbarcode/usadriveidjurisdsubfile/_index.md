---
title: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "Klass för jurisdiktionsspecifika fält för USA DL"
type: docs
weight: 38
url: /sv/androidjava/com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
**Inheritance:**
java.lang.Object
```
public class USADriveIdJurisdSubfile
```

Klass för jurisdiktionsspecifika fält för USA DL
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [USADriveIdJurisdSubfile()](#USADriveIdJurisdSubfile--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addOrReplace(USADriveIdJurisdSubfile.DataElement node)](#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Lägger till nytt DataElement eller ersätter det om ElementID redan finns. |
| [addOrReplace(String id, String value)](#addOrReplace-java.lang.String-java.lang.String-) | Lägger till ett nytt DataElement med den angivna identifieraren och värdet, eller ersätter det befintliga elementet om en post med samma ElementID redan finns. |
| [clear()](#clear--) | Rensar alla dataelement |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findDataElement(String id, boolean isOpenOrCreate)](#findDataElement-java.lang.String-boolean-) | Söker efter dataelement med 3‑bokstavs‑id |
| [get(int index)](#get-int-) | Indexering efter indexnummer |
| [get(String id)](#get-java.lang.String-) | Indexering efter 3‑bokstavs‑element‑id |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [insert(int index, USADriveIdJurisdSubfile.DataElement node)](#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Infogar det angivna DataElementet på det givna indexet. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(int index)](#remove-int-) | Försöker ta bort elementet vid indexet |
| [remove(String id)](#remove-java.lang.String-) | Försöker ta bort elementet med 3‑bokstavs‑id |
| [set(int index, USADriveIdJurisdSubfile.DataElement value)](#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexering efter indexnummer |
| [set(String id, USADriveIdJurisdSubfile.DataElement value)](#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexering efter 3‑bokstavs‑element‑id |
| [size()](#size--) | Returnerar antalet dataelement |
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


Lägger till nytt DataElement eller ersätter det om ElementID redan finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | DataElement att lägga till |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Added/replaced data element
### addOrReplace(String id, String value) {#addOrReplace-java.lang.String-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(String id, String value)
```


Lägger till ett nytt DataElement med den angivna identifieraren och värdet, eller ersätter det befintliga elementet om en post med samma ElementID redan finns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | java.lang.String | En 3‑bokstavsidentifierare som unikt specificerar det jurisdiktionsrelaterade dataelementet. |
| värde | java.lang.String | Textvärdet som tilldelas dataelementet; detta värde kommer att skriva över det befintliga om elementet redan finns. |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement instance that was added to the collection or updated in place.
### clear() {#clear--}
```
public final void clear()
```


Rensar alla dataelement

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
### findDataElement(String id, boolean isOpenOrCreate) {#findDataElement-java.lang.String-boolean-}
```
public final USADriveIdJurisdSubfile.DataElement findDataElement(String id, boolean isOpenOrCreate)
```


Söker efter dataelement med 3‑bokstavs‑id

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | java.lang.String | 3‑bokstavs‑id |
| isOpenOrCreate | boolean | Om true, kommer det att skapas om det inte hittas. |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Found data element
### get(int index) {#get-int-}
```
public final USADriveIdJurisdSubfile.DataElement get(int index)
```


Indexering efter indexnummer

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Elementindex (int) |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### get(String id) {#get-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement get(String id)
```


Indexering efter 3‑bokstavs‑element‑id

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | java.lang.String | 3-bokstävers element-id |

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


Infogar det angivna DataElement på det angivna indexet. Om ett DataElement med samma ElementID redan finns, kommer det att ersättas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där elementet ska infogas. |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | DataElement‑instansen som ska infogas eller ersättas på målpositionen. |

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


Försöker ta bort elementet vid indexet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | indexnummer |

**Returns:**
boolesk – true om lyckad, false om utanför intervallet
### remove(String id) {#remove-java.lang.String-}
```
public final boolean remove(String id)
```


Försöker ta bort elementet med 3‑bokstavs‑id

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | java.lang.String | 3‑bokstavs‑id |

**Returns:**
boolesk – true om lyckad, false om ingen sådan id finns
### set(int index, USADriveIdJurisdSubfile.DataElement value) {#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(int index, USADriveIdJurisdSubfile.DataElement value)
```


Indexering efter indexnummer

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Elementindex (int) |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### set(String id, USADriveIdJurisdSubfile.DataElement value) {#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(String id, USADriveIdJurisdSubfile.DataElement value)
```


Indexering efter 3‑bokstavs‑element‑id

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | java.lang.String | 3-bokstävers element-id |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### size() {#size--}
```
public final int size()
```


Returnerar antalet dataelement

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

