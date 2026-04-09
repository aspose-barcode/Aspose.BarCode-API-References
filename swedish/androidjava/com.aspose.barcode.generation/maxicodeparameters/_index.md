---
title: MaxiCodeParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: MaxiCode‑parametrar.
type: docs
weight: 57
url: /sv/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode‑parametrar.
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Hämtar ett MaxiCode-kodningsläge. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Hämtar ett MaxiCode-kodningsläge. |
| [getMaxiCodeMode()](#getMaxiCodeMode--) | Hämtar ett MaxiCode-kodningsläge. |
| [getMaxiCodeStructuredAppendModeBarcodeId()](#getMaxiCodeStructuredAppendModeBarcodeId--) | Hämtar ett MaxiCode streckkod-ID i strukturerat tilläggsläge. |
| [getMaxiCodeStructuredAppendModeBarcodesCount()](#getMaxiCodeStructuredAppendModeBarcodesCount--) | Hämtar antalet MaxiCode-streckkoder i strukturerat tilläggsläge. |
| [getMode()](#getMode--) | Hämtar ett MaxiCode-kodningsläge. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Hämtar ett MaxiCode streckkod-ID i strukturerat tilläggsläge. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Hämtar antalet MaxiCode-streckkoder i strukturerat tilläggsläge. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ställer in ECI‑kodning. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Ställer in ett MaxiCode‑kodningsläge. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Ställer in ett MaxiCode‑kodningsläge. |
| [setMaxiCodeMode(int value)](#setMaxiCodeMode-int-) | Ställer in ett MaxiCode‑kodningsläge. |
| [setMaxiCodeStructuredAppendModeBarcodeId(int value)](#setMaxiCodeStructuredAppendModeBarcodeId-int-) | Ställer in ett MaxiCode streckkod-ID i strukturerat tilläggsläge. |
| [setMaxiCodeStructuredAppendModeBarcodesCount(int value)](#setMaxiCodeStructuredAppendModeBarcodesCount-int-) | Ställer in antalet MaxiCode-streckkoder i strukturerat tilläggsläge. |
| [setMode(int value)](#setMode-int-) | Ställer in ett MaxiCode‑kodningsläge. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Ställer in ett MaxiCode streckkod-ID i strukturerat tilläggsläge. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Ställer in antalet MaxiCode-streckkoder i strukturerat tilläggsläge. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters). |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Hämtar ECI‑kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1

**Returns:**
int - ECI‑kodning.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Hämtar ett MaxiCode‑kodningsläge. Standardvärde: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Hämtar ett MaxiCode‑kodningsläge. Standardvärde: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeMode() {#getMaxiCodeMode--}
```
public final int getMaxiCodeMode()
```


Hämtar ett MaxiCode-kodningsläge.

**Returns:**
int - ett MaxiCode-kodningsläge.
### getMaxiCodeStructuredAppendModeBarcodeId() {#getMaxiCodeStructuredAppendModeBarcodeId--}
```
public final int getMaxiCodeStructuredAppendModeBarcodeId()
```


Hämtar ett MaxiCode streckkod-ID i strukturerat tilläggsläge. ID måste vara ett värde mellan 1 och 8. Standardvärde: 0

**Returns:**
int - ett MaxiCode streckkod-ID i strukturerat tilläggsläge.
### getMaxiCodeStructuredAppendModeBarcodesCount() {#getMaxiCodeStructuredAppendModeBarcodesCount--}
```
public final int getMaxiCodeStructuredAppendModeBarcodesCount()
```


Hämtar antalet MaxiCode-streckkoder i strukturerat tilläggsläge. Antalet måste vara ett värde mellan 2 och 8 (maximalt antal streckkoder). Standardvärde: -1

**Returns:**
int - ett MaxiCode-streckkodantal i strukturerat tilläggsläge.
### getMode() {#getMode--}
```
public final int getMode()
```


Hämtar ett MaxiCode-kodningsläge.

**Returns:**
int - ett MaxiCode-kodningsläge.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Hämtar ett MaxiCode streckkod-ID i strukturerat tilläggsläge. ID måste vara ett värde mellan 1 och 8. Standardvärde: 0

**Returns:**
int - ett MaxiCode streckkod-ID i strukturerat tilläggsläge.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Hämtar antalet MaxiCode-streckkoder i strukturerat tilläggsläge. Antalet måste vara ett värde mellan 2 och 8 (maximalt antal streckkoder). Standardvärde: -1

**Returns:**
int - ett MaxiCode-streckkodantal i strukturerat tilläggsläge.
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
public final void setAspectRatio(float value)
```


Höjd/bredd-förhållande för 2D BarCode-modulen.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Ställer in ECI‑kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | ECI‑kodning. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Ställer in ett MaxiCode‑kodningsläge. Standardvärde: Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | ett MaxiCode‑kodningsläge. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Ställer in ett MaxiCode‑kodningsläge. Standardvärde: Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | ett MaxiCode‑kodningsläge. |

### setMaxiCodeMode(int value) {#setMaxiCodeMode-int-}
```
public final void setMaxiCodeMode(int value)
```


Ställer in ett MaxiCode‑kodningsläge.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | ett MaxiCode‑kodningsläge. |

### setMaxiCodeStructuredAppendModeBarcodeId(int value) {#setMaxiCodeStructuredAppendModeBarcodeId-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodeId(int value)
```


Ställer in ett MaxiCode streckkod-ID i strukturerat tilläggsläge. ID måste vara ett värde mellan 1 och 8. Standardvärde: 0

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | ett MaxiCode streckkod-ID i strukturerat tilläggsläge. |

### setMaxiCodeStructuredAppendModeBarcodesCount(int value) {#setMaxiCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodesCount(int value)
```


Ställer in antalet MaxiCode-streckkoder i strukturerat tilläggsläge. Antalet måste vara ett värde mellan 2 och 8 (maximalt antal streckkoder). Standardvärde: -1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | Ett antal MaxiCode-streckkoder i strukturerat tilläggsläge. |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Ställer in ett MaxiCode‑kodningsläge.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | ett MaxiCode‑kodningsläge. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Ställer in ett MaxiCode streckkod-ID i strukturerat tilläggsläge. ID måste vara ett värde mellan 1 och 8. Standardvärde: 0

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | ett MaxiCode streckkod-ID i strukturerat tilläggsläge. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Ställer in antalet MaxiCode-streckkoder i strukturerat tilläggsläge. Antalet måste vara ett värde mellan 2 och 8 (maximalt antal streckkoder). Standardvärde: -1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int | Ett antal MaxiCode-streckkoder i strukturerat tilläggsläge. |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).

**Returns:**
java.lang.String - En sträng som representerar detta [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).
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

