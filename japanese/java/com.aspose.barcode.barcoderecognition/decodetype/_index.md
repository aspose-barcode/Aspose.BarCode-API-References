---
title: "DecodeType"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "読み取るバーコードのタイプを指定します。"
type: docs
weight: 30
url: /ja/java/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

読み取るバーコードのタイプを指定します。

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
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | データが利用可能なすべてのシンボロジーでチェックされることを指定します。 |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | データを **Australian Post Domestic eParcel Barcode** バーコード仕様でデコードすべきことを指定します。 |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | データは **Australia Post** バーコード仕様でデコードされるように指定します |
| [AZTEC](#AZTEC) | データは **Aztec** バーコード仕様でデコードされるように指定します |
| [CODABAR](#CODABAR) | データは **CODABAR** バーコード仕様でデコードされるように指定します |
| [CODABLOCK_F](#CODABLOCK-F) | データは **CodablockF** バーコード仕様でデコードされるように指定します |
| [CODE_11](#CODE-11) | データは **CODE 11** バーコード仕様でデコードされるように指定します |
| [CODE_128](#CODE-128) | データは **CODE 128** バーコード仕様でデコードされるように指定します |
| [CODE_16_K](#CODE-16-K) | データは **SCode16K** バーコード仕様でデコードされるように指定します |
| [CODE_32](#CODE-32) | データは **Code32** バーコード仕様でデコードされるように指定します |
| [CODE_39](#CODE-39) | データは **Code 39** 基本文字セットのバーコード仕様でデコードされるように指定します: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | データは **Code 39** フル ASCII 文字セットのバーコード仕様でデコードされるように指定します: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | データは **CODE 93** バーコード仕様でデコードされるように指定します |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | データは **CompactPdf417** (Pdf417Truncated) バーコード仕様でデコードされるように指定します |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | データは **GS1 DATABAR expanded** バーコード仕様でデコードされるように指定します |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | データは **GS1 DATABAR expanded stacked** バーコード仕様でデコードされるように指定します |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | データは **GS1 DATABAR limited** バーコード仕様でデコードされるように指定します |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | データは **GS1 DATABAR omni-directional** バーコード仕様でデコードされるように指定します |
| [DATABAR_STACKED](#DATABAR-STACKED) | データは **GS1 DATABAR stacked** バーコード仕様でデコードされるように指定します |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | データは **GS1 DATABAR stacked omni-directional** バーコード仕様でデコードされるように指定します |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | データは **GS1 DATABAR truncated** バーコード仕様でデコードされるように指定します |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | データは **DataLogic 2 of 5** バーコード仕様でデコードされるように指定します |
| [DATA_MATRIX](#DATA-MATRIX) | データは **DataMatrix** バーコードシンボロジーでデコードされるように指定します |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | データは **DeutschePost Ident code** バーコード仕様でデコードされるように指定します |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | データは **DeutschePost Leit code** バーコード仕様でデコードされるように指定します |
| [DOT_CODE](#DOT-CODE) | データは **DotCode** バーコード仕様でデコードされるように指定します |
| [DUTCH_KIX](#DUTCH-KIX) | データは **DotCode** バーコード仕様でデコードされるように指定します |
| [EAN_13](#EAN-13) | データは **EAN-13** バーコード仕様でデコードされるように指定します |
| [EAN_14](#EAN-14) | データを **EAN14** バーコード仕様でデコードすることを指定します |
| [EAN_8](#EAN-8) | データを **EAN-8** バーコード仕様でデコードすることを指定します |
| [GS_1_AZTEC](#GS-1-AZTEC) | データを **GS1 Aztec** バーコード仕様でデコードすることを指定します |
| [GS_1_CODE_128](#GS-1-CODE-128) | データを **GS1 CODE 128** バーコード仕様でデコードすることを指定します |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | データを **GS1 Composite Bar** バーコード仕様でデコードすることを指定します |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | データを **GS1DataMatrix** バーコードシンボルでデコードすることを指定します |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | データを **GS1 DotCode** バーコード仕様でデコードすることを指定します |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | データを **GS1 Han Xin Code** バーコード仕様でデコードすることを指定します |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | データを **MicroPdf417** バーコード仕様でデコードすることを指定します |
| [GS_1_QR](#GS-1-QR) | データを **GS1 QR** バーコード仕様でデコードすることを指定します |
| [HAN_XIN](#HAN-XIN) | データを **Han Xin Code** バーコード仕様でデコードすることを指定します |
| [HIBCQRLIC](#HIBCQRLIC) | データを **HIBC LIC QR** バーコード仕様でデコードすることを指定します |
| [HIBCQRPAS](#HIBCQRPAS) | データを **HIBC PAS QR** バーコード仕様でデコードすることを指定します |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | データを **HIBC LIC Aztec** バーコード仕様でデコードすることを指定します |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | データを **HIBC PAS Aztec** バーコード仕様でデコードすることを指定します |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | データを **HIBC LIC Code128** バーコード仕様でデコードすることを指定します |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | データを **HIBC PAS Code128** バーコード仕様でデコードすることを指定します |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | データを **HIBC LIC Code39** バーコード仕様でデコードすることを指定します |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | データを **HIBC PAS Code39** バーコード仕様でデコードすることを指定します |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | データを **HIBC LIC DataMatrix** バーコード仕様でデコードすることを指定します |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | データを **HIBC PAS DataMatrix** バーコード仕様でデコードすることを指定します |
| [IATA_2_OF_5](#IATA-2-OF-5) | データを **IATA 2 of 5** バーコード仕様でデコードすることを指定します。 |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | データを **INTERLEAVED 2 of 5** バーコード仕様でデコードすることを指定します |
| [ISBN](#ISBN) | データを **ISBN** バーコード仕様でデコードすることを指定します |
| [ISMN](#ISMN) | データを **ISMN** バーコード仕様でデコードすることを指定します |
| [ISSN](#ISSN) | データは **ISSN** バーコード仕様でデコードされることを指定します |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | データは **Italian Post 25** バーコード仕様でデコードされることを指定します |
| [ITF_14](#ITF-14) | データは **ITF14** バーコード仕様でデコードされることを指定します |
| [ITF_6](#ITF-6) | データは **ITF6** バーコード仕様でデコードされることを指定します |
| [MACRO_PDF_417](#MACRO-PDF-417) | データは **MacroPdf417** バーコード仕様でデコードされることを指定します |
| [MAILMARK](#MAILMARK) | データは **Royal Mail Mailmark** バーコード仕様でデコードされることを指定します。 |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | データは **Matrix 2 of 5** バーコード仕様でデコードされることを指定します |
| [MAXI_CODE](#MAXI-CODE) | データは **MaxiCode** バーコード仕様でデコードされることを指定します |
| [MICRO_PDF_417](#MICRO-PDF-417) | データは **MicroPdf417** バーコード仕様でデコードされることを指定します |
| [MICRO_QR](#MICRO-QR) | データは **MicroQR Code** バーコード仕様でデコードされることを指定します |
| [MICR_E_13_B](#MICR-E-13-B) | データは **MICR E-13B** バーコード仕様でデコードされることを指定します |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | データは最も一般的に使用されるシンボルでチェックされることを指定します |
| [MSI](#MSI) | データは **MSI Plessey** バーコード仕様でデコードされることを指定します |
| [NONE](#NONE) | デコードタイプが未指定です。 |
| [ONE_CODE](#ONE-CODE) | データは USPS **OneCode** バーコード仕様でデコードされることを指定します |
| [OPC](#OPC) | データは **OPC** バーコード仕様でデコードされることを指定します |
| [PATCH_CODE](#PATCH-CODE) | データは **Patch code** バーコード仕様でデコードされることを指定します。 |
| [PDF_417](#PDF-417) | データは **Pdf417** バーコードシンボルでデコードされることを指定します |
| [PHARMACODE](#PHARMACODE) | データは **Pharmacode** バーコードでデコードされることを指定します。 |
| [PLANET](#PLANET) | データは **Planet** バーコード仕様でデコードされることを指定します |
| [POSTAL_TYPES](#POSTAL-TYPES) | データは **1.5D POSTAL** バーコードシンボルすべてでチェックされます。例えば **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** のように。 |
| [POSTNET](#POSTNET) | データは **Postnet** バーコード仕様でデコードされることを指定します |
| [PZN](#PZN) | データは **PZN** バーコード仕様でデコードされることを指定します。 |
| [QR](#QR) | データは **QR Code** バーコード仕様でデコードされることを指定します |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | データは **RectMicroQR (rMQR) Code** バーコード仕様でデコードされることを指定します |
| [RM_4_SCC](#RM-4-SCC) | データは **RM4SCC** バーコード仕様でデコードされることを指定します。 |
| [SCC_14](#SCC-14) | データは **SCC14** バーコード仕様でデコードされることを指定します |
| [SSCC_18](#SSCC-18) | データは **SSCC18** バーコード仕様でデコードされることを指定します |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | データは **Standard 2 of 5** バーコード仕様でデコードされることを指定します |
| [SUPPLEMENT](#SUPPLEMENT) | データは **Supplement(EAN2, EAN5)** バーコード仕様でデコードされることを指定します |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | データは **Swiss Post Parcel Barcode** バーコード仕様でデコードされることを指定します |
| [TYPES_1D](#TYPES-1D) | データはすべての **1D** バーコードシンボルでチェックされることを指定します |
| [TYPES_2D](#TYPES-2D) | データはすべての **2D** バーコードシンボルでチェックされることを指定します |
| [UPCA](#UPCA) | データは **UPC-A** バーコード仕様でデコードされることを指定します |
| [UPCE](#UPCE) | データは **UPC-E** バーコード仕様でデコードされることを指定します |
| [VIN](#VIN) | データは **VIN**（Vehicle Identification Number）バーコード仕様でデコードされることを指定します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | AllSupportedTypes を表す配列を取得します |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | デコードタイプの名前の配列を取得します。 |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 指定された BaseDecodeType が 1D バーコードシンボルを含むかどうかを判定します |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 指定された BaseDecodeType が 2D バーコードシンボルを含むかどうかを判定します |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 指定された BaseDecodeType が郵便バーコードシンボルを含むかどうかを判定します |
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


データは **Australia Post** バーコード仕様でデコードされるように指定します

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


データは **Aztec** バーコード仕様でデコードされるように指定します

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


データは **CODABAR** バーコード仕様でデコードされるように指定します

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


データは **CodablockF** バーコード仕様でデコードされるように指定します

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


データは **CODE 11** バーコード仕様でデコードされるように指定します

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


データは **CODE 128** バーコード仕様でデコードされるように指定します

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


データは **SCode16K** バーコード仕様でデコードされるように指定します

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


データは **Code32** バーコード仕様でデコードされるように指定します

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


データは **Code 39** 基本文字セットのバーコード仕様でデコードされるように指定します: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


データは **Code 39** フル ASCII 文字セットのバーコード仕様でデコードされるように指定します: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


データは **CODE 93** バーコード仕様でデコードされるように指定します

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


データは **CompactPdf417** (Pdf417Truncated) バーコード仕様でデコードされるように指定します

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


データは **GS1 DATABAR expanded** バーコード仕様でデコードされるように指定します

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


データは **GS1 DATABAR expanded stacked** バーコード仕様でデコードされるように指定します

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


データは **GS1 DATABAR limited** バーコード仕様でデコードされるように指定します

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


データは **GS1 DATABAR omni-directional** バーコード仕様でデコードされるように指定します

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


データは **GS1 DATABAR stacked** バーコード仕様でデコードされるように指定します

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


データは **GS1 DATABAR stacked omni-directional** バーコード仕様でデコードされるように指定します

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


データは **GS1 DATABAR truncated** バーコード仕様でデコードされるように指定します

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


データは **DataLogic 2 of 5** バーコード仕様でデコードされるように指定します

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


データは **DataMatrix** バーコードシンボロジーでデコードされるように指定します

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


データは **DeutschePost Ident code** バーコード仕様でデコードされるように指定します

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


データは **DeutschePost Leit code** バーコード仕様でデコードされるように指定します

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


データは **DotCode** バーコード仕様でデコードされるように指定します

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


データは **DotCode** バーコード仕様でデコードされるように指定します

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


データは **EAN-13** バーコード仕様でデコードされるように指定します

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


データを **EAN14** バーコード仕様でデコードすることを指定します

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


データを **EAN-8** バーコード仕様でデコードすることを指定します

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


データを **GS1 Aztec** バーコード仕様でデコードすることを指定します

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


データを **GS1 CODE 128** バーコード仕様でデコードすることを指定します

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


データを **GS1 Composite Bar** バーコード仕様でデコードすることを指定します

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


データを **GS1DataMatrix** バーコードシンボルでデコードすることを指定します

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


データを **GS1 DotCode** バーコード仕様でデコードすることを指定します

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


データを **GS1 Han Xin Code** バーコード仕様でデコードすることを指定します

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


データを **MicroPdf417** バーコード仕様でデコードすることを指定します

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


データを **GS1 QR** バーコード仕様でデコードすることを指定します

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


データを **Han Xin Code** バーコード仕様でデコードすることを指定します

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


データを **HIBC LIC QR** バーコード仕様でデコードすることを指定します

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


データを **HIBC PAS QR** バーコード仕様でデコードすることを指定します

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


データを **HIBC LIC Aztec** バーコード仕様でデコードすることを指定します

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


データを **HIBC PAS Aztec** バーコード仕様でデコードすることを指定します

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


データを **HIBC LIC Code128** バーコード仕様でデコードすることを指定します

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


データを **HIBC PAS Code128** バーコード仕様でデコードすることを指定します

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


データを **HIBC LIC Code39** バーコード仕様でデコードすることを指定します

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


データを **HIBC PAS Code39** バーコード仕様でデコードすることを指定します

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


データを **HIBC LIC DataMatrix** バーコード仕様でデコードすることを指定します

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


データを **HIBC PAS DataMatrix** バーコード仕様でデコードすることを指定します

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


データは **IATA 2 of 5** バーコード仕様でデコードされることを指定します。IATA（International Air Transport Association）は航空貨物の管理にこのバーコードを使用します。

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


データを **INTERLEAVED 2 of 5** バーコード仕様でデコードすることを指定します

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


データを **ISBN** バーコード仕様でデコードすることを指定します

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


データを **ISMN** バーコード仕様でデコードすることを指定します

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


データは **ISSN** バーコード仕様でデコードされることを指定します

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


データは **Italian Post 25** バーコード仕様でデコードされることを指定します

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


データは **ITF14** バーコード仕様でデコードされることを指定します

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


データは **ITF6** バーコード仕様でデコードされることを指定します

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


データは **MacroPdf417** バーコード仕様でデコードされることを指定します

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


データは **Royal Mail Mailmark** バーコード仕様でデコードされることを指定します。

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


データは **Matrix 2 of 5** バーコード仕様でデコードされることを指定します

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


データは **MaxiCode** バーコード仕様でデコードされることを指定します

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


データは **MicroPdf417** バーコード仕様でデコードされることを指定します

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


データは **MicroQR Code** バーコード仕様でデコードされることを指定します

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


データは **MICR E-13B** バーコード仕様でデコードされることを指定します

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


データは最も一般的に使用されるシンボルでチェックされることを指定します

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


データは **MSI Plessey** バーコード仕様でデコードされることを指定します

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


デコードタイプが未指定です。

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


データは USPS **OneCode** バーコード仕様でデコードされることを指定します

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


データは **OPC** バーコード仕様でデコードされることを指定します

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


データは **Patch code** バーコード仕様でデコードされることを指定します。バーコードシンボルは自動スキャンに使用されます

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


データは **Pdf417** バーコードシンボルでデコードされることを指定します

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


データは **Pharmacode** バーコードでデコードされることを指定します。このシンボルは Pharmaceutical BINARY Code とも呼ばれます

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


データは **Planet** バーコード仕様でデコードされることを指定します

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


データは **1.5D POSTAL** バーコードシンボルすべてでチェックされます。例えば **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** のように。

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


データは **Postnet** バーコード仕様でデコードされることを指定します

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


データは **PZN** バーコード仕様でデコードされることを指定します。このシンボルは Pharma Zentral Nummer とも呼ばれます。PZN7 と PZN8 がサポートされています。

### QR {#QR}
```
public static final SingleDecodeType QR
```


データは **QR Code** バーコード仕様でデコードされることを指定します

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


データは **RectMicroQR (rMQR) Code** バーコード仕様でデコードされることを指定します

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


データは **RM4SCC** バーコード仕様でデコードされることを指定します。RM4SCC（Royal Mail 4-state Customer Code）は英国の自動郵便仕分けプロセスで使用されます。

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


データは **SCC14** バーコード仕様でデコードされることを指定します

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


データは **SSCC18** バーコード仕様でデコードされることを指定します

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


データは **Standard 2 of 5** バーコード仕様でデコードされることを指定します

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


データは **Supplement(EAN2, EAN5)** バーコード仕様でデコードされることを指定します

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


データは **Swiss Post Parcel Barcode** バーコード仕様でデコードされることを指定します

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


データはすべての **1D** バーコードシンボルでチェックされることを指定します

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


データはすべての **2D** バーコードシンボルでチェックされることを指定します

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


データは **UPC-A** バーコード仕様でデコードされることを指定します

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


データは **UPC-E** バーコード仕様でデコードされることを指定します

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


データは **VIN**（Vehicle Identification Number）バーコード仕様でデコードされることを指定します

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
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


デコードタイプの名前の配列を取得します。

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


指定された BaseDecodeType が 1D バーコードシンボルを含むかどうかを判定します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | テスト対象の BaseDecodeType。 |

**Returns:**
boolean - BaseDecodeType が任意の 1D バーコードシンボロジーを含む場合は **true** を返し、そうでない場合は **false** を返します。
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


指定された BaseDecodeType が 2D バーコードシンボルを含むかどうかを判定します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | テスト対象の BaseDecodeType。 |

**Returns:**
boolean - BaseDecodeTypeddddddddw が任意の 2D バーコードシンボロジーを含む場合は **true** を返し、そうでない場合は **false** を返します。
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


指定された BaseDecodeType が郵便バーコードシンボルを含むかどうかを判定します

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | テスト対象の BaseDecodeType |

**Returns:**
boolean - BaseDecodeType が任意の郵便バーコードシンボロジーを含む場合は **true** を返し、そうでない場合は **false** を返します。
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための SingleDecodeType 表現を含む文字列。 |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

それ以外の場合は不定型を返します。あるいは SingleDecodeType (-1, "NONE")。
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


SingleDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための、\"EAN8\"、\"EAN13\"、\"CodaBar\" などの形式の SingleDecodeType を含む文字列。 |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - s が正常に変換された場合は **true**、それ以外は **false**。
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


barcodeTypes によってスキャンセットを指定します

**Parameters:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための文字列で、形式は "AllSupportedTypes" または "EAN8,EAN13,CodaBar" のいずれかです。 |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully; otherwise it returns indefinite type: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | java.lang.String | 変換するための、\"EAN8\"、\"EAN13\"、\"CodaBar\" などの形式の SingleDecodeType を含む文字列。 |

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

