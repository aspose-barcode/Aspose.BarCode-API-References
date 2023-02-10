---
title: EmfCanvas
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.drawing.emf/emfcanvas/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.drawing.ICanvas](../../com.aspose.barcode.drawing/icanvas)
```
public class EmfCanvas implements ICanvas
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCanvas(int width, int height, System.IO.Stream output, double resolution, CanvasQualityMode qualityMode)](#EmfCanvas-int-int-com.aspose.ms.System.IO.Stream-double-com.aspose.barcode.drawing.CanvasQualityMode-) | Initializes new instance of class  EmfCanvasV3 . |
## Methods

| Method | Description |
| --- | --- |
| [clear(System.Drawing.Color color)](#clear-com.aspose.ms.System.Drawing.Color-) | Clears all canvas with specified color. |
| [createBrush(System.Drawing.Color color)](#createBrush-com.aspose.ms.System.Drawing.Color-) | Creates brush for current canvas. |
| [createPen(System.Drawing.Color color, float thickness)](#createPen-com.aspose.ms.System.Drawing.Color-float-) | Creates pen for current canvas. |
| [dispose()](#dispose--) | Disposes all internal resources. |
| [drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2)](#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Draws line between two points with specified pen. |
| [drawLine(IPen pen, System.Drawing.PointF p1, System.Drawing.PointF p2)](#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | Draws line between two points with specified pen. |
| [drawRectangle(IPen pen, System.Drawing.Rectangle rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-) | Draws rectangle border with specified pen. |
| [drawRectangle(IPen pen, System.Drawing.RectangleF rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-) | Draws rectangle border with specified pen. |
| [drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-) | Draws text from specified origin point. |
| [drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) | Draws text in the specified text box rectangle. |
| [drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) | Draws text in the specified text box rectangle with additional options. |
| [drawText(String text, System.Drawing.Font font, IBrush brush, float x, float y)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-float-float-) | Draws text from specified origin point. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillEllipse(IBrush brush, System.Drawing.RectangleF rectangle)](#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) | Fills ellipse with specified brush. |
| [fillPolygon(IBrush brush, System.Drawing.Point[] points)](#fillPolygon-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Point---) | Fills polygon with specified brush. |
| [fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-) | Fills rectangle with specified brush. |
| [fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) | Fills rectangle with specified brush. |
| [getCanvasSize()](#getCanvasSize--) | Gets actual canvas size in pixels. |
| [getClass()](#getClass--) |  |
| [getOffsetX()](#getOffsetX--) | Gets translate offset X in pixels. |
| [getOffsetY()](#getOffsetY--) | Gets translate offset Y in pixels. |
| [getQualityMode()](#getQualityMode--) | Gets image quality mode. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotateTransform(float angle)](#rotateTransform-float-) | Applies rotate transform for all further drawing. |
| [setScaleX(float scaleX)](#setScaleX-float-) | Sets scale factor for all further drawings |
| [toString()](#toString--) |  |
| [translateTransform(float offsetX, float offsetY)](#translateTransform-float-float-) | Applies translate transform for all further drawing. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmfCanvas(int width, int height, System.IO.Stream output, double resolution, CanvasQualityMode qualityMode) {#EmfCanvas-int-int-com.aspose.ms.System.IO.Stream-double-com.aspose.barcode.drawing.CanvasQualityMode-}
```
public EmfCanvas(int width, int height, System.IO.Stream output, double resolution, CanvasQualityMode qualityMode)
```


Initializes new instance of class  EmfCanvasV3 .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Desired width of output EMF image. |
| height | int | Desired height of output EMF image. |
| output | com.aspose.ms.System.IO.Stream | Stream to write EMF data. |
| resolution | double | Resolution of the image |
| qualityMode | [CanvasQualityMode](../../com.aspose.barcode.drawing/canvasqualitymode) | quality mode of text drawing |

### clear(System.Drawing.Color color) {#clear-com.aspose.ms.System.Drawing.Color-}
```
public void clear(System.Drawing.Color color)
```


Clears all canvas with specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color | Color to clear. |

### createBrush(System.Drawing.Color color) {#createBrush-com.aspose.ms.System.Drawing.Color-}
```
public IBrush createBrush(System.Drawing.Color color)
```


Creates brush for current canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color | Solid color of the brush. |

**Returns:**
[IBrush](../../com.aspose.barcode.drawing/ibrush) - Brush, which can be used with this canvas.
### createPen(System.Drawing.Color color, float thickness) {#createPen-com.aspose.ms.System.Drawing.Color-float-}
```
public IPen createPen(System.Drawing.Color color, float thickness)
```


Creates pen for current canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color | Solid color of the pen. |
| thickness | float | Thickness in pixels of the pen. |

**Returns:**
[IPen](../../com.aspose.barcode.drawing/ipen) - Pen, which can be used with this canvas.
### dispose() {#dispose--}
```
public void dispose()
```


Disposes all internal resources.

### drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2) {#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public void drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2)
```


