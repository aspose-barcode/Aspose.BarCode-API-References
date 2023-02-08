---
title: RegionDetectorSpot
second_title: Aspose.BarCode for Java API Reference
description: Region detector for the rotated datamatrix.
type: docs
weight: 14
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.regions/regiondetectorspot/
---
**Inheritance:**
java.lang.Object
```
public class RegionDetectorSpot
```

Region detector for the rotated datamatrix. Uses the extremal points of spots to locate the region
## Constructors

| Constructor | Description |
| --- | --- |
| [RegionDetectorSpot()](#RegionDetectorSpot--) |  |
## Methods

| Method | Description |
| --- | --- |
| [detectLPatternCorner(ByteBitmap byteBitmap, ByteBitmap binarizeBitmap, RectangleOfInterest region, boolean isAddSimpleRegion)](#detectLPatternCorner-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.regions.corners.RectangleOfInterest-boolean-) | Detects an L-pattern corner. |
| [detectLPatternCorner(ByteBitmap byteBitmap, ByteBitmap binarizeBitmap, System.Drawing.Point yMin, System.Drawing.Point xMin, System.Drawing.Point xMax, System.Drawing.Point yMax, boolean isAddSimpleRegion)](#detectLPatternCorner-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-boolean-) | Detects L-pattern corner (cutted datamatrix and global vertexes) by extremal points yMin, xMin, yMax, xMax |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [searchRegions(ByteBitmap byteBitmap)](#searchRegions-com.aspose.barcode.common.bitmaps.ByteBitmap-) | Search datamatrix regions |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RegionDetectorSpot() {#RegionDetectorSpot--}
```
public RegionDetectorSpot()
```


### detectLPatternCorner(ByteBitmap byteBitmap, ByteBitmap binarizeBitmap, RectangleOfInterest region, boolean isAddSimpleRegion) {#detectLPatternCorner-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.regions.corners.RectangleOfInterest-boolean-}
```
public static List<VertexesCorner> detectLPatternCorner(ByteBitmap byteBitmap, ByteBitmap binarizeBitmap, RectangleOfInterest region, boolean isAddSimpleRegion)
```


Detects an L-pattern corner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| binarizeBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Binarized bytebitmap |
| region | [RectangleOfInterest](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.regions.corners/rectangleofinterest) | A region |
| isAddSimpleRegion | boolean |  |

**Returns:**
[List](../../java.util/list) - L-pattern corner (cutted datamatrix and global vertexes)
### detectLPatternCorner(ByteBitmap byteBitmap, ByteBitmap binarizeBitmap, System.Drawing.Point yMin, System.Drawing.Point xMin, System.Drawing.Point xMax, System.Drawing.Point yMax, boolean isAddSimpleRegion) {#detectLPatternCorner-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-com.aspose.ms.System.Drawing.Point-boolean-}
```
public static List<VertexesCorner> detectLPatternCorner(ByteBitmap byteBitmap, ByteBitmap binarizeBitmap, System.Drawing.Point yMin, System.Drawing.Point xMin, System.Drawing.Point xMax, System.Drawing.Point yMax, boolean isAddSimpleRegion)
```


Detects L-pattern corner (cutted datamatrix and global vertexes) by extremal points yMin, xMin, yMax, xMax

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| binarizeBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input binarized bytebitmap |
| yMin | com.aspose.ms.System.Drawing.Point | The point with the minimum Y |
| xMin | com.aspose.ms.System.Drawing.Point | The point with the minimum X |
| xMax | com.aspose.ms.System.Drawing.Point | The point with the maximum X |
| yMax | com.aspose.ms.System.Drawing.Point | The point with the maximum Y |
| isAddSimpleRegion | boolean |  |

**Returns:**
[List](../../java.util/list) - List of detected corners
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




### searchRegions(ByteBitmap byteBitmap) {#searchRegions-com.aspose.barcode.common.bitmaps.ByteBitmap-}
```
public static List<VertexesCorner> searchRegions(ByteBitmap byteBitmap)
```


Search datamatrix regions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |

**Returns:**
[List](../../java.util/list) - List of regions
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

