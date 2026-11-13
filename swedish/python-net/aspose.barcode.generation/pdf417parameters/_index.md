---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

PDF417-parametrar. Innehåller PDF417, MacroPDF417, MicroPDF417 och GS1MicroPdf417 parametrar.<br/>            MacroPDF417 kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria.<br/>            MicroPDF417 i Structured Append-läge (samma som MacroPDF417-läge) kräver två fält: Pdf417MacroFileID och Pdf417MacroSegmentID. Alla andra fält är valfria.

Pdf417Parameters-typen exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| encode_mode | Identifierar Pdf417-kodningsläge. <br/>            Standardvärde: Auto. |
| error_level | Hämtar eller anger Pdf417-symbologityp för BarCodes felkorrigeringsnivå<br/>            som varierar från level0 till level8, level0 betyder ingen felkorrigeringsinformation,<br/>            level8 betyder bästa felkorrigering vilket innebär en större bild. |
| truncate | Anger om Pdf417-symbologityp för BarCode är trunkerad (för att minska utrymme). <br/>            Även känt som CompactPDF417. Höger radindikator och högra stoppmönster tas bort i detta läge. |
| kolumner | Antal kolumner. |
| rader | Antal rader. |
| aspect_ratio | Höjd/Bredd-förhållande för 2D BarCode-modulen. |
| macro_pdf_417_file_id | MacroPdf417-streckkodens fil-ID (obligatoriskt fält).<br/>            MicroPDF417-streckkodens fil-ID (obligatoriskt fält för Structured Append-läge) |
| macro_pdf_417_segment_id | MacroPdf417-streckkodens segment-ID (obligatoriskt fält), som startar från 0 till MacroSegmentsCount - 1.<br/>            MicroPDF417-streckkodens segment-ID (obligatoriskt fält för Structured Append-läge) |
| macro_pdf_417_segments_count | MacroPdf417-streckkodens segmentantal (valfritt fält).<br/>            MicroPDF417-streckkodens segmentantal (valfritt fält för Structured Append-läge) |
| macro_pdf_417_file_name | MacroPdf417-streckkodens filnamn (valfritt fält).<br/>            MicroPDF417-streckkodens filnamn (valfritt fält för Structured Append-läge) |
| macro_pdf_417_time_stamp | MacroPdf417-streckkodens tidsstämpel (valfritt fält).<br/>            MicroPDF417-streckkodens tidsstämpel (valfritt fält för Structured Append-läge) |
| macro_pdf_417_sender | MacroPdf417-streckkodens avsändarnamn (valfritt fält).<br/>            MicroPDF417-streckkodens avsändarnamn (valfritt fält för Structured Append-läge) |
| macro_pdf_417_addressee | MacroPdf417-streckkodens mottagarnamn (valfritt fält).<br/>            MicroPDF417-streckkodens mottagarnamn (valfritt fält för Structured Append-läge) |
| macro_pdf_417_file_size | MacroPdf417 filstorlek (valfritt fält).<br/>            MicroPDF417 filstorlek (valfritt fält för Structured Append-läge)<br/>            Filstorleksfältet innehåller storleken i byte för hela källfilen. |
| macro_pdf_417_checksum | MacroPdf417 streckkodskontrollsumma (valfritt fält).<br/>            MicroPDF417 streckkodskontrollsumma (valfritt fält för Structured Append-läge)<br/>            Kontrollsummefältet innehåller värdet av den 16-bitars (2 byte) CRC‑kontrollsumman som använder CCITT-16‑polynomet. x^16 + x^12 + x^5 + 1 |
| eci_encoding | Extended Channel Interpretation Identifierare. Den används för att ge streckkodsläsaren detaljer<br/>            om de använda referenserna för kodning av data i symbolen. Tillämpas inte för Macro PDF417‑textfält.<br/>            Aktuell implementation består av alla välkända teckenuppsättningskodningar. |
| macro_pdf_417eci_encoding | Extended Channel Interpretation Identifierare. Gäller för Macro PDF417‑textfält. |
| macro_pdf_417_terminator | Används för att tala om för kodaren om Macro PDF417 Terminator (kodord 922) ska läggas till segmentet. <br/>            Tillämpas endast för Macro PDF417. |
| is_reader_initialization | Används för att instruera läsaren att tolka data som finns i symbolen<br/>            som programmering för läsarens initiering. |
| macro_characters | Macro-tecken 05 och 06 används för att få en mer kompakt kodning i speciallägen.<br/>            Kan endast användas med MicroPdf417 och kodar 916 och 917 MicroPdf417‑lägen<br/>            Standardvärde: MacroCharacters.None. |
| is_linked | Definierar länkade lägen med GS1MicroPdf417-, MicroPdf417- och Pdf417‑streckkoder<br/>            Med GS1MicroPdf417‑symbologi kodar 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128‑lägen<br/>            Med MicroPdf417‑ och Pdf417‑symbologier kodar 918‑länkningsflagga till associerad linjär komponent annat än en EAN.UCC |
| is_code_128_emulation | Kan endast användas med MicroPdf417 och kodar Code 128‑emuleringslägen<br/>            Kan koda FNC1 i andra positions‑lägen 908 och 909, samt kan koda 910 och 911 som bara indikerar att en identifierad MicroPdf417 kan tolkas som Code 128 |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

