---
title: DecodeType
second_title: Aspose.BarCode per Android via Java API Reference
description: Specifica il tipo di codice a barre da leggere.
type: docs
weight: 32
url: /it/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

Specifica il tipo di codice a barre da leggere.

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

| Constructor | Descrizione |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | Specifica che i dati saranno verificati con tutte le simbologie disponibili |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Australian Post Domestic eParcel Barcode** |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Australia Post** |
| [AZTEC](#AZTEC) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Aztec** |
| [CODABAR](#CODABAR) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **CODABAR** |
| [CODABLOCK_F](#CODABLOCK-F) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **CodablockF** |
| [CODE_11](#CODE-11) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **CODE 11** |
| [CODE_128](#CODE-128) | Specifica che i dati devono essere decodificati con **CODE 128** specifica del codice a barre |
| [CODE_16_K](#CODE-16-K) | Specifica che i dati devono essere decodificati con **SCode16K** specifica del codice a barre |
| [CODE_32](#CODE-32) | Specifica che i dati devono essere decodificati con **Code32** specifica del codice a barre |
| [CODE_39](#CODE-39) | Specifica che i dati devono essere decodificati con **Code 39** specifica del set di caratteri base del codice a barre: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | Specifica che i dati devono essere decodificati con **Code 39** specifica del set di caratteri ASCII completo del codice a barre: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | Specifica che i dati devono essere decodificati con **CODE 93** specifica del codice a barre |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | Specifica che i dati devono essere decodificati con **CompactPdf417** (Pdf417Truncated) specifica del codice a barre |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | Specifica che i dati devono essere decodificati con **GS1 DATABAR expanded** specifica del codice a barre |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | Specifica che i dati devono essere decodificati con **GS1 DATABAR expanded stacked** specifica del codice a barre |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | Specifica che i dati devono essere decodificati con **GS1 DATABAR limited** specifica del codice a barre |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | Specifica che i dati devono essere decodificati con **GS1 DATABAR omni-directional** specifica del codice a barre |
| [DATABAR_STACKED](#DATABAR-STACKED) | Specifica che i dati devono essere decodificati con **GS1 DATABAR stacked** specifica del codice a barre |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | Specifica che i dati devono essere decodificati con **GS1 DATABAR stacked omni-directional** specifica del codice a barre |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | Specifica che i dati devono essere decodificati con **GS1 DATABAR truncated** specifica del codice a barre |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | Specifica che i dati devono essere decodificati con **DataLogic 2 of 5** specifica del codice a barre |
| [DATA_MATRIX](#DATA-MATRIX) | Specifica che i dati devono essere decodificati con **DataMatrix** simboli del codice a barre |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | Specifica che i dati devono essere decodificati con **DeutschePost Ident code** specifica del codice a barre |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | Specifica che i dati devono essere decodificati con **DeutschePost Leit code** specifica del codice a barre |
| [DOT_CODE](#DOT-CODE) | Specifica che i dati devono essere decodificati con **DotCode** specifica del codice a barre |
| [DUTCH_KIX](#DUTCH-KIX) | Specifica che i dati devono essere decodificati con **DotCode** specifica del codice a barre |
| [EAN_13](#EAN-13) | Specifica che i dati devono essere decodificati con **EAN-13** specifica del codice a barre |
| [EAN_14](#EAN-14) | Specifica che i dati devono essere decodificati con **EAN14** specifica del codice a barre |
| [EAN_8](#EAN-8) | Specifica che i dati devono essere decodificati con **EAN-8** specifica del codice a barre |
| [GS_1_AZTEC](#GS-1-AZTEC) | Specifica che i dati devono essere decodificati con **GS1 Aztec** specifica del codice a barre |
| [GS_1_CODE_128](#GS-1-CODE-128) | Specifica che i dati devono essere decodificati con **GS1 CODE 128** specifica del codice a barre |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | Specifica che i dati devono essere decodificati con **GS1 Composite Bar** specifica del codice a barre |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | Specifica che i dati devono essere decodificati con  **GS1DataMatrix**  simbologia barcode |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | Specifica che i dati devono essere decodificati con  **GS1 DotCode**  specifica barcode |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | Specifica che i dati devono essere decodificati con **GS1 Han Xin Code** specifica barcode |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | Specifica che i dati devono essere decodificati con **MicroPdf417** specifica barcode |
| [GS_1_QR](#GS-1-QR) | Specifica che i dati devono essere decodificati con  **GS1 QR**  specifica barcode |
| [HAN_XIN](#HAN-XIN) | Specifica che i dati devono essere decodificati con **Han Xin Code** specifica barcode |
| [HIBCQRLIC](#HIBCQRLIC) | Specifica che i dati devono essere decodificati con  **HIBC LIC QR**  specifica barcode |
| [HIBCQRPAS](#HIBCQRPAS) | Specifica che i dati devono essere decodificati con  **HIBC PAS QR**  specifica barcode |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | Specifica che i dati devono essere decodificati con  **HIBC LIC Aztec**  specifica barcode |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | Specifica che i dati devono essere decodificati con  **HIBC PAS Aztec**  specifica barcode |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | Specifica che i dati devono essere decodificati con  **HIBC LIC Code128**  specifica barcode |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | Specifica che i dati devono essere decodificati con  **HIBC PAS Code128**  specifica barcode |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | Specifica che i dati devono essere decodificati con  **HIBC LIC Code39**  specifica barcode |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | Specifica che i dati devono essere decodificati con  **HIBC PAS Code39**  specifica barcode |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | Specifica che i dati devono essere decodificati con  **HIBC LIC DataMatrix**  specifica barcode |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | Specifica che i dati devono essere decodificati con  **HIBC PAS DataMatrix**  specifica barcode |
| [IATA_2_OF_5](#IATA-2-OF-5) | Specifica che i dati devono essere decodificati con  **IATA 2 of 5**  specifica barcode. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | Specifica che i dati devono essere decodificati con  **INTERLEAVED 2 of 5**  specifica barcode |
| [ISBN](#ISBN) | Specifica che i dati devono essere decodificati con  **ISBN**  specifica barcode |
| [ISMN](#ISMN) | Specifica che i dati devono essere decodificati con  **ISMN**  specifica barcode |
| [ISSN](#ISSN) | Specifica che i dati devono essere decodificati con  **ISSN**  specifica barcode |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | Specifica che i dati devono essere decodificati con  **Italian Post 25**  specifica barcode |
| [ITF_14](#ITF-14) | Specifica che i dati devono essere decodificati con  **ITF14**  specifica barcode |
| [ITF_6](#ITF-6) | Specifica che i dati devono essere decodificati con  **ITF6**  specifica barcode |
| [MACRO_PDF_417](#MACRO-PDF-417) | Specifica che i dati devono essere decodificati con  **MacroPdf417**  specifica barcode |
| [MAILMARK](#MAILMARK) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Royal Mail Mailmark**. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Matrix 2 of 5** |
| [MAXI_CODE](#MAXI-CODE) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MaxiCode** |
| [MICRO_PDF_417](#MICRO-PDF-417) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MicroPdf417** |
| [MICRO_QR](#MICRO-QR) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MicroQR Code** |
| [MICR_E_13_B](#MICR-E-13-B) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MICR E-13B** |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | Specifica che i dati saranno controllati con le simbologie più comunemente utilizzate |
| [MSI](#MSI) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **MSI Plessey** |
| [NONE](#NONE) | Tipo di decodifica non specificato. |
| [ONE_CODE](#ONE-CODE) | Specifica che i dati devono essere decodificati con la specifica del codice a barre USPS **OneCode** |
| [OPC](#OPC) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **OPC** |
| [PATCH_CODE](#PATCH-CODE) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Patch code**. |
| [PDF_417](#PDF-417) | Specifica che i dati devono essere decodificati con la simbologia del codice a barre **Pdf417** |
| [PHARMACODE](#PHARMACODE) | Specifica che i dati devono essere decodificati con il codice a barre **Pharmacode**. |
| [PLANET](#PLANET) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Planet** |
| [POSTAL_TYPES](#POSTAL-TYPES) | Specifica che i dati saranno controllati con tutte le simbologie di codice a barre **1.5D POSTAL**, come **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Postnet** |
| [PZN](#PZN) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **PZN**. |
| [QR](#QR) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **QR Code** |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **RectMicroQR (rMQR) Code** |
| [RM_4_SCC](#RM-4-SCC) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **RM4SCC**. |
| [SCC_14](#SCC-14) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **SCC14** |
| [SSCC_18](#SSCC-18) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **SSCC18** |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Standard 2 of 5** |
| [SUPPLEMENT](#SUPPLEMENT) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Supplement(EAN2, EAN5)** |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **Swiss Post Parcel Barcode** |
| [TYPES_1D](#TYPES-1D) | Specifica che i dati saranno controllati con tutte le simbologie di codici a barre **1D** |
| [TYPES_2D](#TYPES-2D) | Specifica che i dati saranno controllati con tutte le simbologie di codici a barre **2D** |
| [UPCA](#UPCA) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **UPC-A** |
| [UPCE](#UPCE) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **UPC-E** |
| [VIN](#VIN) | Specifica che i dati devono essere decodificati con la specifica del codice a barre **VIN** (Vehicle Identification Number) |
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | Ottiene un array che rappresenta AllSupportedTypes |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Recupera un array dei nomi dei tipi di decodifica. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Determina se il BaseDecodeType specificato contiene qualche simbologia di codice a barre 1D |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Determina se il BaseDecodeType specificato contiene qualche simbologia di codice a barre 2D |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Determina se il BaseDecodeType specificato contiene qualche simbologia di codice a barre Postale |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Specifica i set di scansione per barcodeTypes |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un MultiDecodeType nella sua istanza. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. |
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


Specifica che i dati saranno verificati con tutte le simbologie disponibili

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **Australian Post Domestic eParcel Barcode**

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **Australia Post**

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **Aztec**

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **CODABAR**

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **CodablockF**

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **CODE 11**

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


Specifica che i dati devono essere decodificati con **CODE 128** specifica del codice a barre

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


Specifica che i dati devono essere decodificati con **SCode16K** specifica del codice a barre

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


Specifica che i dati devono essere decodificati con **Code32** specifica del codice a barre

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


Specifica che i dati devono essere decodificati con **Code 39** specifica del set di caratteri base del codice a barre: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


Specifica che i dati devono essere decodificati con **Code 39** specifica del set di caratteri ASCII completo del codice a barre: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


Specifica che i dati devono essere decodificati con **CODE 93** specifica del codice a barre

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


Specifica che i dati devono essere decodificati con **CompactPdf417** (Pdf417Truncated) specifica del codice a barre

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


Specifica che i dati devono essere decodificati con **GS1 DATABAR expanded** specifica del codice a barre

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


Specifica che i dati devono essere decodificati con **GS1 DATABAR expanded stacked** specifica del codice a barre

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


Specifica che i dati devono essere decodificati con **GS1 DATABAR limited** specifica del codice a barre

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


Specifica che i dati devono essere decodificati con **GS1 DATABAR omni-directional** specifica del codice a barre

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


Specifica che i dati devono essere decodificati con **GS1 DATABAR stacked** specifica del codice a barre

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


Specifica che i dati devono essere decodificati con **GS1 DATABAR stacked omni-directional** specifica del codice a barre

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


Specifica che i dati devono essere decodificati con **GS1 DATABAR truncated** specifica del codice a barre

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


Specifica che i dati devono essere decodificati con **DataLogic 2 of 5** specifica del codice a barre

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


Specifica che i dati devono essere decodificati con **DataMatrix** simboli del codice a barre

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


Specifica che i dati devono essere decodificati con **DeutschePost Ident code** specifica del codice a barre

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


Specifica che i dati devono essere decodificati con **DeutschePost Leit code** specifica del codice a barre

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


Specifica che i dati devono essere decodificati con **DotCode** specifica del codice a barre

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


Specifica che i dati devono essere decodificati con **DotCode** specifica del codice a barre

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


Specifica che i dati devono essere decodificati con **EAN-13** specifica del codice a barre

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


Specifica che i dati devono essere decodificati con **EAN14** specifica del codice a barre

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


Specifica che i dati devono essere decodificati con **EAN-8** specifica del codice a barre

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


Specifica che i dati devono essere decodificati con **GS1 Aztec** specifica del codice a barre

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


Specifica che i dati devono essere decodificati con **GS1 CODE 128** specifica del codice a barre

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


Specifica che i dati devono essere decodificati con **GS1 Composite Bar** specifica del codice a barre

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


Specifica che i dati devono essere decodificati con  **GS1DataMatrix**  simbologia barcode

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


Specifica che i dati devono essere decodificati con  **GS1 DotCode**  specifica barcode

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


Specifica che i dati devono essere decodificati con **GS1 Han Xin Code** specifica barcode

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


Specifica che i dati devono essere decodificati con **MicroPdf417** specifica barcode

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


Specifica che i dati devono essere decodificati con  **GS1 QR**  specifica barcode

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


Specifica che i dati devono essere decodificati con **Han Xin Code** specifica barcode

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


Specifica che i dati devono essere decodificati con  **HIBC LIC QR**  specifica barcode

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


Specifica che i dati devono essere decodificati con  **HIBC PAS QR**  specifica barcode

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


Specifica che i dati devono essere decodificati con  **HIBC LIC Aztec**  specifica barcode

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


Specifica che i dati devono essere decodificati con  **HIBC PAS Aztec**  specifica barcode

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


Specifica che i dati devono essere decodificati con  **HIBC LIC Code128**  specifica barcode

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


Specifica che i dati devono essere decodificati con  **HIBC PAS Code128**  specifica barcode

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


Specifica che i dati devono essere decodificati con  **HIBC LIC Code39**  specifica barcode

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


Specifica che i dati devono essere decodificati con  **HIBC PAS Code39**  specifica barcode

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


Specifica che i dati devono essere decodificati con  **HIBC LIC DataMatrix**  specifica barcode

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


Specifica che i dati devono essere decodificati con  **HIBC PAS DataMatrix**  specifica barcode

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **IATA 2 of 5**. IATA (International Air Transport Association) utilizza questo codice a barre per la gestione del trasporto aereo di merci.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


Specifica che i dati devono essere decodificati con  **INTERLEAVED 2 of 5**  specifica barcode

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


Specifica che i dati devono essere decodificati con  **ISBN**  specifica barcode

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


Specifica che i dati devono essere decodificati con  **ISMN**  specifica barcode

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


Specifica che i dati devono essere decodificati con  **ISSN**  specifica barcode

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


Specifica che i dati devono essere decodificati con  **Italian Post 25**  specifica barcode

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


Specifica che i dati devono essere decodificati con  **ITF14**  specifica barcode

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


Specifica che i dati devono essere decodificati con  **ITF6**  specifica barcode

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


Specifica che i dati devono essere decodificati con  **MacroPdf417**  specifica barcode

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **Royal Mail Mailmark**.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **Matrix 2 of 5**

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **MaxiCode**

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **MicroPdf417**

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **MicroQR Code**

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **MICR E-13B**

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


Specifica che i dati saranno controllati con le simbologie più comunemente utilizzate

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **MSI Plessey**

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


Tipo di decodifica non specificato.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre USPS **OneCode**

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **OPC**

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **Patch code**. La simbologia del codice a barre è utilizzata per la scansione automatica.

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


Specifica che i dati devono essere decodificati con la simbologia del codice a barre **Pdf417**

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


Specifica che i dati devono essere decodificati con il codice a barre **Pharmacode**. Questa simbologia è anche conosciuta come Pharmaceutical BINARY Code

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **Planet**

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


Specifica che i dati saranno controllati con tutte le simbologie di codice a barre **1.5D POSTAL**, come **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **Postnet**

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **PZN**. Questa simbologia è anche conosciuta come Pharma Zentral Nummer. Sono supportati PZN7 e PZN8.

### QR {#QR}
```
public static final SingleDecodeType QR
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **QR Code**

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **RectMicroQR (rMQR) Code**

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **RM4SCC**. RM4SCC (Royal Mail 4-state Customer Code) è utilizzato per il processo automatizzato di smistamento della posta nel Regno Unito.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **SCC14**

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **SSCC18**

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **Standard 2 of 5**

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **Supplement(EAN2, EAN5)**

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **Swiss Post Parcel Barcode**

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


Specifica che i dati saranno controllati con tutte le simbologie di codici a barre **1D**

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


Specifica che i dati saranno controllati con tutte le simbologie di codici a barre **2D**

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **UPC-A**

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **UPC-E**

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


Specifica che i dati devono essere decodificati con la specifica del codice a barre **VIN** (Vehicle Identification Number)

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


Ottiene un array che rappresenta AllSupportedTypes

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


Recupera un array dei nomi dei tipi di decodifica.

**Returns:**
java.lang.String[] - Un array di stringhe dei nomi dei tipi di decodifica.
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


Determina se il BaseDecodeType specificato contiene qualche simbologia di codice a barre 1D

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il BaseDecodeType da testare. |

**Returns:**
boolean - Restituisce **true** se BaseDecodeType contiene qualche simbologia di codice a barre 1D; altrimenti, restituisce **false**.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


Determina se il BaseDecodeType specificato contiene qualche simbologia di codice a barre 2D

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il BaseDecodeType da testare. |

**Returns:**
boolean - Restituisce **true** se BaseDecodeTypeddddddddw contiene qualche simbologia di codice a barre 2D; altrimenti, restituisce **false**.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


Determina se il BaseDecodeType specificato contiene qualche simbologia di codice a barre Postale

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Il BaseDecodeType da testare |

**Returns:**
boolean - Restituisce **true** se BaseDecodeType contiene qualche simbologia di codice a barre Postale; altrimenti, restituisce **false**.
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


Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa contenente una rappresentazione SingleDecodeType da convertire. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

altrimenti restituisce un tipo indefinito. o SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa contenente un SingleDecodeType nel formato \"EAN8\" o \"EAN13\" o \"CodaBar\"... da convertire. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - **true** se s è stato convertito con successo; altrimenti, **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


Specifica i set di scansione per barcodeTypes

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array di tipi di decodifica singoli e multipli |

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


Converte la rappresentazione stringa di un MultiDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa nel formato "AllSupportedTypes" o "EAN8,EAN13,CodaBar" da convertire. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Viene restituito un vero MultiDecodeType, quando la conversione è terminata con successo; altrimenti restituisce un tipo indefinito: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Converte la rappresentazione stringa di un SingleDecodeType nella sua istanza. Un valore di ritorno indica se la conversione è riuscita o è fallita.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| parsingType | java.lang.String | Una stringa contenente un SingleDecodeType nel formato \"EAN8\" o \"EAN13\" o \"CodaBar\"... da convertire. |

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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

