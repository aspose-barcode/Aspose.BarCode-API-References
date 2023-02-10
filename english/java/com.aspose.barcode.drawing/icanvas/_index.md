---
title: ICanvas
second_title: Aspose.BarCode for Java API Reference
description: Represents generic canvas for barcode generation drawing.
type: docs
weight: 33
url: /java/com.aspose.barcode.drawing/icanvas/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface ICanvas extends System.IDisposable
```

Represents generic canvas for barcode generation drawing.
## Methods

| Method | Description |
| --- | --- |
| [clear(System.Drawing.Color color)](#clear-com.aspose.ms.System.Drawing.Color-) | Clears all canvas with specified color. |
| [createBrush(System.Drawing.Color color)](#createBrush-com.aspose.ms.System.Drawing.Color-) | Creates brush for current canvas. |
| [createPen(System.Drawing.Color color, float thickness)](#createPen-com.aspose.ms.System.Drawing.Color-float-) | Creates pen for current canvas. |
| [drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2)](#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) | Draws line between two points with specified pen. |
| [drawLine(IPen pen, System.Drawing.PointF p1, System.Drawing.PointF p2)](#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) | Draws line between two points with specified pen. |
| [drawRectangle(IPen pen, System.Drawing.Rectangle rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-) | Draws rectangle border with specified pen. |
| [drawRectangle(IPen pen, System.Drawing.RectangleF rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-) | Draws rectangle border with specified pen. |
| [drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-) | Draws text from specified origin point. |
| [drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) | Draws text in the specified text box rectangle. |
| [drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) | Draws text in the specified text box rectangle with additional options. |
| [drawText(String text, System.Drawing.Font font, IBrush brush, float x, float y)](#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-float-float-) | Draws text from specified origin point. |
| [fillEllipse(IBrush brush, System.Drawing.RectangleF rectangle)](#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) | Fills ellipse with specified brush. |
| [fillPolygon(IBrush brush, System.Drawing.Point[] points)](#fillPolygon-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Point---) |  |
| [fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-) | Fills rectangle with specified brush. |
| [fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) | Fills rectangle with specified brush. |
| [getCanvasSize()](#getCanvasSize--) |  |
| [getOffsetX()](#getOffsetX--) |  |
| [getOffsetY()](#getOffsetY--) |  |
| [getQualityMode()](#getQualityMode--) |  |
| [rotateTransform(float angle)](#rotateTransform-float-) | Applies rotate transform for all further drawing. |
| [setScaleX(float scaleX)](#setScaleX-float-) | Sets scale factor for all further drawings |
| [translateTransform(float offsetX, float offsetY)](#translateTransform-float-float-) | Applies translate transform for all further drawing. |
### clear(System.Drawing.Color color) {#clear-com.aspose.ms.System.Drawing.Color-}
```
public abstract void clear(System.Drawing.Color color)
```


Clears all canvas with specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color | Color to clear. |

### createBrush(System.Drawing.Color color) {#createBrush-com.aspose.ms.System.Drawing.Color-}
```
public abstract IBrush createBrush(System.Drawing.Color color)
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
public abstract IPen createPen(System.Drawing.Color color, float thickness)
```


Creates pen for current canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color | Solid color of the pen. |
| thickness | float | Thickness in pixels of the pen. |

**Returns:**
[IPen](../../com.aspose.barcode.drawing/ipen) - Pen, which can be used with this canvas.
### drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2) {#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public abstract void drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2)
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
public abstract void drawLine(IPen pen, System.Drawing.PointF p1, System.Drawing.PointF p2)
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
public abstract void drawRectangle(IPen pen, System.Drawing.Rectangle rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) | Pen to draw. |
| rectangle | com.aspose.ms.System.Drawing.Rectangle | Rectangle coordinates in pixels to draw. |

### drawRectangle(IPen pen, System.Drawing.RectangleF rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-}
```
public abstract void drawRectangle(IPen pen, System.Drawing.RectangleF rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) | Pen to draw. |
| rectangle | com.aspose.ms.System.Drawing.RectangleF | Rectangle coordinates in pixels to draw. |

### drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin) {#drawText-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-}
```
public abstract void drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin)
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
public abstract void drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds)
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
public abstract void drawText(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)
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
public abstract void drawText(String text, System.Drawing.Font font, IBrush brush, float x, float y)
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

### fillEllipse(IBrush brush, System.Drawing.RectangleF rectangle) {#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public abstract void fillEllipse(IBrush brush, System.Drawing.RectangleF rectangle)
```


Fills ellipse with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) | Brush to fill. |
| rectangle | com.aspose.ms.System.Drawing.RectangleF | Bounds of ellipse in pixels to fill. |

### fillPolygon(IBrush brush, System.Drawing.Point[] points) {#fillPolygon-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Point---}
```
public abstract void fillPolygon(IBrush brush, System.Drawing.Point[] points)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| points | com.aspose.ms.System.Drawing.Point[] |  |

### fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-}
```
public abstract void fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) | Brush to fill. |
| rectangle | com.aspose.ms.System.Drawing.Rectangle | Rectangle coordinates in pixels to fill. |

### fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public abstract void fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) | Brush to fill. |
| rectangle | com.aspose.ms.System.Drawing.RectangleF | Rectangle coordinates in pixels to fill. |

### getCanvasSize() {#getCanvasSize--}
```
public abstract System.Drawing.Size getCanvasSize()
```




**Returns:**
com.aspose.ms.System.Drawing.Size - Gets actual canvas size in pixels.
### getOffsetX() {#getOffsetX--}
```
public abstract float getOffsetX()
```




**Returns:**
float - Gets translate offset X in pixels.
### getOffsetY() {#getOffsetY--}
```
public abstract float getOffsetY()
```




**Returns:**
float - Gets translate offset Y in pixels.
### getQualityMode() {#getQualityMode--}
```
public abstract CanvasQualityMode getQualityMode()
```




**Returns:**
[CanvasQualityMode](../../com.aspose.barcode.drawing/canvasqualitymode) - Gets image quality mode.
### rotateTransform(float angle) {#rotateTransform-float-}
```
public abstract void rotateTransform(float angle)
```


Applies rotate transform for all further drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | Angle of rotation in degrees. |

### setScaleX(float scaleX) {#setScaleX-float-}
```
public abstract void setScaleX(float scaleX)
```


Sets scale factor for all further drawings

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | scale factor |

### translateTransform(float offsetX, float offsetY) {#translateTransform-float-float-}
```
public abstract void translateTransform(float offsetX, float offsetY)
```


Applies translate transform for all further drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offsetX | float | offset X in pixels. |
| offsetY | float | offset Y in pixels. |

