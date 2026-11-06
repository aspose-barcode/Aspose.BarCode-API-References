---
title: "DecodeType"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "Ange typen av streckkod som ska läsas."
type: docs
weight: 30
url: /sv/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

Ange typen av streckkod som ska läsas.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | Anger att data kommer att kontrolleras med alla tillgängliga symboler |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | Anger att data ska avkodas med  **Australian Post Domestic eParcel Barcode**  streckkodsspecifikation |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | Anger att data ska avkodas med  **Australia Post**  streckkodsspecifikation |
| [AZTEC](#AZTEC) | Anger att data ska avkodas med  **Aztec**  streckkodsspecifikation |
| [CODABAR](#CODABAR) | Anger att data ska avkodas med  **CODABAR**  streckkodsspecifikation |
| [CODABLOCK_F](#CODABLOCK-F) | Anger att data ska avkodas med  **CodablockF**  streckkodsspecifikation |
| [CODE_11](#CODE-11) | Anger att data ska avkodas med  **CODE 11**  streckkodsspecifikation |
| [CODE_128](#CODE-128) | Anger att data ska avkodas med  **CODE 128**  streckkodsspecifikation |
| [CODE_16_K](#CODE-16-K) | Anger att data ska avkodas med  **SCode16K**  streckkodsspecifikation |
| [CODE_32](#CODE-32) | Anger att data ska avkodas med  **Code32**  streckkodsspecifikation |
| [CODE_39](#CODE-39) | Anger att data ska avkodas med  **Code 39**  grundläggande teckenuppsättning för streckkodsspecifikation: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | Anger att data ska avkodas med  **Code 39**  fullständig ASCII‑teckenuppsättning för streckkodsspecifikation: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | Anger att data ska avkodas med  **CODE 93**  streckkodsspecifikation |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | Anger att data ska avkodas med  **CompactPdf417**  (Pdf417Truncated) streckkodsspecifikation |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | Anger att data ska avkodas med  **GS1 DATABAR expanded**  streckkodsspecifikation |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | Anger att data ska avkodas med  **GS1 DATABAR expanded stacked**  streckkodsspecifikation |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | Anger att data ska avkodas med  **GS1 DATABAR limited**  streckkodsspecifikation |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | Anger att data ska avkodas med  **GS1 DATABAR omni-directional**  streckkodsspecifikation |
| [DATABAR_STACKED](#DATABAR-STACKED) | Anger att data ska avkodas med  **GS1 DATABAR stacked**  streckkodsspecifikation |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | Anger att data ska avkodas med  **GS1 DATABAR stacked omni-directional**  streckkodsspecifikation |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | Anger att data ska avkodas med  **GS1 DATABAR truncated**  streckkodsspecifikation |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | Anger att data ska avkodas med  **DataLogic 2 of 5**  streckkodsspecifikation |
| [DATA_MATRIX](#DATA-MATRIX) | Anger att data ska avkodas med  **DataMatrix**  streckkodssymbol |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | Anger att data ska avkodas med  **DeutschePost Ident code**  streckkodsspecifikation |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | Anger att data ska avkodas med  **DeutschePost Leit code**  streckkodsspecifikation |
| [DOT_CODE](#DOT-CODE) | Anger att data ska avkodas med  **DotCode**  streckkodsspecifikation |
| [DUTCH_KIX](#DUTCH-KIX) | Anger att data ska avkodas med  **DotCode**  streckkodsspecifikation |
| [EAN_13](#EAN-13) | Anger att data ska avkodas med  **EAN-13**  streckkodsspecifikation |
| [EAN_14](#EAN-14) | Anger att data ska avkodas med  **EAN14**  streckkodsspecifikation |
| [EAN_8](#EAN-8) | Anger att data ska avkodas med  **EAN-8**  streckkodsspecifikation |
| [GS_1_AZTEC](#GS-1-AZTEC) | Anger att data ska avkodas med  **GS1 Aztec**  streckkodsspecifikation |
| [GS_1_CODE_128](#GS-1-CODE-128) | Anger att data ska avkodas med  **GS1 CODE 128**  streckkodsspecifikation |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | Anger att data ska avkodas med  **GS1 Composite Bar**  streckkodsspecifikation |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | Anger att data ska avkodas med  **GS1DataMatrix**  streckkodssymbol |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | Anger att data ska avkodas med  **GS1 DotCode**  streckkodsspecifikation |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | Anger att data ska avkodas med **GS1 Han Xin Code** streckkodsspecifikation |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | Anger att data ska avkodas med **MicroPdf417** streckkodsspecifikation |
| [GS_1_QR](#GS-1-QR) | Anger att data ska avkodas med  **GS1 QR**  streckkodsspecifikation |
| [HAN_XIN](#HAN-XIN) | Anger att data ska avkodas med **Han Xin Code** streckkodsspecifikation |
| [HIBCQRLIC](#HIBCQRLIC) | Anger att data ska avkodas med  **HIBC LIC QR**  streckkodsspecifikation |
| [HIBCQRPAS](#HIBCQRPAS) | Anger att data ska avkodas med  **HIBC PAS QR**  streckkodsspecifikation |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | Anger att data ska avkodas med  **HIBC LIC Aztec**  streckkodsspecifikation |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | Anger att data ska avkodas med  **HIBC PAS Aztec**  streckkodsspecifikation |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | Anger att data ska avkodas med  **HIBC LIC Code128**  streckkodsspecifikation |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | Anger att data ska avkodas med  **HIBC PAS Code128**  streckkodsspecifikation |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | Anger att data ska avkodas med  **HIBC LIC Code39**  streckkodsspecifikation |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | Anger att data ska avkodas med  **HIBC PAS Code39**  streckkodsspecifikation |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | Anger att data ska avkodas med  **HIBC LIC DataMatrix**  streckkodsspecifikation |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | Anger att data ska avkodas med  **HIBC PAS DataMatrix**  streckkodsspecifikation |
| [IATA_2_OF_5](#IATA-2-OF-5) | Anger att data ska avkodas med  **IATA 2 of 5**  streckkodsspecifikation. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | Anger att data ska avkodas med  **INTERLEAVED 2 of 5**  streckkodsspecifikation |
| [ISBN](#ISBN) | Anger att data ska avkodas med  **ISBN**  streckkodsspecifikation |
| [ISMN](#ISMN) | Anger att data ska avkodas med  **ISMN**  streckkodsspecifikation |
| [ISSN](#ISSN) | Anger att data ska avkodas med  **ISSN**  streckkodsspecifikation |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | Anger att data ska avkodas med  **Italian Post 25**  streckkodsspecifikation |
| [ITF_14](#ITF-14) | Anger att data ska avkodas med  **ITF14**  streckkodsspecifikation |
| [ITF_6](#ITF-6) | Anger att data ska avkodas med  **ITF6**  streckkodsspecifikation |
| [MACRO_PDF_417](#MACRO-PDF-417) | Anger att data ska avkodas med  **MacroPdf417**  streckkodsspecifikation |
| [MAILMARK](#MAILMARK) | Anger att data ska avkodas med **Royal Mail Mailmark** streckkodsspecifikation. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | Anger att data ska avkodas med  **Matrix 2 of 5**  streckkodsspecifikation |
| [MAXI_CODE](#MAXI-CODE) | Anger att data ska avkodas med  **MaxiCode**  streckkodsspecifikation |
| [MICRO_PDF_417](#MICRO-PDF-417) | Anger att data ska avkodas med  **MicroPdf417**  streckkodsspecifikation |
| [MICRO_QR](#MICRO-QR) | Anger att data ska avkodas med  **MicroQR Code**  streckkodsspecifikation |
| [MICR_E_13_B](#MICR-E-13-B) | Anger att data ska avkodas med  **MICR E-13B**  streckkodsspecifikation |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | Anger att data kommer att kontrolleras med de mest använda symbolerna |
| [MSI](#MSI) | Anger att data ska avkodas med **MSI Plessey** streckkodsspecifikation |
| [NONE](#NONE) | Ospecificerad avkodningstyp. |
| [ONE_CODE](#ONE-CODE) | Anger att data ska avkodas med USPS **OneCode** streckkodsspecifikation |
| [OPC](#OPC) | Anger att data ska avkodas med **OPC** streckkodsspecifikation |
| [PATCH_CODE](#PATCH-CODE) | Anger att data ska avkodas med **Patch code** streckkodsspecifikation. |
| [PDF_417](#PDF-417) | Anger att data ska avkodas med **Pdf417** streckkodssymbol |
| [PHARMACODE](#PHARMACODE) | Anger att data ska avkodas med **Pharmacode** streckkod. |
| [PLANET](#PLANET) | Anger att data ska avkodas med **Planet** streckkodsspecifikation |
| [POSTAL_TYPES](#POSTAL-TYPES) | Anger att data kommer att kontrolleras med alla **1.5D POSTAL** streckkodssymboler, såsom **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | Anger att data ska avkodas med **Postnet** streckkodsspecifikation |
| [PZN](#PZN) | Anger att data ska avkodas med **PZN** streckkodsspecifikation. |
| [QR](#QR) | Anger att data ska avkodas med **QR Code** streckkodsspecifikation |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | Anger att data ska avkodas med **RectMicroQR (rMQR) Code** streckkodsspecifikation |
| [RM_4_SCC](#RM-4-SCC) | Anger att data ska avkodas med **RM4SCC** streckkodsspecifikation. |
| [SCC_14](#SCC-14) | Anger att data ska avkodas med **SCC14** streckkodsspecifikation |
| [SSCC_18](#SSCC-18) | Anger att data ska avkodas med **SSCC18** streckkodsspecifikation |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | Anger att data ska avkodas med **Standard 2 of 5** streckkodsspecifikation |
| [SUPPLEMENT](#SUPPLEMENT) | Anger att data ska avkodas med **Supplement(EAN2, EAN5)** streckkodsspecifikation |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | Anger att data ska avkodas med **Swiss Post Parcel Barcode** streckkodsspecifikation |
| [TYPES_1D](#TYPES-1D) | Anger att data kommer att kontrolleras med alla **1D** streckkodssymboler |
| [TYPES_2D](#TYPES-2D) | Anger att data kommer att kontrolleras med alla **2D** streckkodssymboler |
| [UPCA](#UPCA) | Anger att data ska avkodas med **UPC-A** streckkodsspecifikation |
| [UPCE](#UPCE) | Anger att data ska avkodas med **UPC-E** streckkodsspecifikation |
| [VIN](#VIN) | Anger att data ska avkodas med **VIN** (Vehicle Identification Number) streckkodsspecifikation |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | Hämtar en array som representerar AllSupportedTypes |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Hämtar en array med namnen på avkodningstyperna. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Bestämmer om den angivna BaseDecodeType innehåller någon 1D-streckkodssymbol |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Bestämmer om den angivna BaseDecodeType innehåller någon 2D-streckkodssymbol |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Bestämmer om den angivna BaseDecodeType innehåller någon poststreckkodssymbol |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | Konverterar strängrepresentationen av en SingleDecodeType till dess instans. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | Konverterar strängrepresentationen av en SingleDecodeType till dess instans. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Specificera skanningsuppsättningar efter barcodeTypes |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Konverterar strängrepresentationen av en MultiDecodeType till dess instans. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Konverterar strängrepresentationen av en SingleDecodeType till dess instans. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DecodeType() {#DecodeType--}
```
public DecodeType()
```


### ALL_SUPPORTED_TYPES {#ALL-SUPPORTED-TYPES}
```
public static final MultiDecodeType ALL_SUPPORTED_TYPES
```


Anger att data kommer att kontrolleras med alla tillgängliga symboler

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


Anger att data ska avkodas med  **Australian Post Domestic eParcel Barcode**  streckkodsspecifikation

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


Anger att data ska avkodas med  **Australia Post**  streckkodsspecifikation

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


Anger att data ska avkodas med  **Aztec**  streckkodsspecifikation

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


Anger att data ska avkodas med  **CODABAR**  streckkodsspecifikation

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


Anger att data ska avkodas med  **CodablockF**  streckkodsspecifikation

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


Anger att data ska avkodas med  **CODE 11**  streckkodsspecifikation

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


Anger att data ska avkodas med  **CODE 128**  streckkodsspecifikation

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


Anger att data ska avkodas med  **SCode16K**  streckkodsspecifikation

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


Anger att data ska avkodas med  **Code32**  streckkodsspecifikation

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


Anger att data ska avkodas med  **Code 39**  grundläggande teckenuppsättning för streckkodsspecifikation: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


Anger att data ska avkodas med  **Code 39**  fullständig ASCII‑teckenuppsättning för streckkodsspecifikation: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


Anger att data ska avkodas med  **CODE 93**  streckkodsspecifikation

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


Anger att data ska avkodas med  **CompactPdf417**  (Pdf417Truncated) streckkodsspecifikation

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


Anger att data ska avkodas med  **GS1 DATABAR expanded**  streckkodsspecifikation

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


Anger att data ska avkodas med  **GS1 DATABAR expanded stacked**  streckkodsspecifikation

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


Anger att data ska avkodas med  **GS1 DATABAR limited**  streckkodsspecifikation

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


Anger att data ska avkodas med  **GS1 DATABAR omni-directional**  streckkodsspecifikation

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


Anger att data ska avkodas med  **GS1 DATABAR stacked**  streckkodsspecifikation

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


Anger att data ska avkodas med  **GS1 DATABAR stacked omni-directional**  streckkodsspecifikation

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


Anger att data ska avkodas med  **GS1 DATABAR truncated**  streckkodsspecifikation

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


Anger att data ska avkodas med  **DataLogic 2 of 5**  streckkodsspecifikation

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


Anger att data ska avkodas med  **DataMatrix**  streckkodssymbol

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


Anger att data ska avkodas med  **DeutschePost Ident code**  streckkodsspecifikation

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


Anger att data ska avkodas med  **DeutschePost Leit code**  streckkodsspecifikation

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


Anger att data ska avkodas med  **DotCode**  streckkodsspecifikation

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


Anger att data ska avkodas med  **DotCode**  streckkodsspecifikation

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


Anger att data ska avkodas med  **EAN-13**  streckkodsspecifikation

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


Anger att data ska avkodas med  **EAN14**  streckkodsspecifikation

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


Anger att data ska avkodas med  **EAN-8**  streckkodsspecifikation

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


Anger att data ska avkodas med  **GS1 Aztec**  streckkodsspecifikation

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


Anger att data ska avkodas med  **GS1 CODE 128**  streckkodsspecifikation

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


Anger att data ska avkodas med  **GS1 Composite Bar**  streckkodsspecifikation

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


Anger att data ska avkodas med  **GS1DataMatrix**  streckkodssymbol

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


Anger att data ska avkodas med  **GS1 DotCode**  streckkodsspecifikation

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


Anger att data ska avkodas med **GS1 Han Xin Code** streckkodsspecifikation

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


Anger att data ska avkodas med **MicroPdf417** streckkodsspecifikation

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


Anger att data ska avkodas med  **GS1 QR**  streckkodsspecifikation

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


Anger att data ska avkodas med **Han Xin Code** streckkodsspecifikation

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


Anger att data ska avkodas med  **HIBC LIC QR**  streckkodsspecifikation

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


Anger att data ska avkodas med  **HIBC PAS QR**  streckkodsspecifikation

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


Anger att data ska avkodas med  **HIBC LIC Aztec**  streckkodsspecifikation

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


Anger att data ska avkodas med  **HIBC PAS Aztec**  streckkodsspecifikation

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


Anger att data ska avkodas med  **HIBC LIC Code128**  streckkodsspecifikation

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


Anger att data ska avkodas med  **HIBC PAS Code128**  streckkodsspecifikation

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


Anger att data ska avkodas med  **HIBC LIC Code39**  streckkodsspecifikation

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


Anger att data ska avkodas med  **HIBC PAS Code39**  streckkodsspecifikation

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


Anger att data ska avkodas med  **HIBC LIC DataMatrix**  streckkodsspecifikation

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


Anger att data ska avkodas med  **HIBC PAS DataMatrix**  streckkodsspecifikation

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


Specificerar att data ska avkodas med **IATA 2 of 5** streckkodsspecifikation. IATA (International Air Transport Association) använder denna streckkod för hantering av luftfrakt.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


Anger att data ska avkodas med  **INTERLEAVED 2 of 5**  streckkodsspecifikation

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


Anger att data ska avkodas med  **ISBN**  streckkodsspecifikation

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


Anger att data ska avkodas med  **ISMN**  streckkodsspecifikation

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


Anger att data ska avkodas med  **ISSN**  streckkodsspecifikation

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


Anger att data ska avkodas med  **Italian Post 25**  streckkodsspecifikation

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


Anger att data ska avkodas med  **ITF14**  streckkodsspecifikation

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


Anger att data ska avkodas med  **ITF6**  streckkodsspecifikation

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


Anger att data ska avkodas med  **MacroPdf417**  streckkodsspecifikation

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


Anger att data ska avkodas med **Royal Mail Mailmark** streckkodsspecifikation.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


Anger att data ska avkodas med  **Matrix 2 of 5**  streckkodsspecifikation

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


Anger att data ska avkodas med  **MaxiCode**  streckkodsspecifikation

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


Anger att data ska avkodas med  **MicroPdf417**  streckkodsspecifikation

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


Anger att data ska avkodas med  **MicroQR Code**  streckkodsspecifikation

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


Anger att data ska avkodas med  **MICR E-13B**  streckkodsspecifikation

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


Anger att data kommer att kontrolleras med de mest använda symbolerna

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


Anger att data ska avkodas med **MSI Plessey** streckkodsspecifikation

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


Ospecificerad avkodningstyp.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


Anger att data ska avkodas med USPS **OneCode** streckkodsspecifikation

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


Anger att data ska avkodas med **OPC** streckkodsspecifikation

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


Specificerar att data ska avkodas med **Patch code** streckkodsspecifikation. Streckkodssymbol används för automatiserad skanning

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


Anger att data ska avkodas med **Pdf417** streckkodssymbol

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


Specificerar att data ska avkodas med **Pharmacode** streckkod. Denna symbol är också känd som Pharmaceutical BINARY Code

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


Anger att data ska avkodas med **Planet** streckkodsspecifikation

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


Anger att data kommer att kontrolleras med alla **1.5D POSTAL** streckkodssymboler, såsom **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


Anger att data ska avkodas med **Postnet** streckkodsspecifikation

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


Specificerar att data ska avkodas med **PZN** streckkodsspecifikation. Denna symbol är också känd som Pharma Zentral Nummer. PZN7 och PZN8 stöds.

### QR {#QR}
```
public static final SingleDecodeType QR
```


Anger att data ska avkodas med **QR Code** streckkodsspecifikation

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


Anger att data ska avkodas med **RectMicroQR (rMQR) Code** streckkodsspecifikation

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


Specificerar att data ska avkodas med **RM4SCC** streckkodsspecifikation. RM4SCC (Royal Mail 4-state Customer Code) används för automatiserad postsorteringsprocess i Storbritannien.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


Anger att data ska avkodas med **SCC14** streckkodsspecifikation

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


Anger att data ska avkodas med **SSCC18** streckkodsspecifikation

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


Anger att data ska avkodas med **Standard 2 of 5** streckkodsspecifikation

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


Anger att data ska avkodas med **Supplement(EAN2, EAN5)** streckkodsspecifikation

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


Anger att data ska avkodas med **Swiss Post Parcel Barcode** streckkodsspecifikation

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


Anger att data kommer att kontrolleras med alla **1D** streckkodssymboler

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


Anger att data kommer att kontrolleras med alla **2D** streckkodssymboler

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


Anger att data ska avkodas med **UPC-A** streckkodsspecifikation

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


Anger att data ska avkodas med **UPC-E** streckkodsspecifikation

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


Anger att data ska avkodas med **VIN** (Vehicle Identification Number) streckkodsspecifikation

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
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


Hämtar en array som representerar AllSupportedTypes

**Returns:**
com.aspose.barcode.barcoderecognition.SingleDecodeType[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getNames() {#getNames--}
```
public static String[] getNames()
```


Hämtar en array med namnen på avkodningstyperna.

**Returns:**
java.lang.String[] - En strängarray med namnen på avkodningstyperna.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### is1D(BaseDecodeType symbology) {#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is1D(BaseDecodeType symbology)
```


Bestämmer om den angivna BaseDecodeType innehåller någon 1D-streckkodssymbol

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Den BaseDecodeType att testa. |

**Returns:**
boolean - Returnerar **true** om BaseDecodeType innehåller någon 1D-streckkodssymbol; annars returneras **false**.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


Bestämmer om den angivna BaseDecodeType innehåller någon 2D-streckkodssymbol

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Den BaseDecodeType att testa. |

**Returns:**
boolean - Returnerar **true** om BaseDecodeTypeddddddddw innehåller någon 2D-streckkodssymbol; annars returneras **false**.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


Bestämmer om den angivna BaseDecodeType innehåller någon poststreckkodssymbol

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Den BaseDecodeType att testa |

**Returns:**
boolean - Returnerar **true** om BaseDecodeType innehåller någon poststreckkodssymbol; annars returneras **false**.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(String parsingType) {#parse-java.lang.String-}
```
public static SingleDecodeType parse(String parsingType)
```


Konverterar strängrepresentationen av en SingleDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng som innehåller en SingleDecodeType-representation att konvertera. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

annars returneras en obestämd typ. eller SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


Konverterar strängrepresentationen av en SingleDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng som innehåller en SingleDecodeType i formatet "EAN8" eller "EAN13" eller "CodaBar"... att konvertera. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - **true** om s konverterades framgångsrikt; annars **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


Specificera skanningsuppsättningar efter barcodeTypes

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array av enkla och multipla avkodningstyper |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - A multi decode type
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Konverterar strängrepresentationen av en MultiDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng i formatet antingen "AllSupportedTypes" eller "EAN8,EAN13,CodaBar" att konvertera. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully; otherwise it returns indefinite type: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Konverterar strängrepresentationen av en SingleDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | java.lang.String | En sträng som innehåller en SingleDecodeType i formatet "EAN8" eller "EAN13" eller "CodaBar"... att konvertera. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully; otherwise it returns indefinite type: DecodeType.None.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

