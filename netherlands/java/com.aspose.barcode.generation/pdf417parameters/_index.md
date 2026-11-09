---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode for Java API-referentie"
description: "PDF417 parameters."
type: docs
weight: 58
url: /nl/java/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417‑parameters. Bevat PDF417-, MacroPDF417-, MicroPDF417- en GS1MicroPdf417-parameters. MacroPDF417 vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel. MicroPDF417 in Structured Append‑modus (hetzelfde als MacroPDF417‑modus) vereist twee velden: Pdf417MacroFileID en Pdf417MacroSegmentID. Alle andere velden zijn optioneel.

Deze voorbeelden laten zien hoe UCC/EAN-128 niet‑gelinkte modi te coderen in GS1MicroPdf417

```

 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Aantal kolommen. |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getEncodeMode()](#getEncodeMode--) | Identificeert de Pdf417‑codeermodus. |
| [getErrorLevel()](#getErrorLevel--) | Haalt het Pdf417-symbooltype van het foutcorrectieniveau van BarCode op, variërend van level0 tot level8; level0 betekent geen foutcorrectie-informatie, level8 betekent de beste foutcorrectie, wat een groter beeld betekent. |
| [getMacroCharacters()](#getMacroCharacters--) | Macro‑tekens 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417-barcode geadresseerde naam (optioneel veld). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417-barcode controlesom (optioneel veld). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Bestands‑ID van de MacroPdf417‑barcode (verplicht veld). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417-barcode bestandsnaam (optioneel veld). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417-bestandsgrootte (optioneel veld). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Segment‑ID van de MacroPdf417‑barcode (verplicht veld), die begint bij 0 tot MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Aantal segmenten van de MacroPdf417‑barcode (optioneel veld). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417-barcode afzendernaam (optioneel veld). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417-barcode tijdstempel (optioneel veld). |
| [getRows()](#getRows--) | Aantal rijen. |
| [getTruncate()](#getTruncate--) | Of het Pdf417-symbooltype van BarCode is ingekort (om ruimte te besparen). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Kan alleen worden gebruikt met MicroPdf417 en codeert Code 128-emulatiemodi. Kan FNC1 coderen in de tweede positie in modi 908 en 909, en kan ook 910 en 911 coderen, wat alleen aangeeft dat herkende MicroPdf417 kan worden geïnterpreteerd als Code 128. |
| [isLinked()](#isLinked--) | Definieert gekoppelde modi met GS1MicroPdf417, MicroPdf417 en Pdf417 barcodes Met GS1MicroPdf417 symbooltype codeert 906, 907, 912, 913, 914, 915 \u201cLinked\u201d UCC/EAN-128 modi Met MicroPdf417 en Pdf417 symbooltypes codeert 918 koppelingsvlag naar geassocieerde lineaire component anders dan een EAN.UCC |
| [isReaderInitialization()](#isReaderInitialization--) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Kan alleen worden gebruikt met MicroPdf417 en codeert Code 128-emulatiemodi. Kan FNC1 coderen in de tweede positie in modi 908 en 909, en kan ook 910 en 911 coderen, wat alleen aangeeft dat herkende MicroPdf417 kan worden geïnterpreteerd als Code 128. |
| [setColumns(int value)](#setColumns-int-) | Aantal kolommen. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identificeert de Pdf417‑codeermodus. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Stelt het Pdf417-symbooltype van het foutcorrectieniveau van BarCode in, variërend van level0 tot level8; level0 betekent geen foutcorrectie-informatie, level8 betekent de beste foutcorrectie, wat een groter beeld betekent. |
| [setLinked(boolean value)](#setLinked-boolean-) | Definieert gekoppelde modi met GS1MicroPdf417, MicroPdf417 en Pdf417 barcodes Met GS1MicroPdf417 symbooltype codeert 906, 907, 912, 913, 914, 915 \u201cLinked\u201d UCC/EAN-128 modi Met MicroPdf417 en Pdf417 symbooltypes codeert 918 koppelingsvlag naar geassocieerde lineaire component anders dan een EAN.UCC |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Macro‑tekens 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417-barcode geadresseerde naam (optioneel veld). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417-barcode controlesom (optioneel veld). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Bestands‑ID van de MacroPdf417‑barcode (verplicht veld). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417-barcode bestandsnaam (optioneel veld). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417-bestandsgrootte (optioneel veld). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Segment‑ID van de MacroPdf417‑barcode (verplicht veld), die begint bij 0 tot MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Aantal segmenten van de MacroPdf417‑barcode (optioneel veld). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417-barcode afzendernaam (optioneel veld). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417-barcode tijdstempel (optioneel veld). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [setRows(int value)](#setRows-int-) | Aantal rijen. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Of het Pdf417-symbooltype van BarCode is ingekort (om ruimte te besparen). |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Hoogte/breedteverhouding van 2D BarCode-module.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Aantal kolommen.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Uitgebreide Kanaalinterpretatie-identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. Niet toegepast op Macro PDF417-tekstvelden. De huidige implementatie bestaat uit alle bekende tekensetcoderingen.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Identificeert de Pdf417‑codeermodus. Standaardwaarde: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Haalt het Pdf417-symbooltype van het foutcorrectieniveau van BarCode op, variërend van level0 tot level8; level0 betekent geen foutcorrectie-informatie, level8 betekent de beste foutcorrectie, wat een groter beeld betekent.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro-tekens 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met MicroPdf417 en codeert 916 en 917 MicroPdf417-modi. Standaardwaarde: MacroCharacters.None.

Deze voorbeelden laten zien hoe macro‑tekens te coderen in MicroPdf417

```

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 barcode geadresseerde naam (optioneel veld). MicroPDF417 barcode geadresseerde naam (optioneel veld voor Structured Append-modus)

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 barcode controlesom (optioneel veld). MicroPDF417 barcode controlesom (optioneel veld voor Structured Append-modus) Het controlesomveld bevat de waarde van de 16-bit (2 bytes) CRC-controlesom met behulp van het CCITT-16-polynoom. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Uitgebreide Kanaalinterpretatie-identifiers. Geldt voor Macro PDF417-tekstvelden.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


