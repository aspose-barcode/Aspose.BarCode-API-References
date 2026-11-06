---
title: "AztecParameters"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Aztec-Parameter."
type: docs
weight: 12
url: /de/androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Aztec-Parameter.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhe/Breite-Verhältnis des 2D-BarCode-Moduls. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Liest die ECI-Kodierung. |
| [getEncodeMode()](#getEncodeMode--) | Liefert einen Aztec-Codiermodus. |
| [getErrorLevel()](#getErrorLevel--) | Fehlerkorrekturstufe der Aztec-Barcode-Typen. |
| [getLayersCount()](#getLayersCount--) | Liefert die Ebenenzahl des Aztec-Symbols. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Barcode-ID für den Structured Append-Modus des Aztec-Barcodes. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Anzahl der Barcodes für den Structured Append-Modus des Aztec-Barcodes. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Datei-ID für den Structured Append-Modus des Aztec-Barcodes (optional Feld). |
| [getSymbolMode()](#getSymbolMode--) | Ruft den Aztec Symbol-Modus ab. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höhe/Breite-Verhältnis des 2D-BarCode-Moduls. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Setzt die ECI-Kodierung. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Setzt den Aztec-Codierungsmodus. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Fehlerkorrekturstufe der Aztec-Barcode-Typen. |
| [setLayersCount(int value)](#setLayersCount-int-) | Setzt die Ebenenzahl des Aztec-Symbols. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Barcode-ID für den Structured Append-Modus des Aztec-Barcodes. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Anzahl der Barcodes für den Structured Append-Modus des Aztec-Barcodes. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Datei-ID für den Structured Append-Modus des Aztec-Barcodes (optional Feld). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Setzt den Aztec Symbol-Modus. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) zurück. |
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
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Höhe/Breite-Verhältnis des 2D-BarCode-Moduls.

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


Liest die ECI-Codierung. Wird verwendet, wenn AztecEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Returns:**
int - ECI-Kodierung.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Liest den Aztec-Codierungsmodus. Standardwert: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - ein Aztec-Codierungsmodus.
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Fehlerkorrekturstufe der Aztec-Barcode-Typen. Der Wert sollte zwischen 5 und 95 liegen.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Liest die Ebenenzahl des Aztec-Symbols. Die Ebenenzahl sollte im Bereich von 1 bis 3 für den kompakten Modus und im Bereich von 1 bis 32 für den Vollbereichsmodus liegen. Standardwert: 0 (auto).

**Returns:**
int - Ebenenzahl des Aztec-Symbols.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Barcode-ID für den Structured Append-Modus des Aztec-Barcodes. Die Barcode-ID sollte im Bereich von 1 bis zur Anzahl der Barcodes liegen. Standardwert: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Anzahl der Barcodes für den Structured Append-Modus des Aztec-Barcodes. Die Barcode-Anzahl sollte im Bereich von 1 bis 26 liegen. Standardwert: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Datei-ID für den Structured Append-Modus des Aztec-Barcodes (optional). Die Datei-ID darf keine Leerzeichen enthalten. Standardwert: leerer String

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Liest den Aztec Symbol-Modus. Standardwert: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
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


Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren.

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


Höhe/Breite-Verhältnis des 2D-BarCode-Moduls.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Setzt die ECI-Codierung. Wird verwendet, wenn AztecEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | ECI-Kodierung. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Setzt den Aztec-Codierungsmodus. Standardwert: Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.barcode.generation.AztecEncodeMode | ein Aztec-Codierungsmodus. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Fehlerkorrekturstufe der Aztec-Barcode-Typen. Der Wert sollte zwischen 5 und 95 liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Setzt die Ebenenzahl des Aztec-Symbols. Die Ebenenzahl sollte im Bereich von 1 bis 3 für den kompakten Modus und im Bereich von 1 bis 32 für den Vollbereichsmodus liegen. Standardwert: 0 (auto).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Ebenenzahl des Aztec-Symbols. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Barcode-ID für den Structured Append-Modus des Aztec-Barcodes. Die Barcode-ID sollte im Bereich von 1 bis zur Anzahl der Barcodes liegen. Standardwert: 0

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Anzahl der Barcodes für den Structured Append-Modus des Aztec-Barcodes. Die Barcode-Anzahl sollte im Bereich von 1 bis 26 liegen. Standardwert: 0

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Datei-ID für den Structured Append-Modus des Aztec-Barcodes (optional). Die Datei-ID darf keine Leerzeichen enthalten. Standardwert: leerer String

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Setzt den Aztec Symbol-Modus. Standardwert: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | ein Aztec Symbol-Modus. |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

