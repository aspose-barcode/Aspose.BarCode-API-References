---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "PDF417‑parametrar."
type: docs
weight: 770
url: /sv/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

PDF417-parametrar. Innehåller PDF417-, MacroPDF417-, MicroPDF417- och GS1MicroPdf417-parametrar. MacroPDF417 kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria. MicroPDF417 i Structured Append-läge (samma som MacroPDF417-läge) kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria. Dessa exempel visar hur man kodar UCC/EAN-128 icke‑länkade lägen i GS1MicroPdf417.

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Höjd/bredd-förhållande för 2D-streckkodmodul. |
| [getColumns()](#getcolumns) | Antal kolumner. |
| [getECIEncoding()](#geteciencoding) | Extended Channel Interpretation Identifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för |
| [getEncodeMode()](#getencodemode) | Identifierar Pdf417-kodningsläge. Standardvärde: Auto. |
| [getErrorLevel()](#geterrorlevel) | Hämtar Pdf417-symbology-typ för BarCodes felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigering. |
| [getMacroCharacters()](#getmacrocharacters) | Makrotecknen 05 och 06 används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med Micro. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | MacroPdf417 streckkod mottagarnamn (valfritt fält). MicroPDF417 streckkod mottagarnamn (valfritt fält för Structured A |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | MacroPdf417 streckkod kontrollsumma (valfritt fält). MicroPDF417 streckkod kontrollsumma (valfritt fält för Structured Append-läge). |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält. |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | MacroPdf417 streckkods fil-ID (obligatoriskt fält). MicroPDF417 streckkods fil-ID (obligatoriskt fält för Structured Append-läge). |
| [getMacroPdf417FileName()](#getmacropdf417filename) | MacroPdf417 streckkod filnamn (valfritt fält). MicroPDF417 streckkod filnamn (valfritt fält för Structured Append-läge). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge). Filstorleken |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | MacroPdf417 streckkod segment-ID (obligatoriskt fält), som startar från 0 till MacroSegmentsCount - 1. MicroPDF417 streckkodens |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | MacroPdf417 streckkod segmentantal (valfritt fält). MicroPDF417 streckkod segmentantal (valfritt fält för Structured A |
| [getMacroPdf417Sender()](#getmacropdf417sender) | MacroPdf417 streckkod avsändarnamn (valfritt fält). MicroPDF417 streckkod avsändarnamn (valfritt fält för Structured Append. |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Används för att tala om för kodaren om ett Macro PDF417 Terminator (kodord 922) ska läggas till segmentet. Tillämpas endast för Macro PD |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | MacroPdf417 streckkod tidsstämpel (valfritt fält). MicroPDF417 streckkod tidsstämpel (valfritt fält för Structured Append mo |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | Pdf417-symbology-typ för BarCodes kompakteringsläge. Standardvärde: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Identifierar Pdf417-kodningsläge. Standardvärde: Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | Hämtar Pdf417-symbology-typ för BarCodes felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigering. |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | Hämtar makro Pdf417 streckkod mottagarnamn. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | Hämtar makro Pdf417 streckkod kontrollsumma. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält. |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Hämtar makro Pdf417 streckkods fil-ID. Används för MacroPdf417. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | Hämtar makro Pdf417 streckkod filnamn. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | Hämtar makro Pdf417 filstorlek. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | Hämtar makro Pdf417 streckkods segment-ID, som startar från 0 till MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | Hämtar makro Pdf417 streckkod segmentantal. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | Hämtar makro Pdf417 streckkod avsändarnamn. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | Används för att tala om för kodaren om ett Macro PDF417 Terminator (kodord 922) ska läggas till segmentet. Tillämpas endast för Macro PD |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | Hämtar makro Pdf417 streckkod tidsstämpel. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | Om Pdf417-symbology-typ för BarCode är trunkerad (för att minska utrymme). |
| [getRows()](#getrows) | Antal rader. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Identifierar ID för DotCode strukturerat tilläggsläge streckkod. ID startar från 1 och måste vara mindre än eller lika med streckkoder |
| [getTruncate()](#gettruncate) | Anger om Pdf417-symboltypen för BarCode är trunkerad (för att minska utrymme). Även känd som CompactPDF417. Höger rad indikator |
| [isCode128Emulation()](#iscode128emulation) | Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionen lägen 908 och |
| [isLinked()](#islinked) | Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417 streckkoder. Med GS1MicroPdf417-symbolen kodas 906, 907 |
| [isReaderInitialization()](#isreaderinitialization) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering |
| [setAspectRatio()](#setaspectratio) | Höjd/bredd-förhållande för 2D-streckkodmodul. |
| [setCode128Emulation()](#setcode128emulation) | Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionen lägen 908 och |
| [setColumns()](#setcolumns) | Antal kolumner. |
| [setECIEncoding()](#seteciencoding) | Extended Channel Interpretation Identifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för |
| [setEncodeMode()](#setencodemode) | Identifierar Pdf417-kodningsläge. Standardvärde: Auto. |
| [setErrorLevel(value)](#seterrorlevel) | Ställer in Pdf417-symboltypens felkorrigeringsnivå för BarCode, som varierar från level0 till level8, level0 betyder ingen felkorrigering |
| [setLinked()](#setlinked) | Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417 streckkoder. Med GS1MicroPdf417-symbolen kodas 906, 907 |
| [setMacroCharacters()](#setmacrocharacters) | Makrotecknen 05 och 06 används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med Micro. |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | MacroPdf417 streckkod mottagarnamn (valfritt fält). MicroPDF417 streckkod mottagarnamn (valfritt fält för Structured A |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | MacroPdf417 streckkod kontrollsumma (valfritt fält). MicroPDF417 streckkod kontrollsumma (valfritt fält för Structured Append-läge). |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält. |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | MacroPdf417 streckkods fil-ID (obligatoriskt fält). MicroPDF417 streckkods fil-ID (obligatoriskt fält för Structured Append-läge). |
| [setMacroPdf417FileName()](#setmacropdf417filename) | MacroPdf417 streckkod filnamn (valfritt fält). MicroPDF417 streckkod filnamn (valfritt fält för Structured Append-läge). |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge). Filstorleken |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | MacroPdf417 streckkod segment-ID (obligatoriskt fält), som startar från 0 till MacroSegmentsCount - 1. MicroPDF417 streckkodens |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | MacroPdf417 streckkod segmentantal (valfritt fält). MicroPDF417 streckkod segmentantal (valfritt fält för Structured A |
| [setMacroPdf417Sender()](#setmacropdf417sender) | MacroPdf417 streckkod avsändarnamn (valfritt fält). MicroPDF417 streckkod avsändarnamn (valfritt fält för Structured Append. |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | Används för att tala om för kodaren om ett Macro PDF417 Terminator (kodord 922) ska läggas till segmentet. Tillämpas endast för Macro PD |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | MacroPdf417 streckkod tidsstämpel (valfritt fält). MicroPDF417 streckkod tidsstämpel (valfritt fält för Structured Append mo |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | Pdf417-symbology-typ för BarCodes kompakteringsläge. Standardvärde: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Identifierar Pdf417-kodningsläge. Standardvärde: Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Ställer in Pdf417-symboltypens felkorrigeringsnivå för BarCode, som varierar från level0 till level8, level0 betyder ingen felkorrigering |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | Ställer in makro Pdf417 streckkod mottagarnamn. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | Ställer in makro Pdf417 streckkod kontrollsumma. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält. |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | Ställer in makro Pdf417 streckkods fil-ID. Används för MacroPdf417. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | Ställer in makro Pdf417 streckkod filnamn. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | Ställer in makro Pdf417 filstorlek. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | Ställer in makro Pdf417 streckkods segment-ID, som startar från 0, till MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | Ställer in makro Pdf417 streckkodsegmentantal. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | Ställer in makro Pdf417 streckkod avsändarnamn. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | Används för att tala om för kodaren om ett Macro PDF417 Terminator (kodord 922) ska läggas till segmentet. Tillämpas endast för Macro PD |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | Ställer in makro Pdf417 streckkod tidsstämpel. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | Om Pdf417-symbology-typ för BarCode är trunkerad (för att minska utrymme). |
| [setReaderInitialization(value)](#setreaderinitialization) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering |
| [setRows()](#setrows) | Antal rader. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Identifierar ID för DotCode strukturerat tilläggsläge streckkod. ID startar från 1 och måste vara mindre än eller lika med streckkoder |
| [setTruncate()](#settruncate) | Anger om Pdf417-symboltypen för BarCode är trunkerad (för att minska utrymme). Även känd som CompactPDF417. Höger rad indikator |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av dessa Pdf417Parameters. |

### getAspectRatio() {#getaspectratio}

Höjd/bredd-förhållande för 2D-streckkodmodul.

### getColumns() {#getcolumns}

Antal kolumner.

### getECIEncoding() {#geteciencoding}

Extended Channel Interpretation Identifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Tillämpas inte för Macro PDF417-textfält. Aktuell implementation består av alla välkända teckenuppsättningskodningar.

### getEncodeMode() {#getencodemode}

Identifierar Pdf417-kodningsläge. Standardvärde: Auto.

### getErrorLevel() {#geterrorlevel}

Hämtar Pdf417-symboltypens felkorrigeringsnivå för BarCode, som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

Macro-tecken 05 och 06 används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med MicroPdf417 och kodar 916 och 917 MicroPdf417-lägen. Standardvärde: MacroCharacters.None. Dessa exempel visar hur man kodar Macro-tecken i MicroPdf417

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

MacroPdf417 streckkod mottagarnamn (valfritt fält). MicroPDF417 streckkod mottagarnamn (valfritt fält för Structured Append-läge)

### getMacroPdf417Checksum() {#getmacropdf417checksum}

MacroPdf417 streckkod kontrollsumma (valfritt fält). MicroPDF417 streckkod kontrollsumma (valfritt fält för Structured Append-läge) Kontrollsummafältet innehåller värdet av den 16-bitars (2 byte) CRC-kontrollsumman med CCITT-16-polynomet. x^16 + x^12 + x^5 + 1

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält.

### getMacroPdf417FileID() {#getmacropdf417fileid}

MacroPdf417 streckkods fil-ID (obligatoriskt fält). MicroPDF417 streckkods fil-ID (obligatoriskt fält för Structured Append-läge)

### getMacroPdf417FileName() {#getmacropdf417filename}

MacroPdf417 streckkod filnamn (valfritt fält). MicroPDF417 streckkod filnamn (valfritt fält för Structured Append-läge)

### getMacroPdf417FileSize() {#getmacropdf417filesize}

MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge) Filstorleksfältet innehåller storleken i byte för hela källfilen.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

MacroPdf417 streckkods segment-ID (obligatoriskt fält), som startar från 0, till MacroSegmentsCount - 1. MicroPDF417 streckkods segment-ID (obligatoriskt fält för Structured Append-läge)

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

MacroPdf417 streckkodsegmentantal (valfritt fält). MicroPDF417 streckkodsegmentantal (valfritt fält för Structured Append-läge)

### getMacroPdf417Sender() {#getmacropdf417sender}

MacroPdf417 streckkodavsändarnamn (valfritt fält). MicroPDF417 streckkodavsändarnamn (valfritt fält för Structured Append-läge)

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. Tillämpas endast för Macro PDF417.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

MacroPdf417 streckkodstidsstämpel (valfritt fält). MicroPDF417 streckkodstidsstämpel (valfritt fält för Structured Append-läge)

### getPdf417CompactionMode() {#getpdf417compactionmode}

Pdf417-symbology-typ för BarCodes kompakteringsläge. Standardvärde: Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Utökade kanalinterpretationsidentifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Nuvarande implementation består av alla välkända teckenkodningsuppsättningar.

### getPdf417EncodeMode() {#getpdf417encodemode}

Identifierar Pdf417-kodningsläge. Standardvärde: Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Hämtar Pdf417-symboltypens felkorrigeringsnivå för BarCode, som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Hämtar makro Pdf417 streckkod mottagarnamn.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Hämtar makro Pdf417 streckkod kontrollsumma.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält.

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Hämtar makro Pdf417 streckkods fil-ID. Används för MacroPdf417.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Hämtar makro Pdf417 streckkod filnamn.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Hämtar makro Pdf417 filstorlek.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Hämtar makro Pdf417 streckkods segment-ID, som startar från 0 till MacroSegmentsCount - 1.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Hämtar makro Pdf417 streckkod segmentantal.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

Hämtar makro Pdf417 streckkod avsändarnamn.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. Tillämpas endast för Macro PDF417.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Hämtar makro Pdf417 streckkod tidsstämpel.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

Om Pdf417-symbology-typ för BarCode är trunkerad (för att minska utrymme).

### getRows() {#getrows}

Antal rader.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Identifierar ID för DotCode structured append-läge streckkod. ID börjar på 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1.

### getTruncate() {#gettruncate}

Om Pdf417-symboltypen för BarCode är trunkerad (för att minska utrymme). Även känt som CompactPDF417. Höger radindikator och höger stoppmönster tas bort i detta läge.

### isCode128Emulation() {#iscode128emulation}

Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionen i lägena 908 och 909, samt kan koda 910 och 911 som bara indikerar att en identifierad MicroPdf417 kan tolkas som Code 128. Dessa exempel visar hur man kodar Code 128-emuleringslägen med FNC1 i andra positionen och utan. På så sätt kan MicroPdf417 avkodas som en Code 128-streckkod.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417 streckkoder. Med GS1MicroPdf417-symbolen kodas 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128-lägen. Med MicroPdf417 och Pdf417-symbolerna kodas länkflagg (918) till associerad linjär komponent annat än en EAN.UCC. Dessa exempel visar hur man kodar "Linked" UCC/EAN-128-lägen i GS1MicroPdf417 och länkflagg (918) i MicroPdf417 och Pdf417 streckkoder.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

Höjd/bredd-förhållande för 2D-streckkodmodul.

### setCode128Emulation() {#setcode128emulation}

Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionen i lägena 908 och 909, samt kan koda 910 och 911 som bara indikerar att en identifierad MicroPdf417 kan tolkas som Code 128. Dessa exempel visar hur man kodar Code 128-emuleringslägen med FNC1 i andra positionen och utan. På så sätt kan MicroPdf417 avkodas som en Code 128-streckkod.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

Antal kolumner.

### setECIEncoding() {#seteciencoding}

Extended Channel Interpretation Identifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Tillämpas inte för Macro PDF417-textfält. Aktuell implementation består av alla välkända teckenuppsättningskodningar.

### setEncodeMode() {#setencodemode}

Identifierar Pdf417-kodningsläge. Standardvärde: Auto.

### setErrorLevel(value) {#seterrorlevel}

Ställer in Pdf417-symboltypens felkorrigeringsnivå för BarCode, från nivå0 till nivå8, nivå0 betyder ingen felkorrigeringsinformation, nivå8 betyder bästa felkorrigering vilket ger en större bild.

| Parameter | Beskrivning |
| --- | --- |
| värde | Pdf417-symboltypens felkorrigeringsnivå för BarCode, från nivå0 till nivå8, nivå0 betyder ingen felkorrigeringsinformation, nivå8 betyder bästa felkorrigering vilket ger en större bild. |

### setLinked() {#setlinked}

Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417 streckkoder. Med GS1MicroPdf417-symbolen kodas 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128-lägen. Med MicroPdf417 och Pdf417-symbolerna kodas länkflagg (918) till associerad linjär komponent annat än en EAN.UCC. Dessa exempel visar hur man kodar "Linked" UCC/EAN-128-lägen i GS1MicroPdf417 och länkflagg (918) i MicroPdf417 och Pdf417 streckkoder.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

Macro-tecken 05 och 06 används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med MicroPdf417 och kodar 916 och 917 MicroPdf417-lägen. Standardvärde: MacroCharacters.None. Dessa exempel visar hur man kodar Macro-tecken i MicroPdf417

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

MacroPdf417 streckkod mottagarnamn (valfritt fält). MicroPDF417 streckkod mottagarnamn (valfritt fält för Structured Append-läge)

### setMacroPdf417Checksum() {#setmacropdf417checksum}

MacroPdf417 streckkod kontrollsumma (valfritt fält). MicroPDF417 streckkod kontrollsumma (valfritt fält för Structured Append-läge) Kontrollsummafältet innehåller värdet av den 16-bitars (2 byte) CRC-kontrollsumman med CCITT-16-polynomet. x^16 + x^12 + x^5 + 1

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält.

### setMacroPdf417FileID() {#setmacropdf417fileid}

MacroPdf417 streckkods fil-ID (obligatoriskt fält). MicroPDF417 streckkods fil-ID (obligatoriskt fält för Structured Append-läge)

### setMacroPdf417FileName() {#setmacropdf417filename}

MacroPdf417 streckkod filnamn (valfritt fält). MicroPDF417 streckkod filnamn (valfritt fält för Structured Append-läge)

### setMacroPdf417FileSize() {#setmacropdf417filesize}

MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge) Filstorleksfältet innehåller storleken i byte för hela källfilen.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

MacroPdf417 streckkods segment-ID (obligatoriskt fält), som startar från 0, till MacroSegmentsCount - 1. MicroPDF417 streckkods segment-ID (obligatoriskt fält för Structured Append-läge)

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

MacroPdf417 streckkodsegmentantal (valfritt fält). MicroPDF417 streckkodsegmentantal (valfritt fält för Structured Append-läge)

### setMacroPdf417Sender() {#setmacropdf417sender}

MacroPdf417 streckkodavsändarnamn (valfritt fält). MicroPDF417 streckkodavsändarnamn (valfritt fält för Structured Append-läge)

### setMacroPdf417Terminator() {#setmacropdf417terminator}

Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. Tillämpas endast för Macro PDF417.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

MacroPdf417 streckkodstidsstämpel (valfritt fält). MicroPDF417 streckkodstidsstämpel (valfritt fält för Structured Append-läge)

### setPdf417CompactionMode() {#setpdf417compactionmode}

Pdf417-symbology-typ för BarCodes kompakteringsläge. Standardvärde: Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Utökade kanalinterpretationsidentifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Nuvarande implementation består av alla välkända teckenkodningsuppsättningar.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Identifierar Pdf417-kodningsläge. Standardvärde: Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Ställer in Pdf417-symboltypens felkorrigeringsnivå för BarCode, från nivå0 till nivå8, nivå0 betyder ingen felkorrigeringsinformation, nivå8 betyder bästa felkorrigering vilket ger en större bild.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Ställer in makro Pdf417 streckkod mottagarnamn.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Ställer in makro Pdf417 streckkod kontrollsumma.

| Parameter | Beskrivning |
| --- | --- |
| värde | Kontrollsummafältet innehåller värdet av den 16-bitars (2 byte) CRC-kontrollen med CCITT-16-polynomet. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält.

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Ställer in makro Pdf417 streckkods fil-ID. Används för MacroPdf417.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Ställer in makro Pdf417 streckkod filnamn.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Ställer in makro Pdf417 filstorlek.

| Parameter | Beskrivning |
| --- | --- |
| värde | Filsstorleksfältet innehåller storleken i byte för hela källfilen. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Ställer in makro Pdf417 streckkods segment-ID, som startar från 0, till MacroSegmentsCount - 1.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Ställer in makro Pdf417 streckkodsegmentantal.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

Ställer in makro Pdf417 streckkod avsändarnamn.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. Tillämpas endast för Macro PDF417.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Ställer in makro Pdf417 streckkod tidsstämpel.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

Om Pdf417-symbology-typ för BarCode är trunkerad (för att minska utrymme).

### setReaderInitialization(value) {#setreaderinitialization}

Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering

| Parameter | Beskrivning |
| --- | --- |
| värde |  |

### setRows() {#setrows}

Antal rader.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Identifierar ID för DotCode structured append-läge streckkod. ID börjar på 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1.

### setTruncate() {#settruncate}

Om Pdf417-symboltypen för BarCode är trunkerad (för att minska utrymme). Även känt som CompactPDF417. Höger radindikator och höger stoppmönster tas bort i detta läge.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av dessa Pdf417Parameters.

**Returns:** A string that represents this Pdf417Parameters.
