---
title: pdf417RowsSplitter
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.pdf417.colsrows/pdf417rowssplitter/
---
**Inheritance:**
java.lang.Object
```
public class pdf417RowsSplitter
```
## Constructors

| Constructor | Description |
| --- | --- |
| [pdf417RowsSplitter()](#pdf417RowsSplitter--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [splitClearColumnsToRows(pdf417ColumnsRows aInfo, ITerminationCheck aTerminationCheck)](#splitClearColumnsToRows-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417ColumnsRows-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Split high quality barcode images |
| [splitClearColumnsToRowsWithMetadataFix(pdf417ColumnsRows aInfo, pdf417Metadata aMetaData, ITerminationCheck aTerminationCheck)](#splitClearColumnsToRowsWithMetadataFix-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417ColumnsRows-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [splitColumnsToRows(pdf417ColumnsRows aInfo, pdf417Metadata aMetaData, ITerminationCheck aTerminationCheck)](#splitColumnsToRows-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417ColumnsRows-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) |  |
| [splitColumnsToRowsByMetaDataPositions(pdf417ColumnsRows aInfo, pdf417Metadata aMetaData, ITerminationCheck aTerminationCheck)](#splitColumnsToRowsByMetaDataPositions-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417ColumnsRows-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Split low quality (blurred and noised) barcode images |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### pdf417RowsSplitter() {#pdf417RowsSplitter--}
```
public pdf417RowsSplitter()
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




### splitClearColumnsToRows(pdf417ColumnsRows aInfo, ITerminationCheck aTerminationCheck) {#splitClearColumnsToRows-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417ColumnsRows-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static boolean splitClearColumnsToRows(pdf417ColumnsRows aInfo, ITerminationCheck aTerminationCheck)
```


Split high quality barcode images

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aInfo | [pdf417ColumnsRows](../../com.aspose.barcode.barcoderecognition.pdf417.colsrows/pdf417columnsrows) | split columns array |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
boolean - is image detected as high quality
### splitClearColumnsToRowsWithMetadataFix(pdf417ColumnsRows aInfo, pdf417Metadata aMetaData, ITerminationCheck aTerminationCheck) {#splitClearColumnsToRowsWithMetadataFix-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417ColumnsRows-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static void splitClearColumnsToRowsWithMetadataFix(pdf417ColumnsRows aInfo, pdf417Metadata aMetaData, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aInfo | [pdf417ColumnsRows](../../com.aspose.barcode.barcoderecognition.pdf417.colsrows/pdf417columnsrows) |  |
| aMetaData | [pdf417Metadata](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417metadata) |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

### splitColumnsToRows(pdf417ColumnsRows aInfo, pdf417Metadata aMetaData, ITerminationCheck aTerminationCheck) {#splitColumnsToRows-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417ColumnsRows-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static void splitColumnsToRows(pdf417ColumnsRows aInfo, pdf417Metadata aMetaData, ITerminationCheck aTerminationCheck)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aInfo | [pdf417ColumnsRows](../../com.aspose.barcode.barcoderecognition.pdf417.colsrows/pdf417columnsrows) |  |
| aMetaData | [pdf417Metadata](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417metadata) |  |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) |  |

### splitColumnsToRowsByMetaDataPositions(pdf417ColumnsRows aInfo, pdf417Metadata aMetaData, ITerminationCheck aTerminationCheck) {#splitColumnsToRowsByMetaDataPositions-com.aspose.barcode.barcoderecognition.pdf417.colsrows.pdf417ColumnsRows-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static void splitColumnsToRowsByMetaDataPositions(pdf417ColumnsRows aInfo, pdf417Metadata aMetaData, ITerminationCheck aTerminationCheck)
```


Split low quality (blurred and noised) barcode images

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aInfo | [pdf417ColumnsRows](../../com.aspose.barcode.barcoderecognition.pdf417.colsrows/pdf417columnsrows) | split columns array |
| aMetaData | [pdf417Metadata](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417metadata) | detected metadata |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

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

