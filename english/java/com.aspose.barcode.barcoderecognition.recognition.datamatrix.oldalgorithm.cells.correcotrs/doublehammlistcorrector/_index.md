---
title: DoubleHammListCorrector
second_title: Aspose.BarCode for Java API Reference
description: Correction algorithms with using double hamming
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.correcotrs/doublehammlistcorrector/
---
**Inheritance:**
java.lang.Object
```
public class DoubleHammListCorrector
```

Correction algorithms with using double hamming
## Constructors

| Constructor | Description |
| --- | --- |
| [DoubleHammListCorrector()](#DoubleHammListCorrector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [correctColsByDoubleHamming(ByteBitmap byteBitmap, Int32List rows, Int32List cols)](#correctColsByDoubleHamming-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.generic.list.Int32List-com.aspose.barcode.common.generic.list.Int32List-) | Correct columns by hamming of left and right columns |
| [correctRowsByDoubleHamming(ByteBitmap byteBitmap, Int32List rows, Int32List cols)](#correctRowsByDoubleHamming-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.generic.list.Int32List-com.aspose.barcode.common.generic.list.Int32List-) | Correct rows by hamming of top and bottom rows |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DoubleHammListCorrector() {#DoubleHammListCorrector--}
```
public DoubleHammListCorrector()
```


### correctColsByDoubleHamming(ByteBitmap byteBitmap, Int32List rows, Int32List cols) {#correctColsByDoubleHamming-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.generic.list.Int32List-com.aspose.barcode.common.generic.list.Int32List-}
```
public static Int32List correctColsByDoubleHamming(ByteBitmap byteBitmap, Int32List rows, Int32List cols)
```


Correct columns by hamming of left and right columns

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| rows | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | Input rows |
| cols | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | Input columns |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list) - Corrected columns
### correctRowsByDoubleHamming(ByteBitmap byteBitmap, Int32List rows, Int32List cols) {#correctRowsByDoubleHamming-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.generic.list.Int32List-com.aspose.barcode.common.generic.list.Int32List-}
```
public static Int32List correctRowsByDoubleHamming(ByteBitmap byteBitmap, Int32List rows, Int32List cols)
```


Correct rows by hamming of top and bottom rows

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| rows | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | Input rows |
| cols | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | Input columns |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list) - Corrected rows
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

