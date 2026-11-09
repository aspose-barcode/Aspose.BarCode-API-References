---
title: "Pdf417ParametersUI"
second_title: "Aspose.BarCode för Java API-referens"
description: "UI-omslag för klassen com.aspose.barcode.generation.Pdf417Parameters."
type: docs
weight: 16
url: /sv/java/com.aspose.barcode.barcodecontrol/pdf417parametersui/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417ParametersUI
```

UI-omslag för klassen com.aspose.barcode.generation.Pdf417Parameters.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Höjd/bredd-förhållande för 2D BarCode-modul. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Antal kolumner. |
| [getECIEncoding()](#getECIEncoding--) | Identifierare för utökad kanalinterpretation. |
| [getEncodeMode()](#getEncodeMode--) | Pdf417-symbologi typ för BarCode:s kodningsläge. |
| [getErrorLevel()](#getErrorLevel--) | Hämtar Pdf417-symbologi typ för BarCode:s felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild. |
| [getMacroCharacters()](#getMacroCharacters--) | Makrotecknen 05 och 06 används för att få en mer kompakt kodning i speciella lägen. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417 streckkod mottagarens namn (valfritt fält). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417 streckkod kontrollsumma (valfritt fält). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Identifierare för utökad kanalinterpretation. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Hämtar macro Pdf417 streckkodens fil‑ID. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 streckkod filnamn (valfritt fält). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 filstorlek (valfritt fält). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Hämtar macro Pdf417-streckkodens segment-ID, som börjar från 0 till MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Hämtar antalet segment i macro Pdf417-streckkod. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417-streckkodens avsändarnamn (valfritt fält). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417-streckkodens tidsstämpel (valfritt fält). |
| [getRows()](#getRows--) | Antal rader. |
| [getTruncate()](#getTruncate--) | Om Pdf417-symboltyp för BarCode är trunkerad (för att minska utrymme). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionslägen 908 och 909, samt kan koda 910 och 911 som bara indikerar att identifierad MicroPdf417 kan tolkas som Code 128. |
| [isLinked()](#isLinked--) | Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417-streckkoder. Med GS1MicroPdf417-symbol kodar 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128-lägen. Med MicroPdf417 och Pdf417-symboler kodar 918 länkningsflagga till associerad linjär komponent annan än en EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Höjd/bredd-förhållande för 2D BarCode-modul. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionslägen 908 och 909, samt kan koda 910 och 911 som bara indikerar att identifierad MicroPdf417 kan tolkas som Code 128. |
| [setColumns(int value)](#setColumns-int-) | Antal kolumner. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifierare för utökad kanalinterpretation. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Pdf417-symbologi typ för BarCode:s kodningsläge. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Ställer in Pdf417-symboltypens felkorrigeringsnivå för BarCode, från nivå0 till nivå8. Nivå0 betyder ingen felkorrigering, nivå8 betyder bästa felkorrigering vilket ger en större bild. |
| [setLinked(boolean value)](#setLinked-boolean-) | Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417-streckkoder. Med GS1MicroPdf417-symbol kodar 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128-lägen. Med MicroPdf417 och Pdf417-symboler kodar 918 länkningsflagga till associerad linjär komponent annan än en EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Makrotecknen 05 och 06 används för att få en mer kompakt kodning i speciella lägen. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417 streckkod mottagarens namn (valfritt fält). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417 streckkod kontrollsumma (valfritt fält). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Identifierare för utökad kanalinterpretation. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Ställer in macro Pdf417-streckkodens fil-ID. |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 streckkod filnamn (valfritt fält). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 filstorlek (valfritt fält). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Ställer in macro Pdf417-streckkodens segment-ID, som börjar från 0 till MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Ställer in antalet segment i macro Pdf417-streckkod. |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417-streckkodens avsändarnamn (valfritt fält). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417-streckkodens tidsstämpel (valfritt fält). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering. |
| [setRows(int value)](#setRows-int-) | Antal rader. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Om Pdf417-symboltyp för BarCode är trunkerad (för att minska utrymme). |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Höjd/bredd-förhållande för 2D BarCode-modul.

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


Antal kolumner.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Extended Channel Interpretation Identifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Tillämpas inte på Macro PDF417-textfält. Aktuell implementation består av alla välkända teckenuppsättningskodningar.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Pdf417-symboltypens kodningsläge för BarCode. Standardvärde: Pdf417EncodeMode.Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Hämtar Pdf417-symbologi typ för BarCode:s felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro-tecknen 05 och 06 används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med MicroPdf417 och kodar 916 och 917 MicroPdf417-lägen. Standardvärde: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417-streckkodens mottagarnamn (valfritt fält). MicroPDF417-streckkodens mottagarnamn (valfritt fält för Structured Append-läge).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417-streckkodens kontrollsumma (valfritt fält). MicroPDF417-streckkodens kontrollsumma (valfritt fält för Structured Append-läge). Kontrollsummafältet innehåller värdet av den 16-bitars (2 byte) CRC-kontrollsumman med CCITT-16-polynomet. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


Hämtar macro Pdf417-streckkodens fil-ID. Används för MacroPdf417.

**Returns:**
int - macro Pdf417-streckkodens fil-ID.
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417-streckkodens filnamn (valfritt fält). MicroPDF417-streckkodens filnamn (valfritt fält för Structured Append-läge).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge). Filstorleksfältet innehåller storleken i byte för hela källfilen.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


Hämtar macro Pdf417-streckkodens segment-ID, som börjar från 0 till MacroSegmentsCount - 1.

**Returns:**
int - macro Pdf417-streckkodens segment-ID, som börjar från 0 till MacroSegmentsCount - 1.
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Hämtar antalet segment i macro Pdf417-streckkod.

**Returns:**
int - macro Pdf417-streckkodens segmentantal.
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


Om Pdf417-symboltyp för BarCode är trunkerad (för att minska utrymme).

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


Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionslägen 908 och 909, samt kan koda 910 och 911 som bara indikerar att identifierad MicroPdf417 kan tolkas som Code 128.

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417-streckkoder. Med GS1MicroPdf417-symbol kodar 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128-lägen. Med MicroPdf417 och Pdf417-symboler kodar 918 länkningsflagga till associerad linjär komponent annan än en EAN.UCC.

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


Höjd/bredd-förhållande för 2D BarCode-modul.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionslägen 908 och 909, samt kan koda 910 och 911 som bara indikerar att identifierad MicroPdf417 kan tolkas som Code 128.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Antal kolumner.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation Identifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Tillämpas inte på Macro PDF417-textfält. Aktuell implementation består av alla välkända teckenuppsättningskodningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Pdf417-symboltypens kodningsläge för BarCode. Standardvärde: Pdf417EncodeMode.Auto.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Ställer in Pdf417-symboltypens felkorrigeringsnivå för BarCode, från nivå0 till nivå8. Nivå0 betyder ingen felkorrigering, nivå8 betyder bästa felkorrigering vilket ger en större bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Pdf417-symbologi typ av BarCode:s felkorrigeringsnivå som varierar från nivå0 till nivå8, nivå0 betyder ingen felkorrigeringsinformation, nivå8 betyder bästa felkorrigering vilket innebär en större bild. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417-streckkoder. Med GS1MicroPdf417-symbol kodar 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d UCC/EAN-128-lägen. Med MicroPdf417 och Pdf417-symboler kodar 918 länkningsflagga till associerad linjär komponent annan än en EAN.UCC.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro-tecknen 05 och 06 används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med MicroPdf417 och kodar 916 och 917 MicroPdf417-lägen. Standardvärde: MacroCharacters.None.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417-streckkodens mottagarnamn (valfritt fält). MicroPDF417-streckkodens mottagarnamn (valfritt fält för Structured Append-läge).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417-streckkodens kontrollsumma (valfritt fält). MicroPDF417-streckkodens kontrollsumma (valfritt fält för Structured Append-läge). Kontrollsummafältet innehåller värdet av den 16-bitars (2 byte) CRC-kontrollsumman med CCITT-16-polynomet. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


Ställer in macro Pdf417 streckkods fil-ID. Används för MacroPdf417.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | macro Pdf417 streckkods fil-ID. |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417-streckkodens filnamn (valfritt fält). MicroPDF417-streckkodens filnamn (valfritt fält för Structured Append-läge).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge). Filstorleksfältet innehåller storleken i byte för hela källfilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


Ställer in macro Pdf417-streckkodens segment-ID, som börjar från 0 till MacroSegmentsCount - 1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | macro Pdf417 streckkods segment-ID, som startar från 0 till MacroSegmentsCount - 1. |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Ställer in antalet segment i macro Pdf417-streckkod.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | macro Pdf417 streckkod segmentantal. |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 streckkod avsändarnamn (valfritt fält). MicroPDF417 streckkod avsändarnamn (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. Tillämpas endast för Macro PDF417.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 streckkod tidsstämpel (valfritt fält). MicroPDF417 streckkod tidsstämpel (valfritt fält för Structured Append-läge)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarens initiering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Antal rader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Om Pdf417-symboltyp för BarCode är trunkerad (för att minska utrymme).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - En sträng som representerar detta [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

