---
title: BitmapCanvas
second_title: Aspose.BarCode for Java API Reference
description: Represents GDI bitmap canvas.
type: docs
weight: 12
url: /java/com.aspose.barcode.drawing/bitmapcanvas/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.drawing.GraphicsCanvas](../../com.aspose.barcode.drawing/graphicscanvas)

**All Implemented Interfaces:**
[com.aspose.barcode.drawing.ICanvas](../../com.aspose.barcode.drawing/icanvas), [com.aspose.barcode.drawing.IDrawImageCanvas](../../com.aspose.barcode.drawing/idrawimagecanvas)
```
public class BitmapCanvas extends GraphicsCanvas implements ICanvas, IDrawImageCanvas
```

Represents GDI bitmap canvas.
## Constructors

| Constructor | Description |
| --- | --- |
| [BitmapCanvas(System.Drawing.Bitmap output, Dpi dpi, CanvasQualityMode imageMode, int textHint)](#BitmapCanvas-com.aspose.ms.System.Drawing.Bitmap-com.aspose.barcode.drawing.Dpi-com.aspose.barcode.drawing.CanvasQualityMode-int-) |  |
| [BitmapCanvas(System.Drawing.Bitmap output)](#BitmapCanvas-com.aspose.ms.System.Drawing.Bitmap-) |  |
## Methods

| Method | Description |
| --- | --- |
| [clear(System.Drawing.Color color)](#clear-com.aspose.ms.System.Drawing.Color-) |  |
| [createBrush(System.Drawing.Color color)](#createBrush-com.aspose.ms.System.Drawing.Color-) |  |
| [createPen(System.Drawing.Color color, float thickness)](#createPen-com.aspose.ms.System.Drawing.Color-float-) |  |
| [dispose()](#dispose--) |  |
| [drawImage(System.Drawing.Bitmap bitmap, System.Drawing.Rectangle dst, System.Drawing.Rectangle src)](#drawImage-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Drawing.Rectangle-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [drawLine(IPen p, System.Drawing.Point p1, System.Drawing.Point p2)](#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [drawLine(IPen p, System.Drawing.PointF p1, System.Drawing.PointF p2)](#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) |  |
| [drawRectangle(IPen p, System.Drawing.Rectangle rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [drawRectangle(IPen p, System.Drawing.RectangleF rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [drawText(String text, System.Drawing.Font font, IBrush b, System.Drawing.PointF origin)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-) |  |
| [drawText(String text, System.Drawing.Font font, IBrush b, System.Drawing.RectangleF bounds)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) |  |
| [drawText(String text, System.Drawing.Font font, IBrush b, float x, float y)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-float-float-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillEllipse(IBrush b, System.Drawing.RectangleF rectangle)](#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [fillPolygon(IBrush b, System.Drawing.Point[] points)](#fillPolygon-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Point---) |  |
| [fillRectangle(IBrush b, System.Drawing.Rectangle rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [fillRectangle(IBrush b, System.Drawing.RectangleF rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getCanvasSize()](#getCanvasSize--) |  |
| [getClass()](#getClass--) |  |
| [getOffsetX()](#getOffsetX--) |  |
| [getOffsetY()](#getOffsetY--) |  |
| [getQualityMode()](#getQualityMode--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotateTransform(float angle)](#rotateTransform-float-) |  |
| [setScaleX(float scaleX)](#setScaleX-float-) |  |
| [toString()](#toString--) |  |
| [translateTransform(float offsetX, float offsetY)](#translateTransform-float-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BitmapCanvas(System.Drawing.Bitmap output, Dpi dpi, CanvasQualityMode imageMode, int textHint) {#BitmapCanvas-com.aspose.ms.System.Drawing.Bitmap-com.aspose.barcode.drawing.Dpi-com.aspose.barcode.drawing.CanvasQualityMode-int-}
```
public BitmapCanvas(System.Drawing.Bitmap output, Dpi dpi, CanvasQualityMode imageMode, int textHint)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | com.aspose.ms.System.Drawing.Bitmap |  |
| dpi | [Dpi](../../com.aspose.barcode.drawing/dpi) |  |
| imageMode | [CanvasQualityMode](../../com.aspose.barcode.drawing/canvasqualitymode) |  |
| textHint | int |  |

### BitmapCanvas(System.Drawing.Bitmap output) {#BitmapCanvas-com.aspose.ms.System.Drawing.Bitmap-}
```
public BitmapCanvas(System.Drawing.Bitmap output)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | com.aspose.ms.System.Drawing.Bitmap |  |

### clear(System.Drawing.Color color) {#clear-com.aspose.ms.System.Drawing.Color-}
```
public void clear(System.Drawing.Color color)
```


Clears all canvas with specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color |  |

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




### drawImage(System.Drawing.Bitmap bitmap, System.Drawing.Rectangle dst, System.Drawing.Rectangle src) {#drawImage-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Drawing.Rectangle-com.aspose.ms.System.Drawing.Rectangle-}
```
public void drawImage(System.Drawing.Bitmap bitmap, System.Drawing.Rectangle dst, System.Drawing.Rectangle src)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | com.aspose.ms.System.Drawing.Bitmap |  |
| dst | com.aspose.ms.System.Drawing.Rectangle |  |
| src | com.aspose.ms.System.Drawing.Rectangle |  |

### drawLine(IPen p, System.Drawing.Point p1, System.Drawing.Point p2) {#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public void drawLine(IPen p, System.Drawing.Point p1, System.Drawing.Point p2)
```


Draws line between two points with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| p | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| p1 | com.aspose.ms.System.Drawing.Point |  |
| p2 | com.aspose.ms.System.Drawing.Point |  |

### drawLine(IPen p, System.Drawing.PointF p1, System.Drawing.PointF p2) {#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-}
```
public void drawLine(IPen p, System.Drawing.PointF p1, System.Drawing.PointF p2)
```


Draws line between two points with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| p | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| p1 | com.aspose.ms.System.Drawing.PointF |  |
| p2 | com.aspose.ms.System.Drawing.PointF |  |

### drawRectangle(IPen p, System.Drawing.Rectangle rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-}
```
public void drawRectangle(IPen p, System.Drawing.Rectangle rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| p | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### drawRectangle(IPen p, System.Drawing.RectangleF rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawRectangle(IPen p, System.Drawing.RectangleF rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| p | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| rectangle | com.aspose.ms.System.Drawing.RectangleF |  |

### drawText(String text, System.Drawing.Font font, IBrush b, System.Drawing.PointF origin) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-}
```
public void drawText(String text, System.Drawing.Font font, IBrush b, System.Drawing.PointF origin)
```


Draws text from specified origin point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| b | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| origin | com.aspose.ms.System.Drawing.PointF |  |

### drawText(String text, System.Drawing.Font font, IBrush b, System.Drawing.RectangleF bounds) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawText(String text, System.Drawing.Font font, IBrush b, System.Drawing.RectangleF bounds)
```


Draws text in the specified text box rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| b | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
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

### drawText(String text, System.Drawing.Font font, IBrush b, float x, float y) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-float-float-}
```
public void drawText(String text, System.Drawing.Font font, IBrush b, float x, float y)
```


Draws text from specified origin point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| b | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| x | float |  |
| y | float |  |

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
### fillEllipse(IBrush b, System.Drawing.RectangleF rectangle) {#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void fillEllipse(IBrush b, System.Drawing.RectangleF rectangle)
```


Fills ellipse with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| rectangle | com.aspose.ms.System.Drawing.RectangleF |  |

### fillPolygon(IBrush b, System.Drawing.Point[] points) {#fillPolygon-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Point---}
```
public void fillPolygon(IBrush b, System.Drawing.Point[] points)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| points | com.aspose.ms.System.Drawing.Point[] |  |

### fillRectangle(IBrush b, System.Drawing.Rectangle rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-}
```
public void fillRectangle(IBrush b, System.Drawing.Rectangle rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### fillRectangle(IBrush b, System.Drawing.RectangleF rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void fillRectangle(IBrush b, System.Drawing.RectangleF rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
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