Draws line between two points with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) | Pen to draw. |
| p1 | com.aspose.ms.System.Drawing.Point | Start line point. |
| p2 | com.aspose.ms.System.Drawing.Point | End line point. |

### drawLine(IPen pen, System.Drawing.PointF p1, System.Drawing.PointF p2) {#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public void drawLine(IPen pen, System.Drawing.PointF p1, System.Drawing.PointF p2)
```


Draws line between two points with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) | Pen to draw. |
| p1 | com.aspose.ms.System.Drawing.PointF | Start line point. |
| p2 | com.aspose.ms.System.Drawing.PointF | End line point. |

### drawRectangle(IPen pen, System.Drawing.Rectangle rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-}
```
public void drawRectangle(IPen pen, System.Drawing.Rectangle rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) | Pen to draw. |
| rectangle | com.aspose.ms.System.Drawing.Rectangle | Rectangle coordinates in pixels to draw. |

### drawRectangle(IPen pen, System.Drawing.RectangleF rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawRectangle(IPen pen, System.Drawing.RectangleF rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) | Pen to draw. |
| rectangle | com.aspose.ms.System.Drawing.RectangleF | Rectangle coordinates in pixels to draw. |

### drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-}
```
public void drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin)
```


Draws text from specified origin point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to draw. |
| font | com.aspose.ms.System.Drawing.Font | Font of the text. |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) | Brush to fill text. |
| origin | com.aspose.ms.System.Drawing.PointF | Origin point of the text. |

### drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds)
```


Draws text in the specified text box rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to draw. |
| font | com.aspose.ms.System.Drawing.Font | Font of the text. |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) | Brush to fill text. |
| bounds | com.aspose.ms.System.Drawing.RectangleF | Bounds of the text box. |

### drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-}
```
public void drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)
```


Draws text in the specified text box rectangle with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to draw. |
| font | com.aspose.ms.System.Drawing.Font | Font of the text. |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) | Brush to fill text. |
| bounds | com.aspose.ms.System.Drawing.RectangleF | Bounds of the text box. |
| options | [TextOptions](../../com.aspose.barcode.drawing/textoptions) | Additional drawing options. |

### drawText(String text, System.Drawing.Font font, IBrush brush, float x, float y) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-float-float-}
```
public void drawText(String text, System.Drawing.Font font, IBrush brush, float x, float y)
```


Draws text from specified origin point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to draw. |
| font | com.aspose.ms.System.Drawing.Font | Font of the text. |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) | Brush to fill text. |
| x | float | X-coordinate in pixels of origin point. |
| y | float | Y-coordinate in pixels of origin point. |

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
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) | Brush to fill. |
| rectangle | com.aspose.ms.System.Drawing.RectangleF | Bounds of ellipse in pixels to fill. |

### fillPolygon(IBrush brush, System.Drawing.Point[] points) {#fillPolygon-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Point---}
```
public void fillPolygon(IBrush brush, System.Drawing.Point[] points)
```


Fills polygon with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) | Brush to fill. |
| points | com.aspose.ms.System.Drawing.Point[] | Points, which represent polygon. |

### fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-}
```
public void fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) | Brush to fill. |
| rectangle | com.aspose.ms.System.Drawing.Rectangle | Rectangle coordinates in pixels to fill. |

### fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) | Brush to fill. |
| rectangle | com.aspose.ms.System.Drawing.RectangleF | Rectangle coordinates in pixels to fill. |

### getCanvasSize() {#getCanvasSize--}
```
public System.Drawing.Size getCanvasSize()
```


Gets actual canvas size in pixels.

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


Gets translate offset X in pixels.

**Returns:**
float
### getOffsetY() {#getOffsetY--}
```
public float getOffsetY()
```


Gets translate offset Y in pixels.

**Returns:**
float
### getQualityMode() {#getQualityMode--}
```
public CanvasQualityMode getQualityMode()
```


Gets image quality mode.

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
| angle | float | Angle of rotation in degrees. |

### setScaleX(float scaleX) {#setScaleX-float-}
```
public void setScaleX(float scaleX)
```


Sets scale factor for all further drawings

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | scale factor |

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
| offsetX | float | Offset X in pixels. |
| offsetY | float | Offset Y in pixels. |

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

