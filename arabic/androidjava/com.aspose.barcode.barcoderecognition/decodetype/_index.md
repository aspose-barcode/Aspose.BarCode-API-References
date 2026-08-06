---
title: DecodeType
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: حدد نوع الباركود للقراءة.
type: docs
weight: 32
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

حدد نوع الباركود للقراءة.

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

| Constructor | الوصف |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | يحدد أن البيانات سيتم فحصها بجميع الرموز المتاحة |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **Australian Post Domestic eParcel Barcode** |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **Australia Post** |
| [AZTEC](#AZTEC) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **Aztec** |
| [CODABAR](#CODABAR) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **CODABAR** |
| [CODABLOCK_F](#CODABLOCK-F) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **CodablockF** |
| [CODE_11](#CODE-11) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **CODE 11** |
| [CODE_128](#CODE-128) | يحدد أن البيانات يجب فك ترميزها باستخدام  **CODE 128**  مواصفة الباركود |
| [CODE_16_K](#CODE-16-K) | يحدد أن البيانات يجب فك ترميزها باستخدام  **SCode16K**  مواصفة الباركود |
| [CODE_32](#CODE-32) | يحدد أن البيانات يجب فك ترميزها باستخدام  **Code32**  مواصفة الباركود |
| [CODE_39](#CODE-39) | يحدد أن البيانات يجب فك ترميزها باستخدام  **Code 39**  مواصفة الباركود لمجموعة الأحرف الأساسية: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | يحدد أن البيانات يجب فك ترميزها باستخدام  **Code 39**  مواصفة الباركود لمجموعة الأحرف ASCII الكاملة: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | يحدد أن البيانات يجب فك ترميزها باستخدام  **CODE 93**  مواصفة الباركود |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | يحدد أن البيانات يجب فك ترميزها باستخدام  **CompactPdf417**  (Pdf417Truncated) مواصفة الباركود |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR expanded**  مواصفة الباركود |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR expanded stacked**  مواصفة الباركود |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR limited**  مواصفة الباركود |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR omni-directional**  مواصفة الباركود |
| [DATABAR_STACKED](#DATABAR-STACKED) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR stacked**  مواصفة الباركود |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR stacked omni-directional**  مواصفة الباركود |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR truncated**  مواصفة الباركود |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | يحدد أن البيانات يجب فك ترميزها باستخدام  **DataLogic 2 of 5**  مواصفة الباركود |
| [DATA_MATRIX](#DATA-MATRIX) | يحدد أن البيانات يجب فك ترميزها باستخدام  **DataMatrix**  نظام ترميز الباركود |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | يحدد أن البيانات يجب فك ترميزها باستخدام  **DeutschePost Ident code**  مواصفة الباركود |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | يحدد أن البيانات يجب فك ترميزها باستخدام  **DeutschePost Leit code**  مواصفة الباركود |
| [DOT_CODE](#DOT-CODE) | يحدد أن البيانات يجب فك ترميزها باستخدام  **DotCode**  مواصفة الباركود |
| [DUTCH_KIX](#DUTCH-KIX) | يحدد أن البيانات يجب فك ترميزها باستخدام  **DotCode**  مواصفة الباركود |
| [EAN_13](#EAN-13) | يحدد أن البيانات يجب فك ترميزها باستخدام  **EAN-13**  مواصفة الباركود |
| [EAN_14](#EAN-14) | يحدد أن البيانات يجب فك ترميزها باستخدام  **EAN14**  مواصفة الباركود |
| [EAN_8](#EAN-8) | يحدد أن البيانات يجب فك ترميزها باستخدام  **EAN-8**  مواصفة الباركود |
| [GS_1_AZTEC](#GS-1-AZTEC) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 Aztec**  مواصفة الباركود |
| [GS_1_CODE_128](#GS-1-CODE-128) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 CODE 128**  مواصفة الباركود |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 Composite Bar**  مواصفة الباركود |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1DataMatrix**  ترميز الباركود |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DotCode**  مواصفات الباركود |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | يحدد أن البيانات يجب فك ترميزها باستخدام **GS1 Han Xin Code** مواصفات الباركود |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | يحدد أن البيانات يجب فك ترميزها باستخدام **MicroPdf417** مواصفات الباركود |
| [GS_1_QR](#GS-1-QR) | يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 QR**  مواصفات الباركود |
| [HAN_XIN](#HAN-XIN) | يحدد أن البيانات يجب فك ترميزها باستخدام **Han Xin Code** مواصفات الباركود |
| [HIBCQRLIC](#HIBCQRLIC) | يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC LIC QR**  مواصفات الباركود |
| [HIBCQRPAS](#HIBCQRPAS) | يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC PAS QR**  مواصفات الباركود |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC LIC Aztec**  مواصفات الباركود |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC PAS Aztec**  مواصفات الباركود |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC LIC Code128**  مواصفات الباركود |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC PAS Code128**  مواصفات الباركود |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC LIC Code39**  مواصفات الباركود |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC PAS Code39**  مواصفات الباركود |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC LIC DataMatrix**  مواصفات الباركود |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC PAS DataMatrix**  مواصفات الباركود |
| [IATA_2_OF_5](#IATA-2-OF-5) | يحدد أن البيانات يجب فك ترميزها باستخدام  **IATA 2 of 5**  مواصفات الباركود. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | يحدد أن البيانات يجب فك ترميزها باستخدام  **INTERLEAVED 2 of 5**  مواصفات الباركود |
| [ISBN](#ISBN) | يحدد أن البيانات يجب فك ترميزها باستخدام  **ISBN**  مواصفات الباركود |
| [ISMN](#ISMN) | يحدد أن البيانات يجب فك ترميزها باستخدام  **ISMN**  مواصفات الباركود |
| [ISSN](#ISSN) | يحدد أن البيانات يجب فك ترميزها باستخدام  **ISSN**  مواصفات الباركود |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | يحدد أن البيانات يجب فك ترميزها باستخدام  **Italian Post 25**  مواصفات الباركود |
| [ITF_14](#ITF-14) | يحدد أن البيانات يجب فك ترميزها باستخدام  **ITF14**  مواصفات الباركود |
| [ITF_6](#ITF-6) | يحدد أن البيانات يجب فك ترميزها باستخدام  **ITF6**  مواصفات الباركود |
| [MACRO_PDF_417](#MACRO-PDF-417) | يحدد أن البيانات يجب فك ترميزها باستخدام  **MacroPdf417**  مواصفات الباركود |
| [MAILMARK](#MAILMARK) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Royal Mail Mailmark**. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Matrix 2 of 5** |
| [MAXI_CODE](#MAXI-CODE) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **MaxiCode** |
| [MICRO_PDF_417](#MICRO-PDF-417) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **MicroPdf417** |
| [MICRO_QR](#MICRO-QR) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **MicroQR Code** |
| [MICR_E_13_B](#MICR-E-13-B) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **MICR E-13B** |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | يحدد أن البيانات سيتم فحصها باستخدام أكثر الرموز شيوعًا |
| [MSI](#MSI) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **MSI Plessey** |
| [NONE](#NONE) | نوع فك الترميز غير محدد. |
| [ONE_CODE](#ONE-CODE) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود USPS **OneCode**. |
| [OPC](#OPC) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **OPC** |
| [PATCH_CODE](#PATCH-CODE) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Patch code**. |
| [PDF_417](#PDF-417) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام رمز الباركود **Pdf417**. |
| [PHARMACODE](#PHARMACODE) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام الباركود **Pharmacode**. |
| [PLANET](#PLANET) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Planet** |
| [POSTAL_TYPES](#POSTAL-TYPES) | يحدد أن البيانات سيتم فحصها باستخدام جميع رموز الباركود **1.5D POSTAL**، مثل **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**. |
| [POSTNET](#POSTNET) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Postnet** |
| [PZN](#PZN) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **PZN**. |
| [QR](#QR) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **QR Code** |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **RectMicroQR (rMQR) Code** |
| [RM_4_SCC](#RM-4-SCC) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **RM4SCC**. |
| [SCC_14](#SCC-14) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **SCC14** |
| [SSCC_18](#SSCC-18) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **SSCC18** |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Standard 2 of 5** |
| [SUPPLEMENT](#SUPPLEMENT) | يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Supplement(EAN2, EAN5)** |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **Swiss Post Parcel Barcode** |
| [TYPES_1D](#TYPES-1D) | يحدد أن البيانات سيتم فحصها باستخدام جميع رموز الباركود **1D** |
| [TYPES_2D](#TYPES-2D) | يحدد أن البيانات سيتم فحصها باستخدام جميع رموز الباركود **2D** |
| [UPCA](#UPCA) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **UPC-A** |
| [UPCE](#UPCE) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **UPC-E** |
| [VIN](#VIN) | يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **VIN** (رقم تعريف المركبة) |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | يحصل على مصفوفة تمثل AllSupportedTypes |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | يسترجع مصفوفة بأسماء أنواع فك الترميز. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | يحدد ما إذا كان BaseDecodeType المحدد يحتوي على أي رموز باركود 1D |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | يحدد ما إذا كان BaseDecodeType المحدد يحتوي على أي رموز باركود 2D |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | يحدد ما إذا كان BaseDecodeType المحدد يحتوي على أي رموز باركود بريدية |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | تحويل التمثيل النصي لـ SingleDecodeType إلى كائنه. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | تحويل التمثيل النصي لـ SingleDecodeType إلى كائنه. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | حدد مجموعات الفحص حسب barcodeTypes |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | تحويل التمثيل النصي لـ MultiDecodeType إلى كائنه. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | تحويل التمثيل النصي لـ SingleDecodeType إلى كائنه. |
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


يحدد أن البيانات سيتم فحصها بجميع الرموز المتاحة

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **Australian Post Domestic eParcel Barcode**

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **Australia Post**

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **Aztec**

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **CODABAR**

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **CodablockF**

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود  **CODE 11**

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **CODE 128**  مواصفة الباركود

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **SCode16K**  مواصفة الباركود

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **Code32**  مواصفة الباركود

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **Code 39**  مواصفة الباركود لمجموعة الأحرف الأساسية: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **Code 39**  مواصفة الباركود لمجموعة الأحرف ASCII الكاملة: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **CODE 93**  مواصفة الباركود

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **CompactPdf417**  (Pdf417Truncated) مواصفة الباركود

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR expanded**  مواصفة الباركود

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR expanded stacked**  مواصفة الباركود

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR limited**  مواصفة الباركود

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR omni-directional**  مواصفة الباركود

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR stacked**  مواصفة الباركود

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR stacked omni-directional**  مواصفة الباركود

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DATABAR truncated**  مواصفة الباركود

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **DataLogic 2 of 5**  مواصفة الباركود

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **DataMatrix**  نظام ترميز الباركود

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **DeutschePost Ident code**  مواصفة الباركود

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **DeutschePost Leit code**  مواصفة الباركود

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **DotCode**  مواصفة الباركود

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **DotCode**  مواصفة الباركود

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **EAN-13**  مواصفة الباركود

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **EAN14**  مواصفة الباركود

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **EAN-8**  مواصفة الباركود

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 Aztec**  مواصفة الباركود

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 CODE 128**  مواصفة الباركود

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 Composite Bar**  مواصفة الباركود

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1DataMatrix**  ترميز الباركود

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 DotCode**  مواصفات الباركود

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


يحدد أن البيانات يجب فك ترميزها باستخدام **GS1 Han Xin Code** مواصفات الباركود

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


يحدد أن البيانات يجب فك ترميزها باستخدام **MicroPdf417** مواصفات الباركود

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **GS1 QR**  مواصفات الباركود

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


يحدد أن البيانات يجب فك ترميزها باستخدام **Han Xin Code** مواصفات الباركود

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC LIC QR**  مواصفات الباركود

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC PAS QR**  مواصفات الباركود

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC LIC Aztec**  مواصفات الباركود

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC PAS Aztec**  مواصفات الباركود

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC LIC Code128**  مواصفات الباركود

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC PAS Code128**  مواصفات الباركود

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC LIC Code39**  مواصفات الباركود

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC PAS Code39**  مواصفات الباركود

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC LIC DataMatrix**  مواصفات الباركود

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **HIBC PAS DataMatrix**  مواصفات الباركود

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **IATA 2 of 5**. تستخدم IATA (الاتحاد الدولي للنقل الجوي) هذا الباركود لإدارة الشحن الجوي.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **INTERLEAVED 2 of 5**  مواصفات الباركود

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **ISBN**  مواصفات الباركود

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **ISMN**  مواصفات الباركود

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **ISSN**  مواصفات الباركود

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **Italian Post 25**  مواصفات الباركود

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **ITF14**  مواصفات الباركود

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **ITF6**  مواصفات الباركود

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


يحدد أن البيانات يجب فك ترميزها باستخدام  **MacroPdf417**  مواصفات الباركود

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Royal Mail Mailmark**.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Matrix 2 of 5**

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **MaxiCode**

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **MicroPdf417**

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **MicroQR Code**

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **MICR E-13B**

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


يحدد أن البيانات سيتم فحصها باستخدام أكثر الرموز شيوعًا

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **MSI Plessey**

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


نوع فك الترميز غير محدد.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود USPS **OneCode**.

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **OPC**

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **Patch code**. تُستخدم رموز الباركود للمسح الآلي

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام رمز الباركود **Pdf417**.

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام الباركود **Pharmacode**. تُعرف هذه الرموز أيضًا باسم Pharmaceutical BINARY Code

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Planet**

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


يحدد أن البيانات سيتم فحصها باستخدام جميع رموز الباركود **1.5D POSTAL**، مثل **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**.

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Postnet**

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **PZN**. تُعرف هذه الرموز أيضًا باسم Pharma Zentral Nummer. يتم دعم PZN7 و PZN8.

### QR {#QR}
```
public static final SingleDecodeType QR
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **QR Code**

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **RectMicroQR (rMQR) Code**

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **RM4SCC**. يُستخدم RM4SCC (رمز العميل ذي الأربع حالات للبريد الملكي) في عملية فرز البريد الآلية في المملكة المتحدة.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **SCC14**

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **SSCC18**

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Standard 2 of 5**

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


يحدد أن البيانات يجب أن تُفكّ شفرتها باستخدام مواصفة الباركود **Supplement(EAN2, EAN5)**

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **Swiss Post Parcel Barcode**

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


يحدد أن البيانات سيتم فحصها باستخدام جميع رموز الباركود **1D**

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


يحدد أن البيانات سيتم فحصها باستخدام جميع رموز الباركود **2D**

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **UPC-A**

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **UPC-E**

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


يحدد أن البيانات يجب أن تُفكّ شفرتها وفقًا لمواصفات الباركود **VIN** (رقم تعريف المركبة)

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


يحصل على مصفوفة تمثل AllSupportedTypes

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


يسترجع مصفوفة بأسماء أنواع فك الترميز.

**Returns:**
java.lang.String[] - مصفوفة سلاسل النصوص لأسماء أنواع فك الترميز.
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


يحدد ما إذا كان BaseDecodeType المحدد يحتوي على أي رموز باركود 1D

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | BaseDecodeType للاختبار. |

**Returns:**
boolean - تُرجع **true** إذا كان BaseDecodeType يحتوي على أي رموز باركود 1D؛ وإلا تُرجع **false**.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


يحدد ما إذا كان BaseDecodeType المحدد يحتوي على أي رموز باركود 2D

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | BaseDecodeType للاختبار. |

**Returns:**
boolean - تُرجع **true** إذا كان BaseDecodeTypeddddddddw يحتوي على أي رموز باركود 2D؛ وإلا تُرجع **false**.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


يحدد ما إذا كان BaseDecodeType المحدد يحتوي على أي رموز باركود بريدية

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | BaseDecodeType للاختبار |

**Returns:**
boolean - تُرجع **true** إذا كان BaseDecodeType يحتوي على أي رموز باركود بريدية؛ وإلا تُرجع **false**.
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


يقوم بتحويل تمثيل السلسلة لـ SingleDecodeType إلى مثاله. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة نصية تحتوي على تمثيل SingleDecodeType للتحويل. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

إلا فإنه يعيد نوعًا غير محدد. أو SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


يقوم بتحويل تمثيل السلسلة لـ SingleDecodeType إلى مثاله. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة تحتوي على SingleDecodeType بالتنسيق مثل "EAN8" أو "EAN13" أو "CodaBar"... للتحويل. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
منطقي - **true** إذا تم تحويل s بنجاح؛ وإلا **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


حدد مجموعات الفحص حسب barcodeTypes

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | مصفوفة من أنواع فك الترميز الفردية والمتعددة |

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


يقوم بتحويل تمثيل السلسلة لـ MultiDecodeType إلى مثاله. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة نصية بالتنسيق إما "AllSupportedTypes" أو "EAN8,EAN13,CodaBar" للتحويل. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - يتم إرجاع MultiDecodeType فعلي عندما تكتمل عملية التحويل بنجاح؛ وإلا فإنه يعيد نوعًا غير محدد: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


يقوم بتحويل تمثيل السلسلة لـ SingleDecodeType إلى مثاله. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة تحتوي على SingleDecodeType بالتنسيق مثل "EAN8" أو "EAN13" أو "CodaBar"... للتحويل. |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

