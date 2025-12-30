---
title: DecodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: Specify the type of barcode to read.
type: docs
weight: 32
url: /androidjava/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

Specify the type of barcode to read.

--------------------

> ```
> This sample shows how to detect Code39 and Code128 barcodes.
>  
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## Fields

| Field | Description |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | Specifies that data will be checked with all available symbologies |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | Specifies that the data should be decoded with  **Australian Post Domestic eParcel Barcode**  barcode specification |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | Specifies that the data should be decoded with  **Australia Post**  barcode specification |
| [AZTEC](#AZTEC) | Specifies that the data should be decoded with  **Aztec**  barcode specification |
| [CODABAR](#CODABAR) | Specifies that the data should be decoded with  **CODABAR**  barcode specification |
| [CODABLOCK_F](#CODABLOCK-F) | Specifies that the data should be decoded with  **CodablockF**  barcode specification |
| [CODE_11](#CODE-11) | Specifies that the data should be decoded with  **CODE 11**  barcode specification |
| [CODE_128](#CODE-128) | Specifies that the data should be decoded with  **CODE 128**  barcode specification |
| [CODE_16_K](#CODE-16-K) | Specifies that the data should be decoded with  **SCode16K**  barcode specification |
| [CODE_32](#CODE-32) | Specifies that the data should be decoded with  **Code32**  barcode specification |
| [CODE_39](#CODE-39) | Specifies that the data should be decoded with  **Code 39**  basic charset barcode specification: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | Specifies that the data should be decoded with  **Code 39**  full ASCII charset barcode specification: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | Specifies that the data should be decoded with  **CODE 93**  barcode specification |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | Specifies that the data should be decoded with  **CompactPdf417**  (Pdf417Truncated) barcode specification |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | Specifies that the data should be decoded with  **GS1 DATABAR expanded**  barcode specification |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | Specifies that the data should be decoded with  **GS1 DATABAR expanded stacked**  barcode specification |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | Specifies that the data should be decoded with  **GS1 DATABAR limited**  barcode specification |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | Specifies that the data should be decoded with  **GS1 DATABAR omni-directional**  barcode specification |
| [DATABAR_STACKED](#DATABAR-STACKED) | Specifies that the data should be decoded with  **GS1 DATABAR stacked**  barcode specification |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | Specifies that the data should be decoded with  **GS1 DATABAR stacked omni-directional**  barcode specification |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | Specifies that the data should be decoded with  **GS1 DATABAR truncated**  barcode specification |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | Specifies that the data should be decoded with  **DataLogic 2 of 5**  barcode specification |
| [DATA_MATRIX](#DATA-MATRIX) | Specifies that the data should be decoded with  **DataMatrix**  barcode symbology |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | Specifies that the data should be decoded with  **DeutschePost Ident code**  barcode specification |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | Specifies that the data should be decoded with  **DeutschePost Leit code**  barcode specification |
| [DOT_CODE](#DOT-CODE) | Specifies that the data should be decoded with  **DotCode**  barcode specification |
| [DUTCH_KIX](#DUTCH-KIX) | Specifies that the data should be decoded with  **DotCode**  barcode specification |
| [EAN_13](#EAN-13) | Specifies that the data should be decoded with  **EAN-13**  barcode specification |
| [EAN_14](#EAN-14) | Specifies that the data should be decoded with  **EAN14**  barcode specification |
| [EAN_8](#EAN-8) | Specifies that the data should be decoded with  **EAN-8**  barcode specification |
| [GS_1_AZTEC](#GS-1-AZTEC) | Specifies that the data should be decoded with  **GS1 Aztec**  barcode specification |
| [GS_1_CODE_128](#GS-1-CODE-128) | Specifies that the data should be decoded with  **GS1 CODE 128**  barcode specification |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | Specifies that the data should be decoded with  **GS1 Composite Bar**  barcode specification |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | Specifies that the data should be decoded with  **GS1DataMatrix**  barcode symbology |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | Specifies that the data should be decoded with  **GS1 DotCode**  barcode specification |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | Specifies that the data should be decoded with **GS1 Han Xin Code** barcode specification |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | Specifies that the data should be decoded with **MicroPdf417** barcode specification |
| [GS_1_QR](#GS-1-QR) | Specifies that the data should be decoded with  **GS1 QR**  barcode specification |
| [HAN_XIN](#HAN-XIN) | Specifies that the data should be decoded with **Han Xin Code** barcode specification |
| [HIBCQRLIC](#HIBCQRLIC) | Specifies that the data should be decoded with  **HIBC LIC QR**  barcode specification |
| [HIBCQRPAS](#HIBCQRPAS) | Specifies that the data should be decoded with  **HIBC PAS QR**  barcode specification |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | Specifies that the data should be decoded with  **HIBC LIC Aztec**  barcode specification |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | Specifies that the data should be decoded with  **HIBC PAS Aztec**  barcode specification |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | Specifies that the data should be decoded with  **HIBC LIC Code128**  barcode specification |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | Specifies that the data should be decoded with  **HIBC PAS Code128**  barcode specification |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | Specifies that the data should be decoded with  **HIBC LIC Code39**  barcode specification |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | Specifies that the data should be decoded with  **HIBC PAS Code39**  barcode specification |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | Specifies that the data should be decoded with  **HIBC LIC DataMatrix**  barcode specification |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | Specifies that the data should be decoded with  **HIBC PAS DataMatrix**  barcode specification |
| [IATA_2_OF_5](#IATA-2-OF-5) | Specifies that the data should be decoded with  **IATA 2 of 5**  barcode specification. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | Specifies that the data should be decoded with  **INTERLEAVED 2 of 5**  barcode specification |
| [ISBN](#ISBN) | Specifies that the data should be decoded with  **ISBN**  barcode specification |
| [ISMN](#ISMN) | Specifies that the data should be decoded with  **ISMN**  barcode specification |
| [ISSN](#ISSN) | Specifies that the data should be decoded with  **ISSN**  barcode specification |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | Specifies that the data should be decoded with  **Italian Post 25**  barcode specification |
| [ITF_14](#ITF-14) | Specifies that the data should be decoded with  **ITF14**  barcode specification |
| [ITF_6](#ITF-6) | Specifies that the data should be decoded with  **ITF6**  barcode specification |
| [MACRO_PDF_417](#MACRO-PDF-417) | Specifies that the data should be decoded with  **MacroPdf417**  barcode specification |
| [MAILMARK](#MAILMARK) | Specifies that the data should be decoded with **Royal Mail Mailmark** barcode specification. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | Specifies that the data should be decoded with  **Matrix 2 of 5**  barcode specification |
| [MAXI_CODE](#MAXI-CODE) | Specifies that the data should be decoded with  **MaxiCode**  barcode specification |
| [MICRO_PDF_417](#MICRO-PDF-417) | Specifies that the data should be decoded with  **MicroPdf417**  barcode specification |
| [MICRO_QR](#MICRO-QR) | Specifies that the data should be decoded with  **MicroQR Code**  barcode specification |
| [MICR_E_13_B](#MICR-E-13-B) | Specifies that the data should be decoded with  **MICR E-13B**  barcode specification |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | Specifies that data will be checked with most commonly used symbologies |
| [MSI](#MSI) | Specifies that the data should be decoded with  **MSI Plessey**  barcode specification |
| [NONE](#NONE) | Unspecified decode type. |
| [ONE_CODE](#ONE-CODE) | Specifies that the data should be decoded with USPS  **OneCode**  barcode specification |
| [OPC](#OPC) | Specifies that the data should be decoded with  **OPC**  barcode specification |
| [PATCH_CODE](#PATCH-CODE) | Specifies that the data should be decoded with  **Patch code**  barcode specification. |
| [PDF_417](#PDF-417) | Specifies that the data should be decoded with  **Pdf417**  barcode symbology |
| [PHARMACODE](#PHARMACODE) | Specifies that the data should be decoded with  **Pharmacode**  barcode. |
| [PLANET](#PLANET) | Specifies that the data should be decoded with  **Planet**  barcode specification |
| [POSTAL_TYPES](#POSTAL-TYPES) | Specifies that data will be checked with all of **1.5D POSTAL** barcode symbologies, like **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | Specifies that the data should be decoded with  **Postnet**  barcode specification |
| [PZN](#PZN) | Specifies that the data should be decoded with  **PZN**  barcode specification. |
| [QR](#QR) | Specifies that the data should be decoded with  **QR Code**  barcode specification |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | Specifies that the data should be decoded with **RectMicroQR (rMQR) Code** barcode specification |
| [RM_4_SCC](#RM-4-SCC) | Specifies that the data should be decoded with  **RM4SCC**  barcode specification. |
| [SCC_14](#SCC-14) | Specifies that the data should be decoded with  **SCC14**  barcode specification |
| [SSCC_18](#SSCC-18) | Specifies that the data should be decoded with  **SSCC18**  barcode specification |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | Specifies that the data should be decoded with  **Standard 2 of 5**  barcode specification |
| [SUPPLEMENT](#SUPPLEMENT) | Specifies that the data should be decoded with  **Supplement(EAN2, EAN5)**  barcode specification |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | Specifies that the data should be decoded with  **Swiss Post Parcel Barcode**  barcode specification |
| [TYPES_1D](#TYPES-1D) | Specifies that data will be checked with all of **1D** barcode symbologies |
| [TYPES_2D](#TYPES-2D) | Specifies that data will be checked with all of **2D** barcode symbologies |
| [UPCA](#UPCA) | Specifies that the data should be decoded with  **UPC-A**  barcode specification |
| [UPCE](#UPCE) | Specifies that the data should be decoded with  **UPC-E**  barcode specification |
| [VIN](#VIN) | Specifies that the data should be decoded with  **VIN**  (Vehicle Identification Number) barcode specification |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | Gets an array that represents AllSupportedTypes |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Retrieves an array of the names of the decode types. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Determines if the specified BaseDecodeType contains any 1D barcode symbology |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Determines if the specified BaseDecodeType contains any 2D barcode symbology |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Determines if the specified BaseDecodeType contains any Postal barcode symbology |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | Converts the string representation of a SingleDecodeType to its instance. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | Converts the string representation of a SingleDecodeType to its instance. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Specify scan sets by barcodeTypes |
| [toString()](#toString--) |  |
| [tryParseMultyDecodeType(String parsingType)](#tryParseMultyDecodeType-java.lang.String-) | Converts the string representation of a MultyDecodeType to its instance. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converts the string representation of a SingleDecodeType to its instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DecodeType() {#DecodeType--}
```
public DecodeType()
```


### ALL_SUPPORTED_TYPES {#ALL-SUPPORTED-TYPES}
```
public static final MultyDecodeType ALL_SUPPORTED_TYPES
```


Specifies that data will be checked with all available symbologies

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


Specifies that the data should be decoded with  **Australian Post Domestic eParcel Barcode**  barcode specification

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


Specifies that the data should be decoded with  **Australia Post**  barcode specification

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


Specifies that the data should be decoded with  **Aztec**  barcode specification

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


Specifies that the data should be decoded with  **CODABAR**  barcode specification

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


Specifies that the data should be decoded with  **CodablockF**  barcode specification

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


Specifies that the data should be decoded with  **CODE 11**  barcode specification

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


Specifies that the data should be decoded with  **CODE 128**  barcode specification

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


Specifies that the data should be decoded with  **SCode16K**  barcode specification

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


Specifies that the data should be decoded with  **Code32**  barcode specification

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


Specifies that the data should be decoded with  **Code 39**  basic charset barcode specification: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


Specifies that the data should be decoded with  **Code 39**  full ASCII charset barcode specification: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


Specifies that the data should be decoded with  **CODE 93**  barcode specification

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


Specifies that the data should be decoded with  **CompactPdf417**  (Pdf417Truncated) barcode specification

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


Specifies that the data should be decoded with  **GS1 DATABAR expanded**  barcode specification

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


Specifies that the data should be decoded with  **GS1 DATABAR expanded stacked**  barcode specification

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


Specifies that the data should be decoded with  **GS1 DATABAR limited**  barcode specification

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


Specifies that the data should be decoded with  **GS1 DATABAR omni-directional**  barcode specification

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


Specifies that the data should be decoded with  **GS1 DATABAR stacked**  barcode specification

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


Specifies that the data should be decoded with  **GS1 DATABAR stacked omni-directional**  barcode specification

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


Specifies that the data should be decoded with  **GS1 DATABAR truncated**  barcode specification

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


Specifies that the data should be decoded with  **DataLogic 2 of 5**  barcode specification

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


Specifies that the data should be decoded with  **DataMatrix**  barcode symbology

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


Specifies that the data should be decoded with  **DeutschePost Ident code**  barcode specification

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


Specifies that the data should be decoded with  **DeutschePost Leit code**  barcode specification

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


Specifies that the data should be decoded with  **DotCode**  barcode specification

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


Specifies that the data should be decoded with  **DotCode**  barcode specification

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


Specifies that the data should be decoded with  **EAN-13**  barcode specification

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


Specifies that the data should be decoded with  **EAN14**  barcode specification

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


Specifies that the data should be decoded with  **EAN-8**  barcode specification

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


Specifies that the data should be decoded with  **GS1 Aztec**  barcode specification

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


Specifies that the data should be decoded with  **GS1 CODE 128**  barcode specification

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


Specifies that the data should be decoded with  **GS1 Composite Bar**  barcode specification

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


Specifies that the data should be decoded with  **GS1DataMatrix**  barcode symbology

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


Specifies that the data should be decoded with  **GS1 DotCode**  barcode specification

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


Specifies that the data should be decoded with **GS1 Han Xin Code** barcode specification

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


Specifies that the data should be decoded with **MicroPdf417** barcode specification

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


Specifies that the data should be decoded with  **GS1 QR**  barcode specification

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


Specifies that the data should be decoded with **Han Xin Code** barcode specification

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


Specifies that the data should be decoded with  **HIBC LIC QR**  barcode specification

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


Specifies that the data should be decoded with  **HIBC PAS QR**  barcode specification

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


Specifies that the data should be decoded with  **HIBC LIC Aztec**  barcode specification

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


Specifies that the data should be decoded with  **HIBC PAS Aztec**  barcode specification

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


Specifies that the data should be decoded with  **HIBC LIC Code128**  barcode specification

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


Specifies that the data should be decoded with  **HIBC PAS Code128**  barcode specification

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


Specifies that the data should be decoded with  **HIBC LIC Code39**  barcode specification

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


Specifies that the data should be decoded with  **HIBC PAS Code39**  barcode specification

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


Specifies that the data should be decoded with  **HIBC LIC DataMatrix**  barcode specification

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


Specifies that the data should be decoded with  **HIBC PAS DataMatrix**  barcode specification

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


Specifies that the data should be decoded with  **IATA 2 of 5**  barcode specification. IATA (International Air Transport Association) uses this barcode for the management of air cargo.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


Specifies that the data should be decoded with  **INTERLEAVED 2 of 5**  barcode specification

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


Specifies that the data should be decoded with  **ISBN**  barcode specification

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


Specifies that the data should be decoded with  **ISMN**  barcode specification

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


Specifies that the data should be decoded with  **ISSN**  barcode specification

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


Specifies that the data should be decoded with  **Italian Post 25**  barcode specification

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


Specifies that the data should be decoded with  **ITF14**  barcode specification

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


Specifies that the data should be decoded with  **ITF6**  barcode specification

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


Specifies that the data should be decoded with  **MacroPdf417**  barcode specification

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


Specifies that the data should be decoded with **Royal Mail Mailmark** barcode specification.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


Specifies that the data should be decoded with  **Matrix 2 of 5**  barcode specification

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


Specifies that the data should be decoded with  **MaxiCode**  barcode specification

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


Specifies that the data should be decoded with  **MicroPdf417**  barcode specification

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


Specifies that the data should be decoded with  **MicroQR Code**  barcode specification

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


Specifies that the data should be decoded with  **MICR E-13B**  barcode specification

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultyDecodeType MOST_COMMON_TYPES
```


