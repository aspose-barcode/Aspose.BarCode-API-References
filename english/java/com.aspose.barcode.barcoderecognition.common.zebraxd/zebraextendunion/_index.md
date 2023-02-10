---
title: ZebraExtendUnion
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 21
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebraextendunion/
---
**Inheritance:**
java.lang.Object
```
public class ZebraExtendUnion
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraExtendUnion()](#ZebraExtendUnion--) |  |
## Methods

| Method | Description |
| --- | --- |
| [addAllSegmentsListsToSingleList(List<List<ZebraSegment>> aLists)](#addAllSegmentsListsToSingleList-java.util.List-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment---) | Merge split zebra segments list of lists. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extendZebraSegments(List<ZebraSegment> aSegmentsList, IExtendZebraProcessor aExtendProcessor, IClusterZebraProcessor aClusterProcessor, ByteBitmap aBitmap)](#extendZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.IExtendZebraProcessor-com.aspose.barcode.barcoderecognition.common.zebraxd.IClusterZebraProcessor-com.aspose.barcode.common.bitmaps.ByteBitmap-) | Extends scanned with ScanRectangle.ScanAngle directions unions with gradient detected angle |
| [extendZebraSegmentsFromUnion(ZebraUnion aUnion, IExtendZebraProcessor aProcessor, ByteBitmap aBitmap)](#extendZebraSegmentsFromUnion-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-com.aspose.barcode.barcoderecognition.common.zebraxd.IExtendZebraProcessor-com.aspose.barcode.common.bitmaps.ByteBitmap-) | Extends scanned with ScanRectangle.ScanAngle directions union with gradient detected angle |
| [extendZebraSegmentsFromUnionList(List<ZebraUnion> aUnions, IExtendZebraProcessor aProcessor, ByteBitmap aBitmap)](#extendZebraSegmentsFromUnionList-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--com.aspose.barcode.barcoderecognition.common.zebraxd.IExtendZebraProcessor-com.aspose.barcode.common.bitmaps.ByteBitmap-) | Extends scanned with ScanRectangle.ScanAngle directions unions with gradient detected angle |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraExtendUnion() {#ZebraExtendUnion--}
```
public ZebraExtendUnion()
```


### addAllSegmentsListsToSingleList(List<List<ZebraSegment>> aLists) {#addAllSegmentsListsToSingleList-java.util.List-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment---}
```
public static List<ZebraSegment> addAllSegmentsListsToSingleList(List<List<ZebraSegment>> aLists)
```


Merge split zebra segments list of lists. All of the list is extended ZebraSegments with gradient detected angle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aLists | java.util.List<java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment>> | list of extended ZebraSegment for every union |

**Returns:**
[List](../../java.util/list) - united list
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
### extendZebraSegments(List<ZebraSegment> aSegmentsList, IExtendZebraProcessor aExtendProcessor, IClusterZebraProcessor aClusterProcessor, ByteBitmap aBitmap) {#extendZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.IExtendZebraProcessor-com.aspose.barcode.barcoderecognition.common.zebraxd.IClusterZebraProcessor-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static List<ZebraUnion> extendZebraSegments(List<ZebraSegment> aSegmentsList, IExtendZebraProcessor aExtendProcessor, IClusterZebraProcessor aClusterProcessor, ByteBitmap aBitmap)
```


Extends scanned with ScanRectangle.ScanAngle directions unions with gradient detected angle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentsList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |
| aExtendProcessor | [IExtendZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iextendzebraprocessor) |  |
| aClusterProcessor | [IClusterZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iclusterzebraprocessor) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | bitmap to scan |

**Returns:**
[List](../../java.util/list) - extended by gradient detected angle unions list
### extendZebraSegmentsFromUnion(ZebraUnion aUnion, IExtendZebraProcessor aProcessor, ByteBitmap aBitmap) {#extendZebraSegmentsFromUnion-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion-com.aspose.barcode.barcoderecognition.common.zebraxd.IExtendZebraProcessor-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static List<ZebraSegment> extendZebraSegmentsFromUnion(ZebraUnion aUnion, IExtendZebraProcessor aProcessor, ByteBitmap aBitmap)
```


Extends scanned with ScanRectangle.ScanAngle directions union with gradient detected angle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnion | [ZebraUnion](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebraunion) | union scanned with ScanRectangle.ScanAngle directions |
| aProcessor | [IExtendZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iextendzebraprocessor) | extending processor with symbology defined params |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | processing bitmap |

**Returns:**
[List](../../java.util/list) - extended by gradient detected angle zebra segments
### extendZebraSegmentsFromUnionList(List<ZebraUnion> aUnions, IExtendZebraProcessor aProcessor, ByteBitmap aBitmap) {#extendZebraSegmentsFromUnionList-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion--com.aspose.barcode.barcoderecognition.common.zebraxd.IExtendZebraProcessor-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static List<ZebraSegment> extendZebraSegmentsFromUnionList(List<ZebraUnion> aUnions, IExtendZebraProcessor aProcessor, ByteBitmap aBitmap)
```


Extends scanned with ScanRectangle.ScanAngle directions unions with gradient detected angle

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aUnions | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraUnion> | unions scanned with ScanRectangle.ScanAngle directions |
| aProcessor | [IExtendZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iextendzebraprocessor) | extending processor with symbology defined params |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | processing bitmap |

**Returns:**
[List](../../java.util/list) - extended by gradient detected angle united zebra segments list (must be clustered)
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

