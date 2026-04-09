---
title: Pdf417Parameters
second_title: Aspose.BarCode for Android via Java API-referens
description: PDF417‑parametrar.
type: docs
weight: 60
url: /sv/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417‑parametrar. Innehåller PDF417-, MacroPDF417-, MicroPDF417- och GS1MicroPdf417‑parametrar. MacroPDF417 kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria. MicroPDF417 i Structured Append‑läge (samma som MacroPDF417‑läge) kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria.

Dessa exempel visar hur man kodar UCC/EAN-128 icke‑länkade lägen i GS1MicroPdf417

```

 [C#]
 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Kolumnantal. |
| [getECIEncoding()](#getECIEncoding--) | Identifierare för utökad kanalinterpretation. |
| [getEncodeMode()](#getEncodeMode--) | Identifierar Pdf417‑kodningsläge. |
| [getErrorLevel()](#getErrorLevel--) | Hämtar Pdf417‑symbology‑typ för BarCodes felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild. |
| [getMacroCharacters()](#getMacroCharacters--) | Macro-tecken 05 och 06 används för att få en mer kompakt kodning i speciallägen. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417‑streckkod mottagarnamn (valfritt fält). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417‑streckkod kontrollsumma (valfritt fält). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Identifierare för utökad kanalinterpretation. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | MacroPdf417‑streckkodens fil‑ID (obligatoriskt fält). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 streckkod filnamn (valfritt fält). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 filstorlek (valfritt fält). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | MacroPdf417 streckkods segment-ID (Obligatoriskt fält), som börjar från 0 till MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | MacroPdf417 streckkod segmentantal (valfritt fält). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 streckkod avsändarnamn (valfritt fält). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 streckkod tidsstämpel (valfritt fält). |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | Pdf417-symbologi typ för BarCode:s kompakteringsläge. |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | Identifierare för utökad kanalinterpretation. |
| [getPdf417EncodeMode()](#getPdf417EncodeMode--) | Identifierar Pdf417‑kodningsläge. |
| [getPdf417ErrorLevel()](#getPdf417ErrorLevel--) | Hämtar Pdf417‑symbology‑typ för BarCodes felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild. |
| [getPdf417MacroAddressee()](#getPdf417MacroAddressee--) | MacroPdf417‑streckkod mottagarnamn (valfritt fält). |
| [getPdf417MacroChecksum()](#getPdf417MacroChecksum--) | MacroPdf417‑streckkod kontrollsumma (valfritt fält). |
| [getPdf417MacroECIEncoding()](#getPdf417MacroECIEncoding--) | Identifierare för utökad kanalinterpretation. |
| [getPdf417MacroFileID()](#getPdf417MacroFileID--) | MacroPdf417‑streckkodens fil‑ID (obligatoriskt fält). |
| [getPdf417MacroFileName()](#getPdf417MacroFileName--) | MacroPdf417 streckkod filnamn (valfritt fält). |
| [getPdf417MacroFileSize()](#getPdf417MacroFileSize--) | MacroPdf417 filstorlek (valfritt fält). |
| [getPdf417MacroSegmentID()](#getPdf417MacroSegmentID--) | MacroPdf417 streckkods segment-ID (Obligatoriskt fält), som börjar från 0 till MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getPdf417MacroSegmentsCount--) | MacroPdf417 streckkod segmentantal (valfritt fält). |
| [getPdf417MacroSender()](#getPdf417MacroSender--) | MacroPdf417 streckkod avsändarnamn (valfritt fält). |
| [getPdf417MacroTerminator()](#getPdf417MacroTerminator--) | Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. |
| [getPdf417MacroTimeStamp()](#getPdf417MacroTimeStamp--) | MacroPdf417 streckkod tidsstämpel (valfritt fält). |
| [getPdf417Truncate()](#getPdf417Truncate--) | Om Pdf417-symbologi typ för BarCode är trunkerad (för att minska utrymme). |
| [getRows()](#getRows--) | Antal rader. |
| [getTruncate()](#getTruncate--) | Om Pdf417-symbologi typ för BarCode är trunkerad (för att minska utrymme). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionen lägen 908 och 909, kan också koda 910 och 911 som bara indikerar att igenkänd MicroPdf417 kan tolkas som Code 128. |
| [isLinked()](#isLinked--) | Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417 streckkoder. Med GS1MicroPdf417-symbologi kodas 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128-lägen. Med MicroPdf417- och Pdf417-symbologier kodas 918 länkningsflagga till associerad linjär komponent annat än en EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höjd/bredd-förhållande för 2D BarCode-modulen. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionen lägen 908 och 909, kan också koda 910 och 911 som bara indikerar att igenkänd MicroPdf417 kan tolkas som Code 128. |
| [setColumns(int value)](#setColumns-int-) | Kolumnantal. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifierare för utökad kanalinterpretation. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identifierar Pdf417‑kodningsläge. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Ställer in Pdf417-symbologi typ för BarCode:s felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild. |
| [setLinked(boolean value)](#setLinked-boolean-) | Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417 streckkoder. Med GS1MicroPdf417-symbologi kodas 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128-lägen. Med MicroPdf417- och Pdf417-symbologier kodas 918 länkningsflagga till associerad linjär komponent annat än en EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Macro-tecken 05 och 06 används för att få en mer kompakt kodning i speciallägen. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417‑streckkod mottagarnamn (valfritt fält). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417‑streckkod kontrollsumma (valfritt fält). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Identifierare för utökad kanalinterpretation. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | MacroPdf417‑streckkodens fil‑ID (obligatoriskt fält). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 streckkod filnamn (valfritt fält). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 filstorlek (valfritt fält). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | MacroPdf417 streckkods segment-ID (Obligatoriskt fält), som börjar från 0 till MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | MacroPdf417 streckkod segmentantal (valfritt fält). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 streckkod avsändarnamn (valfritt fält). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 streckkod tidsstämpel (valfritt fält). |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | Pdf417-symbologi typ för BarCode:s kompakteringsläge. |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | Identifierare för utökad kanalinterpretation. |
| [setPdf417EncodeMode(Pdf417EncodeMode value)](#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Identifierar Pdf417‑kodningsläge. |
| [setPdf417ErrorLevel(Pdf417ErrorLevel value)](#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Ställer in Pdf417-symbologi typ för BarCode:s felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild. |
| [setPdf417MacroAddressee(String value)](#setPdf417MacroAddressee-java.lang.String-) | MacroPdf417‑streckkod mottagarnamn (valfritt fält). |
| [setPdf417MacroChecksum(int value)](#setPdf417MacroChecksum-int-) | MacroPdf417‑streckkod kontrollsumma (valfritt fält). |
| [setPdf417MacroECIEncoding(int value)](#setPdf417MacroECIEncoding-int-) | Identifierare för utökad kanalinterpretation. |
| [setPdf417MacroFileID(int value)](#setPdf417MacroFileID-int-) | MacroPdf417‑streckkodens fil‑ID (obligatoriskt fält). |
| [setPdf417MacroFileName(String value)](#setPdf417MacroFileName-java.lang.String-) | MacroPdf417 streckkod filnamn (valfritt fält). |
| [setPdf417MacroFileSize(int value)](#setPdf417MacroFileSize-int-) | MacroPdf417 filstorlek (valfritt fält). |
| [setPdf417MacroSegmentID(int value)](#setPdf417MacroSegmentID-int-) | MacroPdf417 streckkods segment-ID (Obligatoriskt fält), som börjar från 0 till MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount(int value)](#setPdf417MacroSegmentsCount-int-) | MacroPdf417 streckkod segmentantal (valfritt fält). |
| [setPdf417MacroSender(String value)](#setPdf417MacroSender-java.lang.String-) | MacroPdf417 streckkod avsändarnamn (valfritt fält). |
| [setPdf417MacroTerminator(Pdf417MacroTerminator value)](#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. |
| [setPdf417MacroTimeStamp(LocalDateTime value)](#setPdf417MacroTimeStamp-java.time.LocalDateTime-) | MacroPdf417 streckkod tidsstämpel (valfritt fält). |
| [setPdf417Truncate(boolean value)](#setPdf417Truncate-boolean-) | Om Pdf417-symbologi typ för BarCode är trunkerad (för att minska utrymme). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [setRows(int value)](#setRows-int-) | Antal rader. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Om Pdf417-symbologi typ för BarCode är trunkerad (för att minska utrymme). |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Höjd/bredd-förhållande för 2D BarCode-modulen.

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


Kolumnantal.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Extended Channel Interpretation Identifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Tillämpas inte för Macro PDF417 textfält. Aktuell implementation består av alla välkända teckenkodningar.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Identifierar Pdf417-kodningsläge. Standardvärde: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Hämtar Pdf417‑symbology‑typ för BarCodes felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro-tecken 05 och 06 värden används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med MicroPdf417 och kodar 916 och 917 MicroPdf417-lägen. Standardvärde: MacroCharacters.None.

Dessa exempel visar hur man kodar Macro-tecken i MicroPdf417

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 streckkod mottagarnamn (valfritt fält). MicroPDF417 streckkod mottagarnamn (valfritt fält för Structured Append-läge)

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 streckkod kontrollsumma (valfritt fält). MicroPDF417 streckkod kontrollsumma (valfritt fält för Structured Append-läge) Kontrollsummefältet innehåller värdet av den 16-bitars (2 byte) CRC-kontrollsumman med CCITT-16-polynomet. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Extended Channel Interpretation Identifierare. Gäller för Macro PDF417 textfält.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


MacroPdf417 streckkods fil-ID (Obligatoriskt fält). MicroPDF417 streckkods fil-ID (Obligatoriskt fält för Structured Append-läge)

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 streckkod filnamn (valfritt fält). MicroPDF417 streckkod filnamn (valfritt fält för Structured Append-läge)

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge) Filstorleksfältet innehåller storleken i byte för hela källfilen.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


MacroPdf417 streckkods segment-ID (Obligatoriskt fält), som börjar från 0 till MacroSegmentsCount - 1. MicroPDF417 streckkods segment-ID (Obligatoriskt fält för Structured Append-läge)

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


MacroPdf417 streckkod segmentantal (valfritt fält). MicroPDF417 streckkod segmentantal (valfritt fält för Structured Append-läge)

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 streckkod avsändarnamn (valfritt fält). MicroPDF417 streckkod avsändarnamn (valfritt fält för Structured Append-läge)

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. Tillämpas endast för Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 streckkod tidsstämpel (valfritt fält). MicroPDF417 streckkod tidsstämpel (valfritt fält för Structured Append-läge)

**Returns:**
java.time.LocalDateTime
### getPdf417CompactionMode() {#getPdf417CompactionMode--}
```
public final Pdf417CompactionMode getPdf417CompactionMode()
```


Pdf417-symboltyp för BarCode:s kompakteringsläge. Standardvärde: Pdf417CompactionMode.Auto.

**Returns:**
[Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode)
### getPdf417ECIEncoding() {#getPdf417ECIEncoding--}
```
public final int getPdf417ECIEncoding()
```


Extended Channel Interpretation Identifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Tillämpas inte för Macro PDF417 textfält. Aktuell implementation består av alla välkända teckenkodningar.

**Returns:**
int
### getPdf417EncodeMode() {#getPdf417EncodeMode--}
```
public final Pdf417EncodeMode getPdf417EncodeMode()
```


Identifierar Pdf417-kodningsläge. Standardvärde: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getPdf417ErrorLevel() {#getPdf417ErrorLevel--}
```
public final Pdf417ErrorLevel getPdf417ErrorLevel()
```


Hämtar Pdf417‑symbology‑typ för BarCodes felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getPdf417MacroAddressee() {#getPdf417MacroAddressee--}
```
public final String getPdf417MacroAddressee()
```


MacroPdf417 streckkod mottagarnamn (valfritt fält). MicroPDF417 streckkod mottagarnamn (valfritt fält för Structured Append-läge)

**Returns:**
java.lang.String
### getPdf417MacroChecksum() {#getPdf417MacroChecksum--}
```
public final int getPdf417MacroChecksum()
```


MacroPdf417 streckkod kontrollsumma (valfritt fält). MicroPDF417 streckkod kontrollsumma (valfritt fält för Structured Append-läge) Kontrollsummefältet innehåller värdet av den 16-bitars (2 byte) CRC-kontrollsumman med CCITT-16-polynomet. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getPdf417MacroECIEncoding() {#getPdf417MacroECIEncoding--}
```
public final int getPdf417MacroECIEncoding()
```


Extended Channel Interpretation Identifierare. Gäller för Macro PDF417 textfält.

**Returns:**
int
### getPdf417MacroFileID() {#getPdf417MacroFileID--}
```
public final int getPdf417MacroFileID()
```


MacroPdf417 streckkods fil-ID (Obligatoriskt fält). MicroPDF417 streckkods fil-ID (Obligatoriskt fält för Structured Append-läge)

**Returns:**
int
### getPdf417MacroFileName() {#getPdf417MacroFileName--}
```
public final String getPdf417MacroFileName()
```


MacroPdf417 streckkod filnamn (valfritt fält). MicroPDF417 streckkod filnamn (valfritt fält för Structured Append-läge)

**Returns:**
java.lang.String
### getPdf417MacroFileSize() {#getPdf417MacroFileSize--}
```
public final int getPdf417MacroFileSize()
```


MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge) Filstorleksfältet innehåller storleken i byte för hela källfilen.

**Returns:**
int
### getPdf417MacroSegmentID() {#getPdf417MacroSegmentID--}
```
public final int getPdf417MacroSegmentID()
```


MacroPdf417 streckkods segment-ID (Obligatoriskt fält), som börjar från 0 till MacroSegmentsCount - 1. MicroPDF417 streckkods segment-ID (Obligatoriskt fält för Structured Append-läge)

**Returns:**
int
### getPdf417MacroSegmentsCount() {#getPdf417MacroSegmentsCount--}
```
public final int getPdf417MacroSegmentsCount()
```


MacroPdf417 streckkod segmentantal (valfritt fält). MicroPDF417 streckkod segmentantal (valfritt fält för Structured Append-läge)

**Returns:**
int
### getPdf417MacroSender() {#getPdf417MacroSender--}
```
public final String getPdf417MacroSender()
```


MacroPdf417 streckkod avsändarnamn (valfritt fält). MicroPDF417 streckkod avsändarnamn (valfritt fält för Structured Append-läge)

**Returns:**
java.lang.String
### getPdf417MacroTerminator() {#getPdf417MacroTerminator--}
```
public final Pdf417MacroTerminator getPdf417MacroTerminator()
```


Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. Tillämpas endast för Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getPdf417MacroTimeStamp() {#getPdf417MacroTimeStamp--}
```
public final LocalDateTime getPdf417MacroTimeStamp()
```


MacroPdf417 streckkod tidsstämpel (valfritt fält). MicroPDF417 streckkod tidsstämpel (valfritt fält för Structured Append-läge)

**Returns:**
java.time.LocalDateTime
### getPdf417Truncate() {#getPdf417Truncate--}
```
public final boolean getPdf417Truncate()
```


Om Pdf417-symboltyp för BarCode är trunkerad (för att minska utrymme). Även känt som CompactPDF417. Höger radindikator och högerrastningsmönster tas bort i detta läge.

**Returns:**
boolean
### getRows() {#getRows--}
```
public final int getRows()
```


Antal rader.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Om Pdf417-symboltyp för BarCode är trunkerad (för att minska utrymme). Även känt som CompactPDF417. Höger radindikator och högerrastningsmönster tas bort i detta läge.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionen lägen 908 och 909, kan också koda 910 och 911 som bara indikerar att igenkänd MicroPdf417 kan tolkas som Code 128.

Dessa exempel visar hur man kodar Code 128-emuleringslägen med FNC1 i andra positionen och utan. På så sätt kan MicroPdf417 avkodas som en Code 128-streckkod

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

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417 streckkoder. Med GS1MicroPdf417-symbologi kodas 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128-lägen. Med MicroPdf417- och Pdf417-symbologier kodas 918 länkningsflagga till associerad linjär komponent annat än en EAN.UCC.

Dessa exempel visar hur man kodar \"Linked\" UCC/EAN-128-lägen i GS1MicroPdf417 och Linkage Flag (918) i MicroPdf417- och Pdf417-streckkoder

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering.

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


Höjd/bredd-förhållande för 2D BarCode-modulen.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionen lägen 908 och 909, kan också koda 910 och 911 som bara indikerar att igenkänd MicroPdf417 kan tolkas som Code 128.

Dessa exempel visar hur man kodar Code 128-emuleringslägen med FNC1 i andra positionen och utan. På så sätt kan MicroPdf417 avkodas som en Code 128-streckkod

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Kolumnantal.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation Identifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Tillämpas inte för Macro PDF417 textfält. Aktuell implementation består av alla välkända teckenkodningar.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Identifierar Pdf417-kodningsläge. Standardvärde: Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Ställer in Pdf417-symbologi typ för BarCode:s felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417-symboltyp för BarCode:s felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417 streckkoder. Med GS1MicroPdf417-symbologi kodas 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128-lägen. Med MicroPdf417- och Pdf417-symbologier kodas 918 länkningsflagga till associerad linjär komponent annat än en EAN.UCC.

Dessa exempel visar hur man kodar \"Linked\" UCC/EAN-128-lägen i GS1MicroPdf417 och Linkage Flag (918) i MicroPdf417- och Pdf417-streckkoder

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro-tecken 05 och 06 värden används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med MicroPdf417 och kodar 916 och 917 MicroPdf417-lägen. Standardvärde: MacroCharacters.None.

Dessa exempel visar hur man kodar Macro-tecken i MicroPdf417

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 streckkod mottagarnamn (valfritt fält). MicroPDF417 streckkod mottagarnamn (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 streckkod kontrollsumma (valfritt fält). MicroPDF417 streckkod kontrollsumma (valfritt fält för Structured Append-läge) Kontrollsummefältet innehåller värdet av den 16-bitars (2 byte) CRC-kontrollsumman med CCITT-16-polynomet. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Extended Channel Interpretation Identifierare. Gäller för Macro PDF417 textfält.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


MacroPdf417 streckkods fil-ID (Obligatoriskt fält). MicroPDF417 streckkods fil-ID (Obligatoriskt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 streckkod filnamn (valfritt fält). MicroPDF417 streckkod filnamn (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge) Filstorleksfältet innehåller storleken i byte för hela källfilen.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


MacroPdf417 streckkods segment-ID (Obligatoriskt fält), som börjar från 0 till MacroSegmentsCount - 1. MicroPDF417 streckkods segment-ID (Obligatoriskt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


MacroPdf417 streckkod segmentantal (valfritt fält). MicroPDF417 streckkod segmentantal (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 streckkod avsändarnamn (valfritt fält). MicroPDF417 streckkod avsändarnamn (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. Tillämpas endast för Macro PDF417.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 streckkod tidsstämpel (valfritt fält). MicroPDF417 streckkod tidsstämpel (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDateTime |  |

### setPdf417CompactionMode(Pdf417CompactionMode value) {#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-}
```
public final void setPdf417CompactionMode(Pdf417CompactionMode value)
```


Pdf417-symboltyp för BarCode:s kompakteringsläge. Standardvärde: Pdf417CompactionMode.Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode) |  |

### setPdf417ECIEncoding(int value) {#setPdf417ECIEncoding-int-}
```
public final void setPdf417ECIEncoding(int value)
```


Extended Channel Interpretation Identifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Tillämpas inte för Macro PDF417 textfält. Aktuell implementation består av alla välkända teckenkodningar.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPdf417EncodeMode(Pdf417EncodeMode value) {#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setPdf417EncodeMode(Pdf417EncodeMode value)
```


