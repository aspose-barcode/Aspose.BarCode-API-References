---
title: Simple2DRenderer
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 26
url: /java/com.aspose.barcode.generation.renderers.barcoderenderers/simple2drenderer/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.renderers.barcoderenderers.SimpleBarcodeRenderer](../../com.aspose.barcode.generation.renderers.barcoderenderers/simplebarcoderenderer)
```
public class Simple2DRenderer extends SimpleBarcodeRenderer
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Simple2DRenderer(BarcodeParameters barcodeParams, String encodedCodetext, String humanCodetext, CodetextParameters codetextParams, ITextMeasurer textMeasurer)](#Simple2DRenderer-com.aspose.barcode.generation.BarcodeParameters-java.lang.String-java.lang.String-com.aspose.barcode.generation.CodetextParameters-com.aspose.barcode.internal.ITextMeasurer-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [measure(CoreImageParameters coreImageParameters)](#measure-com.aspose.barcode.generation.generationparameters.CoreImageParameters-) |  |
| [measure(CoreImageParameters coreImageParameters, int requiredWidth, int requiredHeight, AutoSizeMode autoSizeMode)](#measure-com.aspose.barcode.generation.generationparameters.CoreImageParameters-int-int-com.aspose.barcode.generation.AutoSizeMode-) |  |
| [measureHeight(CoreImageParameters coreImageParameters, AutoSizeMode autoSizeMode, BarcodeWidthMeasurement widthMeasurement, int heightRequired)](#measureHeight-com.aspose.barcode.generation.generationparameters.CoreImageParameters-com.aspose.barcode.generation.AutoSizeMode-com.aspose.barcode.generation.renderers.BarcodeWidthMeasurement-int-) |  |
| [measureWidth(CoreImageParameters coreImageParameters, AutoSizeMode autoSizeMode, int availableHeight)](#measureWidth-com.aspose.barcode.generation.generationparameters.CoreImageParameters-com.aspose.barcode.generation.AutoSizeMode-int-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [render(ICanvas canvas, System.Drawing.Point upperLeftPoint, BarcodeMeasurement barcodeMeasurement)](#render-com.aspose.barcode.drawing.ICanvas-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.generation.renderers.BarcodeMeasurement-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Simple2DRenderer(BarcodeParameters barcodeParams, String encodedCodetext, String humanCodetext, CodetextParameters codetextParams, ITextMeasurer textMeasurer) {#Simple2DRenderer-com.aspose.barcode.generation.BarcodeParameters-java.lang.String-java.lang.String-com.aspose.barcode.generation.CodetextParameters-com.aspose.barcode.internal.ITextMeasurer-}
```
public Simple2DRenderer(BarcodeParameters barcodeParams, String encodedCodetext, String humanCodetext, CodetextParameters codetextParams, ITextMeasurer textMeasurer)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| barcodeParams | [BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters) |  |
| encodedCodetext | java.lang.String |  |
| humanCodetext | java.lang.String |  |
| codetextParams | [CodetextParameters](../../com.aspose.barcode.generation/codetextparameters) |  |
| textMeasurer | [ITextMeasurer](../../com.aspose.barcode.internal/itextmeasurer) |  |

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
### measure(CoreImageParameters coreImageParameters) {#measure-com.aspose.barcode.generation.generationparameters.CoreImageParameters-}
```
public BarcodeMeasurement measure(CoreImageParameters coreImageParameters)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| coreImageParameters | [CoreImageParameters](../../com.aspose.barcode.generation.generationparameters/coreimageparameters) |  |

**Returns:**
[BarcodeMeasurement](../../com.aspose.barcode.generation.renderers/barcodemeasurement)
### measure(CoreImageParameters coreImageParameters, int requiredWidth, int requiredHeight, AutoSizeMode autoSizeMode) {#measure-com.aspose.barcode.generation.generationparameters.CoreImageParameters-int-int-com.aspose.barcode.generation.AutoSizeMode-}
```
public BarcodeMeasurement measure(CoreImageParameters coreImageParameters, int requiredWidth, int requiredHeight, AutoSizeMode autoSizeMode)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| coreImageParameters | [CoreImageParameters](../../com.aspose.barcode.generation.generationparameters/coreimageparameters) |  |
| requiredWidth | int |  |
| requiredHeight | int |  |
| autoSizeMode | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

**Returns:**
[BarcodeMeasurement](../../com.aspose.barcode.generation.renderers/barcodemeasurement)
### measureHeight(CoreImageParameters coreImageParameters, AutoSizeMode autoSizeMode, BarcodeWidthMeasurement widthMeasurement, int heightRequired) {#measureHeight-com.aspose.barcode.generation.generationparameters.CoreImageParameters-com.aspose.barcode.generation.AutoSizeMode-com.aspose.barcode.generation.renderers.BarcodeWidthMeasurement-int-}
```
public BarcodeHeightMeasurement measureHeight(CoreImageParameters coreImageParameters, AutoSizeMode autoSizeMode, BarcodeWidthMeasurement widthMeasurement, int heightRequired)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| coreImageParameters | [CoreImageParameters](../../com.aspose.barcode.generation.generationparameters/coreimageparameters) |  |
| autoSizeMode | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |
| widthMeasurement | [BarcodeWidthMeasurement](../../com.aspose.barcode.generation.renderers/barcodewidthmeasurement) |  |
| heightRequired | int |  |

**Returns:**
[BarcodeHeightMeasurement](../../com.aspose.barcode.generation.renderers/barcodeheightmeasurement)
### measureWidth(CoreImageParameters coreImageParameters, AutoSizeMode autoSizeMode, int availableHeight) {#measureWidth-com.aspose.barcode.generation.generationparameters.CoreImageParameters-com.aspose.barcode.generation.AutoSizeMode-int-}
```
public BarcodeWidthMeasurement measureWidth(CoreImageParameters coreImageParameters, AutoSizeMode autoSizeMode, int availableHeight)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| coreImageParameters | [CoreImageParameters](../../com.aspose.barcode.generation.generationparameters/coreimageparameters) |  |
| autoSizeMode | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |
| availableHeight | int |  |

**Returns:**
[BarcodeWidthMeasurement](../../com.aspose.barcode.generation.renderers/barcodewidthmeasurement)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### render(ICanvas canvas, System.Drawing.Point upperLeftPoint, BarcodeMeasurement barcodeMeasurement) {#render-com.aspose.barcode.drawing.ICanvas-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.generation.renderers.BarcodeMeasurement-}
```
public void render(ICanvas canvas, System.Drawing.Point upperLeftPoint, BarcodeMeasurement barcodeMeasurement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canvas | [ICanvas](../../com.aspose.barcode.drawing/icanvas) |  |
| upperLeftPoint | com.aspose.ms.System.Drawing.Point |  |
| barcodeMeasurement | [BarcodeMeasurement](../../com.aspose.barcode.generation.renderers/barcodemeasurement) |  |

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

