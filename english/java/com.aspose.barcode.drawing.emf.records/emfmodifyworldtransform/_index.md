---
title: EmfModifyWorldTransform
second_title: Aspose.BarCode for Java API Reference
description: The EMR_MODIFYWORLDTRANSFORM record modifies the current world-space to page-space transform in the playback device context.
type: docs
weight: 19
url: /java/com.aspose.barcode.drawing.emf.records/emfmodifyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord)
```
public class EmfModifyWorldTransform extends EmfRecord
```

The EMR\_MODIFYWORLDTRANSFORM record modifies the current world-space to page-space transform in the playback device context.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform--) |  |
| [EmfModifyWorldTransform(EmfXForm form, long modifyWorldTransformMode)](#EmfModifyWorldTransform-com.aspose.barcode.drawing.emf.objects.EmfXForm-long-) |  |
## Fields

| Field | Description |
| --- | --- |
| [ModifyWorldTransformMode](#ModifyWorldTransformMode) | A 32-bit unsigned integer that specifies how the transform specified in Xform is used. |
| [RecordType](#RecordType) | The type of the record |
| [Size](#Size) | The size of the record |
| [Xform](#Xform) | An XForm object (section 2.2.28), which defines a world-space to page space transform. |
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
### EmfModifyWorldTransform() {#EmfModifyWorldTransform--}
```
public EmfModifyWorldTransform()
```


### EmfModifyWorldTransform(EmfXForm form, long modifyWorldTransformMode) {#EmfModifyWorldTransform-com.aspose.barcode.drawing.emf.objects.EmfXForm-long-}
```
public EmfModifyWorldTransform(EmfXForm form, long modifyWorldTransformMode)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| form | [EmfXForm](../../com.aspose.barcode.drawing.emf.objects/emfxform) |  |
| modifyWorldTransformMode | long |  |

### ModifyWorldTransformMode {#ModifyWorldTransformMode}
```
public long ModifyWorldTransformMode
```


A 32-bit unsigned integer that specifies how the transform specified in Xform is used. This value MUST be in the ModifyWorldTransformMode enumeration (section 2.1.24).

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

### Xform {#Xform}
```
public EmfXForm Xform
```


An XForm object (section 2.2.28), which defines a world-space to page space transform.

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

