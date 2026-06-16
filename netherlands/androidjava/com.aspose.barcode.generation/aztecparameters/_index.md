---
title: AztecParameters
second_title: Aspose.BarCode for Android via Java API-referentie
description: Aztec-parameters.
type: docs
weight: 12
url: /nl/androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Aztec-parameters.
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [getAztecEncodeMode()](#getAztecEncodeMode--) | Haalt een Aztec-encodeermodus op. |
| [getAztecErrorLevel()](#getAztecErrorLevel--) | Niveau van foutcorrectie van Aztec-typen barcode. |
| [getAztecSymbolMode()](#getAztecSymbolMode--) | Haalt een Aztec-symboolmodus op. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Haalt ECI-codering op. |
| [getEncodeMode()](#getEncodeMode--) | Haalt een Aztec-encodeermodus op. |
| [getErrorLevel()](#getErrorLevel--) | Niveau van foutcorrectie van Aztec-typen barcode. |
| [getLayersCount()](#getLayersCount--) | Haalt het aantal lagen van het Aztec-symbool op. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Barcode-ID voor de Structured Append-modus van de Aztec-barcode. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aantal barcodes voor de Structured Append-modus van de Aztec-barcode. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Bestands-ID voor de Structured Append-modus van de Aztec-barcode (optioneel veld). |
| [getSymbolMode()](#getSymbolMode--) | Haalt een Aztec-symboolmodus op. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [setAztecEncodeMode(AztecEncodeMode value)](#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Stelt een Aztec-coderingsmodus in. |
| [setAztecErrorLevel(int value)](#setAztecErrorLevel-int-) | Niveau van foutcorrectie van Aztec-typen barcode. |
| [setAztecSymbolMode(AztecSymbolMode value)](#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Stelt een Aztec-symboolmodus in. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Stelt ECI-codering in. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Stelt een Aztec-coderingsmodus in. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Niveau van foutcorrectie van Aztec-typen barcode. |
| [setLayersCount(int value)](#setLayersCount-int-) | Stelt het aantal lagen van het Aztec-symbool in. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Barcode-ID voor de Structured Append-modus van de Aztec-barcode. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Aantal barcodes voor de Structured Append-modus van de Aztec-barcode. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Bestands-ID voor de Structured Append-modus van de Aztec-barcode (optioneel veld). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Stelt een Aztec-symboolmodus in. |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [AztecParameters](../../com.aspose.barcode.generation/aztecparameters). |
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
### getAztecEncodeMode() {#getAztecEncodeMode--}
```
public final AztecEncodeMode getAztecEncodeMode()
```


Haalt een Aztec-coderingsmodus op. Standaardwaarde: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - een Aztec-coderingsmodus.
### getAztecErrorLevel() {#getAztecErrorLevel--}
```
public final int getAztecErrorLevel()
```


Niveau van foutcorrectie van Aztec-type barcodes. Waarde moet tussen 5 en 95 liggen.

**Returns:**
int
### getAztecSymbolMode() {#getAztecSymbolMode--}
```
public final AztecSymbolMode getAztecSymbolMode()
```


Haalt een Aztec-symboolmodus op. Standaardwaarde: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
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


Haalt ECI-codering op. Wordt gebruikt wanneer AztecEncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Returns:**
int - ECI-codering.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Haalt een Aztec-coderingsmodus op. Standaardwaarde: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - een Aztec-coderingsmodus.
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Niveau van foutcorrectie van Aztec-type barcodes. Waarde moet tussen 5 en 95 liggen.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Haalt het aantal lagen van het Aztec-symbool op. Het aantal lagen moet liggen tussen 1 en 3 voor Compact-modus en tussen 1 en 32 voor Full Range-modus. Standaardwaarde: 0 (auto).

**Returns:**
int - aantal lagen van het Aztec-symbool.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Barcode-ID voor de Structured Append-modus van de Aztec-barcode. Barcode-ID moet liggen tussen 1 en het aantal barcodes. Standaardwaarde: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Aantal barcodes voor de Structured Append-modus van de Aztec-barcode. Aantal barcodes moet liggen tussen 1 en 26. Standaardwaarde: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Bestands-ID voor de Structured Append-modus van de Aztec-barcode (optioneel veld). Bestands-ID mag geen spaties bevatten. Standaardwaarde: lege tekenreeks

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Haalt een Aztec-symboolmodus op. Standaardwaarde: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie.

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

### setAztecEncodeMode(AztecEncodeMode value) {#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setAztecEncodeMode(AztecEncodeMode value)
```


Stelt een Aztec-coderingsmodus in. Standaardwaarde: Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.barcode.generation.AztecEncodeMode | een Aztec-coderingsmodus. |

### setAztecErrorLevel(int value) {#setAztecErrorLevel-int-}
```
public final void setAztecErrorLevel(int value)
```


Niveau van foutcorrectie van Aztec-type barcodes. Waarde moet tussen 5 en 95 liggen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setAztecSymbolMode(AztecSymbolMode value) {#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setAztecSymbolMode(AztecSymbolMode value)
```


Stelt een Aztec-symboolmodus in. Standaardwaarde: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | een Aztec-symboolmodus. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Stelt ECI-codering in. Wordt gebruikt wanneer AztecEncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | ECI-codering. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Stelt een Aztec-coderingsmodus in. Standaardwaarde: Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.barcode.generation.AztecEncodeMode | een Aztec-coderingsmodus. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Niveau van foutcorrectie van Aztec-type barcodes. Waarde moet tussen 5 en 95 liggen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Stelt het aantal lagen van het Aztec-symbool in. Het aantal lagen moet liggen tussen 1 en 3 voor Compact-modus en tussen 1 en 32 voor Full Range-modus. Standaardwaarde: 0 (auto).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | aantal lagen van het Aztec-symbool. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Barcode-ID voor de Structured Append-modus van de Aztec-barcode. Barcode-ID moet liggen tussen 1 en het aantal barcodes. Standaardwaarde: 0

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Aantal barcodes voor de Structured Append-modus van de Aztec-barcode. Aantal barcodes moet liggen tussen 1 en 26. Standaardwaarde: 0

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Bestands-ID voor de Structured Append-modus van de Aztec-barcode (optioneel veld). Bestands-ID mag geen spaties bevatten. Standaardwaarde: lege tekenreeks

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Stelt een Aztec-symboolmodus in. Standaardwaarde: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | een Aztec-symboolmodus. |

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String - Een string die dit [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

