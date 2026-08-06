---
title: DecodeType
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 指定要读取的条形码类型。
type: docs
weight: 32
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

指定要读取的条形码类型。

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

| Constructor | 描述 |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | 指定将使用所有可用的符号体系检查数据。 |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | 指定应使用  **Australian Post Domestic eParcel Barcode**  条形码规范解码数据 |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | 指定应使用  **Australia Post**  条形码规范解码数据 |
| [AZTEC](#AZTEC) | 指定应使用  **Aztec**  条形码规范解码数据 |
| [CODABAR](#CODABAR) | 指定应使用  **CODABAR**  条形码规范解码数据 |
| [CODABLOCK_F](#CODABLOCK-F) | 指定应使用  **CodablockF**  条形码规范解码数据 |
| [CODE_11](#CODE-11) | 指定应使用  **CODE 11**  条形码规范解码数据 |
| [CODE_128](#CODE-128) | 指定数据应使用 **CODE 128** 条形码规范进行解码 |
| [CODE_16_K](#CODE-16-K) | 指定数据应使用 **SCode16K** 条形码规范进行解码 |
| [CODE_32](#CODE-32) | 指定数据应使用 **Code32** 条形码规范进行解码 |
| [CODE_39](#CODE-39) | 指定数据应使用 **Code 39** 基本字符集条形码规范：ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | 指定数据应使用 **Code 39** 完整 ASCII 字符集条形码规范：ISO/IEC 16388 |
| [CODE_93](#CODE-93) | 指定数据应使用 **CODE 93** 条形码规范进行解码 |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | 指定数据应使用 **CompactPdf417**（Pdf417Truncated）条形码规范进行解码 |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | 指定数据应使用 **GS1 DATABAR expanded** 条形码规范进行解码 |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | 指定数据应使用 **GS1 DATABAR expanded stacked** 条形码规范进行解码 |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | 指定数据应使用 **GS1 DATABAR limited** 条形码规范进行解码 |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | 指定数据应使用 **GS1 DATABAR omni-directional** 条形码规范进行解码 |
| [DATABAR_STACKED](#DATABAR-STACKED) | 指定数据应使用 **GS1 DATABAR stacked** 条形码规范进行解码 |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | 指定数据应使用 **GS1 DATABAR stacked omni-directional** 条形码规范进行解码 |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | 指定数据应使用 **GS1 DATABAR truncated** 条形码规范进行解码 |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | 指定数据应使用 **DataLogic 2 of 5** 条形码规范进行解码 |
| [DATA_MATRIX](#DATA-MATRIX) | 指定数据应使用 **DataMatrix** 条形码符号进行解码 |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | 指定数据应使用 **DeutschePost Ident code** 条形码规范进行解码 |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | 指定数据应使用 **DeutschePost Leit code** 条形码规范进行解码 |
| [DOT_CODE](#DOT-CODE) | 指定数据应使用 **DotCode** 条形码规范进行解码 |
| [DUTCH_KIX](#DUTCH-KIX) | 指定数据应使用 **DotCode** 条形码规范进行解码 |
| [EAN_13](#EAN-13) | 指定数据应使用 **EAN-13** 条形码规范进行解码 |
| [EAN_14](#EAN-14) | 指定数据应使用 **EAN14** 条形码规范进行解码 |
| [EAN_8](#EAN-8) | 指定数据应使用 **EAN-8** 条形码规范进行解码 |
| [GS_1_AZTEC](#GS-1-AZTEC) | 指定数据应使用 **GS1 Aztec** 条形码规范进行解码 |
| [GS_1_CODE_128](#GS-1-CODE-128) | 指定数据应使用 **GS1 CODE 128** 条形码规范进行解码 |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | 指定数据应使用 **GS1 Composite Bar** 条形码规范进行解码 |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | 指定应使用 **GS1DataMatrix** 条形码符号进行解码 |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | 指定应使用 **GS1 DotCode** 条形码规范进行解码 |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | 指定应使用 **GS1 Han Xin Code** 条形码规范进行解码 |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | 指定应使用 **MicroPdf417** 条形码规范进行解码 |
| [GS_1_QR](#GS-1-QR) | 指定应使用 **GS1 QR** 条形码规范进行解码 |
| [HAN_XIN](#HAN-XIN) | 指定应使用 **Han Xin Code** 条形码规范进行解码 |
| [HIBCQRLIC](#HIBCQRLIC) | 指定应使用 **HIBC LIC QR** 条形码规范进行解码 |
| [HIBCQRPAS](#HIBCQRPAS) | 指定应使用 **HIBC PAS QR** 条形码规范进行解码 |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | 指定应使用 **HIBC LIC Aztec** 条形码规范进行解码 |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | 指定应使用 **HIBC PAS Aztec** 条形码规范进行解码 |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | 指定应使用 **HIBC LIC Code128** 条形码规范进行解码 |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | 指定应使用 **HIBC PAS Code128** 条形码规范进行解码 |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | 指定应使用 **HIBC LIC Code39** 条形码规范进行解码 |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | 指定应使用 **HIBC PAS Code39** 条形码规范进行解码 |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | 指定应使用 **HIBC LIC DataMatrix** 条形码规范进行解码 |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | 指定应使用 **HIBC PAS DataMatrix** 条形码规范进行解码 |
| [IATA_2_OF_5](#IATA-2-OF-5) | 指定应使用 **IATA 2 of 5** 条形码规范进行解码。 |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | 指定应使用 **INTERLEAVED 2 of 5** 条形码规范进行解码 |
| [ISBN](#ISBN) | 指定应使用 **ISBN** 条形码规范进行解码 |
| [ISMN](#ISMN) | 指定应使用 **ISMN** 条形码规范进行解码 |
| [ISSN](#ISSN) | 指定应使用 **ISSN** 条形码规范进行解码 |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | 指定应使用 **Italian Post 25** 条形码规范进行解码 |
| [ITF_14](#ITF-14) | 指定应使用 **ITF14** 条形码规范进行解码 |
| [ITF_6](#ITF-6) | 指定应使用 **ITF6** 条形码规范进行解码 |
| [MACRO_PDF_417](#MACRO-PDF-417) | 指定应使用 **MacroPdf417** 条形码规范进行解码 |
| [MAILMARK](#MAILMARK) | 指定应使用 **Royal Mail Mailmark** 条形码规范对数据进行解码。 |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | 指定应使用 **Matrix 2 of 5** 条形码规范对数据进行解码 |
| [MAXI_CODE](#MAXI-CODE) | 指定应使用 **MaxiCode** 条形码规范对数据进行解码 |
| [MICRO_PDF_417](#MICRO-PDF-417) | 指定应使用 **MicroPdf417** 条形码规范对数据进行解码 |
| [MICRO_QR](#MICRO-QR) | 指定应使用 **MicroQR Code** 条形码规范对数据进行解码 |
| [MICR_E_13_B](#MICR-E-13-B) | 指定应使用 **MICR E-13B** 条形码规范对数据进行解码 |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | 指定将使用最常用的符号集检查数据 |
| [MSI](#MSI) | 指定应使用 **MSI Plessey** 条形码规范对数据进行解码 |
| [NONE](#NONE) | 未指定的解码类型。 |
| [ONE_CODE](#ONE-CODE) | 指定应使用 USPS **OneCode** 条形码规范对数据进行解码 |
| [OPC](#OPC) | 指定应使用 **OPC** 条形码规范对数据进行解码 |
| [PATCH_CODE](#PATCH-CODE) | 指定应使用 **Patch code** 条形码规范对数据进行解码。 |
| [PDF_417](#PDF-417) | 指定应使用 **Pdf417** 条形码符号对数据进行解码 |
| [PHARMACODE](#PHARMACODE) | 指定应使用 **Pharmacode** 条形码对数据进行解码。 |
| [PLANET](#PLANET) | 指定应使用 **Planet** 条形码规范对数据进行解码 |
| [POSTAL_TYPES](#POSTAL-TYPES) | 指定将使用所有 **1.5D POSTAL** 条形码符号集检查数据，例如 **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | 指定应使用 **Postnet** 条形码规范对数据进行解码 |
| [PZN](#PZN) | 指定应使用 **PZN** 条形码规范对数据进行解码。 |
| [QR](#QR) | 指定应使用 **QR Code** 条形码规范对数据进行解码 |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | 指定应使用 **RectMicroQR (rMQR) Code** 条形码规范对数据进行解码 |
| [RM_4_SCC](#RM-4-SCC) | 指定应使用 **RM4SCC** 条形码规范对数据进行解码。 |
| [SCC_14](#SCC-14) | 指定应使用 **SCC14** 条形码规范对数据进行解码 |
| [SSCC_18](#SSCC-18) | 指定应使用 **SSCC18** 条形码规范对数据进行解码 |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | 指定应使用 **Standard 2 of 5** 条形码规范对数据进行解码 |
| [SUPPLEMENT](#SUPPLEMENT) | 指定应使用 **Supplement(EAN2, EAN5)** 条形码规范对数据进行解码 |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | 指定应使用 **Swiss Post Parcel Barcode** 条形码规范对数据进行解码 |
| [TYPES_1D](#TYPES-1D) | 指定将使用所有 **1D** 条形码符号检查数据 |
| [TYPES_2D](#TYPES-2D) | 指定将使用所有 **2D** 条形码符号检查数据 |
| [UPCA](#UPCA) | 指定应使用 **UPC-A** 条形码规范对数据进行解码 |
| [UPCE](#UPCE) | 指定应使用 **UPC-E** 条形码规范对数据进行解码 |
| [VIN](#VIN) | 指定应使用 **VIN**（Vehicle Identification Number）条形码规范对数据进行解码 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | 获取表示 AllSupportedTypes 的数组 |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | 检索解码类型名称的数组。 |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 确定指定的 BaseDecodeType 是否包含任何 1D 条形码符号 |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 确定指定的 BaseDecodeType 是否包含任何 2D 条形码符号 |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | 确定指定的 BaseDecodeType 是否包含任何邮政条形码符号 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | 将 SingleDecodeType 的字符串表示转换为其实例。 |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | 将 SingleDecodeType 的字符串表示转换为其实例。 |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | 通过 barcodeTypes 指定扫描集 |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | 将 MultiDecodeType 的字符串表示转换为其实例。 |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | 将 SingleDecodeType 的字符串表示转换为其实例。 |
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


指定将使用所有可用的符号体系检查数据。

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


指定应使用  **Australian Post Domestic eParcel Barcode**  条形码规范解码数据

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


指定应使用  **Australia Post**  条形码规范解码数据

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


指定应使用  **Aztec**  条形码规范解码数据

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


指定应使用  **CODABAR**  条形码规范解码数据

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


指定应使用  **CodablockF**  条形码规范解码数据

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


指定应使用  **CODE 11**  条形码规范解码数据

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


指定数据应使用 **CODE 128** 条形码规范进行解码

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


指定数据应使用 **SCode16K** 条形码规范进行解码

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


指定数据应使用 **Code32** 条形码规范进行解码

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


指定数据应使用 **Code 39** 基本字符集条形码规范：ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


指定数据应使用 **Code 39** 完整 ASCII 字符集条形码规范：ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


指定数据应使用 **CODE 93** 条形码规范进行解码

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


指定数据应使用 **CompactPdf417**（Pdf417Truncated）条形码规范进行解码

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


指定数据应使用 **GS1 DATABAR expanded** 条形码规范进行解码

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


指定数据应使用 **GS1 DATABAR expanded stacked** 条形码规范进行解码

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


指定数据应使用 **GS1 DATABAR limited** 条形码规范进行解码

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


指定数据应使用 **GS1 DATABAR omni-directional** 条形码规范进行解码

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


指定数据应使用 **GS1 DATABAR stacked** 条形码规范进行解码

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


指定数据应使用 **GS1 DATABAR stacked omni-directional** 条形码规范进行解码

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


指定数据应使用 **GS1 DATABAR truncated** 条形码规范进行解码

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


指定数据应使用 **DataLogic 2 of 5** 条形码规范进行解码

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


指定数据应使用 **DataMatrix** 条形码符号进行解码

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


指定数据应使用 **DeutschePost Ident code** 条形码规范进行解码

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


指定数据应使用 **DeutschePost Leit code** 条形码规范进行解码

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


指定数据应使用 **DotCode** 条形码规范进行解码

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


指定数据应使用 **DotCode** 条形码规范进行解码

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


指定数据应使用 **EAN-13** 条形码规范进行解码

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


指定数据应使用 **EAN14** 条形码规范进行解码

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


指定数据应使用 **EAN-8** 条形码规范进行解码

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


指定数据应使用 **GS1 Aztec** 条形码规范进行解码

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


指定数据应使用 **GS1 CODE 128** 条形码规范进行解码

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


指定数据应使用 **GS1 Composite Bar** 条形码规范进行解码

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


指定应使用 **GS1DataMatrix** 条形码符号进行解码

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


指定应使用 **GS1 DotCode** 条形码规范进行解码

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


指定应使用 **GS1 Han Xin Code** 条形码规范进行解码

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


指定应使用 **MicroPdf417** 条形码规范进行解码

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


指定应使用 **GS1 QR** 条形码规范进行解码

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


指定应使用 **Han Xin Code** 条形码规范进行解码

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


指定应使用 **HIBC LIC QR** 条形码规范进行解码

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


指定应使用 **HIBC PAS QR** 条形码规范进行解码

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


指定应使用 **HIBC LIC Aztec** 条形码规范进行解码

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


指定应使用 **HIBC PAS Aztec** 条形码规范进行解码

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


指定应使用 **HIBC LIC Code128** 条形码规范进行解码

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


指定应使用 **HIBC PAS Code128** 条形码规范进行解码

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


指定应使用 **HIBC LIC Code39** 条形码规范进行解码

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


指定应使用 **HIBC PAS Code39** 条形码规范进行解码

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


指定应使用 **HIBC LIC DataMatrix** 条形码规范进行解码

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


指定应使用 **HIBC PAS DataMatrix** 条形码规范进行解码

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


指定应使用 **IATA 2 of 5** 条形码规范对数据进行解码。IATA（International Air Transport Association）使用此条形码来管理航空货物。

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


指定应使用 **INTERLEAVED 2 of 5** 条形码规范进行解码

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


指定应使用 **ISBN** 条形码规范进行解码

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


指定应使用 **ISMN** 条形码规范进行解码

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


指定应使用 **ISSN** 条形码规范进行解码

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


指定应使用 **Italian Post 25** 条形码规范进行解码

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


指定应使用 **ITF14** 条形码规范进行解码

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


指定应使用 **ITF6** 条形码规范进行解码

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


指定应使用 **MacroPdf417** 条形码规范进行解码

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


指定应使用 **Royal Mail Mailmark** 条形码规范对数据进行解码。

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


指定应使用 **Matrix 2 of 5** 条形码规范对数据进行解码

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


指定应使用 **MaxiCode** 条形码规范对数据进行解码

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


指定应使用 **MicroPdf417** 条形码规范对数据进行解码

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


指定应使用 **MicroQR Code** 条形码规范对数据进行解码

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


指定应使用 **MICR E-13B** 条形码规范对数据进行解码

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


指定将使用最常用的符号集检查数据

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


指定应使用 **MSI Plessey** 条形码规范对数据进行解码

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


未指定的解码类型。

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


指定应使用 USPS **OneCode** 条形码规范对数据进行解码

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


指定应使用 **OPC** 条形码规范对数据进行解码

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


指定应使用 **Patch code** 条形码规范对数据进行解码。条形码符号用于自动扫描

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


指定应使用 **Pdf417** 条形码符号对数据进行解码

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


指定应使用 **Pharmacode** 条形码对数据进行解码。此符号也称为 Pharmaceutical BINARY Code

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


指定应使用 **Planet** 条形码规范对数据进行解码

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


指定将使用所有 **1.5D POSTAL** 条形码符号集检查数据，例如 **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


指定应使用 **Postnet** 条形码规范对数据进行解码

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


指定应使用 **PZN** 条形码规范对数据进行解码。此符号也称为 Pharma Zentral Nummer。支持 PZN7 和 PZN8。

### QR {#QR}
```
public static final SingleDecodeType QR
```


指定应使用 **QR Code** 条形码规范对数据进行解码

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


指定应使用 **RectMicroQR (rMQR) Code** 条形码规范对数据进行解码

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


指定应使用 **RM4SCC** 条形码规范对数据进行解码。RM4SCC（Royal Mail 4-state Customer Code）用于英国的自动邮件分拣过程。

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


指定应使用 **SCC14** 条形码规范对数据进行解码

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


指定应使用 **SSCC18** 条形码规范对数据进行解码

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


指定应使用 **Standard 2 of 5** 条形码规范对数据进行解码

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


指定应使用 **Supplement(EAN2, EAN5)** 条形码规范对数据进行解码

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


指定应使用 **Swiss Post Parcel Barcode** 条形码规范对数据进行解码

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


指定将使用所有 **1D** 条形码符号检查数据

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


指定将使用所有 **2D** 条形码符号检查数据

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


指定应使用 **UPC-A** 条形码规范对数据进行解码

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


指定应使用 **UPC-E** 条形码规范对数据进行解码

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


指定应使用 **VIN**（Vehicle Identification Number）条形码规范对数据进行解码

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


获取表示 AllSupportedTypes 的数组

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


检索解码类型名称的数组。

**Returns:**
java.lang.String[] - 解码类型名称的字符串数组。
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


确定指定的 BaseDecodeType 是否包含任何 1D 条形码符号

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 要测试的 BaseDecodeType。 |

**Returns:**
boolean - 如果 BaseDecodeType 包含任何 1D 条形码符号，则返回 **true**；否则返回 **false**。
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


确定指定的 BaseDecodeType 是否包含任何 2D 条形码符号

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 要测试的 BaseDecodeType。 |

**Returns:**
boolean - 如果 BaseDecodeTypeddddddddw 包含任何 2D 条形码符号，则返回 **true**；否则返回 **false**。
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


确定指定的 BaseDecodeType 是否包含任何邮政条形码符号

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 要测试的 BaseDecodeType |

**Returns:**
boolean - 如果 BaseDecodeType 包含任何邮政条形码符号，则返回 **true**；否则返回 **false**。
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


将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 包含要转换的 SingleDecodeType 表示的字符串。 |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

否则它返回不确定类型。或 SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 包含要转换的 SingleDecodeType，格式如 \"EAN8\"、\"EAN13\"、\"CodaBar\"... 的字符串。 |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
布尔值 - **true** 表示 s 已成功转换；否则为 **false**。
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


通过 barcodeTypes 指定扫描集

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | 单个和多重解码类型的数组 |

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


将 MultiDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 一个字符串，格式为 "AllSupportedTypes" 或 "EAN8,EAN13,CodaBar" 用于转换。 |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - 当转换成功完成时返回实际的 MultiDecodeType；否则返回不确定类型：new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | 包含要转换的 SingleDecodeType，格式如 \"EAN8\"、\"EAN13\"、\"CodaBar\"... 的字符串。 |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

