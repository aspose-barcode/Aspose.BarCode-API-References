---
title: ZebraCutOff
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 19
url: /java/com.aspose.barcode.barcoderecognition.common.zebraxd/zebracutoff/
---
**Inheritance:**
java.lang.Object
```
public class ZebraCutOff
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ZebraCutOff()](#ZebraCutOff--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filterByLineSize(List<ZebraSegment> aList, float MinLineSize, float MaxLineSize)](#filterByLineSize-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--float-float-) | Filter ZebraSegment list by line difference |
| [filterByLineSize(List<ZebraSegment> aList, float BaseValue, float MinMult, float MaxMult)](#filterByLineSize-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--float-float-float-) | Filter ZebraSegment list by line difference from BaseValue |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [leaveOnlyWithCurrentReadType(List<ZebraSegment> aSegmentList, SingleDecodeType aReadtype)](#leaveOnlyWithCurrentReadType-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Filters segments by readtype |
| [leaveOnlyWithCurrentReadTypeAndValue(List<ZebraSegment> aSegmentList, SingleDecodeType aReadtype, int aValue)](#leaveOnlyWithCurrentReadTypeAndValue-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.SingleDecodeType-int-) | Filters segments by readtype and value |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ZebraCutOff() {#ZebraCutOff--}
```
public ZebraCutOff()
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
### filterByLineSize(List<ZebraSegment> aList, float MinLineSize, float MaxLineSize) {#filterByLineSize-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--float-float-}
```
public static List<ZebraSegment> filterByLineSize(List<ZebraSegment> aList, float MinLineSize, float MaxLineSize)
```


Filter ZebraSegment list by line difference

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | processing list |
| MinLineSize | float | minimal value of the ZebraSegment |
| MaxLineSize | float | maximal value of the ZebraSegment |

**Returns:**
[List](../../java.util/list) - filtered segments
### filterByLineSize(List<ZebraSegment> aList, float BaseValue, float MinMult, float MaxMult) {#filterByLineSize-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--float-float-float-}
```
public static List<ZebraSegment> filterByLineSize(List<ZebraSegment> aList, float BaseValue, float MinMult, float MaxMult)
```


Filter ZebraSegment list by line difference from BaseValue

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | processing list |
| BaseValue | float | base value of the ZebraSegment |
| MinMult | float | minimal value of the ZebraSegment defined from BaseValue |
| MaxMult | float | maximal value of the ZebraSegment defined from BaseValue |

**Returns:**
[List](../../java.util/list) - filtered segments
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
### leaveOnlyWithCurrentReadType(List<ZebraSegment> aSegmentList, SingleDecodeType aReadtype) {#leaveOnlyWithCurrentReadType-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static List<ZebraSegment> leaveOnlyWithCurrentReadType(List<ZebraSegment> aSegmentList, SingleDecodeType aReadtype)
```


Filters segments by readtype

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | processing list |
| aReadtype | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | readtype to leave |

**Returns:**
[List](../../java.util/list) - filtered segments
### leaveOnlyWithCurrentReadTypeAndValue(List<ZebraSegment> aSegmentList, SingleDecodeType aReadtype, int aValue) {#leaveOnlyWithCurrentReadTypeAndValue-java.util.List-com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment--com.aspose.barcode.barcoderecognition.SingleDecodeType-int-}
```
public static List<ZebraSegment> leaveOnlyWithCurrentReadTypeAndValue(List<ZebraSegment> aSegmentList, SingleDecodeType aReadtype, int aValue)
```


Filters segments by readtype and value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aSegmentList | java.util.List<com.aspose.barcode.barcoderecognition.common.zebraxd.ZebraSegment> | processing list |
| aReadtype | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | readtype to leave |
| aValue | int | value to leave |

**Returns:**
[List](../../java.util/list) - filtered segments
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

