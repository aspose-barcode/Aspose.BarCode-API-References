---
title: DataMatrixParameters
second_title: Aspose.BarCode for Java API Reference
description: DataMatrix parameters.
type: docs
weight: 33
url: /java/com.aspose.barcode.generation/datamatrixparameters/
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
| [getDataMatrixVersion()](#getDataMatrixVersion--) | Gets a Datamatrix symbol size. |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEccType()](#getEccType--) | Gets a Datamatrix ECC type. |
| [getEncodeMode()](#getEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getMacroCharacters()](#getMacroCharacters--) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. |
| [getRows()](#getRows--) | Rows count. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Barcode ID for Structured Append mode of Datamatrix barcode. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Barcodes count for Structured Append mode of Datamatrix barcode. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | File ID for Structured Append mode of Datamatrix barcode. |
| [getVersion()](#getVersion--) | Gets a Datamatrix symbol size. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Height/Width ratio of 2D BarCode module. |
| [setColumns(int value)](#setColumns-int-) | Columns count. |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | Sets a Datamatrix ECC type. |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Sets a Datamatrix symbol size. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Sets ECI encoding. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Sets a Datamatrix ECC type. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [setRows(int value)](#setRows-int-) | Rows count. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Barcode ID for Structured Append mode of Datamatrix barcode. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Barcodes count for Structured Append mode of Datamatrix barcode. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | File ID for Structured Append mode of Datamatrix barcode. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Sets a Datamatrix symbol size. |
| [toString()](#toString--) | Returns a human-readable string representation of this [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
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
public final float getAspectRatio()
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
public final int getColumns()
```


Columns count.

**Returns:**
int
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public final DataMatrixEccType getDataMatrixEcc()
```


Gets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public final DataMatrixEncodeMode getDataMatrixEncodeMode()
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public final DataMatrixVersion getDataMatrixVersion()
```


Gets a Datamatrix symbol size. Default value: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Gets ECI encoding. Used when EncodeMode is Auto. Default value: ISO-8859-1

**Returns:**
int - ECI encoding.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Gets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.Ecc200 or DataMatrixEccType.EccAuto. Cannot be used with EncodeTypes.GS1DataMatrix Default value: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getRows() {#getRows--}
```
public final int getRows()
```


Rows count.

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


File ID for Structured Append mode of Datamatrix barcode. Default value: 0

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Gets a Datamatrix symbol size. Default value: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
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
public final void setAspectRatio(float value)
```


Height/Width ratio of 2D BarCode module.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Columns count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setDataMatrixEcc(DataMatrixEccType value)
```


Sets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | a Datamatrix ECC type. |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setDataMatrixVersion(DataMatrixVersion value)
```


Sets a Datamatrix symbol size. Default value: Version.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | a Datamatrix symbol size. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Sets ECI encoding. Used when EncodeMode is Auto. Default value: ISO-8859-1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ECI encoding. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Sets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | a Datamatrix ECC type. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.Ecc200 or DataMatrixEccType.EccAuto. Cannot be used with EncodeTypes.GS1DataMatrix Default value: MacroCharacters.None.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Rows count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


File ID for Structured Append mode of Datamatrix barcode. Default value: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Sets a Datamatrix symbol size. Default value: Version.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | a Datamatrix symbol size. |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

**Returns:**
java.lang.String - A string that represents this [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).
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