Identifierar Pdf417-kodningsläge. Standardvärde: Auto.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setPdf417ErrorLevel(Pdf417ErrorLevel value) {#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setPdf417ErrorLevel(Pdf417ErrorLevel value)
```


Ställer in Pdf417-symbologi typ för BarCode:s felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417-symboltyp för BarCode:s felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild. |

### setPdf417MacroAddressee(String value) {#setPdf417MacroAddressee-java.lang.String-}
```
public final void setPdf417MacroAddressee(String value)
```


MacroPdf417 streckkod mottagarnamn (valfritt fält). MicroPDF417 streckkod mottagarnamn (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPdf417MacroChecksum(int value) {#setPdf417MacroChecksum-int-}
```
public final void setPdf417MacroChecksum(int value)
```


MacroPdf417 streckkod kontrollsumma (valfritt fält). MicroPDF417 streckkod kontrollsumma (valfritt fält för Structured Append-läge) Kontrollsummefältet innehåller värdet av den 16-bitars (2 byte) CRC-kontrollsumman med CCITT-16-polynomet. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPdf417MacroECIEncoding(int value) {#setPdf417MacroECIEncoding-int-}
```
public final void setPdf417MacroECIEncoding(int value)
```


Extended Channel Interpretation Identifierare. Gäller för Macro PDF417 textfält.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPdf417MacroFileID(int value) {#setPdf417MacroFileID-int-}
```
public final void setPdf417MacroFileID(int value)
```


MacroPdf417 streckkods fil-ID (Obligatoriskt fält). MicroPDF417 streckkods fil-ID (Obligatoriskt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPdf417MacroFileName(String value) {#setPdf417MacroFileName-java.lang.String-}
```
public final void setPdf417MacroFileName(String value)
```


MacroPdf417 streckkod filnamn (valfritt fält). MicroPDF417 streckkod filnamn (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPdf417MacroFileSize(int value) {#setPdf417MacroFileSize-int-}
```
public final void setPdf417MacroFileSize(int value)
```


MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge) Filstorleksfältet innehåller storleken i byte för hela källfilen.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPdf417MacroSegmentID(int value) {#setPdf417MacroSegmentID-int-}
```
public final void setPdf417MacroSegmentID(int value)
```


MacroPdf417 streckkods segment-ID (Obligatoriskt fält), som börjar från 0 till MacroSegmentsCount - 1. MicroPDF417 streckkods segment-ID (Obligatoriskt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPdf417MacroSegmentsCount(int value) {#setPdf417MacroSegmentsCount-int-}
```
public final void setPdf417MacroSegmentsCount(int value)
```


MacroPdf417 streckkod segmentantal (valfritt fält). MicroPDF417 streckkod segmentantal (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setPdf417MacroSender(String value) {#setPdf417MacroSender-java.lang.String-}
```
public final void setPdf417MacroSender(String value)
```


MacroPdf417 streckkod avsändarnamn (valfritt fält). MicroPDF417 streckkod avsändarnamn (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPdf417MacroTerminator(Pdf417MacroTerminator value) {#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setPdf417MacroTerminator(Pdf417MacroTerminator value)
```


Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. Tillämpas endast för Macro PDF417.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setPdf417MacroTimeStamp(LocalDateTime value) {#setPdf417MacroTimeStamp-java.time.LocalDateTime-}
```
public final void setPdf417MacroTimeStamp(LocalDateTime value)
```


MacroPdf417 streckkod tidsstämpel (valfritt fält). MicroPDF417 streckkod tidsstämpel (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDateTime |  |

### setPdf417Truncate(boolean value) {#setPdf417Truncate-boolean-}
```
public final void setPdf417Truncate(boolean value)
```


Om Pdf417-symboltyp för BarCode är trunkerad (för att minska utrymme). Även känt som CompactPDF417. Höger radindikator och högerrastningsmönster tas bort i detta läge.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Antal rader.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Om Pdf417-symboltyp för BarCode är trunkerad (för att minska utrymme). Även känt som CompactPDF417. Höger radindikator och högerrastningsmönster tas bort i detta läge.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String – En sträng som representerar detta [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

