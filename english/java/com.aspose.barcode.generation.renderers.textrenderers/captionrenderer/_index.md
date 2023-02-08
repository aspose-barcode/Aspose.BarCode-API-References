---
title: CaptionRenderer
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.generation.renderers.textrenderers/captionrenderer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.barcode.generation.renderers.textrenderers.ICaptionRenderer
```
public class CaptionRenderer implements ICaptionRenderer
```
## Constructors

| Constructor | Description |
| --- | --- |
| [CaptionRenderer(ITextMeasurer textMeasurer, CaptionParameters parameters)](#CaptionRenderer-com.aspose.barcode.internal.ITextMeasurer-com.aspose.barcode.generation.CaptionParameters-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [measure(int maxWidth)](#measure-int-) | Calculates actual caption size including paddings |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [render(ICanvas canvas, System.Drawing.Rectangle layout)](#render-com.aspose.barcode.drawing.ICanvas-com.aspose.ms.System.Drawing.Rectangle-) | Renders caption on canvas inside specified region |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CaptionRenderer(ITextMeasurer textMeasurer, CaptionParameters parameters) {#CaptionRenderer-com.aspose.barcode.internal.ITextMeasurer-com.aspose.barcode.generation.CaptionParameters-}
```
public CaptionRenderer(ITextMeasurer textMeasurer, CaptionParameters parameters)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textMeasurer | [ITextMeasurer](../../com.aspose.barcode.internal/itextmeasurer) |  |
| parameters | [CaptionParameters](../../com.aspose.barcode.generation/captionparameters) |  |

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### measure(int maxWidth) {#measure-int-}
```
public System.Drawing.Size measure(int maxWidth)
```


Calculates actual caption size including paddings

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxWidth | int | Max width including paddings |

**Returns:**
com.aspose.ms.System.Drawing.Size - Returns actual caption size including paddings
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### render(ICanvas canvas, System.Drawing.Rectangle layout) {#render-com.aspose.barcode.drawing.ICanvas-com.aspose.ms.System.Drawing.Rectangle-}
```
public void render(ICanvas canvas, System.Drawing.Rectangle layout)
```


Renders caption on canvas inside specified region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canvas | [ICanvas](../../com.aspose.barcode.drawing/icanvas) | Canvas to render on |
| layout | com.aspose.ms.System.Drawing.Rectangle | Region on canvas |

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

