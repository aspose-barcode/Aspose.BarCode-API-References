---
title: EmfContainer
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.drawing.emf/emfcontainer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.drawing.emf.data.IEmfApplyWorldTransform](../../com.aspose.barcode.drawing.emf.data/iemfapplyworldtransform)
```
public class EmfContainer implements IEmfApplyWorldTransform
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfContainer(int width, int height, double resolution, CanvasQualityMode qualityMode)](#EmfContainer-int-int-double-com.aspose.barcode.drawing.CanvasQualityMode-) |  |
## Methods

| Method | Description |
| --- | --- |
| [clear(System.Drawing.Color color)](#clear-com.aspose.ms.System.Drawing.Color-) |  |
| [drawEllipse(IPen pen, System.Drawing.Rectangle rectangle)](#drawEllipse-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [drawEllipse(IPen pen, System.Drawing.RectangleF rectangle)](#drawEllipse-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2)](#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-) |  |
| [drawLine(IPen pen, System.Drawing.PointF p1, System.Drawing.PointF p2)](#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.PointF-com.aspose.ms.System.Drawing.PointF-) |  |
| [drawLines(IPen pen, System.Drawing.Point[] points)](#drawLines-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point---) |  |
| [drawPolygon(IPen pen, System.Drawing.Point[] points)](#drawPolygon-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point---) |  |
| [drawRectangle(IPen pen, System.Drawing.Rectangle rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [drawRectangle(IPen pen, System.Drawing.RectangleF rectangle)](#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [drawRectangleWithRect(IPen pen, System.Drawing.Rectangle rectangle)](#drawRectangleWithRect-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [drawRectangleWithRect(IPen pen, System.Drawing.RectangleF rectangle)](#drawRectangleWithRect-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [drawTextExt(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin)](#drawTextExt-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-) |  |
| [drawTextExt(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds)](#drawTextExt-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [drawTextExt(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)](#drawTextExt-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) |  |
| [drawTextSmall(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin)](#drawTextSmall-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-) |  |
| [drawTextSmall(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds)](#drawTextSmall-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [drawTextSmall(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)](#drawTextSmall-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillEllipse(IBrush brush, System.Drawing.Rectangle rectangle)](#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [fillEllipse(IBrush brush, System.Drawing.RectangleF rectangle)](#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [fillPolygon(IBrush brush, System.Drawing.Point[] points)](#fillPolygon-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Point---) |  |
| [fillRectangle(IBrush brush, System.Drawing.Rectangle rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle)](#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [fillRectangleWithRect(IBrush brush, System.Drawing.Rectangle rectangle)](#fillRectangleWithRect-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [fillRectangleWithRect(IBrush brush, System.Drawing.RectangleF rectangle)](#fillRectangleWithRect-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getCanvasSize()](#getCanvasSize--) |  |
| [getClass()](#getClass--) |  |
| [getQualityMode()](#getQualityMode--) |  |
| [getXform()](#getXform--) |  |
| [hashCode()](#hashCode--) |  |
| [modifyWorldTransform(EmfXForm form, long modifyWorldTransformMode)](#modifyWorldTransform-com.aspose.barcode.drawing.emf.objects.EmfXForm-long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotateTransform(float angle)](#rotateTransform-float-) | Applies rotate transform for all further drawing. |
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [scaleTransform(double scaleX, double scaleY)](#scaleTransform-double-double-) |  |
| [setWorldTransform(EmfXForm form)](#setWorldTransform-com.aspose.barcode.drawing.emf.objects.EmfXForm-) |  |
| [toString()](#toString--) |  |
| [translateTransform(double offsetX, double offsetY)](#translateTransform-double-double-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmfContainer(int width, int height, double resolution, CanvasQualityMode qualityMode) {#EmfContainer-int-int-double-com.aspose.barcode.drawing.CanvasQualityMode-}
```
public EmfContainer(int width, int height, double resolution, CanvasQualityMode qualityMode)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int |  |
| height | int |  |
| resolution | double |  |
| qualityMode | [CanvasQualityMode](../../com.aspose.barcode.drawing/canvasqualitymode) |  |

