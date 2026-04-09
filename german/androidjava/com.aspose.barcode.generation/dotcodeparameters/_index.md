---
title: DotCodeParameters
second_title: Aspose.BarCode für Android via Java API-Referenz
description: DotCode-Parameter.
type: docs
weight: 36
url: /de/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode-Parameter.
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhe/Breite-Verhältnis des 2D-Barcode-Moduls. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Identifiziert die Spaltenanzahl. |
| [getDotCodeEncodeMode()](#getDotCodeEncodeMode--) | Identifiziert den DotCode‑Kodiermodus. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Identifiziert die Anzahl der DotCode‑Structured‑Append‑Modus‑Barcodes. |
| [getECIEncoding()](#getECIEncoding--) | Identifiziert die ECI‑Kodierung. |
| [getEncodeMode()](#getEncodeMode--) | Identifiziert den DotCode‑Kodiermodus. |
| [getRows()](#getRows--) | Identifiziert die Zeilenanzahl. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Identifiziert die Anzahl der DotCode‑Structured‑Append‑Modus‑Barcodes. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neukonfiguration des Barcode-Lesers zu interpretieren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höhe/Breite-Verhältnis des 2D-Barcode-Moduls. |
| [setColumns(int value)](#setColumns-int-) | Identifiziert die Spaltenanzahl. |
| [setDotCodeEncodeMode(DotCodeEncodeMode value)](#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifiziert den DotCode‑Kodiermodus. |
| [setDotCodeStructuredAppendModeBarcodeId(int value)](#setDotCodeStructuredAppendModeBarcodeId-int-) | Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. |
| [setDotCodeStructuredAppendModeBarcodesCount(int value)](#setDotCodeStructuredAppendModeBarcodesCount-int-) | Identifiziert die Anzahl der DotCode‑Structured‑Append‑Modus‑Barcodes. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifiziert die ECI‑Kodierung. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifiziert den DotCode‑Kodiermodus. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neukonfiguration des Barcode-Lesers zu interpretieren. |
| [setRows(int value)](#setRows-int-) | Identifiziert die Zeilenanzahl. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Identifiziert die Anzahl der DotCode‑Structured‑Append‑Modus‑Barcodes. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Höhe/Breite-Verhältnis des 2D-Barcode-Moduls.

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


Identifiziert die Spaltenanzahl. Die Summe aus der Anzahl der Zeilen und der Anzahl der Spalten eines DotCode‑Symbols muss ungerade sein. Die Spaltenanzahl muss mindestens 5 betragen. Standardwert: -1

**Returns:**
int
### getDotCodeEncodeMode() {#getDotCodeEncodeMode--}
```
public final DotCodeEncodeMode getDotCodeEncodeMode()
```


Identifiziert den DotCode‑Kodierungsmodus. Standardwert: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Standardwert ist -1.

**Returns:**
int
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


Identifiziert die Anzahl der Barcodes im DotCode‑Structured‑Append‑Modus. Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identifiziert die ECI‑Kodierung. Wird verwendet, wenn DotCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


Identifiziert den DotCode‑Kodierungsmodus. Standardwert: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Identifiziert die Zeilenanzahl. Die Summe aus der Anzahl der Zeilen und der Anzahl der Spalten eines DotCode‑Symbols muss ungerade sein. Die Zeilenanzahl muss mindestens 5 betragen. Standardwert: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Standardwert ist -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Identifiziert die Anzahl der Barcodes im DotCode‑Structured‑Append‑Modus. Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein.

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


Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neukonfiguration des Barcode-Lesers zu interpretieren. Standardwert ist false.

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


Höhe/Breite-Verhältnis des 2D-Barcode-Moduls.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Identifiziert die Spaltenanzahl. Die Summe aus der Anzahl der Zeilen und der Anzahl der Spalten eines DotCode‑Symbols muss ungerade sein. Die Spaltenanzahl muss mindestens 5 betragen. Standardwert: -1

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDotCodeEncodeMode(DotCodeEncodeMode value) {#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setDotCodeEncodeMode(DotCodeEncodeMode value)
```


Identifiziert den DotCode‑Kodierungsmodus. Standardwert: Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setDotCodeStructuredAppendModeBarcodeId(int value) {#setDotCodeStructuredAppendModeBarcodeId-int-}
```
public final void setDotCodeStructuredAppendModeBarcodeId(int value)
```


Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Standardwert ist -1.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDotCodeStructuredAppendModeBarcodesCount(int value) {#setDotCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setDotCodeStructuredAppendModeBarcodesCount(int value)
```


Identifiziert die Anzahl der Barcodes im DotCode‑Structured‑Append‑Modus. Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identifiziert die ECI‑Kodierung. Wird verwendet, wenn DotCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


Identifiziert den DotCode‑Kodierungsmodus. Standardwert: Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neukonfiguration des Barcode-Lesers zu interpretieren. Standardwert ist false.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Identifiziert die Zeilenanzahl. Die Summe aus der Anzahl der Zeilen und der Anzahl der Spalten eines DotCode‑Symbols muss ungerade sein. Die Zeilenanzahl muss mindestens 5 betragen. Standardwert: -1

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Standardwert ist -1.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Identifiziert die Anzahl der Barcodes im DotCode‑Structured‑Append‑Modus. Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) zurück.

**Returns:**
java.lang.String – Eine Zeichenkette, die dieses [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) repräsentiert.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

