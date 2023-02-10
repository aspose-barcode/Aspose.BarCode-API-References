---
title: DislocationBitsCorrector
second_title: Aspose.BarCode for Java API Reference
description: Corrector for the bit matrix.
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.correcotrs/dislocationbitscorrector/
---
**Inheritance:**
java.lang.Object
```
public class DislocationBitsCorrector
```

Corrector for the bit matrix. Corrects the dent of datamatrix
## Constructors

| Constructor | Description |
| --- | --- |
| [DislocationBitsCorrector()](#DislocationBitsCorrector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDamage(BitArrayArray bits, int x, int y, int lenght, System.Drawing.Point[] damageStart1, System.Drawing.Point[] damageEnd1, boolean isHorizontal)](#getDamage-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-int-int-int-com.aspose.ms.System.Drawing.Point---com.aspose.ms.System.Drawing.Point---boolean-) | Return start and end points of a offset part of a line |
| [hashCode()](#hashCode--) |  |
| [moveHorizontalOffset(BitArrayArray bits, int patternsDistance, int depth)](#moveHorizontalOffset-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-int-int-) | Smooth small vertical offset damage in bits |
| [moveVerticalOffset(BitArrayArray bits, int patternsDistance, int depth)](#moveVerticalOffset-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-int-int-) | Smooth small horizontal offset damage in bits |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [restoreSmallDamage(ByteBitmap byteBitmap, System.Drawing.Rectangle rectangle, BitArrayArray bits)](#restoreSmallDamage-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-) | Restore small damage in BitArrayArray |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DislocationBitsCorrector() {#DislocationBitsCorrector--}
```
public DislocationBitsCorrector()
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
### getDamage(BitArrayArray bits, int x, int y, int lenght, System.Drawing.Point[] damageStart1, System.Drawing.Point[] damageEnd1, boolean isHorizontal) {#getDamage-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-int-int-int-com.aspose.ms.System.Drawing.Point---com.aspose.ms.System.Drawing.Point---boolean-}
```
public static boolean getDamage(BitArrayArray bits, int x, int y, int lenght, System.Drawing.Point[] damageStart1, System.Drawing.Point[] damageEnd1, boolean isHorizontal)
```


Return start and end points of a offset part of a line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bits | [BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) |  |
| x | int | X-coordinate of a offset point to start search all damage |
| y | int | Y-coordinate of a offset point to start search all damage |
| lenght | int | Lenght of a previous damage |
| damageStart1 | com.aspose.ms.System.Drawing.Point[] | Return start point of a damage |
| damageEnd1 | com.aspose.ms.System.Drawing.Point[] | Return end point of a damage |
| isHorizontal | boolean | Is offset horizontal |

**Returns:**
boolean - Is damage found
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### moveHorizontalOffset(BitArrayArray bits, int patternsDistance, int depth) {#moveHorizontalOffset-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-int-int-}
```
public static void moveHorizontalOffset(BitArrayArray bits, int patternsDistance, int depth)
```


Smooth small vertical offset damage in bits

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bits | [BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) | Input bits |
| patternsDistance | int | A distance between alignment pattern lines |
| depth | int | A limiting depth to move |

### moveVerticalOffset(BitArrayArray bits, int patternsDistance, int depth) {#moveVerticalOffset-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-int-int-}
```
public static void moveVerticalOffset(BitArrayArray bits, int patternsDistance, int depth)
```


Smooth small horizontal offset damage in bits

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bits | [BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) | Input bits |
| patternsDistance | int | A distance between alignment pattern lines |
| depth | int | A limiting depth to move |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### restoreSmallDamage(ByteBitmap byteBitmap, System.Drawing.Rectangle rectangle, BitArrayArray bits) {#restoreSmallDamage-com.aspose.barcode.common.bitmaps.ByteBitmap-com.aspose.ms.System.Drawing.Rectangle-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-}
```
public static void restoreSmallDamage(ByteBitmap byteBitmap, System.Drawing.Rectangle rectangle, BitArrayArray bits)
```


Restore small damage in BitArrayArray

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Input bytebitmap |
| rectangle | com.aspose.ms.System.Drawing.Rectangle | Datamatrix rectangle |
| bits | [BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) | Input bits |

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

