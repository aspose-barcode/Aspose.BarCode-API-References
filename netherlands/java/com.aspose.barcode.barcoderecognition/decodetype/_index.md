---
title: "DecodeType"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Geef het type barcode op dat gelezen moet worden."
type: docs
weight: 30
url: /nl/java/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

Geef het type barcode op dat gelezen moet worden.

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

| Constructor | Beschrijving |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | Specificeert dat gegevens worden gecontroleerd met alle beschikbare symbolen. |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Australian Post Domestic eParcel Barcode** barcode-specificatie |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | Specificeert dat de gegevens moeten worden gedecodeerd met  **Australia Post**  barcode-specificatie |
| [AZTEC](#AZTEC) | Specificeert dat de gegevens moeten worden gedecodeerd met  **Aztec**  barcode-specificatie |
| [CODABAR](#CODABAR) | Specificeert dat de gegevens moeten worden gedecodeerd met  **CODABAR**  barcode-specificatie |
| [CODABLOCK_F](#CODABLOCK-F) | Specificeert dat de gegevens moeten worden gedecodeerd met  **CodablockF**  barcode-specificatie |
| [CODE_11](#CODE-11) | Specificeert dat de gegevens moeten worden gedecodeerd met  **CODE 11**  barcode-specificatie |
| [CODE_128](#CODE-128) | Specificeert dat de gegevens moeten worden gedecodeerd met  **CODE 128**  barcode-specificatie |
| [CODE_16_K](#CODE-16-K) | Specificeert dat de gegevens moeten worden gedecodeerd met  **SCode16K**  barcode-specificatie |
| [CODE_32](#CODE-32) | Specificeert dat de gegevens moeten worden gedecodeerd met  **Code32**  barcode-specificatie |
| [CODE_39](#CODE-39) | Specificeert dat de gegevens moeten worden gedecodeerd met  **Code 39**  basistekenset barcode-specificatie: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | Specificeert dat de gegevens moeten worden gedecodeerd met  **Code 39**  volledige ASCII-tekenset barcode-specificatie: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | Specificeert dat de gegevens moeten worden gedecodeerd met  **CODE 93**  barcode-specificatie |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | Specificeert dat de gegevens moeten worden gedecodeerd met  **CompactPdf417**  (Pdf417Truncated) barcode-specificatie |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR expanded**  barcode-specificatie |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR expanded stacked**  barcode-specificatie |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR limited**  barcode-specificatie |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR omni-directional**  barcode-specificatie |
| [DATABAR_STACKED](#DATABAR-STACKED) | Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR stacked**  barcode-specificatie |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR stacked omni-directional**  barcode-specificatie |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR truncated**  barcode-specificatie |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | Specificeert dat de gegevens moeten worden gedecodeerd met  **DataLogic 2 of 5**  barcode-specificatie |
| [DATA_MATRIX](#DATA-MATRIX) | Specificeert dat de gegevens moeten worden gedecodeerd met  **DataMatrix**  barcode-symbool |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | Specificeert dat de gegevens moeten worden gedecodeerd met  **DeutschePost Ident code**  barcode-specificatie |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | Specificeert dat de gegevens moeten worden gedecodeerd met  **DeutschePost Leit code**  barcode-specificatie |
| [DOT_CODE](#DOT-CODE) | Specificeert dat de gegevens moeten worden gedecodeerd met  **DotCode**  barcode-specificatie |
| [DUTCH_KIX](#DUTCH-KIX) | Specificeert dat de gegevens moeten worden gedecodeerd met  **DotCode**  barcode-specificatie |
| [EAN_13](#EAN-13) | Specificeert dat de gegevens moeten worden gedecodeerd met  **EAN-13**  barcode-specificatie |
| [EAN_14](#EAN-14) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **EAN14**  barcode-specificatie |
| [EAN_8](#EAN-8) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **EAN-8**  barcode-specificatie |
| [GS_1_AZTEC](#GS-1-AZTEC) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1 Aztec**  barcode-specificatie |
| [GS_1_CODE_128](#GS-1-CODE-128) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1 CODE 128**  barcode-specificatie |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1 Composite Bar**  barcode-specificatie |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1DataMatrix**  barcode-symbologie |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1 DotCode**  barcode-specificatie |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | Geeft aan dat de gegevens moeten worden gedecodeerd met **GS1 Han Xin Code** barcode-specificatie |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | Geeft aan dat de gegevens moeten worden gedecodeerd met **MicroPdf417** barcode-specificatie |
| [GS_1_QR](#GS-1-QR) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1 QR**  barcode-specificatie |
| [HAN_XIN](#HAN-XIN) | Geeft aan dat de gegevens moeten worden gedecodeerd met **Han Xin Code** barcode-specificatie |
| [HIBCQRLIC](#HIBCQRLIC) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC LIC QR**  barcode-specificatie |
| [HIBCQRPAS](#HIBCQRPAS) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC PAS QR**  barcode-specificatie |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC LIC Aztec**  barcode-specificatie |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC PAS Aztec**  barcode-specificatie |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC LIC Code128**  barcode-specificatie |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC PAS Code128**  barcode-specificatie |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC LIC Code39**  barcode-specificatie |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC PAS Code39**  barcode-specificatie |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC LIC DataMatrix**  barcode-specificatie |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC PAS DataMatrix**  barcode-specificatie |
| [IATA_2_OF_5](#IATA-2-OF-5) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **IATA 2 of 5**  barcode-specificatie. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **INTERLEAVED 2 of 5**  barcode-specificatie |
| [ISBN](#ISBN) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **ISBN**  barcode-specificatie |
| [ISMN](#ISMN) | Geeft aan dat de gegevens moeten worden gedecodeerd met  **ISMN**  barcode-specificatie |
| [ISSN](#ISSN) | Specificeert dat de data moet worden gedecodeerd met de **ISSN** barcode-specificatie |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | Specificeert dat de data moet worden gedecodeerd met de **Italian Post 25** barcode-specificatie |
| [ITF_14](#ITF-14) | Specificeert dat de data moet worden gedecodeerd met de **ITF14** barcode-specificatie |
| [ITF_6](#ITF-6) | Specificeert dat de data moet worden gedecodeerd met de **ITF6** barcode-specificatie |
| [MACRO_PDF_417](#MACRO-PDF-417) | Specificeert dat de data moet worden gedecodeerd met de **MacroPdf417** barcode-specificatie |
| [MAILMARK](#MAILMARK) | Specificeert dat de data moet worden gedecodeerd met de **Royal Mail Mailmark** barcode-specificatie. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | Specificeert dat de data moet worden gedecodeerd met de **Matrix 2 of 5** barcode-specificatie |
| [MAXI_CODE](#MAXI-CODE) | Specificeert dat de data moet worden gedecodeerd met de **MaxiCode** barcode-specificatie |
| [MICRO_PDF_417](#MICRO-PDF-417) | Specificeert dat de data moet worden gedecodeerd met de **MicroPdf417** barcode-specificatie |
| [MICRO_QR](#MICRO-QR) | Specificeert dat de data moet worden gedecodeerd met de **MicroQR Code** barcode-specificatie |
| [MICR_E_13_B](#MICR-E-13-B) | Specificeert dat de data moet worden gedecodeerd met de **MICR E-13B** barcode-specificatie |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | Specificeert dat de data zal worden gecontroleerd met de meest gebruikte symbolen |
| [MSI](#MSI) | Specificeert dat de data moet worden gedecodeerd met de **MSI Plessey** barcode-specificatie |
| [NONE](#NONE) | Niet-gespecificeerd decodeertype. |
| [ONE_CODE](#ONE-CODE) | Specificeert dat de data moet worden gedecodeerd met de USPS **OneCode** barcode-specificatie |
| [OPC](#OPC) | Specificeert dat de data moet worden gedecodeerd met de **OPC** barcode-specificatie |
| [PATCH_CODE](#PATCH-CODE) | Specificeert dat de data moet worden gedecodeerd met de **Patch code** barcode-specificatie. |
| [PDF_417](#PDF-417) | Specificeert dat de data moet worden gedecodeerd met de **Pdf417** barcode-symbool |
| [PHARMACODE](#PHARMACODE) | Specificeert dat de data moet worden gedecodeerd met de **Pharmacode** barcode. |
| [PLANET](#PLANET) | Specificeert dat de data moet worden gedecodeerd met de **Planet** barcode-specificatie |
| [POSTAL_TYPES](#POSTAL-TYPES) | Specificeert dat de data zal worden gecontroleerd met alle **1.5D POSTAL** barcode-symbolen, zoals **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | Specificeert dat de data moet worden gedecodeerd met de **Postnet** barcode-specificatie |
| [PZN](#PZN) | Specificeert dat de data moet worden gedecodeerd met de **PZN** barcode-specificatie. |
| [QR](#QR) | Specificeert dat de data moet worden gedecodeerd met de **QR Code** barcode-specificatie |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | Specificeert dat de data moet worden gedecodeerd met de **RectMicroQR (rMQR) Code** barcode-specificatie |
| [RM_4_SCC](#RM-4-SCC) | Specificeert dat de gegevens moeten worden gedecodeerd met de **RM4SCC** barcode-specificatie. |
| [SCC_14](#SCC-14) | Specificeert dat de gegevens moeten worden gedecodeerd met de **SCC14** barcode-specificatie |
| [SSCC_18](#SSCC-18) | Specificeert dat de gegevens moeten worden gedecodeerd met de **SSCC18** barcode-specificatie |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Standard 2 of 5** barcode-specificatie |
| [SUPPLEMENT](#SUPPLEMENT) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Supplement(EAN2, EAN5)** barcode-specificatie |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | Specificeert dat de gegevens moeten worden gedecodeerd met de **Swiss Post Parcel Barcode** barcode-specificatie |
| [TYPES_1D](#TYPES-1D) | Specificeert dat gegevens worden gecontroleerd met alle **1D** barcode-symbologieën |
| [TYPES_2D](#TYPES-2D) | Specificeert dat gegevens worden gecontroleerd met alle **2D** barcode-symbologieën |
| [UPCA](#UPCA) | Specificeert dat de gegevens moeten worden gedecodeerd met de **UPC-A** barcode-specificatie. |
| [UPCE](#UPCE) | Specificeert dat de gegevens moeten worden gedecodeerd met de **UPC-E** barcode-specificatie. |
| [VIN](#VIN) | Specificeert dat de gegevens moeten worden gedecodeerd met de **VIN** (Vehicle Identification Number) barcode-specificatie. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | Haalt een array op die AllSupportedTypes vertegenwoordigt. |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Haalt een array op met de namen van de decodeertypen. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Bepaalt of het opgegeven BaseDecodeType enige 1D barcode-symbologie bevat |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Bepaalt of het opgegeven BaseDecodeType enige 2D barcode-symbologie bevat |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Bepaalt of het opgegeven BaseDecodeType enige postbarcode-symbologie bevat |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | Converteert de tekenreeksrepresentatie van een SingleDecodeType naar de bijbehorende instantie. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | Converteert de tekenreeksrepresentatie van een SingleDecodeType naar de bijbehorende instantie. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Specificeer scansets op barcodeTypes |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Converteert de tekenreeksrepresentatie van een MultiDecodeType naar de bijbehorende instantie. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Converteert de tekenreeksrepresentatie van een SingleDecodeType naar de bijbehorende instantie. |
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


Specificeert dat gegevens worden gecontroleerd met alle beschikbare symbolen.

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **Australian Post Domestic eParcel Barcode** barcode-specificatie

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **Australia Post**  barcode-specificatie

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **Aztec**  barcode-specificatie

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **CODABAR**  barcode-specificatie

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **CodablockF**  barcode-specificatie

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **CODE 11**  barcode-specificatie

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **CODE 128**  barcode-specificatie

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **SCode16K**  barcode-specificatie

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **Code32**  barcode-specificatie

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **Code 39**  basistekenset barcode-specificatie: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **Code 39**  volledige ASCII-tekenset barcode-specificatie: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **CODE 93**  barcode-specificatie

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **CompactPdf417**  (Pdf417Truncated) barcode-specificatie

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR expanded**  barcode-specificatie

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR expanded stacked**  barcode-specificatie

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR limited**  barcode-specificatie

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR omni-directional**  barcode-specificatie

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR stacked**  barcode-specificatie

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR stacked omni-directional**  barcode-specificatie

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **GS1 DATABAR truncated**  barcode-specificatie

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **DataLogic 2 of 5**  barcode-specificatie

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **DataMatrix**  barcode-symbool

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **DeutschePost Ident code**  barcode-specificatie

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **DeutschePost Leit code**  barcode-specificatie

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **DotCode**  barcode-specificatie

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **DotCode**  barcode-specificatie

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


Specificeert dat de gegevens moeten worden gedecodeerd met  **EAN-13**  barcode-specificatie

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **EAN14**  barcode-specificatie

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **EAN-8**  barcode-specificatie

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1 Aztec**  barcode-specificatie

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1 CODE 128**  barcode-specificatie

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1 Composite Bar**  barcode-specificatie

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1DataMatrix**  barcode-symbologie

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1 DotCode**  barcode-specificatie

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


Geeft aan dat de gegevens moeten worden gedecodeerd met **GS1 Han Xin Code** barcode-specificatie

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


Geeft aan dat de gegevens moeten worden gedecodeerd met **MicroPdf417** barcode-specificatie

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **GS1 QR**  barcode-specificatie

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


Geeft aan dat de gegevens moeten worden gedecodeerd met **Han Xin Code** barcode-specificatie

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC LIC QR**  barcode-specificatie

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC PAS QR**  barcode-specificatie

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC LIC Aztec**  barcode-specificatie

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC PAS Aztec**  barcode-specificatie

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC LIC Code128**  barcode-specificatie

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC PAS Code128**  barcode-specificatie

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC LIC Code39**  barcode-specificatie

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC PAS Code39**  barcode-specificatie

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC LIC DataMatrix**  barcode-specificatie

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **HIBC PAS DataMatrix**  barcode-specificatie

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **IATA 2 of 5** barcode-specificatie. IATA (International Air Transport Association) gebruikt deze barcode voor het beheer van luchtvracht.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **INTERLEAVED 2 of 5**  barcode-specificatie

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **ISBN**  barcode-specificatie

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


Geeft aan dat de gegevens moeten worden gedecodeerd met  **ISMN**  barcode-specificatie

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


Specificeert dat de data moet worden gedecodeerd met de **ISSN** barcode-specificatie

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


Specificeert dat de data moet worden gedecodeerd met de **Italian Post 25** barcode-specificatie

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


Specificeert dat de data moet worden gedecodeerd met de **ITF14** barcode-specificatie

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


Specificeert dat de data moet worden gedecodeerd met de **ITF6** barcode-specificatie

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


Specificeert dat de data moet worden gedecodeerd met de **MacroPdf417** barcode-specificatie

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


Specificeert dat de data moet worden gedecodeerd met de **Royal Mail Mailmark** barcode-specificatie.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


Specificeert dat de data moet worden gedecodeerd met de **Matrix 2 of 5** barcode-specificatie

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


Specificeert dat de data moet worden gedecodeerd met de **MaxiCode** barcode-specificatie

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


Specificeert dat de data moet worden gedecodeerd met de **MicroPdf417** barcode-specificatie

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


Specificeert dat de data moet worden gedecodeerd met de **MicroQR Code** barcode-specificatie

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


Specificeert dat de data moet worden gedecodeerd met de **MICR E-13B** barcode-specificatie

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


Specificeert dat de data zal worden gecontroleerd met de meest gebruikte symbolen

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


Specificeert dat de data moet worden gedecodeerd met de **MSI Plessey** barcode-specificatie

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


Niet-gespecificeerd decodeertype.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


Specificeert dat de data moet worden gedecodeerd met de USPS **OneCode** barcode-specificatie

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


Specificeert dat de data moet worden gedecodeerd met de **OPC** barcode-specificatie

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **Patch code** barcode-specificatie. Barcode-symbologie wordt gebruikt voor geautomatiseerde scanning.

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


Specificeert dat de data moet worden gedecodeerd met de **Pdf417** barcode-symbool

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **Pharmacode** barcode. Deze symbologie staat ook bekend als Pharmaceutical BINARY Code.

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


Specificeert dat de data moet worden gedecodeerd met de **Planet** barcode-specificatie

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


Specificeert dat de data zal worden gecontroleerd met alle **1.5D POSTAL** barcode-symbolen, zoals **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


Specificeert dat de data moet worden gedecodeerd met de **Postnet** barcode-specificatie

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **PZN** barcode-specificatie. Deze symbologie staat ook bekend als Pharma Zentral Nummer. PZN7 en PZN8 worden ondersteund.

### QR {#QR}
```
public static final SingleDecodeType QR
```


Specificeert dat de data moet worden gedecodeerd met de **QR Code** barcode-specificatie

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


Specificeert dat de data moet worden gedecodeerd met de **RectMicroQR (rMQR) Code** barcode-specificatie

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **RM4SCC** barcode-specificatie. RM4SCC (Royal Mail 4-state Customer Code) wordt gebruikt voor geautomatiseerde postsortering in het VK.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **SCC14** barcode-specificatie

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **SSCC18** barcode-specificatie

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **Standard 2 of 5** barcode-specificatie

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **Supplement(EAN2, EAN5)** barcode-specificatie

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **Swiss Post Parcel Barcode** barcode-specificatie

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


Specificeert dat gegevens worden gecontroleerd met alle **1D** barcode-symbologieën

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


Specificeert dat gegevens worden gecontroleerd met alle **2D** barcode-symbologieën

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **UPC-A** barcode-specificatie.

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **UPC-E** barcode-specificatie.

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


Specificeert dat de gegevens moeten worden gedecodeerd met de **VIN** (Vehicle Identification Number) barcode-specificatie.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


Haalt een array op die AllSupportedTypes vertegenwoordigt.

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


Haalt een array op met de namen van de decodeertypen.

**Returns:**
java.lang.String[] - Een stringarray met de namen van de decodeertypen.
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


Bepaalt of het opgegeven BaseDecodeType enige 1D barcode-symbologie bevat

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Het BaseDecodeType om te testen. |

**Returns:**
boolean - Retourneert **true** als BaseDecodeType een 1D barcode-symbool bevat; anders retourneert het **false**.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


Bepaalt of het opgegeven BaseDecodeType enige 2D barcode-symbologie bevat

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Het BaseDecodeType om te testen. |

**Returns:**
boolean - Retourneert **true** als BaseDecodeTypeddddddddw een 2D barcode-symbool bevat; anders retourneert het **false**.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


Bepaalt of het opgegeven BaseDecodeType enige postbarcode-symbologie bevat

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | De BaseDecodeType om te testen |

**Returns:**
boolean - Retourneert **true** als BaseDecodeType een postbarcode-symbool bevat; anders retourneert het **false**.
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


Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string die een SingleDecodeType-representatie bevat om te converteren. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

anders retourneert het een onbepaald type. of SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string die een SingleDecodeType bevat in het formaat \"EAN8\" of \"EAN13\" of \"CodaBar\"... om te converteren. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - **true** als s succesvol is geconverteerd; anders, **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


Specificeer scansets op barcodeTypes

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array van enkele en meerdere decode types |

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


Converteert de tekenreeksrepresentatie van een MultiDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string in het formaat "AllSupportedTypes" of "EAN8,EAN13,CodaBar" om te converteren. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully; otherwise it returns indefinite type: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | java.lang.String | Een string die een SingleDecodeType bevat in het formaat \"EAN8\" of \"EAN13\" of \"CodaBar\"... om te converteren. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

