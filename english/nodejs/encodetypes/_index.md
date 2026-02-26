---
title: EncodeTypes Enum
linktitle: EncodeTypes
articleTitle: EncodeTypes
second_title: Aspose.BarCode for Node.js via Java
description: Specifies the type of barcode to encode.
type: docs
weight: 1040
url: /nodejs/encodetypes/
---
## EncodeTypes enumeration

Specifies the type of barcode to encode.

```javascript
public enum EncodeTypes
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| NONE | `-1` | Unspecified encode type. |
| CODABAR | `0` | Specifies that the data should be encoded with CODABAR barcode specification |
| CODE_11 | `1` | Specifies that the data should be encoded with CODE 11 barcode specification |
| CODE_39 | `2` | Specifies that the data should be encoded with {@code Code 39} basic charset barcode specification: ISO/IEC 16388 |
| CODE_39_FULL_ASCII | `3` | Specifies that the data should be encoded with {@code Code 39} full ASCII charset barcode specification: ISO/IEC 16388 |
| CODE_93 | `5` | Specifies that the data should be encoded with {@code CODE 93} barcode specification |
| CODE_128 | `6` | Specifies that the data should be encoded with CODE 128 barcode specification |
| GS_1_CODE_128 | `7` | Specifies that the data should be encoded with GS1 Code 128 barcode specification. The codetext must contains parentheses for AI. |
| EAN_8 | `8` | Specifies that the data should be encoded with EAN-8 barcode specification |
| EAN_13 | `9` | Specifies that the data should be encoded with EAN-13 barcode specification |
| EAN_14 | `10` | Specifies that the data should be encoded with EAN14 barcode specification |
| SCC_14 | `11` | Specifies that the data should be encoded with SCC14 barcode specification |
| SSCC_18 | `12` | Specifies that the data should be encoded with SSCC18 barcode specification |
| UPCA | `13` | Specifies that the data should be encoded with UPC-A barcode specification |
| UPCE | `14` | Specifies that the data should be encoded with UPC-E barcode specification |
| ISBN | `15` | Specifies that the data should be encoded with isBN barcode specification |
| ISSN | `16` | Specifies that the data should be encoded with ISSN barcode specification |
| ISMN | `17` | Specifies that the data should be encoded with ISMN barcode specification |
| STANDARD_2_OF_5 | `18` | Specifies that the data should be encoded with Standard 2 of 5 barcode specification |
| INTERLEAVED_2_OF_5 | `19` | Specifies that the data should be encoded with INTERLEAVED 2 of 5 barcode specification |
| MATRIX_2_OF_5 | `20` | Represents Matrix 2 of 5 BarCode |
| ITALIAN_POST_25 | `21` | Represents Italian Post 25 barcode. |
| IATA_2_OF_5 | `22` | Represents IATA 2 of 5 barcode.IATA (International Air Transport Assosiation) uses this barcode for the management of air cargo. |
| ITF_14 | `23` | Specifies that the data should be encoded with ITF14 barcode specification |
| ITF_6 | `24` | Represents ITF-6  Barcode. |
| MSI | `25` | Specifies that the data should be encoded with MSI Plessey barcode specification |
| VIN | `26` | Represents VIN (Vehicle Identification Number) Barcode. |
| DEUTSCHE_POST_IDENTCODE | `27` | Represents Deutsch Post barcode, This EncodeType is also known as Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode,  Deutsch Post AG (DHL) |
| DEUTSCHE_POST_LEITCODE | `28` | Represents Deutsch Post Leitcode Barcode,also known as German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL). |
| OPC | `29` | Represents OPC(Optical Product Code) Barcode,also known as , VCA Barcode VCA OPC, Vision Council of America OPC Barcode. |
| PZN | `30` | Represents PZN barcode.This EncodeType is also known as Pharmacy central number, Pharmazentralnummer |
| CODE_16_K | `31` | Represents Code 16K barcode. |
| PHARMACODE | `32` | Represents Pharmacode barcode. |
| DATA_MATRIX | `33` | 2D barcode symbology DataMatrix |
| QR | `34` | Specifies that the data should be encoded with QR Code barcode specification |
| AZTEC | `35` | Specifies that the data should be encoded with Aztec barcode specification |
| GS_1_AZTEC | `81` | Specifies that the data should be encoded with {@code GS1 Aztec} barcode specification. The codetext must contains parentheses for AI. |
| PDF_417 | `36` | Specifies that the data should be encoded with Pdf417 barcode specification |
| MACRO_PDF_417 | `37` | Specifies that the data should be encoded with MacroPdf417 barcode specification |
| GS_1_DATA_MATRIX | `48` | 2D barcode symbology DataMatrix with GS1 string format |
| MICRO_PDF_417 | `55` | Specifies that the data should be encoded with MicroPdf417 barcode specification |
| GS_1_MICRO_PDF_417 | `82` | Specifies that the data should be encoded with GS1MicroPdf417 barcode specification |
| GS_1_QR | `56` | 2D barcode symbology QR with GS1 string format |
| MAXI_CODE | `57` | Specifies that the data should be encoded with MaxiCode barcode specification |
| DOT_CODE | `60` | Specifies that the data should be encoded with DotCode barcode specification |
| AUSTRALIA_POST | `38` | Represents Australia Post Customer BarCode |
| POSTNET | `39` | Specifies that the data should be encoded with Postnet barcode specification |
| PLANET | `40` | Specifies that the data should be encoded with Planet barcode specification |
| ONE_CODE | `41` | Specifies that the data should be encoded with USPS OneCode barcode specification |
| RM_4_SCC | `42` | Represents RM4SCC barcode. RM4SCC (Royal Mail 4-state Customer Code) is used for automated mail sort process in UK. |
| MAILMARK | `66` | Represents Royal Mail Mailmark barcode. |
| DATABAR_OMNI_DIRECTIONAL | `43` | Specifies that the data should be encoded with GS1 Databar omni-directional barcode specification. |
| DATABAR_TRUNCATED | `44` | Specifies that the data should be encoded with GS1 Databar truncated barcode specification. |
| DATABAR_LIMITED | `45` | Represents GS1 DATABAR limited barcode. |
| DATABAR_EXPANDED | `46` | Represents GS1 Databar expanded barcode. |
| DATABAR_EXPANDED_STACKED | `52` | Represents GS1 Databar expanded stacked barcode. |
| DATABAR_STACKED | `53` | Represents GS1 Databar stacked barcode. |
| DATABAR_STACKED_OMNI_DIRECTIONAL | `54` | Represents GS1 Databar stacked omni-directional barcode. |
| SINGAPORE_POST | `47` | Specifies that the data should be encoded with Singapore Post Barcode barcode specification |
| AUSTRALIAN_POSTE_PARCEL | `49` | Specifies that the data should be encoded with Australian Post Domestic eParcel Barcode barcode specification |
| SWISS_POST_PARCEL | `50` | Specifies that the data should be encoded with Swiss Post Parcel Barcode barcode specification. Supported types: Domestic Mail, International Mail, Additional Services (new) |
| PATCH_CODE | `51` | Represents Patch code barcode |
| CODE_32 | `58` | Specifies that the data should be encoded with Code32 barcode specification |
| DATA_LOGIC_2_OF_5 | `59` | Specifies that the data should be encoded with DataLogic 2 of 5 barcode specification |
| DUTCH_KIX | `61` | Specifies that the data should be encoded with Dutch KIX barcode specification |
| UPCA_GS_1_CODE_128_COUPON | `62` | Specifies that the data should be encoded with UPC coupon with GS1-128 Extended Code barcode specification. An example of the input string: BarCodeGenerator.setCodetext("514141100906(8102)03"), where UPCA part is "514141100906", GS1Code128 part is (8102)03. |
| UPCA_GS_1_DATABAR_COUPON | `63` | Specifies that the data should be encoded with UPC coupon with GS1 DataBar addition barcode specification. An example of the input string: BarCodeGenerator.setCodetext("514141100906(8110)106141416543213500110000310123196000"), where UPCA part is "514141100906, DATABAR part is "(8110)106141416543213500110000310123196000". To change the caption, use barCodeBuilder.getCaptionAbove().setText("company prefix + offer code")", |
| CODABLOCK_F | `64` | Specifies that the data should be encoded with Codablock-F barcode specification. |
| GS_1_CODABLOCK_F | `65` | Specifies that the data should be encoded with GS1 Codablock-F barcode specification. The codetext must contains parentheses for AI. |
| GS_1_COMPOSITE_BAR | `67` | Specifies that the data should be encoded with GS1 Composite Bar barcode specification. The codetext must contains parentheses for AI. 1D codetext and 2D codetext must be separated with symbol '/' |
| HIBC_CODE_39_LIC | `68` | Specifies that the data should be encoded with {@code HIBC LIC Code39Standart} barcode specification. |
| HIBC_CODE_128_LIC | `69` | Specifies that the data should be encoded with {@code HIBC LIC Code128} barcode specification. |
| HIBC_AZTEC_LIC | `70` | Specifies that the data should be encoded with {@code HIBC LIC Aztec} barcode specification. |
| HIBC_DATA_MATRIX_LIC | `71` | Specifies that the data should be encoded with {@code HIBC LIC DataMatrix} barcode specification. |
| HIBCQRLIC | `72` | Specifies that the data should be encoded with {@code HIBC LIC QR} barcode specification. |
| HIBC_CODE_39_PAS | `73` | Specifies that the data should be encoded with {@code HIBC PAS Code39Standart} barcode specification. |
| HIBC_CODE_128_PAS | `74` | Specifies that the data should be encoded with {@code HIBC PAS Code128} barcode specification. |
| HIBC_AZTEC_PAS | `75` | Specifies that the data should be encoded with {@code HIBC PAS Aztec} barcode specification. |
| HIBC_DATA_MATRIX_PAS | `76` | Specifies that the data should be encoded with {@code HIBC PAS DataMatrix} barcode specification. |
| HIBCQRPAS | `77` | Specifies that the data should be encoded with {@code HIBC PAS QR} barcode specification. |
| GS_1_DOT_CODE | `78` | Specifies that the data should be encoded with {@code GS1 DotCode} barcode specification. The codetext must contains parentheses for AI. |
| HAN_XIN | `79` | Specifies that the data should be encoded with Han Xin barcode specification |
| GS_1_HAN_XIN | `80` | 2D barcode symbology QR with GS1 string format |
| MICRO_QR | `83` | Specifies that the data should be encoded with MicroQR Code barcode specification |
| RECT_MICRO_QR | `84` | Specifies that the data should be encoded with RectMicroQR (rMQR) Code barcode specification |

### See Also

* assembly [Aspose.BarCode](../)

