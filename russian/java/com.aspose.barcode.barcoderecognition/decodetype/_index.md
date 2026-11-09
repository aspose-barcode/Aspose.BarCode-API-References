---
title: "DecodeType"
second_title: "Aspose.BarCode for Java API Reference"
description: "Укажите тип штрихкода для чтения."
type: docs
weight: 30
url: /ru/java/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

Укажите тип штрихкода для чтения.

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | Указывает, что данные будут проверяться со всеми доступными символогиями. |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | Указывает, что данные должны быть декодированы согласно спецификации штрих‑кода  **Australian Post Domestic eParcel Barcode**. |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | Указывает, что данные должны быть декодированы с  **Australia Post**  спецификацией штрихкода |
| [AZTEC](#AZTEC) | Указывает, что данные должны быть декодированы с  **Aztec**  спецификацией штрихкода |
| [CODABAR](#CODABAR) | Указывает, что данные должны быть декодированы с  **CODABAR**  спецификацией штрихкода |
| [CODABLOCK_F](#CODABLOCK-F) | Указывает, что данные должны быть декодированы с  **CodablockF**  спецификацией штрихкода |
| [CODE_11](#CODE-11) | Указывает, что данные должны быть декодированы с  **CODE 11**  спецификацией штрихкода |
| [CODE_128](#CODE-128) | Указывает, что данные должны быть декодированы с  **CODE 128**  спецификацией штрихкода |
| [CODE_16_K](#CODE-16-K) | Указывает, что данные должны быть декодированы с  **SCode16K**  спецификацией штрихкода |
| [CODE_32](#CODE-32) | Указывает, что данные должны быть декодированы с  **Code32**  спецификацией штрихкода |
| [CODE_39](#CODE-39) | Указывает, что данные должны быть декодированы с  **Code 39**  спецификацией штрихкода базового набора символов: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | Указывает, что данные должны быть декодированы с  **Code 39**  спецификацией штрихкода полного набора ASCII: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | Указывает, что данные должны быть декодированы с  **CODE 93**  спецификацией штрихкода |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | Указывает, что данные должны быть декодированы с  **CompactPdf417**  (Pdf417Truncated) спецификацией штрихкода |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | Указывает, что данные должны быть декодированы с  **GS1 DATABAR expanded**  спецификацией штрихкода |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | Указывает, что данные должны быть декодированы с  **GS1 DATABAR expanded stacked**  спецификацией штрихкода |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | Указывает, что данные должны быть декодированы с  **GS1 DATABAR limited**  спецификацией штрихкода |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | Указывает, что данные должны быть декодированы с  **GS1 DATABAR omni-directional**  спецификацией штрихкода |
| [DATABAR_STACKED](#DATABAR-STACKED) | Указывает, что данные должны быть декодированы с  **GS1 DATABAR stacked**  спецификацией штрихкода |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | Указывает, что данные должны быть декодированы с  **GS1 DATABAR stacked omni-directional**  спецификацией штрихкода |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | Указывает, что данные должны быть декодированы с  **GS1 DATABAR truncated**  спецификацией штрихкода |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | Указывает, что данные должны быть декодированы с  **DataLogic 2 of 5**  спецификацией штрихкода |
| [DATA_MATRIX](#DATA-MATRIX) | Указывает, что данные должны быть декодированы с  **DataMatrix**  символикой штрихкода |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | Указывает, что данные должны быть декодированы с  **DeutschePost Ident code**  спецификацией штрихкода |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | Указывает, что данные должны быть декодированы с  **DeutschePost Leit code**  спецификацией штрихкода |
| [DOT_CODE](#DOT-CODE) | Указывает, что данные должны быть декодированы с  **DotCode**  спецификацией штрихкода |
| [DUTCH_KIX](#DUTCH-KIX) | Указывает, что данные должны быть декодированы с  **DotCode**  спецификацией штрихкода |
| [EAN_13](#EAN-13) | Указывает, что данные должны быть декодированы с  **EAN-13**  спецификацией штрихкода |
| [EAN_14](#EAN-14) | Указывает, что данные должны быть декодированы с использованием  **EAN14**  спецификации штрихкода |
| [EAN_8](#EAN-8) | Указывает, что данные должны быть декодированы с использованием  **EAN-8**  спецификации штрихкода |
| [GS_1_AZTEC](#GS-1-AZTEC) | Указывает, что данные должны быть декодированы с использованием  **GS1 Aztec**  спецификации штрихкода |
| [GS_1_CODE_128](#GS-1-CODE-128) | Указывает, что данные должны быть декодированы с использованием  **GS1 CODE 128**  спецификации штрихкода |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | Указывает, что данные должны быть декодированы с использованием  **GS1 Composite Bar**  спецификации штрихкода |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | Указывает, что данные должны быть декодированы с использованием  **GS1DataMatrix**  символики штрихкода |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | Указывает, что данные должны быть декодированы с использованием  **GS1 DotCode**  спецификации штрихкода |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | Указывает, что данные должны быть декодированы с использованием **GS1 Han Xin Code** спецификации штрихкода |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | Указывает, что данные должны быть декодированы с использованием **MicroPdf417** спецификации штрихкода |
| [GS_1_QR](#GS-1-QR) | Указывает, что данные должны быть декодированы с использованием  **GS1 QR**  спецификации штрихкода |
| [HAN_XIN](#HAN-XIN) | Указывает, что данные должны быть декодированы с использованием **Han Xin Code** спецификации штрихкода |
| [HIBCQRLIC](#HIBCQRLIC) | Указывает, что данные должны быть декодированы с использованием  **HIBC LIC QR**  спецификации штрихкода |
| [HIBCQRPAS](#HIBCQRPAS) | Указывает, что данные должны быть декодированы с использованием  **HIBC PAS QR**  спецификации штрихкода |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | Указывает, что данные должны быть декодированы с использованием  **HIBC LIC Aztec**  спецификации штрихкода |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | Указывает, что данные должны быть декодированы с использованием  **HIBC PAS Aztec**  спецификации штрихкода |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | Указывает, что данные должны быть декодированы с использованием  **HIBC LIC Code128**  спецификации штрихкода |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | Указывает, что данные должны быть декодированы с использованием  **HIBC PAS Code128**  спецификации штрихкода |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | Указывает, что данные должны быть декодированы с использованием  **HIBC LIC Code39**  спецификации штрихкода |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | Указывает, что данные должны быть декодированы с использованием  **HIBC PAS Code39**  спецификации штрихкода |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | Указывает, что данные должны быть декодированы с использованием  **HIBC LIC DataMatrix**  спецификации штрихкода |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | Указывает, что данные должны быть декодированы с использованием  **HIBC PAS DataMatrix**  спецификации штрихкода |
| [IATA_2_OF_5](#IATA-2-OF-5) | Указывает, что данные должны быть декодированы с использованием  **IATA 2 of 5**  спецификации штрихкода. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | Указывает, что данные должны быть декодированы с использованием  **INTERLEAVED 2 of 5**  спецификации штрихкода |
| [ISBN](#ISBN) | Указывает, что данные должны быть декодированы с использованием  **ISBN**  спецификации штрихкода |
| [ISMN](#ISMN) | Указывает, что данные должны быть декодированы с использованием  **ISMN**  спецификации штрихкода |
| [ISSN](#ISSN) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **ISSN** |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Italian Post 25** |
| [ITF_14](#ITF-14) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **ITF14** |
| [ITF_6](#ITF-6) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **ITF6** |
| [MACRO_PDF_417](#MACRO-PDF-417) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MacroPdf417** |
| [MAILMARK](#MAILMARK) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Royal Mail Mailmark**. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Matrix 2 of 5** |
| [MAXI_CODE](#MAXI-CODE) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MaxiCode** |
| [MICRO_PDF_417](#MICRO-PDF-417) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MicroPdf417** |
| [MICRO_QR](#MICRO-QR) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MicroQR Code** |
| [MICR_E_13_B](#MICR-E-13-B) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MICR E-13B** |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | Указывает, что данные будут проверяться с использованием наиболее часто используемых символогий |
| [MSI](#MSI) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MSI Plessey** |
| [NONE](#NONE) | Неуказанный тип декодирования. |
| [ONE_CODE](#ONE-CODE) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода USPS **OneCode** |
| [OPC](#OPC) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **OPC** |
| [PATCH_CODE](#PATCH-CODE) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Patch code**. |
| [PDF_417](#PDF-417) | Указывает, что данные должны быть декодированы с использованием символогии штрихкода **Pdf417** |
| [PHARMACODE](#PHARMACODE) | Указывает, что данные должны быть декодированы с использованием штрихкода **Pharmacode**. |
| [PLANET](#PLANET) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Planet** |
| [POSTAL_TYPES](#POSTAL-TYPES) | Указывает, что данные будут проверяться со всеми символогиями **1.5D POSTAL**, такими как **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Postnet** |
| [PZN](#PZN) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **PZN**. |
| [QR](#QR) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **QR Code** |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **RectMicroQR (rMQR) Code** |
| [RM_4_SCC](#RM-4-SCC) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **RM4SCC**. |
| [SCC_14](#SCC-14) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **SCC14** |
| [SSCC_18](#SSCC-18) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **SSCC18**. |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Standard 2 of 5**. |
| [SUPPLEMENT](#SUPPLEMENT) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Supplement(EAN2, EAN5)**. |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Swiss Post Parcel Barcode**. |
| [TYPES_1D](#TYPES-1D) | Указывает, что данные будут проверяться на соответствие всем символогиям штрихкода **1D**. |
| [TYPES_2D](#TYPES-2D) | Указывает, что данные будут проверяться на соответствие всем символогиям штрихкода **2D**. |
| [UPCA](#UPCA) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **UPC-A**. |
| [UPCE](#UPCE) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **UPC-E**. |
| [VIN](#VIN) | Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **VIN** (Vehicle Identification Number). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | Получает массив, представляющий AllSupportedTypes. |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Получает массив имен типов декодирования. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Определяет, содержит ли указанный BaseDecodeType любую 1D‑символогию штрихкода. |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Определяет, содержит ли указанный BaseDecodeType любую 2D‑символогию штрихкода. |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Определяет, содержит ли указанный BaseDecodeType любую почтовую символогию штрихкода. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | Преобразует строковое представление SingleDecodeType в его экземпляр. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | Преобразует строковое представление SingleDecodeType в его экземпляр. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Укажите наборы сканирования по типам штрихкодов. |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Преобразует строковое представление MultiDecodeType в его экземпляр. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Преобразует строковое представление SingleDecodeType в его экземпляр. |
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


Указывает, что данные будут проверяться со всеми доступными символогиями.

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


Указывает, что данные должны быть декодированы согласно спецификации штрих‑кода  **Australian Post Domestic eParcel Barcode**.

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


Указывает, что данные должны быть декодированы с  **Australia Post**  спецификацией штрихкода

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


Указывает, что данные должны быть декодированы с  **Aztec**  спецификацией штрихкода

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


Указывает, что данные должны быть декодированы с  **CODABAR**  спецификацией штрихкода

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


Указывает, что данные должны быть декодированы с  **CodablockF**  спецификацией штрихкода

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


Указывает, что данные должны быть декодированы с  **CODE 11**  спецификацией штрихкода

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


Указывает, что данные должны быть декодированы с  **CODE 128**  спецификацией штрихкода

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


Указывает, что данные должны быть декодированы с  **SCode16K**  спецификацией штрихкода

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


Указывает, что данные должны быть декодированы с  **Code32**  спецификацией штрихкода

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


Указывает, что данные должны быть декодированы с  **Code 39**  спецификацией штрихкода базового набора символов: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


Указывает, что данные должны быть декодированы с  **Code 39**  спецификацией штрихкода полного набора ASCII: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


Указывает, что данные должны быть декодированы с  **CODE 93**  спецификацией штрихкода

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


Указывает, что данные должны быть декодированы с  **CompactPdf417**  (Pdf417Truncated) спецификацией штрихкода

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


Указывает, что данные должны быть декодированы с  **GS1 DATABAR expanded**  спецификацией штрихкода

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


Указывает, что данные должны быть декодированы с  **GS1 DATABAR expanded stacked**  спецификацией штрихкода

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


Указывает, что данные должны быть декодированы с  **GS1 DATABAR limited**  спецификацией штрихкода

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


Указывает, что данные должны быть декодированы с  **GS1 DATABAR omni-directional**  спецификацией штрихкода

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


Указывает, что данные должны быть декодированы с  **GS1 DATABAR stacked**  спецификацией штрихкода

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


Указывает, что данные должны быть декодированы с  **GS1 DATABAR stacked omni-directional**  спецификацией штрихкода

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


Указывает, что данные должны быть декодированы с  **GS1 DATABAR truncated**  спецификацией штрихкода

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


Указывает, что данные должны быть декодированы с  **DataLogic 2 of 5**  спецификацией штрихкода

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


Указывает, что данные должны быть декодированы с  **DataMatrix**  символикой штрихкода

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


Указывает, что данные должны быть декодированы с  **DeutschePost Ident code**  спецификацией штрихкода

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


Указывает, что данные должны быть декодированы с  **DeutschePost Leit code**  спецификацией штрихкода

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


Указывает, что данные должны быть декодированы с  **DotCode**  спецификацией штрихкода

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


Указывает, что данные должны быть декодированы с  **DotCode**  спецификацией штрихкода

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


Указывает, что данные должны быть декодированы с  **EAN-13**  спецификацией штрихкода

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


Указывает, что данные должны быть декодированы с использованием  **EAN14**  спецификации штрихкода

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


Указывает, что данные должны быть декодированы с использованием  **EAN-8**  спецификации штрихкода

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


Указывает, что данные должны быть декодированы с использованием  **GS1 Aztec**  спецификации штрихкода

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


Указывает, что данные должны быть декодированы с использованием  **GS1 CODE 128**  спецификации штрихкода

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


Указывает, что данные должны быть декодированы с использованием  **GS1 Composite Bar**  спецификации штрихкода

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


Указывает, что данные должны быть декодированы с использованием  **GS1DataMatrix**  символики штрихкода

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


Указывает, что данные должны быть декодированы с использованием  **GS1 DotCode**  спецификации штрихкода

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


Указывает, что данные должны быть декодированы с использованием **GS1 Han Xin Code** спецификации штрихкода

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


Указывает, что данные должны быть декодированы с использованием **MicroPdf417** спецификации штрихкода

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


Указывает, что данные должны быть декодированы с использованием  **GS1 QR**  спецификации штрихкода

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


Указывает, что данные должны быть декодированы с использованием **Han Xin Code** спецификации штрихкода

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


Указывает, что данные должны быть декодированы с использованием  **HIBC LIC QR**  спецификации штрихкода

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


Указывает, что данные должны быть декодированы с использованием  **HIBC PAS QR**  спецификации штрихкода

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


Указывает, что данные должны быть декодированы с использованием  **HIBC LIC Aztec**  спецификации штрихкода

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


Указывает, что данные должны быть декодированы с использованием  **HIBC PAS Aztec**  спецификации штрихкода

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


Указывает, что данные должны быть декодированы с использованием  **HIBC LIC Code128**  спецификации штрихкода

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


Указывает, что данные должны быть декодированы с использованием  **HIBC PAS Code128**  спецификации штрихкода

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


Указывает, что данные должны быть декодированы с использованием  **HIBC LIC Code39**  спецификации штрихкода

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


Указывает, что данные должны быть декодированы с использованием  **HIBC PAS Code39**  спецификации штрихкода

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


Указывает, что данные должны быть декодированы с использованием  **HIBC LIC DataMatrix**  спецификации штрихкода

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


Указывает, что данные должны быть декодированы с использованием  **HIBC PAS DataMatrix**  спецификации штрихкода

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **IATA 2 of 5**. IATA (International Air Transport Association) использует этот штрихкод для управления воздушными грузами.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


Указывает, что данные должны быть декодированы с использованием  **INTERLEAVED 2 of 5**  спецификации штрихкода

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


Указывает, что данные должны быть декодированы с использованием  **ISBN**  спецификации штрихкода

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


Указывает, что данные должны быть декодированы с использованием  **ISMN**  спецификации штрихкода

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **ISSN**

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Italian Post 25**

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **ITF14**

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **ITF6**

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MacroPdf417**

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Royal Mail Mailmark**.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Matrix 2 of 5**

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MaxiCode**

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MicroPdf417**

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MicroQR Code**

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MICR E-13B**

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


Указывает, что данные будут проверяться с использованием наиболее часто используемых символогий

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **MSI Plessey**

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


Неуказанный тип декодирования.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода USPS **OneCode**

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **OPC**

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Patch code**. Симвология штрихкода используется для автоматического сканирования.

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


Указывает, что данные должны быть декодированы с использованием символогии штрихкода **Pdf417**

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


Указывает, что данные должны быть декодированы с использованием штрихкода **Pharmacode**. Эта симвология также известна как Pharmaceutical BINARY Code.

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Planet**

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


Указывает, что данные будут проверяться со всеми символогиями **1.5D POSTAL**, такими как **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Postnet**

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **PZN**. Эта симвология также известна как Pharma Zentral Nummer. Поддерживаются PZN7 и PZN8.

### QR {#QR}
```
public static final SingleDecodeType QR
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **QR Code**

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **RectMicroQR (rMQR) Code**

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **RM4SCC**. RM4SCC (Royal Mail 4-state Customer Code) используется в автоматизированном процессе сортировки почты в Великобритании.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **SCC14**

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **SSCC18**.

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Standard 2 of 5**.

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Supplement(EAN2, EAN5)**.

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **Swiss Post Parcel Barcode**.

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


Указывает, что данные будут проверяться на соответствие всем символогиям штрихкода **1D**.

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


Указывает, что данные будут проверяться на соответствие всем символогиям штрихкода **2D**.

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **UPC-A**.

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **UPC-E**.

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


Указывает, что данные должны быть декодированы с использованием спецификации штрихкода **VIN** (Vehicle Identification Number).

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


Получает массив, представляющий AllSupportedTypes.

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


Получает массив имен типов декодирования.

**Returns:**
java.lang.String[] - Массив строк, содержащий имена типов декодирования.
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


Определяет, содержит ли указанный BaseDecodeType любую 1D‑символогию штрихкода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | BaseDecodeType для тестирования. |

**Returns:**
boolean - Возвращает **true**, если BaseDecodeType содержит любую 1D‑символику штрихкода; в противном случае возвращает **false**.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


Определяет, содержит ли указанный BaseDecodeType любую 2D‑символогию штрихкода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | BaseDecodeType для тестирования. |

**Returns:**
boolean - Возвращает **true**, если BaseDecodeTypeddddddddw содержит любую 2D‑символику штрихкода; в противном случае возвращает **false**.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


Определяет, содержит ли указанный BaseDecodeType любую почтовую символогию штрихкода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | BaseDecodeType для тестирования |

**Returns:**
boolean - Возвращает **true**, если BaseDecodeType содержит любую почтовую символику штрихкода; в противном случае возвращает **false**.
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


Преобразует строковое представление SingleDecodeType в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parsingType | java.lang.String | Строка, содержащая представление SingleDecodeType для преобразования. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

в противном случае возвращает неопределённый тип. или SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


Преобразует строковое представление SingleDecodeType в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parsingType | java.lang.String | Строка, содержащая SingleDecodeType в формате \"EAN8\" или \"EAN13\" или \"CodaBar\"... для преобразования. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - **true**, если s был успешно преобразован; в противном случае **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


Укажите наборы сканирования по типам штрихкодов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Массив одиночных и множественных типов декодирования |

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


Преобразует строковое представление MultiDecodeType в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parsingType | java.lang.String | Строка в формате либо "AllSupportedTypes", либо "EAN8,EAN13,CodaBar" для преобразования. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully; otherwise it returns indefinite type: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Преобразует строковое представление SingleDecodeType в его экземпляр. Возвращаемое значение указывает, удалось ли выполнить преобразование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| parsingType | java.lang.String | Строка, содержащая SingleDecodeType в формате \"EAN8\" или \"EAN13\" или \"CodaBar\"... для преобразования. |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

