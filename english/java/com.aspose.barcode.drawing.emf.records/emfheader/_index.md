---
title: EmfHeader
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 18
url: /java/com.aspose.barcode.drawing.emf.records/emfheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord)
```
public class EmfHeader extends EmfRecord
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfHeader()](#EmfHeader--) | The value of the Size field can be used to distinguish between the different EMR\_HEADER record types listed earlier in this section.There are three possible headers: The EmfMetafileHeader record.The fixed-size part of this header is 88 bytes, and it contains a Header object(section 2.2.9). |
## Fields

| Field | Description |
| --- | --- |
| [EmfHeaderExtension1](#EmfHeaderExtension1) |  |
| [EmfHeaderExtension2](#EmfHeaderExtension2) |  |
| [EmfHeaderMain](#EmfHeaderMain) | A Header object (section 2.2.9), which contains information about the content and structure of the metafile. |
| [RecordType](#RecordType) | The type of the record |
| [Size](#Size) | The size of the record |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmfHeader() {#EmfHeader--}
```
public EmfHeader()
```


The value of the Size field can be used to distinguish between the different EMR\_HEADER record types listed earlier in this section.There are three possible headers: The EmfMetafileHeader record.The fixed-size part of this header is 88 bytes, and it contains a Header object(section 2.2.9). The EmfMetafileHeaderExtension1 record.The fixed-size part of this header is 100 bytes, and it contains a Header object and a HeaderExtension1 object(section 2.2.10). The EmfMetafileHeaderExtension2 record.The fixed-size part of this header is 108 bytes, and it contains a Header

### EmfHeaderExtension1 {#EmfHeaderExtension1}
```
public EmfHeaderExtension1 EmfHeaderExtension1
```


### EmfHeaderExtension2 {#EmfHeaderExtension2}
```
public EmfHeaderExtension2 EmfHeaderExtension2
```


### EmfHeaderMain {#EmfHeaderMain}
```
public EmfHeaderObject EmfHeaderMain
```


A Header object (section 2.2.9), which contains information about the content and structure of the metafile. 80 Bytes

### RecordType {#RecordType}
```
public long RecordType
```


The type of the record

### Size {#Size}
```
public int Size
```


The size of the record

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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

