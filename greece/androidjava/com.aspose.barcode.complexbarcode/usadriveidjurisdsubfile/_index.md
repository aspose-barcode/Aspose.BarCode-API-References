---
title: USADriveIdJurisdSubfile
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Κλάση για πεδία ειδικά για δικαιοδοσία στο USA DL
type: docs
weight: 39
url: /el/androidjava/com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
**Inheritance:**
java.lang.Object
```
public class USADriveIdJurisdSubfile
```

Κλάση για πεδία ειδικά για δικαιοδοσία στο USA DL
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [USADriveIdJurisdSubfile()](#USADriveIdJurisdSubfile--) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [addOrReplace(USADriveIdJurisdSubfile.DataElement node)](#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Προσθέτει νέο DataElement ή το αντικαθιστά εάν το ElementID υπάρχει ήδη. |
| [addOrReplace(String id, String value)](#addOrReplace-java.lang.String-java.lang.String-) | Προσθέτει ένα νέο DataElement με το καθορισμένο αναγνωριστικό και τιμή, ή αντικαθιστά το υπάρχον στοιχείο εάν υπάρχει ήδη μια καταχώρηση με το ίδιο ElementID. |
| [clear()](#clear--) | Καθαρίζει όλα τα στοιχεία δεδομένων |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findDataElement(String id, boolean isOpenOrCreate)](#findDataElement-java.lang.String-boolean-) | Searches for data element by 3-letter id |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Returns number of data elements |
| [get_Item(int index)](#get-Item-int-) | Indexing by index number |
| [get_Item(String id)](#get-Item-java.lang.String-) | Indexing by 3-letter element id |
| [hashCode()](#hashCode--) |  |
| [insert(int index, USADriveIdJurisdSubfile.DataElement node)](#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Inserts the specified DataElement at the given index. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int index)](#removeAt-int-) | Tries to remove element at index |
| [removeAt(String id)](#removeAt-java.lang.String-) | Tries to remove element with 3-letter id |
| [set_Item(int index, USADriveIdJurisdSubfile.DataElement value)](#set-Item-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexing by index number |
| [set_Item(String id, USADriveIdJurisdSubfile.DataElement value)](#set-Item-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexing by 3-letter element id |
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


Προσθέτει νέο DataElement ή το αντικαθιστά εάν το ElementID υπάρχει ήδη.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | DataElement to add |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Added/replaced data element
### addOrReplace(String id, String value) {#addOrReplace-java.lang.String-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(String id, String value)
```


Προσθέτει ένα νέο DataElement με το καθορισμένο αναγνωριστικό και τιμή, ή αντικαθιστά το υπάρχον στοιχείο εάν υπάρχει ήδη μια καταχώρηση με το ίδιο ElementID.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| id | java.lang.String | A 3-letter identifier that uniquely specifies the jurisdiction-related data element. |
| τιμή | java.lang.String | The text value assigned to the data element; this value will overwrite the existing one if the element already exists. |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement instance that was added to the collection or updated in place.
### clear() {#clear--}
```
public final void clear()
```


Καθαρίζει όλα τα στοιχεία δεδομένων

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findDataElement(String id, boolean isOpenOrCreate) {#findDataElement-java.lang.String-boolean-}
```
public final USADriveIdJurisdSubfile.DataElement findDataElement(String id, boolean isOpenOrCreate)
```


Searches for data element by 3-letter id

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| id | java.lang.String | 3-letter id |
| isOpenOrCreate | boolean | If true, it will be created if not found |

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


Returns number of data elements

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final USADriveIdJurisdSubfile.DataElement get_Item(int index)
```


Indexing by index number

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| index | int | Element index (int) |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### get_Item(String id) {#get-Item-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement get_Item(String id)
```


Indexing by 3-letter element id

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| id | java.lang.String | 3-letter element id |

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


Inserts the specified DataElement at the given index. If a DataElement with the same ElementID already exists, it will be replaced.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| index | int | The zero-based index at which the element should be inserted. |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | The DataElement instance to insert or replace at the target position. |

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


Tries to remove element at index

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| index | int | index number |

**Returns:**
boolean - true if successful, false if out of range
### removeAt(String id) {#removeAt-java.lang.String-}
```
public final boolean removeAt(String id)
```


Tries to remove element with 3-letter id

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| id | java.lang.String | 3-letter id |

**Returns:**
boolean - true if successful, false if no such id
### set_Item(int index, USADriveIdJurisdSubfile.DataElement value) {#set-Item-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set_Item(int index, USADriveIdJurisdSubfile.DataElement value)
```


Indexing by index number

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| index | int | Element index (int) |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### set_Item(String id, USADriveIdJurisdSubfile.DataElement value) {#set-Item-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set_Item(String id, USADriveIdJurisdSubfile.DataElement value)
```


Indexing by 3-letter element id

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| id | java.lang.String | 3-letter element id |
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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

