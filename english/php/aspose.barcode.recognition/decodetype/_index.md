---
title: "DecodeType"
linktitle: "DecodeType"
second_title: "Aspose.BarCode for PHP via Java"
description: "Specify the type of barcode to read. This sample shows how to detect Code39 and Code128 barcodes."
type: docs
weight: 10
url: /php/aspose.barcode.recognition/decodetype/
---

## DecodeType class

**Namespace:** `Aspose.Barcode.Recognition`


Specify the type of barcode to read. This sample shows how to detect Code39 and Code128 barcodes.


## Methods

| Name | Static | Description |
| --- | --- | --- |
| [containsAny](#containsany) | Yes | Determines if the BaseDecodeType array contains specified barcode symbology |
| [is1D](#is1d) | Yes | Determines if the specified BaseDecodeType contains any 1D barcode symbology |
| [is2D](#is2d) | Yes | Determines if the specified BaseDecodeType contains any 2D barcode symbology |
| [isPostal](#ispostal) | Yes | Determines if the specified BaseDecodeType contains any Postal barcode symbology |

## Constants

| Name | Value | Description |
| --- | --- | --- |
| [ALL_SUPPORTED_TYPES](#all_supported_types) | `99` | Specifies that data will be checked with all available symbologies |
| [AUSTRALIA_POST](#australia_post) | `37` | Specifies that the data should be decoded with { Australia Post} barcode specification |
| [AUSTRALIAN_POSTE_PARCEL](#australian_poste_parcel) | `50` | Specifies that the data should be decoded with { Australian Post Domestic eParcel Barcode} barcode specification |
| [AZTEC](#aztec) | `33` | Specifies that the data should be decoded with { Aztec} barcode specification |
| [CODABAR](#codabar) | `0` | Specifies that the data should be decoded with { CODABAR} barcode specification |
| [CODABLOCK_F](#codablock_f) | `65` | Specifies that the data should be decoded with { CodablockF} barcode specification |
| [CODE_11](#code_11) | `1` | Specifies that the data should be decoded with { CODE 11} barcode specification |
| [CODE_128](#code_128) | `6` | Specifies that the data should be decoded with { CODE 128} barcode specification |
| [CODE_16_K](#code_16_k) | `52` | Specifies that the data should be decoded with { SCode16K} barcode specification |
| [CODE_32](#code_32) | `61` | Specifies that the data should be decoded with { Code32} blank specification |
| [CODE_39](#code_39) | `2` | Specifies that the data should be decoded with basic charset barcode specification: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#code_39_full_ascii) | `3` | Specifies that the data should be decoded with full ASCII charset barcode specification: ISO/IEC 16388 |
| [CODE_93](#code_93) | `5` | Specifies that the data should be decoded with barcode specification |
| [COMPACT_PDF_417](#compact_pdf_417) | `57` | Specifies that the data should be decoded with { CompactPdf417} (Pdf417Truncated) barcode specification |
| [DATA_LOGIC_2_OF_5](#data_logic_2_of_5) | `62` | Specifies that the data should be decoded with { DataLogic 2 of 5} blank specification |
| [DATA_MATRIX](#data_matrix) | `30` | Specifies that the data should be decoded with { DataMatrix} barcode symbology |
| [DATABAR_EXPANDED](#databar_expanded) | `45` | Specifies that the data should be decoded with { GS1 DATABAR expanded} barcode specification |
| [DATABAR_EXPANDED_STACKED](#databar_expanded_stacked) | `55` | Specifies that the data should be decoded with { GS1 DATABAR expanded stacked} barcode specification |
| [DATABAR_LIMITED](#databar_limited) | `44` | Specifies that the data should be decoded with { GS1 DATABAR limited} barcode specification |
| [DATABAR_OMNI_DIRECTIONAL](#databar_omni_directional) | `42` | Specifies that the data should be decoded with { GS1 DATABAR omni-directional} barcode specification |
| [DATABAR_STACKED](#databar_stacked) | `54` | Specifies that the data should be decoded with { GS1 DATABAR stacked} barcode specification |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#databar_stacked_omni_directional) | `53` | Specifies that the data should be decoded with { GS1 DATABAR stacked omni-directional} barcode specification |
| [DATABAR_TRUNCATED](#databar_truncated) | `43` | Specifies that the data should be decoded with { GS1 DATABAR truncated} barcode specification |
| [DEUTSCHE_POST_IDENTCODE](#deutsche_post_identcode) | `25` | Specifies that the data should be decoded with { DeutschePost Ident code} barcode specification |
| [DEUTSCHE_POST_LEITCODE](#deutsche_post_leitcode) | `26` | Specifies that the data should be decoded with { DeutschePost Leit code} barcode specification |
| [DOT_CODE](#dot_code) | `63` | Specifies that the data should be decoded with { DotCode} blank specification |
| [DUTCH_KIX](#dutch_kix) | `64` | Specifies that the data should be decoded with { DotCode} blank specification |
| [EAN_13](#ean_13) | `9` | Specifies that the data should be decoded with { EAN-13} barcode specification |
| [EAN_14](#ean_14) | `10` | Specifies that the data should be decoded with { EAN14} barcode specification |
| [EAN_8](#ean_8) | `8` | Specifies that the data should be decoded with { EAN-8} barcode specification |
| [GS_1_AZTEC](#gs_1_aztec) | `81` | Specifies that the data should be decoded with barcode specification |
| [GS_1_CODE_128](#gs_1_code_128) | `7` | Specifies that the data should be decoded with { GS1 CODE 128} barcode specification |
| [GS_1_COMPOSITE_BAR](#gs_1_composite_bar) | `80` | Specifies that the data should be decoded with barcode specification |
| [GS_1_DATA_MATRIX](#gs_1_data_matrix) | `31` | Specifies that the data should be decoded with { GS1DataMatrix} barcode symbology |
| [GS_1_DOT_CODE](#gs_1_dot_code) | `77` | Specifies that the data should be decoded with blank specification |
| [GS_1_HAN_XIN](#gs_1_han_xin) | `79` | Specifies that the data should be decoded with Han Xin Code blank specification |
| [GS_1_MICRO_PDF_417](#gs_1_micro_pdf_417) | `82` | Specifies that the data should be decoded with MicroPdf417 barcode specification |
| [GS_1_QR](#gs_1_qr) | `58` | Specifies that the data should be decoded with { GS1 QR} barcode specification |
| [HAN_XIN](#han_xin) | `78` | Specifies that the data should be decoded with Han Xin Code blank specification |
| [HIBC_AZTEC_LIC](#hibc_aztec_lic) | `69` | Specifies that the data should be decoded with blank specification |
| [HIBC_AZTEC_PAS](#hibc_aztec_pas) | `74` | Specifies that the data should be decoded with blank specification |
| [HIBC_CODE_128_LIC](#hibc_code_128_lic) | `68` | Specifies that the data should be decoded with blank specification |
| [HIBC_CODE_128_PAS](#hibc_code_128_pas) | `73` | Specifies that the data should be decoded with blank specification |
| [HIBC_CODE_39_LIC](#hibc_code_39_lic) | `67` | Specifies that the data should be decoded with blank specification |
| [HIBC_CODE_39_PAS](#hibc_code_39_pas) | `72` | Specifies that the data should be decoded with blank specification |
| [HIBC_DATA_MATRIX_LIC](#hibc_data_matrix_lic) | `70` | Specifies that the data should be decoded with blank specification |
| [HIBC_DATA_MATRIX_PAS](#hibc_data_matrix_pas) | `75` | Specifies that the data should be decoded with blank specification |
| [HIBCQRLIC](#hibcqrlic) | `71` | Specifies that the data should be decoded with blank specification |
| [HIBCQRPAS](#hibcqrpas) | `76` | Specifies that the data should be decoded with blank specification |
| [IATA_2_OF_5](#iata_2_of_5) | `20` | Specifies that the data should be decoded with { IATA 2 of 5} barcode specification. IATA (International Air Transport Association) uses this barcode for the management of air cargo. |
| [INTERLEAVED_2_OF_5](#interleaved_2_of_5) | `17` | Specifies that the data should be decoded with { INTERLEAVED 2 of 5} barcode specification |
| [ISBN](#isbn) | `15` | Specifies that the data should be decoded with { ISBN} barcode specification |
| [ISMN](#ismn) | `48` | Specifies that the data should be decoded with { ISMN} barcode specification |
| [ISSN](#issn) | `47` | Specifies that the data should be decoded with { ISSN} barcode specification |
| [ITALIAN_POST_25](#italian_post_25) | `19` | Specifies that the data should be decoded with { Italian Post 25} barcode specification |
| [ITF_14](#itf_14) | `21` | Specifies that the data should be decoded with { ITF14} barcode specification |
| [ITF_6](#itf_6) | `22` | Specifies that the data should be decoded with { ITF6} barcode specification |
| [MACRO_PDF_417](#macro_pdf_417) | `35` | Specifies that the data should be decoded with { MacroPdf417} barcode specification |
| [MAILMARK](#mailmark) | `66` | Specifies that the data should be decoded with Royal Mail Mailmark barcode specification. |
| [MATRIX_2_OF_5](#matrix_2_of_5) | `18` | Specifies that the data should be decoded with { Matrix 2 of 5} barcode specification |
| [MAXI_CODE](#maxi_code) | `59` | Specifies that the data should be decoded with { MaxiCode} barcode specification |
| [MICR_E_13_B](#micr_e_13_b) | `60` | Specifies that the data should be decoded with { MICR E-13B} blank specification |
| [MICRO_PDF_417](#micro_pdf_417) | `36` | Specifies that the data should be decoded with { MicroPdf417} barcode specification |
| [MICRO_QR](#micro_qr) | `56` | Specifies that the data should be decoded with { MicroQR Code} barcode specification |
| [MOST_COMMON_TYPES](#most_common_types) | `96` | Specifies that data will be checked with most commonly used symbologies |
| [MSI](#msi) | `23` | Specifies that the data should be decoded with { MSI Plessey} barcode specification |
| [NONE](#none) | `-1` | Unspecified decode type. |
| [ONE_CODE](#one_code) | `40` | Specifies that the data should be decoded with USPS { OneCode} barcode specification |
| [OPC](#opc) | `27` | Specifies that the data should be decoded with { OPC} barcode specification |
| [PATCH_CODE](#patch_code) | `46` | Specifies that the data should be decoded with { Patch code} barcode specification. Barcode symbology is used for automated scanning |
| [PDF_417](#pdf_417) | `34` | Specifies that the data should be decoded with { Pdf417} barcode symbology |
| [PHARMACODE](#pharmacode) | `29` | Specifies that the data should be decoded with { Pharmacode} barcode. This symbology is also known as Pharmaceutical BINARY Code |
| [PLANET](#planet) | `39` | Specifies that the data should be decoded with { Planet} barcode specification |
| [POSTAL_TYPES](#postal_types) | `95` | Specifies that data will be checked with all of 1.5D POSTAL barcode symbologies, like Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX |
| [POSTNET](#postnet) | `38` | Specifies that the data should be decoded with { Postnet} barcode specification |
| [PZN](#pzn) | `28` | Specifies that the data should be decoded with { PZN} barcode specification. This symbology is also known as Pharma Zentral Nummer |
| [QR](#qr) | `32` | Specifies that the data should be decoded with { QR Code} barcode specification |
| [RECT_MICRO_QR](#rect_micro_qr) | `83` | Specifies that the data should be decoded with RectMicroQR (rMQR) Code barcode specification |
| [RM_4_SCC](#rm_4_scc) | `41` | Specifies that the data should be decoded with { RM4SCC} barcode specification. RM4SCC (Royal Mail 4-state Customer Code) is used for automated mail sort process in UK. |
| [SCC_14](#scc_14) | `11` | Specifies that the data should be decoded with { SCC14} barcode specification |
| [SSCC_18](#sscc_18) | `12` | Specifies that the data should be decoded with { SSCC18} barcode specification |
| [STANDARD_2_OF_5](#standard_2_of_5) | `16` | Specifies that the data should be decoded with { Standard 2 of 5} barcode specification |
| [SUPPLEMENT](#supplement) | `49` | Specifies that the data should be decoded with { Supplement(EAN2, EAN5)} barcode specification |
| [SWISS_POST_PARCEL](#swiss_post_parcel) | `51` | Specifies that the data should be decoded with { Swiss Post Parcel Barcode} barcode specification |
| [TYPES_1D](#types_1d) | `97` | Specifies that data will be checked with all of 1D barcode symbologies |
| [TYPES_2D](#types_2d) | `98` | Specifies that data will be checked with all of 2D barcode symbologies |
| [UPCA](#upca) | `13` | Specifies that the data should be decoded with { UPC-A} barcode specification |
| [UPCE](#upce) | `14` | Specifies that the data should be decoded with { UPC-E} barcode specification |
| [VIN](#vin) | `24` | Specifies that the data should be decoded with { VIN} (Vehicle Identification Number) barcode specification |
### containsAnycontainsAny(int $expectedDecodeType, array $decodeTypes) (static) {#containsany}

Determines if the BaseDecodeType array contains specified barcode symbology

| Parameter | Type | Description |
| --- | --- | --- |
| `$expectedDecodeType` | `int` |  |
| `$decodeTypes` | `array` |  |

**Returns:** bool

### is1Dis1D(int $symbology) (static) {#is1d}

Determines if the specified BaseDecodeType contains any 1D barcode symbology

| Parameter | Type | Description |
| --- | --- | --- |
| `$symbology` | `int` |  |

**Returns:** bool true if BaseDecodeType contains any 1D barcode symbology; otherwise, returns false.

### is2Dis2D(int $symbology) (static) {#is2d}

Determines if the specified BaseDecodeType contains any 2D barcode symbology

| Parameter | Type | Description |
| --- | --- | --- |
| `$symbology` | `int` |  |

**Returns:** bool Returns true if BaseDecodeType contains any 2D barcode symbology; otherwise, returns false.

### isPostalisPostal(int $symbology) (static) {#ispostal}

Determines if the specified BaseDecodeType contains any Postal barcode symbology

| Parameter | Type | Description |
| --- | --- | --- |
| `$symbology` | `int` |  |

**Returns:** bool Returns true if BaseDecodeType contains any Postal barcode symbology; otherwise, returns false.

### ALL_SUPPORTED_TYPES {#all_supported_types}

**Value:** `99`

Specifies that data will be checked with all available symbologies

### AUSTRALIA_POST {#australia_post}

**Value:** `37`

Specifies that the data should be decoded with { Australia Post} barcode specification

### AUSTRALIAN_POSTE_PARCEL {#australian_poste_parcel}

**Value:** `50`

Specifies that the data should be decoded with { Australian Post Domestic eParcel Barcode} barcode specification

### AZTEC {#aztec}

**Value:** `33`

Specifies that the data should be decoded with { Aztec} barcode specification

### CODABAR {#codabar}

**Value:** `0`

Specifies that the data should be decoded with { CODABAR} barcode specification

### CODABLOCK_F {#codablock_f}

**Value:** `65`

Specifies that the data should be decoded with { CodablockF} barcode specification

### CODE_11 {#code_11}

**Value:** `1`

Specifies that the data should be decoded with { CODE 11} barcode specification

### CODE_128 {#code_128}

**Value:** `6`

Specifies that the data should be decoded with { CODE 128} barcode specification

### CODE_16_K {#code_16_k}

**Value:** `52`

Specifies that the data should be decoded with { SCode16K} barcode specification

### CODE_32 {#code_32}

**Value:** `61`

Specifies that the data should be decoded with { Code32} blank specification

### CODE_39 {#code_39}

**Value:** `2`

Specifies that the data should be decoded with basic charset barcode specification: ISO/IEC 16388

### CODE_39_FULL_ASCII {#code_39_full_ascii}

**Value:** `3`

Specifies that the data should be decoded with full ASCII charset barcode specification: ISO/IEC 16388

### CODE_93 {#code_93}

**Value:** `5`

Specifies that the data should be decoded with barcode specification

### COMPACT_PDF_417 {#compact_pdf_417}

**Value:** `57`

Specifies that the data should be decoded with { CompactPdf417} (Pdf417Truncated) barcode specification

### DATA_LOGIC_2_OF_5 {#data_logic_2_of_5}

**Value:** `62`

Specifies that the data should be decoded with { DataLogic 2 of 5} blank specification

### DATA_MATRIX {#data_matrix}

**Value:** `30`

Specifies that the data should be decoded with { DataMatrix} barcode symbology

### DATABAR_EXPANDED {#databar_expanded}

**Value:** `45`

Specifies that the data should be decoded with { GS1 DATABAR expanded} barcode specification

### DATABAR_EXPANDED_STACKED {#databar_expanded_stacked}

**Value:** `55`

Specifies that the data should be decoded with { GS1 DATABAR expanded stacked} barcode specification

### DATABAR_LIMITED {#databar_limited}

**Value:** `44`

Specifies that the data should be decoded with { GS1 DATABAR limited} barcode specification

### DATABAR_OMNI_DIRECTIONAL {#databar_omni_directional}

**Value:** `42`

Specifies that the data should be decoded with { GS1 DATABAR omni-directional} barcode specification

### DATABAR_STACKED {#databar_stacked}

**Value:** `54`

Specifies that the data should be decoded with { GS1 DATABAR stacked} barcode specification

### DATABAR_STACKED_OMNI_DIRECTIONAL {#databar_stacked_omni_directional}

**Value:** `53`

Specifies that the data should be decoded with { GS1 DATABAR stacked omni-directional} barcode specification

### DATABAR_TRUNCATED {#databar_truncated}

**Value:** `43`

Specifies that the data should be decoded with { GS1 DATABAR truncated} barcode specification

### DEUTSCHE_POST_IDENTCODE {#deutsche_post_identcode}

**Value:** `25`

Specifies that the data should be decoded with { DeutschePost Ident code} barcode specification

### DEUTSCHE_POST_LEITCODE {#deutsche_post_leitcode}

**Value:** `26`

Specifies that the data should be decoded with { DeutschePost Leit code} barcode specification

### DOT_CODE {#dot_code}

**Value:** `63`

Specifies that the data should be decoded with { DotCode} blank specification

### DUTCH_KIX {#dutch_kix}

**Value:** `64`

Specifies that the data should be decoded with { DotCode} blank specification

### EAN_13 {#ean_13}

**Value:** `9`

Specifies that the data should be decoded with { EAN-13} barcode specification

### EAN_14 {#ean_14}

**Value:** `10`

Specifies that the data should be decoded with { EAN14} barcode specification

### EAN_8 {#ean_8}

**Value:** `8`

Specifies that the data should be decoded with { EAN-8} barcode specification

### GS_1_AZTEC {#gs_1_aztec}

**Value:** `81`

Specifies that the data should be decoded with barcode specification

### GS_1_CODE_128 {#gs_1_code_128}

**Value:** `7`

Specifies that the data should be decoded with { GS1 CODE 128} barcode specification

### GS_1_COMPOSITE_BAR {#gs_1_composite_bar}

**Value:** `80`

Specifies that the data should be decoded with barcode specification

### GS_1_DATA_MATRIX {#gs_1_data_matrix}

**Value:** `31`

Specifies that the data should be decoded with { GS1DataMatrix} barcode symbology

### GS_1_DOT_CODE {#gs_1_dot_code}

**Value:** `77`

Specifies that the data should be decoded with blank specification

### GS_1_HAN_XIN {#gs_1_han_xin}

**Value:** `79`

Specifies that the data should be decoded with Han Xin Code blank specification

### GS_1_MICRO_PDF_417 {#gs_1_micro_pdf_417}

**Value:** `82`

Specifies that the data should be decoded with MicroPdf417 barcode specification

### GS_1_QR {#gs_1_qr}

**Value:** `58`

Specifies that the data should be decoded with { GS1 QR} barcode specification

### HAN_XIN {#han_xin}

**Value:** `78`

Specifies that the data should be decoded with Han Xin Code blank specification

### HIBC_AZTEC_LIC {#hibc_aztec_lic}

**Value:** `69`

Specifies that the data should be decoded with blank specification

### HIBC_AZTEC_PAS {#hibc_aztec_pas}

**Value:** `74`

Specifies that the data should be decoded with blank specification

### HIBC_CODE_128_LIC {#hibc_code_128_lic}

**Value:** `68`

Specifies that the data should be decoded with blank specification

### HIBC_CODE_128_PAS {#hibc_code_128_pas}

**Value:** `73`

Specifies that the data should be decoded with blank specification

### HIBC_CODE_39_LIC {#hibc_code_39_lic}

**Value:** `67`

Specifies that the data should be decoded with blank specification

### HIBC_CODE_39_PAS {#hibc_code_39_pas}

**Value:** `72`

Specifies that the data should be decoded with blank specification

### HIBC_DATA_MATRIX_LIC {#hibc_data_matrix_lic}

**Value:** `70`

Specifies that the data should be decoded with blank specification

### HIBC_DATA_MATRIX_PAS {#hibc_data_matrix_pas}

**Value:** `75`

Specifies that the data should be decoded with blank specification

### HIBCQRLIC {#hibcqrlic}

**Value:** `71`

Specifies that the data should be decoded with blank specification

### HIBCQRPAS {#hibcqrpas}

**Value:** `76`

Specifies that the data should be decoded with blank specification

### IATA_2_OF_5 {#iata_2_of_5}

**Value:** `20`

Specifies that the data should be decoded with { IATA 2 of 5} barcode specification. IATA (International Air Transport Association) uses this barcode for the management of air cargo.

### INTERLEAVED_2_OF_5 {#interleaved_2_of_5}

**Value:** `17`

Specifies that the data should be decoded with { INTERLEAVED 2 of 5} barcode specification

### ISBN {#isbn}

**Value:** `15`

Specifies that the data should be decoded with { ISBN} barcode specification

### ISMN {#ismn}

**Value:** `48`

Specifies that the data should be decoded with { ISMN} barcode specification

### ISSN {#issn}

**Value:** `47`

Specifies that the data should be decoded with { ISSN} barcode specification

### ITALIAN_POST_25 {#italian_post_25}

**Value:** `19`

Specifies that the data should be decoded with { Italian Post 25} barcode specification

### ITF_14 {#itf_14}

**Value:** `21`

Specifies that the data should be decoded with { ITF14} barcode specification

### ITF_6 {#itf_6}

**Value:** `22`

Specifies that the data should be decoded with { ITF6} barcode specification

### MACRO_PDF_417 {#macro_pdf_417}

**Value:** `35`

Specifies that the data should be decoded with { MacroPdf417} barcode specification

### MAILMARK {#mailmark}

**Value:** `66`

Specifies that the data should be decoded with Royal Mail Mailmark barcode specification.

### MATRIX_2_OF_5 {#matrix_2_of_5}

**Value:** `18`

Specifies that the data should be decoded with { Matrix 2 of 5} barcode specification

### MAXI_CODE {#maxi_code}

**Value:** `59`

Specifies that the data should be decoded with { MaxiCode} barcode specification

### MICR_E_13_B {#micr_e_13_b}

**Value:** `60`

Specifies that the data should be decoded with { MICR E-13B} blank specification

### MICRO_PDF_417 {#micro_pdf_417}

**Value:** `36`

Specifies that the data should be decoded with { MicroPdf417} barcode specification

### MICRO_QR {#micro_qr}

**Value:** `56`

Specifies that the data should be decoded with { MicroQR Code} barcode specification

### MOST_COMMON_TYPES {#most_common_types}

**Value:** `96`

Specifies that data will be checked with most commonly used symbologies

### MSI {#msi}

**Value:** `23`

Specifies that the data should be decoded with { MSI Plessey} barcode specification

### NONE {#none}

**Value:** `-1`

Unspecified decode type.

### ONE_CODE {#one_code}

**Value:** `40`

Specifies that the data should be decoded with USPS { OneCode} barcode specification

### OPC {#opc}

**Value:** `27`

Specifies that the data should be decoded with { OPC} barcode specification

### PATCH_CODE {#patch_code}

**Value:** `46`

Specifies that the data should be decoded with { Patch code} barcode specification. Barcode symbology is used for automated scanning

### PDF_417 {#pdf_417}

**Value:** `34`

Specifies that the data should be decoded with { Pdf417} barcode symbology

### PHARMACODE {#pharmacode}

**Value:** `29`

Specifies that the data should be decoded with { Pharmacode} barcode. This symbology is also known as Pharmaceutical BINARY Code

### PLANET {#planet}

**Value:** `39`

Specifies that the data should be decoded with { Planet} barcode specification

### POSTAL_TYPES {#postal_types}

**Value:** `95`

Specifies that data will be checked with all of 1.5D POSTAL barcode symbologies, like Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX

### POSTNET {#postnet}

**Value:** `38`

Specifies that the data should be decoded with { Postnet} barcode specification

### PZN {#pzn}

**Value:** `28`

Specifies that the data should be decoded with { PZN} barcode specification. This symbology is also known as Pharma Zentral Nummer

### QR {#qr}

**Value:** `32`

Specifies that the data should be decoded with { QR Code} barcode specification

### RECT_MICRO_QR {#rect_micro_qr}

**Value:** `83`

Specifies that the data should be decoded with RectMicroQR (rMQR) Code barcode specification

### RM_4_SCC {#rm_4_scc}

**Value:** `41`

Specifies that the data should be decoded with { RM4SCC} barcode specification. RM4SCC (Royal Mail 4-state Customer Code) is used for automated mail sort process in UK.

### SCC_14 {#scc_14}

**Value:** `11`

Specifies that the data should be decoded with { SCC14} barcode specification

### SSCC_18 {#sscc_18}

**Value:** `12`

Specifies that the data should be decoded with { SSCC18} barcode specification

### STANDARD_2_OF_5 {#standard_2_of_5}

**Value:** `16`

Specifies that the data should be decoded with { Standard 2 of 5} barcode specification

### SUPPLEMENT {#supplement}

**Value:** `49`

Specifies that the data should be decoded with { Supplement(EAN2, EAN5)} barcode specification

### SWISS_POST_PARCEL {#swiss_post_parcel}

**Value:** `51`

Specifies that the data should be decoded with { Swiss Post Parcel Barcode} barcode specification

### TYPES_1D {#types_1d}

**Value:** `97`

Specifies that data will be checked with all of 1D barcode symbologies

### TYPES_2D {#types_2d}

**Value:** `98`

Specifies that data will be checked with all of 2D barcode symbologies

### UPCA {#upca}

**Value:** `13`

Specifies that the data should be decoded with { UPC-A} barcode specification

### UPCE {#upce}

**Value:** `14`

Specifies that the data should be decoded with { UPC-E} barcode specification

### VIN {#vin}

**Value:** `24`

Specifies that the data should be decoded with { VIN} (Vehicle Identification Number) barcode specification

