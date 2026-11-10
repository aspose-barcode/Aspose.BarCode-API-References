---
title: "Klasse Pdf417Parameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.Pdf417Parameters Klasse. PDF417‑Parameter. Enthält PDF417‑MacroPDF417‑, MicroPDF417‑ und GS1MicroPdf417‑Parameter. MacroPDF417 erfordert zwei Felder Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. MicroPDF417 im Structured‑Append‑Modus, ähnlich dem MacroPDF417‑Modus, erfordert ebenfalls die beiden Felder Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional."
type: docs
weight: 1570
url: /de/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417-Parameter. Enthält PDF417-, MacroPDF417-, MicroPDF417- und GS1MicroPdf417-Parameter. MacroPDF417 erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. MicroPDF417 im Structured Append‑Modus (gleich wie MacroPDF417‑Modus) erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional.

```csharp
public class Pdf417Parameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | Höhen/Breiten-Verhältnis des 2D‑BarCode‑Moduls. |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | Spaltenanzahl. |
| [ECIEncoding](../../aspose.barcode.generation/pdf417parameters/eciencoding/) { get; set; } | Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro‑PDF417‑Textfelder. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. |
| [EncodeMode](../../aspose.barcode.generation/pdf417parameters/encodemode/) { get; set; } | Identifiziert den Pdf417‑Kodierungsmodus. Standardwert: Auto. |
| [ErrorLevel](../../aspose.barcode.generation/pdf417parameters/errorlevel/) { get; set; } | Liest oder setzt den Pdf417‑Symboltyp des Fehlerkorrektur‑Levels von BarCode, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| [IsCode128Emulation](../../aspose.barcode.generation/pdf417parameters/iscode128emulation/) { get; set; } | Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position in den Modi 908 und 909 kodieren, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann. |
| [IsLinked](../../aspose.barcode.generation/pdf417parameters/islinked/) { get; set; } | Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417- und Pdf417‑Barcodes. Mit der GS1MicroPdf417‑Symbolik werden die „Linked“ UCC/EAN‑128‑Modi 906, 907, 912, 913, 914, 915 kodiert. Mit den Symboliken MicroPdf417 und Pdf417 wird das Verknüpfungsflag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [MacroCharacters](../../aspose.barcode.generation/pdf417parameters/macrocharacters/) { get; set; } | Macro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. Können nur mit MicroPdf417 verwendet werden und kodieren die Modi 916 und 917 von MicroPdf417. Standardwert: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.generation/pdf417parameters/macropdf417addressee/) { get; set; } | MacroPdf417‑Barcode‑Empfängername (optional). MicroPDF417‑Barcode‑Empfängername (optional für den Structured Append‑Modus). |
| [MacroPdf417Checksum](../../aspose.barcode.generation/pdf417parameters/macropdf417checksum/) { get; set; } | MacroPdf417 Barcode-Prüfsumme (optional Feld). MicroPDF417 Barcode-Prüfsumme (optional Feld für den Structured Append‑Modus) Das Prüfsummenfeld enthält den Wert der 16‑Bit (2 Byte) CRC‑Prüfsumme unter Verwendung des CCITT‑16‑Polynoms. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/macropdf417eciencoding/) { get; set; } | Extended Channel Interpretation‑Kennungen. Gilt für Macro‑PDF417‑Textfelder. |
| [MacroPdf417FileID](../../aspose.barcode.generation/pdf417parameters/macropdf417fileid/) { get; set; } | MacroPdf417‑Barcode‑Datei‑ID (erforderliches Feld). MicroPDF417‑Barcode‑Datei‑ID (erforderliches Feld für den Structured‑Append‑Modus). |
| [MacroPdf417FileName](../../aspose.barcode.generation/pdf417parameters/macropdf417filename/) { get; set; } | MacroPdf417 Barcode-Dateiname (optional Feld). MicroPDF417 Barcode-Dateiname (optional Feld für den Structured Append‑Modus) |
| [MacroPdf417FileSize](../../aspose.barcode.generation/pdf417parameters/macropdf417filesize/) { get; set; } | MacroPdf417 Dateigröße (optional Feld). MicroPDF417 Dateigröße (optional Feld für den Structured Append‑Modus) Das Feld für die Dateigröße enthält die Größe in Bytes der gesamten Quelldatei. |
| [MacroPdf417SegmentID](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentid/) { get; set; } | MacroPdf417‑Barcode‑Segment‑ID (erforderliches Feld), das von 0 bis MacroSegmentsCount - 1 reicht. MicroPDF417‑Barcode‑Segment‑ID (erforderliches Feld für den Structured‑Append‑Modus). |
| [MacroPdf417SegmentsCount](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentscount/) { get; set; } | MacroPdf417‑Barcode‑Segmentanzahl (optionales Feld). MicroPDF417‑Barcode‑Segmentanzahl (optionales Feld für den Structured‑Append‑Modus). |
| [MacroPdf417Sender](../../aspose.barcode.generation/pdf417parameters/macropdf417sender/) { get; set; } | MacroPdf417 Barcode-Absendername (optional Feld). MicroPDF417 Barcode-Absendername (optional Feld für den Structured Append‑Modus) |
| [MacroPdf417Terminator](../../aspose.barcode.generation/pdf417parameters/macropdf417terminator/) { get; set; } | Wird verwendet, um dem Encoder mitzuteilen, ob ein Macro PDF417 Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Wird nur für Macro PDF417 angewendet. |
| [MacroPdf417TimeStamp](../../aspose.barcode.generation/pdf417parameters/macropdf417timestamp/) { get; set; } | MacroPdf417 Barcode-Zeitstempel (optional Feld). MicroPDF417 Barcode-Zeitstempel (optional Feld für den Structured Append‑Modus) |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | Zeilenanzahl. |
| [Truncate](../../aspose.barcode.generation/pdf417parameters/truncate/) { get; set; } | Gibt an, ob der Pdf417‑Symboltyp des BarCode gekürzt ist (zur Platzersparnis). Auch bekannt als CompactPDF417. Der rechte Zeilenindikator und das rechte Stopp‑Muster werden in diesem Modus entfernt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `Pdf417Parameters` zurück. |

## Beispiele

Diese Beispiele zeigen, wie man UCC/EAN‑128‑Nicht‑Verknüpfungs‑Modi in GS1MicroPdf417 kodiert.

```csharp
[C#]
//Kodiert den GS1 UCC/EAN‑128‑Nicht‑Verknüpfungs‑Modus 905 mit KI 01 (GTIN).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Kodiert die GS1 UCC/EAN‑128‑Nicht‑Verknüpfungs‑Modi 903, 904 mit beliebiger KI.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


