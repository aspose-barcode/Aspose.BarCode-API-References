---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "PDF417-Parameter."
type: docs
weight: 58
url: /de/java/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417‑Parameter. Enthält Parameter für PDF417, MacroPDF417, MicroPDF417 und GS1MicroPdf417. MacroPDF417 erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. MicroPDF417 im Structured‑Append‑Modus (derselbe wie MacroPDF417‑Modus) erfordert ebenfalls zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional.

Diese Beispiele zeigen, wie man UCC/EAN-128‑nicht‑verknüpfte Modi in GS1MicroPdf417 codiert.

```

 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höhen-/Breitenverhältnis des 2D-BarCode-Moduls. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Spaltenanzahl. |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getEncodeMode()](#getEncodeMode--) | Identifiziert den Pdf417‑Kodiermodus. |
| [getErrorLevel()](#getErrorLevel--) | Liefert den Pdf417‑Symbologie‑Typ des BarCode‑Fehlerkorrektur‑Levels, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| [getMacroCharacters()](#getMacroCharacters--) | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Codierung zu erhalten. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417‑Barcode‑Empfängername (optional). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417‑Barcode‑Prüfsumme (optional). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Extended Channel Interpretation Bezeichner. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Datei‑ID des MacroPdf417‑Barcodes (erforderliches Feld). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417‑Barcode‑Dateiname (optional). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417‑Dateigröße (optional). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Segment‑ID des MacroPdf417‑Barcodes (erforderliches Feld), die von 0 bis MacroSegmentsCount - 1 reicht. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Anzahl der Segmente des MacroPdf417‑Barcodes (optionales Feld). |
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
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identifiziert den Pdf417‑Kodiermodus. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Setzt den Pdf417‑Symbologie‑Typ des BarCode‑Fehlerkorrektur‑Levels, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| [setLinked(boolean value)](#setLinked-boolean-) | Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417- und Pdf417‑Barcodes. Mit der GS1MicroPdf417‑Symbologie werden die Modi 906, 907, 912, 913, 914, 915 „Linked“ UCC/EAN‑128‑Modi kodiert. Mit den Symbologien MicroPdf417 und Pdf417 wird das Verknüpfungs‑Flag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Codierung zu erhalten. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417‑Barcode‑Empfängername (optional). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417‑Barcode‑Prüfsumme (optional). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Extended Channel Interpretation Bezeichner. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Datei‑ID des MacroPdf417‑Barcodes (erforderliches Feld). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417‑Barcode‑Dateiname (optional). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417‑Dateigröße (optional). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Segment‑ID des MacroPdf417‑Barcodes (erforderliches Feld), die von 0 bis MacroSegmentsCount - 1 reicht. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Anzahl der Segmente des MacroPdf417‑Barcodes (optionales Feld). |
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


Identifiziert den Pdf417‑Kodiermodus. Standardwert: Auto.

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

Diese Beispiele zeigen, wie man Makrozeichen in MicroPdf417 kodiert

```

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```

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


MacroPdf417 Barcode-Datei-ID (erforderliches Feld). MicroPDF417 Barcode-Datei-ID (erforderliches Feld für den Structured Append‑Modus)

**Returns:**
int
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


MacroPdf417 Barcode-Segment-ID (erforderliches Feld), die von 0 bis MacroSegmentsCount - 1 reicht. MicroPDF417 Barcode-Segment-ID (erforderliches Feld für den Structured Append‑Modus)

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


MacroPdf417 Barcode-Segmentanzahl (optionales Feld). MicroPDF417 Barcode-Segmentanzahl (optionales Feld für den Structured Append‑Modus)

**Returns:**
int
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


Ob der Pdf417‑Symboltyp des BarCodes gekürzt ist (zur Platzersparnis). Auch bekannt als CompactPDF417. Der rechte Zeilenindikator und das rechte Stopp‑Muster werden in diesem Modus entfernt.

**Returns:**
boolesch
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position in den Modi 908 und 909 kodieren, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann.

Diese Beispiele zeigen, wie man Code‑128‑Emulationsmodi mit FNC1 an zweiter Stelle und ohne kodiert. Auf diese Weise kann MicroPdf417 als Code‑128‑Barcode dekodiert werden

```

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
 
```

**Returns:**
boolesch
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417- und Pdf417‑Barcodes. Mit der GS1MicroPdf417‑Symbologie werden die Modi 906, 907, 912, 913, 914, 915 „Linked“ UCC/EAN‑128‑Modi kodiert. Mit den Symbologien MicroPdf417 und Pdf417 wird das Verknüpfungs‑Flag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert.

Diese Beispiele zeigen, wie man \"Linked\"‑UCC/EAN‑128‑Modi in GS1MicroPdf417 und das Linkage‑Flag (918) in MicroPdf417‑ und Pdf417‑Barcodes kodiert

```

```

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

Diese Beispiele zeigen, wie man Code‑128‑Emulationsmodi mit FNC1 an zweiter Stelle und ohne kodiert. Auf diese Weise kann MicroPdf417 als Code‑128‑Barcode dekodiert werden

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


Identifiziert den Pdf417‑Kodiermodus. Standardwert: Auto.

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

Diese Beispiele zeigen, wie man \"Linked\"‑UCC/EAN‑128‑Modi in GS1MicroPdf417 und das Linkage‑Flag (918) in MicroPdf417‑ und Pdf417‑Barcodes kodiert

```

 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked modes 906, 907 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());
 
```

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in Sondermodi eine kompaktere Kodierung zu erreichen. Kann nur mit MicroPdf417 verwendet werden und kodiert die MicroPdf417‑Modi 916 und 917. Standardwert: MacroCharacters.None.

Diese Beispiele zeigen, wie man Makrozeichen in MicroPdf417 kodiert

```

```

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


MacroPdf417 Barcode-Datei-ID (erforderliches Feld). MicroPDF417 Barcode-Datei-ID (erforderliches Feld für den Structured Append‑Modus)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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


MacroPdf417 Barcode-Segment-ID (erforderliches Feld), die von 0 bis MacroSegmentsCount - 1 reicht. MicroPDF417 Barcode-Segment-ID (erforderliches Feld für den Structured Append‑Modus)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


MacroPdf417 Barcode-Segmentanzahl (optionales Feld). MicroPDF417 Barcode-Segmentanzahl (optionales Feld für den Structured Append‑Modus)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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


Ob der Pdf417‑Symboltyp des BarCodes gekürzt ist (zur Platzersparnis). Auch bekannt als CompactPDF417. Der rechte Zeilenindikator und das rechte Stopp‑Muster werden in diesem Modus entfernt.

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

