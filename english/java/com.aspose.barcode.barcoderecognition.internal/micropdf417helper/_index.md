---
title: MicroPDF417Helper
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 25
url: /java/com.aspose.barcode.barcoderecognition.internal/micropdf417helper/
---
**Inheritance:**
java.lang.Object
```
public class MicroPDF417Helper
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MicroPDF417Helper()](#MicroPDF417Helper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [bitMatrix2CodeWords(BitArrayArray bitMatrix, MicroPDF417RectangleItem item, ITerminationCheck aTerminationCheck)](#bitMatrix2CodeWords-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-com.aspose.barcode.barcoderecognition.internal.MicroPDF417RectangleItem-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClusterNumberByLEFTRAPNumber(int leftRAPNumber)](#getClusterNumberByLEFTRAPNumber-int-) |  |
| [getCodeWordBySymbol(Integer[] symbol, int cluster)](#getCodeWordBySymbol-java.lang.Integer---int-) |  |
| [getECCCount(int columns, int rows)](#getECCCount-int-int-) |  |
| [getRAPNumberBySymbol(Integer[] symbol, int type)](#getRAPNumberBySymbol-java.lang.Integer---int-) |  |
| [getRowsByColumns(int columns)](#getRowsByColumns-int-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MicroPDF417Helper() {#MicroPDF417Helper--}
```
public MicroPDF417Helper()
```


### bitMatrix2CodeWords(BitArrayArray bitMatrix, MicroPDF417RectangleItem item, ITerminationCheck aTerminationCheck) {#bitMatrix2CodeWords-com.aspose.barcode.barcoderecognition.internal.BitArrayArray-com.aspose.barcode.barcoderecognition.internal.MicroPDF417RectangleItem-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static Int32List bitMatrix2CodeWords(BitArrayArray bitMatrix, MicroPDF417RectangleItem item, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bitMatrix | [BitArrayArray](../../com.aspose.barcode.barcoderecognition.internal/bitarrayarray) |  |
| item | com.aspose.barcode.barcoderecognition.internal.MicroPDF417RectangleItem |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list)
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
### getClusterNumberByLEFTRAPNumber(int leftRAPNumber) {#getClusterNumberByLEFTRAPNumber-int-}
```
public static int getClusterNumberByLEFTRAPNumber(int leftRAPNumber)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftRAPNumber | int |  |

**Returns:**
int
### getCodeWordBySymbol(Integer[] symbol, int cluster) {#getCodeWordBySymbol-java.lang.Integer---int-}
```
public static int getCodeWordBySymbol(Integer[] symbol, int cluster)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| symbol | java.lang.Integer[] |  |
| cluster | int |  |

**Returns:**
int
### getECCCount(int columns, int rows) {#getECCCount-int-int-}
```
public static int getECCCount(int columns, int rows)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columns | int |  |
| rows | int |  |

**Returns:**
int
### getRAPNumberBySymbol(Integer[] symbol, int type) {#getRAPNumberBySymbol-java.lang.Integer---int-}
```
public static int getRAPNumberBySymbol(Integer[] symbol, int type)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| symbol | java.lang.Integer[] |  |
| type | int |  |

**Returns:**
int
### getRowsByColumns(int columns) {#getRowsByColumns-int-}
```
public static int[] getRowsByColumns(int columns)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columns | int |  |

**Returns:**
int[]
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

