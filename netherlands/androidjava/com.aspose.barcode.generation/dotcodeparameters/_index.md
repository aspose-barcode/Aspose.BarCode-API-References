---
title: "DotCodeParameters"
second_title: "Aspose.BarCode voor Android via Java API-referentie"
description: "DotCode-parameters."
type: docs
weight: 35
url: /nl/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode-parameters.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Identificeert het aantal kolommen. |
| [getECIEncoding()](#getECIEncoding--) | Identificeert ECI-codering. |
| [getEncodeMode()](#getEncodeMode--) | Identificeert de coderingmodus van DotCode. |
| [getRows()](#getRows--) | Identificeert het aantal rijen. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Identificeert de ID van de DotCode gestructureerde toevoegingsmodus barcode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Identificeert het aantal barcodes van de DotCode gestructureerde toevoegingsmodus. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [setColumns(int value)](#setColumns-int-) | Identificeert het aantal kolommen. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identificeert ECI-codering. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identificeert de coderingmodus van DotCode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. |
| [setRows(int value)](#setRows-int-) | Identificeert het aantal rijen. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Identificeert de ID van de DotCode gestructureerde toevoegingsmodus barcode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Identificeert het aantal barcodes van de DotCode gestructureerde toevoegingsmodus. |
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


Identificeert het aantal kolommen. De som van het aantal rijen en het aantal kolommen van een DotCode-symbool moet oneven zijn. Het aantal kolommen moet minimaal 5 zijn. Standaardwaarde: -1

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identificeert ECI-codering. Wordt gebruikt wanneer DotCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


Identificeert de DotCode-coderingmodus. Standaardwaarde: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Identificeert het aantal rijen. De som van het aantal rijen en het aantal kolommen van een DotCode-symbool moet oneven zijn. Het aantal rijen moet minimaal 5 zijn. Standaardwaarde: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Identificeert de ID van de DotCode gestructureerde toevoegingsmodus barcode. De ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Identificeert het aantal barcodes van de DotCode gestructureerde toevoegingsmodus. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn.

**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

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


Identificeert het aantal kolommen. De som van het aantal rijen en het aantal kolommen van een DotCode-symbool moet oneven zijn. Het aantal kolommen moet minimaal 5 zijn. Standaardwaarde: -1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identificeert ECI-codering. Wordt gebruikt wanneer DotCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


Identificeert de DotCode-coderingmodus. Standaardwaarde: Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Identificeert het aantal rijen. De som van het aantal rijen en het aantal kolommen van een DotCode-symbool moet oneven zijn. Het aantal rijen moet minimaal 5 zijn. Standaardwaarde: -1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Identificeert de ID van de DotCode gestructureerde toevoegingsmodus barcode. De ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Identificeert het aantal barcodes van de DotCode gestructureerde toevoegingsmodus. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn.

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
java.lang.String - Een tekenreeks die deze [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) vertegenwoordigt.
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

