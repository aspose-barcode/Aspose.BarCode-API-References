---
title: SpikedBits
second_title: Aspose.BarCode for Java API Reference
description: This class extends bits matrix model.
type: docs
weight: 14
url: /java/com.aspose.barcode.barcoderecognition.recognition.cells2d/spikedbits/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.internal.BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray)
```
public class SpikedBits extends BitArrayArray
```

This class extends bits matrix model.
## Constructors

| Constructor | Description |
| --- | --- |
| [SpikedBits(int capacity)](#SpikedBits-int-) | Initializes a new instance of the  SpikedBits  that is empty and has the specified initial capacity. |
| [SpikedBits(int col, int row)](#SpikedBits-int-int-) | Initializes a new instance of the  SpikedBits  |
## Fields

| Field | Description |
| --- | --- |
| [ModuleX](#ModuleX) | Module of 2d barcode by x-coordinate (rounding down). |
| [ModuleY](#ModuleY) | Module of 2d barcode by y-coordinate (rounding down). |
| [ProtoBitmap](#ProtoBitmap) | Original byte bitmap to construct the bits. |
| [ProtoCells](#ProtoCells) | Original cells to construct the bits. |
| [Tiles](#Tiles) | Tiles for codewordes. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flip(int i, int j)](#flip-int-int-) |  |
| [getClass()](#getClass--) |  |
| [getCol()](#getCol--) |  |
| [getRow()](#getRow--) |  |
| [get_Item(int i, int j)](#get-Item-int-int-) |  |
| [hashCode()](#hashCode--) |  |
| [isInnerPoint(int rowValue, int colValue)](#isInnerPoint-int-int-) | check inner point conditions |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(int i, int j)](#set-int-int-) |  |
| [set_Item(int i, int j, boolean value)](#set-Item-int-int-boolean-) |  |
| [toByteArrays()](#toByteArrays--) | Cast to byte[][] type. |
| [toString()](#toString--) |  |
| [toZebras()](#toZebras--) |  |
| [unSet(int i, int j)](#unSet-int-int-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SpikedBits(int capacity) {#SpikedBits-int-}
```
public SpikedBits(int capacity)
```


Initializes a new instance of the  SpikedBits  that is empty and has the specified initial capacity. class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | The number of elements that the new list can initially store. |

### SpikedBits(int col, int row) {#SpikedBits-int-int-}
```
public SpikedBits(int col, int row)
```


Initializes a new instance of the  SpikedBits 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| col | int | Specified column count. |
| row | int | Specified rows count. |

### ModuleX {#ModuleX}
```
public int ModuleX
```


Module of 2d barcode by x-coordinate (rounding down).

### ModuleY {#ModuleY}
```
public int ModuleY
```


Module of 2d barcode by y-coordinate (rounding down).

### ProtoBitmap {#ProtoBitmap}
```
public ByteBitmap ProtoBitmap
```


Original byte bitmap to construct the bits.

### ProtoCells {#ProtoCells}
```
public ICells ProtoCells
```


Original cells to construct the bits.

### Tiles {#Tiles}
```
public List<Tile> Tiles
```


Tiles for codewordes. It is post-initialization in the "translate" method.

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
### flip(int i, int j) {#flip-int-int-}
```
public void flip(int i, int j)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int |  |
| j | int |  |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCol() {#getCol--}
```
public int getCol()
```




**Returns:**
int
### getRow() {#getRow--}
```
public int getRow()
```




**Returns:**
int
### get_Item(int i, int j) {#get-Item-int-int-}
```
public boolean get_Item(int i, int j)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int |  |
| j | int |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInnerPoint(int rowValue, int colValue) {#isInnerPoint-int-int-}
```
public boolean isInnerPoint(int rowValue, int colValue)
```


check inner point conditions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowValue | int | row |
| colValue | int | col |

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




### set(int i, int j) {#set-int-int-}
```
public void set(int i, int j)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int |  |
| j | int |  |

### set_Item(int i, int j, boolean value) {#set-Item-int-int-boolean-}
```
public void set_Item(int i, int j, boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int |  |
| j | int |  |
| value | boolean |  |

### toByteArrays() {#toByteArrays--}
```
public byte[][] toByteArrays()
```


Cast to byte[][] type.

**Returns:**
byte[][] - Byte[][]
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toZebras() {#toZebras--}
```
public Int32List[] toZebras()
```




**Returns:**
com.aspose.barcode.common.generic.list.Int32List[]
### unSet(int i, int j) {#unSet-int-int-}
```
public void unSet(int i, int j)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int |  |
| j | int |  |

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

