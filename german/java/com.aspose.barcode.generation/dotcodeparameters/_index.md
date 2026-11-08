---
title: "DotCodeParameters"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "DotCode-Parameter."
type: docs
weight: 34
url: /de/java/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode-Parameter.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhen-/Breitenverhältnis des 2D-BarCode-Moduls. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Identifiziert die Spaltenanzahl. |
| [getECIEncoding()](#getECIEncoding--) | Identifiziert die ECI‑Kodierung. |
| [getEncodeMode()](#getEncodeMode--) | Identifiziert den DotCode‑Kodierungsmodus. |
| [getRows()](#getRows--) | Identifiziert die Zeilenanzahl. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Identifiziert die Anzahl der DotCode‑Structured‑Append‑Modus‑Barcodes. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Gibt an, ob der Code verwendet wird, um dem Leser zu instruieren, die folgenden Daten als Anweisungen zur Initialisierung oder Neu‑programmierung des Barcodelesers zu interpretieren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höhen-/Breitenverhältnis des 2D-BarCode-Moduls. |
| [setColumns(int value)](#setColumns-int-) | Identifiziert die Spaltenanzahl. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifiziert die ECI‑Kodierung. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifiziert den DotCode‑Kodierungsmodus. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Gibt an, ob der Code verwendet wird, um dem Leser zu instruieren, die folgenden Daten als Anweisungen zur Initialisierung oder Neu‑programmierung des Barcodelesers zu interpretieren. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolesch
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Höhen-/Breitenverhältnis des 2D-BarCode-Moduls.

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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Identifiziert die ECI‑Kodierung. Wird verwendet, wenn DotCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1

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


Identifiziert die Anzahl der DotCode‑Structured‑Append‑Modus‑Barcodes. Standardwert ist -1. Die Anzahl muss ein Wert zwischen 1 und 35 sein.

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


Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neukonfiguration des Barcodelesers zu interpretieren. Standardwert ist false.

**Returns:**
boolesch
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


Höhen-/Breitenverhältnis des 2D-BarCode-Moduls.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Identifiziert die Spaltenanzahl. Die Summe aus der Anzahl der Zeilen und der Anzahl der Spalten eines DotCode‑Symbols muss ungerade sein. Die Spaltenanzahl muss mindestens 5 betragen. Standardwert: -1

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Identifiziert die ECI‑Kodierung. Wird verwendet, wenn DotCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


Identifiziert den DotCode‑Kodierungsmodus. Standardwert: Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neukonfiguration des Barcodelesers zu interpretieren. Standardwert ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Identifiziert die Zeilenanzahl. Die Summe aus der Anzahl der Zeilen und der Anzahl der Spalten eines DotCode‑Symbols muss ungerade sein. Die Zeilenanzahl muss mindestens 5 betragen. Standardwert: -1

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Standardwert ist -1.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Identifiziert die Anzahl der DotCode‑Structured‑Append‑Modus‑Barcodes. Standardwert ist -1. Die Anzahl muss ein Wert zwischen 1 und 35 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

