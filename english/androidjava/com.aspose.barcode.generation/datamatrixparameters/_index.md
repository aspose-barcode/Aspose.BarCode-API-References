---
title: DataMatrixParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: DataMatrix parameters.
type: docs
weight: 34
url: /androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix parameters.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Height/Width ratio of 2D BarCode module. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Columns count. |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | Gets a Datamatrix ECC type. |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixVersion()](#getDataMatrixVersion--) | Gets or sets a Datamatrix symbol size. |
| [getECIEncoding()](#getECIEncoding--) | Gets or sets ECI encoding. |
| [getMacroCharacters()](#getMacroCharacters--) | ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. |
| [getRows()](#getRows--) | Rows count. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Barcode ID for Structured Append mode of Datamatrix barcode. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Barcodes count for Structured Append mode of Datamatrix barcode. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | File ID for Structured Append mode of Datamatrix barcode. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Height/Width ratio of 2D BarCode module. |
| [setColumns(int value)](#setColumns-int-) | Columns count. |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | Sets a Datamatrix ECC type. |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Gets or sets a Datamatrix symbol size. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Gets or sets ECI encoding. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [setRows(int value)](#setRows-int-) | Rows count. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Barcode ID for Structured Append mode of Datamatrix barcode. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Barcodes count for Structured Append mode of Datamatrix barcode. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | File ID for Structured Append mode of Datamatrix barcode. |
| [toString()](#toString--) | Returns a human-readable string representation of this  DataMatrixParameters . |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public int getColumns()
```


Columns count.

**Returns:**
int
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public DataMatrixEccType getDataMatrixEcc()
```


Gets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype)
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public DataMatrixEncodeMode getDataMatrixEncodeMode()
```


Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.AUTO.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public DataMatrixVersion getDataMatrixVersion()
```


Gets or sets a Datamatrix symbol size. Default value: DataMatrixVersion.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion)
### getECIEncoding() {#getECIEncoding--}
```
public int getECIEncoding()
```


Gets or sets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1

**Returns:**
int
### getMacroCharacters() {#getMacroCharacters--}
```
public MacroCharacter getMacroCharacters()
```


ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.ECC\_200 or DataMatrixEccType.ECC\_AUTO. Cannot be used with EncodeTypes.GS\_1\_DATA\_MATRIX Default value: MacroCharacter.NONE.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getRows() {#getRows--}
```
public int getRows()
```


Rows count.

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


File ID for Structured Append mode of Datamatrix barcode. Default value: 0

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
```


Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false

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

### setColumns(int value) {#setColumns-int-}
```
public void setColumns(int value)
```


Columns count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public void setDataMatrixEcc(DataMatrixEccType value)
```


Sets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) |  |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.AUTO.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public void setDataMatrixVersion(DataMatrixVersion value)
```


Gets or sets a Datamatrix symbol size. Default value: DataMatrixVersion.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


Gets or sets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public void setMacroCharacters(MacroCharacter value)
```


ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.ECC\_200 or DataMatrixEccType.ECC\_AUTO. Cannot be used with EncodeTypes.GS\_1\_DATA\_MATRIX Default value: MacroCharacter.NONE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public void setReaderProgramming(boolean value)
```


Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRows(int value) {#setRows-int-}
```
public void setRows(int value)
```


Rows count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public void setStructuredAppendBarcodeId(int value)
```


Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public void setStructuredAppendBarcodesCount(int value)
```


Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public void setStructuredAppendFileId(int value)
```


File ID for Structured Append mode of Datamatrix barcode. Default value: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  DataMatrixParameters .

**Returns:**
java.lang.String - A string that represents this  DataMatrixParameters .
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

