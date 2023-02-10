---
title: EmfEof
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.drawing.emf.records/emfeof/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord)
```
public class EmfEof extends EmfRecord
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfEof()](#EmfEof--) |  |
## Fields

| Field | Description |
| --- | --- |
| [NPalEntries](#NPalEntries) | A 32-bit unsigned integer that specifies the number of palette entries. |
| [OffPalEntries](#OffPalEntries) | A 32-bit unsigned integer that specifies the offset to the palette entries from the start of this record. |
| [RecordType](#RecordType) | The type of the record |
| [Size](#Size) | The size of the record |
| [SizeLast](#SizeLast) | A 32-bit unsigned integer that MUST be the same as Size and MUST be the last field of the record and hence the metafile. |
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
### EmfEof() {#EmfEof--}
```
public EmfEof()
```


### NPalEntries {#NPalEntries}
```
public long NPalEntries
```


A 32-bit unsigned integer that specifies the number of palette entries.

### OffPalEntries {#OffPalEntries}
```
public long OffPalEntries
```


A 32-bit unsigned integer that specifies the offset to the palette entries from the start of this record.

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

### SizeLast {#SizeLast}
```
public long SizeLast
```


A 32-bit unsigned integer that MUST be the same as Size and MUST be the last field of the record and hence the metafile. LogPaletteEntry objects, if they exist, MUST precede this field.

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

