---
title: RegionDetectorDashed
second_title: Aspose.BarCode for Java API Reference
description: Region detector for dot peen dashed datamatrix
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.regions/regiondetectordashed/
---
**Inheritance:**
java.lang.Object
```
public class RegionDetectorDashed
```

Region detector for dot peen dashed datamatrix
## Constructors

| Constructor | Description |
| --- | --- |
| [RegionDetectorDashed()](#RegionDetectorDashed--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSpotsList(ByteBitmap binarizedBitmap, byte spotColor, System.Collections.Generic.Dictionary<Integer,Integer>[] areasDictionary, ITerminationCheck aTerminationCheck)](#getSpotsList-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer----com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Get spots on binarized bitmap. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [searchRegions(ByteBitmap binarizedBitmap, ITerminationCheck aTerminationCheck)](#searchRegions-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Search datamatrix regions |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RegionDetectorDashed() {#RegionDetectorDashed--}
```
public RegionDetectorDashed()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSpotsList(ByteBitmap binarizedBitmap, byte spotColor, System.Collections.Generic.Dictionary<Integer,Integer>[] areasDictionary, ITerminationCheck aTerminationCheck) {#getSpotsList-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.Integer-java.lang.Integer----com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<Spot> getSpotsList(ByteBitmap binarizedBitmap, byte spotColor, System.Collections.Generic.Dictionary<Integer,Integer>[] areasDictionary, ITerminationCheck aTerminationCheck)
```


Get spots on binarized bitmap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binarizedBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Binarized bytebitmap |
| spotColor | byte | Spot color(0 - black, 255 - white) |
| areasDictionary | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.Integer>[] | key is area/10; value is count of this areas |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list) - List of spots
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




### searchRegions(ByteBitmap binarizedBitmap, ITerminationCheck aTerminationCheck) {#searchRegions-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<RectangleVertexes> searchRegions(ByteBitmap binarizedBitmap, ITerminationCheck aTerminationCheck)
```


Search datamatrix regions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binarizedBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Bitmap to serach in |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list) - Rectangle vertexes
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

