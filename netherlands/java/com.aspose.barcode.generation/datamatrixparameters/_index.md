---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode for Java API-referentie"
description: "DataMatrix parameters."
type: docs
weight: 32
url: /nl/java/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix parameters.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Haalt ECI-codering op. |
| [getEccType()](#getEccType--) | Haalt een Datamatrix ECC-type op. |
| [getEncodeMode()](#getEncodeMode--) | Coderingsmodus van Datamatrix-barcode. |
| [getMacroCharacters()](#getMacroCharacters--) | Macro‑tekens 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Barcode-ID voor gestructureerde toevoegingsmodus van Datamatrix-streepjescode. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aantal barcodes voor Structured Append-modus van Datamatrix-barcode. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Bestands-ID voor Structured Append-modus van Datamatrix-barcode. |
| [getVersion()](#getVersion--) | Haalt een Datamatrix-symboolgrootte op. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Stelt ECI-codering in. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Stelt een Datamatrix ECC-type in. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Coderingsmodus van Datamatrix-barcode. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Macro‑tekens 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Barcode-ID voor gestructureerde toevoegingsmodus van Datamatrix-streepjescode. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Aantal barcodes voor Structured Append-modus van Datamatrix-barcode. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Bestands-ID voor Structured Append-modus van Datamatrix-barcode. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Stelt een Datamatrix-symboolgrootte in. |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Hoogte/breedteverhouding van 2D BarCode-module.

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


Haalt ECI-codering op. Wordt gebruikt wanneer EncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Returns:**
int - ECI-codering.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Haalt een Datamatrix ECC-type op. Standaardwaarde: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Coderingsmodus van Datamatrix-barcode. Standaardwaarde: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro Characters 05 en 06 waarden worden gebruikt om compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met DataMatrixEccType.Ecc200 of DataMatrixEccType.EccAuto. Kan niet worden gebruikt met EncodeTypes.GS1DataMatrix Standaardwaarde: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Barcode-ID voor Structured Append-modus van Datamatrix-barcode. Standaardwaarde: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Aantal barcodes voor Structured Append-modus van Datamatrix-barcode. Standaardwaarde: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Bestands-ID voor Structured Append-modus van Datamatrix-barcode. Standaardwaarde: 0

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Haalt een Datamatrix-symboolgrootte op. Standaardwaarde: Version.Auto.

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


Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. Standaardwaarde: false

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


Hoogte/breedteverhouding van 2D BarCode-module.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Stelt ECI-codering in. Wordt gebruikt wanneer EncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | ECI-codering. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Stelt een Datamatrix ECC-type in. Standaardwaarde: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | een Datamatrix ECC-type. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Coderingsmodus van Datamatrix-barcode. Standaardwaarde: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro Characters 05 en 06 waarden worden gebruikt om compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met DataMatrixEccType.Ecc200 of DataMatrixEccType.EccAuto. Kan niet worden gebruikt met EncodeTypes.GS1DataMatrix Standaardwaarde: MacroCharacters.None.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. Standaardwaarde: false

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Barcode-ID voor Structured Append-modus van Datamatrix-barcode. Standaardwaarde: 0

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Aantal barcodes voor Structured Append-modus van Datamatrix-barcode. Standaardwaarde: 0

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Bestands-ID voor Structured Append-modus van Datamatrix-barcode. Standaardwaarde: 0

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Stelt een Datamatrix-symboolgrootte in. Standaardwaarde: Version.Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | een Datamatrix-symboolgrootte. |

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

**Returns:**
java.lang.String - Een string die deze [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

