---
title: EmfLogBrushEx
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.aspose.barcode.drawing.emf.objects/emflogbrushex/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.drawing.emf.objects.XmfObject
```
public class EmfLogBrushEx extends XmfObject
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogBrushEx()](#EmfLogBrushEx--) |  |
| [EmfLogBrushEx(System.Drawing.Color color, boolean Transparent)](#EmfLogBrushEx-com.aspose.ms.System.Drawing.Color-boolean-) |  |
## Fields

| Field | Description |
| --- | --- |
| [BrushHatch](#BrushHatch) | A 32-bit unsigned field that contains the brush hatch data. |
| [BrushStyle](#BrushStyle) | A 32-bit unsigned integer that specifies the brush style. |
| [ColorRef](#ColorRef) | A 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies a color. |
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
### EmfLogBrushEx() {#EmfLogBrushEx--}
```
public EmfLogBrushEx()
```


### EmfLogBrushEx(System.Drawing.Color color, boolean Transparent) {#EmfLogBrushEx-com.aspose.ms.System.Drawing.Color-boolean-}
```
public EmfLogBrushEx(System.Drawing.Color color, boolean Transparent)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color |  |
| Transparent | boolean |  |

### BrushHatch {#BrushHatch}
```
public long BrushHatch
```


A 32-bit unsigned field that contains the brush hatch data. Its interpretation depends on the value of BrushStyle,

### BrushStyle {#BrushStyle}
```
public long BrushStyle
```


A 32-bit unsigned integer that specifies the brush style. The value MUST be an enumeration from WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). The style values that are supported in this structure are listed later in this section. The BS\_NULL style SHOULD be used to specify a brush that has no effect.

### ColorRef {#ColorRef}
```
public WmfColorRef ColorRef
```


A 32-bit WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies a color. The interpretation of this field depends on the value of BrushStyle, as explained in the following table.

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

