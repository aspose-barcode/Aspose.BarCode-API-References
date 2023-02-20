---
title: DataMatrixParameters
second_title: Aspose.BarCode for Java API Reference
description: DataMatrix parameters.
type: docs
weight: 28
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
| [getCodeTextEncoding()](#getCodeTextEncoding--) | Gets the encoding of codetext. |
| [getColumns()](#getColumns--) | Columns count. |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | Gets a Datamatrix ECC type. |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getMacroCharacters()](#getMacroCharacters--) | ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. |
| [getRows()](#getRows--) | Rows count. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Height/Width ratio of 2D BarCode module. |
| [setCodeTextEncoding(Charset value)](#setCodeTextEncoding-java.nio.charset.Charset-) | Sets the encoding of codetext. |
| [setColumns(int value)](#setColumns-int-) | Columns count. |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | Sets a Datamatrix ECC type. |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. |
| [setRows(int value)](#setRows-int-) | Rows count. |
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
### getCodeTextEncoding() {#getCodeTextEncoding--}
```
public Charset getCodeTextEncoding()
```


Gets the encoding of codetext. Default value: UTF-8

**Returns:**
java.nio.charset.Charset
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public void setAspectRatio(float value)
```


Height/Width ratio of 2D BarCode module.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setCodeTextEncoding(Charset value) {#setCodeTextEncoding-java.nio.charset.Charset-}
```
public void setCodeTextEncoding(Charset value)
```


Sets the encoding of codetext. Default value: UTF-8

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

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

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public void setMacroCharacters(MacroCharacter value)
```


ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.ECC\_200 or DataMatrixEccType.ECC\_AUTO. Cannot be used with EncodeTypes.GS\_1\_DATA\_MATRIX Default value: MacroCharacter.NONE.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setRows(int value) {#setRows-int-}
```
public void setRows(int value)
```


Rows count.

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

