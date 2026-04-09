---
title: DataMatrixParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: DataMatrix-parametrar.
type: docs
weight: 34
url: /sv/androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix-parametrar.
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Kolumnantal. |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | Hämtar en Datamatrix ECC-typ. |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixVersion()](#getDataMatrixVersion--) | Hämtar en Datamatrix-symbolstorlek. |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEccType()](#getEccType--) | Hämtar en Datamatrix ECC-typ. |
| [getEncodeMode()](#getEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getMacroCharacters()](#getMacroCharacters--) | Macro-tecken 05 och 06 används för att få en mer kompakt kodning i speciallägen. |
| [getRows()](#getRows--) | Antal rader. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Streckkod-ID för Structured Append-läge för Datamatrix-streckkod. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Antal streckkoder för Structured Append-läge för Datamatrix-streckkod. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Fil-ID för Structured Append-läge för Datamatrix-streckkod. |
| [getVersion()](#getVersion--) | Hämtar en Datamatrix-symbolstorlek. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [setColumns(int value)](#setColumns-int-) | Kolumnantal. |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | Ställer in en Datamatrix ECC-typ. |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Ställer in en Datamatrix-symbolstorlek. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ställer in ECI‑kodning. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Ställer in en Datamatrix ECC-typ. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Macro-tecken 05 och 06 används för att få en mer kompakt kodning i speciallägen. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [setRows(int value)](#setRows-int-) | Antal rader. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Streckkod-ID för Structured Append-läge för Datamatrix-streckkod. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Antal streckkoder för Structured Append-läge för Datamatrix-streckkod. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Fil-ID för Structured Append-läge för Datamatrix-streckkod. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Ställer in en Datamatrix-symbolstorlek. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Höjd/bredd-förhållande för 2D BarCode-modulen.

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


Kolumnantal.

**Returns:**
int
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public final DataMatrixEccType getDataMatrixEcc()
```


Hämtar en Datamatrix ECC-typ. Standardvärde: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public final DataMatrixEncodeMode getDataMatrixEncodeMode()
```


Kodningsläge för Datamatrix-streckkod. Standardvärde: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public final DataMatrixVersion getDataMatrixVersion()
```


Hämtar en Datamatrix-symbolstorlek. Standardvärde: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Hämtar ECI-kodning. Används när EncodeMode är Auto. Standardvärde: ISO-8859-1

**Returns:**
int - ECI‑kodning.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Hämtar en Datamatrix ECC-typ. Standardvärde: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Kodningsläge för Datamatrix-streckkod. Standardvärde: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro Characters 05 och 06 används för att erhålla en mer kompakt kodning i speciella lägen. Kan endast användas med DataMatrixEccType.Ecc200 eller DataMatrixEccType.EccAuto. Kan inte användas med EncodeTypes.GS1DataMatrix. Standardvärde: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getRows() {#getRows--}
```
public final int getRows()
```


Antal rader.

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Streckkod-ID för Structured Append-läge för Datamatrix-streckkod. Standardvärde: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Antal streckkoder för Structured Append-läge för Datamatrix-streckkod. Standardvärde: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Fil-ID för Structured Append-läge för Datamatrix-streckkod. Standardvärde: 0

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Hämtar en Datamatrix-symbolstorlek. Standardvärde: Version.Auto.

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


Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitiering. Standardvärde: false

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


Höjd/bredd-förhållande för 2D BarCode-modulen.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Kolumnantal.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setDataMatrixEcc(DataMatrixEccType value)
```


Ställer in en Datamatrix ECC-typ. Standardvärde: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | en Datamatrix ECC-typ. |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


Kodningsläge för Datamatrix-streckkod. Standardvärde: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setDataMatrixVersion(DataMatrixVersion value)
```


Ställer in en Datamatrix-symbolstorlek. Standardvärde: Version.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | en Datamatrix-symbolstorlek. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Ställer in ECI-kodning. Används när EncodeMode är Auto. Standardvärde: ISO-8859-1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | ECI‑kodning. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Ställer in en Datamatrix ECC-typ. Standardvärde: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | en Datamatrix ECC-typ. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Kodningsläge för Datamatrix-streckkod. Standardvärde: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro Characters 05 och 06 används för att erhålla en mer kompakt kodning i speciella lägen. Kan endast användas med DataMatrixEccType.Ecc200 eller DataMatrixEccType.EccAuto. Kan inte användas med EncodeTypes.GS1DataMatrix. Standardvärde: MacroCharacters.None.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitiering. Standardvärde: false

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Antal rader.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Streckkod-ID för Structured Append-läge för Datamatrix-streckkod. Standardvärde: 0

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Antal streckkoder för Structured Append-läge för Datamatrix-streckkod. Standardvärde: 0

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Fil-ID för Structured Append-läge för Datamatrix-streckkod. Standardvärde: 0

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Ställer in en Datamatrix-symbolstorlek. Standardvärde: Version.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | en Datamatrix-symbolstorlek. |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

**Returns:**
java.lang.String - En sträng som representerar detta [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

