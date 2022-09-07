---
title: Pdf417Parameters
second_title: Aspose.BarCode für .NET-API-Referenz
description: PDF417-Parameter. Enthält PDF417- MacroPDF417- und MicroPDF417-Parameter. MacroPDF417 erfordert zwei Felder Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. MicroPDF417 im strukturierten Anhängemodus wie im MacroPDF417-Modus erfordert zwei Felder Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional.
type: docs
weight: 860
url: /de/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417-Parameter. Enthält PDF417-, MacroPDF417- und MicroPDF417-Parameter. MacroPDF417 erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. MicroPDF417 im strukturierten Anhängemodus (wie im MacroPDF417-Modus) erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional.

```csharp
public class Pdf417Parameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio) { get; set; } | Höhen-/Breitenverhältnis des 2D-BarCode-Moduls. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation) { get; set; } | Funktionscodewort für Code 128-Emulation. Gilt nur für MicroPDF417. Für PDF417- und MacroPDF417-Barcodes ignoriert. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding) { get; set; } | Liest oder setzt die Kodierung von Codetext. Standardwert: UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns) { get; set; } | Spaltenanzahl. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization) { get; set; } | Wird verwendet, um das Lesegerät anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Initialisierung des Lesegeräts zu interpretieren. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode) { get; set; } | Pdf417-Symboltyp des Komprimierungsmodus von BarCode. Standardwert: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding) { get; set; } | Erweiterte Kanalinterpretationskennungen. Es wird verwendet, um dem Strichcodeleser details über die verwendeten Referenzen zur Codierung der Daten im Symbol zu informieren. Wird nicht für Macro PDF417-Textfelder angewendet. Die aktuelle Implementierung umfasst alle bekannten Zeichensatzcodierungen. |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel) { get; set; } | Ermittelt oder setzt den Pdf417-Symbologietyp der Fehlerkorrektur von BarCode. level reicht von level0 bis level8, level0 bedeutet keine Fehlerkorrekturinformationen, level8 bedeutet beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee) { get; set; } | MacroPdf417-Barcode-Adressatenname (optionales Feld). MicroPDF417-Barcode-Adressatenname (optionales Feld für strukturiertes Anhängen) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum) { get; set; } | MacroPdf417-Barcode-Prüfsumme (optionales Feld). MicroPDF417-Barcode-Prüfsumme (optionales Feld für strukturiertes Anhängen) Das Prüfsummenfeld enthält den Wert der 16-Bit (2 Byte) CRC-Prüfsumme unter Verwendung des CCITT-16-Polynoms. x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding) { get; set; } | Erweiterte Kanalinterpretationskennungen. Gilt für Macro PDF417-Textfelder. |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid) { get; set; } | Datei-ID des MacroPdf417-Barcodes (erforderliches Feld). MicroPDF417-Barcode-Datei-ID (erforderliches Feld für den strukturierten Anhängemodus) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename) { get; set; } | MacroPdf417-Barcode-Dateiname (optionales Feld). MicroPDF417-Barcode-Dateiname (optionales Feld für den strukturierten Anhängemodus) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize) { get; set; } | MacroPdf417-Dateigröße (optionales Feld). MicroPDF417-Dateigröße (optionales Feld für den strukturierten Anhängemodus) Das Dateigrößenfeld enthält die Größe der gesamten Quelldatei in Byte. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid) { get; set; } | Segment-ID des MacroPdf417-Barcodes (erforderliches Feld), die bei 0 beginnt, bis MacroSegmentsCount - 1. Segment-ID des MicroPDF417-Barcodes (erforderliches Feld für den strukturierten Anhängemodus) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount) { get; set; } | Anzahl der MacroPdf417-Barcodesegmente (optionales Feld). Anzahl der MicroPDF417-Barcodesegmente (optionales Feld für den strukturierten Anhängemodus) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender) { get; set; } | MacroPdf417-Barcode-Absendername (optionales Feld). MicroPDF417-Barcode-Absendername (optionales Feld für strukturiertes Anhängen) |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp) { get; set; } | MacroPdf417-Barcode-Zeitstempel (optionales Feld). MicroPDF417-Barcode-Zeitstempel (optionales Feld für den strukturierten Anhängemodus) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate) { get; set; } | Ob der Pdf417-Symbologietyp des Barcodes abgeschnitten wird (um Platz zu sparen). Auch bekannt als CompactPDF417. Die Anzeige für die rechte Reihe und das rechte Stoppmuster werden in diesem Modus entfernt. |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows) { get; set; } | Zeilenanzahl. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring)() | Gibt eine für Menschen lesbare Zeichenfolgendarstellung davon zurück[`Pdf417Parameters`](../pdf417parameters) . |

### Siehe auch

* namensraum [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* Montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
