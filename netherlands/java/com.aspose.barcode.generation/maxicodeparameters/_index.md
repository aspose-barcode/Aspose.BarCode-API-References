---
title: "MaxiCodeParameters"
second_title: "Aspose.BarCode for Java API-referentie"
description: "MaxiCode parameters."
type: docs
weight: 55
url: /nl/java/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode parameters.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Haalt ECI-codering op. |
| [getEncodeMode()](#getEncodeMode--) | Haalt een MaxiCode-coderingmodus op. |
| [getMode()](#getMode--) | Haalt een MaxiCode-coderingmodus op. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Haalt een MaxiCode-barcode-id op in gestructureerde toevoegingsmodus. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Haalt het aantal MaxiCode-barcodes op in gestructureerde toevoegingsmodus. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Stelt ECI-codering in. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Stelt een MaxiCode-codermodus in. |
| [setMode(MaxiCodeMode value)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | Stelt een MaxiCode-codermodus in. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Stelt een MaxiCode barcode-id in in gestructureerde toevoegingsmodus. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Stelt een MaxiCode barcode-aantal in in gestructureerde toevoegingsmodus. |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters). |
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


Haalt ECI-codering op. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Returns:**
int - ECI-codering.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Haalt een MaxiCode-coderingsmodus op. Standaardwaarde: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public final MaxiCodeMode getMode()
```


Haalt een MaxiCode-coderingmodus op.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - a MaxiCode encode mode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Haalt een MaxiCode barcode-id op in gestructureerde toevoegingsmodus. ID moet een waarde tussen 1 en 8 zijn. Standaardwaarde: 0

**Returns:**
int - een MaxiCode-barcode-id in gestructureerde toevoegingsmodus.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Haalt een MaxiCode barcode-aantal op in gestructureerde toevoegingsmodus. Het aantal moet een waarde tussen 2 en 8 zijn (maximaal aantal barcodes). Standaardwaarde: -1

**Returns:**
int - een aantal MaxiCode-barcodes in gestructureerde toevoegingsmodus.
### hashCode() {#hashCode--}
```
public final int hashCode()
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


Stelt ECI-codering in. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | ECI-codering. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Stelt een MaxiCode-coderingsmodus in. Standaardwaarde: Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | een MaxiCode-coderingsmodus. |

### setMode(MaxiCodeMode value) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public final void setMode(MaxiCodeMode value)
```


Stelt een MaxiCode-codermodus in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | een MaxiCode-coderingsmodus. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Stelt een MaxiCode barcode-id in in gestructureerde toevoegingsmodus. ID moet een waarde tussen 1 en 8 zijn. Standaardwaarde: 0

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | een MaxiCode barcode-id in gestructureerde toevoegingsmodus. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Stelt het aantal MaxiCode-barcodes in gestructureerde toevoegingsmodus in. Het aantal moet een waarde tussen 2 en 8 zijn (maximaal aantal barcodes). Standaardwaarde: -1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | een MaxiCode-barcodes aantal in gestructureerde toevoegingsmodus. |

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).

**Returns:**
java.lang.String - Een string die dit [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) vertegenwoordigt.
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

