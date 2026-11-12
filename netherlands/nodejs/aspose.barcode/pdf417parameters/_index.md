---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "PDF417-parameters."
type: docs
weight: 770
url: /nl/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

PDF417-parameters. Bevat PDF417-, MacroPDF417-, MicroPDF417- en GS1MicroPdf417-parameters. MacroPDF417 vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel. MicroPDF417 in Structured Append-modus (hetzelfde als MacroPDF417-modus) vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel. Deze voorbeelden tonen hoe UCC/EAN-128 niet-gekoppelde modi te coderen in GS1MicroPdf417

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [getColumns()](#getcolumns) | Aantal kolommen. |
| [getECIEncoding()](#geteciencoding) | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor |
| [getEncodeMode()](#getencodemode) | Identificeert de Pdf417-codemodus. Standaardwaarde: Auto. |
| [getErrorLevel()](#geterrorlevel) | Haalt het PDF417-symbooltype op van het foutcorrectieniveau van de BarCode, variërend van level0 tot level8, level0 betekent geen foutcorrectie |
| [getMacroCharacters()](#getmacrocharacters) | Macro Characters 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen met Micro worden gebruikt. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | MacroPdf417 barcode addressee name (optioneel veld). MicroPDF417 barcode addressee name (optioneel veld voor Structured A |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | MacroPdf417 barcode checksum (optioneel veld). MicroPDF417 barcode checksum (optioneel veld voor Structured Append-modus) |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | Extended Channel Interpretation Identifiers. Geldt voor Macro PDF417-tekstvelden. |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | MacroPdf417 barcode's file ID (verplicht veld). MicroPDF417 barcode's file ID (verplicht veld voor Structured Append-modus) |
| [getMacroPdf417FileName()](#getmacropdf417filename) | MacroPdf417 barcode file name (optioneel veld). MicroPDF417 barcode file name (optioneel veld voor Structured Append-modus) |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | MacroPdf417 file size (optioneel veld). MicroPDF417 file size (optioneel veld voor Structured Append-modus) De bestandsgrootte |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | MacroPdf417 barcode's segment ID (verplicht veld), die start bij 0 tot MacroSegmentsCount - 1. MicroPDF417 barcode's |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | MacroPdf417 barcode segments count (optioneel veld). MicroPDF417 barcode segments count (optioneel veld voor Structured A |
| [getMacroPdf417Sender()](#getmacropdf417sender) | MacroPdf417 barcode sender name (optioneel veld). MicroPDF417 barcode sender name (optioneel veld voor Structured Append |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codeword 922) aan het segment moet worden toegevoegd. Alleen toegepast voor Macro PD |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | MacroPdf417 barcode time stamp (optioneel veld). MicroPDF417 barcode time stamp (optioneel veld voor Structured Append mo |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | Pdf417 symbology type van de compaction-modus van BarCode. Standaardwaarde: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Identificeert de Pdf417-codemodus. Standaardwaarde: Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | Haalt het PDF417-symbooltype op van het foutcorrectieniveau van de BarCode, variërend van level0 tot level8, level0 betekent geen foutcorrectie |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | Haalt macro Pdf417 barcode addressee name op. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | Haalt macro Pdf417 barcode checksum op. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. Geldt voor Macro PDF417-tekstvelden. |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Haaltmacro Pdf417 barcode's file ID op. Gebruikt voor MacroPdf417. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | Haalt macro Pdf417 barcode file name op. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | Haalt macro Pdf417 file size op. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | Haalt macro Pdf417 barcode's segment ID op, die start bij 0 tot MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | Haalt macro Pdf417 barcode segments count op. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | Haalt macro Pdf417 barcode sender name op. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codeword 922) aan het segment moet worden toegevoegd. Alleen toegepast voor Macro PD |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | Haalt macro Pdf417 barcode time stamp op. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | Of Pdf417 symbology type van BarCode is ingekort (om ruimte te besparen). |
| [getRows()](#getrows) | Aantal rijen. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Identificeert de ID van de DotCode structured append-modus barcode. ID start vanaf 1 en moet kleiner of gelijk zijn aan barcodes |
| [getTruncate()](#gettruncate) | Of Pdf417 symbology type van BarCode is ingekort (om ruimte te besparen). Ook bekend als CompactPDF417. Rigth row indicato |
| [isCode128Emulation()](#iscode128emulation) | Kan alleen worden gebruikt met MicroPdf417 en codeert Code 128 emulatiemodi. Kan FNC1 coderen in tweede positie modi 908 en |
| [isLinked()](#islinked) | Definieert gekoppelde modi met GS1MicroPdf417, MicroPdf417 en Pdf417 barcodes. Met GS1MicroPdf417 symbologie codeert 906, 907 |
| [isReaderInitialization()](#isreaderinitialization) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie |
| [setAspectRatio()](#setaspectratio) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [setCode128Emulation()](#setcode128emulation) | Kan alleen worden gebruikt met MicroPdf417 en codeert Code 128 emulatiemodi. Kan FNC1 coderen in tweede positie modi 908 en |
| [setColumns()](#setcolumns) | Aantal kolommen. |
| [setECIEncoding()](#seteciencoding) | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor |
| [setEncodeMode()](#setencodemode) | Identificeert de Pdf417-codemodus. Standaardwaarde: Auto. |
| [setErrorLevel(value)](#seterrorlevel) | Stelt het Pdf417-symbooltype van de foutcorrectieniveau van de BarCode in, variërend van level0 tot level8, level0 betekent geen foutcorrectie |
| [setLinked()](#setlinked) | Definieert gekoppelde modi met GS1MicroPdf417, MicroPdf417 en Pdf417 barcodes. Met GS1MicroPdf417 symbologie codeert 906, 907 |
| [setMacroCharacters()](#setmacrocharacters) | Macro Characters 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen met Micro worden gebruikt. |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | MacroPdf417 barcode addressee name (optioneel veld). MicroPDF417 barcode addressee name (optioneel veld voor Structured A |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | MacroPdf417 barcode checksum (optioneel veld). MicroPDF417 barcode checksum (optioneel veld voor Structured Append-modus) |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | Extended Channel Interpretation Identifiers. Geldt voor Macro PDF417-tekstvelden. |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | MacroPdf417 barcode's file ID (verplicht veld). MicroPDF417 barcode's file ID (verplicht veld voor Structured Append-modus) |
| [setMacroPdf417FileName()](#setmacropdf417filename) | MacroPdf417 barcode file name (optioneel veld). MicroPDF417 barcode file name (optioneel veld voor Structured Append-modus) |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | MacroPdf417 file size (optioneel veld). MicroPDF417 file size (optioneel veld voor Structured Append-modus) De bestandsgrootte |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | MacroPdf417 barcode's segment ID (verplicht veld), die start bij 0 tot MacroSegmentsCount - 1. MicroPDF417 barcode's |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | MacroPdf417 barcode segments count (optioneel veld). MicroPDF417 barcode segments count (optioneel veld voor Structured A |
| [setMacroPdf417Sender()](#setmacropdf417sender) | MacroPdf417 barcode sender name (optioneel veld). MicroPDF417 barcode sender name (optioneel veld voor Structured Append |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codeword 922) aan het segment moet worden toegevoegd. Alleen toegepast voor Macro PD |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | MacroPdf417 barcode time stamp (optioneel veld). MicroPDF417 barcode time stamp (optioneel veld voor Structured Append mo |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | Pdf417 symbology type van de compaction-modus van BarCode. Standaardwaarde: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Identificeert de Pdf417-codemodus. Standaardwaarde: Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Stelt het Pdf417-symbooltype van de foutcorrectieniveau van de BarCode in, variërend van level0 tot level8, level0 betekent geen foutcorrectie |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | Stelt de geadresseerde naam van de macro Pdf417 barcode in. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | Stelt de checksum van de macro Pdf417 barcode in. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. Geldt voor Macro PDF417-tekstvelden. |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | Stelt de bestands-ID van de macro Pdf417 barcode in. Wordt gebruikt voor MacroPdf417. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | Stelt de bestandsnaam van de macro Pdf417 barcode in. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | Stelt de bestandsgrootte van de macro Pdf417 in. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | Stelt de segment-ID van de macro Pdf417 barcode in, die start bij 0 tot MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | Stelt het aantal segmenten van de macro Pdf417 barcode in. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | Stelt de afzendernaam van de macro Pdf417 barcode in. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codeword 922) aan het segment moet worden toegevoegd. Alleen toegepast voor Macro PD |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | Stelt de tijdstempel van de macro Pdf417 barcode in. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | Of Pdf417 symbology type van BarCode is ingekort (om ruimte te besparen). |
| [setReaderInitialization(value)](#setreaderinitialization) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie |
| [setRows()](#setrows) | Aantal rijen. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Identificeert de ID van de DotCode structured append-modus barcode. ID start vanaf 1 en moet kleiner of gelijk zijn aan barcodes |
| [setTruncate()](#settruncate) | Of Pdf417 symbology type van BarCode is ingekort (om ruimte te besparen). Ook bekend als CompactPDF417. Rigth row indicato |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Pdf417Parameters. |

### getAspectRatio() {#getaspectratio}

Hoogte/breedteverhouding van 2D BarCode-module.

### getColumns() {#getcolumns}

Aantal kolommen.

### getECIEncoding() {#geteciencoding}

Uitgebreide Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. Niet toegepast op Macro PDF417-tekstvelden. De huidige implementatie bestaat uit alle bekende charset-coderingen.

### getEncodeMode() {#getencodemode}

Identificeert de Pdf417-codemodus. Standaardwaarde: Auto.

### getErrorLevel() {#geterrorlevel}

Haalt het Pdf417-symbooltype van de foutcorrectieniveau van de BarCode op, variërend van level0 tot level8, level0 betekent geen foutcorrectie-informatie, level8 betekent de beste foutcorrectie, wat een groter beeld betekent.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

Macro Characters 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met MicroPdf417 en codeert 916 en 917 MicroPdf417-modus. Standaardwaarde: MacroCharacters.None. Deze voorbeelden laten zien hoe Macro Characters in MicroPdf417 te coderen.

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

MacroPdf417 barcode geadresseerde naam (optioneel veld). MicroPDF417 barcode geadresseerde naam (optioneel veld voor Structured Append-modus)

### getMacroPdf417Checksum() {#getmacropdf417checksum}

MacroPdf417 barcode checksum (optioneel veld). MicroPDF417 barcode checksum (optioneel veld voor Structured Append-modus) Het checksum-veld bevat de waarde van de 16-bit (2 bytes) CRC checksum met de CCITT-16 polynoom. x^16 + x^12 + x^5 + 1

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

Extended Channel Interpretation Identifiers. Geldt voor Macro PDF417-tekstvelden.

### getMacroPdf417FileID() {#getmacropdf417fileid}

MacroPdf417 barcode bestands-ID (verplicht veld). MicroPDF417 barcode bestands-ID (verplicht veld voor Structured Append-modus)

### getMacroPdf417FileName() {#getmacropdf417filename}

MacroPdf417 barcode bestandsnaam (optioneel veld). MicroPDF417 barcode bestandsnaam (optioneel veld voor Structured Append-modus)

### getMacroPdf417FileSize() {#getmacropdf417filesize}

MacroPdf417 bestandsgrootte (optioneel veld). MicroPDF417 bestandsgrootte (optioneel veld voor Structured Append-modus) Het bestandsgrootte-veld bevat de grootte in bytes van het volledige bronbestand.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

MacroPdf417 barcode segment-ID (verplicht veld), die start bij 0 tot MacroSegmentsCount - 1. MicroPDF417 barcode segment-ID (verplicht veld voor Structured Append-modus)

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

MacroPdf417 barcode segmentenaantal (optioneel veld). MicroPDF417 barcode segmentenaantal (optioneel veld voor Structured Append-modus)

### getMacroPdf417Sender() {#getmacropdf417sender}

MacroPdf417 barcode afzendernaam (optioneel veld). MicroPDF417 barcode afzendernaam (optioneel veld voor Structured Append-modus)

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. Alleen toegepast voor Macro PDF417.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

MacroPdf417 barcode tijdstempel (optioneel veld). MicroPDF417 barcode tijdstempel (optioneel veld voor Structured Append-modus)

### getPdf417CompactionMode() {#getpdf417compactionmode}

Pdf417 symbology type van de compaction-modus van BarCode. Standaardwaarde: Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bestaat uit alle bekende charset-encoderingen.

### getPdf417EncodeMode() {#getpdf417encodemode}

Identificeert de Pdf417-codemodus. Standaardwaarde: Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Haalt het Pdf417-symbooltype van de foutcorrectieniveau van de BarCode op, variërend van level0 tot level8, level0 betekent geen foutcorrectie-informatie, level8 betekent de beste foutcorrectie, wat een groter beeld betekent.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Haalt macro Pdf417 barcode addressee name op.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Haalt macro Pdf417 barcode checksum op.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. Geldt voor Macro PDF417-tekstvelden.

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Haaltmacro Pdf417 barcode's file ID op. Gebruikt voor MacroPdf417.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Haalt macro Pdf417 barcode file name op.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Haalt macro Pdf417 file size op.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Haalt macro Pdf417 barcode's segment ID op, die start bij 0 tot MacroSegmentsCount - 1.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Haalt macro Pdf417 barcode segments count op.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

Haalt macro Pdf417 barcode sender name op.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. Alleen toegepast voor Macro PDF417.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Haalt macro Pdf417 barcode time stamp op.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

Of Pdf417 symbology type van BarCode is ingekort (om ruimte te besparen).

### getRows() {#getrows}

Aantal rijen.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Identificeert de ID van de DotCode structured append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1.

### getTruncate() {#gettruncate}

Of het Pdf417-symbooltype van de BarCode is ingekort (om ruimte te besparen). Ook bekend als CompactPDF417. De rechterrij‑indicator en het rechter‑stop‑patroon worden in deze modus verwijderd.

### isCode128Emulation() {#iscode128emulation}

Kan alleen worden gebruikt met MicroPdf417 en codeert Code 128-emulatiemodi. Kan FNC1 coderen in de tweede positie voor de modi 908 en 909, en kan ook 910 en 911 coderen, die alleen aangeven dat een herkende MicroPdf417 kan worden geïnterpreteerd als Code 128. Deze voorbeelden laten zien hoe Code 128-emulatiemodi te coderen met FNC1 in de tweede positie en zonder. Op deze manier kan MicroPdf417 worden gedecodeerd als Code 128-barcode.

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

Definieert gekoppelde modi met GS1MicroPdf417-, MicroPdf417- en Pdf417‑barcodes. Met de GS1MicroPdf417‑symbologie worden de “Linked” UCC/EAN-128‑modi 906, 907, 912, 913, 914, 915 gecodeerd. Met de MicroPdf417‑ en Pdf417‑symbologieën wordt de koppelflag 918 gecodeerd naar een geassocieerd lineair component anders dan een EAN.UCC. Deze voorbeelden laten zien hoe de \"Linked\" UCC/EAN-128‑modi te coderen in GS1MicroPdf417 en de Linkage Flag (918) in MicroPdf417 en Pdf417‑barcodes.

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

Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

Hoogte/breedteverhouding van 2D BarCode-module.

### setCode128Emulation() {#setcode128emulation}

Kan alleen worden gebruikt met MicroPdf417 en codeert Code 128-emulatiemodi. Kan FNC1 coderen in de tweede positie voor de modi 908 en 909, en kan ook 910 en 911 coderen, die alleen aangeven dat een herkende MicroPdf417 kan worden geïnterpreteerd als Code 128. Deze voorbeelden laten zien hoe Code 128-emulatiemodi te coderen met FNC1 in de tweede positie en zonder. Op deze manier kan MicroPdf417 worden gedecodeerd als Code 128-barcode.

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

Aantal kolommen.

### setECIEncoding() {#seteciencoding}

Uitgebreide Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. Niet toegepast op Macro PDF417-tekstvelden. De huidige implementatie bestaat uit alle bekende charset-coderingen.

### setEncodeMode() {#setencodemode}

Identificeert de Pdf417-codemodus. Standaardwaarde: Auto.

### setErrorLevel(value) {#seterrorlevel}

Stelt het Pdf417-symbooltype van de BarCode in voor het foutcorrectieniveau, variërend van level0 tot level8; level0 betekent geen foutcorrectie‑informatie, level8 betekent de beste foutcorrectie, wat een groter beeld oplevert.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Pdf417-symbooltype van de BarCode's foutcorrectieniveau, variërend van level0 tot level8; level0 betekent geen foutcorrectie‑informatie, level8 betekent de beste foutcorrectie, wat een groter beeld oplevert. |

### setLinked() {#setlinked}

Definieert gekoppelde modi met GS1MicroPdf417-, MicroPdf417- en Pdf417‑barcodes. Met de GS1MicroPdf417‑symbologie worden de “Linked” UCC/EAN-128‑modi 906, 907, 912, 913, 914, 915 gecodeerd. Met de MicroPdf417‑ en Pdf417‑symbologieën wordt de koppelflag 918 gecodeerd naar een geassocieerd lineair component anders dan een EAN.UCC. Deze voorbeelden laten zien hoe de \"Linked\" UCC/EAN-128‑modi te coderen in GS1MicroPdf417 en de Linkage Flag (918) in MicroPdf417 en Pdf417‑barcodes.

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

Macro Characters 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met MicroPdf417 en codeert 916 en 917 MicroPdf417-modus. Standaardwaarde: MacroCharacters.None. Deze voorbeelden laten zien hoe Macro Characters in MicroPdf417 te coderen.

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

MacroPdf417 barcode geadresseerde naam (optioneel veld). MicroPDF417 barcode geadresseerde naam (optioneel veld voor Structured Append-modus)

### setMacroPdf417Checksum() {#setmacropdf417checksum}

MacroPdf417 barcode checksum (optioneel veld). MicroPDF417 barcode checksum (optioneel veld voor Structured Append-modus) Het checksum-veld bevat de waarde van de 16-bit (2 bytes) CRC checksum met de CCITT-16 polynoom. x^16 + x^12 + x^5 + 1

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

Extended Channel Interpretation Identifiers. Geldt voor Macro PDF417-tekstvelden.

### setMacroPdf417FileID() {#setmacropdf417fileid}

MacroPdf417 barcode bestands-ID (verplicht veld). MicroPDF417 barcode bestands-ID (verplicht veld voor Structured Append-modus)

### setMacroPdf417FileName() {#setmacropdf417filename}

MacroPdf417 barcode bestandsnaam (optioneel veld). MicroPDF417 barcode bestandsnaam (optioneel veld voor Structured Append-modus)

### setMacroPdf417FileSize() {#setmacropdf417filesize}

MacroPdf417 bestandsgrootte (optioneel veld). MicroPDF417 bestandsgrootte (optioneel veld voor Structured Append-modus) Het bestandsgrootte-veld bevat de grootte in bytes van het volledige bronbestand.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

MacroPdf417 barcode segment-ID (verplicht veld), die start bij 0 tot MacroSegmentsCount - 1. MicroPDF417 barcode segment-ID (verplicht veld voor Structured Append-modus)

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

MacroPdf417 barcode segmentenaantal (optioneel veld). MicroPDF417 barcode segmentenaantal (optioneel veld voor Structured Append-modus)

### setMacroPdf417Sender() {#setmacropdf417sender}

MacroPdf417 barcode afzendernaam (optioneel veld). MicroPDF417 barcode afzendernaam (optioneel veld voor Structured Append-modus)

### setMacroPdf417Terminator() {#setmacropdf417terminator}

Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. Alleen toegepast voor Macro PDF417.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

MacroPdf417 barcode tijdstempel (optioneel veld). MicroPDF417 barcode tijdstempel (optioneel veld voor Structured Append-modus)

### setPdf417CompactionMode() {#setpdf417compactionmode}

Pdf417 symbology type van de compaction-modus van BarCode. Standaardwaarde: Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bestaat uit alle bekende charset-encoderingen.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Identificeert de Pdf417-codemodus. Standaardwaarde: Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Stelt het Pdf417-symbooltype van de BarCode in voor het foutcorrectieniveau, variërend van level0 tot level8; level0 betekent geen foutcorrectie‑informatie, level8 betekent de beste foutcorrectie, wat een groter beeld oplevert.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Stelt de geadresseerde naam van de macro Pdf417 barcode in.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Stelt de checksum van de macro Pdf417 barcode in.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Het checksum‑veld bevat de waarde van de 16‑bit (2 bytes) CRC‑checksum met de CCITT‑16‑polynoom. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. Geldt voor Macro PDF417-tekstvelden.

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Stelt de bestands-ID van de macro Pdf417 barcode in. Wordt gebruikt voor MacroPdf417.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Stelt de bestandsnaam van de macro Pdf417 barcode in.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Stelt de bestandsgrootte van de macro Pdf417 in.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Het bestandsgrootte‑veld bevat de grootte in bytes van het volledige bronbestand. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Stelt de segment-ID van de macro Pdf417 barcode in, die start bij 0 tot MacroSegmentsCount - 1.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Stelt het aantal segmenten van de macro Pdf417 barcode in.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

Stelt de afzendernaam van de macro Pdf417 barcode in.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. Alleen toegepast voor Macro PDF417.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Stelt de tijdstempel van de macro Pdf417 barcode in.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

Of Pdf417 symbology type van BarCode is ingekort (om ruimte te besparen).

### setReaderInitialization(value) {#setreaderinitialization}

Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie

| Parameter | Beschrijving |
| --- | --- |
| waarde |  |

### setRows() {#setrows}

Aantal rijen.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Identificeert de ID van de DotCode structured append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1.

### setTruncate() {#settruncate}

Of het Pdf417-symbooltype van de BarCode is ingekort (om ruimte te besparen). Ook bekend als CompactPDF417. De rechterrij‑indicator en het rechter‑stop‑patroon worden in deze modus verwijderd.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze Pdf417Parameters.

**Returns:** A string that represents this Pdf417Parameters.
