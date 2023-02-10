---
title: BlackPriorityCorrector
second_title: Aspose.BarCode for Java API Reference
description: Correction algorithms.
type: docs
weight: 11
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.correcotrs/blackprioritycorrector/
---
**Inheritance:**
java.lang.Object
```
public class BlackPriorityCorrector
```

Correction algorithms. Apply this corrector for columns/rows in a binarization bitmap with a black losing
## Constructors

| Constructor | Description |
| --- | --- |
| [BlackPriorityCorrector()](#BlackPriorityCorrector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [correctColumns(ByteBitmap byteBitmap, Int32List rows, Int32List[] cols)](#correctColumns-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.generic.list.Int32List-com.aspose.barcode.common.generic.list.Int32List---) | Corrects columns. |
| [correctRows(ByteBitmap byteBitmap, Int32List[] rows, Int32List cols)](#correctRows-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.generic.list.Int32List---com.aspose.barcode.common.generic.list.Int32List-) | Corrects rows. |
| [differenceCount(ByteBitmap byteBitmap, Int32List arrayX, int y1, int y2, boolean flip)](#differenceCount-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.generic.list.Int32List-int-int-boolean-) | Calculates the difference between y1 and y2 on arrayX |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlackPriorityCorrector() {#BlackPriorityCorrector--}
```
public BlackPriorityCorrector()
```


### correctColumns(ByteBitmap byteBitmap, Int32List rows, Int32List[] cols) {#correctColumns-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.generic.list.Int32List-com.aspose.barcode.common.generic.list.Int32List---}
```
public static void correctColumns(ByteBitmap byteBitmap, Int32List rows, Int32List[] cols)
```


Corrects columns. Selects more black column. Rechecks by a hamming

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | byte bitmap |
| rows | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | rows |
| cols | [Int32List\[\]](../../com.aspose.barcode.common.generic.list/int32list) | cols |

### correctRows(ByteBitmap byteBitmap, Int32List[] rows, Int32List cols) {#correctRows-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.generic.list.Int32List---com.aspose.barcode.common.generic.list.Int32List-}
```
public static void correctRows(ByteBitmap byteBitmap, Int32List[] rows, Int32List cols)
```


Corrects rows. Selects more black row. Rechecks by a hamming

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | byte bitmap |
| rows | [Int32List\[\]](../../com.aspose.barcode.common.generic.list/int32list) | rows |
| cols | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | cols |

### differenceCount(ByteBitmap byteBitmap, Int32List arrayX, int y1, int y2, boolean flip) {#differenceCount-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.barcode.common.generic.list.Int32List-int-int-boolean-}
```
public static int differenceCount(ByteBitmap byteBitmap, Int32List arrayX, int y1, int y2, boolean flip)
```


Calculates the difference between y1 and y2 on arrayX

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | byte bitmap |
| arrayX | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | array of x |
| y1 | int | first y |
| y2 | int | second y |
| flip | boolean | "flip x to y" flag |

**Returns:**
int - 
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

