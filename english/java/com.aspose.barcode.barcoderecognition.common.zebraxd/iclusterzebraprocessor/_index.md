---
title: IClusterZebraProcessor
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 32
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/iclusterzebraprocessor/
---```
public interface IClusterZebraProcessor
```
## Methods

| Method | Description |
| --- | --- |
| [clusterZebraSegments(List<ZebraSegment> aSegmentsList)](#clusterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--) |  |
| [createZebraUnionIfCorrect(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap)](#createZebraUnionIfCorrect-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [getProcessorCopy()](#getProcessorCopy--) |  |
| [getTerminatioCheck()](#getTerminatioCheck--) |  |
| [splitZebraSegmentsByBasicParams(List<ZebraSegment> aSegmentsList)](#splitZebraSegmentsByBasicParams-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--) |  |
### clusterZebraSegments(List<ZebraSegment> aSegmentsList) {#clusterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--}
```
public abstract List<List<ZebraSegment>> clusterZebraSegments(List<ZebraSegment> aSegmentsList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentsList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |

**Returns:**
[List](../../java.util/list)
### createZebraUnionIfCorrect(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap) {#createZebraUnionIfCorrect-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public abstract ZebraUnion createZebraUnionIfCorrect(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnionSegments | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion)
### getProcessorCopy() {#getProcessorCopy--}
```
public abstract IClusterZebraProcessor getProcessorCopy()
```




**Returns:**
[IClusterZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iclusterzebraprocessor)
### getTerminatioCheck() {#getTerminatioCheck--}
```
public abstract ITerminationCheck getTerminatioCheck()
```




**Returns:**
[ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck)
### splitZebraSegmentsByBasicParams(List<ZebraSegment> aSegmentsList) {#splitZebraSegmentsByBasicParams-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--}
```
public abstract List<List<ZebraSegment>> splitZebraSegmentsByBasicParams(List<ZebraSegment> aSegmentsList)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentsList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |

**Returns:**
[List](../../java.util/list)
