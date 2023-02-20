---
title: ICanvas
second_title: Aspose.BarCode for Java API Reference
description: Represents generic canvas for barcode generation drawing.
type: docs
weight: 24
url: /java/com.aspose.barcode.drawing/icanvas/
---```
public interface ICanvas
```

Represents generic canvas for barcode generation drawing.
## Methods

| Method | Description |
| --- | --- |
| [clear(int color)](#clear-int-) | Clears all canvas with specified color. |
| [createBrush(int color)](#createBrush-int-) | Creates brush for current canvas. |
| [createPen(int color, float thickness)](#createPen-int-float-) | Creates pen for current canvas. |
| [drawLine(IPen pen, Point p1, Point p2)](#drawLine-com.aspose.barcode.drawing.IPen-android.graphics.Point-android.graphics.Point-) | Draws line between two points with specified pen. |
| [drawLine(IPen pen, PointF p1, PointF p2)](#drawLine-com.aspose.barcode.drawing.IPen-android.graphics.PointF-android.graphics.PointF-) | Draws line between two points with specified pen. |
| [drawRectangle(IPen pen, System.Drawing.Rectangle rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-) | Draws rectangle border with specified pen. |
| [drawRectangle(IPen pen, System.Drawing.RectangleF rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-) | Draws rectangle border with specified pen. |
| [drawText(String text, TextPaint font, IBrush brush, PointF origin)](#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-android.graphics.PointF-) | Draws text from specified origin point. |
| [drawText(String text, TextPaint font, IBrush brush, System.Drawing.RectangleF bounds)](#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) | Draws text in the specified text box rectangle. |
| [drawText(String text, TextPaint font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)](#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) | Draws text in the specified text box rectangle with additional options. |
| [drawText(String text, TextPaint font, IBrush brush, float x, float y)](#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-float-float-) | Draws text from specified origin point. |
| [fillEllipse(IBrush brush, System.Drawing.RectangleF rectangle)](#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) | Fills ellipse with specified brush. |
| [fillPolygon(IBrush brush, Point[] points)](#fillPolygon-com.aspose.barcode.drawing.IBrush-android.graphics.Point---) |  |
| [fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-) | Fills rectangle with specified brush. |
| [fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) | Fills rectangle with specified brush. |
| [getCanvasSize()](#getCanvasSize--) |  |
| [getOffsetX()](#getOffsetX--) |  |
| [getOffsetY()](#getOffsetY--) |  |
| [getQualityMode()](#getQualityMode--) |  |
| [rotateTransform(float angle)](#rotateTransform-float-) | Applies rotate transform for all further drawing. |
| [setScaleX(float scaleX)](#setScaleX-float-) | Sets scale factor for all further drawings |
| [translateTransform(float offsetX, float offsetY)](#translateTransform-float-float-) | Applies translate transform for all further drawing. |
### clear(int color) {#clear-int-}
```
public abstract void clear(int color)
```


Clears all canvas with specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | int | Color to clear. |

### createBrush(int color) {#createBrush-int-}
```
public abstract IBrush createBrush(int color)
```


Creates brush for current canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | int | SOLID color of the brush. |

**Returns:**
com.aspose.barcode.drawing.IBrush - Brush, which can be used with this canvas.
### createPen(int color, float thickness) {#createPen-int-float-}
```
public abstract IPen createPen(int color, float thickness)
```


Creates pen for current canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | int | SOLID color of the pen. |
| thickness | float | Thickness in pixels of the pen. |

**Returns:**
com.aspose.barcode.drawing.IPen - Pen, which can be used with this canvas.
### drawLine(IPen pen, Point p1, Point p2) {#drawLine-com.aspose.barcode.drawing.IPen-android.graphics.Point-android.graphics.Point-}
```
public abstract void drawLine(IPen pen, Point p1, Point p2)
```


Draws line between two points with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | com.aspose.barcode.drawing.IPen | Pen to draw. |
| p1 | android.graphics.Point | Start line point. |
| p2 | android.graphics.Point | End line point. |

### drawLine(IPen pen, PointF p1, PointF p2) {#drawLine-com.aspose.barcode.drawing.IPen-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void drawLine(IPen pen, PointF p1, PointF p2)
```


Draws line between two points with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | com.aspose.barcode.drawing.IPen | Pen to draw. |
| p1 | android.graphics.PointF | Start line point. |
| p2 | android.graphics.PointF | End line point. |

### drawRectangle(IPen pen, System.Drawing.Rectangle rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-}
```
public abstract void drawRectangle(IPen pen, System.Drawing.Rectangle rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | com.aspose.barcode.drawing.IPen | Pen to draw. |
| rectangle | com.aspose.ms.System.Drawing.Rectangle | Rectangle coordinates in pixels to draw. |

### drawRectangle(IPen pen, System.Drawing.RectangleF rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-}
```
public abstract void drawRectangle(IPen pen, System.Drawing.RectangleF rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | com.aspose.barcode.drawing.IPen | Pen to draw. |
| rectangle | com.aspose.ms.System.Drawing.RectangleF | Rectangle coordinates in pixels to draw. |

### drawText(String text, TextPaint font, IBrush brush, PointF origin) {#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-android.graphics.PointF-}
```
public abstract void drawText(String text, TextPaint font, IBrush brush, PointF origin)
```


Draws text from specified origin point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to draw. |
| font | android.text.TextPaint | Font of the text. |
| brush | com.aspose.barcode.drawing.IBrush | Brush to fill text. |
| origin | android.graphics.PointF | Origin point of the text. |

### drawText(String text, TextPaint font, IBrush brush, System.Drawing.RectangleF bounds) {#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public abstract void drawText(String text, TextPaint font, IBrush brush, System.Drawing.RectangleF bounds)
```


Draws text in the specified text box rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to draw. |
| font | android.text.TextPaint | Font of the text. |
| brush | com.aspose.barcode.drawing.IBrush | Brush to fill text. |
| bounds | com.aspose.ms.System.Drawing.RectangleF | Bounds of the text box. |

### drawText(String text, TextPaint font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options) {#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-}
```
public abstract void drawText(String text, TextPaint font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)
```


Draws text in the specified text box rectangle with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to draw. |
| font | android.text.TextPaint | Font of the text. |
| brush | com.aspose.barcode.drawing.IBrush | Brush to fill text. |
| bounds | com.aspose.ms.System.Drawing.RectangleF | Bounds of the text box. |
| options | com.aspose.barcode.drawing.TextOptions | Additional drawing options. |

### drawText(String text, TextPaint font, IBrush brush, float x, float y) {#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-float-float-}
```
public abstract void drawText(String text, TextPaint font, IBrush brush, float x, float y)
```


Draws text from specified origin point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to draw. |
| font | android.text.TextPaint | Font of the text. |
| brush | com.aspose.barcode.drawing.IBrush | Brush to fill text. |
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
| brush | com.aspose.barcode.drawing.IBrush | Brush to fill. |
| rectangle | com.aspose.ms.System.Drawing.RectangleF | Bounds of ellipse in pixels to fill. |

### fillPolygon(IBrush brush, Point[] points) {#fillPolygon-com.aspose.barcode.drawing.IBrush-android.graphics.Point---}
```
public abstract void fillPolygon(IBrush brush, Point[] points)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | com.aspose.barcode.drawing.IBrush |  |
| points | android.graphics.Point[] |  |

### fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-}
```
public abstract void fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | com.aspose.barcode.drawing.IBrush | Brush to fill. |
| rectangle | com.aspose.ms.System.Drawing.Rectangle | Rectangle coordinates in pixels to fill. |

### fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public abstract void fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | com.aspose.barcode.drawing.IBrush | Brush to fill. |
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
com.aspose.barcode.drawing.CanvasQualityMode - Gets image quality mode.
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
| offsetX | float | Offset X in pixels. |
| offsetY | float | Offset Y in pixels. |

