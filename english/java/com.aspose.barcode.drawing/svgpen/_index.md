---
title: SvgPen
second_title: Aspose.BarCode for Java API Reference
description: Represents pen for SvgCanvas.
type: docs
weight: 27
url: /java/com.aspose.barcode.drawing/svgpen/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.drawing.IPen](../../com.aspose.barcode.drawing/ipen)
```
public class SvgPen implements IPen
```

Represents pen for  SvgCanvas .
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgPen(System.Drawing.Color color, float thickness)](#SvgPen-com.aspose.ms.System.Drawing.Color-float-) | Initializes new instance of class  SvgPen . |
## Methods

| Method | Description |
| --- | --- |
| [dispose()](#dispose--) | Disposes pen and internal GDI resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Gets solid color of pen. |
| [getDashStyle()](#getDashStyle--) | Gets dash style of pen. |
| [getSvgColor()](#getSvgColor--) | Gets color SVG wrapper. |
| [getThickness()](#getThickness--) | Gets thickness of pen in pixels. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDashStyle(PenDashStyle value)](#setDashStyle-com.aspose.barcode.drawing.PenDashStyle-) | Gets dash style of pen. |
| [toString()](#toString--) |  |
| [tryGetDashPattern()](#tryGetDashPattern--) | Gets dash pattern for SVG. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SvgPen(System.Drawing.Color color, float thickness) {#SvgPen-com.aspose.ms.System.Drawing.Color-float-}
```
public SvgPen(System.Drawing.Color color, float thickness)
```


Initializes new instance of class  SvgPen .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color | Solid color of pen. |
| thickness | float | Thickness of pen in pixels. |

### dispose() {#dispose--}
```
public void dispose()
```


Disposes pen and internal GDI resources.

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
### getColor() {#getColor--}
```
public System.Drawing.Color getColor()
```


Gets solid color of pen.

**Returns:**
com.aspose.ms.System.Drawing.Color
### getDashStyle() {#getDashStyle--}
```
public PenDashStyle getDashStyle()
```


Gets dash style of pen.

**Returns:**
[PenDashStyle](../../com.aspose.barcode.drawing/pendashstyle)
### getSvgColor() {#getSvgColor--}
```
public SvgColor getSvgColor()
```


Gets color SVG wrapper.

**Returns:**
[SvgColor](../../com.aspose.barcode.drawing/svgcolor)
### getThickness() {#getThickness--}
```
public float getThickness()
```


Gets thickness of pen in pixels.

**Returns:**
float
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




### setDashStyle(PenDashStyle value) {#setDashStyle-com.aspose.barcode.drawing.PenDashStyle-}
```
public void setDashStyle(PenDashStyle value)
```


Gets dash style of pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PenDashStyle](../../com.aspose.barcode.drawing/pendashstyle) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetDashPattern() {#tryGetDashPattern--}
```
public float[] tryGetDashPattern()
```


Gets dash pattern for SVG.

**Returns:**
float[] - 
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