Bestands‑ID van de MacroPdf417‑barcode (verplicht veld). Bestands‑ID van de MicroPDF417‑barcode (verplicht veld voor Structured Append‑modus)

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 barcode bestandsnaam (optioneel veld). MicroPDF417 barcode bestandsnaam (optioneel veld voor Structured Append-modus)

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 bestandsgrootte (optioneel veld). MicroPDF417 bestandsgrootte (optioneel veld voor Structured Append-modus) Het bestandsgrootteveld bevat de grootte in bytes van het volledige bronbestand.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


Segment‑ID van de MacroPdf417‑barcode (verplicht veld), die begint bij 0 tot MacroSegmentsCount - 1. Segment‑ID van de MicroPDF417‑barcode (verplicht veld voor Structured Append‑modus)

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Aantal segmenten van de MacroPdf417‑barcode (optioneel veld). Aantal segmenten van de MicroPDF417‑barcode (optioneel veld voor Structured Append‑modus)

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 barcode afzendernaam (optioneel veld). MicroPDF417 barcode afzendernaam (optioneel veld voor Structured Append-modus)

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. Alleen toegepast voor Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 barcode tijdstempel (optioneel veld). MicroPDF417 barcode tijdstempel (optioneel veld voor Structured Append-modus)

**Returns:**
java.time.LocalDateTime
### getRows() {#getRows--}
```
public final int getRows()
```


Aantal rijen.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Of het Pdf417‑symbooltype van de barcode is ingekort (om ruimte te besparen). Ook bekend als CompactPDF417. De rechter‑rij‑indicator en het rechter‑stop‑patroon worden in deze modus verwijderd.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Kan alleen worden gebruikt met MicroPdf417 en codeert Code 128-emulatiemodi. Kan FNC1 coderen in de tweede positie in modi 908 en 909, en kan ook 910 en 911 coderen, wat alleen aangeeft dat herkende MicroPdf417 kan worden geïnterpreteerd als Code 128.

Deze voorbeelden laten zien hoe Code‑128‑emulatiemodi te coderen met FNC1 op de tweede positie en zonder. Op deze manier kan MicroPdf417 worden gedecodeerd als Code‑128‑barcode

```

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Definieert gekoppelde modi met GS1MicroPdf417, MicroPdf417 en Pdf417 barcodes Met GS1MicroPdf417 symbooltype codeert 906, 907, 912, 913, 914, 915 \u201cLinked\u201d UCC/EAN-128 modi Met MicroPdf417 en Pdf417 symbooltypes codeert 918 koppelingsvlag naar geassocieerde lineaire component anders dan een EAN.UCC

Deze voorbeelden laten zien hoe "Linked" UCC/EAN-128‑modi te coderen in GS1MicroPdf417 en de Linkage‑vlag (918) in MicroPdf417‑ en Pdf417‑barcodes

```

