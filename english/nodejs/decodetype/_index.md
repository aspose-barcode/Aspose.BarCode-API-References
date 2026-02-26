---
title: "DecodeType Enum"
linktitle: "DecodeType"
articleTitle: "DecodeType"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Specify the type of barcode to read."
type: docs
weight: 1470
url: /nodejs/decodetype/
---
## DecodeType enumeration

Specify the type of barcode to read.

```javascript
public enum DecodeType
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| NONE | `-1` | Unspecified decode type. |
| CODABAR | `0` | Specifies that the data should be decoded with {@code CODABAR} barcode specification |
| CODE_11 | `1` | Specifies that the data should be decoded with {@code CODE 11} barcode specification |
| CODE_39 | `2` | Specifies that the data should be decoded with {@code Code 39} basic charset barcode specification: ISO/IEC 16388 |
| CODE_39_FULL_ASCII | `3` | Specifies that the data should be decoded with {@code Code 39} full ASCII charset barcode specification: ISO/IEC 16388 |
| CODE_93 | `5` | Specifies that the data should be decoded with {@code CODE 93} barcode specification |
| CODE_128 | `6` | Specifies that the data should be decoded with {@code CODE 128} barcode specification |
| GS_1_CODE_128 | `7` | Specifies that the data should be decoded with {@code GS1 CODE 128} barcode specification |
| EAN_8 | `8` | Specifies that the data should be decoded with {@code EAN-8} barcode specification |
| EAN_13 | `9` | Specifies that the data should be decoded with {@code EAN-13} barcode specification |
| EAN_14 | `10` | Specifies that the data should be decoded with {@code EAN14} barcode specification |
| SCC_14 | `11` | Specifies that the data should be decoded with {@code SCC14} barcode specification |
| SSCC_18 | `12` | Specifies that the data should be decoded with {@code SSCC18} barcode specification |
| UPCA | `13` | Specifies that the data should be decoded with {@code UPC-A} barcode specification |
| UPCE | `14` | Specifies that the data should be decoded with {@code UPC-E} barcode specification |
| ISBN | `15` | Specifies that the data should be decoded with {@code ISBN} barcode specification |
| STANDARD_2_OF_5 | `16` | Specifies that the data should be decoded with {@code Standard 2 of 5} barcode specification |
| INTERLEAVED_2_OF_5 | `17` | Specifies that the data should be decoded with {@code INTERLEAVED 2 of 5} barcode specification |
| MATRIX_2_OF_5 | `18` | Specifies that the data should be decoded with {@code Matrix 2 of 5} barcode specification |
| ITALIAN_POST_25 | `19` | Specifies that the data should be decoded with {@code Italian Post 25} barcode specification |
| IATA_2_OF_5 | `20` | Specifies that the data should be decoded with {@code IATA 2 of 5} barcode specification. IATA (International Air Transport Association) uses this barcode for the management of air cargo. |
| ITF_14 | `21` | Specifies that the data should be decoded with {@code ITF14} barcode specification |
| ITF_6 | `22` | Specifies that the data should be decoded with {@code ITF6} barcode specification |
| MSI | `23` | Specifies that the data should be decoded with {@code MSI Plessey} barcode specification |
| VIN | `24` | Specifies that the data should be decoded with {@code VIN} (Vehicle Identification Number) barcode specification |
| DEUTSCHE_POST_IDENTCODE | `25` | Specifies that the data should be decoded with {@code DeutschePost Ident code} barcode specification |
| DEUTSCHE_POST_LEITCODE | `26` | Specifies that the data should be decoded with {@code DeutschePost Leit code} barcode specification |
| OPC | `27` | Specifies that the data should be decoded with {@code OPC} barcode specification |
| PZN | `28` | Specifies that the data should be decoded with {@code PZN} barcode specification. This symbology is also known as Pharma Zentral Nummer |
| PHARMACODE | `29` | Specifies that the data should be decoded with {@code Pharmacode} barcode. This symbology is also known as Pharmaceutical BINARY Code |
| DATA_MATRIX | `30` | Specifies that the data should be decoded with {@code DataMatrix} barcode symbology |
| GS_1_DATA_MATRIX | `31` | Specifies that the data should be decoded with {@code GS1DataMatrix} barcode symbology |
| QR | `32` | Specifies that the data should be decoded with {@code QR Code} barcode specification |
| AZTEC | `33` | Specifies that the data should be decoded with {@code Aztec} barcode specification |
| GS_1_AZTEC | `81` | Specifies that the data should be decoded with {@code GS1 Aztec} barcode specification |
| PDF_417 | `34` | Specifies that the data should be decoded with {@code Pdf417} barcode symbology |
| MACRO_PDF_417 | `35` | Specifies that the data should be decoded with {@code MacroPdf417} barcode specification |
| MICRO_PDF_417 | `36` | Specifies that the data should be decoded with {@code MicroPdf417} barcode specification |
| GS_1_MICRO_PDF_417 | `82` | Specifies that the data should be decoded with MicroPdf417 barcode specification |
| CODABLOCK_F | `65` | Specifies that the data should be decoded with {@code CodablockF} barcode specification |
| MAILMARK | `66` | Specifies that the data should be decoded with Royal Mail Mailmark barcode specification. |
| AUSTRALIA_POST | `37` | Specifies that the data should be decoded with {@code Australia Post} barcode specification |
| POSTNET | `38` | Specifies that the data should be decoded with {@code Postnet} barcode specification |
| PLANET | `39` | Specifies that the data should be decoded with {@code Planet} barcode specification |
| ONE_CODE | `40` | Specifies that the data should be decoded with USPS {@code OneCode} barcode specification |
| RM_4_SCC | `41` | Specifies that the data should be decoded with {@code RM4SCC} barcode specification. RM4SCC (Royal Mail 4-state Customer Code) is used for automated mail sort process in UK. |
| DATABAR_OMNI_DIRECTIONAL | `42` | Specifies that the data should be decoded with {@code GS1 DATABAR omni-directional} barcode specification |
| DATABAR_TRUNCATED | `43` | Specifies that the data should be decoded with {@code GS1 DATABAR truncated} barcode specification |
| DATABAR_LIMITED | `44` | Specifies that the data should be decoded with {@code GS1 DATABAR limited} barcode specification |
| DATABAR_EXPANDED | `45` | Specifies that the data should be decoded with {@code GS1 DATABAR expanded} barcode specification |
| DATABAR_STACKED_OMNI_DIRECTIONAL | `53` | Specifies that the data should be decoded with {@code GS1 DATABAR stacked omni-directional} barcode specification |
| DATABAR_STACKED | `54` | Specifies that the data should be decoded with {@code GS1 DATABAR stacked} barcode specification |
| DATABAR_EXPANDED_STACKED | `55` | Specifies that the data should be decoded with {@code GS1 DATABAR expanded stacked} barcode specification |
| PATCH_CODE | `46` | Specifies that the data should be decoded with {@code Patch code} barcode specification. Barcode symbology is used for automated scanning |
| ISSN | `47` | Specifies that the data should be decoded with {@code ISSN} barcode specification |
| ISMN | `48` | Specifies that the data should be decoded with {@code ISMN} barcode specification |
| SUPPLEMENT | `49` | Specifies that the data should be decoded with {@code Supplement(EAN2, EAN5)} barcode specification |
| AUSTRALIAN_POSTE_PARCEL | `50` | Specifies that the data should be decoded with {@code Australian Post Domestic eParcel Barcode} barcode specification |
| SWISS_POST_PARCEL | `51` | Specifies that the data should be decoded with {@code Swiss Post Parcel Barcode} barcode specification |
| CODE_16_K | `52` | Specifies that the data should be decoded with {@code SCode16K} barcode specification |
| MICRO_QR | `56` | Specifies that the data should be decoded with {@code MicroQR Code} barcode specification |
| RECT_MICRO_QR | `83` | Specifies that the data should be decoded with RectMicroQR (rMQR) Code barcode specification |
| COMPACT_PDF_417 | `57` | Specifies that the data should be decoded with {@code CompactPdf417} (Pdf417Truncated) barcode specification |
| GS_1_QR | `58` | Specifies that the data should be decoded with {@code GS1 QR} barcode specification |
| MAXI_CODE | `59` | Specifies that the data should be decoded with {@code MaxiCode} barcode specification |
| MICR_E_13_B | `60` | Specifies that the data should be decoded with {@code MICR E-13B} blank specification |
| CODE_32 | `61` | Specifies that the data should be decoded with {@code Code32} blank specification |
| DATA_LOGIC_2_OF_5 | `62` | Specifies that the data should be decoded with {@code DataLogic 2 of 5} blank specification |
| DOT_CODE | `63` | Specifies that the data should be decoded with {@code DotCode} blank specification |
| GS_1_DOT_CODE | `77` | Specifies that the data should be decoded with {@code GS1 DotCode} blank specification |
| DUTCH_KIX | `64` | Specifies that the data should be decoded with {@code DotCode} blank specification |
| HIBC_CODE_39_LIC | `67` | Specifies that the data should be decoded with {@code HIBC LIC Code39} blank specification |
| HIBC_CODE_128_LIC | `68` | Specifies that the data should be decoded with {@code HIBC LIC Code128} blank specification |
| HIBC_AZTEC_LIC | `69` | Specifies that the data should be decoded with {@code HIBC LIC Aztec} blank specification |
| HIBC_DATA_MATRIX_LIC | `70` | Specifies that the data should be decoded with {@code HIBC LIC DataMatrix} blank specification |
| HIBCQRLIC | `71` | Specifies that the data should be decoded with {@code HIBC LIC QR} blank specification |
| HIBC_CODE_39_PAS | `72` | Specifies that the data should be decoded with {@code HIBC PAS Code39} blank specification |
| HIBC_CODE_128_PAS | `73` | Specifies that the data should be decoded with {@code HIBC PAS Code128} blank specification |
| HIBC_AZTEC_PAS | `74` | Specifies that the data should be decoded with {@code HIBC PAS Aztec} blank specification |
| HIBC_DATA_MATRIX_PAS | `75` | Specifies that the data should be decoded with {@code HIBC PAS DataMatrix} blank specification |
| HIBCQRPAS | `76` | Specifies that the data should be decoded with {@code HIBC PAS QR} blank specification |
| HAN_XIN | `78` | Specifies that the data should be decoded with Han Xin Code blank specification |
| GS_1_HAN_XIN | `79` | Specifies that the data should be decoded with Han Xin Code blank specification |
| GS_1_COMPOSITE_BAR | `80` | Specifies that the data should be decoded with {@code GS1 Composite Bar} barcode specification |
| TYPES_1D | `97` | Specifies that data will be checked with all of  1D  barcode symbologies |
| POSTAL_TYPES | `95` | Specifies that data will be checked with all of  1.5D POSTAL  barcode symbologies, like  Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX |
| MOST_COMMON_TYPES | `96` | Specifies that data will be checked with most commonly used symbologies |
| TYPES_2D | `98` | Specifies that data will be checked with all of 2D barcode symbologies |
| ALL_SUPPORTED_TYPES | `99` | Specifies that data will be checked with all available symbologies |

## Examples

```javascript
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode Type: " + result.getCodeTypeName());
console.log("BarCode CodeText: " + result.getCodeText());
}
```

### See Also

* assembly [Aspose.BarCode](../)

