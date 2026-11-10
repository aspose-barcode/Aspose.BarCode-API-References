---
title: "Klasse Pdf417ParametersUI"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Windows.Forms.Pdf417ParametersUI‑Klasse. UI‑Wrapper für die Pdf417Parameters‑Klasse"
type: docs
weight: 1860
url: /de/net/aspose.barcode.windows.forms/pdf417parametersui/
---
## Pdf417ParametersUI class

UI‑Wrapper für die [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/)‑Klasse.

```csharp
public class Pdf417ParametersUI
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/pdf417parametersui/aspectratio/) { get; set; } | Höhen/Breiten-Verhältnis des 2D‑BarCode‑Moduls. |
| [Columns](../../aspose.barcode.windows.forms/pdf417parametersui/columns/) { get; set; } | Spaltenanzahl. |
| [ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/eciencoding/) { get; set; } | Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro‑PDF417‑Textfelder. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. |
| [EncodeMode](../../aspose.barcode.windows.forms/pdf417parametersui/encodemode/) { get; set; } | Pdf417‑Symboltyp des Kodierungsmodus von BarCode. Standardwert: Pdf417EncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.windows.forms/pdf417parametersui/errorlevel/) { get; set; } | Liest oder setzt den Pdf417‑Symboltyp des Fehlerkorrektur‑Levels von BarCode, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| [IsCode128Emulation](../../aspose.barcode.windows.forms/pdf417parametersui/iscode128emulation/) { get; set; } | Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in zweiter Position in den Modi 908 und 909 kodieren, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann. |
| [IsLinked](../../aspose.barcode.windows.forms/pdf417parametersui/islinked/) { get; set; } | Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417- und Pdf417‑Barcodes. Mit der GS1MicroPdf417‑Symbolik werden die „Linked“ UCC/EAN‑128‑Modi 906, 907, 912, 913, 914, 915 kodiert. Mit den Symboliken MicroPdf417 und Pdf417 wird das Verknüpfungsflag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert. |
| [IsReaderInitialization](../../aspose.barcode.windows.forms/pdf417parametersui/isreaderinitialization/) { get; set; } | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [MacroCharacters](../../aspose.barcode.windows.forms/pdf417parametersui/macrocharacters/) { get; set; } | Macro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. Können nur mit MicroPdf417 verwendet werden und kodieren die Modi 916 und 917 von MicroPdf417. Standardwert: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417addressee/) { get; set; } | MacroPdf417‑Barcode‑Empfängername (optional). MicroPDF417‑Barcode‑Empfängername (optional für den Structured Append‑Modus). |
| [MacroPdf417Checksum](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417checksum/) { get; set; } | MacroPdf417 Barcode-Prüfsumme (optional Feld). MicroPDF417 Barcode-Prüfsumme (optional Feld für den Structured Append‑Modus) Das Prüfsummenfeld enthält den Wert der 16‑Bit (2 Byte) CRC‑Prüfsumme unter Verwendung des CCITT‑16‑Polynoms. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417eciencoding/) { get; set; } | Extended Channel Interpretation‑Kennungen. Gilt für Macro‑PDF417‑Textfelder. |
| [MacroPdf417FileID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417fileid/) { get; set; } | Liest oder setzt die Datei‑ID des Macro‑Pdf417 Barcodes. Wird für MacroPdf417 verwendet. |
| [MacroPdf417FileName](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filename/) { get; set; } | MacroPdf417 Barcode-Dateiname (optional Feld). MicroPDF417 Barcode-Dateiname (optional Feld für den Structured Append‑Modus) |
| [MacroPdf417FileSize](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filesize/) { get; set; } | MacroPdf417 Dateigröße (optional Feld). MicroPDF417 Dateigröße (optional Feld für den Structured Append‑Modus) Das Feld für die Dateigröße enthält die Größe in Bytes der gesamten Quelldatei. |
| [MacroPdf417SegmentID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentid/) { get; set; } | Liest oder setzt die Segment‑ID des Macro‑Pdf417 Barcodes, die von 0 bis MacroSegmentsCount - 1 reicht. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentscount/) { get; set; } | Liest oder setzt die Anzahl der Segmente des Macro‑Pdf417 Barcodes. |
| [MacroPdf417Sender](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417sender/) { get; set; } | MacroPdf417 Barcode-Absendername (optional Feld). MicroPDF417 Barcode-Absendername (optional Feld für den Structured Append‑Modus) |
| [MacroPdf417Terminator](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417terminator/) { get; set; } | Wird verwendet, um dem Encoder mitzuteilen, ob ein Macro PDF417 Terminator (Codewort 922) zum Segment hinzugefügt werden soll. Wird nur für Macro PDF417 angewendet. |
| [MacroPdf417TimeStamp](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417timestamp/) { get; set; } | MacroPdf417 Barcode-Zeitstempel (optional Feld). MicroPDF417 Barcode-Zeitstempel (optional Feld für den Structured Append‑Modus) |
| [Rows](../../aspose.barcode.windows.forms/pdf417parametersui/rows/) { get; set; } | Zeilenanzahl. |
| [Truncate](../../aspose.barcode.windows.forms/pdf417parametersui/truncate/) { get; set; } | Ob der Pdf417‑Symboltyp des Barcodes gekürzt ist (zur Platzersparnis). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/pdf417parametersui/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/) zurück. |

### Siehe auch

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


