---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "PDF417-Parameter."
type: docs
weight: 770
url: /de/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

PDF417-Parameter. Enthält Parameter für PDF417, MacroPDF417, MicroPDF417 und GS1MicroPdf417. MacroPDF417 erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. MicroPDF417 im Structured Append‑Modus (wie im MacroPDF417‑Modus) erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. Diese Beispiele zeigen, wie man UCC/EAN-128‑Nicht‑Verknüpfungs‑Modi in GS1MicroPdf417 codiert.

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Höhen-/Breitenverhältnis des 2D-Barcode-Moduls. |
| [getColumns()](#getcolumns) | Spaltenanzahl. |
| [getECIEncoding()](#geteciencoding) | Erweiterte Kanalinterpretations-Identifikatoren. Sie werden verwendet, um dem Barcode-Leser Details über die verwendeten Referenzen für |
| [getEncodeMode()](#getencodemode) | Identifiziert den Pdf417‑Kodierungsmodus. Standardwert: Auto. |
| [getErrorLevel()](#geterrorlevel) | Ermittelt den Pdf417‑Symboltyp des Fehlerkorrektur‑Levels des BarCodes, das von level0 bis level8 reicht, level0 bedeutet keine Fehlerkorrektur. |
| [getMacroCharacters()](#getmacrocharacters) | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um eine kompaktere Codierung in speziellen Modi zu erreichen. Kann nur mit Micro verwendet werden. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | MacroPdf417‑Barcode-Empfängername (optional). MicroPDF417‑Barcode-Empfängername (optional für Structured A |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | MacroPdf417‑Barcode-Prüfsumme (optional). MicroPDF417‑Barcode-Prüfsumme (optional für Structured Append‑Modus) |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | Extended Channel Interpretation‑Bezeichner. Gilt für Macro‑PDF417‑Textfelder. |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | MacroPdf417‑Barcode‑Datei‑ID (erforderliches Feld). MicroPDF417‑Barcode‑Datei‑ID (erforderliches Feld für Structured Append‑Modus |
| [getMacroPdf417FileName()](#getmacropdf417filename) | MacroPdf417‑Barcode‑Dateiname (optional). MicroPDF417‑Barcode‑Dateiname (optional für Structured Append‑Modus |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | MacroPdf417‑Dateigröße (optional). MicroPDF417‑Dateigröße (optional für Structured Append‑Modus) Die Dateigröße |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | MacroPdf417‑Barcode‑Segment‑ID (erforderliches Feld), die von 0 bis MacroSegmentsCount - 1 reicht. MicroPDF417‑Barcode‑ |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | MacroPdf417‑Barcode‑Segmentanzahl (optional). MicroPDF417‑Barcode‑Segmentanzahl (optional für Structured A |
| [getMacroPdf417Sender()](#getmacropdf417sender) | MacroPdf417‑Barcode‑Absendername (optional). MicroPDF417‑Barcode‑Absendername (optional für Structured Append |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Wird verwendet, um dem Encoder mitzuteilen, ob ein Macro PDF417 Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Wird nur für Macro PD angewendet. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | MacroPdf417‑Barcode‑Zeitstempel (optional). MicroPDF417‑Barcode‑Zeitstempel (optional für Structured Append mo |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | Pdf417‑Symboltyp des Komprimierungsmodus des BarCodes. Standardwert: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | Erweiterte Kanalinterpretations-Identifikatoren. Sie werden verwendet, um dem Barcode-Leser Details über die verwendeten Referenzen für |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Identifiziert den Pdf417‑Kodierungsmodus. Standardwert: Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | Ermittelt den Pdf417‑Symboltyp des Fehlerkorrektur‑Levels des BarCodes, das von level0 bis level8 reicht, level0 bedeutet keine Fehlerkorrektur. |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | Ermittelt den Makro‑Pdf417‑Barcode‑Empfängername. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | Ermittelt die Makro‑Pdf417‑Barcode‑Prüfsumme. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | Extended Channel Interpretation‑Bezeichner. Gilt für Macro‑PDF417‑Textfelder. |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Ermittelt die Pdf417‑Barcode‑Datei‑ID. Wird für MacroPdf417 verwendet. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | Ermittelt den Makro‑Pdf417‑Barcode‑Dateinamen. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | Ermittelt die Makro‑Pdf417‑Dateigröße. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | Ermittelt die Makro‑Pdf417‑Barcode‑Segment‑ID, die von 0 bis MacroSegmentsCount - 1 reicht. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | Ermittelt die Makro‑Pdf417‑Barcode‑Segmentanzahl. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | Ermittelt den Makro‑Pdf417‑Barcode‑Absendernamen. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | Wird verwendet, um dem Encoder mitzuteilen, ob ein Macro PDF417 Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Wird nur für Macro PD angewendet. |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | Ermittelt den Makro‑Pdf417‑Barcode‑Zeitstempel. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | Ob der Pdf417 Symbologie‑Typ des BarCode gekürzt ist (um Platz zu reduzieren). |
| [getRows()](#getrows) | Zeilenanzahl. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Identifiziert die ID des DotCode Structured Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Anzahl der Barcodes sein. |
| [getTruncate()](#gettruncate) | Ob der Pdf417 Symbologie‑Typ des BarCode gekürzt ist (um Platz zu reduzieren). Auch bekannt als CompactPDF417. Rechte Zeilenanzeige |
| [isCode128Emulation()](#iscode128emulation) | Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position kodieren, Modi 908 und |
| [isLinked()](#islinked) | Definiert verknüpfte Modi mit GS1MicroPdf417, MicroPdf417 und Pdf417 Barcodes. Mit der GS1MicroPdf417‑Symbologie werden 906, 907 kodiert. |
| [isReaderInitialization()](#isreaderinitialization) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [setAspectRatio()](#setaspectratio) | Höhen-/Breitenverhältnis des 2D-Barcode-Moduls. |
| [setCode128Emulation()](#setcode128emulation) | Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position kodieren, Modi 908 und |
| [setColumns()](#setcolumns) | Spaltenanzahl. |
| [setECIEncoding()](#seteciencoding) | Erweiterte Kanalinterpretations-Identifikatoren. Sie werden verwendet, um dem Barcode-Leser Details über die verwendeten Referenzen für |
| [setEncodeMode()](#setencodemode) | Identifiziert den Pdf417‑Kodierungsmodus. Standardwert: Auto. |
| [setErrorLevel(value)](#seterrorlevel) | Legt das Fehlerkorrektur‑Level des Pdf417‑Symbologie‑Typs des BarCode fest, von level0 bis level8, wobei level0 keine Fehlerkorrektur bedeutet. |
| [setLinked()](#setlinked) | Definiert verknüpfte Modi mit GS1MicroPdf417, MicroPdf417 und Pdf417 Barcodes. Mit der GS1MicroPdf417‑Symbologie werden 906, 907 kodiert. |
| [setMacroCharacters()](#setmacrocharacters) | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um eine kompaktere Codierung in speziellen Modi zu erreichen. Kann nur mit Micro verwendet werden. |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | MacroPdf417‑Barcode-Empfängername (optional). MicroPDF417‑Barcode-Empfängername (optional für Structured A |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | MacroPdf417‑Barcode-Prüfsumme (optional). MicroPDF417‑Barcode-Prüfsumme (optional für Structured Append‑Modus) |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | Extended Channel Interpretation‑Bezeichner. Gilt für Macro‑PDF417‑Textfelder. |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | MacroPdf417‑Barcode‑Datei‑ID (erforderliches Feld). MicroPDF417‑Barcode‑Datei‑ID (erforderliches Feld für Structured Append‑Modus |
| [setMacroPdf417FileName()](#setmacropdf417filename) | MacroPdf417‑Barcode‑Dateiname (optional). MicroPDF417‑Barcode‑Dateiname (optional für Structured Append‑Modus |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | MacroPdf417‑Dateigröße (optional). MicroPDF417‑Dateigröße (optional für Structured Append‑Modus) Die Dateigröße |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | MacroPdf417‑Barcode‑Segment‑ID (erforderliches Feld), die von 0 bis MacroSegmentsCount - 1 reicht. MicroPDF417‑Barcode‑ |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | MacroPdf417‑Barcode‑Segmentanzahl (optional). MicroPDF417‑Barcode‑Segmentanzahl (optional für Structured A |
| [setMacroPdf417Sender()](#setmacropdf417sender) | MacroPdf417‑Barcode‑Absendername (optional). MicroPDF417‑Barcode‑Absendername (optional für Structured Append |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | Wird verwendet, um dem Encoder mitzuteilen, ob ein Macro PDF417 Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Wird nur für Macro PD angewendet. |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | MacroPdf417‑Barcode‑Zeitstempel (optional). MicroPDF417‑Barcode‑Zeitstempel (optional für Structured Append mo |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | Pdf417‑Symboltyp des Komprimierungsmodus des BarCodes. Standardwert: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | Erweiterte Kanalinterpretations-Identifikatoren. Sie werden verwendet, um dem Barcode-Leser Details über die verwendeten Referenzen für |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Identifiziert den Pdf417‑Kodierungsmodus. Standardwert: Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Legt das Fehlerkorrektur‑Level des Pdf417‑Symbologie‑Typs des BarCode fest, von level0 bis level8, wobei level0 keine Fehlerkorrektur bedeutet. |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | Setzt den Empfängernamen des Makro‑Pdf417‑Barcodes. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | Setzt die Prüfsumme des Makro‑Pdf417‑Barcodes. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | Extended Channel Interpretation‑Bezeichner. Gilt für Macro‑PDF417‑Textfelder. |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | Setzt die Datei‑ID des Makro‑Pdf417‑Barcodes. Wird für MacroPdf417 verwendet. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | Setzt den Dateinamen des Makro‑Pdf417. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | Setzt die Dateigröße des Makro‑Pdf417. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | Setzt die Segment‑ID des Makro‑Pdf417‑Barcodes, die bei 0 beginnt, bis zu MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | Setzt die Anzahl der Segmente des Makro‑Pdf417‑Barcodes. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | Setzt den Absendernamen des Makro‑Pdf417‑Barcodes. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | Wird verwendet, um dem Encoder mitzuteilen, ob ein Macro PDF417 Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Wird nur für Macro PD angewendet. |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | Setzt den Zeitstempel des Makro‑Pdf417‑Barcodes. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | Ob der Pdf417 Symbologie‑Typ des BarCode gekürzt ist (um Platz zu reduzieren). |
| [setReaderInitialization(value)](#setreaderinitialization) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [setRows()](#setrows) | Zeilenanzahl. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Identifiziert die ID des DotCode Structured Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Anzahl der Barcodes sein. |
| [setTruncate()](#settruncate) | Ob der Pdf417 Symbologie‑Typ des BarCode gekürzt ist (um Platz zu reduzieren). Auch bekannt als CompactPDF417. Rechte Zeilenanzeige |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenketten‑Darstellung dieser Pdf417Parameters zurück. |

### getAspectRatio() {#getaspectratio}

Höhen-/Breitenverhältnis des 2D-Barcode-Moduls.

### getColumns() {#getcolumns}

Spaltenanzahl.

### getECIEncoding() {#geteciencoding}

Extended Channel Interpretation Identifiers. Wird verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro‑PDF417‑Textfelder. Die aktuelle Implementierung umfasst alle bekannten Zeichensatzkodierungen.

### getEncodeMode() {#getencodemode}

Identifiziert den Pdf417‑Kodierungsmodus. Standardwert: Auto.

### getErrorLevel() {#geterrorlevel}

Liest das Fehlerkorrektur‑Level des Pdf417‑Symbologie‑Typs des BarCode aus, von level0 bis level8, wobei level0 keine Fehlerkorrektur‑Informationen bedeutet, level8 die beste Fehlerkorrektur bietet, was ein größeres Bild bedeutet.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in Sondermodi eine kompaktere Kodierung zu erreichen. Können nur mit MicroPdf417 verwendet werden und kodieren die Modi 916 und 917 von MicroPdf417. Standardwert: MacroCharacters.None. Diese Beispiele zeigen, wie Makro‑Zeichen in MicroPdf417 kodiert werden.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

MacroPdf417‑Barcode‑Empfängernamen (optional). MicroPDF417‑Barcode‑Empfängernamen (optional für den Structured Append‑Modus).

### getMacroPdf417Checksum() {#getmacropdf417checksum}

MacroPdf417‑Barcode‑Prüfsumme (optional). MicroPDF417‑Barcode‑Prüfsumme (optional für den Structured Append‑Modus). Das Prüfsummenfeld enthält den Wert der 16‑Bit‑(2‑Byte‑)CRC‑Prüfsumme unter Verwendung des CCITT‑16‑Polynoms. x^16 + x^12 + x^5 + 1

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

Extended Channel Interpretation‑Bezeichner. Gilt für Macro‑PDF417‑Textfelder.

### getMacroPdf417FileID() {#getmacropdf417fileid}

MacroPdf417‑Barcode‑Datei‑ID (erforderliches Feld). MicroPDF417‑Barcode‑Datei‑ID (erforderliches Feld für den Structured Append‑Modus).

### getMacroPdf417FileName() {#getmacropdf417filename}

MacroPdf417‑Barcode‑Dateiname (optional). MicroPDF417‑Barcode‑Dateiname (optional für den Structured Append‑Modus).

### getMacroPdf417FileSize() {#getmacropdf417filesize}

MacroPdf417‑Dateigröße (optional). MicroPDF417‑Dateigröße (optional für den Structured Append‑Modus). Das Feld Dateigröße enthält die Größe in Bytes der gesamten Quelldatei.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

MacroPdf417-Barcode-Segment-ID (erforderliches Feld), die von 0 bis MacroSegmentsCount - 1 reicht. MicroPDF417-Barcode-Segment-ID (erforderliches Feld für den Structured Append‑Modus)

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

MacroPdf417-Barcode‑Segmentanzahl (optionales Feld). MicroPDF417-Barcode‑Segmentanzahl (optionales Feld für den Structured Append‑Modus)

### getMacroPdf417Sender() {#getmacropdf417sender}

MacroPdf417-Barcode‑Absendername (optionales Feld). MicroPDF417-Barcode‑Absendername (optionales Feld für den Structured Append‑Modus)

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Wird verwendet, um dem Encoder mitzuteilen, ob der Macro PDF417‑Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Wird nur für Macro PDF417 angewendet.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

MacroPdf417-Barcode‑Zeitstempel (optionales Feld). MicroPDF417-Barcode‑Zeitstempel (optionales Feld für den Structured Append‑Modus)

### getPdf417CompactionMode() {#getpdf417compactionmode}

Pdf417‑Symboltyp des Komprimierungsmodus des BarCodes. Standardwert: Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Erweiterte Channel‑Interpretations‑Identifikatoren. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung besteht aus allen bekannten Zeichensatzkodierungen.

### getPdf417EncodeMode() {#getpdf417encodemode}

Identifiziert den Pdf417‑Kodierungsmodus. Standardwert: Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Liest das Fehlerkorrektur‑Level des Pdf417‑Symbologie‑Typs des BarCode aus, von level0 bis level8, wobei level0 keine Fehlerkorrektur‑Informationen bedeutet, level8 die beste Fehlerkorrektur bietet, was ein größeres Bild bedeutet.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Ermittelt den Makro‑Pdf417‑Barcode‑Empfängername.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Ermittelt die Makro‑Pdf417‑Barcode‑Prüfsumme.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation‑Bezeichner. Gilt für Macro‑PDF417‑Textfelder.

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Ermittelt die Pdf417‑Barcode‑Datei‑ID. Wird für MacroPdf417 verwendet.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Ermittelt den Makro‑Pdf417‑Barcode‑Dateinamen.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Ermittelt die Makro‑Pdf417‑Dateigröße.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Ermittelt die Makro‑Pdf417‑Barcode‑Segment‑ID, die von 0 bis MacroSegmentsCount - 1 reicht.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Ermittelt die Makro‑Pdf417‑Barcode‑Segmentanzahl.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

Ermittelt den Makro‑Pdf417‑Barcode‑Absendernamen.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Wird verwendet, um dem Encoder mitzuteilen, ob der Macro PDF417‑Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Wird nur für Macro PDF417 angewendet.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Ermittelt den Makro‑Pdf417‑Barcode‑Zeitstempel.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

Ob der Pdf417 Symbologie‑Typ des BarCode gekürzt ist (um Platz zu reduzieren).

### getRows() {#getrows}

Zeilenanzahl.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Der Standardwert ist -1.

### getTruncate() {#gettruncate}

Gibt an, ob der Pdf417‑Symboltyp des Barcodes gekürzt ist (zur Platzersparnis). Auch bekannt als CompactPDF417. Der rechte Zeilenindikator und das rechte Stopp‑Muster werden in diesem Modus entfernt.

### isCode128Emulation() {#iscode128emulation}

Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position in den Modi 908 und 909 kodieren, sowie 910 und 911, die lediglich anzeigen, dass ein erkannter MicroPdf417 als Code 128 interpretiert werden kann. Diese Beispiele zeigen, wie Code‑128‑Emulationsmodi mit FNC1 in zweiter Position und ohne kodiert werden. Auf diese Weise kann MicroPdf417 als Code 128‑Barcode dekodiert werden.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417- und Pdf417‑Barcodes. Mit dem GS1MicroPdf417‑Symbol werden die "Linked"-UCC/EAN-128‑Modi 906, 907, 912, 913, 914, 915 kodiert. Mit den MicroPdf417‑ und Pdf417‑Symbolen wird das Verknüpfungsflag 918 für die zugehörige lineare Komponente außer einem EAN.UCC kodiert. Diese Beispiele zeigen, wie die "Linked"-UCC/EAN-128‑Modi in GS1MicroPdf417 und das Verknüpfungsflag (918) in MicroPdf417‑ und Pdf417‑Barcodes kodiert werden.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren.

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

Höhen-/Breitenverhältnis des 2D-Barcode-Moduls.

### setCode128Emulation() {#setcode128emulation}

Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position in den Modi 908 und 909 kodieren, sowie 910 und 911, die lediglich anzeigen, dass ein erkannter MicroPdf417 als Code 128 interpretiert werden kann. Diese Beispiele zeigen, wie Code‑128‑Emulationsmodi mit FNC1 in zweiter Position und ohne kodiert werden. Auf diese Weise kann MicroPdf417 als Code 128‑Barcode dekodiert werden.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

Spaltenanzahl.

### setECIEncoding() {#seteciencoding}

Extended Channel Interpretation Identifiers. Wird verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro‑PDF417‑Textfelder. Die aktuelle Implementierung umfasst alle bekannten Zeichensatzkodierungen.

### setEncodeMode() {#setencodemode}

Identifiziert den Pdf417‑Kodierungsmodus. Standardwert: Auto.

### setErrorLevel(value) {#seterrorlevel}

Legt den Pdf417‑Symboltyp des Barcodes für das Fehlerkorrektur‑Level fest, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet die beste Fehlerkorrektur, was ein größeres Bild bedeutet.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Pdf417‑Symboltyp des Barcodes für das Fehlerkorrektur‑Level, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet die beste Fehlerkorrektur, was ein größeres Bild bedeutet. |

### setLinked() {#setlinked}

Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417- und Pdf417‑Barcodes. Mit dem GS1MicroPdf417‑Symbol werden die "Linked"-UCC/EAN-128‑Modi 906, 907, 912, 913, 914, 915 kodiert. Mit den MicroPdf417‑ und Pdf417‑Symbolen wird das Verknüpfungsflag 918 für die zugehörige lineare Komponente außer einem EAN.UCC kodiert. Diese Beispiele zeigen, wie die "Linked"-UCC/EAN-128‑Modi in GS1MicroPdf417 und das Verknüpfungsflag (918) in MicroPdf417‑ und Pdf417‑Barcodes kodiert werden.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in Sondermodi eine kompaktere Kodierung zu erreichen. Können nur mit MicroPdf417 verwendet werden und kodieren die Modi 916 und 917 von MicroPdf417. Standardwert: MacroCharacters.None. Diese Beispiele zeigen, wie Makro‑Zeichen in MicroPdf417 kodiert werden.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

MacroPdf417‑Barcode‑Empfängernamen (optional). MicroPDF417‑Barcode‑Empfängernamen (optional für den Structured Append‑Modus).

### setMacroPdf417Checksum() {#setmacropdf417checksum}

MacroPdf417‑Barcode‑Prüfsumme (optional). MicroPDF417‑Barcode‑Prüfsumme (optional für den Structured Append‑Modus). Das Prüfsummenfeld enthält den Wert der 16‑Bit‑(2‑Byte‑)CRC‑Prüfsumme unter Verwendung des CCITT‑16‑Polynoms. x^16 + x^12 + x^5 + 1

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

Extended Channel Interpretation‑Bezeichner. Gilt für Macro‑PDF417‑Textfelder.

### setMacroPdf417FileID() {#setmacropdf417fileid}

MacroPdf417‑Barcode‑Datei‑ID (erforderliches Feld). MicroPDF417‑Barcode‑Datei‑ID (erforderliches Feld für den Structured Append‑Modus).

### setMacroPdf417FileName() {#setmacropdf417filename}

MacroPdf417‑Barcode‑Dateiname (optional). MicroPDF417‑Barcode‑Dateiname (optional für den Structured Append‑Modus).

### setMacroPdf417FileSize() {#setmacropdf417filesize}

MacroPdf417‑Dateigröße (optional). MicroPDF417‑Dateigröße (optional für den Structured Append‑Modus). Das Feld Dateigröße enthält die Größe in Bytes der gesamten Quelldatei.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

MacroPdf417-Barcode-Segment-ID (erforderliches Feld), die von 0 bis MacroSegmentsCount - 1 reicht. MicroPDF417-Barcode-Segment-ID (erforderliches Feld für den Structured Append‑Modus)

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

MacroPdf417-Barcode‑Segmentanzahl (optionales Feld). MicroPDF417-Barcode‑Segmentanzahl (optionales Feld für den Structured Append‑Modus)

### setMacroPdf417Sender() {#setmacropdf417sender}

MacroPdf417-Barcode‑Absendername (optionales Feld). MicroPDF417-Barcode‑Absendername (optionales Feld für den Structured Append‑Modus)

### setMacroPdf417Terminator() {#setmacropdf417terminator}

Wird verwendet, um dem Encoder mitzuteilen, ob der Macro PDF417‑Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Wird nur für Macro PDF417 angewendet.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

MacroPdf417-Barcode‑Zeitstempel (optionales Feld). MicroPDF417-Barcode‑Zeitstempel (optionales Feld für den Structured Append‑Modus)

### setPdf417CompactionMode() {#setpdf417compactionmode}

Pdf417‑Symboltyp des Komprimierungsmodus des BarCodes. Standardwert: Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Erweiterte Channel‑Interpretations‑Identifikatoren. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung besteht aus allen bekannten Zeichensatzkodierungen.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Identifiziert den Pdf417‑Kodierungsmodus. Standardwert: Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Legt den Pdf417‑Symboltyp des Barcodes für das Fehlerkorrektur‑Level fest, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet die beste Fehlerkorrektur, was ein größeres Bild bedeutet.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Setzt den Empfängernamen des Makro‑Pdf417‑Barcodes.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Setzt die Prüfsumme des Makro‑Pdf417‑Barcodes.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Das Prüfsummenfeld enthält den Wert der 16‑Bit‑(2‑Byte‑)CRC‑Prüfsumme, die den CCITT‑16‑Polynom verwendet. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation‑Bezeichner. Gilt für Macro‑PDF417‑Textfelder.

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Setzt die Datei‑ID des Makro‑Pdf417‑Barcodes. Wird für MacroPdf417 verwendet.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Setzt den Dateinamen des Makro‑Pdf417.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Setzt die Dateigröße des Makro‑Pdf417.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Das Feld Dateigröße enthält die Größe in Bytes der gesamten Quelldatei. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Setzt die Segment‑ID des Makro‑Pdf417‑Barcodes, die bei 0 beginnt, bis zu MacroSegmentsCount - 1.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Setzt die Anzahl der Segmente des Makro‑Pdf417‑Barcodes.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

Setzt den Absendernamen des Makro‑Pdf417‑Barcodes.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Wird verwendet, um dem Encoder mitzuteilen, ob der Macro PDF417‑Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Wird nur für Macro PDF417 angewendet.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Setzt den Zeitstempel des Makro‑Pdf417‑Barcodes.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

Ob der Pdf417 Symbologie‑Typ des BarCode gekürzt ist (um Platz zu reduzieren).

### setReaderInitialization(value) {#setreaderinitialization}

Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren.

| Parameter | Beschreibung |
| --- | --- |
| Wert |  |

### setRows() {#setrows}

Zeilenanzahl.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Der Standardwert ist -1.

### setTruncate() {#settruncate}

Gibt an, ob der Pdf417‑Symboltyp des Barcodes gekürzt ist (zur Platzersparnis). Auch bekannt als CompactPDF417. Der rechte Zeilenindikator und das rechte Stopp‑Muster werden in diesem Modus entfernt.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenketten‑Darstellung dieser Pdf417Parameters zurück.

**Returns:** A string that represents this Pdf417Parameters.
