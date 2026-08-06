---
title: DecodeType
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Spécifiez le type de code‑barres à lire.
type: docs
weight: 32
url: /fr/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

Spécifiez le type de code‑barres à lire.

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
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | Spécifie que les données seront vérifiées avec toutes les symbologies disponibles |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | Spécifie que les données doivent être décodées avec  **Australian Post Domestic eParcel Barcode**  spécification de code-barres |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | Spécifie que les données doivent être décodées avec  **Australia Post**  spécification de code-barres |
| [AZTEC](#AZTEC) | Spécifie que les données doivent être décodées avec  **Aztec**  spécification de code-barres |
| [CODABAR](#CODABAR) | Spécifie que les données doivent être décodées avec  **CODABAR**  spécification de code-barres |
| [CODABLOCK_F](#CODABLOCK-F) | Spécifie que les données doivent être décodées avec  **CodablockF**  spécification de code-barres |
| [CODE_11](#CODE-11) | Spécifie que les données doivent être décodées avec  **CODE 11**  spécification de code-barres |
| [CODE_128](#CODE-128) | Spécifie que les données doivent être décodées avec la spécification de code-barres **CODE 128** |
| [CODE_16_K](#CODE-16-K) | Spécifie que les données doivent être décodées avec la spécification de code-barres **SCode16K** |
| [CODE_32](#CODE-32) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Code32** |
| [CODE_39](#CODE-39) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Code 39** jeu de caractères de base : ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Code 39** jeu de caractères ASCII complet : ISO/IEC 16388 |
| [CODE_93](#CODE-93) | Spécifie que les données doivent être décodées avec la spécification de code-barres **CODE 93** |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | Spécifie que les données doivent être décodées avec la spécification de code-barres **CompactPdf417** (Pdf417Truncated) |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR expanded** |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR expanded stacked** |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR limited** |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR omni-directional** |
| [DATABAR_STACKED](#DATABAR-STACKED) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR stacked** |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR stacked omni-directional** |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR truncated** |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | Spécifie que les données doivent être décodées avec la spécification de code-barres **DataLogic 2 of 5** |
| [DATA_MATRIX](#DATA-MATRIX) | Spécifie que les données doivent être décodées avec la symbologie de code-barres **DataMatrix** |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | Spécifie que les données doivent être décodées avec la spécification de code-barres **DeutschePost Ident code** |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | Spécifie que les données doivent être décodées avec la spécification de code-barres **DeutschePost Leit code** |
| [DOT_CODE](#DOT-CODE) | Spécifie que les données doivent être décodées avec la spécification de code-barres **DotCode** |
| [DUTCH_KIX](#DUTCH-KIX) | Spécifie que les données doivent être décodées avec la spécification de code-barres **DotCode** |
| [EAN_13](#EAN-13) | Spécifie que les données doivent être décodées avec la spécification de code-barres **EAN-13** |
| [EAN_14](#EAN-14) | Spécifie que les données doivent être décodées avec la spécification de code-barres **EAN14** |
| [EAN_8](#EAN-8) | Spécifie que les données doivent être décodées avec la spécification de code-barres **EAN-8** |
| [GS_1_AZTEC](#GS-1-AZTEC) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Aztec** |
| [GS_1_CODE_128](#GS-1-CODE-128) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 CODE 128** |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Composite Bar** |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | Spécifie que les données doivent être décodées avec la symbologie de code-barres **GS1DataMatrix** |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DotCode** |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Han Xin Code** |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | Spécifie que les données doivent être décodées avec la spécification de code-barres **MicroPdf417** |
| [GS_1_QR](#GS-1-QR) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 QR** |
| [HAN_XIN](#HAN-XIN) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Han Xin Code** |
| [HIBCQRLIC](#HIBCQRLIC) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC QR** |
| [HIBCQRPAS](#HIBCQRPAS) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS QR** |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC Aztec** |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS Aztec** |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC Code128** |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS Code128** |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC Code39** |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS Code39** |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC DataMatrix** |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS DataMatrix** |
| [IATA_2_OF_5](#IATA-2-OF-5) | Spécifie que les données doivent être décodées avec la spécification de code-barres **IATA 2 of 5**. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | Spécifie que les données doivent être décodées avec la spécification de code-barres **INTERLEAVED 2 of 5** |
| [ISBN](#ISBN) | Spécifie que les données doivent être décodées avec la spécification de code-barres **ISBN** |
| [ISMN](#ISMN) | Spécifie que les données doivent être décodées avec la spécification de code-barres **ISMN** |
| [ISSN](#ISSN) | Spécifie que les données doivent être décodées avec la spécification de code-barres **ISSN** |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Italian Post 25** |
| [ITF_14](#ITF-14) | Spécifie que les données doivent être décodées avec la spécification de code-barres **ITF14** |
| [ITF_6](#ITF-6) | Spécifie que les données doivent être décodées avec la spécification de code-barres **ITF6** |
| [MACRO_PDF_417](#MACRO-PDF-417) | Spécifie que les données doivent être décodées avec la spécification de code-barres **MacroPdf417** |
| [MAILMARK](#MAILMARK) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **Royal Mail Mailmark**. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **Matrix 2 of 5** |
| [MAXI_CODE](#MAXI-CODE) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **MaxiCode** |
| [MICRO_PDF_417](#MICRO-PDF-417) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **MicroPdf417** |
| [MICRO_QR](#MICRO-QR) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **MicroQR Code** |
| [MICR_E_13_B](#MICR-E-13-B) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **MICR E-13B** |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | Spécifie que les données seront vérifiées avec les symbologies les plus couramment utilisées |
| [MSI](#MSI) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **MSI Plessey** |
| [NONE](#NONE) | Type de décodage non spécifié. |
| [ONE_CODE](#ONE-CODE) | Spécifie que les données doivent être décodées avec la spécification de code‑barres USPS **OneCode** |
| [OPC](#OPC) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **OPC** |
| [PATCH_CODE](#PATCH-CODE) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **Patch code**. |
| [PDF_417](#PDF-417) | Spécifie que les données doivent être décodées avec la symbologie de code‑barres **Pdf417** |
| [PHARMACODE](#PHARMACODE) | Spécifie que les données doivent être décodées avec le code‑barres **Pharmacode**. |
| [PLANET](#PLANET) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **Planet** |
| [POSTAL_TYPES](#POSTAL-TYPES) | Spécifie que les données seront vérifiées avec toutes les symbologies de code‑barres **1.5D POSTAL**, comme **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **Postnet** |
| [PZN](#PZN) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **PZN**. |
| [QR](#QR) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **QR Code** |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **RectMicroQR (rMQR) Code** |
| [RM_4_SCC](#RM-4-SCC) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **RM4SCC**. |
| [SCC_14](#SCC-14) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **SCC14** |
| [SSCC_18](#SSCC-18) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **SSCC18** |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **Standard 2 of 5** |
| [SUPPLEMENT](#SUPPLEMENT) | Spécifie que les données doivent être décodées avec la spécification de code‑barres **Supplement(EAN2, EAN5)** |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | Spécifie que les données doivent être décodées selon la spécification de code-barres **Swiss Post Parcel Barcode** |
| [TYPES_1D](#TYPES-1D) | Spécifie que les données seront vérifiées avec toutes les symbologies de code-barres **1D** |
| [TYPES_2D](#TYPES-2D) | Spécifie que les données seront vérifiées avec toutes les symbologies de code-barres **2D** |
| [UPCA](#UPCA) | Spécifie que les données doivent être décodées selon la spécification de code-barres **UPC-A** |
| [UPCE](#UPCE) | Spécifie que les données doivent être décodées selon la spécification de code-barres **UPC-E** |
| [VIN](#VIN) | Spécifie que les données doivent être décodées selon la spécification de code-barres **VIN** (numéro d'identification du véhicule) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | Obtient un tableau qui représente AllSupportedTypes |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Récupère un tableau des noms des types de décodage. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Détermine si le BaseDecodeType spécifié contient une quelconque symbologie de code-barres 1D |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Détermine si le BaseDecodeType spécifié contient une quelconque symbologie de code-barres 2D |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Détermine si le BaseDecodeType spécifié contient une quelconque symbologie de code-barres Postal |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | Convertit la représentation chaîne d'un SingleDecodeType en son instance. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | Convertit la représentation chaîne d'un SingleDecodeType en son instance. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Spécifiez les ensembles de numérisation par barcodeTypes |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Convertit la représentation chaîne d'un MultiDecodeType en son instance. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Convertit la représentation chaîne d'un SingleDecodeType en son instance. |
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


Spécifie que les données seront vérifiées avec toutes les symbologies disponibles

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


Spécifie que les données doivent être décodées avec  **Australian Post Domestic eParcel Barcode**  spécification de code-barres

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


Spécifie que les données doivent être décodées avec  **Australia Post**  spécification de code-barres

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


Spécifie que les données doivent être décodées avec  **Aztec**  spécification de code-barres

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


Spécifie que les données doivent être décodées avec  **CODABAR**  spécification de code-barres

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


Spécifie que les données doivent être décodées avec  **CodablockF**  spécification de code-barres

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


Spécifie que les données doivent être décodées avec  **CODE 11**  spécification de code-barres

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **CODE 128**

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **SCode16K**

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **Code32**

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **Code 39** jeu de caractères de base : ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **Code 39** jeu de caractères ASCII complet : ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **CODE 93**

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **CompactPdf417** (Pdf417Truncated)

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR expanded**

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR expanded stacked**

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR limited**

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR omni-directional**

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR stacked**

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR stacked omni-directional**

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DATABAR truncated**

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **DataLogic 2 of 5**

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


Spécifie que les données doivent être décodées avec la symbologie de code-barres **DataMatrix**

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **DeutschePost Ident code**

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **DeutschePost Leit code**

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **DotCode**

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **DotCode**

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **EAN-13**

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **EAN14**

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **EAN-8**

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Aztec**

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 CODE 128**

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Composite Bar**

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


Spécifie que les données doivent être décodées avec la symbologie de code-barres **GS1DataMatrix**

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DotCode**

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Han Xin Code**

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **MicroPdf417**

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 QR**

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **Han Xin Code**

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC QR**

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS QR**

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC Aztec**

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS Aztec**

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC Code128**

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS Code128**

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC Code39**

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS Code39**

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC DataMatrix**

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS DataMatrix**

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


Spécifie que les données doivent être décodées selon la spécification de code-barres **IATA 2 of 5**. IATA (International Air Transport Association) utilise ce code-barres pour la gestion du fret aérien.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **INTERLEAVED 2 of 5**

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **ISBN**

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **ISMN**

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **ISSN**

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **Italian Post 25**

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **ITF14**

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **ITF6**

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


Spécifie que les données doivent être décodées avec la spécification de code-barres **MacroPdf417**

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **Royal Mail Mailmark**.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **Matrix 2 of 5**

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **MaxiCode**

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **MicroPdf417**

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **MicroQR Code**

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **MICR E-13B**

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


Spécifie que les données seront vérifiées avec les symbologies les plus couramment utilisées

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **MSI Plessey**

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


Type de décodage non spécifié.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres USPS **OneCode**

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **OPC**

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


Spécifie que les données doivent être décodées selon la spécification de code-barres **Patch code**. La symbologie de code-barres est utilisée pour le scan automatisé

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


Spécifie que les données doivent être décodées avec la symbologie de code‑barres **Pdf417**

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


Spécifie que les données doivent être décodées avec le code-barres **Pharmacode**. Cette symbologie est également connue sous le nom de Pharmaceutical BINARY Code

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **Planet**

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


Spécifie que les données seront vérifiées avec toutes les symbologies de code‑barres **1.5D POSTAL**, comme **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **Postnet**

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


Spécifie que les données doivent être décodées selon la spécification de code-barres **PZN**. Cette symbologie est également connue sous le nom de Pharma Zentral Nummer. Les PZN7 et PZN8 sont pris en charge.

### QR {#QR}
```
public static final SingleDecodeType QR
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **QR Code**

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **RectMicroQR (rMQR) Code**

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


Spécifie que les données doivent être décodées selon la spécification de code-barres **RM4SCC**. RM4SCC (Royal Mail 4-state Customer Code) est utilisé pour le processus automatisé de tri du courrier au Royaume-Uni.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **SCC14**

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **SSCC18**

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **Standard 2 of 5**

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


Spécifie que les données doivent être décodées avec la spécification de code‑barres **Supplement(EAN2, EAN5)**

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


Spécifie que les données doivent être décodées selon la spécification de code-barres **Swiss Post Parcel Barcode**

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


Spécifie que les données seront vérifiées avec toutes les symbologies de code-barres **1D**

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


Spécifie que les données seront vérifiées avec toutes les symbologies de code-barres **2D**

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


Spécifie que les données doivent être décodées selon la spécification de code-barres **UPC-A**

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


Spécifie que les données doivent être décodées selon la spécification de code-barres **UPC-E**

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


Spécifie que les données doivent être décodées selon la spécification de code-barres **VIN** (numéro d'identification du véhicule)

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


Obtient un tableau qui représente AllSupportedTypes

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


Récupère un tableau des noms des types de décodage.

**Returns:**
java.lang.String[] - Un tableau de chaînes contenant les noms des types de décodage.
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


Détermine si le BaseDecodeType spécifié contient une quelconque symbologie de code-barres 1D

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Le BaseDecodeType à tester. |

**Returns:**
boolean - Retourne **true** si BaseDecodeType contient une quelconque symbologie de code-barres 1D ; sinon, retourne **false**.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


Détermine si le BaseDecodeType spécifié contient une quelconque symbologie de code-barres 2D

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Le BaseDecodeType à tester. |

**Returns:**
boolean - Retourne **true** si BaseDecodeTypeddddddddw contient une quelconque symbologie de code-barres 2D ; sinon, retourne **false**.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


Détermine si le BaseDecodeType spécifié contient une quelconque symbologie de code-barres Postal

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Le BaseDecodeType à tester |

**Returns:**
boolean - Retourne **true** si BaseDecodeType contient une quelconque symbologie de code-barres Postal ; sinon, retourne **false**.
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


Convertit la représentation sous forme de chaîne d'un SingleDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Une chaîne contenant une représentation SingleDecodeType à convertir. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

sinon il renvoie un type indéfini. ou SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


Convertit la représentation sous forme de chaîne d'un SingleDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Une chaîne contenant un SingleDecodeType au format "EAN8" ou "EAN13" ou "CodaBar"... à convertir. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
booléen - **true** si s a été converti avec succès; sinon, **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


Spécifiez les ensembles de numérisation par barcodeTypes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Tableau de types de décodage simples et multiples |

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


Convertit la représentation sous forme de chaîne d'un MultiDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Une chaîne au format "AllSupportedTypes" ou "EAN8,EAN13,CodaBar" à convertir. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Un véritable MultiDecodeType est renvoyé lorsque la conversion s'est terminée avec succès; sinon il renvoie un type indéfini: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Convertit la représentation sous forme de chaîne d'un SingleDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Une chaîne contenant un SingleDecodeType au format "EAN8" ou "EAN13" ou "CodaBar"... à convertir. |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

