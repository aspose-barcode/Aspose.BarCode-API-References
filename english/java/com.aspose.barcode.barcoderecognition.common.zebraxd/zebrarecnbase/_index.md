---
title: ZebraRecNBase
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 25
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebrarecnbase/
---
**Inheritance:**
java.lang.Object
```
public class ZebraRecNBase
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraRecNBase()](#ZebraRecNBase--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFilteredByNotMasterList(List<ZebraSegment> aMasterList, List<ZebraSegment> aCheckedList, float MaxDiff)](#getFilteredByNotMasterList-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--float-) | Filters zebra segments from aCheckedList which start2start distance less then MaxDiff from aMasterList segments |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [packNBaseZebraToInt(byte[] aZebra, int Width)](#packNBaseZebraToInt-byte---int-) | Packs array to int. |
| [recognizeNBaseZebraSegment(List<ZebraScan.ZebraBar> aZebra, ZebraNBaseKeeper aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest)](#recognizeNBaseZebraSegment-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraNBaseKeeper-int-float-float-float-) | Recognizes zebra patterns into ZebraSegments from aZebra by ZebraMatrix matching |
| [recognizeNBaseZebraSegment(List<ZebraScan.ZebraBar> aZebra, int aIndex, ZebraNBaseKeeper aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest)](#recognizeNBaseZebraSegment-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraNBaseKeeper-int-float-float-float-) | Recognizes zebra patterns into ZebraSegments from aZebra by ZebraMatrix matching |
| [recognizeNBaseZebraSegmentByPickup(List<ZebraScan.ZebraBar> aZebra, ZebraNBasePackedKeeperBase aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest)](#recognizeNBaseZebraSegmentByPickup-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraNBasePackedKeeperBase-int-float-float-float-) | Recognizes zebra patterns into ZebraSegments from aZebra by packed pattern dictionary search |
| [recognizeNBaseZebraSegmentByPickup(List<ZebraScan.ZebraBar> aZebra, int aIndex, ZebraNBasePackedKeeperBase aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest)](#recognizeNBaseZebraSegmentByPickup-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraNBasePackedKeeperBase-int-float-float-float-) | Recognizes zebra patterns into ZebraSegments from aZebra by packed pattern dictionary search |
| [toString()](#toString--) |  |
| [unpackNBaseZebraFromInt(int Zebra, int Width)](#unpackNBaseZebraFromInt-int-int-) | Unpacks int to array. |
| [unpackNBaseZebraFromIntAuto(int Zebra)](#unpackNBaseZebraFromIntAuto-int-) | Unpacks int to array with Width calculation. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraRecNBase() {#ZebraRecNBase--}
```
public ZebraRecNBase()
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
### getFilteredByNotMasterList(List<ZebraSegment> aMasterList, List<ZebraSegment> aCheckedList, float MaxDiff) {#getFilteredByNotMasterList-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--float-}
```
public static List<ZebraSegment> getFilteredByNotMasterList(List<ZebraSegment> aMasterList, List<ZebraSegment> aCheckedList, float MaxDiff)
```


Filters zebra segments from aCheckedList which start2start distance less then MaxDiff from aMasterList segments

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aMasterList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | list of already exists segments |
| aCheckedList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | recognized segments with new restoration |
| MaxDiff | float | max distance between checked ZebraSegment and any ZebraSegment from aMasterList |

**Returns:**
[List](../../java.util/list) - filtered zebra segments from aCheckedList
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




### packNBaseZebraToInt(byte[] aZebra, int Width) {#packNBaseZebraToInt-byte---int-}
```
public static int packNBaseZebraToInt(byte[] aZebra, int Width)
```


Packs array to int. Width(sum) maust be less then 31

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aZebra | byte[] | zebra pattern |
| Width | int | summ of zebra pattern segments |

**Returns:**
int - packed zebra
### recognizeNBaseZebraSegment(List<ZebraScan.ZebraBar> aZebra, ZebraNBaseKeeper aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest) {#recognizeNBaseZebraSegment-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraNBaseKeeper-int-float-float-float-}
```
public static List<ZebraSegment> recognizeNBaseZebraSegment(List<ZebraScan.ZebraBar> aZebra, ZebraNBaseKeeper aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest)
```


Recognizes zebra patterns into ZebraSegments from aZebra by ZebraMatrix matching

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aZebra | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> | zebra segments with color, position and size from binarized bitmap line |
| aKeeper | [ZebraNBaseKeeper](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebranbasekeeper) | patterns storage |
| aZebraColour | int | starting color of the pattern black/white |
| aSingleTolerance | float | maximal distance between pattern segment and aZebra segment normalized to pattern width |
| aMinQualityTolerance | float | quality of matching between zebra segments and pattern values. 0 - 1 |
| MaxQualityDistFromBest | float | which segments also need to add to result instead best by quality. in most cases is 0. sometimes we can add -0.02, add also segments which is on 2% worse then the best |

