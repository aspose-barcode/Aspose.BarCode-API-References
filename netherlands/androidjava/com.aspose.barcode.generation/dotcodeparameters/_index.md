---
title: DotCodeParameters
second_title: Aspose.BarCode for Android via Java API-referentie
description: DotCode-parameters.
type: docs
weight: 36
url: /nl/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode-parameters.
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Identificeert het aantal kolommen. |
| [getDotCodeEncodeMode()](#getDotCodeEncodeMode--) | Identificeert de DotCode‑codeermodus. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Identificeert de ID van de DotCode gestructureerde toevoegingsmodus barcode. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Identificeert het aantal barcodes in de DotCode gestructureerde toevoegingsmodus. |
| [getECIEncoding()](#getECIEncoding--) | Identificeert de ECI‑codering. |
| [getEncodeMode()](#getEncodeMode--) | Identificeert de DotCode‑codeermodus. |
| [getRows()](#getRows--) | Identificeert het aantal rijen. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Identificeert de ID van de DotCode gestructureerde toevoegingsmodus barcode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Identificeert het aantal barcodes in de DotCode gestructureerde toevoegingsmodus. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [setColumns(int value)](#setColumns-int-) | Identificeert het aantal kolommen. |
| [setDotCodeEncodeMode(DotCodeEncodeMode value)](#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identificeert de DotCode‑codeermodus. |
| [setDotCodeStructuredAppendModeBarcodeId(int value)](#setDotCodeStructuredAppendModeBarcodeId-int-) | Identificeert de ID van de DotCode gestructureerde toevoegingsmodus barcode. |
| [setDotCodeStructuredAppendModeBarcodesCount(int value)](#setDotCodeStructuredAppendModeBarcodesCount-int-) | Identificeert het aantal barcodes in de DotCode gestructureerde toevoegingsmodus. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identificeert de ECI‑codering. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identificeert de DotCode‑codeermodus. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. |
| [setRows(int value)](#setRows-int-) | Identificeert het aantal rijen. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Identificeert de ID van de DotCode gestructureerde toevoegingsmodus barcode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Identificeert het aantal barcodes in de DotCode gestructureerde toevoegingsmodus. |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters). |
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
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Identificeert het aantal kolommen. De som van het aantal rijen plus het aantal kolommen van een DotCode‑symbool moet oneven zijn. Het aantal kolommen moet minstens 5 zijn. Standaardwaarde: -1

**Returns:**
int
### getDotCodeEncodeMode() {#getDotCodeEncodeMode--}
```
public final DotCodeEncodeMode getDotCodeEncodeMode()
```


Identificeert de DotCode‑coderingmodus. Standaardwaarde: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


Identificeert de ID van de DotCode gestructureerde append‑modus barcode. ID begint bij 1 en moet kleiner dan of gelijk aan het aantal barcodes zijn. Standaardwaarde is -1.

**Returns:**
int
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


Identificeert het aantal barcodes in de DotCode gestructureerde append‑modus. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identificeert ECI‑codering. Wordt gebruikt wanneer DotCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


Identificeert de DotCode‑coderingmodus. Standaardwaarde: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Identificeert het aantal rijen. De som van het aantal rijen plus het aantal kolommen van een DotCode‑symbool moet oneven zijn. Het aantal rijen moet minstens 5 zijn. Standaardwaarde: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Identificeert de ID van de DotCode gestructureerde append‑modus barcode. ID begint bij 1 en moet kleiner dan of gelijk aan het aantal barcodes zijn. Standaardwaarde is -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Identificeert het aantal barcodes in de DotCode gestructureerde append‑modus. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn.

**Returns:**
int
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


Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

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

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Identificeert het aantal kolommen. De som van het aantal rijen plus het aantal kolommen van een DotCode‑symbool moet oneven zijn. Het aantal kolommen moet minstens 5 zijn. Standaardwaarde: -1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setDotCodeEncodeMode(DotCodeEncodeMode value) {#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setDotCodeEncodeMode(DotCodeEncodeMode value)
```


Identificeert de DotCode‑coderingmodus. Standaardwaarde: Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setDotCodeStructuredAppendModeBarcodeId(int value) {#setDotCodeStructuredAppendModeBarcodeId-int-}
```
public final void setDotCodeStructuredAppendModeBarcodeId(int value)
```


Identificeert de ID van de DotCode gestructureerde append‑modus barcode. ID begint bij 1 en moet kleiner dan of gelijk aan het aantal barcodes zijn. Standaardwaarde is -1.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setDotCodeStructuredAppendModeBarcodesCount(int value) {#setDotCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setDotCodeStructuredAppendModeBarcodesCount(int value)
```


Identificeert het aantal barcodes in de DotCode gestructureerde append‑modus. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identificeert ECI‑codering. Wordt gebruikt wanneer DotCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


Identificeert de DotCode‑coderingmodus. Standaardwaarde: Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Geeft aan of code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Identificeert het aantal rijen. De som van het aantal rijen plus het aantal kolommen van een DotCode‑symbool moet oneven zijn. Het aantal rijen moet minstens 5 zijn. Standaardwaarde: -1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Identificeert de ID van de DotCode gestructureerde append‑modus barcode. ID begint bij 1 en moet kleiner dan of gelijk aan het aantal barcodes zijn. Standaardwaarde is -1.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Identificeert het aantal barcodes in de DotCode gestructureerde append‑modus. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).

**Returns:**
java.lang.String - Een string die dit [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) vertegenwoordigt.
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

