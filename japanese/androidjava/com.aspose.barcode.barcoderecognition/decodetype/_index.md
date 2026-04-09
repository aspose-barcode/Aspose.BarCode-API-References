---
title: DecodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: Specify the type of barcode to read.
type: docs
weight: 32
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
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
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128);
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
## フィールド

| フィールド | Description |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | データが利用可能なすべてのシンボロジーでチェックされることを指定します。 |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | データを **Australian Post Domestic eParcel Barcode** バーコード仕様でデコードすべきことを指定します。 |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | データを **Australia Post** バーコード仕様でデコードすべきことを指定します。 |
| [AZTEC](#AZTEC) | データを **Aztec** バーコード仕様でデコードすべきことを指定します。 |
| [CODABAR](#CODABAR) | データを **CODABAR** バーコード仕様でデコードすべきことを指定します。 |
| [CODABLOCK_F](#CODABLOCK-F) | データを **CodablockF** バーコード仕様でデコードすべきことを指定します。 |
| [CODE_11](#CODE-11) | データを **CODE 11** バーコード仕様でデコードすべきことを指定します。 |
| [CODE_128](#CODE-128) | データは **CODE 128** バーコード仕様でデコードされることを指定します |
| [CODE_16_K](#CODE-16-K) | データは **SCode16K** バーコード仕様でデコードされることを指定します |
| [CODE_32](#CODE-32) | データは **Code32** バーコード仕様でデコードされることを指定します |
| [CODE_39](#CODE-39) | データは **Code 39** 基本文字セットのバーコード仕様（ISO/IEC 16388）でデコードされることを指定します |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | データは **Code 39** フルASCII文字セットのバーコード仕様（ISO/IEC 16388）でデコードされることを指定します |
| [CODE_93](#CODE-93) | データは **CODE 93** バーコード仕様でデコードされることを指定します |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | データは **CompactPdf417**（Pdf417Truncated）バーコード仕様でデコードされることを指定します |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | データは **GS1 DATABAR expanded** バーコード仕様でデコードされることを指定します |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | データは **GS1 DATABAR expanded stacked** バーコード仕様でデコードされることを指定します |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | データは **GS1 DATABAR limited** バーコード仕様でデコードされることを指定します |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | データは **GS1 DATABAR omni-directional** バーコード仕様でデコードされることを指定します |
| [DATABAR_STACKED](#DATABAR-STACKED) | データは **GS1 DATABAR stacked** バーコード仕様でデコードされることを指定します |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | データは **GS1 DATABAR stacked omni-directional** バーコード仕様でデコードされることを指定します |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | データは **GS1 DATABAR truncated** バーコード仕様でデコードされることを指定します |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | データは **DataLogic 2 of 5** バーコード仕様でデコードされることを指定します |
| [DATA_MATRIX](#DATA-MATRIX) | データは **DataMatrix** バーコードシンボロジーでデコードされることを指定します |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | データは **DeutschePost Ident code** バーコード仕様でデコードされることを指定します |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | データは **DeutschePost Leit code** バーコード仕様でデコードされることを指定します |
| [DOT_CODE](#DOT-CODE) | データは **DotCode** バーコード仕様でデコードされることを指定します |
| [DUTCH_KIX](#DUTCH-KIX) | データは **DotCode** バーコード仕様でデコードされることを指定します |
| [EAN_13](#EAN-13) | データは **EAN-13** バーコード仕様でデコードされることを指定します |
| [EAN_14](#EAN-14) | データは **EAN14** バーコード仕様でデコードされることを指定します |
| [EAN_8](#EAN-8) | データは **EAN-8** バーコード仕様でデコードされることを指定します |
| [GS_1_AZTEC](#GS-1-AZTEC) | データは **GS1 Aztec** バーコード仕様でデコードされることを指定します |
| [GS_1_CODE_128](#GS-1-CODE-128) | データは **GS1 CODE 128** バーコード仕様でデコードされることを指定します |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | データは **GS1 Composite Bar** バーコード仕様でデコードされることを指定します |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | データは **GS1DataMatrix** バーコードシンボルでデコードされるように指定します |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | データは **GS1 DotCode** バーコード仕様でデコードされるように指定します |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | データは **GS1 Han Xin Code** バーコード仕様でデコードされるように指定します |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | データは **MicroPdf417** バーコード仕様でデコードされるように指定します |
| [GS_1_QR](#GS-1-QR) | データは **GS1 QR** バーコード仕様でデコードされるように指定します |
| [HAN_XIN](#HAN-XIN) | データは **Han Xin Code** バーコード仕様でデコードされるように指定します |
| [HIBCQRLIC](#HIBCQRLIC) | データは **HIBC LIC QR** バーコード仕様でデコードされるように指定します |
| [HIBCQRPAS](#HIBCQRPAS) | データは **HIBC PAS QR** バーコード仕様でデコードされるように指定します |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | データは **HIBC LIC Aztec** バーコード仕様でデコードされるように指定します |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | データは **HIBC PAS Aztec** バーコード仕様でデコードされるように指定します |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | データは **HIBC LIC Code128** バーコード仕様でデコードされるように指定します |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | データは **HIBC PAS Code128** バーコード仕様でデコードされるように指定します |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | データは **HIBC LIC Code39** バーコード仕様でデコードされるように指定します |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | データは **HIBC PAS Code39** バーコード仕様でデコードされるように指定します |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | データは **HIBC LIC DataMatrix** バーコード仕様でデコードされるように指定します |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | データは **HIBC PAS DataMatrix** バーコード仕様でデコードされるように指定します |
| [IATA_2_OF_5](#IATA-2-OF-5) | データは **IATA 2 of 5** バーコード仕様でデコードされるように指定します。 |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | データは **INTERLEAVED 2 of 5** バーコード仕様でデコードされるように指定します |
| [ISBN](#ISBN) | データは **ISBN** バーコード仕様でデコードされるように指定します |
| [ISMN](#ISMN) | データは **ISMN** バーコード仕様でデコードされるように指定します |
| [ISSN](#ISSN) | データは **ISSN** バーコード仕様でデコードされるように指定します |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | データは **Italian Post 25** バーコード仕様でデコードされるように指定します |
| [ITF_14](#ITF-14) | データは **ITF14** バーコード仕様でデコードされるように指定します |
| [ITF_6](#ITF-6) | データは **ITF6** バーコード仕様でデコードされるように指定します |
| [MACRO_PDF_417](#MACRO-PDF-417) | データは **MacroPdf417** バーコード仕様でデコードされるように指定します |
| [MAILMARK](#MAILMARK) | データは **Royal Mail Mailmark** バーコード仕様でデコードするように指定します。 |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | データは **Matrix 2 of 5** バーコード仕様でデコードするように指定します。 |
| [MAXI_CODE](#MAXI-CODE) | データは **MaxiCode** バーコード仕様でデコードするように指定します。 |
| [MICRO_PDF_417](#MICRO-PDF-417) | データは **MicroPdf417** バーコード仕様でデコードするように指定します。 |
| [MICRO_QR](#MICRO-QR) | データは **MicroQR Code** バーコード仕様でデコードするように指定します。 |
| [MICR_E_13_B](#MICR-E-13-B) | データは **MICR E-13B** バーコード仕様でデコードするように指定します。 |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | データは最も一般的に使用されるシンボルでチェックされるように指定します。 |
| [MSI](#MSI) | データは **MSI Plessey** バーコード仕様でデコードするように指定します。 |
| [NONE](#NONE) | デコードタイプが未指定です。 |
| [ONE_CODE](#ONE-CODE) | データは USPS の **OneCode** バーコード仕様でデコードするように指定します。 |
| [OPC](#OPC) | データは **OPC** バーコード仕様でデコードするように指定します。 |
| [PATCH_CODE](#PATCH-CODE) | データは **Patch code** バーコード仕様でデコードするように指定します。 |
| [PDF_417](#PDF-417) | データは **Pdf417** バーコードシンボルでデコードするように指定します。 |
| [PHARMACODE](#PHARMACODE) | データは **Pharmacode** バーコードでデコードするように指定します。 |
| [PLANET](#PLANET) | データは **Planet** バーコード仕様でデコードするように指定します。 |
| [POSTAL_TYPES](#POSTAL-TYPES) | データは **1.5D POSTAL** のすべてのバーコードシンボルでチェックされるように指定します。例として **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** が含まれます。 |
| [POSTNET](#POSTNET) | データは **Postnet** バーコード仕様でデコードするように指定します。 |
| [PZN](#PZN) | データは **PZN** バーコード仕様でデコードするように指定します。 |
| [QR](#QR) | データは **QR Code** バーコード仕様でデコードするように指定します。 |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | データは **RectMicroQR (rMQR) Code** バーコード仕様でデコードするように指定します。 |
| [RM_4_SCC](#RM-4-SCC) | データは **RM4SCC** バーコード仕様でデコードするように指定します。 |
| [SCC_14](#SCC-14) | データは **SCC14** バーコード仕様でデコードするように指定します。 |
| [SSCC_18](#SSCC-18) | データは **SSCC18** バーコード仕様でデコードするように指定します。 |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | データは **Standard 2 of 5** バーコード仕様でデコードするように指定します。 |
| [SUPPLEMENT](#SUPPLEMENT) | データは **Supplement(EAN2, EAN5)** バーコード仕様でデコードするように指定します。 |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | データを **Swiss Post Parcel Barcode** バーコード仕様でデコードすることを指定します |
| [TYPES_1D](#TYPES-1D) | データが **1D** バーコードシンボルすべてでチェックされることを指定します |
| [TYPES_2D](#TYPES-2D) | データが **2D** バーコードシンボルすべてでチェックされることを指定します |
| [UPCA](#UPCA) | データを **UPC-A** バーコード仕様でデコードすることを指定します |
| [UPCE](#UPCE) | データを **UPC-E** バーコード仕様でデコードすることを指定します |
| [VIN](#VIN) | データを **VIN**（Vehicle Identification Number）バーコード仕様でデコードすることを指定します |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | AllSupportedTypes を表す配列を取得します |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | デコードタイプの名前の配列を取得します |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 指定された BaseDecodeType が 1D バーコードシンボルを含むかどうかを判断します |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 指定された BaseDecodeType が 2D バーコードシンボルを含むかどうかを判断します |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 指定された BaseDecodeType が郵便バーコードシンボルを含むかどうかを判断します |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | SingleDecodeType の文字列表現をインスタンスに変換します。 |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | SingleDecodeType の文字列表現をインスタンスに変換します。 |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | barcodeTypes によってスキャンセットを指定します |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType の文字列表現をインスタンスに変換します。 |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType の文字列表現をインスタンスに変換します。 |
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


データが利用可能なすべてのシンボロジーでチェックされることを指定します。

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


データを **Australian Post Domestic eParcel Barcode** バーコード仕様でデコードすべきことを指定します。

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


データを **Australia Post** バーコード仕様でデコードすべきことを指定します。

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


データを **Aztec** バーコード仕様でデコードすべきことを指定します。

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


データを **CODABAR** バーコード仕様でデコードすべきことを指定します。

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


データを **CodablockF** バーコード仕様でデコードすべきことを指定します。

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


データを **CODE 11** バーコード仕様でデコードすべきことを指定します。

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


データは **CODE 128** バーコード仕様でデコードされることを指定します

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


データは **SCode16K** バーコード仕様でデコードされることを指定します

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


データは **Code32** バーコード仕様でデコードされることを指定します

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


データは **Code 39** 基本文字セットのバーコード仕様（ISO/IEC 16388）でデコードされることを指定します

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


データは **Code 39** フルASCII文字セットのバーコード仕様（ISO/IEC 16388）でデコードされることを指定します

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


データは **CODE 93** バーコード仕様でデコードされることを指定します

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


データは **CompactPdf417**（Pdf417Truncated）バーコード仕様でデコードされることを指定します

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


データは **GS1 DATABAR expanded** バーコード仕様でデコードされることを指定します

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


データは **GS1 DATABAR expanded stacked** バーコード仕様でデコードされることを指定します

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


データは **GS1 DATABAR limited** バーコード仕様でデコードされることを指定します

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


データは **GS1 DATABAR omni-directional** バーコード仕様でデコードされることを指定します

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


データは **GS1 DATABAR stacked** バーコード仕様でデコードされることを指定します

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


データは **GS1 DATABAR stacked omni-directional** バーコード仕様でデコードされることを指定します

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


データは **GS1 DATABAR truncated** バーコード仕様でデコードされることを指定します

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


データは **DataLogic 2 of 5** バーコード仕様でデコードされることを指定します

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


データは **DataMatrix** バーコードシンボロジーでデコードされることを指定します

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


データは **DeutschePost Ident code** バーコード仕様でデコードされることを指定します

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


データは **DeutschePost Leit code** バーコード仕様でデコードされることを指定します

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


データは **DotCode** バーコード仕様でデコードされることを指定します

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


データは **DotCode** バーコード仕様でデコードされることを指定します

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


データは **EAN-13** バーコード仕様でデコードされることを指定します

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


データは **EAN14** バーコード仕様でデコードされることを指定します

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


データは **EAN-8** バーコード仕様でデコードされることを指定します

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


データは **GS1 Aztec** バーコード仕様でデコードされることを指定します

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


データは **GS1 CODE 128** バーコード仕様でデコードされることを指定します

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


データは **GS1 Composite Bar** バーコード仕様でデコードされることを指定します

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


データは **GS1DataMatrix** バーコードシンボルでデコードされるように指定します

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


データは **GS1 DotCode** バーコード仕様でデコードされるように指定します

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


データは **GS1 Han Xin Code** バーコード仕様でデコードされるように指定します

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


データは **MicroPdf417** バーコード仕様でデコードされるように指定します

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


データは **GS1 QR** バーコード仕様でデコードされるように指定します

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


データは **Han Xin Code** バーコード仕様でデコードされるように指定します

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


データは **HIBC LIC QR** バーコード仕様でデコードされるように指定します

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


データは **HIBC PAS QR** バーコード仕様でデコードされるように指定します

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


データは **HIBC LIC Aztec** バーコード仕様でデコードされるように指定します

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


データは **HIBC PAS Aztec** バーコード仕様でデコードされるように指定します

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


データは **HIBC LIC Code128** バーコード仕様でデコードされるように指定します

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


データは **HIBC PAS Code128** バーコード仕様でデコードされるように指定します

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


データは **HIBC LIC Code39** バーコード仕様でデコードされるように指定します

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


データは **HIBC PAS Code39** バーコード仕様でデコードされるように指定します

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


データは **HIBC LIC DataMatrix** バーコード仕様でデコードされるように指定します

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


データは **HIBC PAS DataMatrix** バーコード仕様でデコードされるように指定します

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


データを **IATA 2 of 5** バーコード仕様でデコードすることを指定します。IATA（International Air Transport Association）は航空貨物の管理にこのバーコードを使用します。

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


データは **INTERLEAVED 2 of 5** バーコード仕様でデコードされるように指定します

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


データは **ISBN** バーコード仕様でデコードされるように指定します

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


データは **ISMN** バーコード仕様でデコードされるように指定します

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


データは **ISSN** バーコード仕様でデコードされるように指定します

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


データは **Italian Post 25** バーコード仕様でデコードされるように指定します

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


データは **ITF14** バーコード仕様でデコードされるように指定します

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


データは **ITF6** バーコード仕様でデコードされるように指定します

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


データは **MacroPdf417** バーコード仕様でデコードされるように指定します

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


データは **Royal Mail Mailmark** バーコード仕様でデコードするように指定します。

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


データは **Matrix 2 of 5** バーコード仕様でデコードするように指定します。

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


データは **MaxiCode** バーコード仕様でデコードするように指定します。

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


データは **MicroPdf417** バーコード仕様でデコードするように指定します。

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


データは **MicroQR Code** バーコード仕様でデコードするように指定します。

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


データは **MICR E-13B** バーコード仕様でデコードするように指定します。

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


データは最も一般的に使用されるシンボルでチェックされるように指定します。

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


データは **MSI Plessey** バーコード仕様でデコードするように指定します。

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


デコードタイプが未指定です。

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


データは USPS の **OneCode** バーコード仕様でデコードするように指定します。

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


データは **OPC** バーコード仕様でデコードするように指定します。

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


データを **Patch code** バーコード仕様でデコードすることを指定します。バーコードシンボルは自動スキャンに使用されます

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


データは **Pdf417** バーコードシンボルでデコードするように指定します。

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


データを **Pharmacode** バーコードでデコードすることを指定します。このシンボルは Pharmaceutical BINARY Code とも呼ばれます

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


データは **Planet** バーコード仕様でデコードするように指定します。

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


データは **1.5D POSTAL** のすべてのバーコードシンボルでチェックされるように指定します。例として **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** が含まれます。

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


データは **Postnet** バーコード仕様でデコードするように指定します。

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


データを **PZN** バーコード仕様でデコードすることを指定します。このシンボルは Pharma Zentral Nummer とも呼ばれます。PZN7 と PZN8 がサポートされています。

### QR {#QR}
```
public static final SingleDecodeType QR
```


データは **QR Code** バーコード仕様でデコードするように指定します。

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


データは **RectMicroQR (rMQR) Code** バーコード仕様でデコードするように指定します。

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


データを **RM4SCC** バーコード仕様でデコードすることを指定します。RM4SCC（Royal Mail 4-state Customer Code）は英国の自動郵便仕分けプロセスで使用されます。

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


データは **SCC14** バーコード仕様でデコードするように指定します。

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


データは **SSCC18** バーコード仕様でデコードするように指定します。

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


データは **Standard 2 of 5** バーコード仕様でデコードするように指定します。

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


データは **Supplement(EAN2, EAN5)** バーコード仕様でデコードするように指定します。

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


データを **Swiss Post Parcel Barcode** バーコード仕様でデコードすることを指定します

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


データが **1D** バーコードシンボルすべてでチェックされることを指定します

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


データが **2D** バーコードシンボルすべてでチェックされることを指定します

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


データを **UPC-A** バーコード仕様でデコードすることを指定します

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


データを **UPC-E** バーコード仕様でデコードすることを指定します

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


データを **VIN**（Vehicle Identification Number）バーコード仕様でデコードすることを指定します

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


AllSupportedTypes を表す配列を取得します

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


デコードタイプの名前の配列を取得します

**Returns:**
java.lang.String[] - デコードタイプの名前の文字列配列です。
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


指定された BaseDecodeType が 1D バーコードシンボルを含むかどうかを判断します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | テスト対象の BaseDecodeType。 |

**Returns:**
boolean - BaseDecodeType が 1D バーコードシンボルを含む場合は **true** を返し、そうでない場合は **false** を返します。
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


指定された BaseDecodeType が 2D バーコードシンボルを含むかどうかを判断します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | テスト対象の BaseDecodeType。 |

**Returns:**
boolean - BaseDecodeTypeddddddddw が 2D バーコードシンボルを含む場合は **true** を返し、そうでない場合は **false** を返します。
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


指定された BaseDecodeType が郵便バーコードシンボルを含むかどうかを判断します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | テスト対象の BaseDecodeType |

**Returns:**
boolean - BaseDecodeType が郵便バーコードシンボルを含む場合は **true** を返し、そうでない場合は **false** を返します。
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


SingleDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための SingleDecodeType 表現を含む文字列です。 |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

それ以外の場合は不定型を返します。 または SingleDecodeType (-1, "NONE")。
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


SingleDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための "EAN8"、"EAN13"、"CodaBar" などの形式で表された SingleDecodeType を含む文字列 |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - **true** が s の変換に成功した場合; それ以外は **false**。
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


barcodeTypes によってスキャンセットを指定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 単一および複数デコードタイプの配列 |

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


MultiDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための文字列で、形式は "AllSupportedTypes" または "EAN8,EAN13,CodaBar" のいずれかです。 |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - 変換が正常に完了した場合は実際の MultiDecodeType が返されます; それ以外の場合は不定型を返します: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための "EAN8"、"EAN13"、"CodaBar" などの形式で表された SingleDecodeType を含む文字列 |

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

