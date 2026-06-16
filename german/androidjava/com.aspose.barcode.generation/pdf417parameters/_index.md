---
title: Pdf417Parameters
second_title: Aspose.BarCode für Android via Java API-Referenz
description: PDF417-Parameter.
type: docs
weight: 60
url: /de/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417‑Parameter. Enthält Parameter für PDF417, MacroPDF417, MicroPDF417 und GS1MicroPdf417. MacroPDF417 erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. MicroPDF417 im Structured‑Append‑Modus (gleichbedeutend mit dem MacroPDF417‑Modus) erfordert ebenfalls zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional.

Diese Beispiele zeigen, wie man UCC/EAN-128‑nicht‑verknüpfte Modi in GS1MicroPdf417 kodiert.

```

 [C#]
 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhe/Breite-Verhältnis des 2D-Barcode-Moduls. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Spaltenanzahl. |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getEncodeMode()](#getEncodeMode--) | Identifiziert den Pdf417‑Kodiermodus. |
| [getErrorLevel()](#getErrorLevel--) | Ermittelt den Pdf417‑Symboltyp des Fehlerschutzniveaus des BarCode, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerschutzinformation, level8 bedeutet die beste Fehlerschutzstufe, was ein größeres Bild bedeutet. |
| [getMacroCharacters()](#getMacroCharacters--) | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417‑Barcode‑Empfängername (optional). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417‑Barcode‑Prüfsumme (optional). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | MacroPdf417‑Barcode‑Datei‑ID (erforderliches Feld). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 barcode Dateiname (optional Feld). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 Dateigröße (optional Feld). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | MacroPdf417 barcode's Segment-ID (erforderliches Feld), die bei 0 beginnt und bis MacroSegmentsCount - 1 reicht. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | MacroPdf417 barcode Segmentanzahl (optional Feld). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 barcode Absendername (optional Feld). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Wird verwendet, um dem Encoder mitzuteilen, ob dem Segment ein Macro‑PDF417‑Terminator (Codewort 922) hinzugefügt werden soll. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 barcode Zeitstempel (optional Feld). |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | Pdf417 Symbologie-Typ des BarCode-Komprimierungsmodus. |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getPdf417EncodeMode()](#getPdf417EncodeMode--) | Identifiziert den Pdf417‑Kodiermodus. |
| [getPdf417ErrorLevel()](#getPdf417ErrorLevel--) | Ermittelt den Pdf417‑Symboltyp des Fehlerschutzniveaus des BarCode, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerschutzinformation, level8 bedeutet die beste Fehlerschutzstufe, was ein größeres Bild bedeutet. |
| [getPdf417MacroAddressee()](#getPdf417MacroAddressee--) | MacroPdf417‑Barcode‑Empfängername (optional). |
| [getPdf417MacroChecksum()](#getPdf417MacroChecksum--) | MacroPdf417‑Barcode‑Prüfsumme (optional). |
| [getPdf417MacroECIEncoding()](#getPdf417MacroECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getPdf417MacroFileID()](#getPdf417MacroFileID--) | MacroPdf417‑Barcode‑Datei‑ID (erforderliches Feld). |
| [getPdf417MacroFileName()](#getPdf417MacroFileName--) | MacroPdf417 barcode Dateiname (optional Feld). |
| [getPdf417MacroFileSize()](#getPdf417MacroFileSize--) | MacroPdf417 Dateigröße (optional Feld). |
| [getPdf417MacroSegmentID()](#getPdf417MacroSegmentID--) | MacroPdf417 barcode's Segment-ID (erforderliches Feld), die bei 0 beginnt und bis MacroSegmentsCount - 1 reicht. |
| [getPdf417MacroSegmentsCount()](#getPdf417MacroSegmentsCount--) | MacroPdf417 barcode Segmentanzahl (optional Feld). |
| [getPdf417MacroSender()](#getPdf417MacroSender--) | MacroPdf417 barcode Absendername (optional Feld). |
| [getPdf417MacroTerminator()](#getPdf417MacroTerminator--) | Wird verwendet, um dem Encoder mitzuteilen, ob dem Segment ein Macro‑PDF417‑Terminator (Codewort 922) hinzugefügt werden soll. |
| [getPdf417MacroTimeStamp()](#getPdf417MacroTimeStamp--) | MacroPdf417 barcode Zeitstempel (optional Feld). |
| [getPdf417Truncate()](#getPdf417Truncate--) | Ob der Pdf417 Symbologie-Typ des BarCode gekürzt ist (zur Platzersparnis). |
| [getRows()](#getRows--) | Zeilenanzahl. |
| [getTruncate()](#getTruncate--) | Ob der Pdf417 Symbologie-Typ des BarCode gekürzt ist (zur Platzersparnis). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position kodieren, Modi 908 und 909, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann. |
| [isLinked()](#isLinked--) | Definiert verknüpfte Modi mit GS1MicroPdf417, MicroPdf417 und Pdf417 Barcodes. Mit GS1MicroPdf417 Symbologie werden 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128 Modi kodiert. Mit MicroPdf417 und Pdf417 Symbologien wird 918 Verknüpfungs-Flag zu zugehöriger linearer Komponente außer einem EAN.UCC kodiert. |
| [isReaderInitialization()](#isReaderInitialization--) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höhe/Breite-Verhältnis des 2D-Barcode-Moduls. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position kodieren, Modi 908 und 909, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann. |
| [setColumns(int value)](#setColumns-int-) | Spaltenanzahl. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Bezeichner. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identifiziert den Pdf417‑Kodiermodus. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Legt den Pdf417 Symbologie-Typ des BarCode-Fehlerkorrekturlevels fest, der von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrekturinformationen, level8 bedeutet die beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| [setLinked(boolean value)](#setLinked-boolean-) | Definiert verknüpfte Modi mit GS1MicroPdf417, MicroPdf417 und Pdf417 Barcodes. Mit GS1MicroPdf417 Symbologie werden 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128 Modi kodiert. Mit MicroPdf417 und Pdf417 Symbologien wird 918 Verknüpfungs-Flag zu zugehöriger linearer Komponente außer einem EAN.UCC kodiert. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417‑Barcode‑Empfängername (optional). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417‑Barcode‑Prüfsumme (optional). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Extended Channel Interpretation Bezeichner. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | MacroPdf417‑Barcode‑Datei‑ID (erforderliches Feld). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 barcode Dateiname (optional Feld). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 Dateigröße (optional Feld). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | MacroPdf417 barcode's Segment-ID (erforderliches Feld), die bei 0 beginnt und bis MacroSegmentsCount - 1 reicht. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | MacroPdf417 barcode Segmentanzahl (optional Feld). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 barcode Absendername (optional Feld). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Wird verwendet, um dem Encoder mitzuteilen, ob dem Segment ein Macro‑PDF417‑Terminator (Codewort 922) hinzugefügt werden soll. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 barcode Zeitstempel (optional Feld). |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | Pdf417 Symbologie-Typ des BarCode-Komprimierungsmodus. |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | Extended Channel Interpretation Bezeichner. |
| [setPdf417EncodeMode(Pdf417EncodeMode value)](#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identifiziert den Pdf417‑Kodiermodus. |
| [setPdf417ErrorLevel(Pdf417ErrorLevel value)](#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Legt den Pdf417 Symbologie-Typ des BarCode-Fehlerkorrekturlevels fest, der von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrekturinformationen, level8 bedeutet die beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| [setPdf417MacroAddressee(String value)](#setPdf417MacroAddressee-java.lang.String-) | MacroPdf417‑Barcode‑Empfängername (optional). |
| [setPdf417MacroChecksum(int value)](#setPdf417MacroChecksum-int-) | MacroPdf417‑Barcode‑Prüfsumme (optional). |
| [setPdf417MacroECIEncoding(int value)](#setPdf417MacroECIEncoding-int-) | Extended Channel Interpretation Bezeichner. |
| [setPdf417MacroFileID(int value)](#setPdf417MacroFileID-int-) | MacroPdf417‑Barcode‑Datei‑ID (erforderliches Feld). |
| [setPdf417MacroFileName(String value)](#setPdf417MacroFileName-java.lang.String-) | MacroPdf417 barcode Dateiname (optional Feld). |
| [setPdf417MacroFileSize(int value)](#setPdf417MacroFileSize-int-) | MacroPdf417 Dateigröße (optional Feld). |
| [setPdf417MacroSegmentID(int value)](#setPdf417MacroSegmentID-int-) | MacroPdf417 barcode's Segment-ID (erforderliches Feld), die bei 0 beginnt und bis MacroSegmentsCount - 1 reicht. |
| [setPdf417MacroSegmentsCount(int value)](#setPdf417MacroSegmentsCount-int-) | MacroPdf417 barcode Segmentanzahl (optional Feld). |
| [setPdf417MacroSender(String value)](#setPdf417MacroSender-java.lang.String-) | MacroPdf417 barcode Absendername (optional Feld). |
| [setPdf417MacroTerminator(Pdf417MacroTerminator value)](#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Wird verwendet, um dem Encoder mitzuteilen, ob dem Segment ein Macro‑PDF417‑Terminator (Codewort 922) hinzugefügt werden soll. |
| [setPdf417MacroTimeStamp(LocalDateTime value)](#setPdf417MacroTimeStamp-java.time.LocalDateTime-) | MacroPdf417 barcode Zeitstempel (optional Feld). |
| [setPdf417Truncate(boolean value)](#setPdf417Truncate-boolean-) | Ob der Pdf417 Symbologie-Typ des BarCode gekürzt ist (zur Platzersparnis). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [setRows(int value)](#setRows-int-) | Zeilenanzahl. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Ob der Pdf417 Symbologie-Typ des BarCode gekürzt ist (zur Platzersparnis). |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) zurück. |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode-Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro PDF417 Textfelder. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Identifiziert den Pdf417 Kodiermodus. Standardwert: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Ermittelt den Pdf417‑Symboltyp des Fehlerschutzniveaus des BarCode, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerschutzinformation, level8 bedeutet die beste Fehlerschutzstufe, was ein größeres Bild bedeutet.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro Characters 05 und 06 Werte werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. Kann nur mit MicroPdf417 verwendet werden und kodiert 916 und 917 MicroPdf417 Modi. Standardwert: MacroCharacters.None.

Diese Beispiele zeigen, wie Macro Characters in MicroPdf417 kodiert werden.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 barcode Empfängername (optional Feld). MicroPDF417 barcode Empfängername (optional Feld für den Structured Append‑Modus).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 barcode Prüfsumme (optional Feld). MicroPDF417 barcode Prüfsumme (optional Feld für den Structured Append‑Modus). Das Prüfsummenfeld enthält den Wert der 16‑Bit (2‑Byte) CRC‑Prüfsumme unter Verwendung des CCITT‑16‑Polynoms. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Extended Channel Interpretation Identifiers. Gilt für Macro PDF417 Textfelder.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


MacroPdf417 barcode's Datei-ID (erforderliches Feld). MicroPDF417 barcode's Datei-ID (erforderliches Feld für den Structured Append‑Modus).

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 barcode Dateiname (optional Feld). MicroPDF417 barcode Dateiname (optional Feld für den Structured Append‑Modus).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 Dateigröße (optional Feld). MicroPDF417 Dateigröße (optional Feld für den Structured Append‑Modus). Das Dateigrößenfeld enthält die Größe in Bytes der gesamten Quelldatei.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


MacroPdf417 barcode's Segment-ID (erforderliches Feld), die bei 0 beginnt und bis MacroSegmentsCount - 1 reicht. MicroPDF417 barcode's Segment-ID (erforderliches Feld für den Structured Append‑Modus).

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


MacroPdf417 barcode Segmentanzahl (optional Feld). MicroPDF417 barcode Segmentanzahl (optional Feld für den Structured Append‑Modus).

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 barcode Absendername (optional Feld). MicroPDF417 barcode Absendername (optional Feld für den Structured Append‑Modus).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Wird verwendet, um dem Encoder mitzuteilen, ob das Makro‑PDF417‑Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Nur für Makro‑PDF417 angewendet.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 Barcode-Zeitstempel (optionales Feld). MicroPDF417 Barcode-Zeitstempel (optionales Feld für den Structured Append‑Modus)

**Returns:**
java.time.LocalDateTime
### getPdf417CompactionMode() {#getPdf417CompactionMode--}
```
public final Pdf417CompactionMode getPdf417CompactionMode()
```


Pdf417 Symbologie‑Typ des BarCode‑Komprimierungsmodus. Standardwert: Pdf417CompactionMode.Auto.

**Returns:**
[Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode)
### getPdf417ECIEncoding() {#getPdf417ECIEncoding--}
```
public final int getPdf417ECIEncoding()
```


Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode-Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro PDF417 Textfelder. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen.

**Returns:**
int
### getPdf417EncodeMode() {#getPdf417EncodeMode--}
```
public final Pdf417EncodeMode getPdf417EncodeMode()
```


Identifiziert den Pdf417 Kodiermodus. Standardwert: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getPdf417ErrorLevel() {#getPdf417ErrorLevel--}
```
public final Pdf417ErrorLevel getPdf417ErrorLevel()
```


Ermittelt den Pdf417‑Symboltyp des Fehlerschutzniveaus des BarCode, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerschutzinformation, level8 bedeutet die beste Fehlerschutzstufe, was ein größeres Bild bedeutet.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getPdf417MacroAddressee() {#getPdf417MacroAddressee--}
```
public final String getPdf417MacroAddressee()
```


MacroPdf417 barcode Empfängername (optional Feld). MicroPDF417 barcode Empfängername (optional Feld für den Structured Append‑Modus).

**Returns:**
java.lang.String
### getPdf417MacroChecksum() {#getPdf417MacroChecksum--}
```
public final int getPdf417MacroChecksum()
```


MacroPdf417 barcode Prüfsumme (optional Feld). MicroPDF417 barcode Prüfsumme (optional Feld für den Structured Append‑Modus). Das Prüfsummenfeld enthält den Wert der 16‑Bit (2‑Byte) CRC‑Prüfsumme unter Verwendung des CCITT‑16‑Polynoms. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getPdf417MacroECIEncoding() {#getPdf417MacroECIEncoding--}
```
public final int getPdf417MacroECIEncoding()
```


Extended Channel Interpretation Identifiers. Gilt für Macro PDF417 Textfelder.

**Returns:**
int
### getPdf417MacroFileID() {#getPdf417MacroFileID--}
```
public final int getPdf417MacroFileID()
```


MacroPdf417 barcode's Datei-ID (erforderliches Feld). MicroPDF417 barcode's Datei-ID (erforderliches Feld für den Structured Append‑Modus).

**Returns:**
int
### getPdf417MacroFileName() {#getPdf417MacroFileName--}
```
public final String getPdf417MacroFileName()
```


MacroPdf417 barcode Dateiname (optional Feld). MicroPDF417 barcode Dateiname (optional Feld für den Structured Append‑Modus).

**Returns:**
java.lang.String
### getPdf417MacroFileSize() {#getPdf417MacroFileSize--}
```
public final int getPdf417MacroFileSize()
```


MacroPdf417 Dateigröße (optional Feld). MicroPDF417 Dateigröße (optional Feld für den Structured Append‑Modus). Das Dateigrößenfeld enthält die Größe in Bytes der gesamten Quelldatei.

**Returns:**
int
### getPdf417MacroSegmentID() {#getPdf417MacroSegmentID--}
```
public final int getPdf417MacroSegmentID()
```


MacroPdf417 barcode's Segment-ID (erforderliches Feld), die bei 0 beginnt und bis MacroSegmentsCount - 1 reicht. MicroPDF417 barcode's Segment-ID (erforderliches Feld für den Structured Append‑Modus).

**Returns:**
int
### getPdf417MacroSegmentsCount() {#getPdf417MacroSegmentsCount--}
```
public final int getPdf417MacroSegmentsCount()
```


MacroPdf417 barcode Segmentanzahl (optional Feld). MicroPDF417 barcode Segmentanzahl (optional Feld für den Structured Append‑Modus).

**Returns:**
int
### getPdf417MacroSender() {#getPdf417MacroSender--}
```
public final String getPdf417MacroSender()
```


MacroPdf417 barcode Absendername (optional Feld). MicroPDF417 barcode Absendername (optional Feld für den Structured Append‑Modus).

**Returns:**
java.lang.String
### getPdf417MacroTerminator() {#getPdf417MacroTerminator--}
```
public final Pdf417MacroTerminator getPdf417MacroTerminator()
```


Wird verwendet, um dem Encoder mitzuteilen, ob das Makro‑PDF417‑Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Nur für Makro‑PDF417 angewendet.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getPdf417MacroTimeStamp() {#getPdf417MacroTimeStamp--}
```
public final LocalDateTime getPdf417MacroTimeStamp()
```


MacroPdf417 Barcode-Zeitstempel (optionales Feld). MicroPDF417 Barcode-Zeitstempel (optionales Feld für den Structured Append‑Modus)

**Returns:**
java.time.LocalDateTime
### getPdf417Truncate() {#getPdf417Truncate--}
```
public final boolean getPdf417Truncate()
```


Ob der Pdf417 Symbologie‑Typ des BarCode gekürzt ist (zur Platzersparnis). Auch bekannt als CompactPDF417. Rechts‑Zeilen‑Indikator und Rechts‑Stopp‑Muster werden in diesem Modus entfernt.

**Returns:**
boolean
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


Ob der Pdf417 Symbologie‑Typ des BarCode gekürzt ist (zur Platzersparnis). Auch bekannt als CompactPDF417. Rechts‑Zeilen‑Indikator und Rechts‑Stopp‑Muster werden in diesem Modus entfernt.

**Returns:**
boolean
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


Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position kodieren, Modi 908 und 909, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann.

Diese Beispiele zeigen, wie man Code‑128‑Emulationsmodi mit FNC1 an zweiter Position und ohne kodiert. Auf diese Weise kann MicroPdf417 als Code‑128‑Barcode dekodiert werden.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Definiert verknüpfte Modi mit GS1MicroPdf417, MicroPdf417 und Pdf417 Barcodes. Mit GS1MicroPdf417 Symbologie werden 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128 Modi kodiert. Mit MicroPdf417 und Pdf417 Symbologien wird 918 Verknüpfungs-Flag zu zugehöriger linearer Komponente außer einem EAN.UCC kodiert.

Diese Beispiele zeigen, wie man "Linked" UCC/EAN‑128‑Modi in GS1MicroPdf417 und das Linkage‑Flag (918) in MicroPdf417‑ und Pdf417‑Barcodes kodiert.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Returns:**
boolean
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


Höhe/Breite-Verhältnis des 2D-Barcode-Moduls.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position kodieren, Modi 908 und 909, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann.

Diese Beispiele zeigen, wie man Code‑128‑Emulationsmodi mit FNC1 an zweiter Position und ohne kodiert. Auf diese Weise kann MicroPdf417 als Code‑128‑Barcode dekodiert werden.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Spaltenanzahl.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode-Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro PDF417 Textfelder. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Identifiziert den Pdf417 Kodiermodus. Standardwert: Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Legt den Pdf417 Symbologie-Typ des BarCode-Fehlerkorrekturlevels fest, der von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrekturinformationen, level8 bedeutet die beste Fehlerkorrektur, was ein größeres Bild bedeutet.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417 Symbologie‑Typ des BarCode‑Fehlerkorrektur‑Levels von level0 bis level8, level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet beste Fehlerkorrektur, was ein größeres Bild bedeutet. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Definiert verknüpfte Modi mit GS1MicroPdf417, MicroPdf417 und Pdf417 Barcodes. Mit GS1MicroPdf417 Symbologie werden 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128 Modi kodiert. Mit MicroPdf417 und Pdf417 Symbologien wird 918 Verknüpfungs-Flag zu zugehöriger linearer Komponente außer einem EAN.UCC kodiert.

Diese Beispiele zeigen, wie man "Linked" UCC/EAN‑128‑Modi in GS1MicroPdf417 und das Linkage‑Flag (918) in MicroPdf417‑ und Pdf417‑Barcodes kodiert.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro Characters 05 und 06 Werte werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. Kann nur mit MicroPdf417 verwendet werden und kodiert 916 und 917 MicroPdf417 Modi. Standardwert: MacroCharacters.None.

Diese Beispiele zeigen, wie Macro Characters in MicroPdf417 kodiert werden.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 barcode Empfängername (optional Feld). MicroPDF417 barcode Empfängername (optional Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 barcode Prüfsumme (optional Feld). MicroPDF417 barcode Prüfsumme (optional Feld für den Structured Append‑Modus). Das Prüfsummenfeld enthält den Wert der 16‑Bit (2‑Byte) CRC‑Prüfsumme unter Verwendung des CCITT‑16‑Polynoms. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. Gilt für Macro PDF417 Textfelder.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


MacroPdf417 barcode's Datei-ID (erforderliches Feld). MicroPDF417 barcode's Datei-ID (erforderliches Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 barcode Dateiname (optional Feld). MicroPDF417 barcode Dateiname (optional Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 Dateigröße (optional Feld). MicroPDF417 Dateigröße (optional Feld für den Structured Append‑Modus). Das Dateigrößenfeld enthält die Größe in Bytes der gesamten Quelldatei.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


MacroPdf417 barcode's Segment-ID (erforderliches Feld), die bei 0 beginnt und bis MacroSegmentsCount - 1 reicht. MicroPDF417 barcode's Segment-ID (erforderliches Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


MacroPdf417 barcode Segmentanzahl (optional Feld). MicroPDF417 barcode Segmentanzahl (optional Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 barcode Absendername (optional Feld). MicroPDF417 barcode Absendername (optional Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Wird verwendet, um dem Encoder mitzuteilen, ob das Makro‑PDF417‑Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Nur für Makro‑PDF417 angewendet.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 Barcode-Zeitstempel (optionales Feld). MicroPDF417 Barcode-Zeitstempel (optionales Feld für den Structured Append‑Modus)

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDateTime |  |

### setPdf417CompactionMode(Pdf417CompactionMode value) {#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-}
```
public final void setPdf417CompactionMode(Pdf417CompactionMode value)
```


Pdf417 Symbologie‑Typ des BarCode‑Komprimierungsmodus. Standardwert: Pdf417CompactionMode.Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode) |  |

### setPdf417ECIEncoding(int value) {#setPdf417ECIEncoding-int-}
```
public final void setPdf417ECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode-Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro PDF417 Textfelder. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPdf417EncodeMode(Pdf417EncodeMode value) {#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setPdf417EncodeMode(Pdf417EncodeMode value)
```


Identifiziert den Pdf417 Kodiermodus. Standardwert: Auto.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setPdf417ErrorLevel(Pdf417ErrorLevel value) {#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setPdf417ErrorLevel(Pdf417ErrorLevel value)
```


Legt den Pdf417 Symbologie-Typ des BarCode-Fehlerkorrekturlevels fest, der von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrekturinformationen, level8 bedeutet die beste Fehlerkorrektur, was ein größeres Bild bedeutet.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417 Symbologie‑Typ des BarCode‑Fehlerkorrektur‑Levels von level0 bis level8, level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet beste Fehlerkorrektur, was ein größeres Bild bedeutet. |

### setPdf417MacroAddressee(String value) {#setPdf417MacroAddressee-java.lang.String-}
```
public final void setPdf417MacroAddressee(String value)
```


MacroPdf417 barcode Empfängername (optional Feld). MicroPDF417 barcode Empfängername (optional Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPdf417MacroChecksum(int value) {#setPdf417MacroChecksum-int-}
```
public final void setPdf417MacroChecksum(int value)
```


MacroPdf417 barcode Prüfsumme (optional Feld). MicroPDF417 barcode Prüfsumme (optional Feld für den Structured Append‑Modus). Das Prüfsummenfeld enthält den Wert der 16‑Bit (2‑Byte) CRC‑Prüfsumme unter Verwendung des CCITT‑16‑Polynoms. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPdf417MacroECIEncoding(int value) {#setPdf417MacroECIEncoding-int-}
```
public final void setPdf417MacroECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. Gilt für Macro PDF417 Textfelder.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPdf417MacroFileID(int value) {#setPdf417MacroFileID-int-}
```
public final void setPdf417MacroFileID(int value)
```


MacroPdf417 barcode's Datei-ID (erforderliches Feld). MicroPDF417 barcode's Datei-ID (erforderliches Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPdf417MacroFileName(String value) {#setPdf417MacroFileName-java.lang.String-}
```
public final void setPdf417MacroFileName(String value)
```


MacroPdf417 barcode Dateiname (optional Feld). MicroPDF417 barcode Dateiname (optional Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPdf417MacroFileSize(int value) {#setPdf417MacroFileSize-int-}
```
public final void setPdf417MacroFileSize(int value)
```


MacroPdf417 Dateigröße (optional Feld). MicroPDF417 Dateigröße (optional Feld für den Structured Append‑Modus). Das Dateigrößenfeld enthält die Größe in Bytes der gesamten Quelldatei.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPdf417MacroSegmentID(int value) {#setPdf417MacroSegmentID-int-}
```
public final void setPdf417MacroSegmentID(int value)
```


MacroPdf417 barcode's Segment-ID (erforderliches Feld), die bei 0 beginnt und bis MacroSegmentsCount - 1 reicht. MicroPDF417 barcode's Segment-ID (erforderliches Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPdf417MacroSegmentsCount(int value) {#setPdf417MacroSegmentsCount-int-}
```
public final void setPdf417MacroSegmentsCount(int value)
```


MacroPdf417 barcode Segmentanzahl (optional Feld). MicroPDF417 barcode Segmentanzahl (optional Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setPdf417MacroSender(String value) {#setPdf417MacroSender-java.lang.String-}
```
public final void setPdf417MacroSender(String value)
```


MacroPdf417 barcode Absendername (optional Feld). MicroPDF417 barcode Absendername (optional Feld für den Structured Append‑Modus).

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPdf417MacroTerminator(Pdf417MacroTerminator value) {#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setPdf417MacroTerminator(Pdf417MacroTerminator value)
```


Wird verwendet, um dem Encoder mitzuteilen, ob das Makro‑PDF417‑Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Nur für Makro‑PDF417 angewendet.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setPdf417MacroTimeStamp(LocalDateTime value) {#setPdf417MacroTimeStamp-java.time.LocalDateTime-}
```
public final void setPdf417MacroTimeStamp(LocalDateTime value)
```


MacroPdf417 Barcode-Zeitstempel (optionales Feld). MicroPDF417 Barcode-Zeitstempel (optionales Feld für den Structured Append‑Modus)

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDateTime |  |

### setPdf417Truncate(boolean value) {#setPdf417Truncate-boolean-}
```
public final void setPdf417Truncate(boolean value)
```


Ob der Pdf417 Symbologie‑Typ des BarCode gekürzt ist (zur Platzersparnis). Auch bekannt als CompactPDF417. Rechts‑Zeilen‑Indikator und Rechts‑Stopp‑Muster werden in diesem Modus entfernt.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren.

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

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Ob der Pdf417 Symbologie‑Typ des BarCode gekürzt ist (zur Platzersparnis). Auch bekannt als CompactPDF417. Rechts‑Zeilen‑Indikator und Rechts‑Stopp‑Muster werden in diesem Modus entfernt.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die dieses [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) repräsentiert.
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

