---
title: "Pdf417ParametersUI"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "UI-Wrapper für die Klasse com.aspose.barcode.generation.Pdf417Parameters."
type: docs
weight: 16
url: /de/java/com.aspose.barcode.barcodecontrol/pdf417parametersui/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417ParametersUI
```

UI-Wrapper für die Klasse com.aspose.barcode.generation.Pdf417Parameters.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhen-/Breitenverhältnis des 2D-BarCode-Moduls. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Spaltenanzahl. |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getEncodeMode()](#getEncodeMode--) | Pdf417‑Symbologie‑Typ des BarCode‑Encode‑Modus. |
| [getErrorLevel()](#getErrorLevel--) | Liefert den Pdf417‑Symbologie‑Typ des BarCode‑Fehlerkorrektur‑Levels, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| [getMacroCharacters()](#getMacroCharacters--) | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Codierung zu erhalten. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417‑Barcode‑Empfängername (optional). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417‑Barcode‑Prüfsumme (optional). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Liefert die Datei‑ID des Macro‑Pdf417‑Barcodes. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417‑Barcode‑Dateiname (optional). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417‑Dateigröße (optional). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Liefert die Segment‑ID des Macro‑Pdf417‑Barcodes, die von 0 bis MacroSegmentsCount - 1 reicht. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Liefert die Anzahl der Segmente des Macro‑Pdf417‑Barcodes. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417‑Barcode‑Absendername (optional). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Wird verwendet, um dem Encoder mitzuteilen, ob dem Segment ein Macro‑PDF417‑Terminator (Codewort 922) hinzugefügt werden soll. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417‑Barcode‑Zeitstempel (optional). |
| [getRows()](#getRows--) | Zeilenanzahl. |
| [getTruncate()](#getTruncate--) | Gibt an, ob der Pdf417‑Symbologie‑Typ des BarCode gekürzt ist (zur Platzersparnis). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position in den Modi 908 und 909 kodieren, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann. |
| [isLinked()](#isLinked--) | Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417- und Pdf417‑Barcodes. Mit der GS1MicroPdf417‑Symbologie werden die Modi 906, 907, 912, 913, 914, 915 „Linked“ UCC/EAN‑128‑Modi kodiert. Mit den Symbologien MicroPdf417 und Pdf417 wird das Verknüpfungs‑Flag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert. |
| [isReaderInitialization()](#isReaderInitialization--) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höhen-/Breitenverhältnis des 2D-BarCode-Moduls. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position in den Modi 908 und 909 kodieren, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann. |
| [setColumns(int value)](#setColumns-int-) | Spaltenanzahl. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Bezeichner. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Pdf417‑Symbologie‑Typ des BarCode‑Encode‑Modus. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Setzt den Pdf417‑Symbologie‑Typ des BarCode‑Fehlerkorrektur‑Levels, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| [setLinked(boolean value)](#setLinked-boolean-) | Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417- und Pdf417‑Barcodes. Mit der GS1MicroPdf417‑Symbologie werden die Modi 906, 907, 912, 913, 914, 915 „Linked“ UCC/EAN‑128‑Modi kodiert. Mit den Symbologien MicroPdf417 und Pdf417 wird das Verknüpfungs‑Flag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Codierung zu erhalten. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417‑Barcode‑Empfängername (optional). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417‑Barcode‑Prüfsumme (optional). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Extended Channel Interpretation Bezeichner. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Setzt die Datei‑ID des Macro‑Pdf417‑Barcodes. |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417‑Barcode‑Dateiname (optional). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417‑Dateigröße (optional). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Setzt die Segment‑ID des Macro‑Pdf417‑Barcodes, die von 0 bis MacroSegmentsCount - 1 reicht. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Setzt die Anzahl der Segmente des Macro‑Pdf417‑Barcodes. |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417‑Barcode‑Absendername (optional). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Wird verwendet, um dem Encoder mitzuteilen, ob dem Segment ein Macro‑PDF417‑Terminator (Codewort 922) hinzugefügt werden soll. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417‑Barcode‑Zeitstempel (optional). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [setRows(int value)](#setRows-int-) | Zeilenanzahl. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Gibt an, ob der Pdf417‑Symbologie‑Typ des BarCode gekürzt ist (zur Platzersparnis). |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenketten‑Darstellung dieses [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) zurück. |
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


Spaltenanzahl.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro‑PDF417‑Textfelder. Die aktuelle Implementierung umfasst alle bekannten Zeichensatz‑Kodierungen.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Pdf417‑Symbologie‑Typ des BarCode‑Encode‑Modus. Standardwert: Pdf417EncodeMode.Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Liefert den Pdf417‑Symbologie‑Typ des BarCode‑Fehlerkorrektur‑Levels, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet beste Fehlerkorrektur, was ein größeres Bild bedeutet.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in Sondermodi eine kompaktere Kodierung zu erreichen. Kann nur mit MicroPdf417 verwendet werden und kodiert die MicroPdf417‑Modi 916 und 917. Standardwert: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417‑Barcode‑Empfängername (optional). MicroPDF417‑Barcode‑Empfängername (optional für den Structured‑Append‑Modus).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417‑Barcode‑Prüfsumme (optional). MicroPDF417‑Barcode‑Prüfsumme (optional für den Structured‑Append‑Modus). Das Prüfsummenfeld enthält den Wert der 16‑Bit‑(2‑Byte‑)CRC‑Prüfsumme, die mit dem CCITT‑16‑Polynom berechnet wird: x^16 + x^12 + x^5 + 1.

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Erweiterte Kanalinterpretationskennungen. Gilt für Macro PDF417 Textfelder.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


Liest die Datei-ID des Makro‑Pdf417‑Barcodes. Wird für MacroPdf417 verwendet.

**Returns:**
int – macro Pdf417 Barcode‑Datei‑ID.
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 Barcode-Dateiname (optional). MicroPDF417 Barcode-Dateiname (optional für den Structured‑Append‑Modus)

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 Dateigröße (optional). MicroPDF417 Dateigröße (optional für den Structured‑Append‑Modus) Das Feld Dateigröße enthält die Größe in Bytes der gesamten Quelldatei.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


Liefert die Segment‑ID des Macro‑Pdf417‑Barcodes, die von 0 bis MacroSegmentsCount - 1 reicht.

**Returns:**
int – macro Pdf417 Barcode‑Segment‑ID, beginnend bei 0 bis MacroSegmentsCount - 1.
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Liefert die Anzahl der Segmente des Macro‑Pdf417‑Barcodes.

**Returns:**
int – macro Pdf417 Barcode‑Segmentanzahl.
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 Barcode‑Absendername (optional). MicroPDF417 Barcode‑Absendername (optional für den Structured‑Append‑Modus)

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Wird verwendet, um dem Encoder mitzuteilen, ob der Macro PDF417 Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Nur für Macro PDF417 anwendbar.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 Barcode‑Zeitstempel (optional). MicroPDF417 Barcode‑Zeitstempel (optional für den Structured‑Append‑Modus)

**Returns:**
java.time.LocalDateTime
### getRows() {#getRows--}
```
public final int getRows()
```


Zeilenanzahl.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Gibt an, ob der Pdf417‑Symbologie‑Typ des BarCode gekürzt ist (zur Platzersparnis).

**Returns:**
boolesch
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position in den Modi 908 und 909 kodieren, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann.

**Returns:**
boolesch
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417- und Pdf417‑Barcodes. Mit der GS1MicroPdf417‑Symbologie werden die Modi 906, 907, 912, 913, 914, 915 „Linked“ UCC/EAN‑128‑Modi kodiert. Mit den Symbologien MicroPdf417 und Pdf417 wird das Verknüpfungs‑Flag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert.

**Returns:**
boolesch
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren.

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

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position in den Modi 908 und 909 kodieren, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Spaltenanzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro‑PDF417‑Textfelder. Die aktuelle Implementierung umfasst alle bekannten Zeichensatz‑Kodierungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Pdf417‑Symbologie‑Typ des BarCode‑Encode‑Modus. Standardwert: Pdf417EncodeMode.Auto.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Setzt den Pdf417‑Symbologie‑Typ des BarCode‑Fehlerkorrektur‑Levels, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet beste Fehlerkorrektur, was ein größeres Bild bedeutet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417‑Symboltyp des BarCode‑Fehlerkorrekturlevels, von level0 bis level8, wobei level0 keine Fehlerkorrekturinformationen bedeutet und level8 die beste Fehlerkorrektur bietet, was ein größeres Bild ergibt. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417- und Pdf417‑Barcodes. Mit der GS1MicroPdf417‑Symbologie werden die Modi 906, 907, 912, 913, 914, 915 „Linked“ UCC/EAN‑128‑Modi kodiert. Mit den Symbologien MicroPdf417 und Pdf417 wird das Verknüpfungs‑Flag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in Sondermodi eine kompaktere Kodierung zu erreichen. Kann nur mit MicroPdf417 verwendet werden und kodiert die MicroPdf417‑Modi 916 und 917. Standardwert: MacroCharacters.None.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417‑Barcode‑Empfängername (optional). MicroPDF417‑Barcode‑Empfängername (optional für den Structured‑Append‑Modus).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417‑Barcode‑Prüfsumme (optional). MicroPDF417‑Barcode‑Prüfsumme (optional für den Structured‑Append‑Modus). Das Prüfsummenfeld enthält den Wert der 16‑Bit‑(2‑Byte‑)CRC‑Prüfsumme, die mit dem CCITT‑16‑Polynom berechnet wird: x^16 + x^12 + x^5 + 1.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Erweiterte Kanalinterpretationskennungen. Gilt für Macro PDF417 Textfelder.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


Setzt die Datei-ID des macro Pdf417 Barcodes. Wird für MacroPdf417 verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | macro Pdf417 Barcode‑Datei‑ID. |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 Barcode-Dateiname (optional). MicroPDF417 Barcode-Dateiname (optional für den Structured‑Append‑Modus)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 Dateigröße (optional). MicroPDF417 Dateigröße (optional für den Structured‑Append‑Modus) Das Feld Dateigröße enthält die Größe in Bytes der gesamten Quelldatei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


Setzt die Segment‑ID des Macro‑Pdf417‑Barcodes, die von 0 bis MacroSegmentsCount - 1 reicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | macro Pdf417 Barcode‑Segment‑ID, beginnend bei 0 bis MacroSegmentsCount - 1. |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Setzt die Anzahl der Segmente des Macro‑Pdf417‑Barcodes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | macro Pdf417 Barcode‑Segmentanzahl. |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 Barcode‑Absendername (optional). MicroPDF417 Barcode‑Absendername (optional für den Structured‑Append‑Modus)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Wird verwendet, um dem Encoder mitzuteilen, ob der Macro PDF417 Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Nur für Macro PDF417 anwendbar.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 Barcode‑Zeitstempel (optional). MicroPDF417 Barcode‑Zeitstempel (optional für den Structured‑Append‑Modus)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Zeilenanzahl.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Gibt an, ob der Pdf417‑Symbologie‑Typ des BarCode gekürzt ist (zur Platzersparnis).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenketten‑Darstellung dieses [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) zurück.

**Returns:**
java.lang.String – Eine Zeichenkette, die dieses [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) repräsentiert.
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

