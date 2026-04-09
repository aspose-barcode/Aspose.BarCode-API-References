---
title: DecodeType
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Geben Sie den zu lesenden Strichcodetyp an.
type: docs
weight: 32
url: /de/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

Geben Sie den zu lesenden Strichcodetyp an.

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

| Constructor | Beschreibung |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | Gibt an, dass Daten mit allen verfügbaren Symbolen überprüft werden. |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | Gibt an, dass die Daten mit der Barcode-Spezifikation **Australian Post Domestic eParcel Barcode** dekodiert werden sollen. |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | Gibt an, dass die Daten mit der Barcode-Spezifikation **Australia Post** dekodiert werden sollen. |
| [AZTEC](#AZTEC) | Gibt an, dass die Daten mit der Barcode-Spezifikation **Aztec** dekodiert werden sollen. |
| [CODABAR](#CODABAR) | Gibt an, dass die Daten mit der Barcode-Spezifikation **CODABAR** dekodiert werden sollen. |
| [CODABLOCK_F](#CODABLOCK-F) | Gibt an, dass die Daten mit der Barcode-Spezifikation **CodablockF** dekodiert werden sollen. |
| [CODE_11](#CODE-11) | Gibt an, dass die Daten mit der Barcode-Spezifikation **CODE 11** dekodiert werden sollen. |
| [CODE_128](#CODE-128) | Gibt an, dass die Daten mit der **CODE 128** Barcode-Spezifikation dekodiert werden sollen |
| [CODE_16_K](#CODE-16-K) | Gibt an, dass die Daten mit der **SCode16K** Barcode-Spezifikation dekodiert werden sollen |
| [CODE_32](#CODE-32) | Gibt an, dass die Daten mit der **Code32** Barcode-Spezifikation dekodiert werden sollen |
| [CODE_39](#CODE-39) | Gibt an, dass die Daten mit der **Code 39** Basiszeichensatz-Barcode-Spezifikation dekodiert werden sollen: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | Gibt an, dass die Daten mit der **Code 39** Voll-ASCII-Zeichensatz-Barcode-Spezifikation dekodiert werden sollen: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | Gibt an, dass die Daten mit der **CODE 93** Barcode-Spezifikation dekodiert werden sollen |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | Gibt an, dass die Daten mit der **CompactPdf417** (Pdf417Truncated) Barcode-Spezifikation dekodiert werden sollen |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | Gibt an, dass die Daten mit der **GS1 DATABAR expanded** Barcode-Spezifikation dekodiert werden sollen |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | Gibt an, dass die Daten mit der **GS1 DATABAR expanded stacked** Barcode-Spezifikation dekodiert werden sollen |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | Gibt an, dass die Daten mit der **GS1 DATABAR limited** Barcode-Spezifikation dekodiert werden sollen |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | Gibt an, dass die Daten mit der **GS1 DATABAR omni-directional** Barcode-Spezifikation dekodiert werden sollen |
| [DATABAR_STACKED](#DATABAR-STACKED) | Gibt an, dass die Daten mit der **GS1 DATABAR stacked** Barcode-Spezifikation dekodiert werden sollen |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | Gibt an, dass die Daten mit der **GS1 DATABAR stacked omni-directional** Barcode-Spezifikation dekodiert werden sollen |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | Gibt an, dass die Daten mit der **GS1 DATABAR truncated** Barcode-Spezifikation dekodiert werden sollen |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | Gibt an, dass die Daten mit der **DataLogic 2 of 5** Barcode-Spezifikation dekodiert werden sollen |
| [DATA_MATRIX](#DATA-MATRIX) | Gibt an, dass die Daten mit der **DataMatrix** Barcode-Symbologie dekodiert werden sollen |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | Gibt an, dass die Daten mit der **DeutschePost Ident code** Barcode-Spezifikation dekodiert werden sollen |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | Gibt an, dass die Daten mit der **DeutschePost Leit code** Barcode-Spezifikation dekodiert werden sollen |
| [DOT_CODE](#DOT-CODE) | Gibt an, dass die Daten mit der **DotCode** Barcode-Spezifikation dekodiert werden sollen |
| [DUTCH_KIX](#DUTCH-KIX) | Gibt an, dass die Daten mit der **DotCode** Barcode-Spezifikation dekodiert werden sollen |
| [EAN_13](#EAN-13) | Gibt an, dass die Daten mit der **EAN-13** Barcode-Spezifikation dekodiert werden sollen |
| [EAN_14](#EAN-14) | Gibt an, dass die Daten mit der **EAN14** Barcode-Spezifikation dekodiert werden sollen |
| [EAN_8](#EAN-8) | Gibt an, dass die Daten mit der **EAN-8** Barcode-Spezifikation dekodiert werden sollen |
| [GS_1_AZTEC](#GS-1-AZTEC) | Gibt an, dass die Daten mit der **GS1 Aztec** Barcode-Spezifikation dekodiert werden sollen |
| [GS_1_CODE_128](#GS-1-CODE-128) | Gibt an, dass die Daten mit der **GS1 CODE 128** Barcode-Spezifikation dekodiert werden sollen |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | Gibt an, dass die Daten mit der **GS1 Composite Bar** Barcode-Spezifikation dekodiert werden sollen |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | Gibt an, dass die Daten mit  **GS1DataMatrix**  Barcode‑Symbologie decodiert werden sollen |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | Gibt an, dass die Daten mit  **GS1 DotCode**  Barcode‑Spezifikation decodiert werden sollen |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | Gibt an, dass die Daten mit **GS1 Han Xin Code** Barcode‑Spezifikation decodiert werden sollen |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | Gibt an, dass die Daten mit **MicroPdf417** Barcode‑Spezifikation decodiert werden sollen |
| [GS_1_QR](#GS-1-QR) | Gibt an, dass die Daten mit  **GS1 QR**  Barcode‑Spezifikation decodiert werden sollen |
| [HAN_XIN](#HAN-XIN) | Gibt an, dass die Daten mit **Han Xin Code** Barcode‑Spezifikation decodiert werden sollen |
| [HIBCQRLIC](#HIBCQRLIC) | Gibt an, dass die Daten mit  **HIBC LIC QR**  Barcode‑Spezifikation decodiert werden sollen |
| [HIBCQRPAS](#HIBCQRPAS) | Gibt an, dass die Daten mit  **HIBC PAS QR**  Barcode‑Spezifikation decodiert werden sollen |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | Gibt an, dass die Daten mit  **HIBC LIC Aztec**  Barcode‑Spezifikation decodiert werden sollen |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | Gibt an, dass die Daten mit  **HIBC PAS Aztec**  Barcode‑Spezifikation decodiert werden sollen |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | Gibt an, dass die Daten mit  **HIBC LIC Code128**  Barcode‑Spezifikation decodiert werden sollen |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | Gibt an, dass die Daten mit  **HIBC PAS Code128**  Barcode‑Spezifikation decodiert werden sollen |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | Gibt an, dass die Daten mit  **HIBC LIC Code39**  Barcode‑Spezifikation decodiert werden sollen |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | Gibt an, dass die Daten mit  **HIBC PAS Code39**  Barcode‑Spezifikation decodiert werden sollen |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | Gibt an, dass die Daten mit  **HIBC LIC DataMatrix**  Barcode‑Spezifikation decodiert werden sollen |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | Gibt an, dass die Daten mit  **HIBC PAS DataMatrix**  Barcode‑Spezifikation decodiert werden sollen |
| [IATA_2_OF_5](#IATA-2-OF-5) | Gibt an, dass die Daten mit  **IATA 2 of 5**  Barcode‑Spezifikation decodiert werden sollen. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | Gibt an, dass die Daten mit  **INTERLEAVED 2 of 5**  Barcode‑Spezifikation decodiert werden sollen |
| [ISBN](#ISBN) | Gibt an, dass die Daten mit  **ISBN**  Barcode‑Spezifikation decodiert werden sollen |
| [ISMN](#ISMN) | Gibt an, dass die Daten mit  **ISMN**  Barcode‑Spezifikation decodiert werden sollen |
| [ISSN](#ISSN) | Gibt an, dass die Daten mit  **ISSN**  Barcode‑Spezifikation decodiert werden sollen |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | Gibt an, dass die Daten mit  **Italian Post 25**  Barcode‑Spezifikation decodiert werden sollen |
| [ITF_14](#ITF-14) | Gibt an, dass die Daten mit  **ITF14**  Barcode‑Spezifikation decodiert werden sollen |
| [ITF_6](#ITF-6) | Gibt an, dass die Daten mit  **ITF6**  Barcode‑Spezifikation decodiert werden sollen |
| [MACRO_PDF_417](#MACRO-PDF-417) | Gibt an, dass die Daten mit  **MacroPdf417**  Barcode‑Spezifikation decodiert werden sollen |
| [MAILMARK](#MAILMARK) | Gibt an, dass die Daten mit der **Royal Mail Mailmark** Barcode‑Spezifikation dekodiert werden sollen. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | Gibt an, dass die Daten mit der **Matrix 2 of 5** Barcode‑Spezifikation dekodiert werden sollen |
| [MAXI_CODE](#MAXI-CODE) | Gibt an, dass die Daten mit der **MaxiCode** Barcode‑Spezifikation dekodiert werden sollen |
| [MICRO_PDF_417](#MICRO-PDF-417) | Gibt an, dass die Daten mit der **MicroPdf417** Barcode‑Spezifikation dekodiert werden sollen |
| [MICRO_QR](#MICRO-QR) | Gibt an, dass die Daten mit der **MicroQR Code** Barcode‑Spezifikation dekodiert werden sollen |
| [MICR_E_13_B](#MICR-E-13-B) | Gibt an, dass die Daten mit der **MICR E-13B** Barcode‑Spezifikation dekodiert werden sollen |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | Gibt an, dass Daten mit den am häufigsten verwendeten Symbolen überprüft werden |
| [MSI](#MSI) | Gibt an, dass die Daten mit der **MSI Plessey** Barcode‑Spezifikation dekodiert werden sollen |
| [NONE](#NONE) | Nicht spezifizierter Dekodierungstyp. |
| [ONE_CODE](#ONE-CODE) | Gibt an, dass die Daten mit der USPS **OneCode** Barcode‑Spezifikation dekodiert werden sollen |
| [OPC](#OPC) | Gibt an, dass die Daten mit der **OPC** Barcode‑Spezifikation dekodiert werden sollen |
| [PATCH_CODE](#PATCH-CODE) | Gibt an, dass die Daten mit der **Patch code** Barcode‑Spezifikation dekodiert werden sollen. |
| [PDF_417](#PDF-417) | Gibt an, dass die Daten mit der **Pdf417** Barcode‑Symbologie dekodiert werden sollen |
| [PHARMACODE](#PHARMACODE) | Gibt an, dass die Daten mit dem **Pharmacode** Barcode dekodiert werden sollen. |
| [PLANET](#PLANET) | Gibt an, dass die Daten mit der **Planet** Barcode‑Spezifikation dekodiert werden sollen |
| [POSTAL_TYPES](#POSTAL-TYPES) | Gibt an, dass Daten mit allen **1.5D POSTAL** Barcode‑Symbolen überprüft werden, wie **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | Gibt an, dass die Daten mit der **Postnet** Barcode‑Spezifikation dekodiert werden sollen |
| [PZN](#PZN) | Gibt an, dass die Daten mit der **PZN** Barcode‑Spezifikation dekodiert werden sollen. |
| [QR](#QR) | Gibt an, dass die Daten mit der **QR Code** Barcode‑Spezifikation dekodiert werden sollen |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | Gibt an, dass die Daten mit der **RectMicroQR (rMQR) Code** Barcode‑Spezifikation dekodiert werden sollen |
| [RM_4_SCC](#RM-4-SCC) | Gibt an, dass die Daten mit der **RM4SCC** Barcode‑Spezifikation dekodiert werden sollen. |
| [SCC_14](#SCC-14) | Gibt an, dass die Daten mit der **SCC14** Barcode‑Spezifikation dekodiert werden sollen |
| [SSCC_18](#SSCC-18) | Gibt an, dass die Daten mit der **SSCC18** Barcode‑Spezifikation dekodiert werden sollen |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | Gibt an, dass die Daten mit der **Standard 2 of 5** Barcode‑Spezifikation dekodiert werden sollen |
| [SUPPLEMENT](#SUPPLEMENT) | Gibt an, dass die Daten mit der **Supplement(EAN2, EAN5)** Barcode‑Spezifikation dekodiert werden sollen |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | Gibt an, dass die Daten mit der **Swiss Post Parcel Barcode** Barcode-Spezifikation dekodiert werden sollen. |
| [TYPES_1D](#TYPES-1D) | Gibt an, dass Daten mit allen **1D**-Barcode-Symbologien geprüft werden. |
| [TYPES_2D](#TYPES-2D) | Gibt an, dass Daten mit allen **2D**-Barcode-Symbologien geprüft werden. |
| [UPCA](#UPCA) | Gibt an, dass die Daten mit der **UPC-A** Barcode-Spezifikation dekodiert werden sollen. |
| [UPCE](#UPCE) | Gibt an, dass die Daten mit der **UPC-E** Barcode-Spezifikation dekodiert werden sollen. |
| [VIN](#VIN) | Gibt an, dass die Daten mit der **VIN** (Vehicle Identification Number) Barcode-Spezifikation dekodiert werden sollen. |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | Liefert ein Array, das AllSupportedTypes darstellt. |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Ruft ein Array der Namen der Decodierungstypen ab. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Bestimmt, ob der angegebene BaseDecodeType irgendeine 1D-Barcode-Symbologie enthält. |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Bestimmt, ob der angegebene BaseDecodeType irgendeine 2D-Barcode-Symbologie enthält. |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Bestimmt, ob der angegebene BaseDecodeType irgendeine Post-Barcode-Symbologie enthält. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Geben Sie Scan-Sets nach barcodeTypes an. |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines MultiDecodeType in seine Instanz. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. |
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


Gibt an, dass Daten mit allen verfügbaren Symbolen überprüft werden.

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


Gibt an, dass die Daten mit der Barcode-Spezifikation **Australian Post Domestic eParcel Barcode** dekodiert werden sollen.

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


Gibt an, dass die Daten mit der Barcode-Spezifikation **Australia Post** dekodiert werden sollen.

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


Gibt an, dass die Daten mit der Barcode-Spezifikation **Aztec** dekodiert werden sollen.

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


Gibt an, dass die Daten mit der Barcode-Spezifikation **CODABAR** dekodiert werden sollen.

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


Gibt an, dass die Daten mit der Barcode-Spezifikation **CodablockF** dekodiert werden sollen.

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


Gibt an, dass die Daten mit der Barcode-Spezifikation **CODE 11** dekodiert werden sollen.

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


Gibt an, dass die Daten mit der **CODE 128** Barcode-Spezifikation dekodiert werden sollen

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


Gibt an, dass die Daten mit der **SCode16K** Barcode-Spezifikation dekodiert werden sollen

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


Gibt an, dass die Daten mit der **Code32** Barcode-Spezifikation dekodiert werden sollen

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


Gibt an, dass die Daten mit der **Code 39** Basiszeichensatz-Barcode-Spezifikation dekodiert werden sollen: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


Gibt an, dass die Daten mit der **Code 39** Voll-ASCII-Zeichensatz-Barcode-Spezifikation dekodiert werden sollen: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


Gibt an, dass die Daten mit der **CODE 93** Barcode-Spezifikation dekodiert werden sollen

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


Gibt an, dass die Daten mit der **CompactPdf417** (Pdf417Truncated) Barcode-Spezifikation dekodiert werden sollen

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


Gibt an, dass die Daten mit der **GS1 DATABAR expanded** Barcode-Spezifikation dekodiert werden sollen

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


Gibt an, dass die Daten mit der **GS1 DATABAR expanded stacked** Barcode-Spezifikation dekodiert werden sollen

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


Gibt an, dass die Daten mit der **GS1 DATABAR limited** Barcode-Spezifikation dekodiert werden sollen

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


Gibt an, dass die Daten mit der **GS1 DATABAR omni-directional** Barcode-Spezifikation dekodiert werden sollen

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


Gibt an, dass die Daten mit der **GS1 DATABAR stacked** Barcode-Spezifikation dekodiert werden sollen

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


Gibt an, dass die Daten mit der **GS1 DATABAR stacked omni-directional** Barcode-Spezifikation dekodiert werden sollen

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


Gibt an, dass die Daten mit der **GS1 DATABAR truncated** Barcode-Spezifikation dekodiert werden sollen

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


Gibt an, dass die Daten mit der **DataLogic 2 of 5** Barcode-Spezifikation dekodiert werden sollen

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


Gibt an, dass die Daten mit der **DataMatrix** Barcode-Symbologie dekodiert werden sollen

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


Gibt an, dass die Daten mit der **DeutschePost Ident code** Barcode-Spezifikation dekodiert werden sollen

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


Gibt an, dass die Daten mit der **DeutschePost Leit code** Barcode-Spezifikation dekodiert werden sollen

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


Gibt an, dass die Daten mit der **DotCode** Barcode-Spezifikation dekodiert werden sollen

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


Gibt an, dass die Daten mit der **DotCode** Barcode-Spezifikation dekodiert werden sollen

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


Gibt an, dass die Daten mit der **EAN-13** Barcode-Spezifikation dekodiert werden sollen

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


Gibt an, dass die Daten mit der **EAN14** Barcode-Spezifikation dekodiert werden sollen

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


Gibt an, dass die Daten mit der **EAN-8** Barcode-Spezifikation dekodiert werden sollen

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


Gibt an, dass die Daten mit der **GS1 Aztec** Barcode-Spezifikation dekodiert werden sollen

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


Gibt an, dass die Daten mit der **GS1 CODE 128** Barcode-Spezifikation dekodiert werden sollen

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


Gibt an, dass die Daten mit der **GS1 Composite Bar** Barcode-Spezifikation dekodiert werden sollen

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


Gibt an, dass die Daten mit  **GS1DataMatrix**  Barcode‑Symbologie decodiert werden sollen

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


Gibt an, dass die Daten mit  **GS1 DotCode**  Barcode‑Spezifikation decodiert werden sollen

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


Gibt an, dass die Daten mit **GS1 Han Xin Code** Barcode‑Spezifikation decodiert werden sollen

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


Gibt an, dass die Daten mit **MicroPdf417** Barcode‑Spezifikation decodiert werden sollen

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


Gibt an, dass die Daten mit  **GS1 QR**  Barcode‑Spezifikation decodiert werden sollen

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


Gibt an, dass die Daten mit **Han Xin Code** Barcode‑Spezifikation decodiert werden sollen

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


Gibt an, dass die Daten mit  **HIBC LIC QR**  Barcode‑Spezifikation decodiert werden sollen

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


Gibt an, dass die Daten mit  **HIBC PAS QR**  Barcode‑Spezifikation decodiert werden sollen

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


Gibt an, dass die Daten mit  **HIBC LIC Aztec**  Barcode‑Spezifikation decodiert werden sollen

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


Gibt an, dass die Daten mit  **HIBC PAS Aztec**  Barcode‑Spezifikation decodiert werden sollen

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


Gibt an, dass die Daten mit  **HIBC LIC Code128**  Barcode‑Spezifikation decodiert werden sollen

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


Gibt an, dass die Daten mit  **HIBC PAS Code128**  Barcode‑Spezifikation decodiert werden sollen

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


Gibt an, dass die Daten mit  **HIBC LIC Code39**  Barcode‑Spezifikation decodiert werden sollen

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


Gibt an, dass die Daten mit  **HIBC PAS Code39**  Barcode‑Spezifikation decodiert werden sollen

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


Gibt an, dass die Daten mit  **HIBC LIC DataMatrix**  Barcode‑Spezifikation decodiert werden sollen

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


Gibt an, dass die Daten mit  **HIBC PAS DataMatrix**  Barcode‑Spezifikation decodiert werden sollen

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


Gibt an, dass die Daten mit der **IATA 2 of 5** Barcode-Spezifikation dekodiert werden sollen. IATA (International Air Transport Association) verwendet diesen Barcode für die Verwaltung von Luftfracht.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


Gibt an, dass die Daten mit  **INTERLEAVED 2 of 5**  Barcode‑Spezifikation decodiert werden sollen

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


Gibt an, dass die Daten mit  **ISBN**  Barcode‑Spezifikation decodiert werden sollen

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


Gibt an, dass die Daten mit  **ISMN**  Barcode‑Spezifikation decodiert werden sollen

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


Gibt an, dass die Daten mit  **ISSN**  Barcode‑Spezifikation decodiert werden sollen

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


Gibt an, dass die Daten mit  **Italian Post 25**  Barcode‑Spezifikation decodiert werden sollen

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


Gibt an, dass die Daten mit  **ITF14**  Barcode‑Spezifikation decodiert werden sollen

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


Gibt an, dass die Daten mit  **ITF6**  Barcode‑Spezifikation decodiert werden sollen

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


Gibt an, dass die Daten mit  **MacroPdf417**  Barcode‑Spezifikation decodiert werden sollen

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


Gibt an, dass die Daten mit der **Royal Mail Mailmark** Barcode‑Spezifikation dekodiert werden sollen.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


Gibt an, dass die Daten mit der **Matrix 2 of 5** Barcode‑Spezifikation dekodiert werden sollen

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


Gibt an, dass die Daten mit der **MaxiCode** Barcode‑Spezifikation dekodiert werden sollen

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


Gibt an, dass die Daten mit der **MicroPdf417** Barcode‑Spezifikation dekodiert werden sollen

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


Gibt an, dass die Daten mit der **MicroQR Code** Barcode‑Spezifikation dekodiert werden sollen

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


Gibt an, dass die Daten mit der **MICR E-13B** Barcode‑Spezifikation dekodiert werden sollen

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


Gibt an, dass Daten mit den am häufigsten verwendeten Symbolen überprüft werden

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


Gibt an, dass die Daten mit der **MSI Plessey** Barcode‑Spezifikation dekodiert werden sollen

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


Nicht spezifizierter Dekodierungstyp.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


Gibt an, dass die Daten mit der USPS **OneCode** Barcode‑Spezifikation dekodiert werden sollen

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


Gibt an, dass die Daten mit der **OPC** Barcode‑Spezifikation dekodiert werden sollen

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


Gibt an, dass die Daten mit der **Patch code** Barcode-Spezifikation dekodiert werden sollen. Die Barcode-Symbologie wird für automatisiertes Scannen verwendet.

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


Gibt an, dass die Daten mit der **Pdf417** Barcode‑Symbologie dekodiert werden sollen

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


Gibt an, dass die Daten mit dem **Pharmacode** Barcode dekodiert werden sollen. Diese Symbologie ist auch als Pharmaceutical BINARY Code bekannt.

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


Gibt an, dass die Daten mit der **Planet** Barcode‑Spezifikation dekodiert werden sollen

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


Gibt an, dass Daten mit allen **1.5D POSTAL** Barcode‑Symbolen überprüft werden, wie **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


Gibt an, dass die Daten mit der **Postnet** Barcode‑Spezifikation dekodiert werden sollen

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


Gibt an, dass die Daten mit der **PZN** Barcode-Spezifikation dekodiert werden sollen. Diese Symbologie ist auch als Pharma Zentral Nummer bekannt. PZN7 und PZN8 werden unterstützt.

### QR {#QR}
```
public static final SingleDecodeType QR
```


Gibt an, dass die Daten mit der **QR Code** Barcode‑Spezifikation dekodiert werden sollen

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


Gibt an, dass die Daten mit der **RectMicroQR (rMQR) Code** Barcode‑Spezifikation dekodiert werden sollen

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


Gibt an, dass die Daten mit der **RM4SCC** Barcode-Spezifikation dekodiert werden sollen. RM4SCC (Royal Mail 4-state Customer Code) wird für den automatisierten Postsortierprozess im Vereinigten Königreich verwendet.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


Gibt an, dass die Daten mit der **SCC14** Barcode‑Spezifikation dekodiert werden sollen

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


Gibt an, dass die Daten mit der **SSCC18** Barcode‑Spezifikation dekodiert werden sollen

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


Gibt an, dass die Daten mit der **Standard 2 of 5** Barcode‑Spezifikation dekodiert werden sollen

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


Gibt an, dass die Daten mit der **Supplement(EAN2, EAN5)** Barcode‑Spezifikation dekodiert werden sollen

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


Gibt an, dass die Daten mit der **Swiss Post Parcel Barcode** Barcode-Spezifikation dekodiert werden sollen.

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


Gibt an, dass Daten mit allen **1D**-Barcode-Symbologien geprüft werden.

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


Gibt an, dass Daten mit allen **2D**-Barcode-Symbologien geprüft werden.

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


Gibt an, dass die Daten mit der **UPC-A** Barcode-Spezifikation dekodiert werden sollen.

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


Gibt an, dass die Daten mit der **UPC-E** Barcode-Spezifikation dekodiert werden sollen.

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


Gibt an, dass die Daten mit der **VIN** (Vehicle Identification Number) Barcode-Spezifikation dekodiert werden sollen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


Liefert ein Array, das AllSupportedTypes darstellt.

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


Ruft ein Array der Namen der Decodierungstypen ab.

**Returns:**
java.lang.String[] - Ein String-Array der Namen der Decodierungstypen.
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


Bestimmt, ob der angegebene BaseDecodeType irgendeine 1D-Barcode-Symbologie enthält.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Der BaseDecodeType zum Testen. |

**Returns:**
boolean - Gibt **true** zurück, wenn BaseDecodeType irgendeine 1D-Barcode-Symbologie enthält; andernfalls gibt es **false** zurück.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


Bestimmt, ob der angegebene BaseDecodeType irgendeine 2D-Barcode-Symbologie enthält.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Der BaseDecodeType zum Testen. |

**Returns:**
boolean - Gibt **true** zurück, wenn BaseDecodeTypeddddddddw irgendeine 2D-Barcode-Symbologie enthält; andernfalls gibt es **false** zurück.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


Bestimmt, ob der angegebene BaseDecodeType irgendeine Post-Barcode-Symbologie enthält.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Der BaseDecodeType zum Testen |

**Returns:**
boolean - Gibt **true** zurück, wenn BaseDecodeType irgendeine Post-Barcode-Symbologie enthält; andernfalls gibt es **false** zurück.
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


Konvertiert die String-Darstellung eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Ein String, der eine SingleDecodeType-Darstellung zum Konvertieren enthält. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

ansonsten gibt es einen unbestimmten Typ zurück. oder SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


Konvertiert die String-Darstellung eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Ein String, der einen SingleDecodeType im Format "EAN8" oder "EAN13" oder "CodaBar"... zum Konvertieren enthält. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - **true** wenn s erfolgreich konvertiert wurde; andernfalls **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


Geben Sie Scan-Sets nach barcodeTypes an.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Array von einzelnen und mehreren Dekodierungstypen |

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


Konvertiert die String-Darstellung eines MultiDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Ein String im Format entweder "AllSupportedTypes" oder "EAN8,EAN13,CodaBar" zum Konvertieren. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Ein tatsächlicher MultiDecodeType wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; andernfalls gibt er einen unbestimmten Typ zurück: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Konvertiert die String-Darstellung eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| parsingType | java.lang.String | Ein String, der einen SingleDecodeType im Format "EAN8" oder "EAN13" oder "CodaBar"... zum Konvertieren enthält. |

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

