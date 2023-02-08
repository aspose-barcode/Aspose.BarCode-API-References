---
title: EmfWorldTransformObj
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 21
url: /java/com.aspose.barcode.drawing.emf.data/emfworldtransformobj/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.drawing.emf.data.EmfStateObj
```
public class EmfWorldTransformObj extends EmfStateObj
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfWorldTransformObj(IEmfApplyWorldTransform applyTransform)](#EmfWorldTransformObj-com.aspose.barcode.drawing.emf.data.IEmfApplyWorldTransform-) |  |
| [EmfWorldTransformObj(EmfWorldTransformObj obj)](#EmfWorldTransformObj-com.aspose.barcode.drawing.emf.data.EmfWorldTransformObj-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getTransformInterface()](#getTransformInterface--) |  |
| [getXform()](#getXform--) |  |
| [hashCode()](#hashCode--) |  |
| [modifyWorldTransform(EmfXForm form, long modifyWorldTransformMode)](#modifyWorldTransform-com.aspose.barcode.drawing.emf.objects.EmfXForm-long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Resets transformation to normal |
| [rotateTransform(double angle)](#rotateTransform-double-) | Applies rotate transform for all further drawing. |
| [scaleTransform(double sX, double sY)](#scaleTransform-double-double-) | Applies scale transform for all further drawing. |
| [setTransformInterface(IEmfApplyWorldTransform value)](#setTransformInterface-com.aspose.barcode.drawing.emf.data.IEmfApplyWorldTransform-) |  |
| [setXform(EmfXForm value)](#setXform-com.aspose.barcode.drawing.emf.objects.EmfXForm-) |  |
| [toString()](#toString--) |  |
| [translateTransform(double dX, double dY)](#translateTransform-double-double-) | Applies translate transform for all further drawing. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmfWorldTransformObj(IEmfApplyWorldTransform applyTransform) {#EmfWorldTransformObj-com.aspose.barcode.drawing.emf.data.IEmfApplyWorldTransform-}
```
public EmfWorldTransformObj(IEmfApplyWorldTransform applyTransform)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| applyTransform | [IEmfApplyWorldTransform](../../com.aspose.barcode.drawing.emf.data/iemfapplyworldtransform) |  |

### EmfWorldTransformObj(EmfWorldTransformObj obj) {#EmfWorldTransformObj-com.aspose.barcode.drawing.emf.data.EmfWorldTransformObj-}
```
public EmfWorldTransformObj(EmfWorldTransformObj obj)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | [EmfWorldTransformObj](../../com.aspose.barcode.drawing.emf.data/emfworldtransformobj) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getTransformInterface() {#getTransformInterface--}
```
public IEmfApplyWorldTransform getTransformInterface()
```




**Returns:**
[IEmfApplyWorldTransform](../../com.aspose.barcode.drawing.emf.data/iemfapplyworldtransform)
### getXform() {#getXform--}
```
public EmfXForm getXform()
```




**Returns:**
[EmfXForm](../../com.aspose.barcode.drawing.emf.objects/emfxform)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### modifyWorldTransform(EmfXForm form, long modifyWorldTransformMode) {#modifyWorldTransform-com.aspose.barcode.drawing.emf.objects.EmfXForm-long-}
```
public void modifyWorldTransform(EmfXForm form, long modifyWorldTransformMode)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| form | [EmfXForm](../../com.aspose.barcode.drawing.emf.objects/emfxform) |  |
| modifyWorldTransformMode | long |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Resets transformation to normal

### rotateTransform(double angle) {#rotateTransform-double-}
```
public void rotateTransform(double angle)
```


Applies rotate transform for all further drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | double | angle in degree |

### scaleTransform(double sX, double sY) {#scaleTransform-double-double-}
```
public void scaleTransform(double sX, double sY)
```


Applies scale transform for all further drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sX | double | scale by width coefficient |
| sY | double | scale by height coefficient |

### setTransformInterface(IEmfApplyWorldTransform value) {#setTransformInterface-com.aspose.barcode.drawing.emf.data.IEmfApplyWorldTransform-}
```
public void setTransformInterface(IEmfApplyWorldTransform value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IEmfApplyWorldTransform](../../com.aspose.barcode.drawing.emf.data/iemfapplyworldtransform) |  |

### setXform(EmfXForm value) {#setXform-com.aspose.barcode.drawing.emf.objects.EmfXForm-}
```
public void setXform(EmfXForm value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfXForm](../../com.aspose.barcode.drawing.emf.objects/emfxform) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(double dX, double dY) {#translateTransform-double-double-}
```
public void translateTransform(double dX, double dY)
```


Applies translate transform for all further drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dX | double | shift drawing by X coord |
| dY | double | shift drawing by Y coord |

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

