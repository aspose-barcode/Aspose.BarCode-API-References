---
title: MicroPdf417Encoder
second_title: Aspose.BarCode for Java API Reference
description: Contains functions to encode MicroPDF417
type: docs
weight: 68
url: /java/com.aspose.barcode.generation.renderers.barcoderenderers.encoders/micropdf417encoder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.BarCodeEncoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/barcodeencoder), [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.Pdf417Encoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/pdf417encoder)
```
public class MicroPdf417Encoder extends Pdf417Encoder
```

Contains functions to encode MicroPDF417
## Constructors

| Constructor | Description |
| --- | --- |
| [MicroPdf417Encoder(MacroPdf417EncoderParameters parameters)](#MicroPdf417Encoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.MacroPdf417EncoderParameters-) | Initializes a new instance of the  MicroPdf417Encoder  class. |
## Fields

| Field | Description |
| --- | --- |
| [Clusters](#Clusters) |  |
## Methods

| Method | Description |
| --- | --- |
| [convertIntToBinaryString(long param, int len)](#convertIntToBinaryString-long-int-) |  |
| [encode(String str)](#encode-java.lang.String-) | Encodes string of data to MicroPDF417 barcode string |
| [encodeCodewords(Int32List nonEcCodeWords, int actualCodewordsCount)](#encodeCodewords-com.aspose.barcode.common.generic.list.Int32List-int-) | Adds ECC and encodes compacted codewords into MicroPDF417 barcode string |
| [encodeCodewords(Int32List nonEcCodeWords, int actualCodewordsCount, int columns)](#encodeCodewords-com.aspose.barcode.common.generic.list.Int32List-int-int-) | Adds ECC and encodes compacted codewords into MicroPDF417 barcode string |
| [encodeCodewords(Int32List nonEcCodeWords, int actualCodewordsCount, int columns, int rows)](#encodeCodewords-com.aspose.barcode.common.generic.list.Int32List-int-int-int-) | Adds ECC and encodes compacted codewords into MicroPDF417 barcode string |
| [encodeCodewords(Int32List nonEcCodeWords, int errorLevel, int columns, int rows, boolean isTruncated)](#encodeCodewords-com.aspose.barcode.common.generic.list.Int32List-int-int-int-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChecksum()](#getChecksum--) |  |
| [getClass()](#getClass--) |  |
| [getEnableChecksum()](#getEnableChecksum--) |  |
| [getHumanReadableCodeText()](#getHumanReadableCodeText--) |  |
| [getHumanReadableCodeText_Rename_Namesake()](#getHumanReadableCodeText-Rename-Namesake--) |  |
| [getMacroPDF417CodeWords()](#getMacroPDF417CodeWords--) |  |
| [getMinErrorCorrectionLevel(int nonEcCodewordsCount)](#getMinErrorCorrectionLevel-int-) |  |
| [getParameters()](#getParameters--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareCode(String data)](#prepareCode-java.lang.String-) | Creates codewords sequence |
| [toBeEncode(String text)](#toBeEncode-java.lang.String-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MicroPdf417Encoder(MacroPdf417EncoderParameters parameters) {#MicroPdf417Encoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.MacroPdf417EncoderParameters-}
```
public MicroPdf417Encoder(MacroPdf417EncoderParameters parameters)
```


Initializes a new instance of the  MicroPdf417Encoder  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parameters | [MacroPdf417EncoderParameters](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters/macropdf417encoderparameters) |  |

### Clusters {#Clusters}
```
public static final int[][] Clusters
```


### convertIntToBinaryString(long param, int len) {#convertIntToBinaryString-long-int-}
```
public static String convertIntToBinaryString(long param, int len)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| param | long |  |
| len | int |  |

**Returns:**
java.lang.String
### encode(String str) {#encode-java.lang.String-}
```
public String encode(String str)
```


Encodes string of data to MicroPDF417 barcode string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | Input string |

**Returns:**
java.lang.String - Binary string
### encodeCodewords(Int32List nonEcCodeWords, int actualCodewordsCount) {#encodeCodewords-com.aspose.barcode.common.generic.list.Int32List-int-}
```
public static String encodeCodewords(Int32List nonEcCodeWords, int actualCodewordsCount)
```


Adds ECC and encodes compacted codewords into MicroPDF417 barcode string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nonEcCodeWords | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | Compacted codewords |
| actualCodewordsCount | int |  |

**Returns:**
java.lang.String - Binary string
### encodeCodewords(Int32List nonEcCodeWords, int actualCodewordsCount, int columns) {#encodeCodewords-com.aspose.barcode.common.generic.list.Int32List-int-int-}
```
public static String encodeCodewords(Int32List nonEcCodeWords, int actualCodewordsCount, int columns)
```


Adds ECC and encodes compacted codewords into MicroPDF417 barcode string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nonEcCodeWords | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | Compacted codewords |
| actualCodewordsCount | int |  |
| columns | int |  |

**Returns:**
java.lang.String - Binary string
### encodeCodewords(Int32List nonEcCodeWords, int actualCodewordsCount, int columns, int rows) {#encodeCodewords-com.aspose.barcode.common.generic.list.Int32List-int-int-int-}
```
public static String encodeCodewords(Int32List nonEcCodeWords, int actualCodewordsCount, int columns, int rows)
```


Adds ECC and encodes compacted codewords into MicroPDF417 barcode string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nonEcCodeWords | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) | Compacted codewords |
| actualCodewordsCount | int |  |
| columns | int | Required columns count |
| rows | int | Required rows count |

**Returns:**
java.lang.String - Binary string
### encodeCodewords(Int32List nonEcCodeWords, int errorLevel, int columns, int rows, boolean isTruncated) {#encodeCodewords-com.aspose.barcode.common.generic.list.Int32List-int-int-int-boolean-}
```
public static String encodeCodewords(Int32List nonEcCodeWords, int errorLevel, int columns, int rows, boolean isTruncated)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nonEcCodeWords | [Int32List](../../com.aspose.barcode.common.generic.list/int32list) |  |
| errorLevel | int |  |
| columns | int |  |
| rows | int |  |
| isTruncated | boolean |  |

**Returns:**
java.lang.String
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
### getChecksum() {#getChecksum--}
```
public String getChecksum()
```




**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableChecksum() {#getEnableChecksum--}
```
public EnableChecksum getEnableChecksum()
```




**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### getHumanReadableCodeText() {#getHumanReadableCodeText--}
```
public String getHumanReadableCodeText()
```




**Returns:**
java.lang.String
### getHumanReadableCodeText_Rename_Namesake() {#getHumanReadableCodeText-Rename-Namesake--}
```
public String getHumanReadableCodeText_Rename_Namesake()
```




**Returns:**
java.lang.String
### getMacroPDF417CodeWords() {#getMacroPDF417CodeWords--}
```
public Int32List getMacroPDF417CodeWords()
```




**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list)
### getMinErrorCorrectionLevel(int nonEcCodewordsCount) {#getMinErrorCorrectionLevel-int-}
```
public static int getMinErrorCorrectionLevel(int nonEcCodewordsCount)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nonEcCodewordsCount | int |  |

**Returns:**
int
### getParameters() {#getParameters--}
```
public EncoderParameters getParameters()
```




**Returns:**
[EncoderParameters](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters/encoderparameters)
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




### prepareCode(String data) {#prepareCode-java.lang.String-}
```
public Int32List prepareCode(String data)
```


Creates codewords sequence

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | java.lang.String |  |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list)
### toBeEncode(String text) {#toBeEncode-java.lang.String-}
```
public String toBeEncode(String text)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |

**Returns:**
java.lang.String
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
