---
title: "DecodeType"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Okunacak barkod tipini belirtin."
type: docs
weight: 30
url: /tr/java/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

Okunacak barkod tipini belirtin.

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
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | Verilerin tüm mevcut sembolojilerle kontrol edileceğini belirtir |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | Verilerin **Australian Post Domestic eParcel Barcode** barkod spesifikasyonu ile çözüleceğini belirtir |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | Verinin **Australia Post** barkod spesifikasyonu ile çözüleceğini belirtir |
| [AZTEC](#AZTEC) | Verinin **Aztec** barkod spesifikasyonu ile çözüleceğini belirtir |
| [CODABAR](#CODABAR) | Verinin **CODABAR** barkod spesifikasyonu ile çözüleceğini belirtir |
| [CODABLOCK_F](#CODABLOCK-F) | Verinin **CodablockF** barkod spesifikasyonu ile çözüleceğini belirtir |
| [CODE_11](#CODE-11) | Verinin **CODE 11** barkod spesifikasyonu ile çözüleceğini belirtir |
| [CODE_128](#CODE-128) | Verinin **CODE 128** barkod spesifikasyonu ile çözüleceğini belirtir |
| [CODE_16_K](#CODE-16-K) | Verinin **SCode16K** barkod spesifikasyonu ile çözüleceğini belirtir |
| [CODE_32](#CODE-32) | Verinin **Code32** barkod spesifikasyonu ile çözüleceğini belirtir |
| [CODE_39](#CODE-39) | Verinin **Code 39** temel karakter kümesi barkod spesifikasyonu: ISO/IEC 16388 ile çözüleceğini belirtir |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | Verinin **Code 39** tam ASCII karakter kümesi barkod spesifikasyonu: ISO/IEC 16388 ile çözüleceğini belirtir |
| [CODE_93](#CODE-93) | Verinin **CODE 93** barkod spesifikasyonu ile çözüleceğini belirtir |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | Verinin **CompactPdf417** (Pdf417Truncated) barkod spesifikasyonu ile çözüleceğini belirtir |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | Verinin **GS1 DATABAR expanded** barkod spesifikasyonu ile çözüleceğini belirtir |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | Verinin **GS1 DATABAR expanded stacked** barkod spesifikasyonu ile çözüleceğini belirtir |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | Verinin **GS1 DATABAR limited** barkod spesifikasyonu ile çözüleceğini belirtir |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | Verinin **GS1 DATABAR omni-directional** barkod spesifikasyonu ile çözüleceğini belirtir |
| [DATABAR_STACKED](#DATABAR-STACKED) | Verinin **GS1 DATABAR stacked** barkod spesifikasyonu ile çözüleceğini belirtir |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | Verinin **GS1 DATABAR stacked omni-directional** barkod spesifikasyonu ile çözüleceğini belirtir |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | Verinin **GS1 DATABAR truncated** barkod spesifikasyonu ile çözüleceğini belirtir |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | Verinin **DataLogic 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir |
| [DATA_MATRIX](#DATA-MATRIX) | Verinin **DataMatrix** barkod sembolojisi ile çözüleceğini belirtir |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | Verinin **DeutschePost Ident code** barkod spesifikasyonu ile çözüleceğini belirtir |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | Verinin **DeutschePost Leit code** barkod spesifikasyonu ile çözüleceğini belirtir |
| [DOT_CODE](#DOT-CODE) | Verinin **DotCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| [DUTCH_KIX](#DUTCH-KIX) | Verinin **DotCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| [EAN_13](#EAN-13) | Verinin **EAN-13** barkod spesifikasyonu ile çözüleceğini belirtir |
| [EAN_14](#EAN-14) | Verinin **EAN14** barkod spesifikasyonu ile çözüleceğini belirtir |
| [EAN_8](#EAN-8) | Verinin **EAN-8** barkod spesifikasyonu ile çözüleceğini belirtir |
| [GS_1_AZTEC](#GS-1-AZTEC) | Verinin **GS1 Aztec** barkod spesifikasyonu ile çözüleceğini belirtir |
| [GS_1_CODE_128](#GS-1-CODE-128) | Verinin **GS1 CODE 128** barkod spesifikasyonu ile çözüleceğini belirtir |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | Verinin **GS1 Composite Bar** barkod spesifikasyonu ile çözüleceğini belirtir |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | Verinin **GS1DataMatrix** barkod sembolojisi ile çözüleceğini belirtir |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | Verinin **GS1 DotCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | Verinin **GS1 Han Xin Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | Verinin **MicroPdf417** barkod spesifikasyonu ile çözüleceğini belirtir |
| [GS_1_QR](#GS-1-QR) | Verinin **GS1 QR** barkod spesifikasyonu ile çözüleceğini belirtir |
| [HAN_XIN](#HAN-XIN) | Verinin **Han Xin Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| [HIBCQRLIC](#HIBCQRLIC) | Verinin **HIBC LIC QR** barkod spesifikasyonu ile çözüleceğini belirtir |
| [HIBCQRPAS](#HIBCQRPAS) | Verinin **HIBC PAS QR** barkod spesifikasyonu ile çözüleceğini belirtir |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | Verinin **HIBC LIC Aztec** barkod spesifikasyonu ile çözüleceğini belirtir |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | Verinin **HIBC PAS Aztec** barkod spesifikasyonu ile çözüleceğini belirtir |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | Verinin **HIBC LIC Code128** barkod spesifikasyonu ile çözüleceğini belirtir |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | Verinin **HIBC PAS Code128** barkod spesifikasyonu ile çözüleceğini belirtir |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | Verinin **HIBC LIC Code39** barkod spesifikasyonu ile çözüleceğini belirtir |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | Verinin **HIBC PAS Code39** barkod spesifikasyonu ile çözüleceğini belirtir |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | Verinin **HIBC LIC DataMatrix** barkod spesifikasyonu ile çözüleceğini belirtir |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | Verinin **HIBC PAS DataMatrix** barkod spesifikasyonu ile çözüleceğini belirtir |
| [IATA_2_OF_5](#IATA-2-OF-5) | Verinin **IATA 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | Verinin **INTERLEAVED 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir |
| [ISBN](#ISBN) | Verinin **ISBN** barkod spesifikasyonu ile çözüleceğini belirtir |
| [ISMN](#ISMN) | Verinin **ISMN** barkod spesifikasyonu ile çözüleceğini belirtir |
| [ISSN](#ISSN) | Verinin **ISSN** barkod spesifikasyonu ile çözüleceğini belirtir |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | Verinin **Italian Post 25** barkod spesifikasyonu ile çözüleceğini belirtir |
| [ITF_14](#ITF-14) | Verinin **ITF14** barkod spesifikasyonu ile çözüleceğini belirtir |
| [ITF_6](#ITF-6) | Verinin **ITF6** barkod spesifikasyonu ile çözüleceğini belirtir |
| [MACRO_PDF_417](#MACRO-PDF-417) | Verinin **MacroPdf417** barkod spesifikasyonu ile çözüleceğini belirtir |
| [MAILMARK](#MAILMARK) | Verinin **Royal Mail Mailmark** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | Verinin **Matrix 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir |
| [MAXI_CODE](#MAXI-CODE) | Verinin **MaxiCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| [MICRO_PDF_417](#MICRO-PDF-417) | Verinin **MicroPdf417** barkod spesifikasyonu ile çözüleceğini belirtir |
| [MICRO_QR](#MICRO-QR) | Verinin **MicroQR Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| [MICR_E_13_B](#MICR-E-13-B) | Verinin **MICR E-13B** barkod spesifikasyonu ile çözüleceğini belirtir |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | Verinin en yaygın kullanılan sembolojilerle kontrol edileceğini belirtir |
| [MSI](#MSI) | Verinin **MSI Plessey** barkod spesifikasyonu ile çözüleceğini belirtir |
| [NONE](#NONE) | Belirtilmemiş çözüm türü. |
| [ONE_CODE](#ONE-CODE) | Verinin USPS **OneCode** barkod spesifikasyonu ile çözüleceğini belirtir |
| [OPC](#OPC) | Verinin **OPC** barkod spesifikasyonu ile çözüleceğini belirtir |
| [PATCH_CODE](#PATCH-CODE) | Verinin **Patch code** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [PDF_417](#PDF-417) | Verinin **Pdf417** barkod sembolojisi ile çözüleceğini belirtir |
| [PHARMACODE](#PHARMACODE) | Verinin **Pharmacode** barkod ile çözüleceğini belirtir. |
| [PLANET](#PLANET) | Verinin **Planet** barkod spesifikasyonu ile çözüleceğini belirtir |
| [POSTAL_TYPES](#POSTAL-TYPES) | Verinin **1.5D POSTAL** barkod sembollerinin tümüyle, örneğin **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** gibi, kontrol edileceğini belirtir |
| [POSTNET](#POSTNET) | Verinin **Postnet** barkod spesifikasyonu ile çözüleceğini belirtir |
| [PZN](#PZN) | Verinin **PZN** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [QR](#QR) | Verinin **QR Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | Verinin **RectMicroQR (rMQR) Code** barkod spesifikasyonu ile çözüleceğini belirtir |
| [RM_4_SCC](#RM-4-SCC) | Verilerin **RM4SCC** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [SCC_14](#SCC-14) | Verilerin **SCC14** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [SSCC_18](#SSCC-18) | Verilerin **SSCC18** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | Verilerin **Standard 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [SUPPLEMENT](#SUPPLEMENT) | Verilerin **Supplement(EAN2, EAN5)** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | Verilerin **Swiss Post Parcel Barcode** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [TYPES_1D](#TYPES-1D) | Verilerin tüm **1D** barkod sembolleriyle kontrol edileceğini belirtir. |
| [TYPES_2D](#TYPES-2D) | Verilerin tüm **2D** barkod sembolleriyle kontrol edileceğini belirtir. |
| [UPCA](#UPCA) | Verilerin **UPC-A** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [UPCE](#UPCE) | Verilerin **UPC-E** barkod spesifikasyonu ile çözüleceğini belirtir. |
| [VIN](#VIN) | Verilerin **VIN** (Vehicle Identification Number) barkod spesifikasyonu ile çözüleceğini belirtir. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | AllSupportedTypes'ı temsil eden bir dizi alır. |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Çözüm türlerinin adlarını içeren bir dizi alır. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Belirtilen BaseDecodeType'ın herhangi bir 1D barkod sembolü içerip içermediğini belirler. |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Belirtilen BaseDecodeType'ın herhangi bir 2D barkod sembolü içerip içermediğini belirler. |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Belirtilen BaseDecodeType'ın herhangi bir Posta barkod sembolü içerip içermediğini belirler. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | SingleDecodeType'ın dize temsilini örneğine dönüştürür. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | SingleDecodeType'ın dize temsilini örneğine dönüştürür. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Tarama setlerini barcodeTypes ile belirtin. |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType'ın dize temsilini örneğine dönüştürür. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType'ın dize temsilini örneğine dönüştürür. |
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


Verilerin tüm mevcut sembolojilerle kontrol edileceğini belirtir

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


Verilerin **Australian Post Domestic eParcel Barcode** barkod spesifikasyonu ile çözüleceğini belirtir

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


Verinin **Australia Post** barkod spesifikasyonu ile çözüleceğini belirtir

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


Verinin **Aztec** barkod spesifikasyonu ile çözüleceğini belirtir

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


Verinin **CODABAR** barkod spesifikasyonu ile çözüleceğini belirtir

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


Verinin **CodablockF** barkod spesifikasyonu ile çözüleceğini belirtir

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


Verinin **CODE 11** barkod spesifikasyonu ile çözüleceğini belirtir

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


Verinin **CODE 128** barkod spesifikasyonu ile çözüleceğini belirtir

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


Verinin **SCode16K** barkod spesifikasyonu ile çözüleceğini belirtir

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


Verinin **Code32** barkod spesifikasyonu ile çözüleceğini belirtir

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


Verinin **Code 39** temel karakter kümesi barkod spesifikasyonu: ISO/IEC 16388 ile çözüleceğini belirtir

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


Verinin **Code 39** tam ASCII karakter kümesi barkod spesifikasyonu: ISO/IEC 16388 ile çözüleceğini belirtir

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


Verinin **CODE 93** barkod spesifikasyonu ile çözüleceğini belirtir

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


Verinin **CompactPdf417** (Pdf417Truncated) barkod spesifikasyonu ile çözüleceğini belirtir

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


Verinin **GS1 DATABAR expanded** barkod spesifikasyonu ile çözüleceğini belirtir

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


Verinin **GS1 DATABAR expanded stacked** barkod spesifikasyonu ile çözüleceğini belirtir

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


Verinin **GS1 DATABAR limited** barkod spesifikasyonu ile çözüleceğini belirtir

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


Verinin **GS1 DATABAR omni-directional** barkod spesifikasyonu ile çözüleceğini belirtir

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


Verinin **GS1 DATABAR stacked** barkod spesifikasyonu ile çözüleceğini belirtir

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


Verinin **GS1 DATABAR stacked omni-directional** barkod spesifikasyonu ile çözüleceğini belirtir

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


Verinin **GS1 DATABAR truncated** barkod spesifikasyonu ile çözüleceğini belirtir

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


Verinin **DataLogic 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


Verinin **DataMatrix** barkod sembolojisi ile çözüleceğini belirtir

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


Verinin **DeutschePost Ident code** barkod spesifikasyonu ile çözüleceğini belirtir

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


Verinin **DeutschePost Leit code** barkod spesifikasyonu ile çözüleceğini belirtir

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


Verinin **DotCode** barkod spesifikasyonu ile çözüleceğini belirtir

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


Verinin **DotCode** barkod spesifikasyonu ile çözüleceğini belirtir

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


Verinin **EAN-13** barkod spesifikasyonu ile çözüleceğini belirtir

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


Verinin **EAN14** barkod spesifikasyonu ile çözüleceğini belirtir

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


Verinin **EAN-8** barkod spesifikasyonu ile çözüleceğini belirtir

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


Verinin **GS1 Aztec** barkod spesifikasyonu ile çözüleceğini belirtir

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


Verinin **GS1 CODE 128** barkod spesifikasyonu ile çözüleceğini belirtir

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


Verinin **GS1 Composite Bar** barkod spesifikasyonu ile çözüleceğini belirtir

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


Verinin **GS1DataMatrix** barkod sembolojisi ile çözüleceğini belirtir

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


Verinin **GS1 DotCode** barkod spesifikasyonu ile çözüleceğini belirtir

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


Verinin **GS1 Han Xin Code** barkod spesifikasyonu ile çözüleceğini belirtir

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


Verinin **MicroPdf417** barkod spesifikasyonu ile çözüleceğini belirtir

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


Verinin **GS1 QR** barkod spesifikasyonu ile çözüleceğini belirtir

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


Verinin **Han Xin Code** barkod spesifikasyonu ile çözüleceğini belirtir

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


Verinin **HIBC LIC QR** barkod spesifikasyonu ile çözüleceğini belirtir

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


Verinin **HIBC PAS QR** barkod spesifikasyonu ile çözüleceğini belirtir

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


Verinin **HIBC LIC Aztec** barkod spesifikasyonu ile çözüleceğini belirtir

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


Verinin **HIBC PAS Aztec** barkod spesifikasyonu ile çözüleceğini belirtir

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


Verinin **HIBC LIC Code128** barkod spesifikasyonu ile çözüleceğini belirtir

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


Verinin **HIBC PAS Code128** barkod spesifikasyonu ile çözüleceğini belirtir

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


Verinin **HIBC LIC Code39** barkod spesifikasyonu ile çözüleceğini belirtir

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


Verinin **HIBC PAS Code39** barkod spesifikasyonu ile çözüleceğini belirtir

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


Verinin **HIBC LIC DataMatrix** barkod spesifikasyonu ile çözüleceğini belirtir

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


Verinin **HIBC PAS DataMatrix** barkod spesifikasyonu ile çözüleceğini belirtir

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


Verilerin **IATA 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir. IATA (International Air Transport Association) bu barkodu hava kargo yönetimi için kullanır.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


Verinin **INTERLEAVED 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


Verinin **ISBN** barkod spesifikasyonu ile çözüleceğini belirtir

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


Verinin **ISMN** barkod spesifikasyonu ile çözüleceğini belirtir

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


Verinin **ISSN** barkod spesifikasyonu ile çözüleceğini belirtir

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


Verinin **Italian Post 25** barkod spesifikasyonu ile çözüleceğini belirtir

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


Verinin **ITF14** barkod spesifikasyonu ile çözüleceğini belirtir

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


Verinin **ITF6** barkod spesifikasyonu ile çözüleceğini belirtir

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


Verinin **MacroPdf417** barkod spesifikasyonu ile çözüleceğini belirtir

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


Verinin **Royal Mail Mailmark** barkod spesifikasyonu ile çözüleceğini belirtir.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


Verinin **Matrix 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


Verinin **MaxiCode** barkod spesifikasyonu ile çözüleceğini belirtir

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


Verinin **MicroPdf417** barkod spesifikasyonu ile çözüleceğini belirtir

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


Verinin **MicroQR Code** barkod spesifikasyonu ile çözüleceğini belirtir

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


Verinin **MICR E-13B** barkod spesifikasyonu ile çözüleceğini belirtir

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


Verinin en yaygın kullanılan sembolojilerle kontrol edileceğini belirtir

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


Verinin **MSI Plessey** barkod spesifikasyonu ile çözüleceğini belirtir

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


Belirtilmemiş çözüm türü.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


Verinin USPS **OneCode** barkod spesifikasyonu ile çözüleceğini belirtir

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


Verinin **OPC** barkod spesifikasyonu ile çözüleceğini belirtir

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


Verilerin **Patch code** barkod spesifikasyonu ile çözüleceğini belirtir. Barkod sembolü otomatik tarama için kullanılır.

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


Verinin **Pdf417** barkod sembolojisi ile çözüleceğini belirtir

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


Verilerin **Pharmacode** barkodu ile çözüleceğini belirtir. Bu sembol aynı zamanda Pharmaceutical BINARY Code olarak da bilinir.

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


Verinin **Planet** barkod spesifikasyonu ile çözüleceğini belirtir

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


Verinin **1.5D POSTAL** barkod sembollerinin tümüyle, örneğin **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** gibi, kontrol edileceğini belirtir

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


Verinin **Postnet** barkod spesifikasyonu ile çözüleceğini belirtir

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


Verilerin **PZN** barkod spesifikasyonu ile çözüleceğini belirtir. Bu sembol aynı zamanda Pharma Zentral Nummer olarak bilinir. PZN7 ve PZN8 desteklenir.

### QR {#QR}
```
public static final SingleDecodeType QR
```


Verinin **QR Code** barkod spesifikasyonu ile çözüleceğini belirtir

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


Verinin **RectMicroQR (rMQR) Code** barkod spesifikasyonu ile çözüleceğini belirtir

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


Verilerin **RM4SCC** barkod spesifikasyonu ile çözüleceğini belirtir. RM4SCC (Royal Mail 4-state Customer Code), Birleşik Krallık'ta otomatik posta sınıflandırma sürecinde kullanılır.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


Verilerin **SCC14** barkod spesifikasyonu ile çözüleceğini belirtir.

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


Verilerin **SSCC18** barkod spesifikasyonu ile çözüleceğini belirtir.

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


Verilerin **Standard 2 of 5** barkod spesifikasyonu ile çözüleceğini belirtir.

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


Verilerin **Supplement(EAN2, EAN5)** barkod spesifikasyonu ile çözüleceğini belirtir.

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


Verilerin **Swiss Post Parcel Barcode** barkod spesifikasyonu ile çözüleceğini belirtir.

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


Verilerin tüm **1D** barkod sembolleriyle kontrol edileceğini belirtir.

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


Verilerin tüm **2D** barkod sembolleriyle kontrol edileceğini belirtir.

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


Verilerin **UPC-A** barkod spesifikasyonu ile çözüleceğini belirtir.

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


Verilerin **UPC-E** barkod spesifikasyonu ile çözüleceğini belirtir.

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


Verilerin **VIN** (Vehicle Identification Number) barkod spesifikasyonu ile çözüleceğini belirtir.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


AllSupportedTypes'ı temsil eden bir dizi alır.

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


Çözüm türlerinin adlarını içeren bir dizi alır.

**Returns:**
java.lang.String[] - Çözüm türlerinin adlarını içeren bir dizi.
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


Belirtilen BaseDecodeType'ın herhangi bir 1D barkod sembolü içerip içermediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Test edilecek BaseDecodeType. |

**Returns:**
boolean - **true** döndürür eğer BaseDecodeType herhangi bir 1D barkod sembolojisi içeriyorsa; aksi takdirde **false** döndürür.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


Belirtilen BaseDecodeType'ın herhangi bir 2D barkod sembolü içerip içermediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Test edilecek BaseDecodeType. |

**Returns:**
boolean - **true** döndürür eğer BaseDecodeTypeddddddddw herhangi bir 2D barkod sembolojisi içeriyorsa; aksi takdirde **false** döndürür.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


Belirtilen BaseDecodeType'ın herhangi bir Posta barkod sembolü içerip içermediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Test edilecek BaseDecodeType |

**Returns:**
boolean - **true** döndürür eğer BaseDecodeType herhangi bir Posta barkod sembolojisi içeriyorsa; aksi takdirde **false** döndürür.
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


SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | Dönüştürülecek bir SingleDecodeType temsili içeren bir dize. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

aksi takdirde belirsiz bir tip döndürür. ya da SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | Dönüştürülecek \"EAN8\" veya \"EAN13\" veya \"CodaBar\"... biçimindeki bir SingleDecodeType içeren bir dize. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - s başarıyla dönüştürüldüyse **true**; aksi takdirde **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


Tarama setlerini barcodeTypes ile belirtin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tek ve çoklu çözümleme tiplerinin dizisi |

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


MultiDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | Dönüştürmek için "AllSupportedTypes" veya "EAN8,EAN13,CodaBar" biçiminde bir dize. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully; otherwise it returns indefinite type: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType'ın dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | Dönüştürülecek \"EAN8\" veya \"EAN13\" veya \"CodaBar\"... biçimindeki bir SingleDecodeType içeren bir dize. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully; otherwise it returns indefinite type: DecodeType.None.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

