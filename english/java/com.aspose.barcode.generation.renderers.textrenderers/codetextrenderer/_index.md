---
title: CodetextRenderer
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.generation.renderers.textrenderers/codetextrenderer/
---
**Inheritance:**
java.lang.Object
```
public class CodetextRenderer
```
## Constructors

| Constructor | Description |
| --- | --- |
| [CodetextRenderer(ITextMeasurer textMeasurer, String codetext, CodetextParameters parameters, CodetextTypedParameters typedParameters)](#CodetextRenderer-com.aspose.barcode.internal.ITextMeasurer-java.lang.String-com.aspose.barcode.generation.CodetextParameters-com.aspose.barcode.generation.generationparameters.barcodeparamsspecification.CodetextTypedParameters-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOneLineFontSize(int maxWidth, int desiredSize)](#getOneLineFontSize-int-int-) |  |
| [hashCode()](#hashCode--) |  |
| [measure(int maxWidth, FontUnit font)](#measure-int-com.aspose.barcode.generation.FontUnit-) | Calculates actual codetext size |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [render(ICanvas canvas, System.Drawing.Rectangle layout)](#render-com.aspose.barcode.drawing.ICanvas-com.aspose.ms.System.Drawing.Rectangle-) | Renders codetext on canvas inside specified region |
| [render(ICanvas canvas, System.Drawing.Rectangle layout, GuardPosition[] guardPositions)](#render-com.aspose.barcode.drawing.ICanvas-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.generation.renderers.textrenderers.GuardPosition---) | Renders codetext on canvas inside specified region |
| [setFont(FontUnit newFont)](#setFont-com.aspose.barcode.generation.FontUnit-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodetextRenderer(ITextMeasurer textMeasurer, String codetext, CodetextParameters parameters, CodetextTypedParameters typedParameters) {#CodetextRenderer-com.aspose.barcode.internal.ITextMeasurer-java.lang.String-com.aspose.barcode.generation.CodetextParameters-com.aspose.barcode.generation.generationparameters.barcodeparamsspecification.CodetextTypedParameters-}
```
public CodetextRenderer(ITextMeasurer textMeasurer, String codetext, CodetextParameters parameters, CodetextTypedParameters typedParameters)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textMeasurer | [ITextMeasurer](../../com.aspose.barcode.internal/itextmeasurer) |  |
| codetext | java.lang.String |  |
| parameters | [CodetextParameters](../../com.aspose.barcode.generation/codetextparameters) |  |
| typedParameters | [CodetextTypedParameters](../../com.aspose.barcode.generation.generationparameters.barcodeparamsspecification/codetexttypedparameters) |  |

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
### getOneLineFontSize(int maxWidth, int desiredSize) {#getOneLineFontSize-int-int-}
```
public int getOneLineFontSize(int maxWidth, int desiredSize)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxWidth | int |  |
| desiredSize | int |  |

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### measure(int maxWidth, FontUnit font) {#measure-int-com.aspose.barcode.generation.FontUnit-}
```
public CodeTextSize measure(int maxWidth, FontUnit font)
```


Calculates actual codetext size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxWidth | int | Max width |
| font | [FontUnit](../../com.aspose.barcode.generation/fontunit) | Font |

**Returns:**
[CodeTextSize](../../com.aspose.barcode.generation.renderers.textrenderers/codetextsize) - Returns actual codetext size
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


Renders codetext on canvas inside specified region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canvas | [ICanvas](../../com.aspose.barcode.drawing/icanvas) | Canvas to render on |
| layout | com.aspose.ms.System.Drawing.Rectangle | Region on canvas |

### render(ICanvas canvas, System.Drawing.Rectangle layout, GuardPosition[] guardPositions) {#render-com.aspose.barcode.drawing.ICanvas-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.generation.renderers.textrenderers.GuardPosition---}
```
public void render(ICanvas canvas, System.Drawing.Rectangle layout, GuardPosition[] guardPositions)
```


Renders codetext on canvas inside specified region

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canvas | [ICanvas](../../com.aspose.barcode.drawing/icanvas) | Canvas to render on |
| layout | com.aspose.ms.System.Drawing.Rectangle | Region on canvas for barcode and codetext including paddings |
| guardPositions | [GuardPosition\[\]](../../com.aspose.barcode.generation.renderers.textrenderers/guardposition) |  |

### setFont(FontUnit newFont) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit newFont)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newFont | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

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

