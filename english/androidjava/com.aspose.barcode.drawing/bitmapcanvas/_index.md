---
title: BitmapCanvas
second_title: Aspose.BarCode for Android via Java API Reference
description: Represents GDI bitmap canvas.
type: docs
weight: 12
url: /androidjava/com.aspose.barcode.drawing/bitmapcanvas/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.drawing.GraphicsCanvas

**All Implemented Interfaces:**
com.aspose.barcode.drawing.ICanvas, com.aspose.barcode.drawing.IDrawImageCanvas
```
public class BitmapCanvas extends GraphicsCanvas implements ICanvas, IDrawImageCanvas
```

Represents GDI bitmap canvas.
## Constructors

| Constructor | Description |
| --- | --- |
| [BitmapCanvas(Bitmap output, Dpi dpi, CanvasQualityMode imageMode, TextRenderingHint textHint)](#BitmapCanvas-android.graphics.Bitmap-com.aspose.barcode.drawing.Dpi-com.aspose.barcode.drawing.CanvasQualityMode-com.aspose.barcode.generation.TextRenderingHint-) |  |
## Methods

| Method | Description |
| --- | --- |
| [adaptFontToActualResolution(TextPaint font)](#adaptFontToActualResolution-android.text.TextPaint-) |  |
| [clear(int color)](#clear-int-) |  |
| [createBrush(int color)](#createBrush-int-) |  |
| [createPen(int color, float thickness)](#createPen-int-float-) |  |
| [dispose()](#dispose--) |  |
| [drawImage(Bitmap bitmap, Rect dst, Rect src)](#drawImage-android.graphics.Bitmap-android.graphics.Rect-android.graphics.Rect-) |  |
| [drawLine(IPen pen, Point p1, Point p2)](#drawLine-com.aspose.barcode.drawing.IPen-android.graphics.Point-android.graphics.Point-) |  |
| [drawLine(IPen pen, PointF p1, PointF p2)](#drawLine-com.aspose.barcode.drawing.IPen-android.graphics.PointF-android.graphics.PointF-) |  |
| [drawRectangle(IPen p, System.Drawing.Rectangle rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [drawRectangle(IPen p, System.Drawing.RectangleF rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [drawText(String text, TextPaint font, IBrush brush, PointF origin)](#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-android.graphics.PointF-) |  |
| [drawText(String text, TextPaint font, IBrush b, System.Drawing.RectangleF bounds)](#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [drawText(String text, TextPaint font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)](#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) |  |
| [drawText(String text, TextPaint font, IBrush b, float x, float y)](#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-float-float-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillEllipse(IBrush b, System.Drawing.RectangleF rectangle)](#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [fillPolygon(IBrush brush, Point[] points)](#fillPolygon-com.aspose.barcode.drawing.IBrush-android.graphics.Point---) |  |
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
### BitmapCanvas(Bitmap output, Dpi dpi, CanvasQualityMode imageMode, TextRenderingHint textHint) {#BitmapCanvas-android.graphics.Bitmap-com.aspose.barcode.drawing.Dpi-com.aspose.barcode.drawing.CanvasQualityMode-com.aspose.barcode.generation.TextRenderingHint-}
```
public BitmapCanvas(Bitmap output, Dpi dpi, CanvasQualityMode imageMode, TextRenderingHint textHint)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | android.graphics.Bitmap |  |
| dpi | com.aspose.barcode.drawing.Dpi |  |
| imageMode | com.aspose.barcode.drawing.CanvasQualityMode |  |
| textHint | com.aspose.barcode.generation.TextRenderingHint |  |

### adaptFontToActualResolution(TextPaint font) {#adaptFontToActualResolution-android.text.TextPaint-}
```
public TextPaint adaptFontToActualResolution(TextPaint font)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| font | android.text.TextPaint |  |

**Returns:**
android.text.TextPaint
### clear(int color) {#clear-int-}
```
public void clear(int color)
```


Clears all canvas with specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | int |  |

### createBrush(int color) {#createBrush-int-}
```
public IBrush createBrush(int color)
```


Creates brush for current canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | int |  |

**Returns:**
com.aspose.barcode.drawing.IBrush
### createPen(int color, float thickness) {#createPen-int-float-}
```
public IPen createPen(int color, float thickness)
```


Creates pen for current canvas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | int |  |
| thickness | float |  |

**Returns:**
com.aspose.barcode.drawing.IPen
### dispose() {#dispose--}
```
public void dispose()
```




### drawImage(Bitmap bitmap, Rect dst, Rect src) {#drawImage-android.graphics.Bitmap-android.graphics.Rect-android.graphics.Rect-}
```
public void drawImage(Bitmap bitmap, Rect dst, Rect src)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | android.graphics.Bitmap |  |
| dst | android.graphics.Rect |  |
| src | android.graphics.Rect |  |

### drawLine(IPen pen, Point p1, Point p2) {#drawLine-com.aspose.barcode.drawing.IPen-android.graphics.Point-android.graphics.Point-}
```
public void drawLine(IPen pen, Point p1, Point p2)
```


Draws line between two points with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | com.aspose.barcode.drawing.IPen |  |
| p1 | android.graphics.Point |  |
| p2 | android.graphics.Point |  |

### drawLine(IPen pen, PointF p1, PointF p2) {#drawLine-com.aspose.barcode.drawing.IPen-android.graphics.PointF-android.graphics.PointF-}
```
public void drawLine(IPen pen, PointF p1, PointF p2)
```


Draws line between two points with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | com.aspose.barcode.drawing.IPen |  |
| p1 | android.graphics.PointF |  |
| p2 | android.graphics.PointF |  |

### drawRectangle(IPen p, System.Drawing.Rectangle rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-}
```
public void drawRectangle(IPen p, System.Drawing.Rectangle rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| p | com.aspose.barcode.drawing.IPen |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### drawRectangle(IPen p, System.Drawing.RectangleF rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawRectangle(IPen p, System.Drawing.RectangleF rectangle)
```


Draws rectangle border with specified pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| p | com.aspose.barcode.drawing.IPen |  |
| rectangle | com.aspose.ms.System.Drawing.RectangleF |  |

### drawText(String text, TextPaint font, IBrush brush, PointF origin) {#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-android.graphics.PointF-}
```
public void drawText(String text, TextPaint font, IBrush brush, PointF origin)
```


Draws text from specified origin point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | android.text.TextPaint |  |
| brush | com.aspose.barcode.drawing.IBrush |  |
| origin | android.graphics.PointF |  |

### drawText(String text, TextPaint font, IBrush b, System.Drawing.RectangleF bounds) {#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawText(String text, TextPaint font, IBrush b, System.Drawing.RectangleF bounds)
```


Draws text in the specified text box rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | android.text.TextPaint |  |
| b | com.aspose.barcode.drawing.IBrush |  |
| bounds | com.aspose.ms.System.Drawing.RectangleF |  |

### drawText(String text, TextPaint font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options) {#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-}
```
public void drawText(String text, TextPaint font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)
```


Draws text in the specified text box rectangle with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | android.text.TextPaint |  |
| brush | com.aspose.barcode.drawing.IBrush |  |
| bounds | com.aspose.ms.System.Drawing.RectangleF |  |
| options | com.aspose.barcode.drawing.TextOptions |  |

### drawText(String text, TextPaint font, IBrush b, float x, float y) {#drawText-java.lang.String-android.text.TextPaint-com.aspose.barcode.drawing.IBrush-float-float-}
```
public void drawText(String text, TextPaint font, IBrush b, float x, float y)
```


Draws text from specified origin point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | android.text.TextPaint |  |
| b | com.aspose.barcode.drawing.IBrush |  |
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
| b | com.aspose.barcode.drawing.IBrush |  |
| rectangle | com.aspose.ms.System.Drawing.RectangleF |  |

### fillPolygon(IBrush brush, Point[] points) {#fillPolygon-com.aspose.barcode.drawing.IBrush-android.graphics.Point---}
```
public void fillPolygon(IBrush brush, Point[] points)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | com.aspose.barcode.drawing.IBrush |  |
| points | android.graphics.Point[] |  |

### fillRectangle(IBrush b, System.Drawing.Rectangle rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-}
```
public void fillRectangle(IBrush b, System.Drawing.Rectangle rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b | com.aspose.barcode.drawing.IBrush |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### fillRectangle(IBrush b, System.Drawing.RectangleF rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void fillRectangle(IBrush b, System.Drawing.RectangleF rectangle)
```


Fills rectangle with specified brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| b | com.aspose.barcode.drawing.IBrush |  |
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
com.aspose.barcode.drawing.CanvasQualityMode
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

