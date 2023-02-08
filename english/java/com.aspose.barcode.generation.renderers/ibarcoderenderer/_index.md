---
title: IBarcodeRenderer
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 17
url: /java/com.aspose.barcode.generation.renderers/ibarcoderenderer/
---```
public interface IBarcodeRenderer
```
## Methods

| Method | Description |
| --- | --- |
| [measure(CoreImageParameters coreImageParameters)](#measure-com.aspose.barcode.generation.generationparameters.CoreImageParameters-) |  |
| [measure(CoreImageParameters coreImageParameters, int requiredWidth, int requiredHeight, AutoSizeMode autoSizeMode)](#measure-com.aspose.barcode.generation.generationparameters.CoreImageParameters-int-int-com.aspose.barcode.generation.AutoSizeMode-) |  |
| [measureHeight(CoreImageParameters coreImageParameters, AutoSizeMode autoSizeMode, BarcodeWidthMeasurement widthMeasurement, int heightRequired)](#measureHeight-com.aspose.barcode.generation.generationparameters.CoreImageParameters-com.aspose.barcode.generation.AutoSizeMode-com.aspose.barcode.generation.renderers.BarcodeWidthMeasurement-int-) |  |
| [measureWidth(CoreImageParameters coreImageParameters, AutoSizeMode autoSizeMode, int availableHeight)](#measureWidth-com.aspose.barcode.generation.generationparameters.CoreImageParameters-com.aspose.barcode.generation.AutoSizeMode-int-) |  |
| [render(ICanvas canvas, System.Drawing.Point upperLeftPoint, BarcodeMeasurement barcodeMeasurement)](#render-com.aspose.barcode.drawing.ICanvas-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.generation.renderers.BarcodeMeasurement-) |  |
### measure(CoreImageParameters coreImageParameters) {#measure-com.aspose.barcode.generation.generationparameters.CoreImageParameters-}
```
public abstract BarcodeMeasurement measure(CoreImageParameters coreImageParameters)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| coreImageParameters | [CoreImageParameters](../../com.aspose.barcode.generation.generationparameters/coreimageparameters) |  |

**Returns:**
[BarcodeMeasurement](../../com.aspose.barcode.generation.renderers/barcodemeasurement)
### measure(CoreImageParameters coreImageParameters, int requiredWidth, int requiredHeight, AutoSizeMode autoSizeMode) {#measure-com.aspose.barcode.generation.generationparameters.CoreImageParameters-int-int-com.aspose.barcode.generation.AutoSizeMode-}
```
public abstract BarcodeMeasurement measure(CoreImageParameters coreImageParameters, int requiredWidth, int requiredHeight, AutoSizeMode autoSizeMode)
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
public abstract BarcodeHeightMeasurement measureHeight(CoreImageParameters coreImageParameters, AutoSizeMode autoSizeMode, BarcodeWidthMeasurement widthMeasurement, int heightRequired)
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
public abstract BarcodeWidthMeasurement measureWidth(CoreImageParameters coreImageParameters, AutoSizeMode autoSizeMode, int availableHeight)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| coreImageParameters | [CoreImageParameters](../../com.aspose.barcode.generation.generationparameters/coreimageparameters) |  |
| autoSizeMode | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |
| availableHeight | int |  |

**Returns:**
[BarcodeWidthMeasurement](../../com.aspose.barcode.generation.renderers/barcodewidthmeasurement)
### render(ICanvas canvas, System.Drawing.Point upperLeftPoint, BarcodeMeasurement barcodeMeasurement) {#render-com.aspose.barcode.drawing.ICanvas-com.aspose.ms.System.Drawing.Point-com.aspose.barcode.generation.renderers.BarcodeMeasurement-}
```
public abstract void render(ICanvas canvas, System.Drawing.Point upperLeftPoint, BarcodeMeasurement barcodeMeasurement)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canvas | [ICanvas](../../com.aspose.barcode.drawing/icanvas) |  |
| upperLeftPoint | com.aspose.ms.System.Drawing.Point |  |
| barcodeMeasurement | [BarcodeMeasurement](../../com.aspose.barcode.generation.renderers/barcodemeasurement) |  |

