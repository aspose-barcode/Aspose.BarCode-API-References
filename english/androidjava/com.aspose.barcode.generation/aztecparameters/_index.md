---
title: AztecParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Aztec parameters.
type: docs
weight: 12
url: /androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Aztec parameters.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Height/Width ratio of 2D BarCode module. |
| [getAztecEncodeMode()](#getAztecEncodeMode--) | Gets a Aztec encode mode. |
| [getAztecErrorLevel()](#getAztecErrorLevel--) | Level of error correction of Aztec types of barcode. |
| [getAztecSymbolMode()](#getAztecSymbolMode--) | Gets a Aztec Symbol mode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getLayersCount()](#getLayersCount--) | Gets layers count of Aztec symbol. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Barcode ID for Structured Append mode of Aztec barcode. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Barcodes count for Structured Append mode of Aztec barcode. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | File ID for Structured Append mode of Aztec barcode (optional field). |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Height/Width ratio of 2D BarCode module. |
| [setAztecEncodeMode(AztecEncodeMode value)](#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Sets a Aztec encode mode. |
| [setAztecErrorLevel(int value)](#setAztecErrorLevel-int-) | Level of error correction of Aztec types of barcode. |
| [setAztecSymbolMode(AztecSymbolMode value)](#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Sets a Aztec Symbol mode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Sets ECI encoding. |
| [setLayersCount(int value)](#setLayersCount-int-) | Sets layers count of Aztec symbol. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Barcode ID for Structured Append mode of Aztec barcode. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Barcodes count for Structured Append mode of Aztec barcode. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | File ID for Structured Append mode of Aztec barcode (optional field). |
| [toString()](#toString--) | Returns a human-readable string representation of this  AztecParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAspectRatio() {#getAspectRatio--}
```
public float getAspectRatio()
```


Height/Width ratio of 2D BarCode module.

**Returns:**
float
### getAztecEncodeMode() {#getAztecEncodeMode--}
```
public AztecEncodeMode getAztecEncodeMode()
```


Gets a Aztec encode mode. Default value: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode
### getAztecErrorLevel() {#getAztecErrorLevel--}
```
public int getAztecErrorLevel()
```


Level of error correction of Aztec types of barcode. Value should between 5 to 95.

**Returns:**
int
### getAztecSymbolMode() {#getAztecSymbolMode--}
```
public AztecSymbolMode getAztecSymbolMode()
```


Gets a Aztec Symbol mode. Default value: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public int getECIEncoding()
```


Gets ECI encoding. Used when AztecEncodeMode is Auto. Default value: ISO-8859-1

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public int getLayersCount()
```


Gets layers count of Aztec symbol. Layers count should be in range from 1 to 3 for Compact mode and in range from 1 to 32 for Full Range mode. Default value: 0 (auto).

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


Barcode ID for Structured Append mode of Aztec barcode. Barcode ID should be in range from 1 to barcodes count. Default value: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Barcodes count for Structured Append mode of Aztec barcode. Barcodes count should be in range from 1 to 26. Default value: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public String getStructuredAppendFileId()
```


File ID for Structured Append mode of Aztec barcode (optional field). File ID should not contain spaces. Default value: empty string

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public void setAspectRatio(float value)
```


Height/Width ratio of 2D BarCode module.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setAztecEncodeMode(AztecEncodeMode value) {#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public void setAztecEncodeMode(AztecEncodeMode value)
```


Sets a Aztec encode mode. Default value: Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.barcode.generation.AztecEncodeMode |  |

### setAztecErrorLevel(int value) {#setAztecErrorLevel-int-}
```
public void setAztecErrorLevel(int value)
```


Level of error correction of Aztec types of barcode. Value should between 5 to 95.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setAztecSymbolMode(AztecSymbolMode value) {#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public void setAztecSymbolMode(AztecSymbolMode value)
```


Sets a Aztec Symbol mode. Default value: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


Sets ECI encoding. Used when AztecEncodeMode is Auto. Default value: ISO-8859-1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public void setLayersCount(int value)
```


Sets layers count of Aztec symbol. Layers count should be in range from 1 to 3 for Compact mode and in range from 1 to 32 for Full Range mode. Default value: 0 (auto).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public void setReaderInitialization(boolean value)
```


Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public void setStructuredAppendBarcodeId(int value)
```


Barcode ID for Structured Append mode of Aztec barcode. Barcode ID should be in range from 1 to barcodes count. Default value: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public void setStructuredAppendBarcodesCount(int value)
```


Barcodes count for Structured Append mode of Aztec barcode. Barcodes count should be in range from 1 to 26. Default value: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public void setStructuredAppendFileId(String value)
```


File ID for Structured Append mode of Aztec barcode (optional field). File ID should not contain spaces. Default value: empty string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  AztecParameters .

**Returns:**
java.lang.String - A string that represents this  AztecParameters .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

