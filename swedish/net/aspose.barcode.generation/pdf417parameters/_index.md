---
title: Pdf417Parameters
second_title: Aspose.BarCode för .NET API-referens
description: PDF417 parametrar. Innehåller parametrarna PDF417 MacroPDF417 och MicroPDF417. MacroPDF417 kräver två fält Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria. MicroPDF417 i Structured Append-läge samma som MacroPDF417-läge kräver två fält Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria.
type: docs
weight: 860
url: /sv/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417 parametrar. Innehåller parametrarna PDF417, MacroPDF417 och MicroPDF417. MacroPDF417 kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria. MicroPDF417 i Structured Append-läge (samma som MacroPDF417-läge) kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria.

```csharp
public class Pdf417Parameters
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio) { get; set; } | Höjd/bredd-förhållande för 2D streckkodsmodul. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation) { get; set; } | Funktionskodord för kod 128-emulering. Gällde endast för MicroPDF417. Ignoreras för streckkoderna PDF417 och MacroPDF417. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding) { get; set; } | Hämtar eller ställer in kodningen för kodtext. Standardvärde: UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns) { get; set; } | Antal kolumner. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization) { get; set; } | Används för att instruera läsaren att tolka data som finns i symbol som programmering för läsarinitiering. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode) { get; set; } | Pdf417 symbolisk typ av streckkods komprimeringsläge. Standardvärde: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding) { get; set; } | Identifierare för utökad kanaltolkning. Den används för att berätta för streckkodsläsaren details om de referenser som används för att koda data i symbolen. Används inte för Macro PDF417 textfält. Nuvarande implementering består av alla välkända teckenuppsättningskodningar. |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel) { get; set; } | Hämtar eller ställer in Pdf417 symbology typ av streckkods felkorrigeringsnivå som sträcker sig från nivå0 till nivå8, nivå0 betyder ingen felkorrigeringsinformation, nivå8 betyder bästa felkorrigering vilket innebär en större bild. |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee) { get; set; } | MacroPdf417 streckkod adressatens namn (valfritt fält). MicroPDF417 streckkod adressatens namn (valfritt fält för Structured Append mode) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum) { get; set; } | MacroPdf417 streckkodskontrollsumma (valfritt fält). MicroPDF417 streckkodskontrollsumma (valfritt fält för Structured Append-läge) Kontrollsummafältet innehåller värdet av 16-bitars (2 bytes) CRC-kontrollsumma med CCITT-16-polynomet. x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding) { get; set; } | Identifierare för utökad kanaltolkning. Gäller Macro PDF417 textfält. |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid) { get; set; } | MacroPdf417 streckkodens fil-ID (Obligatoriskt fält). MicroPDF417 streckkodens fil-ID (Obligatoriskt fält för strukturerat tilläggsläge) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename) { get; set; } | MacroPdf417 streckkodsfilnamn (valfritt fält). MicroPDF417 streckkodsfilnamn (valfritt fält för Structured Append-läge) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize) { get; set; } | MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge) Filstorleksfältet innehåller storleken i byte för hela källfilen. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid) { get; set; } | MacroPdf417 streckkodens segment-ID (Obligatoriskt fält), som börjar från 0, till MacroSegmentsCount - 1. MicroPDF417 streckkodens segment-ID (Obligatoriskt fält för Structured Append-läge) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount) { get; set; } | MacroPdf417 streckkodssegment antal (valfritt fält). MicroPDF417 streckkodssegment antal (valfritt fält för strukturerat tilläggsläge) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender) { get; set; } | MacroPdf417 streckkodsavsändarens namn (valfritt fält). MicroPDF417 streckkodsavsändarens namn (valfritt fält för strukturerat tilläggsläge) |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp) { get; set; } | MacroPdf417 streckkod tidsstämpel (valfritt fält). MicroPDF417 streckkod tidsstämpel (valfritt fält för Structured Append-läge) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate) { get; set; } | Huruvida Pdf417 symbology typ av streckkod är trunkerad (för att minska utrymme). Även känd som CompactPDF417. Höger radindikator och höger stoppmönster tas bort i detta läge. |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows) { get; set; } | Antal rader. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring)() | Returnerar en mänsklig läsbar strängrepresentation av detta[`Pdf417Parameters`](../pdf417parameters) . |

### Se även

* namnutrymme [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
