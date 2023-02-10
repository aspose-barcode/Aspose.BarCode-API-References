---
title: DensityTimePatternDetector
second_title: Aspose.BarCode for Java API Reference
description: Detector of the time pattern.
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.timepatterns/densitytimepatterndetector/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.IAlgorithm](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/ialgorithm)
```
public class DensityTimePatternDetector implements IAlgorithm
```

Detector of the time pattern. Analyzes whole time pattern
## Constructors

| Constructor | Description |
| --- | --- |
| [DensityTimePatternDetector()](#DensityTimePatternDetector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(ModelHolder modelHolder)](#execute-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-) | Locates time pattern by black color density |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [locateTimePattern(ByteBitmap byteBitmap, int fromI, int toI, boolean flip)](#locateTimePattern-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-boolean-) | Locates time pattern by black color density ------Module------ fromI || || || . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DensityTimePatternDetector() {#DensityTimePatternDetector--}
```
public DensityTimePatternDetector()
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
### execute(ModelHolder modelHolder) {#execute-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-}
```
public final boolean execute(ModelHolder modelHolder)
```


Locates time pattern by black color density

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| modelHolder | [ModelHolder](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/modelholder) | Model holder |

**Returns:**
boolean - Is succesfully got result
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
### locateTimePattern(ByteBitmap byteBitmap, int fromI, int toI, boolean flip) {#locateTimePattern-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-boolean-}
```
public static Int32List locateTimePattern(ByteBitmap byteBitmap, int fromI, int toI, boolean flip)
```


Locates time pattern by black color density ------Module------ fromI || || || . |||||| |||||| |||||| . ||||||||| ||||||||| ||||||||| n ||||||||+ ||||||||| ||||||||| . |||||| |||||| |||||| . ||| || || . |||||||||||||||| ||||||||||||||||| toI |||||||||||||||| ||||||||||||||||| 0 -------i----------bitmap.Width or Height

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | byteBitmap |
| fromI | int | a started coordinate to search |
| toI | int | a finished coordinate to search (hypothetical). Algorithm has auto finish property |
| flip | boolean | Value is false if we search vertical pattern. |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list) - spikes - zebra centrs
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

