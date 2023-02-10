---
title: Pdf417Parameters
second_title: Aspose.BarCode voor .NET API-referentie
description: PDF417parameters. Bevat PDF417 MacroPDF417 en MicroPDF417parameters. MacroPDF417 vereist twee velden Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel. MicroPDF417 in de modus Gestructureerd toevoegen hetzelfde als de modus MacroPDF417 vereist twee velden Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel.
type: docs
weight: 1130
url: /nl/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417-parameters. Bevat PDF417-, MacroPDF417- en MicroPDF417-parameters. MacroPDF417 vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel. MicroPDF417 in de modus Gestructureerd toevoegen (hetzelfde als de modus MacroPDF417) vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel.

```csharp
public class Pdf417Parameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | Hoogte/Breedte-verhouding van 2D BarCode-module. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation/) { get; set; } | Functiecodewoord voor Code 128-emulatie. Alleen toegepast voor MicroPDF417. Genegeerd voor PDF417- en MacroPDF417-streepjescodes. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding/) { get; set; } | Haalt de codering van codetekst op of stelt deze in. Standaardwaarde: UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | Aantal kolommen. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | Wordt gebruikt om de lezer te instrueren om de gegevens in het symbol te interpreteren als programmering voor lezerinitialisatie. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode/) { get; set; } | Pdf417 symbologietype van de verdichtingsmodus van BarCode. Standaardwaarde: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding/) { get; set; } | Uitgebreide kanaalinterpretatie-ID's. Het wordt gebruikt om de streepjescodelezer details te vertellen over de gebruikte referenties voor het coderen van de gegevens in het symbool. Niet toegepast voor Macro PDF417-tekstvelden. Huidige implementatie bestaat uit alle bekende tekensetcoderingen. |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel/) { get; set; } | Krijgt of stelt Pdf417-symboliektype van BarCode's foutcorrectieniveau in variërend van niveau0 tot niveau8, niveau0 betekent geen informatie over foutcorrectie, niveau8 betekent de beste foutcorrectie, wat een groter beeld betekent. |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee/) { get; set; } | MacroPdf417 barcode geadresseerde naam (optioneel veld). MicroPDF417 barcode geadresseerde naam (optioneel veld voor gestructureerde toevoegmodus) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum/) { get; set; } | MacroPdf417 streepjescodecontrolesom (optioneel veld). MicroPDF417 streepjescodecontrolesom (optioneel veld voor gestructureerde append-modus) Het controlesomveld bevat de waarde van de 16-bits (2 bytes) CRC-controlesom met behulp van de CCITT-16-polynoom. x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding/) { get; set; } | Uitgebreide kanaalinterpretatie-ID's. Geldt voor Macro PDF417 tekstvelden. |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid/) { get; set; } | Bestands-ID van de MacroPdf417-streepjescode (verplicht veld). Bestands-ID van de MicroPDF417-streepjescode (verplicht veld voor de modus Gestructureerd toevoegen) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename/) { get; set; } | MacroPdf417 barcodebestandsnaam (optioneel veld). MicroPDF417 barcodebestandsnaam (optioneel veld voor gestructureerde append-modus) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize/) { get; set; } | Bestandsgrootte MacroPdf417 (optioneel veld). Bestandsgrootte MicroPDF417 (optioneel veld voor modus Gestructureerd toevoegen) Het veld Bestandsgrootte bevat de grootte in bytes van het volledige bronbestand. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid/) { get; set; } | Segment-ID van MacroPdf417-streepjescode (verplicht veld), beginnend bij 0, tot MacroSegmentsCount - 1. Segment-ID van MicroPDF417-streepjescode (vereist veld voor modus Gestructureerd toevoegen) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount/) { get; set; } | Aantal macroPdf417-streepjescodesegmenten (optioneel veld). Aantal MicroPDF417-streepjescodesegmenten (optioneel veld voor modus Gestructureerd toevoegen) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender/) { get; set; } | MacroPdf417 barcode afzender naam (optioneel veld). MicroPDF417 barcode afzender naam (optioneel veld voor gestructureerde toevoegmodus) |
| [Pdf417MacroTerminator](../../aspose.barcode.generation/pdf417parameters/pdf417macroterminator/) { get; set; } | Gebruikt om de encoder te vertellen of Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. Alleen toegepast voor Macro PDF417. |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp/) { get; set; } | MacroPdf417 streepjescode tijdstempel (optioneel veld). MicroPDF417 streepjescode tijdstempel (optioneel veld voor gestructureerde append-modus) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate/) { get; set; } | Of Pdf417-symboliektype BarCode wordt afgekapt (om ruimte te besparen). Ook bekend als CompactPDF417. De rechter rij-indicator en het rechter stoppatroon worden in deze modus verwijderd. |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | Aantal rijen. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | Retourneert hiervan een door mensen leesbare tekenreeksrepresentatie`Pdf417Parameters` . |

### Zie ook

* naamruimte [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
