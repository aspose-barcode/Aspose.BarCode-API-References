---
title: "DataMatrixParametersUI"
second_title: "Aspose.BarCode för Java API-referens"
description: "UI-omslag för klassen com.aspose.barcode.generation.DataMatrixParameters."
type: docs
weight: 14
url: /sv/java/com.aspose.barcode.barcodecontrol/datamatrixparametersui/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParametersUI
```

UI-omslag för klassen com.aspose.barcode.generation.DataMatrixParameters.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höjd/bredd-förhållande för 2D BarCode-modul. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Hämtar ECI-kodning. |
| [getEccType()](#getEccType--) | Hämtar en Datamatrix ECC-typ. |
| [getEncodeMode()](#getEncodeMode--) | Kodningsläge för Datamatrix-streckkod. |
| [getMacroCharacters()](#getMacroCharacters--) | Protokoll för makrotecken i den första positionen (ECC 200 only) |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Streckkod-ID för Structured Append-läge. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Antal streckkoder för Structured Append-läge. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Fil-ID för Structured Append-läge. |
| [getVersion()](#getVersion--) | DataMatrix-symbolstorlek. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höjd/bredd-förhållande för 2D BarCode-modul. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ställer in ECI-kodning. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Ställer in en Datamatrix ECC-typ. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Kodningsläge för Datamatrix-streckkod. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Protokoll för makrotecken i den första positionen (ECC 200 only) |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Streckkod-ID för Structured Append-läge. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Antal streckkoder för Structured Append-läge. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Fil-ID för Structured Append-läge. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | DataMatrix-symbolstorlek. |
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


Hämtar ECI‑kodning. Används när EncodeMode är Auto.

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


Protokoll för makrotecken i den första positionen (ECC 200 only)

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Streckkod-ID för Structured Append-läge.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Antal streckkoder för Structured Append-läge.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Fil-ID för Structured Append-läge.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


DataMatrix-symbolstorlek.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion)
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


Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering.

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


Ställer in ECI‑kodning. Används när EncodeMode är Auto.

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


Protokoll för makrotecken i den första positionen (ECC 200 only)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Streckkod-ID för Structured Append-läge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Antal streckkoder för Structured Append-läge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Fil-ID för Structured Append-läge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


DataMatrix-symbolstorlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) |  |

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

