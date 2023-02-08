---
title: EmfSetWorldTransform
second_title: Aspose.BarCode for Java API Reference
description: The EMR_SETWORLDTRANSFORM record specifies a transform for the current world-space to page space transform in the playback device context.
type: docs
weight: 34
url: /java/com.aspose.barcode.drawing.emf.records/emfsetworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.emf.records.EmfRecord](../../com.aspose.barcode.drawing.emf.records/emfrecord)
```
public class EmfSetWorldTransform extends EmfRecord
```

The EMR\_SETWORLDTRANSFORM record specifies a transform for the current world-space to page space transform in the playback device context.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfSetWorldTransform()](#EmfSetWorldTransform--) |  |
| [EmfSetWorldTransform(EmfXForm form)](#EmfSetWorldTransform-com.aspose.barcode.drawing.emf.objects.EmfXForm-) |  |
## Fields

| Field | Description |
| --- | --- |
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
### EmfSetWorldTransform() {#EmfSetWorldTransform--}
```
public EmfSetWorldTransform()
```


### EmfSetWorldTransform(EmfXForm form) {#EmfSetWorldTransform-com.aspose.barcode.drawing.emf.objects.EmfXForm-}
```
public EmfSetWorldTransform(EmfXForm form)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| form | [EmfXForm](../../com.aspose.barcode.drawing.emf.objects/emfxform) |  |

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

