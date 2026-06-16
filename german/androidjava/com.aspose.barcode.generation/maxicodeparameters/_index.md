---
title: MaxiCodeParameters
second_title: Aspose.BarCode für Android via Java API-Referenz
description: MaxiCode-Parameter.
type: docs
weight: 57
url: /de/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode-Parameter.
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhe/Breite-Verhältnis des 2D-Barcode-Moduls. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Gibt einen MaxiCode-Kodierungsmodus zurück. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Gibt einen MaxiCode-Kodierungsmodus zurück. |
| [getMaxiCodeMode()](#getMaxiCodeMode--) | Gibt einen MaxiCode-Kodierungsmodus zurück. |
| [getMaxiCodeStructuredAppendModeBarcodeId()](#getMaxiCodeStructuredAppendModeBarcodeId--) | Gibt eine MaxiCode-Barcode-ID im strukturierten Anfügemodus zurück. |
| [getMaxiCodeStructuredAppendModeBarcodesCount()](#getMaxiCodeStructuredAppendModeBarcodesCount--) | Gibt die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus zurück. |
| [getMode()](#getMode--) | Gibt einen MaxiCode-Kodierungsmodus zurück. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Gibt eine MaxiCode-Barcode-ID im strukturierten Anfügemodus zurück. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Gibt die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus zurück. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höhe/Breite-Verhältnis des 2D-Barcode-Moduls. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Setzt die ECI-Codierung. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Setzt einen MaxiCode-Codierungsmodus. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Setzt einen MaxiCode-Codierungsmodus. |
| [setMaxiCodeMode(int value)](#setMaxiCodeMode-int-) | Setzt einen MaxiCode-Codierungsmodus. |
| [setMaxiCodeStructuredAppendModeBarcodeId(int value)](#setMaxiCodeStructuredAppendModeBarcodeId-int-) | Legt eine MaxiCode-Barcode-ID im strukturierten Anfügemodus fest. |
| [setMaxiCodeStructuredAppendModeBarcodesCount(int value)](#setMaxiCodeStructuredAppendModeBarcodesCount-int-) | Legt die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus fest. |
| [setMode(int value)](#setMode-int-) | Setzt einen MaxiCode-Codierungsmodus. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Legt eine MaxiCode-Barcode-ID im strukturierten Anfügemodus fest. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Legt die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus fest. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) zurück. |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Liest die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Returns:**
int - ECI-Codierung.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Liest einen MaxiCode-Codierungsmodus. Standardwert: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Liest einen MaxiCode-Codierungsmodus. Standardwert: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeMode() {#getMaxiCodeMode--}
```
public final int getMaxiCodeMode()
```


Gibt einen MaxiCode-Kodierungsmodus zurück.

**Returns:**
int - ein MaxiCode-Kodierungsmodus.
### getMaxiCodeStructuredAppendModeBarcodeId() {#getMaxiCodeStructuredAppendModeBarcodeId--}
```
public final int getMaxiCodeStructuredAppendModeBarcodeId()
```


Liest eine MaxiCode-Barcode-ID im strukturierten Anfügemodus. Die ID muss ein Wert zwischen 1 und 8 sein. Standardwert: 0

**Returns:**
int - eine MaxiCode-Barcode-ID im strukturierten Anfügemodus.
### getMaxiCodeStructuredAppendModeBarcodesCount() {#getMaxiCodeStructuredAppendModeBarcodesCount--}
```
public final int getMaxiCodeStructuredAppendModeBarcodesCount()
```


Liest die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus. Die Zählzahl muss ein Wert zwischen 2 und 8 (maximale Barcode-Anzahl) sein. Standardwert: -1

**Returns:**
int - die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus.
### getMode() {#getMode--}
```
public final int getMode()
```


Gibt einen MaxiCode-Kodierungsmodus zurück.

**Returns:**
int - ein MaxiCode-Kodierungsmodus.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Liest eine MaxiCode-Barcode-ID im strukturierten Anfügemodus. Die ID muss ein Wert zwischen 1 und 8 sein. Standardwert: 0

**Returns:**
int - eine MaxiCode-Barcode-ID im strukturierten Anfügemodus.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Liest die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus. Die Zählzahl muss ein Wert zwischen 2 und 8 (maximale Barcode-Anzahl) sein. Standardwert: -1

**Returns:**
int - die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus.
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


Höhe/Breite-Verhältnis des 2D-Barcode-Moduls.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Setzt die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int | ECI-Codierung. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Setzt einen MaxiCode-Codierungsmodus. Standardwert: Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | ein MaxiCode-Codierungsmodus. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Setzt einen MaxiCode-Codierungsmodus. Standardwert: Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | ein MaxiCode-Codierungsmodus. |

### setMaxiCodeMode(int value) {#setMaxiCodeMode-int-}
```
public final void setMaxiCodeMode(int value)
```


Setzt einen MaxiCode-Codierungsmodus.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int | ein MaxiCode-Codierungsmodus. |

### setMaxiCodeStructuredAppendModeBarcodeId(int value) {#setMaxiCodeStructuredAppendModeBarcodeId-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodeId(int value)
```


Legt eine MaxiCode-Barcode-ID im strukturierten Anfügemodus fest. Die ID muss ein Wert zwischen 1 und 8 sein. Standardwert: 0

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int | eine MaxiCode-Barcode-ID im strukturierten Anfügemodus. |

### setMaxiCodeStructuredAppendModeBarcodesCount(int value) {#setMaxiCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodesCount(int value)
```


Legt die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus fest. Die Zählzahl muss ein Wert zwischen 2 und 8 (maximale Barcode-Anzahl) sein. Standardwert: -1

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int | eine MaxiCode-Barcode-Anzahl im strukturierten Append-Modus. |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Setzt einen MaxiCode-Codierungsmodus.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int | ein MaxiCode-Codierungsmodus. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Legt eine MaxiCode-Barcode-ID im strukturierten Anfügemodus fest. Die ID muss ein Wert zwischen 1 und 8 sein. Standardwert: 0

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int | eine MaxiCode-Barcode-ID im strukturierten Anfügemodus. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Legt die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus fest. Die Zählzahl muss ein Wert zwischen 2 und 8 (maximale Barcode-Anzahl) sein. Standardwert: -1

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int | eine MaxiCode-Barcode-Anzahl im strukturierten Append-Modus. |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) darstellt.
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

