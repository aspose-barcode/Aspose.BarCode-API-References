---
title: "EncodeTypes"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Anger typen av streckkod att koda."
type: docs
weight: 260
url: /sv/nodejs/global/encodetypes/
---

## EncodeTypes

Anger typen av streckkod att koda.

## Värden

| Namn | Beskrivning |
| --- | --- |
| INGEN | Odefinierad kodningstyp. |
| CODABAR | Anger att data ska kodas enligt CODABAR-streckkodsspecifikation |
| CODE_11 | Anger att data ska kodas enligt CODE 11-streckkodsspecifikation |
| CODE_39 | Anger att data ska kodas med `Code 39 ` grundteckenuppsättning för streckkodsspecifikation: ISO/IEC 16388 |
| CODE_39_FULL_ASCII | Anger att data ska kodas med `Code 39 ` fullständig ASCII-teckenuppsättning för streckkodsspecifikation: ISO/IEC 16388 |
| CODE_93 | Anger att data ska kodas med `CODE 93 ` streckkodsspecifikation |
| CODE_128 | Anger att data ska kodas med CODE 128 streckkodsspecifikation |
| GS_1_CODE_128 | Anger att data ska kodas med GS1 Code 128 streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
| EAN_8 | Anger att data ska kodas med EAN-8 streckkodsspecifikation |
| EAN_13 | Anger att data ska kodas med EAN-13 streckkodsspecifikation |
| EAN_14 | Anger att data ska kodas med EAN14 streckkodsspecifikation |
| SCC_14 | Anger att data ska kodas med SCC14 streckkodsspecifikation |
| SSCC_18 | Anger att data ska kodas med SSCC18 streckkodsspecifikation |
| UPCA | Anger att data ska kodas med UPC-A streckkodsspecifikation |
| UPCE | Anger att data ska kodas med UPC-E streckkodsspecifikation |
| ISBN | Anger att data ska kodas med isBN streckkodsspecifikation |
| ISSN | Anger att data ska kodas med ISSN streckkodsspecifikation |
| ISMN | Anger att data ska kodas med ISMN streckkodsspecifikation |
| STANDARD_2_OF_5 | Anger att data ska kodas med Standard 2 of 5 streckkodsspecifikation |
| INTERLEAVED_2_OF_5 | Anger att data ska kodas med INTERLEAVED 2 of 5 streckkodsspecifikation |
| MATRIX_2_OF_5 | Representerar Matrix 2 of 5 BarCode |
| ITALIAN_POST_25 | Representerar Italian Post 25 streckkod. |
| IATA_2_OF_5 | Representerar IATA 2 of 5 streckkod. IATA (International Air Transport Association) använder denna streckkod för hantering av luftfrakt. |
| ITF_14 | Anger att data ska kodas med ITF14 streckkodsspecifikation |
| ITF_6 | Representerar ITF-6 streckkod. |
| MSI | Anger att data ska kodas med MSI Plessey streckkodsspecifikation |
| VIN | Representerar VIN (Vehicle Identification Number) streckkod. |
| DEUTSCHE_POST_IDENTCODE | Representerar Deutsch Post streckkod, denna EncodeType är också känd som Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| DEUTSCHE_POST_LEITCODE | Representerar Deutsch Post Leitcode streckkod, också känd som German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| OPC | Representerar OPC(Optical Product Code) streckkod, också känd som , VCA Barcode VCA OPC, Vision Council of America OPC Barcode. |
| PZN | Representerar PZN-streckkod. Denna EncodeType är också känd som apotekets centrala nummer, Pharmazentralnummer |
| CODE_16_K | Representerar Code 16K-streckkod. |
| PHARMACODE | Representerar Pharmacode-streckkod. |
| DATA_MATRIX | 2D-streckkodssymbolik DataMatrix |
| QR | Anger att data ska kodas enligt QR Code-streckkodsspecifikation |
| AZTEC | Anger att data ska kodas enligt Aztec-streckkodsspecifikation |
| GS_1_AZTEC | Anger att data ska kodas enligt `GS1 Aztec ` streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
| PDF_417 | Anger att data ska kodas enligt Pdf417-streckkodsspecifikation |
| MACRO_PDF_417 | Anger att data ska kodas enligt MacroPdf417-streckkodsspecifikation |
| GS_1_DATA_MATRIX | 2D-streckkodssymbolik DataMatrix med GS1-strängformat |
| MICRO_PDF_417 | Anger att data ska kodas enligt MicroPdf417-streckkodsspecifikation |
| GS_1_MICRO_PDF_417 | Anger att data ska kodas enligt GS1MicroPdf417-streckkodsspecifikation |
| GS_1_QR | 2D-streckkodssymbolik QR med GS1-strängformat |
| MAXI_CODE | Anger att data ska kodas enligt MaxiCode-streckkodsspecifikation |
| DOT_CODE | Anger att data ska kodas enligt DotCode-streckkodsspecifikation |
| AUSTRALIA_POST | Representerar Australia Post kundstreckkod |
| POSTNET | Anger att data ska kodas enligt Postnet-streckkodsspecifikation |
| PLANET | Anger att data ska kodas enligt Planet-streckkodsspecifikation |
| ONE_CODE | Anger att data ska kodas enligt USPS OneCode-streckkodsspecifikation |
| RM_4_SCC | Representerar RM4SCC-streckkod. RM4SCC (Royal Mail 4-state Customer Code) används för automatiserad postsorteringsprocess i Storbritannien. |
| MAILMARK | Representerar Royal Mail Mailmark-streckkod. |
| DATABAR_OMNI_DIRECTIONAL | Anger att data ska kodas enligt GS1 Databar omni-directional-streckkodsspecifikation. |
| DATABAR_TRUNCATED | Anger att data ska kodas enligt GS1 Databar truncated-streckkodsspecifikation. |
| DATABAR_LIMITED | Representerar GS1 DATABAR limited-streckkod. |
| DATABAR_EXPANDED | Representerar GS1 Databar expanded-streckkod. |
| DATABAR_EXPANDED_STACKED | Representerar GS1 Databar expanderad staplad streckkod. |
| DATABAR_STACKED | Representerar GS1 Databar staplad streckkod. |
| DATABAR_STACKED_OMNI_DIRECTIONAL | Representerar GS1 Databar staplad omni-riktad streckkod. |
| SINGAPORE_POST | Anger att data ska kodas med specifikationen för Singapore Post Barcode streckkod. |
| AUSTRALIAN_POSTE_PARCEL | Anger att data ska kodas med specifikationen för Australian Post Domestic eParcel Barcode streckkod. |
| SWISS_POST_PARCEL | Anger att data ska kodas med specifikationen för Swiss Post Parcel Barcode streckkod. Stödda typer: Domestic Mail, International Mail, Additional Services (new) |
| PATCH_CODE | Representerar Patch code streckkod. |
| CODE_32 | Anger att data ska kodas med specifikationen för Code32 streckkod. |
| DATA_LOGIC_2_OF_5 | Anger att data ska kodas med specifikationen för DataLogic 2 of 5 streckkod. |
| DUTCH_KIX | Anger att data ska kodas med specifikationen för Dutch KIX streckkod. |
| UPCA_GS_1_CODE_128_COUPON | Anger att data ska kodas med UPC-kupong med GS1-128 Extended Code streckkodsspecifikation. |
| UPCA_GS_1_DATABAR_COUPON | Anger att data ska kodas med UPC-kupong med GS1 DataBar addition streckkodsspecifikation. |
| CODABLOCK_F | Anger att data ska kodas med Codablock-F streckkodsspecifikation. |
| GS_1_CODABLOCK_F | Anger att data ska kodas med GS1 Codablock-F streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
| GS_1_COMPOSITE_BAR | Anger att data ska kodas med GS1 Composite Bar streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. 1D-kodtext och 2D-kodtext måste separeras med symbolen '/' |
| HIBC_CODE_39_LIC | Anger att data ska kodas med `HIBC LIC Code39Standart ` streckkodsspecifikation. |
| HIBC_CODE_128_LIC | Anger att data ska kodas med `HIBC LIC Code128 ` streckkodsspecifikation. |
| HIBC_AZTEC_LIC | Anger att data ska kodas med `HIBC LIC Aztec ` streckkodsspecifikation. |
| HIBC_DATA_MATRIX_LIC | Anger att data ska kodas med `HIBC LIC DataMatrix ` streckkodsspecifikation. |
| HIBCQRLIC | Anger att data ska kodas med `HIBC LIC QR ` streckkodsspecifikation. |
| HIBC_CODE_39_PAS | Anger att data ska kodas med `HIBC PAS Code39Standart ` streckkodsspecifikation. |
| HIBC_CODE_128_PAS | Anger att data ska kodas med `HIBC PAS Code128 ` streckkodsspecifikation. |
| HIBC_AZTEC_PAS | Anger att data ska kodas med `HIBC PAS Aztec ` streckkodsspecifikation. |
| HIBC_DATA_MATRIX_PAS | Anger att data ska kodas med `HIBC PAS DataMatrix ` streckkodsspecifikation. |
| HIBCQRPAS | Anger att data ska kodas med `HIBC PAS QR ` streckkodsspecifikation. |
| GS_1_DOT_CODE | Anger att data ska kodas med `GS1 DotCode ` streckkodsspecifikation. Kodtexten måste innehålla parenteser för AI. |
| HAN_XIN | Anger att data ska kodas med Han Xin streckkodsspecifikation |
| GS_1_HAN_XIN | 2D-streckkodssymbolik QR med GS1-strängformat |
| MICRO_QR | Anger att data ska kodas med MicroQR Code streckkodsspecifikation |
| RECT_MICRO_QR | Anger att data ska kodas med RectMicroQR (rMQR) Code streckkodsspecifikation |
| tolka |  |
