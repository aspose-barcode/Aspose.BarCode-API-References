---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode voor Python via .NET API-referentie"
description: 
type: docs
url: /nl/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

PDF417-parameters. Bevat PDF417-, MacroPDF417-, MicroPDF417- en GS1MicroPdf417-parameters.<br/>            MacroPDF417 vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel.<br/>            MicroPDF417 in Structured Append-modus (hetzelfde als MacroPDF417-modus) vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel.

Het Pdf417Parameters-type biedt de volgende leden:
## Properties
| Name | Beschrijving |
| :- | :- |
| encode_mode | Identificeert de Pdf417-coderingsmodus. <br/>            Standaardwaarde: Auto. |
| error_level | Haalt het Pdf417-symbooltype van het foutcorrigerniveau van BarCode op of stelt dit in<br/>            variërend van level0 tot level8, level0 betekent geen foutcorrigatie-informatie,<br/>            level8 betekent de beste foutcorrigatie, wat een grotere afbeelding betekent. |
| truncate | Geeft aan of het Pdf417-symbooltype van BarCode is ingekort (om ruimte te besparen). <br/>            Ook bekend als CompactPDF417. De rechterrij-indicator en het rechterstoppatroon worden in deze modus verwijderd. |
| kolommen | Aantal kolommen. |
| rijen | Aantal rijen. |
| aspect_ratio | Hoogte/breedteverhouding van de 2D BarCode-module. |
| macro_pdf_417_file_id | MacroPdf417-barcodebestand-ID (verplicht veld).<br/>            MicroPDF417-barcodebestand-ID (verplicht veld voor Structured Append-modus) |
| macro_pdf_417_segment_id | MacroPdf417-barcodesegment-ID (verplicht veld), beginnend bij 0 tot MacroSegmentsCount - 1.<br/>            MicroPDF417-barcodesegment-ID (verplicht veld voor Structured Append-modus) |
| macro_pdf_417_segments_count | MacroPdf417-aantal barcode-segmenten (optioneel veld).<br/>            MicroPDF417-aantal barcode-segmenten (optioneel veld voor Structured Append-modus) |
| macro_pdf_417_file_name | MacroPdf417-barcodebestandsnaam (optioneel veld).<br/>            MicroPDF417-barcodebestandsnaam (optioneel veld voor Structured Append-modus) |
| macro_pdf_417_time_stamp | MacroPdf417-barcode tijdstempel (optioneel veld).<br/>            MicroPDF417-barcode tijdstempel (optioneel veld voor Structured Append-modus) |
| macro_pdf_417_sender | MacroPdf417-barcode afzendernaam (optioneel veld).<br/>            MicroPDF417-barcode afzendernaam (optioneel veld voor Structured Append-modus) |
| macro_pdf_417_addressee | MacroPdf417-barcode geadresseerde naam (optioneel veld).<br/>            MicroPDF417-barcode geadresseerde naam (optioneel veld voor Structured Append-modus) |
| macro_pdf_417_file_size | MacroPdf417 bestandsgrootte (optioneel veld).<br/>            MicroPDF417 bestandsgrootte (optioneel veld voor Structured Append-modus)<br/>            Het bestandsgrootteveld bevat de grootte in bytes van het volledige bronbestand. |
| macro_pdf_417_checksum | MacroPdf417 barcode checksum (optioneel veld).<br/>            MicroPDF417 barcode checksum (optioneel veld voor Structured Append-modus)<br/>            Het checksumveld bevat de waarde van de 16‑bit (2 bytes) CRC‑checksum met de CCITT‑16‑polynoom. x^16 + x^12 + x^5 + 1 |
| eci_encoding | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven<br/>            over de gebruikte referenties voor het coderen van de gegevens in het symbool. Niet toegepast op Macro PDF417-tekstvelden.<br/>            De huidige implementatie bevat alle bekende charset‑coderingen. |
| macro_pdf_417eci_encoding | Extended Channel Interpretation Identifiers. Geldt voor Macro PDF417-tekstvelden. |
| macro_pdf_417_terminator | Wordt gebruikt om de encoder te vertellen of de Macro PDF417-terminator (codewoord 922) aan het segment moet worden toegevoegd. <br/>            Alleen toegepast voor Macro PDF417. |
| is_reader_initialization | Wordt gebruikt om de lezer te instrueren de gegevens binnen het symbool te interpreteren<br/>            als programmering voor lezerinitialisatie. |
| macro_characters | Macro Characters 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi.<br/>            Kan alleen worden gebruikt met MicroPdf417 en codeert 916 en 917 MicroPdf417-modus<br/>            Standaardwaarde: MacroCharacters.None. |
| is_linked | Definieert gekoppelde modi met GS1MicroPdf417, MicroPdf417 en Pdf417 barcodes<br/>            Met GS1MicroPdf417-symbologie codeert 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128-modus<br/>            Met MicroPdf417- en Pdf417-symbologie codeert 918 koppelingsvlag naar geassocieerde lineaire component anders dan een EAN.UCC |
| is_code_128_emulation | Kan alleen worden gebruikt met MicroPdf417 en codeert Code 128-emulatiemodi<br/>            Kan FNC1 coderen in tweede‑positie‑modi 908 en 909, en kan ook 910 en 911 coderen, die alleen aangeven dat een herkende MicroPdf417 kan worden geïnterpreteerd als Code 128 |

### Zie ook

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

