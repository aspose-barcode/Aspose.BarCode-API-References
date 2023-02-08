---
title: IExtendZebraProcessor
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 34
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/iextendzebraprocessor/
---```
public interface IExtendZebraProcessor
```
## Methods

| Method | Description |
| --- | --- |
| [filterZebraSegments(List<ZebraSegment> aSegments, ZebraUnion aUnion)](#filterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-) |  |
| [getExtendedQuad(ZebraUnion aUnion)](#getExtendedQuad-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-) |  |
| [getProcessorCopy()](#getProcessorCopy--) |  |
| [getTerminatioCheck()](#getTerminatioCheck--) |  |
| [scan(ByteBitmap aBitmap, List<DoublePoints> aLinesList)](#scan-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints--) |  |
### filterZebraSegments(List<ZebraSegment> aSegments, ZebraUnion aUnion) {#filterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-}
```
public abstract List<ZebraSegment> filterZebraSegments(List<ZebraSegment> aSegments, ZebraUnion aUnion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegments | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |
| aUnion | [ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) |  |

**Returns:**
[List](../../java.util/list)
### getExtendedQuad(ZebraUnion aUnion) {#getExtendedQuad-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-}
```
public abstract QuadPoints getExtendedQuad(ZebraUnion aUnion)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) |  |

**Returns:**
[QuadPoints](../../com.aspose.barcode.barcoderecognition.common.algorithms/quadpoints)
### getProcessorCopy() {#getProcessorCopy--}
```
public abstract IExtendZebraProcessor getProcessorCopy()
```




**Returns:**
[IExtendZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iextendzebraprocessor)
### getTerminatioCheck() {#getTerminatioCheck--}
```
public abstract ITerminationCheck getTerminatioCheck()
```




**Returns:**
[ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck)
### scan(ByteBitmap aBitmap, List<DoublePoints> aLinesList) {#scan-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints--}
```
public abstract List<ZebraSegment> scan(ByteBitmap aBitmap, List<DoublePoints> aLinesList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aLinesList | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints> |  |

**Returns:**
[List](../../java.util/list)
