---
title: "Aspose::BarCode::Generation::Pdf417Parameters Klasse"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::Pdf417Parameters Klasse. PDF417‑Parameter. Enthält PDF417-, MacroPDF417-, MicroPDF417‑ und GS1MicroPdf417‑Parameter. MacroPDF417 erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. MicroPDF417 im Structured‑Append‑Modus (gleichbedeutend mit dem MacroPDF417‑Modus) erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional in C++."
type: docs
weight: 4000
url: /de/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


PDF417-Parameter. Enthält Parameter für PDF417, MacroPDF417, MicroPDF417 und GS1MicroPdf417. MacroPDF417 erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional. MicroPDF417 im Structured‑Append‑Modus (gleich wie MacroPDF417‑Modus) erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional.

```cpp
class Pdf417Parameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [get_Columns](./get_columns/)() const | Spaltenanzahl. |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details über die verwendeten Referenzen zur Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro‑PDF417‑Textfelder. Die aktuelle Implementierung umfasst alle bekannten Zeichensatzkodierungen. |
| [get_EncodeMode](./get_encodemode/)() const | Identifiziert den Pdf417‑Kodiermodus. Standardwert: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Ermittelt den Pdf417‑Symboltyp des Fehlerkorrektur‑Levels von [BarCode](../../aspose.barcode/), das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Information, level8 bedeutet die beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in der zweiten Positions‑Modi 908 und 909 kodieren, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann. |
| [get_IsLinked](./get_islinked/)() const | Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417‑ und Pdf417‑Barcodes. Mit der GS1MicroPdf417‑Symbolik werden die „Linked“-UCC/EAN‑128‑Modi 906, 907, 912, 913, 914, 915 kodiert. Mit den MicroPdf417‑ und Pdf417‑Symboliken wird das Verknüpfungs‑Flag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [get_MacroCharacters](./get_macrocharacters/)() const | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. Kann nur mit MicroPdf417 verwendet werden und kodiert die MicroPdf417‑Modi 916 und 917. Standardwert: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | MacroPdf417‑Barcode‑Empfängername (optionales Feld). MicroPDF417‑Barcode‑Empfängername (optionales Feld für den Structured‑Append‑Modus). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | MacroPdf417‑Barcode‑Prüfsumme (optionales Feld). MicroPDF417‑Barcode‑Prüfsumme (optionales Feld für den Structured‑Append‑Modus). Das Prüfsummenfeld enthält den Wert der 16‑Bit‑(2‑Byte‑)CRC‑Prüfsumme unter Verwendung des CCITT‑16‑Polynoms. x^16 + x^12 + x^5 + 1 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Extended Channel Interpretation‑Bezeichner. Gilt für Macro‑PDF417‑Textfelder. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417‑Barcode‑Datei‑ID (erforderliches Feld). MicroPDF417‑Barcode‑Datei‑ID (erforderliches Feld für den Structured‑Append‑Modus). |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | MacroPdf417‑Barcode‑Dateiname (optionales Feld). MicroPDF417‑Barcode‑Dateiname (optionales Feld für den Structured‑Append‑Modus). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | MacroPdf417‑Dateigröße (optionales Feld). MicroPDF417‑Dateigröße (optionales Feld für den Structured‑Append‑Modus). Das Dateigrößenfeld enthält die Größe in Bytes der gesamten Quelldatei. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | Segment-ID des MacroPdf417-Barcodes (erforderliches Feld), die von 0 bis MacroSegmentsCount - 1 reicht. Segment-ID des MicroPDF417-Barcodes (erforderliches Feld für den Structured Append‑Modus) |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Anzahl der Segmente des MacroPdf417-Barcodes (optional). Anzahl der Segmente des MicroPDF417-Barcodes (optional für den Structured Append‑Modus) |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Absendername des MacroPdf417-Barcodes (optional). Absendername des MicroPDF417-Barcodes (optional für den Structured Append‑Modus) |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Wird verwendet, um dem Encoder mitzuteilen, ob dem Segment ein Macro PDF417 Terminator (Codewort 922) hinzugefügt werden soll. Wird nur für Macro PDF417 angewendet. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Zeitstempel des MacroPdf417-Barcodes (optional). Zeitstempel des MicroPDF417-Barcodes (optional für den Structured Append‑Modus) |
| [get_Rows](./get_rows/)() const | Zeilenanzahl. |
| [get_Truncate](./get_truncate/)() const | Ob der Pdf417‑Symboltyp von [BarCode](../../aspose.barcode/) gekürzt ist (zur Platzersparnis). Auch bekannt als CompactPDF417. Der rechte Zeilenindikator und das rechte Stopp‑Muster werden in diesem Modus entfernt. |
| [set_AspectRatio](./set_aspectratio/)(float) | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [set_Columns](./set_columns/)(int32_t) | Spaltenanzahl. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details über die verwendeten Referenzen zur Kodierung der Daten im Symbol mitzuteilen. Nicht angewendet für Macro‑PDF417‑Textfelder. Die aktuelle Implementierung umfasst alle bekannten Zeichensatzkodierungen. |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Identifiziert den Pdf417‑Kodiermodus. Standardwert: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | Legt das Fehlerkorrektur‑Level des Pdf417‑Symboltyps von [BarCode](../../aspose.barcode/) fest, das von level0 bis level8 reicht; level0 bedeutet keine Fehlerkorrektur‑Informationen, level8 bedeutet die beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi. Kann FNC1 in der zweiten Positions‑Modi 908 und 909 kodieren, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass das erkannte MicroPdf417 als Code 128 interpretiert werden kann. |
| [set_IsLinked](./set_islinked/)(bool) | Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417‑ und Pdf417‑Barcodes. Mit der GS1MicroPdf417‑Symbolik werden die „Linked“-UCC/EAN‑128‑Modi 906, 907, 912, 913, 914, 915 kodiert. Mit den MicroPdf417‑ und Pdf417‑Symboliken wird das Verknüpfungs‑Flag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Die Werte der Makro‑Zeichen 05 und 06 werden verwendet, um in speziellen Modi eine kompaktere Kodierung zu erhalten. Kann nur mit MicroPdf417 verwendet werden und kodiert die MicroPdf417‑Modi 916 und 917. Standardwert: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | MacroPdf417‑Barcode‑Empfängername (optionales Feld). MicroPDF417‑Barcode‑Empfängername (optionales Feld für den Structured‑Append‑Modus). |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | MacroPdf417‑Barcode‑Prüfsumme (optionales Feld). MicroPDF417‑Barcode‑Prüfsumme (optionales Feld für den Structured‑Append‑Modus). Das Prüfsummenfeld enthält den Wert der 16‑Bit‑(2‑Byte‑)CRC‑Prüfsumme unter Verwendung des CCITT‑16‑Polynoms. x^16 + x^12 + x^5 + 1 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Extended Channel Interpretation‑Bezeichner. Gilt für Macro‑PDF417‑Textfelder. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | MacroPdf417‑Barcode‑Datei‑ID (erforderliches Feld). MicroPDF417‑Barcode‑Datei‑ID (erforderliches Feld für den Structured‑Append‑Modus). |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | MacroPdf417‑Barcode‑Dateiname (optionales Feld). MicroPDF417‑Barcode‑Dateiname (optionales Feld für den Structured‑Append‑Modus). |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | MacroPdf417‑Dateigröße (optionales Feld). MicroPDF417‑Dateigröße (optionales Feld für den Structured‑Append‑Modus). Das Dateigrößenfeld enthält die Größe in Bytes der gesamten Quelldatei. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | Segment-ID des MacroPdf417-Barcodes (erforderliches Feld), die von 0 bis MacroSegmentsCount - 1 reicht. Segment-ID des MicroPDF417-Barcodes (erforderliches Feld für den Structured Append‑Modus) |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | Anzahl der Segmente des MacroPdf417-Barcodes (optional). Anzahl der Segmente des MicroPDF417-Barcodes (optional für den Structured Append‑Modus) |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | Absendername des MacroPdf417-Barcodes (optional). Absendername des MicroPDF417-Barcodes (optional für den Structured Append‑Modus) |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | Wird verwendet, um dem Encoder mitzuteilen, ob dem Segment ein Macro PDF417 Terminator (Codewort 922) hinzugefügt werden soll. Wird nur für Macro PDF417 angewendet. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | Zeitstempel des MacroPdf417-Barcodes (optional). Zeitstempel des MicroPDF417-Barcodes (optional für den Structured Append‑Modus) |
| [set_Rows](./set_rows/)(int32_t) | Zeilenanzahl. |
| [set_Truncate](./set_truncate/)(bool) | Ob der Pdf417‑Symboltyp von [BarCode](../../aspose.barcode/) gekürzt ist (zur Platzersparnis). Auch bekannt als CompactPDF417. Der rechte Zeilenindikator und das rechte Stopp‑Muster werden in diesem Modus entfernt. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [Pdf417Parameters](./) zurück. |
## Hinweise


Diese Beispiele zeigen, wie man nicht verknüpfte UCC/EAN-128‑Modi in GS1MicroPdf417 kodiert.
```cpp
[C#]
//Kodiert den nicht verknüpften Modus 905 von GS1 UCC/EAN-128 mit AI 01 (GTIN).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Kodiert die nicht verknüpften Modi 903, 904 von GS1 UCC/EAN-128 mit beliebigem AI.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