Specifies that data will be checked with most commonly used symbologies

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


Specifies that the data should be decoded with  **MSI Plessey**  barcode specification

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


Unspecified decode type.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


Specifies that the data should be decoded with USPS  **OneCode**  barcode specification

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


Specifies that the data should be decoded with  **OPC**  barcode specification

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


Specifies that the data should be decoded with  **Patch code**  barcode specification. Barcode symbology is used for automated scanning

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


Specifies that the data should be decoded with  **Pdf417**  barcode symbology

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


Specifies that the data should be decoded with  **Pharmacode**  barcode. This symbology is also known as Pharmaceutical BINARY Code

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


Specifies that the data should be decoded with  **Planet**  barcode specification

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultyDecodeType POSTAL_TYPES
```


Specifies that data will be checked with all of **1.5D POSTAL** barcode symbologies, like **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


Specifies that the data should be decoded with  **Postnet**  barcode specification

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


Specifies that the data should be decoded with  **PZN**  barcode specification. This symbology is also known as Pharma Zentral Nummer. PZN7 and PZN8 are supported.

### QR {#QR}
```
public static final SingleDecodeType QR
```


Specifies that the data should be decoded with  **QR Code**  barcode specification

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


Specifies that the data should be decoded with **RectMicroQR (rMQR) Code** barcode specification

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


Specifies that the data should be decoded with  **RM4SCC**  barcode specification. RM4SCC (Royal Mail 4-state Customer Code) is used for automated mail sort process in UK.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


Specifies that the data should be decoded with  **SCC14**  barcode specification

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


Specifies that the data should be decoded with  **SSCC18**  barcode specification

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


Specifies that the data should be decoded with  **Standard 2 of 5**  barcode specification

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


Specifies that the data should be decoded with  **Supplement(EAN2, EAN5)**  barcode specification

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


Specifies that the data should be decoded with  **Swiss Post Parcel Barcode**  barcode specification

### TYPES_1D {#TYPES-1D}
```
public static final MultyDecodeType TYPES_1D
```


Specifies that data will be checked with all of **1D** barcode symbologies

### TYPES_2D {#TYPES-2D}
```
public static final MultyDecodeType TYPES_2D
```


Specifies that data will be checked with all of **2D** barcode symbologies

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


Specifies that the data should be decoded with  **UPC-A**  barcode specification

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


Specifies that the data should be decoded with  **UPC-E**  barcode specification

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


Specifies that the data should be decoded with  **VIN**  (Vehicle Identification Number) barcode specification

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


Gets an array that represents AllSupportedTypes

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


Retrieves an array of the names of the decode types.

**Returns:**
java.lang.String[] - A string array of the names of the decode types.
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


Determines if the specified BaseDecodeType contains any 1D barcode symbology

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | The BaseDecodeType to test. |

**Returns:**
boolean - Returns **true** if BaseDecodeType contains any 1D barcode symbology; otherwise, returns **false**.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


Determines if the specified BaseDecodeType contains any 2D barcode symbology

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | The BaseDecodeType to test. |

**Returns:**
boolean - Returns **true** if BaseDecodeTypeddddddddw contains any 2D barcode symbology; otherwise, returns **false**.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


Determines if the specified BaseDecodeType contains any Postal barcode symbology

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | The BaseDecodeType to test |

**Returns:**
boolean - Returns **true** if BaseDecodeType contains any Postal barcode symbology; otherwise, returns **false**.
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


Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | A string containing a SingleDecodeType representation to convert. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

otherwise it returns indefinite type. or SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | A string containing a SingleDecodeType in the format as "EAN8" or "EAN13" or "CodaBar"... to convert. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - **true** if s was converted successfully; otherwise, **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


Specify scan sets by barcodeTypes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array of single and multy decode types |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - A multi decode type
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryParseMultyDecodeType(String parsingType) {#tryParseMultyDecodeType-java.lang.String-}
```
public static MultyDecodeType tryParseMultyDecodeType(String parsingType)
```


Converts the string representation of a MultyDecodeType to its instance. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | A string in the format as either "AllSupportedTypes" or "EAN8,EAN13,CodaBar" to convert. |

**Returns:**
[MultyDecodeType](../../com.aspose.barcode.barcoderecognition/multydecodetype) - An actual MultyDecodeType is returned, when conversion has completed successfully; otherwise it returns indefinite type: new MultyDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | A string containing a SingleDecodeType in the format as "EAN8" or "EAN13" or "CodaBar"... to convert. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

