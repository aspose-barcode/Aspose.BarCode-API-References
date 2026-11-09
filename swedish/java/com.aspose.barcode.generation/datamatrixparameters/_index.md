---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode för Java API-referens"
description: "DataMatrix-parametrar."
type: docs
weight: 32
url: /sv/java/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix-parametrar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höjd/bredd-förhållande för 2D BarCode-modul. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Hämtar ECI-kodning. |
| [getEccType()](#getEccType--) | Hämtar en Datamatrix ECC-typ. |
| [getEncodeMode()](#getEncodeMode--) | Kodningsläge för Datamatrix-streckkod. |
| [getMacroCharacters()](#getMacroCharacters--) | Makrotecknen 05 och 06 används för att få en mer kompakt kodning i speciella lägen. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Streckkod-ID för Structured Append-läge för Datamatrix-streckkod. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Antal streckkoder för Structured Append-läge för Datamatrix-streckkod. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Fil-ID för Structured Append-läge för Datamatrix-streckkod. |
| [getVersion()](#getVersion--) | Hämtar en Datamatrix-symbolstorlek. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höjd/bredd-förhållande för 2D BarCode-modul. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ställer in ECI-kodning. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Ställer in en Datamatrix ECC-typ. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Kodningsläge för Datamatrix-streckkod. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Makrotecknen 05 och 06 används för att få en mer kompakt kodning i speciella lägen. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Höjd/bredd-förhållande för 2D BarCode-modul.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Hämtar ECI-kodning. Används när EncodeMode är Auto. Standardvärde: ISO-8859-1

**Returns:**
int – ECI‑kodning.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Hämtar en Datamatrix ECC‑typ. Standardvärde: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Kodningsläge för Datamatrix‑streckkod. Standardvärde: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Makrotecken 05 och 06 används för att få en mer kompakt kodning i speciallägen. Kan endast användas med DataMatrixEccType.Ecc200 eller DataMatrixEccType.EccAuto. Kan inte användas med EncodeTypes.GS1DataMatrix Standardvärde: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
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
public final int hashCode()
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


Höjd/bredd-förhållande för 2D BarCode-modul.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Ställer in ECI-kodning. Används när EncodeMode är Auto. Standardvärde: ISO-8859-1

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | ECI‑kodning. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Ställer in en Datamatrix ECC‑typ. Standardvärde: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | en Datamatrix ECC‑typ. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Kodningsläge för Datamatrix‑streckkod. Standardvärde: EncodeMode.Auto.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Makrotecken 05 och 06 används för att få en mer kompakt kodning i speciallägen. Kan endast användas med DataMatrixEccType.Ecc200 eller DataMatrixEccType.EccAuto. Kan inte användas med EncodeTypes.GS1DataMatrix Standardvärde: MacroCharacters.None.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitiering. Standardvärde: false

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Streckkod-ID för Structured Append-läge för Datamatrix-streckkod. Standardvärde: 0

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Antal streckkoder för Structured Append-läge för Datamatrix-streckkod. Standardvärde: 0

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Fil-ID för Structured Append-läge för Datamatrix-streckkod. Standardvärde: 0

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Ställer in en Datamatrix-symbolstorlek. Standardvärde: Version.Auto.

**Parameters:**
| Parameter | Typ | Beskrivning |
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
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

