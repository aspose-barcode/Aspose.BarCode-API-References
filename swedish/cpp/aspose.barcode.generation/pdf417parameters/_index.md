---
title: "Aspose::BarCode::Generation::Pdf417Parameters-klass"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::Pdf417Parameters-klass. PDF417-parametrar. Innehåller PDF417-, MacroPDF417-, MicroPDF417- och GS1MicroPdf417-parametrar. MacroPDF417 kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria. MicroPDF417 i Structured Append-läge (samma som MacroPDF417-läge) kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria i C++."
type: docs
weight: 4000
url: /sv/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


PDF417-parametrar. Innehåller PDF417, MacroPDF417, MicroPDF417 och GS1MicroPdf417 parametrar. MacroPDF417 kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria. MicroPDF417 i Structured Append-läge (samma som MacroPDF417-läge) kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria.

```cpp
class Pdf417Parameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Höjd/bredd‑förhållande för 2D‑[BarCode](../../aspose.barcode/)-modulen. |
| [get_Columns](./get_columns/)() const | Antal kolumner. |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Tillämpas inte för Macro PDF417-textfält. Den nuvarande implementeringen består av alla välkända teckenkodningsuppsättningar. |
| [get_EncodeMode](./get_encodemode/)() const | Identifierar Pdf417-kodningsläge. Standardvärde: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Hämtar Pdf417-symbologityp för [BarCode](../../aspose.barcode/)'s felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionslägena 908 och 909, samt kan koda 910 och 911 som bara indikerar att identifierad MicroPdf417 kan tolkas som Code 128. |
| [get_IsLinked](./get_islinked/)() const | Definierar länkade lägen med GS1MicroPdf417-, MicroPdf417- och Pdf417-streckkoder. Med GS1MicroPdf417-symbologi kodas 906, 907, 912, 913, 914, 915 “Länkade” UCC/EAN-128-lägen. Med MicroPdf417- och Pdf417-symbologier kodas 918-länkningsflagga till associerad linjär komponent annan än en EAN.UCC. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering. |
| [get_MacroCharacters](./get_macrocharacters/)() const | Macro-tecknen 05 och 06 används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med MicroPdf417 och kodar 916 och 917 MicroPdf417-lägen. Standardvärde: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | MacroPdf417-streckkod mottagarnamn (valfritt fält). MicroPDF417-streckkod mottagarnamn (valfritt fält för Structured Append-läge). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | MacroPdf417-streckkod kontrollsumma (valfritt fält). MicroPDF417-streckkod kontrollsumma (valfritt fält för Structured Append-läge). Kontrollsummafältet innehåller värdet av den 16-bitars (2 byte) CRC-kontrollen med CCITT-16-polynomet. x^16 + x^12 + x^5 + 1 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417-streckkodens fil-ID (obligatoriskt fält). MicroPDF417-streckkodens fil-ID (obligatoriskt fält för Structured Append-läge). |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | MacroPdf417-streckkod filnamn (valfritt fält). MicroPDF417-streckkod filnamn (valfritt fält för Structured Append-läge). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge). Filstorleksfältet innehåller storleken i byte för hela källfilen. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | MacroPdf417-streckkodens segment-ID (obligatoriskt fält), som startar från 0 till MacroSegmentsCount - 1. MicroPDF417-streckkodens segment-ID (obligatoriskt fält för Structured Append-läge). |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | MacroPdf417 streckkodsegmentantal (valfritt fält). MicroPDF417 streckkodsegmentantal (valfritt fält för Structured Append-läge) |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | MacroPdf417 streckkodavsändarnamn (valfritt fält). MicroPDF417 streckkodavsändarnamn (valfritt fält för Structured Append-läge) |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. Tillämpas endast för Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | MacroPdf417 streckkodtidsstämpel (valfritt fält). MicroPDF417 streckkodtidsstämpel (valfritt fält för Structured Append-läge) |
| [get_Rows](./get_rows/)() const | Antal rader. |
| [get_Truncate](./get_truncate/)() const | Om Pdf417-symbologi-typ för [BarCode](../../aspose.barcode/) är trunkerad (för att minska utrymme). Även känd som CompactPDF417. Höger radindikator och höger stoppmönster tas bort i detta läge. |
| [set_AspectRatio](./set_aspectratio/)(float) | Höjd/bredd‑förhållande för 2D‑[BarCode](../../aspose.barcode/)-modulen. |
| [set_Columns](./set_columns/)(int32_t) | Antal kolumner. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Tillämpas inte för Macro PDF417-textfält. Den nuvarande implementeringen består av alla välkända teckenkodningsuppsättningar. |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Identifierar Pdf417-kodningsläge. Standardvärde: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | Ställer in Pdf417-symbologi-typ för [BarCode](../../aspose.barcode/)'s felkorrigeringsnivå som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation, level8 betyder bästa felkorrigering vilket innebär en större bild. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | Kan endast användas med MicroPdf417 och kodar Code 128-emuleringslägen. Kan koda FNC1 i andra positionslägena 908 och 909, samt kan koda 910 och 911 som bara indikerar att identifierad MicroPdf417 kan tolkas som Code 128. |
| [set_IsLinked](./set_islinked/)(bool) | Definierar länkade lägen med GS1MicroPdf417-, MicroPdf417- och Pdf417-streckkoder. Med GS1MicroPdf417-symbologi kodas 906, 907, 912, 913, 914, 915 “Länkade” UCC/EAN-128-lägen. Med MicroPdf417- och Pdf417-symbologier kodas 918-länkningsflagga till associerad linjär komponent annan än en EAN.UCC. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Macro-tecknen 05 och 06 används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med MicroPdf417 och kodar 916 och 917 MicroPdf417-lägen. Standardvärde: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | MacroPdf417-streckkod mottagarnamn (valfritt fält). MicroPDF417-streckkod mottagarnamn (valfritt fält för Structured Append-läge). |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | MacroPdf417-streckkod kontrollsumma (valfritt fält). MicroPDF417-streckkod kontrollsumma (valfritt fält för Structured Append-läge). Kontrollsummafältet innehåller värdet av den 16-bitars (2 byte) CRC-kontrollen med CCITT-16-polynomet. x^16 + x^12 + x^5 + 1 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifierare. Gäller för Macro PDF417-textfält. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | MacroPdf417-streckkodens fil-ID (obligatoriskt fält). MicroPDF417-streckkodens fil-ID (obligatoriskt fält för Structured Append-läge). |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | MacroPdf417-streckkod filnamn (valfritt fält). MicroPDF417-streckkod filnamn (valfritt fält för Structured Append-läge). |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | MacroPdf417 filstorlek (valfritt fält). MicroPDF417 filstorlek (valfritt fält för Structured Append-läge). Filstorleksfältet innehåller storleken i byte för hela källfilen. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | MacroPdf417-streckkodens segment-ID (obligatoriskt fält), som startar från 0 till MacroSegmentsCount - 1. MicroPDF417-streckkodens segment-ID (obligatoriskt fält för Structured Append-läge). |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | MacroPdf417 streckkodsegmentantal (valfritt fält). MicroPDF417 streckkodsegmentantal (valfritt fält för Structured Append-läge) |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | MacroPdf417 streckkodavsändarnamn (valfritt fält). MicroPDF417 streckkodavsändarnamn (valfritt fält för Structured Append-läge) |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till i segmentet. Tillämpas endast för Macro PDF417. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | MacroPdf417 streckkodtidsstämpel (valfritt fält). MicroPDF417 streckkodtidsstämpel (valfritt fält för Structured Append-läge) |
| [set_Rows](./set_rows/)(int32_t) | Antal rader. |
| [set_Truncate](./set_truncate/)(bool) | Om Pdf417-symbologi-typ för [BarCode](../../aspose.barcode/) är trunkerad (för att minska utrymme). Även känd som CompactPDF417. Höger radindikator och höger stoppmönster tas bort i detta läge. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [Pdf417Parameters](./). |
## Anmärkningar


Dessa exempel visar hur man kodar UCC/EAN-128 icke länkade lägen i GS1MicroPdf417
```cpp
[C#]
//Kodar GS1 UCC/EAN-128 icke länkat läge 905 med AI 01 (GTIN)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Kodar GS1 UCC/EAN-128 icke länkade lägen 903, 904 med valfri AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
