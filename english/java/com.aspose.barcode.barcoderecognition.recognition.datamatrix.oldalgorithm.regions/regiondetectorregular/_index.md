---
title: RegionDetectorRegular
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.regions/regiondetectorregular/
---
**Inheritance:**
java.lang.Object
```
public class RegionDetectorRegular
```
## Constructors

| Constructor | Description |
| --- | --- |
| [RegionDetectorRegular(ByteBitmap byteBitmap, ITerminationCheck aTerminationCheck)](#RegionDetectorRegular-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [RegionDetectorRegular(ByteBitmap byteBitmap, boolean allowDamagedBorder, ITerminationCheck aTerminationCheck)](#RegionDetectorRegular-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Corners](#Corners) |  |
| [size_seed](#size-seed) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filterRotatedRegions(ByteBitmap byteBitmap, boolean isAddSimpleRegion)](#filterRotatedRegions-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-) | Searches rotated datamatrix regions in the \_allRegions |
| [getByteBitmap()](#getByteBitmap--) | Get a bytebitmap |
| [getClass()](#getClass--) |  |
| [getInterestRectangles()](#getInterestRectangles--) |  |
| [hashCode()](#hashCode--) |  |
| [isBlurredRegions()](#isBlurredRegions--) | Checks if the regions are blurred |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RegionDetectorRegular(ByteBitmap byteBitmap, ITerminationCheck aTerminationCheck) {#RegionDetectorRegular-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public RegionDetectorRegular(ByteBitmap byteBitmap, ITerminationCheck aTerminationCheck)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

### RegionDetectorRegular(ByteBitmap byteBitmap, boolean allowDamagedBorder, ITerminationCheck aTerminationCheck) {#RegionDetectorRegular-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public RegionDetectorRegular(ByteBitmap byteBitmap, boolean allowDamagedBorder, ITerminationCheck aTerminationCheck)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| allowDamagedBorder | boolean |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

### Corners {#Corners}
```
public List<VertexesCorner> Corners
```


### size_seed {#size-seed}
```
public static int size_seed
```


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
### filterRotatedRegions(ByteBitmap byteBitmap, boolean isAddSimpleRegion) {#filterRotatedRegions-com.aspose.barcode.common.bitmaps.ByteBitmap-boolean-}
```
public final void filterRotatedRegions(ByteBitmap byteBitmap, boolean isAddSimpleRegion)
```


Searches rotated datamatrix regions in the \_allRegions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| isAddSimpleRegion | boolean |  |

### getByteBitmap() {#getByteBitmap--}
```
public final ByteBitmap getByteBitmap()
```


Get a bytebitmap

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - A bytebitmap
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInterestRectangles() {#getInterestRectangles--}
```
public final List<RectangleOfInterest> getInterestRectangles()
```




**Returns:**
[List](../../java.util/list)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBlurredRegions() {#isBlurredRegions--}
```
public final boolean isBlurredRegions()
```


Checks if the regions are blurred

**Returns:**
boolean - 
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