### clear(System.Drawing.Color color) {#clear-com.aspose.ms.System.Drawing.Color-}
```
public void clear(System.Drawing.Color color)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | com.aspose.ms.System.Drawing.Color |  |

### drawEllipse(IPen pen, System.Drawing.Rectangle rectangle) {#drawEllipse-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-}
```
public void drawEllipse(IPen pen, System.Drawing.Rectangle rectangle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### drawEllipse(IPen pen, System.Drawing.RectangleF rectangle) {#drawEllipse-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawEllipse(IPen pen, System.Drawing.RectangleF rectangle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| rectangle | com.aspose.ms.System.Drawing.RectangleF |  |

### drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2) {#drawLine-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-}
```
public void drawLine(IPen pen, System.Drawing.Point p1, System.Drawing.Point p2)
```




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




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| p1 | com.aspose.ms.System.Drawing.PointF |  |
| p2 | com.aspose.ms.System.Drawing.PointF |  |

### drawLines(IPen pen, System.Drawing.Point[] points) {#drawLines-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point---}
```
public void drawLines(IPen pen, System.Drawing.Point[] points)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| points | com.aspose.ms.System.Drawing.Point[] |  |

### drawPolygon(IPen pen, System.Drawing.Point[] points) {#drawPolygon-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Point---}
```
public void drawPolygon(IPen pen, System.Drawing.Point[] points)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| points | com.aspose.ms.System.Drawing.Point[] |  |

### drawRectangle(IPen pen, System.Drawing.Rectangle rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-}
```
public void drawRectangle(IPen pen, System.Drawing.Rectangle rectangle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### drawRectangle(IPen pen, System.Drawing.RectangleF rectangle) {#drawRectangle-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawRectangle(IPen pen, System.Drawing.RectangleF rectangle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| rectangle | com.aspose.ms.System.Drawing.RectangleF |  |

### drawRectangleWithRect(IPen pen, System.Drawing.Rectangle rectangle) {#drawRectangleWithRect-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.Rectangle-}
```
public void drawRectangleWithRect(IPen pen, System.Drawing.Rectangle rectangle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### drawRectangleWithRect(IPen pen, System.Drawing.RectangleF rectangle) {#drawRectangleWithRect-com.aspose.barcode.drawing.IPen-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawRectangleWithRect(IPen pen, System.Drawing.RectangleF rectangle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [IPen](../../com.aspose.barcode.drawing/ipen) |  |
| rectangle | com.aspose.ms.System.Drawing.RectangleF |  |

### drawTextExt(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin) {#drawTextExt-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-}
```
public void drawTextExt(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| origin | com.aspose.ms.System.Drawing.PointF |  |

### drawTextExt(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds) {#drawTextExt-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawTextExt(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| bounds | com.aspose.ms.System.Drawing.RectangleF |  |

### drawTextExt(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options) {#drawTextExt-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-}
```
public void drawTextExt(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| bounds | com.aspose.ms.System.Drawing.RectangleF |  |
| options | [TextOptions](../../com.aspose.barcode.drawing/textoptions) |  |

### drawTextSmall(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin) {#drawTextSmall-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.PointF-}
```
public void drawTextSmall(String text, System.Drawing.Font font, IBrush brush, System.Drawing.PointF origin)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| origin | com.aspose.ms.System.Drawing.PointF |  |

### drawTextSmall(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds) {#drawTextSmall-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void drawTextSmall(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| bounds | com.aspose.ms.System.Drawing.RectangleF |  |

### drawTextSmall(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options) {#drawTextSmall-java.lang.String-com.aspose.ms.System.Drawing.Font-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-}
```
public void drawTextSmall(String text, System.Drawing.Font font, IBrush brush, System.Drawing.RectangleF bounds, TextOptions options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| font | com.aspose.ms.System.Drawing.Font |  |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| bounds | com.aspose.ms.System.Drawing.RectangleF |  |
| options | [TextOptions](../../com.aspose.barcode.drawing/textoptions) |  |

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
### fillEllipse(IBrush brush, System.Drawing.Rectangle rectangle) {#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-}
```
public void fillEllipse(IBrush brush, System.Drawing.Rectangle rectangle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### fillEllipse(IBrush brush, System.Drawing.RectangleF rectangle) {#fillEllipse-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void fillEllipse(IBrush brush, System.Drawing.RectangleF rectangle)
```




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




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle) {#fillRectangle-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void fillRectangle(IBrush brush, System.Drawing.RectangleF rectangle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| rectangle | com.aspose.ms.System.Drawing.RectangleF |  |

### fillRectangleWithRect(IBrush brush, System.Drawing.Rectangle rectangle) {#fillRectangleWithRect-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.Rectangle-}
```
public void fillRectangleWithRect(IBrush brush, System.Drawing.Rectangle rectangle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [IBrush](../../com.aspose.barcode.drawing/ibrush) |  |
| rectangle | com.aspose.ms.System.Drawing.Rectangle |  |

### fillRectangleWithRect(IBrush brush, System.Drawing.RectangleF rectangle) {#fillRectangleWithRect-com.aspose.barcode.drawing.IBrush-com.aspose.ms.System.Drawing.RectangleF-}
```
public void fillRectangleWithRect(IBrush brush, System.Drawing.RectangleF rectangle)
```




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
### getQualityMode() {#getQualityMode--}
```
public CanvasQualityMode getQualityMode()
```




**Returns:**
[CanvasQualityMode](../../com.aspose.barcode.drawing/canvasqualitymode)
### getXform() {#getXform--}
```
public EmfXForm getXform()
```




**Returns:**
[EmfXForm](../../com.aspose.barcode.drawing.emf.objects/emfxform)
### hashCode() {#hashCode--}
```
public native int hashCode()
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




### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Applies rotate transform for all further drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | Angle of rotation in degrees. |

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### scaleTransform(double scaleX, double scaleY) {#scaleTransform-double-double-}
```
public void scaleTransform(double scaleX, double scaleY)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | double |  |
| scaleY | double |  |

### setWorldTransform(EmfXForm form) {#setWorldTransform-com.aspose.barcode.drawing.emf.objects.EmfXForm-}
```
public void setWorldTransform(EmfXForm form)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| form | [EmfXForm](../../com.aspose.barcode.drawing.emf.objects/emfxform) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(double offsetX, double offsetY) {#translateTransform-double-double-}
```
public void translateTransform(double offsetX, double offsetY)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offsetX | double |  |
| offsetY | double |  |

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

