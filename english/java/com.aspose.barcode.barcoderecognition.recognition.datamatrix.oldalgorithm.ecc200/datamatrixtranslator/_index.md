---
title: DataMatrixTranslator
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.barcoderecognition.recognition.datamatrix.oldalgorithm.ecc200/datamatrixtranslator/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixTranslator
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DataMatrixTranslator()](#DataMatrixTranslator--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [translate(BitArrayArray bits, List<Tile>[] tailes)](#translate-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-java.util.List-com.aspose.barcode.barcoderecognition.recognition.cells2d.Tile----) |  |
| [translateWithVary(SpikedBits spikedBits)](#translateWithVary-com.aspose.barcode.barcoderecognition.recognition.cells2d.SpikedBits-) | Translate bits using vary moot codewords |
| [validateDatamatrix(BitArrayArray bitmap, boolean isECC200)](#validateDatamatrix-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-boolean-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataMatrixTranslator() {#DataMatrixTranslator--}
```
public DataMatrixTranslator()
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
### translate(BitArrayArray bits, List<Tile>[] tailes) {#translate-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-java.util.List-com.aspose.barcode.barcoderecognition.recognition.cells2d.Tile----}
```
public static System.Text.msStringBuilder translate(BitArrayArray bits, List<Tile>[] tailes)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bits | [BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) |  |
| tailes | java.util.List<com.aspose.barcode.barcoderecognition.recognition.cells2d.Tile>[] |  |

**Returns:**
com.aspose.ms.System.Text.msStringBuilder
### translateWithVary(SpikedBits spikedBits) {#translateWithVary-com.aspose.barcode.barcoderecognition.recognition.cells2d.SpikedBits-}
```
public final System.Text.msStringBuilder translateWithVary(SpikedBits spikedBits)
```


Translate bits using vary moot codewords

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| spikedBits | [SpikedBits](../../com.aspose.barcode.barcoderecognition.recognition.cells2d/spikedbits) | Spiked bits |

**Returns:**
com.aspose.ms.System.Text.msStringBuilder - Result codetext
### validateDatamatrix(BitArrayArray bitmap, boolean isECC200) {#validateDatamatrix-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-boolean-}
```
public static boolean validateDatamatrix(BitArrayArray bitmap, boolean isECC200)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitmap | [BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) |  |
| isECC200 | boolean |  |

**Returns:**
boolean
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

