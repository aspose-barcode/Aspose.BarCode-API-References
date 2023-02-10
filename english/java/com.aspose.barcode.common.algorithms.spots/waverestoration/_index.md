---
title: WaveRestoration
second_title: Aspose.BarCode for Java API Reference
description: This class implements different algorithms to repair damaged parts of the picture
type: docs
weight: 12
url: /java/com.aspose.barcode.common.algorithms.spots/waverestoration/
---
**Inheritance:**
java.lang.Object
```
public class WaveRestoration
```

This class implements different algorithms to repair damaged parts of the picture
## Constructors

| Constructor | Description |
| --- | --- |
| [WaveRestoration()](#WaveRestoration--) |  |
## Methods

| Method | Description |
| --- | --- |
| [calculateSpot(List<ShortPoint> spotPoints)](#calculateSpot-java.util.List-com.aspose.barcode.common.types.ShortPoint--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSpots(ByteBitmap bitmap, byte spotColor, ITerminationCheck aTerminationCheck)](#getAllSpots-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [getClass()](#getClass--) |  |
| [getSpot(ByteBitmap bitmap, ShortPoint startPoint, byte spotColor, ITerminationCheck aTerminationCheck)](#getSpot-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.types.ShortPoint-byte-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Get points of white cluster(spot) contains startPoint |
| [getSpotsList(ByteBitmap binarizedBitmap, byte spotColor, ITerminationCheck aTerminationCheck)](#getSpotsList-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Get spots on binarized bitmap. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAllWhiteSpots(ByteBitmap bitmap, int[] removedArea, ITerminationCheck aTerminationCheck)](#removeAllWhiteSpots-com.aspose.barcode.common.bitmaps.ByteBitmap-int---com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | This function implements the simplified wave algorithm lee to remove all internal white spots in black and white bitmap |
| [removeMicroWhiteSpots(ByteBitmap bitmap, ITerminationCheck aTerminationCheck)](#removeMicroWhiteSpots-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Removes one 1px white spots |
| [removeWhiteSpots(ByteBitmap bitmap, int sizeLimit, ITerminationCheck aTerminationCheck)](#removeWhiteSpots-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Find and remove white spots with a relatively small area. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WaveRestoration() {#WaveRestoration--}
```
public WaveRestoration()
```


### calculateSpot(List<ShortPoint> spotPoints) {#calculateSpot-java.util.List-com.aspose.barcode.common.types.ShortPoint--}
```
public static Spot calculateSpot(List<ShortPoint> spotPoints)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| spotPoints | java.util.List<com.aspose.barcode.common.types.ShortPoint> |  |

**Returns:**
[Spot](../../com.aspose.barcode.common.types/spot)
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
### getAllSpots(ByteBitmap bitmap, byte spotColor, ITerminationCheck aTerminationCheck) {#getAllSpots-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<FullSpot> getAllSpots(ByteBitmap bitmap, byte spotColor, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) |  |
| spotColor | byte |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[List](../../java.util/list)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSpot(ByteBitmap bitmap, ShortPoint startPoint, byte spotColor, ITerminationCheck aTerminationCheck) {#getSpot-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.types.ShortPoint-byte-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static FullSpot getSpot(ByteBitmap bitmap, ShortPoint startPoint, byte spotColor, ITerminationCheck aTerminationCheck)
```


Get points of white cluster(spot) contains startPoint

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bitmap |
| startPoint | [ShortPoint](../../com.aspose.barcode.common.types/shortpoint) | Start point |
| spotColor | byte | Spot Color |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[FullSpot](../../com.aspose.barcode.common.algorithms.spots/fullspot) - Points of the spot
### getSpotsList(ByteBitmap binarizedBitmap, byte spotColor, ITerminationCheck aTerminationCheck) {#getSpotsList-com.aspose.barcode.common.bitmaps.ByteBitmap-byte-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static List<Spot> getSpotsList(ByteBitmap binarizedBitmap, byte spotColor, ITerminationCheck aTerminationCheck)
```


Get spots on binarized bitmap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binarizedBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Binarized bytebitmap |
| spotColor | byte | Spot color(0 - black, 255 - white) |
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




### removeAllWhiteSpots(ByteBitmap bitmap, int[] removedArea, ITerminationCheck aTerminationCheck) {#removeAllWhiteSpots-com.aspose.barcode.common.bitmaps.ByteBitmap-int---com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static ByteBitmap removeAllWhiteSpots(ByteBitmap bitmap, int[] removedArea, ITerminationCheck aTerminationCheck)
```


This function implements the simplified wave algorithm lee to remove all internal white spots in black and white bitmap

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | black and white bitmap |
| removedArea | int[] | Removed area size in pixels |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - restorated bitmap
### removeMicroWhiteSpots(ByteBitmap bitmap, ITerminationCheck aTerminationCheck) {#removeMicroWhiteSpots-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static ByteBitmap removeMicroWhiteSpots(ByteBitmap bitmap, ITerminationCheck aTerminationCheck)
```


Removes one 1px white spots

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Gray bitmap |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - restorated bitmap
### removeWhiteSpots(ByteBitmap bitmap, int sizeLimit, ITerminationCheck aTerminationCheck) {#removeWhiteSpots-com.aspose.barcode.common.bitmaps.ByteBitmap-int-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static ByteBitmap removeWhiteSpots(ByteBitmap bitmap, int sizeLimit, ITerminationCheck aTerminationCheck)
```


Find and remove white spots with a relatively small area. A spot size is auto detected. For only black and white images. Uses wave Lee algorithm

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap in black and white |
| sizeLimit | int | Limit of the spot size(sum of pixels in spot). The value "-1" means that there is no limit (auto detected size) |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) - bitmap without white spots
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

