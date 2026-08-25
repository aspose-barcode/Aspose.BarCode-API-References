---
title: USADriveIdJurisdSubfile
second_title: Aspose.BarCode for Java API Reference
description: Class for Jurisdiction specific fields for USA DL
type: docs
weight: 38
url: /java/com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
**Inheritance:**
java.lang.Object
```
public class USADriveIdJurisdSubfile
```

Class for Jurisdiction specific fields for USA DL
## Constructors

| Constructor | Description |
| --- | --- |
| [USADriveIdJurisdSubfile()](#USADriveIdJurisdSubfile--) |  |
## Methods

| Method | Description |
| --- | --- |
| [addOrReplace(USADriveIdJurisdSubfile.DataElement node)](#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Adds new DataElement or replaces it if ElementID already exists. |
| [addOrReplace(String id, String value)](#addOrReplace-java.lang.String-java.lang.String-) | Adds a new DataElement with the specified identifier and value, or replaces the existing element if an entry with the same ElementID is already present. |
| [clear()](#clear--) | Clears all data elements |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findDataElement(String id, boolean isOpenOrCreate)](#findDataElement-java.lang.String-boolean-) | Searches for data element by 3-letter id |
| [get(int index)](#get-int-) | Indexing by index number |
| [get(String id)](#get-java.lang.String-) | Indexing by 3-letter element id |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [insert(int index, USADriveIdJurisdSubfile.DataElement node)](#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Inserts the specified DataElement at the given index. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(int index)](#remove-int-) | Tries to remove element at index |
| [remove(String id)](#remove-java.lang.String-) | Tries to remove element with 3-letter id |
| [set(int index, USADriveIdJurisdSubfile.DataElement value)](#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexing by index number |
| [set(String id, USADriveIdJurisdSubfile.DataElement value)](#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | Indexing by 3-letter element id |
| [size()](#size--) | Returns number of data elements |
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


Adds new DataElement or replaces it if ElementID already exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | DataElement to add |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Added/replaced data element
### addOrReplace(String id, String value) {#addOrReplace-java.lang.String-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(String id, String value)
```


Adds a new DataElement with the specified identifier and value, or replaces the existing element if an entry with the same ElementID is already present.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | A 3-letter identifier that uniquely specifies the jurisdiction-related data element. |
| value | java.lang.String | The text value assigned to the data element; this value will overwrite the existing one if the element already exists. |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement instance that was added to the collection or updated in place.
### clear() {#clear--}
```
public final void clear()
```


Clears all data elements

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | 3-letter id |
| isOpenOrCreate | boolean | If true, it will be created if not found |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Found data element
### get(int index) {#get-int-}
```
public final USADriveIdJurisdSubfile.DataElement get(int index)
```


Indexing by index number

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Element index (int) |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### get(String id) {#get-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement get(String id)
```


Indexing by 3-letter element id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | 3-letter element id |

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


Inserts the specified DataElement at the given index. If a DataElement with the same ElementID already exists, it will be replaced.

**Parameters:**
| Parameter | Type | Description |
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




### remove(int index) {#remove-int-}
```
public final boolean remove(int index)
```


Tries to remove element at index

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | index number |

**Returns:**
boolean - true if successful, false if out of range
### remove(String id) {#remove-java.lang.String-}
```
public final boolean remove(String id)
```


Tries to remove element with 3-letter id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | 3-letter id |

**Returns:**
boolean - true if successful, false if no such id
### set(int index, USADriveIdJurisdSubfile.DataElement value) {#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(int index, USADriveIdJurisdSubfile.DataElement value)
```


Indexing by index number

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Element index (int) |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### set(String id, USADriveIdJurisdSubfile.DataElement value) {#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(String id, USADriveIdJurisdSubfile.DataElement value)
```


Indexing by 3-letter element id

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | 3-letter element id |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### size() {#size--}
```
public final int size()
```


Returns number of data elements

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

