---
title: "Aspose::BarCode::Generation::Pdf417Parameters klasse"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::Pdf417Parameters klasse. PDF417‑parameters. Bevat PDF417-, MacroPDF417-, MicroPDF417- en GS1MicroPdf417‑parameters. MacroPDF417 vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel. MicroPDF417 in Structured Append‑modus (hetzelfde als MacroPDF417‑modus) vereist twee velden: Pdf917MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel in C++."
type: docs
weight: 4000
url: /nl/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


PDF417-parameters. Bevat PDF417, MacroPDF417, MicroPDF417 en GS1MicroPdf417 parameters. MacroPDF417 vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel. MicroPDF417 in Structured Append-modus (hetzelfde als MacroPDF417-modus) vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel.

```cpp
class Pdf417Parameters : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Hoogte/breedte‑verhouding van 2D [BarCode](../../aspose.barcode/) module. |
| [get_Columns](./get_columns/)() const | Aantal kolommen. |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation‑identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. Niet toegepast op Macro PDF417‑tekstvelden. De huidige implementatie bestaat uit alle algemeen bekende tekenset‑coderingen. |
| [get_EncodeMode](./get_encodemode/)() const | Identificeert de Pdf417‑codeermodus. Standaardwaarde: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Haalt het Pdf417‑symbooltype op van het foutcorrectieniveau van [BarCode](../../aspose.barcode/), variërend van level0 tot level8; level0 betekent geen foutcorrectie‑informatie, level8 betekent de beste foutcorrectie, wat een grotere afbeelding betekent. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Kan alleen worden gebruikt met MicroPdf417 en codeert Code‑128‑emulatiemodi. Kan FNC1 coderen op de tweede positie in de modi 908 en 909, en kan ook 910 en 911 coderen, die alleen aangeven dat herkende MicroPdf417 kan worden geïnterpreteerd als Code 128. |
| [get_IsLinked](./get_islinked/)() const | Definieert gekoppelde modi met GS1MicroPdf417-, MicroPdf417- en Pdf417‑barcodes. Met GS1MicroPdf417‑symboolcode worden 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN‑128‑modi gecodeerd. Met MicroPdf417‑ en Pdf417‑symboolcodes wordt 918‑koppelingsvlag naar een geassocieerd lineair component anders dan een EAN.UCC gecodeerd. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [get_MacroCharacters](./get_macrocharacters/)() const | Macro‑karakters 05 en 06 worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met MicroPdf417 en codeert 916‑ en 917‑MicroPdf417‑modi. Standaardwaarde: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | MacroPdf417‑barcode geadresseerde naam (optioneel veld). MicroPDF417‑barcode geadresseerde naam (optioneel veld voor Structured Append‑modus). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | MacroPdf417‑barcode controlesom (optioneel veld). MicroPDF417‑barcode controlesom (optioneel veld voor Structured Append‑modus). Het controlesom‑veld bevat de waarde van de 16‑bit (2 bytes) CRC‑controlesom met de CCITT‑16‑polynoom. x^16 + x^12 + x^5 + 1 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Extended Channel Interpretation‑identifiers. Van toepassing op Macro PDF417‑tekstvelden. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417‑barcode bestand‑ID (verplicht veld). MicroPDF417‑barcode bestand‑ID (verplicht veld voor Structured Append‑modus). |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | MacroPdf417‑barcode bestandsnaam (optioneel veld). MicroPDF417‑barcode bestandsnaam (optioneel veld voor Structured Append‑modus). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | MacroPdf417‑bestandsgrootte (optioneel veld). MicroPDF417‑bestandsgrootte (optioneel veld voor Structured Append‑modus). Het bestandsgrootte‑veld bevat de grootte in bytes van het volledige bronbestand. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | MacroPdf417‑barcode segment‑ID (verplicht veld), beginnend bij 0 tot MacroSegmentsCount - 1. MicroPDF417‑barcode segment‑ID (verplicht veld voor Structured Append‑modus). |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | MacroPdf417‑barcode segmentenaantal (optioneel veld). MicroPDF417‑barcode segmentenaantal (optioneel veld voor Structured Append‑modus). |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | MacroPdf417‑barcode afzendernaam (optioneel veld). MicroPDF417‑barcode afzendernaam (optioneel veld voor Structured Append‑modus). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. Alleen van toepassing op Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | MacroPdf417‑barcode tijdstempel (optioneel veld). MicroPDF417‑barcode tijdstempel (optioneel veld voor Structured Append‑modus). |
| [get_Rows](./get_rows/)() const | Aantal rijen. |
| [get_Truncate](./get_truncate/)() const | Of het Pdf417‑symbooltype van [BarCode](../../aspose.barcode/) is ingekort (om ruimte te besparen). Ook bekend als CompactPDF417. De rechter rij‑indicator en het rechter stop‑patroon worden in deze modus verwijderd. |
| [set_AspectRatio](./set_aspectratio/)(float) | Hoogte/breedte‑verhouding van 2D [BarCode](../../aspose.barcode/) module. |
| [set_Columns](./set_columns/)(int32_t) | Aantal kolommen. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation‑identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. Niet toegepast op Macro PDF417‑tekstvelden. De huidige implementatie bestaat uit alle algemeen bekende tekenset‑coderingen. |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Identificeert de Pdf417‑codeermodus. Standaardwaarde: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | Stelt het Pdf417-symbooltype van de foutcorrectieniveau van [BarCode](../../aspose.barcode/) in, variërend van level0 tot level8; level0 betekent geen foutcorrectie-informatie, level8 betekent de beste foutcorrectie, wat een grotere afbeelding betekent. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | Kan alleen worden gebruikt met MicroPdf417 en codeert Code‑128‑emulatiemodi. Kan FNC1 coderen op de tweede positie in de modi 908 en 909, en kan ook 910 en 911 coderen, die alleen aangeven dat herkende MicroPdf417 kan worden geïnterpreteerd als Code 128. |
| [set_IsLinked](./set_islinked/)(bool) | Definieert gekoppelde modi met GS1MicroPdf417-, MicroPdf417- en Pdf417‑barcodes. Met GS1MicroPdf417‑symboolcode worden 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN‑128‑modi gecodeerd. Met MicroPdf417‑ en Pdf417‑symboolcodes wordt 918‑koppelingsvlag naar een geassocieerd lineair component anders dan een EAN.UCC gecodeerd. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Macro‑karakters 05 en 06 worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met MicroPdf417 en codeert 916‑ en 917‑MicroPdf417‑modi. Standaardwaarde: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | MacroPdf417‑barcode geadresseerde naam (optioneel veld). MicroPDF417‑barcode geadresseerde naam (optioneel veld voor Structured Append‑modus). |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | MacroPdf417‑barcode controlesom (optioneel veld). MicroPDF417‑barcode controlesom (optioneel veld voor Structured Append‑modus). Het controlesom‑veld bevat de waarde van de 16‑bit (2 bytes) CRC‑controlesom met de CCITT‑16‑polynoom. x^16 + x^12 + x^5 + 1 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Extended Channel Interpretation‑identifiers. Van toepassing op Macro PDF417‑tekstvelden. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | MacroPdf417‑barcode bestand‑ID (verplicht veld). MicroPDF417‑barcode bestand‑ID (verplicht veld voor Structured Append‑modus). |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | MacroPdf417‑barcode bestandsnaam (optioneel veld). MicroPDF417‑barcode bestandsnaam (optioneel veld voor Structured Append‑modus). |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | MacroPdf417‑bestandsgrootte (optioneel veld). MicroPDF417‑bestandsgrootte (optioneel veld voor Structured Append‑modus). Het bestandsgrootte‑veld bevat de grootte in bytes van het volledige bronbestand. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | MacroPdf417‑barcode segment‑ID (verplicht veld), beginnend bij 0 tot MacroSegmentsCount - 1. MicroPDF417‑barcode segment‑ID (verplicht veld voor Structured Append‑modus). |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | MacroPdf417‑barcode segmentenaantal (optioneel veld). MicroPDF417‑barcode segmentenaantal (optioneel veld voor Structured Append‑modus). |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | MacroPdf417‑barcode afzendernaam (optioneel veld). MicroPDF417‑barcode afzendernaam (optioneel veld voor Structured Append‑modus). |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. Alleen van toepassing op Macro PDF417. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | MacroPdf417‑barcode tijdstempel (optioneel veld). MicroPDF417‑barcode tijdstempel (optioneel veld voor Structured Append‑modus). |
| [set_Rows](./set_rows/)(int32_t) | Aantal rijen. |
| [set_Truncate](./set_truncate/)(bool) | Of het Pdf417‑symbooltype van [BarCode](../../aspose.barcode/) is ingekort (om ruimte te besparen). Ook bekend als CompactPDF417. De rechter rij‑indicator en het rechter stop‑patroon worden in deze modus verwijderd. |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [Pdf417Parameters](./). |
## Opmerkingen


Deze voorbeelden laten zien hoe UCC/EAN-128 niet-gekoppelde modi te coderen in GS1MicroPdf417.
```cpp
[C#]
//Codeert GS1 UCC/EAN-128 niet-gekoppelde modus 905 met AI 01 (GTIN).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Codeert GS1 UCC/EAN-128 niet-gekoppelde modi 903, 904 met elke AI.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
