---
title: DotCodeParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: DotCode-parametrar.
type: docs
weight: 36
url: /sv/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode-parametrar.
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Identifies columns count. |
| [getDotCodeEncodeMode()](#getDotCodeEncodeMode--) | Identifies DotCode encode mode. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [getECIEncoding()](#getECIEncoding--) | Identifies ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Identifies DotCode encode mode. |
| [getRows()](#getRows--) | Identifies rows count. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [setColumns(int value)](#setColumns-int-) | Identifies columns count. |
| [setDotCodeEncodeMode(DotCodeEncodeMode value)](#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setDotCodeStructuredAppendModeBarcodeId(int value)](#setDotCodeStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setDotCodeStructuredAppendModeBarcodesCount(int value)](#setDotCodeStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifies ECI encoding. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. |
| [setRows(int value)](#setRows-int-) | Identifies rows count. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [toString()](#toString--) | Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters). |
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


Identifierar kolumnantal. Summan av antalet rader plus antalet kolumner i en DotCode-symbol måste vara udda. Antalet kolumner måste vara minst 5. Standardvärde: -1

**Returns:**
int
### getDotCodeEncodeMode() {#getDotCodeEncodeMode--}
```
public final DotCodeEncodeMode getDotCodeEncodeMode()
```


Identifierar DotCode-kodningsläge. Standardvärde: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


Identifierar ID för DotCode strukturerade tilläggsläge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärde är -1.

**Returns:**
int
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


Identifierar antalet streckkoder för DotCode strukturerade tilläggsläge. Standardvärde är -1. Antalet måste vara ett värde mellan 1 och 35.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identifierar ECI-kodning. Används när DotCodeEncodeMode är Auto. Standardvärde: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


Identifierar DotCode-kodningsläge. Standardvärde: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Identifierar radantal. Summan av antalet rader plus antalet kolumner i en DotCode-symbol måste vara udda. Antalet rader måste vara minst 5. Standardvärde: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Identifierar ID för DotCode strukturerade tilläggsläge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärde är -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Identifierar antalet streckkoder för DotCode strukturerade tilläggsläge. Standardvärde är -1. Antalet måste vara ett värde mellan 1 och 35.

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


Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är false.

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


Identifierar kolumnantal. Summan av antalet rader plus antalet kolumner i en DotCode-symbol måste vara udda. Antalet kolumner måste vara minst 5. Standardvärde: -1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDotCodeEncodeMode(DotCodeEncodeMode value) {#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setDotCodeEncodeMode(DotCodeEncodeMode value)
```


Identifierar DotCode-kodningsläge. Standardvärde: Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setDotCodeStructuredAppendModeBarcodeId(int value) {#setDotCodeStructuredAppendModeBarcodeId-int-}
```
public final void setDotCodeStructuredAppendModeBarcodeId(int value)
```


Identifierar ID för DotCode strukturerade tilläggsläge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärde är -1.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setDotCodeStructuredAppendModeBarcodesCount(int value) {#setDotCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setDotCodeStructuredAppendModeBarcodesCount(int value)
```


Identifierar antalet streckkoder för DotCode strukturerade tilläggsläge. Standardvärde är -1. Antalet måste vara ett värde mellan 1 och 35.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identifierar ECI-kodning. Används när DotCodeEncodeMode är Auto. Standardvärde: ISO-8859-1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


Identifierar DotCode-kodningsläge. Standardvärde: Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är false.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Identifierar radantal. Summan av antalet rader plus antalet kolumner i en DotCode-symbol måste vara udda. Antalet rader måste vara minst 5. Standardvärde: -1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Identifierar ID för DotCode strukturerade tilläggsläge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärde är -1.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Identifierar antalet streckkoder för DotCode strukturerade tilläggsläge. Standardvärde är -1. Antalet måste vara ett värde mellan 1 och 35.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).

**Returns:**
java.lang.String - En sträng som representerar detta [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).
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

