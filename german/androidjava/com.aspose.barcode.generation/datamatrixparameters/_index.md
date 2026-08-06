---
title: DataMatrixParameters
second_title: Aspose.BarCode für Android via Java API-Referenz
description: DataMatrix-Parameter.
type: docs
weight: 34
url: /de/androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix-Parameter.
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhe/Breite-Verhältnis des 2D-Barcode-Moduls. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Spaltenanzahl. |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | Liefert einen Datamatrix ECC-Typ. |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixVersion()](#getDataMatrixVersion--) | Liefert die Symbolgröße eines Datamatrix. |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEccType()](#getEccType--) | Liefert einen Datamatrix ECC-Typ. |
| [getEncodeMode()](#getEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getMacroCharacters()](#getMacroCharacters--) | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. |
| [getRows()](#getRows--) | Zeilenanzahl. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Barcode-ID für den Structured-Append-Modus des Datamatrix-Barcodes. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Anzahl der Barcodes für den Structured-Append-Modus des Datamatrix-Barcodes. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Datei-ID für den Structured-Append-Modus des Datamatrix-Barcodes. |
| [getVersion()](#getVersion--) | Liefert die Symbolgröße eines Datamatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höhe/Breite-Verhältnis des 2D-Barcode-Moduls. |
| [setColumns(int value)](#setColumns-int-) | Spaltenanzahl. |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | Setzt einen Datamatrix ECC-Typ. |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Setzt die Symbolgröße eines Datamatrix. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Setzt die ECI-Codierung. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Setzt einen Datamatrix ECC-Typ. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [setRows(int value)](#setRows-int-) | Zeilenanzahl. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Barcode-ID für den Structured-Append-Modus des Datamatrix-Barcodes. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Anzahl der Barcodes für den Structured-Append-Modus des Datamatrix-Barcodes. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Datei-ID für den Structured-Append-Modus des Datamatrix-Barcodes. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Setzt die Symbolgröße eines Datamatrix. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) zurück. |
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


Spaltenanzahl.

**Returns:**
int
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public final DataMatrixEccType getDataMatrixEcc()
```


Liefert einen Datamatrix ECC-Typ. Standardwert: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public final DataMatrixEncodeMode getDataMatrixEncodeMode()
```


Kodiermodus des Datamatrix-Barcodes. Standardwert: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public final DataMatrixVersion getDataMatrixVersion()
```


Liefert die Symbolgröße eines Datamatrix. Standardwert: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Liefert die ECI-Codierung. Wird verwendet, wenn EncodeMode Auto ist. Standardwert: ISO-8859-1.

**Returns:**
int - ECI-Codierung.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Liefert einen Datamatrix ECC-Typ. Standardwert: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Kodiermodus des Datamatrix-Barcodes. Standardwert: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Die Werte der Makrozeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Codierung zu erhalten. Können nur mit DataMatrixEccType.Ecc200 oder DataMatrixEccType.EccAuto verwendet werden. Können nicht mit EncodeTypes.GS1DataMatrix verwendet werden. Standardwert: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getRows() {#getRows--}
```
public final int getRows()
```


Zeilenanzahl.

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Barcode-ID für den Structured-Append-Modus des Datamatrix-Barcodes. Standardwert: 0.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Anzahl der Barcodes für den Structured-Append-Modus des Datamatrix-Barcodes. Standardwert: 0.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Datei-ID für den Structured-Append-Modus des Datamatrix-Barcodes. Standardwert: 0.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Liefert die Symbolgröße eines Datamatrix. Standardwert: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. Standardwert: false.

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


Spaltenanzahl.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setDataMatrixEcc(DataMatrixEccType value)
```


Setzt einen Datamatrix ECC-Typ. Standardwert: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | ein Datamatrix ECC-Typ. |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


Kodiermodus des Datamatrix-Barcodes. Standardwert: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setDataMatrixVersion(DataMatrixVersion value)
```


Setzt die Symbolgröße eines Datamatrix. Standardwert: Version.Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | eine Datamatrix-Symbolgröße. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Setzt die ECI-Codierung. Wird verwendet, wenn EncodeMode Auto ist. Standardwert: ISO-8859-1.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int | ECI-Codierung. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Setzt einen Datamatrix ECC-Typ. Standardwert: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | ein Datamatrix ECC-Typ. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Kodiermodus des Datamatrix-Barcodes. Standardwert: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Die Werte der Makrozeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Codierung zu erhalten. Können nur mit DataMatrixEccType.Ecc200 oder DataMatrixEccType.EccAuto verwendet werden. Können nicht mit EncodeTypes.GS1DataMatrix verwendet werden. Standardwert: MacroCharacters.None.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. Standardwert: false.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Zeilenanzahl.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Barcode-ID für den Structured-Append-Modus des Datamatrix-Barcodes. Standardwert: 0.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Anzahl der Barcodes für den Structured-Append-Modus des Datamatrix-Barcodes. Standardwert: 0.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Datei-ID für den Structured-Append-Modus des Datamatrix-Barcodes. Standardwert: 0.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Setzt die Symbolgröße eines Datamatrix. Standardwert: Version.Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | eine Datamatrix-Symbolgröße. |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters) repräsentiert.
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

