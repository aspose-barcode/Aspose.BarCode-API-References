---
title: RendererFactory
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 16
url: /java/com.aspose.barcode.generation.renderers/rendererfactory/
---
**Inheritance:**
java.lang.Object
```
public class RendererFactory
```
## Constructors

| Constructor | Description |
| --- | --- |
| [RendererFactory()](#RendererFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [create(BarcodeParameters barcodeParams, CodetextParameters codetextParameters, IBarCodeEncoder encoder, IBarCodeEncoder supplementEncoder, ITextMeasurer textMeasurer)](#create-com.aspose.barcode.generation.BarcodeParameters-com.aspose.barcode.generation.CodetextParameters-com.aspose.barcode.generation.IBarCodeEncoder-com.aspose.barcode.generation.IBarCodeEncoder-com.aspose.barcode.internal.ITextMeasurer-) |  |
| [create(BarcodeParameters barcodeParams, ITextMeasurer textMeasurer)](#create-com.aspose.barcode.generation.BarcodeParameters-com.aspose.barcode.internal.ITextMeasurer-) |  |
| [createEncoder(BarcodeParameters barcodeParams)](#createEncoder-com.aspose.barcode.generation.BarcodeParameters-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RendererFactory() {#RendererFactory--}
```
public RendererFactory()
```


### create(BarcodeParameters barcodeParams, CodetextParameters codetextParameters, IBarCodeEncoder encoder, IBarCodeEncoder supplementEncoder, ITextMeasurer textMeasurer) {#create-com.aspose.barcode.generation.BarcodeParameters-com.aspose.barcode.generation.CodetextParameters-com.aspose.barcode.generation.IBarCodeEncoder-com.aspose.barcode.generation.IBarCodeEncoder-com.aspose.barcode.internal.ITextMeasurer-}
```
public static IBarcodeRenderer create(BarcodeParameters barcodeParams, CodetextParameters codetextParameters, IBarCodeEncoder encoder, IBarCodeEncoder supplementEncoder, ITextMeasurer textMeasurer)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| barcodeParams | [BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters) |  |
| codetextParameters | [CodetextParameters](../../com.aspose.barcode.generation/codetextparameters) |  |
| encoder | [IBarCodeEncoder](../../com.aspose.barcode.generation/ibarcodeencoder) |  |
| supplementEncoder | [IBarCodeEncoder](../../com.aspose.barcode.generation/ibarcodeencoder) |  |
| textMeasurer | [ITextMeasurer](../../com.aspose.barcode.internal/itextmeasurer) |  |

**Returns:**
[IBarcodeRenderer](../../com.aspose.barcode.generation.renderers/ibarcoderenderer)
### create(BarcodeParameters barcodeParams, ITextMeasurer textMeasurer) {#create-com.aspose.barcode.generation.BarcodeParameters-com.aspose.barcode.internal.ITextMeasurer-}
```
public static IBarcodeRenderer create(BarcodeParameters barcodeParams, ITextMeasurer textMeasurer)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| barcodeParams | [BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters) |  |
| textMeasurer | [ITextMeasurer](../../com.aspose.barcode.internal/itextmeasurer) |  |

**Returns:**
[IBarcodeRenderer](../../com.aspose.barcode.generation.renderers/ibarcoderenderer)
### createEncoder(BarcodeParameters barcodeParams) {#createEncoder-com.aspose.barcode.generation.BarcodeParameters-}
```
public static IBarCodeEncoder createEncoder(BarcodeParameters barcodeParams)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| barcodeParams | [BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters) |  |

**Returns:**
[IBarCodeEncoder](../../com.aspose.barcode.generation/ibarcodeencoder)
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

