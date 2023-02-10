---
title: IExtend3DZebraProcessor
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 33
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/iextend3dzebraprocessor/
---```
public interface IExtend3DZebraProcessor
```
## Methods

| Method | Description |
| --- | --- |
| [createZebraUnion(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap)](#createZebraUnion-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.common.bitmaps.ByteBitmap-) |  |
| [filterZebraSegments(List<ZebraSegment> aSegments, ZebraUnion aUnion)](#filterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-) |  |
| [getExtendingParam()](#getExtendingParam--) |  |
| [getProcessorCopy()](#getProcessorCopy--) |  |
| [getTerminatioCheck()](#getTerminatioCheck--) |  |
| [scan(ByteBitmap aBitmap, List<DoublePoints> aLinesList)](#scan-com.aspose.barcode.common.bitmaps.ByteBitmap-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.DoublePoints--) |  |
### createZebraUnion(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap) {#createZebraUnion-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public abstract ZebraUnion createZebraUnion(List<ZebraSegment> aUnionSegments, ByteBitmap aBitmap)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnionSegments | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion)
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
### getExtendingParam() {#getExtendingParam--}
```
public abstract ZebraExtend3DParam getExtendingParam()
```




**Returns:**
[ZebraExtend3DParam](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraextend3dparam)
### getProcessorCopy() {#getProcessorCopy--}
```
public abstract IExtend3DZebraProcessor getProcessorCopy()
```




**Returns:**
[IExtend3DZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iextend3dzebraprocessor)
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
