---
title: EmfLogPenEx
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 19
url: /java/com.aspose.barcode.drawing.emf.objects/emflogpenex/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.drawing.emf.objects.XmfObject, com.aspose.barcode.drawing.emf.objects.EmfLogPenBase
```
public class EmfLogPenEx extends EmfLogPenBase
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogPenEx()](#EmfLogPenEx--) |  |
| [EmfLogPenEx(System.Drawing.Color Color)](#EmfLogPenEx-com.aspose.ms.System.Drawing.Color-) |  |
| [EmfLogPenEx(System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle)](#EmfLogPenEx-com.aspose.ms.System.Drawing.Color-int-com.aspose.barcode.drawing.PenDashStyle-) |  |
## Fields

| Field | Description |
| --- | --- |
| [BrushHatch](#BrushHatch) | The brush hatch pattern. |
| [BrushStyle](#BrushStyle) | A 32-bit unsigned integer that specifies a brush style for the pen from the WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). |
| [ColorRef](#ColorRef) | A WMF ColorRef object ([MS-WMF] section 2.2.2.8). |
| [NumStyleEntities](#NumStyleEntities) | The number of elements in the array specified in the StyleEntry field. |
| [PenStyle](#PenStyle) | The pen style |
| [StyleEntry](#StyleEntry) | An optional array of 32-bit unsigned integers that defines the lengths of dashes and gaps in the line drawn by this pen, when the value of PenStyle is PS\_USERSTYLE line style for the pen. |
| [Width](#Width) | A 32-bit unsigned integer that specifies the width of the line drawn by the pen. |
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
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### EmfLogPenEx(System.Drawing.Color Color) {#EmfLogPenEx-com.aspose.ms.System.Drawing.Color-}
```
public EmfLogPenEx(System.Drawing.Color Color)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Color | com.aspose.ms.System.Drawing.Color |  |

### EmfLogPenEx(System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle) {#EmfLogPenEx-com.aspose.ms.System.Drawing.Color-int-com.aspose.barcode.drawing.PenDashStyle-}
```
public EmfLogPenEx(System.Drawing.Color Color, int Thickness, PenDashStyle DashStyle)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Color | com.aspose.ms.System.Drawing.Color |  |
| Thickness | int |  |
| DashStyle | [PenDashStyle](../../com.aspose.barcode.drawing/pendashstyle) |  |

### BrushHatch {#BrushHatch}
```
public long BrushHatch
```


The brush hatch pattern. The definition of this field depends on the BrushStyle value, as shown in the table later in this section.

### BrushStyle {#BrushStyle}
```
public long BrushStyle
```


A 32-bit unsigned integer that specifies a brush style for the pen from the WMF BrushStyle enumeration ([MS-WMF] section 2.1.1.4). If the pen type in the PenStyle field is PS\_GEOMETRIC, this value MUST be either BS\_SOLID or BS\_HATCHED. The value of this field can be BS\_NULL, but only if the line style specified in PenStyle is PS\_NULL. The BS\_NULL style SHOULD be used to specify a brush that has no effect.

### ColorRef {#ColorRef}
```
public WmfColorRef ColorRef
```


A WMF ColorRef object ([MS-WMF] section 2.2.2.8). The interpretation of this field depends on the BrushStyle value, as shown in the table later in this section.

### NumStyleEntities {#NumStyleEntities}
```
public long NumStyleEntities
```


The number of elements in the array specified in the StyleEntry field. This value SHOULD be zero if PenStyle does not specify PS\_USERSTYLE.

### PenStyle {#PenStyle}
```
public long PenStyle
```


The pen style

### StyleEntry {#StyleEntry}
```
public long[] StyleEntry
```


An optional array of 32-bit unsigned integers that defines the lengths of dashes and gaps in the line drawn by this pen, when the value of PenStyle is PS\_USERSTYLE line style for the pen. The array contains a number of entries specified by NumStyleEntries, but it is used as if it repeated indefinitely The first entry in the array specifies the length of the first dash. The second entry specifies the length of the first gap. Thereafter, lengths of dashes and gaps alternate. If the pen type in the PenStyle field is PS\_GEOMETRIC, the lengths are specified in logical units; otherwise, the lengths are specified in device units.

### Width {#Width}
```
public long Width
```


A 32-bit unsigned integer that specifies the width of the line drawn by the pen. If the pen type in the PenStyle field is PS\_GEOMETRIC, this value is the width in logical units; otherwise, the width is specified in device units. If the pen type in the PenStyle field is PS\_COSMETIC, this value MUST be 0x00000001.

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

