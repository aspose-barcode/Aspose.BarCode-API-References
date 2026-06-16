---
title: DecodeType
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Tentukan jenis kode batang yang akan dibaca.
type: docs
weight: 32
url: /id/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

Tentukan jenis kode batang yang akan dibaca.

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
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | Menentukan bahwa data akan diperiksa dengan semua simbolologi yang tersedia |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Australian Post Domestic eParcel Barcode** |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Australia Post** |
| [AZTEC](#AZTEC) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Aztec** |
| [CODABAR](#CODABAR) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **CODABAR** |
| [CODABLOCK_F](#CODABLOCK-F) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **CodablockF** |
| [CODE_11](#CODE-11) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **CODE 11** |
| [CODE_128](#CODE-128) | Menentukan bahwa data harus didekode dengan **CODE 128** spesifikasi barcode |
| [CODE_16_K](#CODE-16-K) | Menentukan bahwa data harus didekode dengan **SCode16K** spesifikasi barcode |
| [CODE_32](#CODE-32) | Menentukan bahwa data harus didekode dengan **Code32** spesifikasi barcode |
| [CODE_39](#CODE-39) | Menentukan bahwa data harus didekode dengan **Code 39** spesifikasi barcode set karakter dasar: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | Menentukan bahwa data harus didekode dengan **Code 39** spesifikasi barcode set karakter ASCII penuh: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | Menentukan bahwa data harus didekode dengan **CODE 93** spesifikasi barcode |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | Menentukan bahwa data harus didekode dengan **CompactPdf417** (Pdf417Truncated) spesifikasi barcode |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | Menentukan bahwa data harus didekode dengan **GS1 DATABAR expanded** spesifikasi barcode |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | Menentukan bahwa data harus didekode dengan **GS1 DATABAR expanded stacked** spesifikasi barcode |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | Menentukan bahwa data harus didekode dengan **GS1 DATABAR limited** spesifikasi barcode |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | Menentukan bahwa data harus didekode dengan **GS1 DATABAR omni-directional** spesifikasi barcode |
| [DATABAR_STACKED](#DATABAR-STACKED) | Menentukan bahwa data harus didekode dengan **GS1 DATABAR stacked** spesifikasi barcode |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | Menentukan bahwa data harus didekode dengan **GS1 DATABAR stacked omni-directional** spesifikasi barcode |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | Menentukan bahwa data harus didekode dengan **GS1 DATABAR truncated** spesifikasi barcode |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | Menentukan bahwa data harus didekode dengan **DataLogic 2 of 5** spesifikasi barcode |
| [DATA_MATRIX](#DATA-MATRIX) | Menentukan bahwa data harus didekode dengan **DataMatrix** simbol barcode |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | Menentukan bahwa data harus didekode dengan **DeutschePost Ident code** spesifikasi barcode |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | Menentukan bahwa data harus didekode dengan **DeutschePost Leit code** spesifikasi barcode |
| [DOT_CODE](#DOT-CODE) | Menentukan bahwa data harus didekode dengan **DotCode** spesifikasi barcode |
| [DUTCH_KIX](#DUTCH-KIX) | Menentukan bahwa data harus didekode dengan **DotCode** spesifikasi barcode |
| [EAN_13](#EAN-13) | Menentukan bahwa data harus didekode dengan **EAN-13** spesifikasi barcode |
| [EAN_14](#EAN-14) | Menentukan bahwa data harus didekode dengan **EAN14** spesifikasi barcode |
| [EAN_8](#EAN-8) | Menentukan bahwa data harus didekode dengan **EAN-8** spesifikasi barcode |
| [GS_1_AZTEC](#GS-1-AZTEC) | Menentukan bahwa data harus didekode dengan **GS1 Aztec** spesifikasi barcode |
| [GS_1_CODE_128](#GS-1-CODE-128) | Menentukan bahwa data harus didekode dengan **GS1 CODE 128** spesifikasi barcode |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | Menentukan bahwa data harus didekode dengan **GS1 Composite Bar** spesifikasi barcode |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | Menentukan bahwa data harus didekode dengan  **GS1DataMatrix**  simbol barcode |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | Menentukan bahwa data harus didekode dengan  **GS1 DotCode**  spesifikasi barcode |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | Menentukan bahwa data harus didekode dengan **GS1 Han Xin Code** spesifikasi barcode |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | Menentukan bahwa data harus didekode dengan **MicroPdf417** spesifikasi barcode |
| [GS_1_QR](#GS-1-QR) | Menentukan bahwa data harus didekode dengan  **GS1 QR**  spesifikasi barcode |
| [HAN_XIN](#HAN-XIN) | Menentukan bahwa data harus didekode dengan **Han Xin Code** spesifikasi barcode |
| [HIBCQRLIC](#HIBCQRLIC) | Menentukan bahwa data harus didekode dengan  **HIBC LIC QR**  spesifikasi barcode |
| [HIBCQRPAS](#HIBCQRPAS) | Menentukan bahwa data harus didekode dengan  **HIBC PAS QR**  spesifikasi barcode |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | Menentukan bahwa data harus didekode dengan  **HIBC LIC Aztec**  spesifikasi barcode |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | Menentukan bahwa data harus didekode dengan  **HIBC PAS Aztec**  spesifikasi barcode |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | Menentukan bahwa data harus didekode dengan  **HIBC LIC Code128**  spesifikasi barcode |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | Menentukan bahwa data harus didekode dengan  **HIBC PAS Code128**  spesifikasi barcode |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | Menentukan bahwa data harus didekode dengan  **HIBC LIC Code39**  spesifikasi barcode |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | Menentukan bahwa data harus didekode dengan  **HIBC PAS Code39**  spesifikasi barcode |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | Menentukan bahwa data harus didekode dengan  **HIBC LIC DataMatrix**  spesifikasi barcode |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | Menentukan bahwa data harus didekode dengan  **HIBC PAS DataMatrix**  spesifikasi barcode |
| [IATA_2_OF_5](#IATA-2-OF-5) | Menentukan bahwa data harus didekode dengan  **IATA 2 of 5**  spesifikasi barcode. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | Menentukan bahwa data harus didekode dengan  **INTERLEAVED 2 of 5**  spesifikasi barcode |
| [ISBN](#ISBN) | Menentukan bahwa data harus didekode dengan  **ISBN**  spesifikasi barcode |
| [ISMN](#ISMN) | Menentukan bahwa data harus didekode dengan  **ISMN**  spesifikasi barcode |
| [ISSN](#ISSN) | Menentukan bahwa data harus didekode dengan  **ISSN**  spesifikasi barcode |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | Menentukan bahwa data harus didekode dengan  **Italian Post 25**  spesifikasi barcode |
| [ITF_14](#ITF-14) | Menentukan bahwa data harus didekode dengan  **ITF14**  spesifikasi barcode |
| [ITF_6](#ITF-6) | Menentukan bahwa data harus didekode dengan  **ITF6**  spesifikasi barcode |
| [MACRO_PDF_417](#MACRO-PDF-417) | Menentukan bahwa data harus didekode dengan  **MacroPdf417**  spesifikasi barcode |
| [MAILMARK](#MAILMARK) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Royal Mail Mailmark**. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Matrix 2 of 5** |
| [MAXI_CODE](#MAXI-CODE) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **MaxiCode** |
| [MICRO_PDF_417](#MICRO-PDF-417) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **MicroPdf417** |
| [MICRO_QR](#MICRO-QR) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **MicroQR Code** |
| [MICR_E_13_B](#MICR-E-13-B) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **MICR E-13B** |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | Menentukan bahwa data akan diperiksa dengan simbol yang paling umum digunakan |
| [MSI](#MSI) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **MSI Plessey** |
| [NONE](#NONE) | Tipe dekode tidak ditentukan. |
| [ONE_CODE](#ONE-CODE) | Menentukan bahwa data harus didekode dengan spesifikasi barcode USPS **OneCode** |
| [OPC](#OPC) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **OPC** |
| [PATCH_CODE](#PATCH-CODE) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Patch code**. |
| [PDF_417](#PDF-417) | Menentukan bahwa data harus didekode dengan simbol barcode **Pdf417** |
| [PHARMACODE](#PHARMACODE) | Menentukan bahwa data harus didekode dengan barcode **Pharmacode**. |
| [PLANET](#PLANET) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Planet** |
| [POSTAL_TYPES](#POSTAL-TYPES) | Menentukan bahwa data akan diperiksa dengan semua simbol barcode **1.5D POSTAL**, seperti **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Postnet** |
| [PZN](#PZN) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **PZN**. |
| [QR](#QR) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **QR Code** |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **RectMicroQR (rMQR) Code** |
| [RM_4_SCC](#RM-4-SCC) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **RM4SCC**. |
| [SCC_14](#SCC-14) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **SCC14** |
| [SSCC_18](#SSCC-18) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **SSCC18** |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Standard 2 of 5** |
| [SUPPLEMENT](#SUPPLEMENT) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Supplement(EAN2, EAN5)** |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **Swiss Post Parcel Barcode** |
| [TYPES_1D](#TYPES-1D) | Menentukan bahwa data akan diperiksa dengan semua simbologi barcode **1D** |
| [TYPES_2D](#TYPES-2D) | Menentukan bahwa data akan diperiksa dengan semua simbologi barcode **2D** |
| [UPCA](#UPCA) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **UPC-A** |
| [UPCE](#UPCE) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **UPC-E** |
| [VIN](#VIN) | Menentukan bahwa data harus didekode dengan spesifikasi barcode **VIN** (Vehicle Identification Number) |
## Methods

| Method | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | Mendapatkan array yang mewakili AllSupportedTypes |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Mengambil array nama-nama tipe decode. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menentukan apakah BaseDecodeType yang ditentukan berisi simbologi barcode 1D apa pun |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menentukan apakah BaseDecodeType yang ditentukan berisi simbologi barcode 2D apa pun |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Menentukan apakah BaseDecodeType yang ditentukan berisi simbologi barcode Pos apa pun |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | Mengonversi representasi string dari SingleDecodeType ke instance-nya. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | Mengonversi representasi string dari SingleDecodeType ke instance-nya. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Tentukan set pemindaian berdasarkan barcodeTypes |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Mengonversi representasi string dari MultiDecodeType ke instance-nya. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Mengonversi representasi string dari SingleDecodeType ke instance-nya. |
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


Menentukan bahwa data akan diperiksa dengan semua simbolologi yang tersedia

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **Australian Post Domestic eParcel Barcode**

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **Australia Post**

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **Aztec**

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **CODABAR**

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **CodablockF**

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **CODE 11**

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


Menentukan bahwa data harus didekode dengan **CODE 128** spesifikasi barcode

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


Menentukan bahwa data harus didekode dengan **SCode16K** spesifikasi barcode

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


Menentukan bahwa data harus didekode dengan **Code32** spesifikasi barcode

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


Menentukan bahwa data harus didekode dengan **Code 39** spesifikasi barcode set karakter dasar: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


Menentukan bahwa data harus didekode dengan **Code 39** spesifikasi barcode set karakter ASCII penuh: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


Menentukan bahwa data harus didekode dengan **CODE 93** spesifikasi barcode

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


Menentukan bahwa data harus didekode dengan **CompactPdf417** (Pdf417Truncated) spesifikasi barcode

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


Menentukan bahwa data harus didekode dengan **GS1 DATABAR expanded** spesifikasi barcode

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


Menentukan bahwa data harus didekode dengan **GS1 DATABAR expanded stacked** spesifikasi barcode

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


Menentukan bahwa data harus didekode dengan **GS1 DATABAR limited** spesifikasi barcode

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


Menentukan bahwa data harus didekode dengan **GS1 DATABAR omni-directional** spesifikasi barcode

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


Menentukan bahwa data harus didekode dengan **GS1 DATABAR stacked** spesifikasi barcode

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


Menentukan bahwa data harus didekode dengan **GS1 DATABAR stacked omni-directional** spesifikasi barcode

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


Menentukan bahwa data harus didekode dengan **GS1 DATABAR truncated** spesifikasi barcode

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


Menentukan bahwa data harus didekode dengan **DataLogic 2 of 5** spesifikasi barcode

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


Menentukan bahwa data harus didekode dengan **DataMatrix** simbol barcode

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


Menentukan bahwa data harus didekode dengan **DeutschePost Ident code** spesifikasi barcode

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


Menentukan bahwa data harus didekode dengan **DeutschePost Leit code** spesifikasi barcode

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


Menentukan bahwa data harus didekode dengan **DotCode** spesifikasi barcode

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


Menentukan bahwa data harus didekode dengan **DotCode** spesifikasi barcode

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


Menentukan bahwa data harus didekode dengan **EAN-13** spesifikasi barcode

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


Menentukan bahwa data harus didekode dengan **EAN14** spesifikasi barcode

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


Menentukan bahwa data harus didekode dengan **EAN-8** spesifikasi barcode

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


Menentukan bahwa data harus didekode dengan **GS1 Aztec** spesifikasi barcode

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


Menentukan bahwa data harus didekode dengan **GS1 CODE 128** spesifikasi barcode

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


Menentukan bahwa data harus didekode dengan **GS1 Composite Bar** spesifikasi barcode

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


Menentukan bahwa data harus didekode dengan  **GS1DataMatrix**  simbol barcode

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


Menentukan bahwa data harus didekode dengan  **GS1 DotCode**  spesifikasi barcode

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


Menentukan bahwa data harus didekode dengan **GS1 Han Xin Code** spesifikasi barcode

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


Menentukan bahwa data harus didekode dengan **MicroPdf417** spesifikasi barcode

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


Menentukan bahwa data harus didekode dengan  **GS1 QR**  spesifikasi barcode

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


Menentukan bahwa data harus didekode dengan **Han Xin Code** spesifikasi barcode

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


Menentukan bahwa data harus didekode dengan  **HIBC LIC QR**  spesifikasi barcode

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


Menentukan bahwa data harus didekode dengan  **HIBC PAS QR**  spesifikasi barcode

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


Menentukan bahwa data harus didekode dengan  **HIBC LIC Aztec**  spesifikasi barcode

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


Menentukan bahwa data harus didekode dengan  **HIBC PAS Aztec**  spesifikasi barcode

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


Menentukan bahwa data harus didekode dengan  **HIBC LIC Code128**  spesifikasi barcode

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


Menentukan bahwa data harus didekode dengan  **HIBC PAS Code128**  spesifikasi barcode

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


Menentukan bahwa data harus didekode dengan  **HIBC LIC Code39**  spesifikasi barcode

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


Menentukan bahwa data harus didekode dengan  **HIBC PAS Code39**  spesifikasi barcode

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


Menentukan bahwa data harus didekode dengan  **HIBC LIC DataMatrix**  spesifikasi barcode

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


Menentukan bahwa data harus didekode dengan  **HIBC PAS DataMatrix**  spesifikasi barcode

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **IATA 2 of 5**. IATA (International Air Transport Association) menggunakan barcode ini untuk manajemen kargo udara.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


Menentukan bahwa data harus didekode dengan  **INTERLEAVED 2 of 5**  spesifikasi barcode

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


Menentukan bahwa data harus didekode dengan  **ISBN**  spesifikasi barcode

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


Menentukan bahwa data harus didekode dengan  **ISMN**  spesifikasi barcode

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


Menentukan bahwa data harus didekode dengan  **ISSN**  spesifikasi barcode

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


Menentukan bahwa data harus didekode dengan  **Italian Post 25**  spesifikasi barcode

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


Menentukan bahwa data harus didekode dengan  **ITF14**  spesifikasi barcode

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


Menentukan bahwa data harus didekode dengan  **ITF6**  spesifikasi barcode

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


Menentukan bahwa data harus didekode dengan  **MacroPdf417**  spesifikasi barcode

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **Royal Mail Mailmark**.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **Matrix 2 of 5**

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **MaxiCode**

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **MicroPdf417**

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **MicroQR Code**

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **MICR E-13B**

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


Menentukan bahwa data akan diperiksa dengan simbol yang paling umum digunakan

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **MSI Plessey**

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


Tipe dekode tidak ditentukan.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode USPS **OneCode**

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **OPC**

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **Patch code**. Simbologi barcode ini digunakan untuk pemindaian otomatis.

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


Menentukan bahwa data harus didekode dengan simbol barcode **Pdf417**

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


Menentukan bahwa data harus didekode dengan barcode **Pharmacode**. Simbologi ini juga dikenal sebagai Pharmaceutical BINARY Code.

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **Planet**

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


Menentukan bahwa data akan diperiksa dengan semua simbol barcode **1.5D POSTAL**, seperti **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **Postnet**

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **PZN**. Simbologi ini juga dikenal sebagai Pharma Zentral Nummer. PZN7 dan PZN8 didukung.

### QR {#QR}
```
public static final SingleDecodeType QR
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **QR Code**

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **RectMicroQR (rMQR) Code**

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **RM4SCC**. RM4SCC (Royal Mail 4-state Customer Code) digunakan untuk proses penyortiran surat otomatis di Inggris.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **SCC14**

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **SSCC18**

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **Standard 2 of 5**

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **Supplement(EAN2, EAN5)**

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **Swiss Post Parcel Barcode**

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


Menentukan bahwa data akan diperiksa dengan semua simbologi barcode **1D**

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


Menentukan bahwa data akan diperiksa dengan semua simbologi barcode **2D**

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **UPC-A**

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **UPC-E**

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


Menentukan bahwa data harus didekode dengan spesifikasi barcode **VIN** (Vehicle Identification Number)

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


Mendapatkan array yang mewakili AllSupportedTypes

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


Mengambil array nama-nama tipe decode.

**Returns:**
java.lang.String[] - Array string berisi nama-nama tipe decode.
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


Menentukan apakah BaseDecodeType yang ditentukan berisi simbologi barcode 1D apa pun

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | BaseDecodeType untuk diuji. |

**Returns:**
boolean - Mengembalikan **true** jika BaseDecodeType berisi simbologi barcode 1D apa pun; jika tidak, mengembalikan **false**.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


Menentukan apakah BaseDecodeType yang ditentukan berisi simbologi barcode 2D apa pun

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | BaseDecodeType untuk diuji. |

**Returns:**
boolean - Mengembalikan **true** jika BaseDecodeTypeddddddddw berisi simbologi barcode 2D apa pun; jika tidak, mengembalikan **false**.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


Menentukan apakah BaseDecodeType yang ditentukan berisi simbologi barcode Pos apa pun

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | BaseDecodeType untuk diuji |

**Returns:**
boolean - Mengembalikan **true** jika BaseDecodeType berisi simbologi barcode Pos apa pun; jika tidak, mengembalikan **false**.
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


Mengonversi representasi string dari SingleDecodeType menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | String yang berisi representasi SingleDecodeType untuk dikonversi. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

sebaliknya mengembalikan tipe tak terbatas. atau SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


Mengonversi representasi string dari SingleDecodeType menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | Sebuah string yang berisi SingleDecodeType dalam format seperti "EAN8" atau "EAN13" atau "CodaBar"... untuk dikonversi. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - **true** jika s berhasil dikonversi; sebaliknya, **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


Tentukan set pemindaian berdasarkan barcodeTypes

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array dari tipe decode tunggal dan ganda |

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


Mengonversi representasi string dari MultiDecodeType menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | String dalam format baik "AllSupportedTypes" atau "EAN8,EAN13,CodaBar" untuk dikonversi. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Sebuah MultiDecodeType yang sebenarnya dikembalikan, ketika konversi selesai dengan sukses; sebaliknya mengembalikan tipe tak terbatas: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Mengonversi representasi string dari SingleDecodeType menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| parsingType | java.lang.String | Sebuah string yang berisi SingleDecodeType dalam format seperti "EAN8" atau "EAN13" atau "CodaBar"... untuk dikonversi. |

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

