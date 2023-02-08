---
title: EmfHeaderObject
second_title: Aspose.BarCode for Java API Reference
description: 2.2.9 Header Object The Header object defines the EMF metafile header.It specifies properties of the device on which the image in the metafile was created.
type: docs
weight: 13
url: /java/com.aspose.barcode.drawing.emf.objects/emfheaderobject/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.drawing.emf.objects.XmfObject
```
public class EmfHeaderObject extends XmfObject
```

2.2.9 Header Object The Header object defines the EMF metafile header.It specifies properties of the device on which the image in the metafile was created.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfHeaderObject()](#EmfHeaderObject--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Bounds](#Bounds) | A WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangular inclusive-inclusive bounds in device units of the smallest rectangle that can be drawn around the image stored in the metafile |
| [Bytes](#Bytes) | 32-bit unsigned integer that specifies the size of the metafile, in bytes. |
| [Device](#Device) | A WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the size of the reference device, in pixels |
| [Frame](#Frame) | A WMF RectL object that specifies the rectangular inclusive-inclusive dimensions, in .01 millimeter units, of a rectangle that surrounds the image stored in the metafile |
| [Handles](#Handles) | A 16-bit unsigned integer that specifies the number of graphics objects that will be used during the processing of the metafile |
| [Millimeters](#Millimeters) | A WMF SizeL object that specifies the size of the reference device, in millimeters |
| [NDesription](#NDesription) | A 32-bit unsigned integer that specifies the number of characters in the array that contains the description of the metafile's contents. |
| [NPalEntries](#NPalEntries) | A 32-bit unsigned integer that specifies the number of entries in the metafile palette. |
| [OffDescription](#OffDescription) | A 32-bit unsigned integer that specifies the offset from the beginning of this record to the array that contains the description of the metafile's contents |
| [RecordSignature](#RecordSignature) | A 32-bit unsigned integer that specifies the record signature. |
| [Records](#Records) | A 32-bit unsigned integer that specifies the number of records in the metafile |
| [Reserved](#Reserved) | A 16-bit unsigned integer that MUST be 0x0000 and MUST be ignored |
| [Version](#Version) | Version (4 bytes): A 32-bit unsigned integer that specifies EMF metafile interoperability. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSize()](#getSize--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmfHeaderObject() {#EmfHeaderObject--}
```
public EmfHeaderObject()
```


### Bounds {#Bounds}
```
public WmfRectL Bounds
```


A WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the rectangular inclusive-inclusive bounds in device units of the smallest rectangle that can be drawn around the image stored in the metafile

### Bytes {#Bytes}
```
public long Bytes
```


32-bit unsigned integer that specifies the size of the metafile, in bytes.

### Device {#Device}
```
public WmfSizeL Device
```


A WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the size of the reference device, in pixels

### Frame {#Frame}
```
public WmfRectL Frame
```


A WMF RectL object that specifies the rectangular inclusive-inclusive dimensions, in .01 millimeter units, of a rectangle that surrounds the image stored in the metafile

### Handles {#Handles}
```
public int Handles
```


A 16-bit unsigned integer that specifies the number of graphics objects that will be used during the processing of the metafile

### Millimeters {#Millimeters}
```
public WmfSizeL Millimeters
```


A WMF SizeL object that specifies the size of the reference device, in millimeters

### NDesription {#NDesription}
```
public long NDesription
```


A 32-bit unsigned integer that specifies the number of characters in the array that contains the description of the metafile's contents. This is zero if there is no description string.

### NPalEntries {#NPalEntries}
```
public long NPalEntries
```


A 32-bit unsigned integer that specifies the number of entries in the metafile palette. The palette is located in the EMR\_EOF record

### OffDescription {#OffDescription}
```
public long OffDescription
```


A 32-bit unsigned integer that specifies the offset from the beginning of this record to the array that contains the description of the metafile's contents

### RecordSignature {#RecordSignature}
```
public long RecordSignature
```


A 32-bit unsigned integer that specifies the record signature. This MUST be ENHMETA\_SIGNATURE, from the FormatSignature enumeration (section 2.1.14).

### Records {#Records}
```
public long Records
```


A 32-bit unsigned integer that specifies the number of records in the metafile

### Reserved {#Reserved}
```
public int Reserved
```


A 16-bit unsigned integer that MUST be 0x0000 and MUST be ignored

### Version {#Version}
```
public long Version
```


Version (4 bytes): A 32-bit unsigned integer that specifies EMF metafile interoperability. This SHOULD be 0x00010000

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
### getSize() {#getSize--}
```
public int getSize()
```




**Returns:**
int
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

