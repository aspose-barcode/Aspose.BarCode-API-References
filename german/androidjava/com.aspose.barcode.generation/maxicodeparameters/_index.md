---
title: "MaxiCodeParameters"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "MaxiCode-Parameter."
type: docs
weight: 55
url: /de/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode-Parameter.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhe/Breite-Verhältnis des 2D-BarCode-Moduls. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Liest die ECI-Kodierung. |
| [getEncodeMode()](#getEncodeMode--) | Ermittelt einen MaxiCode-Kodierungsmodus. |
| [getMode()](#getMode--) | Ermittelt einen MaxiCode-Kodierungsmodus. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Ermittelt die MaxiCode-Barcode-ID im Structured-Append-Modus. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Ermittelt die MaxiCode-Barcodes-Anzahl im strukturierten Anfügemodus. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höhe/Breite-Verhältnis des 2D-BarCode-Moduls. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Setzt die ECI-Kodierung. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Setzt einen MaxiCode-Kodiermodus. |
| [setMode(MaxiCodeMode value)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | Setzt einen MaxiCode-Kodiermodus. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Legt eine MaxiCode Barcode-ID im strukturierten Anfügemodus fest. |
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


Liest die ECI-Kodierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Returns:**
int - ECI-Kodierung.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Liest einen MaxiCode-Kodiermodus. Standardwert: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public final MaxiCodeMode getMode()
```


Ermittelt einen MaxiCode-Kodierungsmodus.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - a MaxiCode encode mode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Liest eine MaxiCode Barcode-ID im strukturierten Anfügemodus aus. Die ID muss ein Wert zwischen 1 und 8 sein. Standardwert: 0

**Returns:**
int - eine MaxiCode-Barcode-ID im strukturierten Anfügemodus.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Liest die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus aus. Die Anzahl muss ein Wert zwischen 2 und 8 (maximale Barcode-Anzahl) sein. Standardwert: -1

**Returns:**
int - eine MaxiCode-Barcodes-Anzahl im strukturierten Anfügemodus.
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


Höhe/Breite-Verhältnis des 2D-BarCode-Moduls.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Setzt die ECI-Kodierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto steht. Standardwert: ISO-8859-1

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | ECI-Kodierung. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Setzt einen MaxiCode-Kodiermodus. Standardwert: Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | ein MaxiCode-Kodiermodus. |

### setMode(MaxiCodeMode value) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public final void setMode(MaxiCodeMode value)
```


Setzt einen MaxiCode-Kodiermodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | ein MaxiCode-Kodiermodus. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Legt eine MaxiCode Barcode-ID im strukturierten Anfügemodus fest. Die ID muss ein Wert zwischen 1 und 8 sein. Standardwert: 0

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | eine MaxiCode Barcode-ID im strukturierten Anfügemodus. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Legt die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus fest. Die Anzahl muss ein Wert zwischen 2 und 8 (maximale Barcode-Anzahl) sein. Standardwert: -1

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | eine MaxiCode-Barcodes-Anzahl im strukturierten Anfügemodus. |

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