```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


Hoogte/breedteverhouding van 2D BarCode-module.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Kan alleen worden gebruikt met MicroPdf417 en codeert Code 128-emulatiemodi. Kan FNC1 coderen in de tweede positie in modi 908 en 909, en kan ook 910 en 911 coderen, wat alleen aangeeft dat herkende MicroPdf417 kan worden geïnterpreteerd als Code 128.

Deze voorbeelden laten zien hoe Code‑128‑emulatiemodi te coderen met FNC1 op de tweede positie en zonder. Op deze manier kan MicroPdf417 worden gedecodeerd als Code‑128‑barcode

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Aantal kolommen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Uitgebreide Kanaalinterpretatie-identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. Niet toegepast op Macro PDF417-tekstvelden. De huidige implementatie bestaat uit alle bekende tekensetcoderingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Identificeert de Pdf417‑codeermodus. Standaardwaarde: Auto.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Stelt het Pdf417-symbooltype van het foutcorrectieniveau van BarCode in, variërend van level0 tot level8; level0 betekent geen foutcorrectie-informatie, level8 betekent de beste foutcorrectie, wat een groter beeld betekent.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417-symbologie type van het foutcorrectieniveau van BarCode, variërend van level0 tot level8, level0 betekent geen foutcorrectie-informatie, level8 betekent de beste foutcorrectie, wat een groter beeld betekent. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Definieert gekoppelde modi met GS1MicroPdf417, MicroPdf417 en Pdf417 barcodes Met GS1MicroPdf417 symbooltype codeert 906, 907, 912, 913, 914, 915 \u201cLinked\u201d UCC/EAN-128 modi Met MicroPdf417 en Pdf417 symbooltypes codeert 918 koppelingsvlag naar geassocieerde lineaire component anders dan een EAN.UCC

Deze voorbeelden laten zien hoe "Linked" UCC/EAN-128‑modi te coderen in GS1MicroPdf417 en de Linkage‑vlag (918) in MicroPdf417‑ en Pdf417‑barcodes

```

 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked modes 906, 907 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());
 
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro-tekens 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met MicroPdf417 en codeert 916 en 917 MicroPdf417-modi. Standaardwaarde: MacroCharacters.None.

Deze voorbeelden laten zien hoe macro‑tekens te coderen in MicroPdf417

```

```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 barcode geadresseerde naam (optioneel veld). MicroPDF417 barcode geadresseerde naam (optioneel veld voor Structured Append-modus)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 barcode controlesom (optioneel veld). MicroPDF417 barcode controlesom (optioneel veld voor Structured Append-modus) Het controlesomveld bevat de waarde van de 16-bit (2 bytes) CRC-controlesom met behulp van het CCITT-16-polynoom. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Uitgebreide Kanaalinterpretatie-identifiers. Geldt voor Macro PDF417-tekstvelden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


Bestands‑ID van de MacroPdf417‑barcode (verplicht veld). Bestands‑ID van de MicroPDF417‑barcode (verplicht veld voor Structured Append‑modus)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 barcode bestandsnaam (optioneel veld). MicroPDF417 barcode bestandsnaam (optioneel veld voor Structured Append-modus)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 bestandsgrootte (optioneel veld). MicroPDF417 bestandsgrootte (optioneel veld voor Structured Append-modus) Het bestandsgrootteveld bevat de grootte in bytes van het volledige bronbestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


Segment‑ID van de MacroPdf417‑barcode (verplicht veld), die begint bij 0 tot MacroSegmentsCount - 1. Segment‑ID van de MicroPDF417‑barcode (verplicht veld voor Structured Append‑modus)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Aantal segmenten van de MacroPdf417‑barcode (optioneel veld). Aantal segmenten van de MicroPDF417‑barcode (optioneel veld voor Structured Append‑modus)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 barcode afzendernaam (optioneel veld). MicroPDF417 barcode afzendernaam (optioneel veld voor Structured Append-modus)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Wordt gebruikt om de encoder te vertellen of de Macro PDF417 Terminator (codewoord 922) aan het segment moet worden toegevoegd. Alleen toegepast voor Macro PDF417.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 barcode tijdstempel (optioneel veld). MicroPDF417 barcode tijdstempel (optioneel veld voor Structured Append-modus)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Aantal rijen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Of het Pdf417‑symbooltype van de barcode is ingekort (om ruimte te besparen). Ook bekend als CompactPDF417. De rechter‑rij‑indicator en het rechter‑stop‑patroon worden in deze modus verwijderd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - Een tekenreeks die deze [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters) vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

