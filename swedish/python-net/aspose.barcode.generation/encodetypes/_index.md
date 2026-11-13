---
title: "EncodeTypes"
second_title: "Aspose.BarCode för Python via .NET API-referens"
description: 
type: docs
url: /sv/python-net/aspose.barcode.generation/encodetypes/
---

## EncodeTypes class

Anger vilken typ av streckkod som ska kodas.

Typen EncodeTypes exponerar följande medlemmar:
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| all_encode_types | Anger att data kommer att kontrolleras med alla tillgängliga symboler. |
| NONE | Ospecificerad kodningstyp. |
| CODABAR | Anger att data ska kodas enligt CODABAR streckkodsspecifikation |
| CODE11 | Anger att data ska kodas enligt CODE 11 streckkodsspecifikation |
| CODE39 | Anger att data ska kodas enligt Code 39 grundteckenuppsättning streckkodsspecifikation: ISO/IEC 16388 |
| CODE_39_FULL_ASCII | Anger att data ska kodas enligt Code 39 fullständig ASCII-teckenuppsättning streckkodsspecifikation: ISO/IEC 16388 |
| CODE93 | Anger att data ska kodas enligt CODE 93 streckkodsspecifikation |
| CODE128 | Anger att data ska kodas enligt CODE 128 streckkodsspecifikation |
| GS1_CODE_128 | Anger att data ska kodas enligt GS1 Code 128 streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
| EAN8 | Anger att data ska kodas enligt EAN-8 streckkodsspecifikation |
| EAN13 | Anger att data ska kodas enligt EAN-13 streckkodsspecifikation |
| EAN14 | Anger att data ska kodas enligt EAN14 streckkodsspecifikation |
| SCC14 | Anger att data ska kodas enligt SCC14 streckkodsspecifikation |
| SSCC18 | Anger att data ska kodas enligt SSCC18 streckkodsspecifikation |
| UPCA | Anger att data ska kodas enligt UPC-A streckkodsspecifikation |
| UPCE | Anger att data ska kodas enligt UPC-E streckkodsspecifikation |
| ISBN | Anger att data ska kodas enligt ISBN streckkodsspecifikation |
| ISSN | Anger att data ska kodas enligt ISSN streckkodsspecifikation |
| ISMN | Anger att data ska kodas enligt ISMN streckkodsspecifikation |
| STANDARD_2OF_5 | Anger att data ska kodas enligt Standard 2 av 5 streckkodsspecifikation |
| INTERLEAVED_2OF_5 | Anger att data ska kodas enligt INTERLEAVED 2 av 5 streckkodsspecifikation |
| MATRIX_2OF_5 | Representerar Matrix 2 av 5 streckkod |
| ITALIAN_POST25 | Representerar Italian Post 25 streckkod. |
| IATA2OF_5 | Representerar IATA 2 av 5 streckkod. IATA (International Air Transport Assosiation) använder denna streckkod för hantering av luftgods. |
| ITF14 | Anger att data ska kodas enligt ITF14 streckkodsspecifikation |
| ITF6 | Representerar ITF-6 streckkod. |
| MSI | Anger att data ska kodas enligt MSI Plessey streckkodsspecifikation |
| VIN | Representerar VIN (Vehicle Identification Number) streckkod. |
| DEUTSCHE_POST_IDENTCODE | Representerar Deutsch Post streckkod, denna symbolik är också känd som Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, <br/>            Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| DEUTSCHE_POST_LEITCODE | Representerar Deutsch Post Leitcode streckkod, också känd som German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| OPC | Representerar OPC (Optical Product Code) streckkod, också känd som , VCA Barcode VCA OPC, Vision Council of America OPC Barcode. |
| PZN | Representerar PZN streckkod. Denna symbolik är också känd som Pharmacy central number, Pharmazentralnummer. PZN7 och PZN8 stöds. <br/>            PZN7 genereras från 6 eller färre siffror, t.ex. \"123456\". PZN8 genereras från 7 eller fler siffror, t.ex. \"1234567\". <br/>            Angivet sista kontrollsiffra ignoreras och genereras av streckkodsmotorn. |
| CODE_16K | Representerar Code 16K streckkod. |
| PHARMACODE | Representerar Pharmacode streckkod. |
| DATA_MATRIX | 2D streckkodssymbolik DataMatrix |
| QR | Anger att data ska kodas enligt QR Code streckkodsspecifikation |
| AZTEC | Anger att data ska kodas enligt Aztec streckkodsspecifikation |
| GS1_AZTEC | Anger att data ska kodas enligt GS1 Aztec streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
| PDF417 | Anger att data ska kodas enligt Pdf417 streckkodsspecifikation |
| MACRO_PDF417 | Anger att data ska kodas enligt MacroPdf417 streckkodsspecifikation |
| GS1_DATA_MATRIX | 2D streckkodssymbolik DataMatrix med GS1 strängformat |
| MICRO_PDF417 | Anger att data ska kodas enligt MicroPdf417 streckkodsspecifikation |
| GS1_MICRO_PDF_417 | Anger att data ska kodas enligt GS1MicroPdf417 streckkodsspecifikation |
| GS1QR | 2D streckkodssymbolik QR med GS1 strängformat |
| MAXI_CODE | Anger att data ska kodas enligt MaxiCode streckkodsspecifikation |
| DOT_CODE | Anger att data ska kodas enligt DotCode streckkodsspecifikation |
| HAN_XIN | Anger att data ska kodas enligt Han Xin streckkodsspecifikation |
| GS1_HAN_XIN | 2D streckkodssymbolik HanXin med GS1 strängformat |
| MICRO_QR | Anger att data ska kodas enligt MicroQR Code streckkodsspecifikation |
| RECT_MICRO_QR | Anger att data ska kodas enligt RectMicroQR (rMQR) Code streckkodsspecifikation |
| AUSTRALIA_POST | Representerar Australia Post Customer BarCode |
| JAPAN_POST | Representerar Japan Post BarCode |
| POSTNET | Anger att data ska kodas enligt Postnet streckkodsspecifikation |
| PLANET | Anger att data ska kodas enligt Planet streckkodsspecifikation |
| ONE_CODE | Anger att data ska kodas enligt USPS OneCode streckkodsspecifikation |
| RM4SCC | Representerar RM4SCC streckkod. RM4SCC (Royal Mail 4-state Customer Code) används för automatiserad postsorteringsprocess i Storbritannien. |
| MAILMARK | Representerar Royal Mail Mailmark streckkod. |
| DATABAR_OMNI_DIRECTIONAL | Anger att data ska kodas enligt GS1 Databar omni-directional streckkodsspecifikation. |
| DATABAR_TRUNCATED | Anger att data ska kodas enligt GS1 Databar truncated streckkodsspecifikation. |
| DATABAR_LIMITED | Representerar GS1 Databar limited streckkod. |
| DATABAR_EXPANDED | Representerar GS1 Databar expanded streckkod. |
| DATABAR_EXPANDED_STACKED | Representerar GS1 Databar expanded stacked streckkod. |
| DATABAR_STACKED | Representerar GS1 Databar stacked streckkod. |
| DATABAR_STACKED_OMNI_DIRECTIONAL | Representerar GS1 Databar stacked omni-directional streckkod. |
| SINGAPORE_POST | Anger att data ska kodas enligt Singapore Post Barcode streckkodsspecifikation |
| AUSTRALIAN_POSTE_PARCEL | Anger att data ska kodas enligt Australian Post Domestic eParcel Barcode streckkodsspecifikation |
| SWISS_POST_PARCEL | Anger att data ska kodas enligt Swiss Post Parcel Barcode streckkodsspecifikation. Stödda typer: Domestic Mail, International Mail, Additional Services (new) |
| PATCH_CODE | Representerar Patch code streckkod |
| CODE32 | Anger att data ska kodas enligt Code32 streckkodsspecifikation |
| DATA_LOGIC_2OF_5 | Anger att data ska kodas enligt DataLogic 2 of 5 streckkodsspecifikation |
| DUTCH_KIX | Anger att data ska kodas enligt Dutch KIX streckkodsspecifikation |
| UPCA_GS_1_CODE_128_COUPON | Anger att data ska kodas enligt UPC‑kupong med GS1-128 Extended Code streckkodsspecifikation.<br/>            Ett exempel på inmatningssträngen:<br/>            BarcodeGenerator.Codetext = "514141100906(8102)03",<br/>            där UPCA‑delen är "514141100906", GS1Code128‑delen är (8102)03. |
| UPCA_GS_1_DATABAR_COUPON | Anger att data ska kodas med UPC‑kupong med GS1 DataBar‑tilläggsstreckkodsspecifikation.<br/>            Ett exempel på inmatningssträngen:<br/>            BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000",<br/>            där UPCA‑delen är "514141100906", Databar‑delen är "(8110)106141416543213500110000310123196000".<br/>            För att ändra rubriken, använd Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| CODABLOCK_F | Anger att data ska kodas med Codablock-F‑streckkodsspecifikation. |
| GS1_CODABLOCK_F | Anger att data ska kodas med GS1 Codablock-F‑streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
| GS1_COMPOSITE_BAR | Anger att data ska kodas med GS1 Composite Bar‑streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. 1D‑kodtext och 2D‑kodtext måste separeras med symbolen '/' |
| HIBC_CODE_39LIC | Anger att data ska kodas med HIBC LIC Code39‑streckkodsspecifikation. |
| HIBC_CODE_128LIC | Anger att data ska kodas med HIBC LIC Code128‑streckkodsspecifikation. |
| HIBC_AZTEC_LIC | Anger att data ska kodas med HIBC LIC Aztec‑streckkodsspecifikation. |
| HIBC_DATA_MATRIX_LIC | Anger att data ska kodas med HIBC LIC DataMatrix‑streckkodsspecifikation. |
| HIBCQRLIC | Anger att data ska kodas med HIBC LIC QR‑streckkodsspecifikation. |
| HIBC_CODE_39PAS | Anger att data ska kodas med HIBC PAS Code39‑streckkodsspecifikation. |
| HIBC_CODE_128PAS | Anger att data ska kodas med HIBC PAS Code128‑streckkodsspecifikation. |
| HIBC_AZTEC_PAS | Anger att data ska kodas med HIBC PAS Aztec‑streckkodsspecifikation. |
| HIBC_DATA_MATRIX_PAS | Anger att data ska kodas med HIBC PAS DataMatrix‑streckkodsspecifikation. |
| HIBCQRPAS | Anger att data ska kodas med HIBC PAS QR‑streckkodsspecifikation. |
| GS1_DOT_CODE | Anger att data ska kodas med GS1 DotCode‑streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| get_names() | Hämtar en array med namnen på kodningstyperna. |
| parse(parsing_type, result) | Konverterar strängrepresentationen av en BaseEncodeType till dess instans.<br/>            Returvärdet indikerar om konverteringen lyckades eller misslyckades. |
| try_parse(parsing_type, result) | Konverterar strängrepresentationen av en BaseEncodeType till dess instans.<br/>            Returvärdet indikerar om konverteringen lyckades eller misslyckades. |

### Se även

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

