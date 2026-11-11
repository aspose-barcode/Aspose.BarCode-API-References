---
title: "Klasse Pdf417Parameters"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.Pdf417Parameters klasse. PDF417‑parameters. Bevat PDF417‑MacroPDF417‑MicroPDF417‑ en GS1MicroPdf417‑parameters. MacroPDF417 vereist twee velden Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel. MicroPDF417 in Structured Append‑modus, net als MacroPDF417‑modus, vereist twee velden Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel"
type: docs
weight: 1570
url: /nl/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417-parameters. Bevat PDF417, MacroPDF417, MicroPDF417 en GS1MicroPdf417 parameters. MacroPDF417 vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel. MicroPDF417 in Structured Append-modus (hetzelfde als MacroPDF417-modus) vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel.

```csharp
public class Pdf417Parameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | Hoogte/breedteverhouding van 2D BarCode-module. |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | Aantal kolommen. |
| [ECIEncoding](../../aspose.barcode.generation/pdf417parameters/eciencoding/) { get; set; } | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. Niet toegepast op Macro PDF417-tekstvelden. De huidige implementatie bevat alle bekende tekensetcoderingen. |
| [EncodeMode](../../aspose.barcode.generation/pdf417parameters/encodemode/) { get; set; } | Identificeert de Pdf417‑codeermodus. Standaardwaarde: Auto. |
| [ErrorLevel](../../aspose.barcode.generation/pdf417parameters/errorlevel/) { get; set; } | Haalt op of stelt het Pdf417-symbologie type van het foutcorrectieniveau van BarCode in, variërend van level0 tot level8; level0 betekent geen foutcorrectie-informatie, level8 betekent de beste foutcorrectie, wat een grotere afbeelding betekent. |
| [IsCode128Emulation](../../aspose.barcode.generation/pdf417parameters/iscode128emulation/) { get; set; } | Kan alleen worden gebruikt met MicroPdf417 en codeert Code‑128-emulatiemodi. Kan FNC1 coderen in tweede‑positie‑modi 908 en 909, en kan ook 910 en 911 coderen, die alleen aangeven dat herkende MicroPdf417 kan worden geïnterpreteerd als Code 128. |
| [IsLinked](../../aspose.barcode.generation/pdf417parameters/islinked/) { get; set; } | Definieert gekoppelde modi met GS1MicroPdf417-, MicroPdf417- en Pdf417-barcodes. Met GS1MicroPdf417-symboolcode codeert 906, 907, 912, 913, 914, 915 “Gekoppelde” UCC/EAN‑128-modi. Met MicroPdf417- en Pdf417-symboolcodes codeert 918 koppelingsvlag naar een geassocieerd lineair component anders dan een EAN.UCC. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | Gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [MacroCharacters](../../aspose.barcode.generation/pdf417parameters/macrocharacters/) { get; set; } | Macro-tekens 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met MicroPdf417 en codeert 916 en 917 MicroPdf417-modi. Standaardwaarde: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.generation/pdf417parameters/macropdf417addressee/) { get; set; } | MacroPdf417-barcode geadresseerde naam (optioneel veld). MicroPDF417-barcode geadresseerde naam (optioneel veld voor Structured Append-modus) |
| [MacroPdf417Checksum](../../aspose.barcode.generation/pdf417parameters/macropdf417checksum/) { get; set; } | MacroPdf417-barcode controlesom (optioneel veld). MicroPDF417-barcode controlesom (optioneel veld voor Structured Append-modus) Het controlesomveld bevat de waarde van de 16-bit (2 bytes) CRC-controlesom met de CCITT-16-polynoom. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/macropdf417eciencoding/) { get; set; } | Extended Channel Interpretation‑identifiers. Geldt voor Macro‑PDF417-tekstvelden. |
| [MacroPdf417FileID](../../aspose.barcode.generation/pdf417parameters/macropdf417fileid/) { get; set; } | MacroPdf417‑barcode‑bestand‑ID (verplicht veld). MicroPDF417‑barcode‑bestand‑ID (verplicht veld voor Structured Append‑modus) |
| [MacroPdf417FileName](../../aspose.barcode.generation/pdf417parameters/macropdf417filename/) { get; set; } | MacroPdf417-barcode bestandsnaam (optioneel veld). MicroPDF417-barcode bestandsnaam (optioneel veld voor Structured Append-modus) |
| [MacroPdf417FileSize](../../aspose.barcode.generation/pdf417parameters/macropdf417filesize/) { get; set; } | MacroPdf417 bestandsgrootte (optioneel veld). MicroPDF417 bestandsgrootte (optioneel veld voor Structured Append-modus) Het bestandsgrootteveld bevat de grootte in bytes van het volledige bronbestand. |
| [MacroPdf417SegmentID](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentid/) { get; set; } | MacroPdf417‑barcode‑segment‑ID (verplicht veld), die start bij 0 tot MacroSegmentsCount - 1. MicroPDF417‑barcode‑segment‑ID (verplicht veld voor Structured Append‑modus) |
| [MacroPdf417SegmentsCount](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentscount/) { get; set; } | MacroPdf417‑barcode‑segment‑aantal (optioneel veld). MicroPDF417‑barcode‑segment‑aantal (optioneel veld voor Structured Append‑modus) |
| [MacroPdf417Sender](../../aspose.barcode.generation/pdf417parameters/macropdf417sender/) { get; set; } | MacroPdf417 barcode afzendernaam (optioneel veld). MicroPDF417 barcode afzendernaam (optioneel veld voor Structured Append-modus) |
| [MacroPdf417Terminator](../../aspose.barcode.generation/pdf417parameters/macropdf417terminator/) { get; set; } | Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. Alleen van toepassing op Macro PDF417. |
| [MacroPdf417TimeStamp](../../aspose.barcode.generation/pdf417parameters/macropdf417timestamp/) { get; set; } | MacroPdf417 barcode tijdstempel (optioneel veld). MicroPDF417 barcode tijdstempel (optioneel veld voor Structured Append-modus) |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | Aantal rijen. |
| [Truncate](../../aspose.barcode.generation/pdf417parameters/truncate/) { get; set; } | Of het Pdf417‑symbooltype van BarCode is ingekort (om ruimte te besparen). Ook bekend als CompactPDF417. De rechter‑rij‑indicator en het rechter‑stop‑patroon worden in deze modus verwijderd. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `Pdf417Parameters`. |

## Voorbeelden

Deze voorbeelden laten zien hoe u UCC/EAN-128 non‑Linked‑modi codeert in GS1MicroPdf417

```csharp
[C#]
//Codeert GS1 UCC/EAN-128 non‑Linked‑modus 905 met AI 01 (GTIN)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Codeert GS1 UCC/EAN-128 non‑Linked‑modi 903, 904 met elke AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


