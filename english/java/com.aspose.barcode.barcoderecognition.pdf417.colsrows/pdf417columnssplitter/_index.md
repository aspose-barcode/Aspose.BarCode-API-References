---
title: pdf417ColumnsSplitter
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 12
url: /java/com.aspose.barcode.barcoderecognition.pdf417.colsrows/pdf417columnssplitter/
---
**Inheritance:**
java.lang.Object
```
public class pdf417ColumnsSplitter
```
## Constructors

| Constructor | Description |
| --- | --- |
| [pdf417ColumnsSplitter()](#pdf417ColumnsSplitter--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractMetadataColumns(pdf417DataRegion aDReg, boolean isExtractLeft, boolean isExtractRight, ITerminationCheck aTerminationCheck)](#extractMetadataColumns-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-boolean-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Extracts optionally left and right metadata columns |
| [extractMetadataColumns(ByteBitmap aRegionBitmap, float aCell17Length, ColumnSplittingRules aRules, boolean isExtractLeft, boolean isExtractRight, ITerminationCheck aTerminationCheck)](#extractMetadataColumns-com.aspose.barcode.common.bitmaps.ByteBitmap-float-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417columnsplitter.ColumnSplittingRules-boolean-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Extracts optionally left and right metadata columns |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [splitDataRegionIntoDataColumns(pdf417DataRegion aDReg, pdf417Metadata aMetaData, boolean isExistLastColumn, ColumnSplittingRules aRules, ITerminationCheck aTerminationCheck)](#splitDataRegionIntoDataColumns-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-boolean-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417columnsplitter.ColumnSplittingRules-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Splits dataregions to column bitmaps |
| [splitDataRegionIntoDataColumns(pdf417DataRegion aDReg, pdf417Metadata aMetaData, boolean isExistLastColumn, ITerminationCheck aTerminationCheck)](#splitDataRegionIntoDataColumns-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Splits dataregions to column bitmaps |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### pdf417ColumnsSplitter() {#pdf417ColumnsSplitter--}
```
public pdf417ColumnsSplitter()
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
### extractMetadataColumns(pdf417DataRegion aDReg, boolean isExtractLeft, boolean isExtractRight, ITerminationCheck aTerminationCheck) {#extractMetadataColumns-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-boolean-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static Tup<ByteBitmap,ByteBitmap> extractMetadataColumns(pdf417DataRegion aDReg, boolean isExtractLeft, boolean isExtractRight, ITerminationCheck aTerminationCheck)
```


Extracts optionally left and right metadata columns

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aDReg | [pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) |  |
| isExtractLeft | boolean | need to extract left meatadata column |
| isExtractRight | boolean | need to extract right meatadata column |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[Tup](../../com.aspose.barcode.common.generic.types/tup) - optionally left and right metadata columns
### extractMetadataColumns(ByteBitmap aRegionBitmap, float aCell17Length, ColumnSplittingRules aRules, boolean isExtractLeft, boolean isExtractRight, ITerminationCheck aTerminationCheck) {#extractMetadataColumns-com.aspose.barcode.common.bitmaps.ByteBitmap-float-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417columnsplitter.ColumnSplittingRules-boolean-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static Tup<ByteBitmap,ByteBitmap> extractMetadataColumns(ByteBitmap aRegionBitmap, float aCell17Length, ColumnSplittingRules aRules, boolean isExtractLeft, boolean isExtractRight, ITerminationCheck aTerminationCheck)
```


Extracts optionally left and right metadata columns

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aRegionBitmap | [ByteBitmap](../../com.aspose.barcode.common.bitmaps/bytebitmap) | Dataregion bitmap |
| aCell17Length | float | possible width of column |
| aRules | [ColumnSplittingRules](../../com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417columnsplitter/columnsplittingrules) | splitting rules |
| isExtractLeft | boolean | need to extract left meatadata column |
| isExtractRight | boolean | need to extract right meatadata column |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[Tup](../../com.aspose.barcode.common.generic.types/tup) - optionally left and right metadata columns
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




### splitDataRegionIntoDataColumns(pdf417DataRegion aDReg, pdf417Metadata aMetaData, boolean isExistLastColumn, ColumnSplittingRules aRules, ITerminationCheck aTerminationCheck) {#splitDataRegionIntoDataColumns-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-boolean-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417columnsplitter.ColumnSplittingRules-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static pdf417ColumnsRows splitDataRegionIntoDataColumns(pdf417DataRegion aDReg, pdf417Metadata aMetaData, boolean isExistLastColumn, ColumnSplittingRules aRules, ITerminationCheck aTerminationCheck)
```


Splits dataregions to column bitmaps

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aDReg | [pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) | Dataregion with params |
| aMetaData | [pdf417Metadata](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417metadata) | recognized metadata |
| isExistLastColumn | boolean | if last(right metadata) column exists is is pdf417, if not = compactpdf417 |
| aRules | [ColumnSplittingRules](../../com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417columnsplitter/columnsplittingrules) | splitting rules |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[pdf417ColumnsRows](../../com.aspose.barcode.barcoderecognition.pdf417.colsrows/pdf417columnsrows) - split dataregions to column bitmaps
### splitDataRegionIntoDataColumns(pdf417DataRegion aDReg, pdf417Metadata aMetaData, boolean isExistLastColumn, ITerminationCheck aTerminationCheck) {#splitDataRegionIntoDataColumns-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static pdf417ColumnsRows splitDataRegionIntoDataColumns(pdf417DataRegion aDReg, pdf417Metadata aMetaData, boolean isExistLastColumn, ITerminationCheck aTerminationCheck)
```


Splits dataregions to column bitmaps

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aDReg | [pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) | Dataregion with params |
| aMetaData | [pdf417Metadata](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417metadata) | recognized metadata |
| isExistLastColumn | boolean | if last(right metadata) column exists is is pdf417, if not = compactpdf417 |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[pdf417ColumnsRows](../../com.aspose.barcode.barcoderecognition.pdf417.colsrows/pdf417columnsrows) - split dataregions to column bitmaps
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

