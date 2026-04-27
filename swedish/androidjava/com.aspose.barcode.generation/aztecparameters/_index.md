---
title: AztecParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: Aztec-parametrar.
type: docs
weight: 12
url: /sv/androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Aztec-parametrar.
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [getAztecEncodeMode()](#getAztecEncodeMode--) | Hämtar ett Aztec‑kodningsläge. |
| [getAztecErrorLevel()](#getAztecErrorLevel--) | Nivå för felkorrigering av Aztec-typer av streckkod. |
| [getAztecSymbolMode()](#getAztecSymbolMode--) | Hämtar ett Aztec‑symbolläge. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Hämtar ett Aztec‑kodningsläge. |
| [getErrorLevel()](#getErrorLevel--) | Nivå för felkorrigering av Aztec-typer av streckkod. |
| [getLayersCount()](#getLayersCount--) | Hämtar lagerantalet för Aztec‑symbolen. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Streckkod-ID för Structured Append-läge för Aztec-streckkod. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Antal streckkoder för Structured Append-läge för Aztec-streckkod. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Fil-ID för Structured Append-läge för Aztec-streckkod (valfritt fält). |
| [getSymbolMode()](#getSymbolMode--) | Hämtar ett Aztec‑symbolläge. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [setAztecEncodeMode(AztecEncodeMode value)](#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Ställer in ett Aztec-kodningsläge. |
| [setAztecErrorLevel(int value)](#setAztecErrorLevel-int-) | Nivå för felkorrigering av Aztec-typer av streckkod. |
| [setAztecSymbolMode(AztecSymbolMode value)](#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Ställer in ett Aztec-symbolläge. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ställer in ECI‑kodning. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Ställer in ett Aztec-kodningsläge. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Nivå för felkorrigering av Aztec-typer av streckkod. |
| [setLayersCount(int value)](#setLayersCount-int-) | Ställer in lagerantalet för Aztec-symbolen. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Streckkod-ID för Structured Append-läge för Aztec-streckkod. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Antal streckkoder för Structured Append-läge för Aztec-streckkod. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Fil-ID för Structured Append-läge för Aztec-streckkod (valfritt fält). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Ställer in ett Aztec-symbolläge. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [AztecParameters](../../com.aspose.barcode.generation/aztecparameters). |
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
### getAztecEncodeMode() {#getAztecEncodeMode--}
```
public final AztecEncodeMode getAztecEncodeMode()
```


Hämtar ett Aztec-kodningsläge. Standardvärde: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode – ett Aztec-kodningsläge.
### getAztecErrorLevel() {#getAztecErrorLevel--}
```
public final int getAztecErrorLevel()
```


Nivå för felkorrigering för Aztec-typer av streckkod. Värdet bör vara mellan 5 och 95.

**Returns:**
int
### getAztecSymbolMode() {#getAztecSymbolMode--}
```
public final AztecSymbolMode getAztecSymbolMode()
```


Hämtar ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto.

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


Hämtar ECI-kodning. Används när AztecEncodeMode är Auto. Standardvärde: ISO-8859-1

**Returns:**
int - ECI‑kodning.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Hämtar ett Aztec-kodningsläge. Standardvärde: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode – ett Aztec-kodningsläge.
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Nivå för felkorrigering för Aztec-typer av streckkod. Värdet bör vara mellan 5 och 95.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Hämtar lagerantalet för Aztec-symbolen. Lagerantalet bör ligga i intervallet 1 till 3 för Compact-läge och 1 till 32 för Full Range-läge. Standardvärde: 0 (auto).

**Returns:**
int – lagerantalet för Aztec-symbolen.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Streckkod-ID för Structured Append-läge för Aztec-streckkod. Streckkod-ID bör ligga i intervallet 1 till antalet streckkoder. Standardvärde: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Antal streckkoder för Structured Append-läge för Aztec-streckkod. Antalet streckkoder bör ligga i intervallet 1 till 26. Standardvärde: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Fil-ID för Structured Append-läge för Aztec-streckkod (valfritt fält). Fil-ID får inte innehålla mellanslag. Standardvärde: tom sträng

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Hämtar ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto.

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


Höjd/bredd-förhållande för 2D BarCode-modulen.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setAztecEncodeMode(AztecEncodeMode value) {#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setAztecEncodeMode(AztecEncodeMode value)
```


Ställer in ett Aztec-kodningsläge. Standardvärde: Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.barcode.generation.AztecEncodeMode | ett Aztec-kodningsläge. |

### setAztecErrorLevel(int value) {#setAztecErrorLevel-int-}
```
public final void setAztecErrorLevel(int value)
```


Nivå för felkorrigering för Aztec-typer av streckkod. Värdet bör vara mellan 5 och 95.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setAztecSymbolMode(AztecSymbolMode value) {#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setAztecSymbolMode(AztecSymbolMode value)
```


Ställer in ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | ett Aztec-symbolläge. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Ställer in ECI-kodning. Används när AztecEncodeMode är Auto. Standardvärde: ISO-8859-1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | ECI‑kodning. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Ställer in ett Aztec-kodningsläge. Standardvärde: Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.barcode.generation.AztecEncodeMode | ett Aztec-kodningsläge. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Nivå för felkorrigering för Aztec-typer av streckkod. Värdet bör vara mellan 5 och 95.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Ställer in lagerantalet för Aztec-symbolen. Lagerantalet bör ligga i intervallet 1 till 3 för Compact-läge och 1 till 32 för Full Range-läge. Standardvärde: 0 (auto).

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | lagerantalet för Aztec-symbolen. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Streckkod-ID för Structured Append-läge för Aztec-streckkod. Streckkod-ID bör ligga i intervallet 1 till antalet streckkoder. Standardvärde: 0

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Antal streckkoder för Structured Append-läge för Aztec-streckkod. Antalet streckkoder bör ligga i intervallet 1 till 26. Standardvärde: 0

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Fil-ID för Structured Append-läge för Aztec-streckkod (valfritt fält). Fil-ID får inte innehålla mellanslag. Standardvärde: tom sträng

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Ställer in ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | ett Aztec-symbolläge. |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String - En sträng som representerar detta [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).
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

