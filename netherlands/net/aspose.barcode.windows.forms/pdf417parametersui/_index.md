---
title: "Klasse Pdf417ParametersUI"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Windows.Forms.Pdf417ParametersUI klasse. UI-wrapper voor Pdf417Parameters-klasse"
type: docs
weight: 1860
url: /nl/net/aspose.barcode.windows.forms/pdf417parametersui/
---
## Pdf417ParametersUI class

UI-wrapper voor [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/) klasse.

```csharp
public class Pdf417ParametersUI
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/pdf417parametersui/aspectratio/) { get; set; } | Hoogte/breedteverhouding van 2D BarCode-module. |
| [Columns](../../aspose.barcode.windows.forms/pdf417parametersui/columns/) { get; set; } | Aantal kolommen. |
| [ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/eciencoding/) { get; set; } | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. Niet toegepast op Macro PDF417-tekstvelden. De huidige implementatie bevat alle bekende tekensetcoderingen. |
| [EncodeMode](../../aspose.barcode.windows.forms/pdf417parametersui/encodemode/) { get; set; } | Pdf417-symbologie type van de coderingsmodus van BarCode. Standaardwaarde: Pdf417EncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.windows.forms/pdf417parametersui/errorlevel/) { get; set; } | Haalt op of stelt het Pdf417-symbologie type van het foutcorrectieniveau van BarCode in, variërend van level0 tot level8; level0 betekent geen foutcorrectie-informatie, level8 betekent de beste foutcorrectie, wat een grotere afbeelding betekent. |
| [IsCode128Emulation](../../aspose.barcode.windows.forms/pdf417parametersui/iscode128emulation/) { get; set; } | Kan alleen worden gebruikt met MicroPdf417 en codeert Code‑128-emulatiemodi. Kan FNC1 coderen in tweede‑positie‑modi 908 en 909, en kan ook 910 en 911 coderen, die alleen aangeven dat herkende MicroPdf417 kan worden geïnterpreteerd als Code 128. |
| [IsLinked](../../aspose.barcode.windows.forms/pdf417parametersui/islinked/) { get; set; } | Definieert gekoppelde modi met GS1MicroPdf417-, MicroPdf417- en Pdf417-barcodes. Met GS1MicroPdf417-symboolcode codeert 906, 907, 912, 913, 914, 915 “Gekoppelde” UCC/EAN‑128-modi. Met MicroPdf417- en Pdf417-symboolcodes codeert 918 koppelingsvlag naar een geassocieerd lineair component anders dan een EAN.UCC. |
| [IsReaderInitialization](../../aspose.barcode.windows.forms/pdf417parametersui/isreaderinitialization/) { get; set; } | Gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [MacroCharacters](../../aspose.barcode.windows.forms/pdf417parametersui/macrocharacters/) { get; set; } | Macro-tekens 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met MicroPdf417 en codeert 916 en 917 MicroPdf417-modi. Standaardwaarde: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417addressee/) { get; set; } | MacroPdf417-barcode geadresseerde naam (optioneel veld). MicroPDF417-barcode geadresseerde naam (optioneel veld voor Structured Append-modus) |
| [MacroPdf417Checksum](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417checksum/) { get; set; } | MacroPdf417-barcode controlesom (optioneel veld). MicroPDF417-barcode controlesom (optioneel veld voor Structured Append-modus) Het controlesomveld bevat de waarde van de 16-bit (2 bytes) CRC-controlesom met de CCITT-16-polynoom. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417eciencoding/) { get; set; } | Extended Channel Interpretation‑identifiers. Geldt voor Macro‑PDF417-tekstvelden. |
| [MacroPdf417FileID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417fileid/) { get; set; } | Haalt op of stelt de bestands-ID van de macro Pdf417-barcode in. Gebruikt voor MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filename/) { get; set; } | MacroPdf417-barcode bestandsnaam (optioneel veld). MicroPDF417-barcode bestandsnaam (optioneel veld voor Structured Append-modus) |
| [MacroPdf417FileSize](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filesize/) { get; set; } | MacroPdf417 bestandsgrootte (optioneel veld). MicroPDF417 bestandsgrootte (optioneel veld voor Structured Append-modus) Het bestandsgrootteveld bevat de grootte in bytes van het volledige bronbestand. |
| [MacroPdf417SegmentID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentid/) { get; set; } | Haalt op of stelt de segment-ID van de macro Pdf417 barcode in, die begint bij 0 en loopt tot MacroSegmentsCount - 1. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentscount/) { get; set; } | Haalt op of stelt het aantal segmenten van de macro Pdf417 barcode in. |
| [MacroPdf417Sender](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417sender/) { get; set; } | MacroPdf417 barcode afzendernaam (optioneel veld). MicroPDF417 barcode afzendernaam (optioneel veld voor Structured Append-modus) |
| [MacroPdf417Terminator](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417terminator/) { get; set; } | Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. Alleen van toepassing op Macro PDF417. |
| [MacroPdf417TimeStamp](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417timestamp/) { get; set; } | MacroPdf417 barcode tijdstempel (optioneel veld). MicroPDF417 barcode tijdstempel (optioneel veld voor Structured Append-modus) |
| [Rows](../../aspose.barcode.windows.forms/pdf417parametersui/rows/) { get; set; } | Aantal rijen. |
| [Truncate](../../aspose.barcode.windows.forms/pdf417parametersui/truncate/) { get; set; } | Of het Pdf417-symbooltype van de barcode is afgekapt (om ruimte te besparen). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/pdf417parametersui/tostring/)() | Retourneert een menselijk leesbare tekenreeksrepresentatie van dit [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/). |

### Zie ook

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


