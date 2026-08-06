---
title: DecodeType
second_title: Aspose.BarCode for Android via Java API Reference
description: 읽을 바코드 유형을 지정합니다.
type: docs
weight: 32
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

읽을 바코드 유형을 지정합니다.

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

| Constructor | 설명 |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | 데이터가 사용 가능한 모든 심볼로지를 사용하여 검사된다고 지정합니다. |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | 데이터를 **Australian Post Domestic eParcel Barcode** 바코드 사양으로 디코딩해야 함을 지정합니다. |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | 데이터를 **Australia Post** 바코드 사양으로 디코딩해야 함을 지정합니다. |
| [AZTEC](#AZTEC) | 데이터를 **Aztec** 바코드 사양으로 디코딩해야 함을 지정합니다. |
| [CODABAR](#CODABAR) | 데이터를 **CODABAR** 바코드 사양으로 디코딩해야 함을 지정합니다. |
| [CODABLOCK_F](#CODABLOCK-F) | 데이터를 **CodablockF** 바코드 사양으로 디코딩해야 함을 지정합니다. |
| [CODE_11](#CODE-11) | 데이터를 **CODE 11** 바코드 사양으로 디코딩해야 함을 지정합니다. |
| [CODE_128](#CODE-128) | 데이터를 **CODE 128** 바코드 사양으로 디코딩하도록 지정합니다 |
| [CODE_16_K](#CODE-16-K) | 데이터를 **SCode16K** 바코드 사양으로 디코딩하도록 지정합니다 |
| [CODE_32](#CODE-32) | 데이터를 **Code32** 바코드 사양으로 디코딩하도록 지정합니다 |
| [CODE_39](#CODE-39) | 데이터를 **Code 39** 기본 문자 집합 바코드 사양(ISO/IEC 16388)으로 디코딩하도록 지정합니다 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | 데이터를 **Code 39** 전체 ASCII 문자 집합 바코드 사양(ISO/IEC 16388)으로 디코딩하도록 지정합니다 |
| [CODE_93](#CODE-93) | 데이터를 **CODE 93** 바코드 사양으로 디코딩하도록 지정합니다 |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | 데이터를 **CompactPdf417** (Pdf417Truncated) 바코드 사양으로 디코딩하도록 지정합니다 |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | 데이터를 **GS1 DATABAR expanded** 바코드 사양으로 디코딩하도록 지정합니다 |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | 데이터를 **GS1 DATABAR expanded stacked** 바코드 사양으로 디코딩하도록 지정합니다 |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | 데이터를 **GS1 DATABAR limited** 바코드 사양으로 디코딩하도록 지정합니다 |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | 데이터를 **GS1 DATABAR omni-directional** 바코드 사양으로 디코딩하도록 지정합니다 |
| [DATABAR_STACKED](#DATABAR-STACKED) | 데이터를 **GS1 DATABAR stacked** 바코드 사양으로 디코딩하도록 지정합니다 |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | 데이터를 **GS1 DATABAR stacked omni-directional** 바코드 사양으로 디코딩하도록 지정합니다 |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | 데이터를 **GS1 DATABAR truncated** 바코드 사양으로 디코딩하도록 지정합니다 |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | 데이터를 **DataLogic 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다 |
| [DATA_MATRIX](#DATA-MATRIX) | 데이터를 **DataMatrix** 바코드 심볼로 디코딩하도록 지정합니다 |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | 데이터를 **DeutschePost Ident code** 바코드 사양으로 디코딩하도록 지정합니다 |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | 데이터를 **DeutschePost Leit code** 바코드 사양으로 디코딩하도록 지정합니다 |
| [DOT_CODE](#DOT-CODE) | 데이터를 **DotCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| [DUTCH_KIX](#DUTCH-KIX) | 데이터를 **DotCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| [EAN_13](#EAN-13) | 데이터를 **EAN-13** 바코드 사양으로 디코딩하도록 지정합니다 |
| [EAN_14](#EAN-14) | 데이터를 **EAN14** 바코드 사양으로 디코딩하도록 지정합니다 |
| [EAN_8](#EAN-8) | 데이터를 **EAN-8** 바코드 사양으로 디코딩하도록 지정합니다 |
| [GS_1_AZTEC](#GS-1-AZTEC) | 데이터를 **GS1 Aztec** 바코드 사양으로 디코딩하도록 지정합니다 |
| [GS_1_CODE_128](#GS-1-CODE-128) | 데이터를 **GS1 CODE 128** 바코드 사양으로 디코딩하도록 지정합니다 |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | 데이터를 **GS1 Composite Bar** 바코드 사양으로 디코딩하도록 지정합니다 |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | 데이터를  **GS1DataMatrix**  바코드 심볼로 디코딩하도록 지정합니다 |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | 데이터를  **GS1 DotCode**  바코드 사양으로 디코딩하도록 지정합니다 |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | 데이터를 **GS1 Han Xin Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | 데이터를 **MicroPdf417** 바코드 사양으로 디코딩하도록 지정합니다 |
| [GS_1_QR](#GS-1-QR) | 데이터를  **GS1 QR**  바코드 사양으로 디코딩하도록 지정합니다 |
| [HAN_XIN](#HAN-XIN) | 데이터를 **Han Xin Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| [HIBCQRLIC](#HIBCQRLIC) | 데이터를  **HIBC LIC QR**  바코드 사양으로 디코딩하도록 지정합니다 |
| [HIBCQRPAS](#HIBCQRPAS) | 데이터를  **HIBC PAS QR**  바코드 사양으로 디코딩하도록 지정합니다 |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | 데이터를  **HIBC LIC Aztec**  바코드 사양으로 디코딩하도록 지정합니다 |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | 데이터를  **HIBC PAS Aztec**  바코드 사양으로 디코딩하도록 지정합니다 |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | 데이터를  **HIBC LIC Code128**  바코드 사양으로 디코딩하도록 지정합니다 |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | 데이터를  **HIBC PAS Code128**  바코드 사양으로 디코딩하도록 지정합니다 |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | 데이터를  **HIBC LIC Code39**  바코드 사양으로 디코딩하도록 지정합니다 |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | 데이터를  **HIBC PAS Code39**  바코드 사양으로 디코딩하도록 지정합니다 |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | 데이터를  **HIBC LIC DataMatrix**  바코드 사양으로 디코딩하도록 지정합니다 |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | 데이터를  **HIBC PAS DataMatrix**  바코드 사양으로 디코딩하도록 지정합니다 |
| [IATA_2_OF_5](#IATA-2-OF-5) | 데이터를  **IATA 2 of 5**  바코드 사양으로 디코딩하도록 지정합니다. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | 데이터를  **INTERLEAVED 2 of 5**  바코드 사양으로 디코딩하도록 지정합니다 |
| [ISBN](#ISBN) | 데이터를  **ISBN**  바코드 사양으로 디코딩하도록 지정합니다 |
| [ISMN](#ISMN) | 데이터를  **ISMN**  바코드 사양으로 디코딩하도록 지정합니다 |
| [ISSN](#ISSN) | 데이터를  **ISSN**  바코드 사양으로 디코딩하도록 지정합니다 |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | 데이터를  **Italian Post 25**  바코드 사양으로 디코딩하도록 지정합니다 |
| [ITF_14](#ITF-14) | 데이터를  **ITF14**  바코드 사양으로 디코딩하도록 지정합니다 |
| [ITF_6](#ITF-6) | 데이터를  **ITF6**  바코드 사양으로 디코딩하도록 지정합니다 |
| [MACRO_PDF_417](#MACRO-PDF-417) | 데이터를  **MacroPdf417**  바코드 사양으로 디코딩하도록 지정합니다 |
| [MAILMARK](#MAILMARK) | 데이터를 **Royal Mail Mailmark** 바코드 사양으로 디코딩하도록 지정합니다. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | 데이터를 **Matrix 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다 |
| [MAXI_CODE](#MAXI-CODE) | 데이터를 **MaxiCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| [MICRO_PDF_417](#MICRO-PDF-417) | 데이터를 **MicroPdf417** 바코드 사양으로 디코딩하도록 지정합니다 |
| [MICRO_QR](#MICRO-QR) | 데이터를 **MicroQR Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| [MICR_E_13_B](#MICR-E-13-B) | 데이터를 **MICR E-13B** 바코드 사양으로 디코딩하도록 지정합니다 |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | 데이터가 가장 일반적으로 사용되는 심볼로 검사되도록 지정합니다 |
| [MSI](#MSI) | 데이터를 **MSI Plessey** 바코드 사양으로 디코딩하도록 지정합니다 |
| [NONE](#NONE) | 지정되지 않은 디코드 유형입니다. |
| [ONE_CODE](#ONE-CODE) | 데이터를 USPS **OneCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| [OPC](#OPC) | 데이터를 **OPC** 바코드 사양으로 디코딩하도록 지정합니다 |
| [PATCH_CODE](#PATCH-CODE) | 데이터를 **Patch code** 바코드 사양으로 디코딩하도록 지정합니다. |
| [PDF_417](#PDF-417) | 데이터를 **Pdf417** 바코드 심볼로 디코딩하도록 지정합니다 |
| [PHARMACODE](#PHARMACODE) | 데이터를 **Pharmacode** 바코드로 디코딩하도록 지정합니다. |
| [PLANET](#PLANET) | 데이터를 **Planet** 바코드 사양으로 디코딩하도록 지정합니다 |
| [POSTAL_TYPES](#POSTAL-TYPES) | 데이터가 **1.5D POSTAL** 바코드 심볼 전체와 **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**와 같은 심볼을 사용하여 검사되도록 지정합니다 |
| [POSTNET](#POSTNET) | 데이터를 **Postnet** 바코드 사양으로 디코딩하도록 지정합니다 |
| [PZN](#PZN) | 데이터를 **PZN** 바코드 사양으로 디코딩하도록 지정합니다. |
| [QR](#QR) | 데이터를 **QR Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | 데이터를 **RectMicroQR (rMQR) Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| [RM_4_SCC](#RM-4-SCC) | 데이터를 **RM4SCC** 바코드 사양으로 디코딩하도록 지정합니다. |
| [SCC_14](#SCC-14) | 데이터를 **SCC14** 바코드 사양으로 디코딩하도록 지정합니다 |
| [SSCC_18](#SSCC-18) | 데이터를 **SSCC18** 바코드 사양으로 디코딩하도록 지정합니다 |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | 데이터를 **Standard 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다 |
| [SUPPLEMENT](#SUPPLEMENT) | 데이터를 **Supplement(EAN2, EAN5)** 바코드 사양으로 디코딩하도록 지정합니다 |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | 데이터를 **Swiss Post Parcel Barcode** 바코드 사양으로 디코딩하도록 지정합니다. |
| [TYPES_1D](#TYPES-1D) | 데이터를 **1D** 바코드 심볼로지 전부로 검사하도록 지정합니다. |
| [TYPES_2D](#TYPES-2D) | 데이터를 **2D** 바코드 심볼로지 전부로 검사하도록 지정합니다. |
| [UPCA](#UPCA) | 데이터를 **UPC-A** 바코드 사양으로 디코딩하도록 지정합니다. |
| [UPCE](#UPCE) | 데이터를 **UPC-E** 바코드 사양으로 디코딩하도록 지정합니다. |
| [VIN](#VIN) | 데이터를 **VIN** (Vehicle Identification Number) 바코드 사양으로 디코딩하도록 지정합니다. |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | AllSupportedTypes를 나타내는 배열을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | 디코드 유형 이름들의 배열을 검색합니다. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 지정된 BaseDecodeType에 1D 바코드 심볼로지가 포함되어 있는지 확인합니다. |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 지정된 BaseDecodeType에 2D 바코드 심볼로지가 포함되어 있는지 확인합니다. |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 지정된 BaseDecodeType에 우편 바코드 심볼로지가 포함되어 있는지 확인합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | barcodeTypes별로 스캔 세트를 지정합니다. |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. |
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


데이터가 사용 가능한 모든 심볼로지를 사용하여 검사된다고 지정합니다.

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


데이터를 **Australian Post Domestic eParcel Barcode** 바코드 사양으로 디코딩해야 함을 지정합니다.

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


데이터를 **Australia Post** 바코드 사양으로 디코딩해야 함을 지정합니다.

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


데이터를 **Aztec** 바코드 사양으로 디코딩해야 함을 지정합니다.

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


데이터를 **CODABAR** 바코드 사양으로 디코딩해야 함을 지정합니다.

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


데이터를 **CodablockF** 바코드 사양으로 디코딩해야 함을 지정합니다.

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


데이터를 **CODE 11** 바코드 사양으로 디코딩해야 함을 지정합니다.

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


데이터를 **CODE 128** 바코드 사양으로 디코딩하도록 지정합니다

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


데이터를 **SCode16K** 바코드 사양으로 디코딩하도록 지정합니다

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


데이터를 **Code32** 바코드 사양으로 디코딩하도록 지정합니다

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


데이터를 **Code 39** 기본 문자 집합 바코드 사양(ISO/IEC 16388)으로 디코딩하도록 지정합니다

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


데이터를 **Code 39** 전체 ASCII 문자 집합 바코드 사양(ISO/IEC 16388)으로 디코딩하도록 지정합니다

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


데이터를 **CODE 93** 바코드 사양으로 디코딩하도록 지정합니다

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


데이터를 **CompactPdf417** (Pdf417Truncated) 바코드 사양으로 디코딩하도록 지정합니다

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


데이터를 **GS1 DATABAR expanded** 바코드 사양으로 디코딩하도록 지정합니다

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


데이터를 **GS1 DATABAR expanded stacked** 바코드 사양으로 디코딩하도록 지정합니다

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


데이터를 **GS1 DATABAR limited** 바코드 사양으로 디코딩하도록 지정합니다

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


데이터를 **GS1 DATABAR omni-directional** 바코드 사양으로 디코딩하도록 지정합니다

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


데이터를 **GS1 DATABAR stacked** 바코드 사양으로 디코딩하도록 지정합니다

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


데이터를 **GS1 DATABAR stacked omni-directional** 바코드 사양으로 디코딩하도록 지정합니다

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


데이터를 **GS1 DATABAR truncated** 바코드 사양으로 디코딩하도록 지정합니다

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


데이터를 **DataLogic 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


데이터를 **DataMatrix** 바코드 심볼로 디코딩하도록 지정합니다

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


데이터를 **DeutschePost Ident code** 바코드 사양으로 디코딩하도록 지정합니다

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


데이터를 **DeutschePost Leit code** 바코드 사양으로 디코딩하도록 지정합니다

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


데이터를 **DotCode** 바코드 사양으로 디코딩하도록 지정합니다

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


데이터를 **DotCode** 바코드 사양으로 디코딩하도록 지정합니다

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


데이터를 **EAN-13** 바코드 사양으로 디코딩하도록 지정합니다

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


데이터를 **EAN14** 바코드 사양으로 디코딩하도록 지정합니다

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


데이터를 **EAN-8** 바코드 사양으로 디코딩하도록 지정합니다

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


데이터를 **GS1 Aztec** 바코드 사양으로 디코딩하도록 지정합니다

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


데이터를 **GS1 CODE 128** 바코드 사양으로 디코딩하도록 지정합니다

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


데이터를 **GS1 Composite Bar** 바코드 사양으로 디코딩하도록 지정합니다

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


데이터를  **GS1DataMatrix**  바코드 심볼로 디코딩하도록 지정합니다

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


데이터를  **GS1 DotCode**  바코드 사양으로 디코딩하도록 지정합니다

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


데이터를 **GS1 Han Xin Code** 바코드 사양으로 디코딩하도록 지정합니다

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


데이터를 **MicroPdf417** 바코드 사양으로 디코딩하도록 지정합니다

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


데이터를  **GS1 QR**  바코드 사양으로 디코딩하도록 지정합니다

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


데이터를 **Han Xin Code** 바코드 사양으로 디코딩하도록 지정합니다

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


데이터를  **HIBC LIC QR**  바코드 사양으로 디코딩하도록 지정합니다

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


데이터를  **HIBC PAS QR**  바코드 사양으로 디코딩하도록 지정합니다

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


데이터를  **HIBC LIC Aztec**  바코드 사양으로 디코딩하도록 지정합니다

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


데이터를  **HIBC PAS Aztec**  바코드 사양으로 디코딩하도록 지정합니다

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


데이터를  **HIBC LIC Code128**  바코드 사양으로 디코딩하도록 지정합니다

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


데이터를  **HIBC PAS Code128**  바코드 사양으로 디코딩하도록 지정합니다

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


데이터를  **HIBC LIC Code39**  바코드 사양으로 디코딩하도록 지정합니다

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


데이터를  **HIBC PAS Code39**  바코드 사양으로 디코딩하도록 지정합니다

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


데이터를  **HIBC LIC DataMatrix**  바코드 사양으로 디코딩하도록 지정합니다

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


데이터를  **HIBC PAS DataMatrix**  바코드 사양으로 디코딩하도록 지정합니다

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


데이터를 **IATA 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다. IATA (International Air Transport Association)는 이 바코드를 항공 화물 관리에 사용합니다.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


데이터를  **INTERLEAVED 2 of 5**  바코드 사양으로 디코딩하도록 지정합니다

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


데이터를  **ISBN**  바코드 사양으로 디코딩하도록 지정합니다

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


데이터를  **ISMN**  바코드 사양으로 디코딩하도록 지정합니다

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


데이터를  **ISSN**  바코드 사양으로 디코딩하도록 지정합니다

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


데이터를  **Italian Post 25**  바코드 사양으로 디코딩하도록 지정합니다

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


데이터를  **ITF14**  바코드 사양으로 디코딩하도록 지정합니다

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


데이터를  **ITF6**  바코드 사양으로 디코딩하도록 지정합니다

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


데이터를  **MacroPdf417**  바코드 사양으로 디코딩하도록 지정합니다

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


데이터를 **Royal Mail Mailmark** 바코드 사양으로 디코딩하도록 지정합니다.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


데이터를 **Matrix 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


데이터를 **MaxiCode** 바코드 사양으로 디코딩하도록 지정합니다

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


데이터를 **MicroPdf417** 바코드 사양으로 디코딩하도록 지정합니다

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


데이터를 **MicroQR Code** 바코드 사양으로 디코딩하도록 지정합니다

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


데이터를 **MICR E-13B** 바코드 사양으로 디코딩하도록 지정합니다

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


데이터가 가장 일반적으로 사용되는 심볼로 검사되도록 지정합니다

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


데이터를 **MSI Plessey** 바코드 사양으로 디코딩하도록 지정합니다

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


지정되지 않은 디코드 유형입니다.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


데이터를 USPS **OneCode** 바코드 사양으로 디코딩하도록 지정합니다

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


데이터를 **OPC** 바코드 사양으로 디코딩하도록 지정합니다

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


데이터를 **Patch code** 바코드 사양으로 디코딩하도록 지정합니다. 바코드 심볼로지는 자동 스캔에 사용됩니다.

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


데이터를 **Pdf417** 바코드 심볼로 디코딩하도록 지정합니다

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


데이터를 **Pharmacode** 바코드로 디코딩하도록 지정합니다. 이 심볼로지는 Pharmaceutical BINARY Code로도 알려져 있습니다.

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


데이터를 **Planet** 바코드 사양으로 디코딩하도록 지정합니다

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


데이터가 **1.5D POSTAL** 바코드 심볼 전체와 **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**와 같은 심볼을 사용하여 검사되도록 지정합니다

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


데이터를 **Postnet** 바코드 사양으로 디코딩하도록 지정합니다

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


데이터를 **PZN** 바코드 사양으로 디코딩하도록 지정합니다. 이 심볼로지는 Pharma Zentral Nummer로도 알려져 있으며, PZN7 및 PZN8을 지원합니다.

### QR {#QR}
```
public static final SingleDecodeType QR
```


데이터를 **QR Code** 바코드 사양으로 디코딩하도록 지정합니다

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


데이터를 **RectMicroQR (rMQR) Code** 바코드 사양으로 디코딩하도록 지정합니다

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


데이터를 **RM4SCC** 바코드 사양으로 디코딩하도록 지정합니다. RM4SCC (Royal Mail 4-state Customer Code)는 영국의 자동 우편 분류 과정에 사용됩니다.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


데이터를 **SCC14** 바코드 사양으로 디코딩하도록 지정합니다

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


데이터를 **SSCC18** 바코드 사양으로 디코딩하도록 지정합니다

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


데이터를 **Standard 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


데이터를 **Supplement(EAN2, EAN5)** 바코드 사양으로 디코딩하도록 지정합니다

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


데이터를 **Swiss Post Parcel Barcode** 바코드 사양으로 디코딩하도록 지정합니다.

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


데이터를 **1D** 바코드 심볼로지 전부로 검사하도록 지정합니다.

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


데이터를 **2D** 바코드 심볼로지 전부로 검사하도록 지정합니다.

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


데이터를 **UPC-A** 바코드 사양으로 디코딩하도록 지정합니다.

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


데이터를 **UPC-E** 바코드 사양으로 디코딩하도록 지정합니다.

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


데이터를 **VIN** (Vehicle Identification Number) 바코드 사양으로 디코딩하도록 지정합니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


AllSupportedTypes를 나타내는 배열을 가져옵니다.

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


디코드 유형 이름들의 배열을 검색합니다.

**Returns:**
java.lang.String[] - 디코드 유형 이름들의 문자열 배열입니다.
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


지정된 BaseDecodeType에 1D 바코드 심볼로지가 포함되어 있는지 확인합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 테스트할 BaseDecodeType입니다. |

**Returns:**
boolean - BaseDecodeType에 1D 바코드 심볼로지가 포함되어 있으면 **true**를 반환하고, 그렇지 않으면 **false**를 반환합니다.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


지정된 BaseDecodeType에 2D 바코드 심볼로지가 포함되어 있는지 확인합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 테스트할 BaseDecodeType입니다. |

**Returns:**
boolean - BaseDecodeTypeddddddddw에 2D 바코드 심볼로지가 포함되어 있으면 **true**를 반환하고, 그렇지 않으면 **false**를 반환합니다.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


지정된 BaseDecodeType에 우편 바코드 심볼로지가 포함되어 있는지 확인합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 테스트할 BaseDecodeType |

**Returns:**
boolean - BaseDecodeType에 우편 바코드 심볼로지가 포함되어 있으면 **true**를 반환하고, 그렇지 않으면 **false**를 반환합니다.
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


SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | 변환할 SingleDecodeType 표현을 포함하는 문자열입니다. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

그렇지 않으면 무한 타입을 반환합니다. 또는 SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | "EAN8" 또는 "EAN13" 또는 "CodaBar" 형식의 SingleDecodeType을 포함하는 문자열을 변환합니다. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - **true**는 s가 성공적으로 변환된 경우; 그렇지 않으면 **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


barcodeTypes별로 스캔 세트를 지정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 단일 및 다중 디코드 타입의 배열 |

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


MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | "AllSupportedTypes" 또는 "EAN8,EAN13,CodaBar" 형식의 문자열을 변환합니다. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - 변환이 성공적으로 완료되면 실제 MultiDecodeType이 반환됩니다; 그렇지 않으면 무한 타입을 반환합니다: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| parsingType | java.lang.String | "EAN8" 또는 "EAN13" 또는 "CodaBar" 형식의 SingleDecodeType을 포함하는 문자열을 변환합니다. |

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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