**Returns:**
[List](../../java.util/list) - recognized patterns into ZebraSegment with value in position
### recognizeNBaseZebraSegment(List<ZebraScan.ZebraBar> aZebra, int aIndex, ZebraNBaseKeeper aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest) {#recognizeNBaseZebraSegment-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraNBaseKeeper-int-float-float-float-}
```
public static List<ZebraSegment> recognizeNBaseZebraSegment(List<ZebraScan.ZebraBar> aZebra, int aIndex, ZebraNBaseKeeper aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest)
```


Recognizes zebra patterns into ZebraSegments from aZebra by ZebraMatrix matching

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aZebra | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> | zebra segments with color, position and size from binarized bitmap line |
| aIndex | int | index of starting segment in aZebra |
| aKeeper | [ZebraNBaseKeeper](../../com.aspose.barcode.barcoderecognition.common.zebraxd/zebranbasekeeper) | patterns storage |
| aZebraColour | int | starting color of the pattern black/white |
| aSingleTolerance | float | maximal distance between pattern segment and aZebra segment normalized to pattern width |
| aMinQualityTolerance | float | quality of matching between zebra segments and pattern values. 0 - 1 |
| MaxQualityDistFromBest | float | which segments also need to add to result instead best by quality. in nost cases is 0. sometimes we can add -0.02, add also segments which is on 2% worse then the best |

**Returns:**
[List](../../java.util/list) - recognized patterns into ZebraSegment with value in position
### recognizeNBaseZebraSegmentByPickup(List<ZebraScan.ZebraBar> aZebra, ZebraNBasePackedKeeperBase aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest) {#recognizeNBaseZebraSegmentByPickup-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraNBasePackedKeeperBase-int-float-float-float-}
```
public static List<ZebraSegment> recognizeNBaseZebraSegmentByPickup(List<ZebraScan.ZebraBar> aZebra, ZebraNBasePackedKeeperBase aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest)
```


Recognizes zebra patterns into ZebraSegments from aZebra by packed pattern dictionary search

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aZebra | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> | zebra segments with color, position and size from binarized bitmap line |
| aKeeper | com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraNBasePackedKeeperBase | patterns storage |
| aZebraColour | int | starting color of the pattern black/white |
| aSingleTolerance | float | maximal distance between pattern segment and aZebra segment normalized to pattern width |
| aMinQualityTolerance | float | quality of matching between zebra segments and pattern values. 0 - 1 |
| MaxQualityDistFromBest | float | which segments also need to add to result instead best by quality. in nost cases is 0. sometimes we can add -0.02, add also segments which is on 2% worse then the best |

**Returns:**
[List](../../java.util/list) - recognized patterns into ZebraSegment with value in position
### recognizeNBaseZebraSegmentByPickup(List<ZebraScan.ZebraBar> aZebra, int aIndex, ZebraNBasePackedKeeperBase aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest) {#recognizeNBaseZebraSegmentByPickup-java.util.List-com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar--int-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraNBasePackedKeeperBase-int-float-float-float-}
```
public static List<ZebraSegment> recognizeNBaseZebraSegmentByPickup(List<ZebraScan.ZebraBar> aZebra, int aIndex, ZebraNBasePackedKeeperBase aKeeper, int aZebraColour, float aSingleTolerance, float aMinQualityTolerance, float MaxQualityDistFromBest)
```


Recognizes zebra patterns into ZebraSegments from aZebra by packed pattern dictionary search

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aZebra | java.util.List<com.aspose.barcode.barcoderecognition.common.algorithms.ZebraScan.ZebraBar> | zebra segments with color, position and size from binarized bitmap line |
| aIndex | int | index of starting segment in aZebra |
| aKeeper | com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraNBasePackedKeeperBase | patterns storage |
| aZebraColour | int | starting color of the pattern black/white |
| aSingleTolerance | float | maximal distance between pattern segment and aZebra segment normalized to pattern width |
| aMinQualityTolerance | float | quality of matching between zebra segments and pattern values. 0 - 1 |
| MaxQualityDistFromBest | float | which segments also need to add to result instead best by quality. in nost cases is 0. sometimes we can add -0.02, add also segments which is on 2% worse then the best |

**Returns:**
[List](../../java.util/list) - recognized patterns into ZebraSegment with value in position
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### unpackNBaseZebraFromInt(int Zebra, int Width) {#unpackNBaseZebraFromInt-int-int-}
```
public static Byte[] unpackNBaseZebraFromInt(int Zebra, int Width)
```


Unpacks int to array. Width(sum) must be less then 31

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Zebra | int | packed zebra pattern |
| Width | int | summ of zebra pattern segments |

**Returns:**
java.lang.Byte[] - unpacked zebra
### unpackNBaseZebraFromIntAuto(int Zebra) {#unpackNBaseZebraFromIntAuto-int-}
```
public static Byte[] unpackNBaseZebraFromIntAuto(int Zebra)
```


Unpacks int to array with Width calculation. Width(sum) must be less then 31

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| Zebra | int | packed zebra pattern |

**Returns:**
java.lang.Byte[] - unpacked zebra
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

