---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

PDF417-Parameter. Enthält PDF417-, MacroPDF417-, MicroPDF417- und GS1MicroPdf417-Parameter.<br/>            MacroPDF417 erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional.<br/>            MicroPDF417 im Structured-Append-Modus (wie im MacroPDF417-Modus) erfordert zwei Felder: Pdf417MacroFileID und Pdf417MacroSegmentID. Alle anderen Felder sind optional.

Der Typ Pdf417Parameters stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| encode_mode | Identifiziert den Pdf417-Codierungsmodus. <br/>            Standardwert: Auto. |
| error_level | Ruft den Symbologie‑Typ von Pdf417 für das Fehlerkorrekturlevel des BarCodes ab oder legt ihn fest<br/>            im Bereich von level0 bis level8, level0 bedeutet keine Fehlerkorrekturinformationen,<br/>            level8 bedeutet die beste Fehlerkorrektur, was ein größeres Bild bedeutet. |
| truncate | Gibt an, ob der Pdf417‑Symbologie‑Typ des BarCodes gekürzt ist (zur Platzersparnis). <br/>            Auch bekannt als CompactPDF417. Der rechte Zeilenindikator und das rechte Stopp‑Muster werden in diesem Modus entfernt. |
| Spalten | Anzahl der Spalten. |
| Zeilen | Anzahl der Zeilen. |
| aspect_ratio | Höhen‑/Breiten‑Verhältnis des 2D‑Barcode‑Moduls. |
| macro_pdf_417_file_id | Datei-ID des MacroPdf417-Barcodes (erforderliches Feld).<br/>            Datei-ID des MicroPDF417-Barcodes (erforderliches Feld für den Structured Append‑Modus) |
| macro_pdf_417_segment_id | Segment-ID des MacroPdf417-Barcodes (erforderliches Feld), die von 0 bis MacroSegmentsCount - 1 reicht.<br/>            Segment-ID des MicroPDF417-Barcodes (erforderliches Feld für den Structured Append‑Modus) |
| macro_pdf_417_segments_count | Anzahl der Segmente des MacroPdf417-Barcodes (optionales Feld).<br/>            Anzahl der Segmente des MicroPDF417-Barcodes (optionales Feld für den Structured Append‑Modus) |
| macro_pdf_417_file_name | Dateiname des MacroPdf417-Barcodes (optionales Feld).<br/>            Dateiname des MicroPDF417-Barcodes (optionales Feld für den Structured Append‑Modus) |
| macro_pdf_417_time_stamp | Zeitstempel des MacroPdf417-Barcodes (optionales Feld).<br/>            Zeitstempel des MicroPDF417-Barcodes (optionales Feld für den Structured Append‑Modus) |
| macro_pdf_417_sender | Absendername des MacroPdf417-Barcodes (optionales Feld).<br/>            Absendername des MicroPDF417-Barcodes (optionales Feld für den Structured Append‑Modus) |
| macro_pdf_417_addressee | Empfängername des MacroPdf417-Barcodes (optionales Feld).<br/>            Empfängername des MicroPDF417-Barcodes (optionales Feld für den Structured Append‑Modus) |
| macro_pdf_417_file_size | MacroPdf417-Dateigröße (optional).<br/>            MicroPDF417-Dateigröße (optional für den Structured Append‑Modus)<br/>            Das Feld für die Dateigröße enthält die Größe in Bytes der gesamten Quelldatei. |
| macro_pdf_417_checksum | MacroPdf417-Barcode-Prüfsumme (optional).<br/>            MicroPDF417-Barcode-Prüfsumme (optional für den Structured Append‑Modus)<br/>            Das Prüfsummenfeld enthält den Wert der 16‑Bit‑(2‑Byte‑) CRC‑Prüfsumme unter Verwendung des CCITT‑16‑Polynoms. x^16 + x^12 + x^5 + 1 |
| eci_encoding | Extended Channel Interpretation Identifiers. Es wird verwendet, um dem Barcode‑Leser Details mitzuteilen<br/>            über die verwendeten Referenzen zur Kodierung der Daten im Symbol. Nicht angewendet für Macro PDF417‑Textfelder.<br/>            Die aktuelle Implementierung umfasst alle bekannten Zeichensatzkodierungen. |
| macro_pdf_417eci_encoding | Extended Channel Interpretation Identifiers. Gilt für Macro PDF417‑Textfelder. |
| macro_pdf_417_terminator | Wird verwendet, um dem Encoder mitzuteilen, ob ein Macro‑PDF417‑Terminator (Codewort 922) zum Segment hinzugefügt werden soll.<br/>            Wird nur für Macro PDF417 angewendet. |
| is_reader_initialization | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten<br/>            als Programmierung für die Leserinitialisierung zu interpretieren. |
| macro_characters | Macro Characters 05 und 06 Werte werden verwendet, um eine kompaktere Kodierung in speziellen Modi zu erhalten.<br/>            Kann nur mit MicroPdf417 verwendet werden und kodiert die Modi 916 und 917 von MicroPdf417<br/>            Standardwert: MacroCharacters.None. |
| is_linked | Definiert verknüpfte Modi mit GS1MicroPdf417, MicroPdf417 und Pdf417 Barcodes<br/>            Mit GS1MicroPdf417‑Symbologie werden die Modi 906, 907, 912, 913, 914, 915 „Linked“ UCC/EAN-128 kodiert<br/>            Mit MicroPdf417‑ und Pdf417‑Symbologien wird das Link‑Flag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert |
| is_code_128_emulation | Kann nur mit MicroPdf417 verwendet werden und kodiert Code‑128‑Emulationsmodi<br/>            Kann FNC1 in der zweiten Positions‑Modi 908 und 909 kodieren, außerdem können 910 und 911 kodiert werden, die lediglich anzeigen, dass ein erkanntes MicroPdf417 als Code 128 interpretiert werden kann |

### Siehe auch

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

