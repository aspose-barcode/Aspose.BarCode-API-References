---
title: BlackGrowsCellsConverter
second_title: Aspose.BarCode for Java API Reference
description: Class for converting the cell to byte color value using algorithms for matrix with black growth.
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.converters/blackgrowscellsconverter/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.converters.CellsConverter](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.cells.converters/cellsconverter)
```
public class BlackGrowsCellsConverter extends CellsConverter
```

Class for converting the cell to byte color value, using algorithms for matrix with black growth.
## Constructors

| Constructor | Description |
| --- | --- |
| [BlackGrowsCellsConverter()](#BlackGrowsCellsConverter--) |  |
## Methods

| Method | Description |
| --- | --- |
| [columnsAndRowsToBits(ByteBitmap byteBitmap, int dimensionX, int dimensionY, int separatrix, Int32List cols, Int32List rows, boolean rotated180, int moduleX, int moduleY)](#columnsAndRowsToBits-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-com.aspose.barcode.common.generic.list.Int32List-com.aspose.barcode.common.generic.list.Int32List-boolean-int-int-) | Initialize bits by columns and rows coordinates |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(ModelHolder modelHolder)](#execute-com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm.ModelHolder-) | Exctracts bits from cells |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlackGrowsCellsConverter() {#BlackGrowsCellsConverter--}
```
public BlackGrowsCellsConverter()
```


### columnsAndRowsToBits(ByteBitmap byteBitmap, int dimensionX, int dimensionY, int separatrix, Int32List cols, Int32List rows, boolean rotated180, int moduleX, int moduleY) {#columnsAndRowsToBits-com.aspose.barcode.common.bitmaps.ByteBitmap-int-int-int-com.aspose.barcode.common.generic.list.Int32List-com.aspose.barcode.common.generic.list.Int32List-boolean-int-int-}
```
public final SpikedBits columnsAndRowsToBits(ByteBitmap byteBitmap, int dimensionX, int dimensionY, int separatrix, Int32List cols, Int32List rows, boolean rotated180, int moduleX, int moduleY)
```


Initialize bits by columns and rows coordinates

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| byteBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | A bytebitmap |
| dimensionX | int | X-dimension |
| dimensionY | int | Y-dimension |
| separatrix | int | A separatrix |
| cols | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | Columms |
| rows | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | Rows |
| rotated180 | boolean | Is datamatrix rotated on 180 degrees |
| moduleX | int | Module x |
| moduleY | int | Module y |

**Returns:**
[SpikedBits](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/spikedbits) - A matrix of bits (SpikedBits)
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


Exctracts bits from cells

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| modelHolder | [ModelHolder](../../com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.treealgorithm/modelholder) | Model holder |

**Returns:**
boolean - Is succesfully got a result
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

