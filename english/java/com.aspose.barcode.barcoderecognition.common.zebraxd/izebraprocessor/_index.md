---
title: IZebraProcessor
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 36
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/izebraprocessor/
---```
public interface IZebraProcessor
```
## Methods

| Method | Description |
| --- | --- |
| [getProcessorCopy()](#getProcessorCopy--) |  |
| [getScanComplexity()](#getScanComplexity--) |  |
| [getZebraSegmentFromZebrasList(List<ZebraScan.ZebraBar> aZebra)](#getZebraSegmentFromZebrasList-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--) |  |
### getProcessorCopy() {#getProcessorCopy--}
```
public abstract IZebraProcessor getProcessorCopy()
```




**Returns:**
[IZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/izebraprocessor)
### getScanComplexity() {#getScanComplexity--}
```
public abstract double getScanComplexity()
```




**Returns:**
double
### getZebraSegmentFromZebrasList(List<ZebraScan.ZebraBar> aZebra) {#getZebraSegmentFromZebrasList-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--}
```
public abstract List<ZebraSegment> getZebraSegmentFromZebrasList(List<ZebraScan.ZebraBar> aZebra)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aZebra | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> |  |

**Returns:**
[List](../../java.util/list)
