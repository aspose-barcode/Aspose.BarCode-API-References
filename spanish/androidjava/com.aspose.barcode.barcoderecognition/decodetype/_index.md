---
title: DecodeType
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Especifique el tipo de código de barras a leer.
type: docs
weight: 32
url: /es/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

Especifique el tipo de código de barras a leer.

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

| Constructor | Descripción |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | Especifica que los datos se comprobarán con todas las simbologías disponibles |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | Especifica que los datos deben decodificarse con  **Australian Post Domestic eParcel Barcode**  barcode specification |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | Especifica que los datos deben decodificarse con  **Australia Post**  barcode specification |
| [AZTEC](#AZTEC) | Especifica que los datos deben decodificarse con  **Aztec**  barcode specification |
| [CODABAR](#CODABAR) | Especifica que los datos deben decodificarse con  **CODABAR**  barcode specification |
| [CODABLOCK_F](#CODABLOCK-F) | Especifica que los datos deben decodificarse con  **CodablockF**  barcode specification |
| [CODE_11](#CODE-11) | Especifica que los datos deben decodificarse con  **CODE 11**  barcode specification |
| [CODE_128](#CODE-128) | Especifica que los datos deben decodificarse con  **CODE 128**  especificación de código de barras |
| [CODE_16_K](#CODE-16-K) | Especifica que los datos deben decodificarse con  **SCode16K**  especificación de código de barras |
| [CODE_32](#CODE-32) | Especifica que los datos deben decodificarse con  **Code32**  especificación de código de barras |
| [CODE_39](#CODE-39) | Especifica que los datos deben decodificarse con  **Code 39**  especificación básica de conjunto de caracteres de código de barras: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | Especifica que los datos deben decodificarse con  **Code 39**  especificación completa de conjunto de caracteres ASCII de código de barras: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | Especifica que los datos deben decodificarse con  **CODE 93**  especificación de código de barras |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | Especifica que los datos deben decodificarse con  **CompactPdf417**  (Pdf417Truncated) especificación de código de barras |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | Especifica que los datos deben decodificarse con  **GS1 DATABAR expanded**  especificación de código de barras |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | Especifica que los datos deben decodificarse con  **GS1 DATABAR expanded stacked**  especificación de código de barras |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | Especifica que los datos deben decodificarse con  **GS1 DATABAR limited**  especificación de código de barras |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | Especifica que los datos deben decodificarse con  **GS1 DATABAR omni-directional**  especificación de código de barras |
| [DATABAR_STACKED](#DATABAR-STACKED) | Especifica que los datos deben decodificarse con  **GS1 DATABAR stacked**  especificación de código de barras |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | Especifica que los datos deben decodificarse con  **GS1 DATABAR stacked omni-directional**  especificación de código de barras |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | Especifica que los datos deben decodificarse con  **GS1 DATABAR truncated**  especificación de código de barras |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | Especifica que los datos deben decodificarse con  **DataLogic 2 of 5**  especificación de código de barras |
| [DATA_MATRIX](#DATA-MATRIX) | Especifica que los datos deben decodificarse con  **DataMatrix**  simbología de código de barras |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | Especifica que los datos deben decodificarse con  **DeutschePost Ident code**  especificación de código de barras |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | Especifica que los datos deben decodificarse con  **DeutschePost Leit code**  especificación de código de barras |
| [DOT_CODE](#DOT-CODE) | Especifica que los datos deben decodificarse con  **DotCode**  especificación de código de barras |
| [DUTCH_KIX](#DUTCH-KIX) | Especifica que los datos deben decodificarse con  **DotCode**  especificación de código de barras |
| [EAN_13](#EAN-13) | Especifica que los datos deben decodificarse con  **EAN-13**  especificación de código de barras |
| [EAN_14](#EAN-14) | Especifica que los datos deben decodificarse con  **EAN14**  especificación de código de barras |
| [EAN_8](#EAN-8) | Especifica que los datos deben decodificarse con  **EAN-8**  especificación de código de barras |
| [GS_1_AZTEC](#GS-1-AZTEC) | Especifica que los datos deben decodificarse con  **GS1 Aztec**  especificación de código de barras |
| [GS_1_CODE_128](#GS-1-CODE-128) | Especifica que los datos deben decodificarse con  **GS1 CODE 128**  especificación de código de barras |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | Especifica que los datos deben decodificarse con  **GS1 Composite Bar**  especificación de código de barras |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | Especifica que los datos deben decodificarse con  **GS1DataMatrix**  simbología de código de barras |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | Especifica que los datos deben decodificarse con  **GS1 DotCode**  especificación de código de barras |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | Especifica que los datos deben decodificarse con **GS1 Han Xin Code** especificación de código de barras |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | Especifica que los datos deben decodificarse con **MicroPdf417** especificación de código de barras |
| [GS_1_QR](#GS-1-QR) | Especifica que los datos deben decodificarse con  **GS1 QR**  especificación de código de barras |
| [HAN_XIN](#HAN-XIN) | Especifica que los datos deben decodificarse con **Han Xin Code** especificación de código de barras |
| [HIBCQRLIC](#HIBCQRLIC) | Especifica que los datos deben decodificarse con  **HIBC LIC QR**  especificación de código de barras |
| [HIBCQRPAS](#HIBCQRPAS) | Especifica que los datos deben decodificarse con  **HIBC PAS QR**  especificación de código de barras |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | Especifica que los datos deben decodificarse con  **HIBC LIC Aztec**  especificación de código de barras |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | Especifica que los datos deben decodificarse con  **HIBC PAS Aztec**  especificación de código de barras |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | Especifica que los datos deben decodificarse con  **HIBC LIC Code128**  especificación de código de barras |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | Especifica que los datos deben decodificarse con  **HIBC PAS Code128**  especificación de código de barras |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | Especifica que los datos deben decodificarse con  **HIBC LIC Code39**  especificación de código de barras |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | Especifica que los datos deben decodificarse con  **HIBC PAS Code39**  especificación de código de barras |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | Especifica que los datos deben decodificarse con  **HIBC LIC DataMatrix**  especificación de código de barras |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | Especifica que los datos deben decodificarse con  **HIBC PAS DataMatrix**  especificación de código de barras |
| [IATA_2_OF_5](#IATA-2-OF-5) | Especifica que los datos deben decodificarse con  **IATA 2 of 5**  especificación de código de barras. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | Especifica que los datos deben decodificarse con  **INTERLEAVED 2 of 5**  especificación de código de barras |
| [ISBN](#ISBN) | Especifica que los datos deben decodificarse con  **ISBN**  especificación de código de barras |
| [ISMN](#ISMN) | Especifica que los datos deben decodificarse con  **ISMN**  especificación de código de barras |
| [ISSN](#ISSN) | Especifica que los datos deben decodificarse con  **ISSN**  especificación de código de barras |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | Especifica que los datos deben decodificarse con  **Italian Post 25**  especificación de código de barras |
| [ITF_14](#ITF-14) | Especifica que los datos deben decodificarse con  **ITF14**  especificación de código de barras |
| [ITF_6](#ITF-6) | Especifica que los datos deben decodificarse con  **ITF6**  especificación de código de barras |
| [MACRO_PDF_417](#MACRO-PDF-417) | Especifica que los datos deben decodificarse con  **MacroPdf417**  especificación de código de barras |
| [MAILMARK](#MAILMARK) | Especifica que los datos deben decodificarse con la especificación de código de barras **Royal Mail Mailmark**. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | Especifica que los datos deben decodificarse con la especificación de código de barras **Matrix 2 of 5** |
| [MAXI_CODE](#MAXI-CODE) | Especifica que los datos deben decodificarse con la especificación de código de barras **MaxiCode** |
| [MICRO_PDF_417](#MICRO-PDF-417) | Especifica que los datos deben decodificarse con la especificación de código de barras **MicroPdf417** |
| [MICRO_QR](#MICRO-QR) | Especifica que los datos deben decodificarse con la especificación de código de barras **MicroQR Code** |
| [MICR_E_13_B](#MICR-E-13-B) | Especifica que los datos deben decodificarse con la especificación de código de barras **MICR E-13B** |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | Especifica que los datos se comprobarán con las simbologías más utilizadas |
| [MSI](#MSI) | Especifica que los datos deben decodificarse con la especificación de código de barras **MSI Plessey** |
| [NONE](#NONE) | Tipo de decodificación no especificado. |
| [ONE_CODE](#ONE-CODE) | Especifica que los datos deben decodificarse con la especificación de código de barras USPS **OneCode** |
| [OPC](#OPC) | Especifica que los datos deben decodificarse con la especificación de código de barras **OPC** |
| [PATCH_CODE](#PATCH-CODE) | Especifica que los datos deben decodificarse con la especificación de código de barras **Patch code**. |
| [PDF_417](#PDF-417) | Especifica que los datos deben decodificarse con la simbología de código de barras **Pdf417** |
| [PHARMACODE](#PHARMACODE) | Especifica que los datos deben decodificarse con el código de barras **Pharmacode**. |
| [PLANET](#PLANET) | Especifica que los datos deben decodificarse con la especificación de código de barras **Planet** |
| [POSTAL_TYPES](#POSTAL-TYPES) | Especifica que los datos se comprobarán con todas las simbologías de código de barras **1.5D POSTAL**, como **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | Especifica que los datos deben decodificarse con la especificación de código de barras **Postnet** |
| [PZN](#PZN) | Especifica que los datos deben decodificarse con la especificación de código de barras **PZN**. |
| [QR](#QR) | Especifica que los datos deben decodificarse con la especificación de código de barras **QR Code** |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | Especifica que los datos deben decodificarse con la especificación de código de barras **RectMicroQR (rMQR) Code** |
| [RM_4_SCC](#RM-4-SCC) | Especifica que los datos deben decodificarse con la especificación de código de barras **RM4SCC**. |
| [SCC_14](#SCC-14) | Especifica que los datos deben decodificarse con la especificación de código de barras **SCC14** |
| [SSCC_18](#SSCC-18) | Especifica que los datos deben decodificarse con la especificación de código de barras **SSCC18** |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | Especifica que los datos deben decodificarse con la especificación de código de barras **Standard 2 of 5** |
| [SUPPLEMENT](#SUPPLEMENT) | Especifica que los datos deben decodificarse con la especificación de código de barras **Supplement(EAN2, EAN5)** |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | Especifica que los datos deben decodificarse con la especificación de código de barras **Swiss Post Parcel Barcode** |
| [TYPES_1D](#TYPES-1D) | Especifica que los datos se comprobarán con todas las simbologías de códigos de barras **1D** |
| [TYPES_2D](#TYPES-2D) | Especifica que los datos se comprobarán con todas las simbologías de códigos de barras **2D** |
| [UPCA](#UPCA) | Especifica que los datos deben decodificarse con la especificación de código de barras **UPC-A** |
| [UPCE](#UPCE) | Especifica que los datos deben decodificarse con la especificación de código de barras **UPC-E** |
| [VIN](#VIN) | Especifica que los datos deben decodificarse con la especificación de código de barras **VIN** (Número de Identificación del Vehículo) |
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | Obtiene una matriz que representa AllSupportedTypes |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Recupera una matriz con los nombres de los tipos de decodificación. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Determina si el BaseDecodeType especificado contiene alguna simbología de código de barras 1D |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Determina si el BaseDecodeType especificado contiene alguna simbología de código de barras 2D |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Determina si el BaseDecodeType especificado contiene alguna simbología de código de barras Postal |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | Convierte la representación en cadena de un SingleDecodeType a su instancia. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | Convierte la representación en cadena de un SingleDecodeType a su instancia. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Especifique los conjuntos de escaneo por barcodeTypes |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Convierte la representación en cadena de un MultiDecodeType a su instancia. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Convierte la representación en cadena de un SingleDecodeType a su instancia. |
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


Especifica que los datos se comprobarán con todas las simbologías disponibles

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


Especifica que los datos deben decodificarse con  **Australian Post Domestic eParcel Barcode**  barcode specification

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


Especifica que los datos deben decodificarse con  **Australia Post**  barcode specification

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


Especifica que los datos deben decodificarse con  **Aztec**  barcode specification

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


Especifica que los datos deben decodificarse con  **CODABAR**  barcode specification

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


Especifica que los datos deben decodificarse con  **CodablockF**  barcode specification

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


Especifica que los datos deben decodificarse con  **CODE 11**  barcode specification

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


Especifica que los datos deben decodificarse con  **CODE 128**  especificación de código de barras

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


Especifica que los datos deben decodificarse con  **SCode16K**  especificación de código de barras

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


Especifica que los datos deben decodificarse con  **Code32**  especificación de código de barras

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


Especifica que los datos deben decodificarse con  **Code 39**  especificación básica de conjunto de caracteres de código de barras: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


Especifica que los datos deben decodificarse con  **Code 39**  especificación completa de conjunto de caracteres ASCII de código de barras: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


Especifica que los datos deben decodificarse con  **CODE 93**  especificación de código de barras

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


Especifica que los datos deben decodificarse con  **CompactPdf417**  (Pdf417Truncated) especificación de código de barras

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


Especifica que los datos deben decodificarse con  **GS1 DATABAR expanded**  especificación de código de barras

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


Especifica que los datos deben decodificarse con  **GS1 DATABAR expanded stacked**  especificación de código de barras

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


Especifica que los datos deben decodificarse con  **GS1 DATABAR limited**  especificación de código de barras

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


Especifica que los datos deben decodificarse con  **GS1 DATABAR omni-directional**  especificación de código de barras

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


Especifica que los datos deben decodificarse con  **GS1 DATABAR stacked**  especificación de código de barras

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


Especifica que los datos deben decodificarse con  **GS1 DATABAR stacked omni-directional**  especificación de código de barras

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


Especifica que los datos deben decodificarse con  **GS1 DATABAR truncated**  especificación de código de barras

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


Especifica que los datos deben decodificarse con  **DataLogic 2 of 5**  especificación de código de barras

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


Especifica que los datos deben decodificarse con  **DataMatrix**  simbología de código de barras

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


Especifica que los datos deben decodificarse con  **DeutschePost Ident code**  especificación de código de barras

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


Especifica que los datos deben decodificarse con  **DeutschePost Leit code**  especificación de código de barras

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


Especifica que los datos deben decodificarse con  **DotCode**  especificación de código de barras

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


Especifica que los datos deben decodificarse con  **DotCode**  especificación de código de barras

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


Especifica que los datos deben decodificarse con  **EAN-13**  especificación de código de barras

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


Especifica que los datos deben decodificarse con  **EAN14**  especificación de código de barras

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


Especifica que los datos deben decodificarse con  **EAN-8**  especificación de código de barras

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


Especifica que los datos deben decodificarse con  **GS1 Aztec**  especificación de código de barras

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


Especifica que los datos deben decodificarse con  **GS1 CODE 128**  especificación de código de barras

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


Especifica que los datos deben decodificarse con  **GS1 Composite Bar**  especificación de código de barras

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


Especifica que los datos deben decodificarse con  **GS1DataMatrix**  simbología de código de barras

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


Especifica que los datos deben decodificarse con  **GS1 DotCode**  especificación de código de barras

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


Especifica que los datos deben decodificarse con **GS1 Han Xin Code** especificación de código de barras

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


Especifica que los datos deben decodificarse con **MicroPdf417** especificación de código de barras

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


Especifica que los datos deben decodificarse con  **GS1 QR**  especificación de código de barras

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


Especifica que los datos deben decodificarse con **Han Xin Code** especificación de código de barras

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


Especifica que los datos deben decodificarse con  **HIBC LIC QR**  especificación de código de barras

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


Especifica que los datos deben decodificarse con  **HIBC PAS QR**  especificación de código de barras

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


Especifica que los datos deben decodificarse con  **HIBC LIC Aztec**  especificación de código de barras

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


Especifica que los datos deben decodificarse con  **HIBC PAS Aztec**  especificación de código de barras

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


Especifica que los datos deben decodificarse con  **HIBC LIC Code128**  especificación de código de barras

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


Especifica que los datos deben decodificarse con  **HIBC PAS Code128**  especificación de código de barras

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


Especifica que los datos deben decodificarse con  **HIBC LIC Code39**  especificación de código de barras

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


Especifica que los datos deben decodificarse con  **HIBC PAS Code39**  especificación de código de barras

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


Especifica que los datos deben decodificarse con  **HIBC LIC DataMatrix**  especificación de código de barras

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


Especifica que los datos deben decodificarse con  **HIBC PAS DataMatrix**  especificación de código de barras

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


Especifica que los datos deben decodificarse con la especificación de código de barras **IATA 2 of 5**. IATA (International Air Transport Association) utiliza este código de barras para la gestión de carga aérea.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


Especifica que los datos deben decodificarse con  **INTERLEAVED 2 of 5**  especificación de código de barras

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


Especifica que los datos deben decodificarse con  **ISBN**  especificación de código de barras

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


Especifica que los datos deben decodificarse con  **ISMN**  especificación de código de barras

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


Especifica que los datos deben decodificarse con  **ISSN**  especificación de código de barras

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


Especifica que los datos deben decodificarse con  **Italian Post 25**  especificación de código de barras

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


Especifica que los datos deben decodificarse con  **ITF14**  especificación de código de barras

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


Especifica que los datos deben decodificarse con  **ITF6**  especificación de código de barras

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


Especifica que los datos deben decodificarse con  **MacroPdf417**  especificación de código de barras

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


Especifica que los datos deben decodificarse con la especificación de código de barras **Royal Mail Mailmark**.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


Especifica que los datos deben decodificarse con la especificación de código de barras **Matrix 2 of 5**

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


Especifica que los datos deben decodificarse con la especificación de código de barras **MaxiCode**

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


Especifica que los datos deben decodificarse con la especificación de código de barras **MicroPdf417**

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


Especifica que los datos deben decodificarse con la especificación de código de barras **MicroQR Code**

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


Especifica que los datos deben decodificarse con la especificación de código de barras **MICR E-13B**

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


Especifica que los datos se comprobarán con las simbologías más utilizadas

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


Especifica que los datos deben decodificarse con la especificación de código de barras **MSI Plessey**

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


Tipo de decodificación no especificado.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


Especifica que los datos deben decodificarse con la especificación de código de barras USPS **OneCode**

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


Especifica que los datos deben decodificarse con la especificación de código de barras **OPC**

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


Especifica que los datos deben decodificarse con la especificación de código de barras **Patch code**. La simbología de códigos de barras se utiliza para escaneo automatizado.

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


Especifica que los datos deben decodificarse con la simbología de código de barras **Pdf417**

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


Especifica que los datos deben decodificarse con el código de barras **Pharmacode**. Esta simbología también se conoce como Pharmaceutical BINARY Code

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


Especifica que los datos deben decodificarse con la especificación de código de barras **Planet**

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


Especifica que los datos se comprobarán con todas las simbologías de código de barras **1.5D POSTAL**, como **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


Especifica que los datos deben decodificarse con la especificación de código de barras **Postnet**

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


Especifica que los datos deben decodificarse con la especificación de código de barras **PZN**. Esta simbología también se conoce como Pharma Zentral Nummer. Se admiten PZN7 y PZN8.

### QR {#QR}
```
public static final SingleDecodeType QR
```


Especifica que los datos deben decodificarse con la especificación de código de barras **QR Code**

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


Especifica que los datos deben decodificarse con la especificación de código de barras **RectMicroQR (rMQR) Code**

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


Especifica que los datos deben decodificarse con la especificación de código de barras **RM4SCC**. RM4SCC (Royal Mail 4-state Customer Code) se utiliza para el proceso automatizado de clasificación de correo en el Reino Unido.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


Especifica que los datos deben decodificarse con la especificación de código de barras **SCC14**

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


Especifica que los datos deben decodificarse con la especificación de código de barras **SSCC18**

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


Especifica que los datos deben decodificarse con la especificación de código de barras **Standard 2 of 5**

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


Especifica que los datos deben decodificarse con la especificación de código de barras **Supplement(EAN2, EAN5)**

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


Especifica que los datos deben decodificarse con la especificación de código de barras **Swiss Post Parcel Barcode**

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


Especifica que los datos se comprobarán con todas las simbologías de códigos de barras **1D**

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


Especifica que los datos se comprobarán con todas las simbologías de códigos de barras **2D**

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


Especifica que los datos deben decodificarse con la especificación de código de barras **UPC-A**

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


Especifica que los datos deben decodificarse con la especificación de código de barras **UPC-E**

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


Especifica que los datos deben decodificarse con la especificación de código de barras **VIN** (Número de Identificación del Vehículo)

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


Obtiene una matriz que representa AllSupportedTypes

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


Recupera una matriz con los nombres de los tipos de decodificación.

**Returns:**
java.lang.String[] - Una matriz de cadenas con los nombres de los tipos de decodificación.
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


Determina si el BaseDecodeType especificado contiene alguna simbología de código de barras 1D

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | El BaseDecodeType a probar. |

**Returns:**
boolean - Devuelve **true** si BaseDecodeType contiene alguna simbología de código de barras 1D; de lo contrario, devuelve **false**.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


Determina si el BaseDecodeType especificado contiene alguna simbología de código de barras 2D

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | El BaseDecodeType a probar. |

**Returns:**
boolean - Devuelve **true** si BaseDecodeTypeddddddddw contiene alguna simbología de código de barras 2D; de lo contrario, devuelve **false**.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


Determina si el BaseDecodeType especificado contiene alguna simbología de código de barras Postal

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | El BaseDecodeType a probar |

**Returns:**
boolean - Devuelve **true** si BaseDecodeType contiene alguna simbología de código de barras Postal; de lo contrario, devuelve **false**.
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


Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena que contiene una representación SingleDecodeType para convertir. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

de lo contrario devuelve un tipo indefinido. o SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena que contiene un SingleDecodeType en el formato "EAN8" o "EAN13" o "CodaBar"... para convertir. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - **true** si s se convirtió correctamente; de lo contrario, **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


Especifique los conjuntos de escaneo por barcodeTypes

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Matriz de tipos de decodificación simples y múltiples |

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


Convierte la representación en cadena de un MultiDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena con el formato "AllSupportedTypes" o "EAN8,EAN13,CodaBar" para convertir. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Se devuelve un MultiDecodeType real cuando la conversión se ha completado correctamente; de lo contrario devuelve un tipo indefinido: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| parsingType | java.lang.String | Una cadena que contiene un SingleDecodeType en el formato "EAN8" o "EAN13" o "CodaBar"... para convertir. |

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

