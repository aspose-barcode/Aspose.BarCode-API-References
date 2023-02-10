---
title: pdf417DataRegionRecognizer
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417dataregionrecognizer/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417CodewordRecognizerBase
```
public class pdf417DataRegionRecognizer extends pdf417CodewordRecognizerBase
```
## Constructors

| Constructor | Description |
| --- | --- |
| [pdf417DataRegionRecognizer()](#pdf417DataRegionRecognizer--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [recognizeDataRegionClassic(pdf417DataRegion aData, pdf417Metadata MetaData, boolean ExistLastColumn, ITerminationCheck aTerminationCheck)](#recognizeDataRegionClassic-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Recognizes whole extracted dataregion without columns/rows spliting with otsu binarization and salt and salt and paper filtering |
| [recognizeDataRegionEroded(pdf417DataRegion aData, pdf417Metadata MetaData, boolean ExistLastColumn, ITerminationCheck aTerminationCheck)](#recognizeDataRegionEroded-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-) | Recognizes whole extracted dataregion without columns/rows spliting with eroded restoration https://homepages.inf.ed.ac.uk/rbf/HIPR2/erode.htm |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### pdf417DataRegionRecognizer() {#pdf417DataRegionRecognizer--}
```
public pdf417DataRegionRecognizer()
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




### recognizeDataRegionClassic(pdf417DataRegion aData, pdf417Metadata MetaData, boolean ExistLastColumn, ITerminationCheck aTerminationCheck) {#recognizeDataRegionClassic-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static pdf417DataGrid recognizeDataRegionClassic(pdf417DataRegion aData, pdf417Metadata MetaData, boolean ExistLastColumn, ITerminationCheck aTerminationCheck)
```


Recognizes whole extracted dataregion without columns/rows spliting with otsu binarization and salt and salt and paper filtering

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aData | [pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) | extracted and rotated to rectangular bitmap region of barcode with data and metadata columns |
| MetaData | [pdf417Metadata](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417metadata) | recognized metadata, columns, rows and ecc |
| ExistLastColumn | boolean | if last(right metadata) column exists is is pdf417, if not = compactpdf417 |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[pdf417DataGrid](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417datagrid) - recognized datagrid or null
### recognizeDataRegionEroded(pdf417DataRegion aData, pdf417Metadata MetaData, boolean ExistLastColumn, ITerminationCheck aTerminationCheck) {#recognizeDataRegionEroded-com.aspose.barcode.barcoderecognition.pdf417.dataregion.pdf417DataRegion-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417Metadata-boolean-com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller.ITerminationCheck-}
```
public static pdf417DataGrid recognizeDataRegionEroded(pdf417DataRegion aData, pdf417Metadata MetaData, boolean ExistLastColumn, ITerminationCheck aTerminationCheck)
```


Recognizes whole extracted dataregion without columns/rows spliting with eroded restoration https://homepages.inf.ed.ac.uk/rbf/HIPR2/erode.htm

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aData | [pdf417DataRegion](../../com.aspose.barcode.barcoderecognition.pdf417.dataregion/pdf417dataregion) | extracted and rotated to rectangular bitmap region of barcode with data and metadata columns |
| MetaData | [pdf417Metadata](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417metadata) | recognized metadata, columns, rows and ecc |
| ExistLastColumn | boolean | if last(right metadata) column exists is is pdf417, if not = compactpdf417 |
| aTerminationCheck | [ITerminationCheck](../../com.aspose.barcode.barcoderecognition.recognition.recognitionsession.terminationcontroller/iterminationcheck) | termination check |

**Returns:**
[pdf417DataGrid](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417datagrid) - recognized datagrid or null
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

