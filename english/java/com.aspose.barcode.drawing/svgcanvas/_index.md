---
title: SvgCanvas
second_title: Aspose.BarCode for Java API Reference
description: Represents SVG canvas.
type: docs
weight: 24
url: /java/com.aspose.barcode.drawing/svgcanvas/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.drawing.ICanvas](../../com.aspose.barcode.drawing/icanvas), com.aspose.ms.System.IDisposable
```
public class SvgCanvas implements ICanvas, System.IDisposable
```

Represents SVG canvas.
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgCanvas(int width, int height, System.IO.Stream output, float dpi, CanvasQualityMode qualityMode)](#SvgCanvas-int-int-com.aspose.ms.System.IO.Stream-float-com.aspose.barcode.drawing.CanvasQualityMode-) |  |
## Methods

| Method | Description |
| --- | --- |
| [clear(System.Drawing.Color color)](#clear-com.aspose.ms.System.Drawing.Color-) |  |
| [closeTransformGroup()](#closeTransformGroup--) |  |
| [createBrush(System.Drawing.Color color)](#createBrush-com.aspose.ms.System.Drawing.Color-) |  |
| [createPen(System.Drawing.Color color, float thickness)](#createPen-com.aspose.ms.System.Drawing.Color-float-) |  |
| [dispose()](#dispose--) |  |
| [drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2)](#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [drawLine(IPen pen, System.Drawing.PointF p1, System.Drawing.PointF p2)](#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) |  |
| [drawRectangle(IPen pen, System.Drawing.Rectangle rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [drawRectangle(IPen pen, System.Drawing.RectangleF rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-) |  |
| [drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) |  |
| [drawText(String text, System.Drawing.Font font, IBrush brush, float x, float y)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-float-float-) |  |
| [endDrawing()](#endDrawing--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillEllipse(IBrush brush, System.Drawing.RectangleF rectangle)](#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [fillPolygon(IBrush brush, System.Drawing.Point[] points)](#fillPolygon-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Point---) |  |
| [fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getCanvasSize()](#getCanvasSize--) |  |
| [getClass()](#getClass--) |  |
| [getOffsetX()](#getOffsetX--) |  |
| [getOffsetY()](#getOffsetY--) |  |
| [getQualityMode()](#getQualityMode--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotateTransform(float angle)](#rotateTransform-float-) |  |
| [scaleTransform(float dx, float dy)](#scaleTransform-float-float-) |  |
| [setScaleX(float scaleX)](#setScaleX-float-) |  |
| [toString()](#toString--) |  |
| [translateTransform(float offsetX, float offsetY)](#translateTransform-float-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SvgCanvas(int width, int height, System.IO.Stream output, float dpi, CanvasQualityMode qualityMode) {#SvgCanvas-int-int-com.aspose.ms.System.IO.Stream-float-com.aspose.barcode.drawing.CanvasQualityMode-}
```
public SvgCanvas(int width, int height, System.IO.Stream output, float dpi, CanvasQualityMode qualityMode)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int |  |
| height | int |  |
| output | com.aspose.ms.System.IO.Stream |  |
| dpi | float |  |
| qualityMode | [CanvasQualityMode](../../com.aspose.barcode.drawing/canvasqualitymode) |  |

### clear(System.Drawing.Color color) {#clear-com.aspose.ms.System.Drawing.Color-}
```
public void clear(System.Drawing.Color color)
```


Clears all canvas with specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color |  |

### closeTransformGroup() {#closeTransformGroup--}
```
public void closeTransformGroup()
```




### createBrush(System.Drawing.Color color) {#createBrush-com.aspose.ms.System.Drawing.Color-}
```
public IBrush createBrush(System.Drawing.Color color)
```


Creates brush for current canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color |  |

**Returns:**
[IBrush](../../com.aspose.barcode.drawing/ibrush)
### createPen(System.Drawing.Color color, float thickness) {#createPen-com.aspose.ms.System.Drawing.Color-float-}
```
public IPen createPen(System.Drawing.Color color, float thickness)
```


Creates pen for current canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color |  |
| thickness | float |  |

**Returns:**
[IPen](../../com.aspose.barcode.drawing/ipen)
### dispose() {#dispose--}
```
public void dispose()
```




### drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2) {#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public void drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2)
```


Draws line between two points with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| p1 | com.aspose.ms.System.Drawing.Point |  |
| p2 | com.aspose.ms.System.Drawing.Point |  |

### drawLine(IPen pen, System.Drawing.PointF p1, System.Drawing.PointF p2) {#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public void drawLine(IPen pen, System.Drawing.PointF p1, System.Drawing.PointF p2)
```


Draws line between two points with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| p1 | com.aspose.ms.System.Drawing.PointF |  |
| p2 | com.aspose.ms.System.Drawing.PointF |  |

### drawRectangle(IPen pen, System.Drawing.Rectangle rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-}
```
public void drawRectangle(IPen pen, System.Drawing.Rectangle rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### drawRectangle(IPen pen, System.Drawing.RectangleF rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawRectangle(IPen pen, System.Drawing.RectangleF rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| rectangle | com.aspose.ms.System.Drawing.RectangleF |  |

### drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-}
```
public void drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin)
```


Draws text from specified origin point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| origin | com.aspose.ms.System.Drawing.PointF |  |

### drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds)
```


Draws text in the specified text box rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| bounds | com.aspose.ms.System.Drawing.RectangleF |  |

### drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-}
```
public void drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)
```


Draws text in the specified text box rectangle with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| bounds | com.aspose.ms.System.Drawing.RectangleF |  |
| options | [TextOptions](../../com.aspose.barcode.drawing/textoptions) |  |

### drawText(String text, System.Drawing.Font font, IBrush brush, float x, float y) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-float-float-}
```
public void drawText(String text, System.Drawing.Font font, IBrush brush, float x, float y)
```


Draws text from specified origin point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| x | float |  |
| y | float |  |

### endDrawing() {#endDrawing--}
```
public void endDrawing()
```




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
### fillEllipse(IBrush brush, System.Drawing.RectangleF rectangle) {#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void fillEllipse(IBrush brush, System.Drawing.RectangleF rectangle)
```


Fills ellipse with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| rectangle | com.aspose.ms.System.Drawing.RectangleF |  |

### fillPolygon(IBrush brush, System.Drawing.Point[] points) {#fillPolygon-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Point---}
```
public void fillPolygon(IBrush brush, System.Drawing.Point[] points)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| points | com.aspose.ms.System.Drawing.Point[] |  |

### fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-}
```
public void fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| rectangle | com.aspose.ms.System.Drawing.RectangleF |  |

### getCanvasSize() {#getCanvasSize--}
```
public System.Drawing.Size getCanvasSize()
```




**Returns:**
com.aspose.ms.System.Drawing.Size
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOffsetX() {#getOffsetX--}
```
public float getOffsetX()
```




**Returns:**
float
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```




**Returns:**
float
### getQualityMode() {#getQualityMode--}
```
public CanvasQualityMode getQualityMode()
```




**Returns:**
[CanvasQualityMode](../../com.aspose.barcode.drawing/canvasqualitymode)
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




### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Applies rotate transform for all further drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float |  |

### scaleTransform(float dx, float dy) {#scaleTransform-float-float-}
```
public void scaleTransform(float dx, float dy)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx | float |  |
| dy | float |  |

### setScaleX(float scaleX) {#setScaleX-float-}
```
public void setScaleX(float scaleX)
```


Sets scale factor for all further drawings

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float offsetX, float offsetY) {#translateTransform-float-float-}
```
public void translateTransform(float offsetX, float offsetY)
```


Applies translate transform for all further drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offsetX | float |  |
| offsetY | float |  |

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

