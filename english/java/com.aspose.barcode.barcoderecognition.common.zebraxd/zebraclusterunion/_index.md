---
title: ZebraClusterUnion
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 18
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebraclusterunion/
---
**Inheritance:**
java.lang.Object
```
public class ZebraClusterUnion
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraClusterUnion()](#ZebraClusterUnion--) |  |
## Methods

| Method | Description |
| --- | --- |
| [clusterZebraSegments(List<ZebraSegment> aSegmentsList, IClusterZebraProcessor aProcessor, ByteBitmap aBitmap, boolean IsSortZebraSegments, boolean isSortZebraUnions)](#clusterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.IClusterZebraProcessor-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-boolean-) | Clusters zebra segments and calculates ZebraUnions params |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraClusterUnion() {#ZebraClusterUnion--}
```
public ZebraClusterUnion()
```


### clusterZebraSegments(List<ZebraSegment> aSegmentsList, IClusterZebraProcessor aProcessor, ByteBitmap aBitmap, boolean IsSortZebraSegments, boolean isSortZebraUnions) {#clusterZebraSegments-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.common.zebraxd.IClusterZebraProcessor-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-boolean-}
```
public static List<ZebraUnion> clusterZebraSegments(List<ZebraSegment> aSegmentsList, IClusterZebraProcessor aProcessor, ByteBitmap aBitmap, boolean IsSortZebraSegments, boolean isSortZebraUnions)
```


Clusters zebra segments and calculates ZebraUnions params

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentsList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> |  |
| aProcessor | [IClusterZebraProcessor](../../com.aspose.barcode.barcoderecognition.common.zebraxd/iclusterzebraprocessor) |  |
| aBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | bitmap for extracting ZebraUnions params |
| IsSortZebraSegments | boolean | sort zebra segments, avoid multithreading order problems |
| isSortZebraUnions | boolean | sort resulting zebra unions, avoid multithreading order problems |

**Returns:**
[List](../../java.util/list) - clustered unions with inizalized params
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

