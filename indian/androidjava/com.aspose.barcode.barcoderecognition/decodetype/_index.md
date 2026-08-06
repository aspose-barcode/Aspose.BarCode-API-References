---
title: DecodeType
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: Specify the type of barcode to read.
type: docs
weight: 32
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
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

| Constructor | विवरण |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | निर्दिष्ट करता है कि डेटा सभी उपलब्ध सिम्बोलॉजीज के साथ जांचा जाएगा |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | निर्दिष्ट करता है कि डेटा को  **Australian Post Domestic eParcel Barcode**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | निर्दिष्ट करता है कि डेटा को  **Australia Post**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| [AZTEC](#AZTEC) | निर्दिष्ट करता है कि डेटा को  **Aztec**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| [CODABAR](#CODABAR) | निर्दिष्ट करता है कि डेटा को  **CODABAR**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| [CODABLOCK_F](#CODABLOCK-F) | निर्दिष्ट करता है कि डेटा को  **CodablockF**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| [CODE_11](#CODE-11) | निर्दिष्ट करता है कि डेटा को  **CODE 11**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए |
| [CODE_128](#CODE-128) | निर्दिष्ट करता है कि डेटा को **CODE 128** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [CODE_16_K](#CODE-16-K) | निर्दिष्ट करता है कि डेटा को **SCode16K** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [CODE_32](#CODE-32) | निर्दिष्ट करता है कि डेटा को **Code32** बारकोड विनिर्�्देशन के साथ डिकोड किया जाना चाहिए |
| [CODE_39](#CODE-39) | निर्दिष्ट करता है कि डेटा को **Code 39** बेसिक कैरसेट बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | निर्दिष्ट करता है कि डेटा को **Code 39** फुल ASCII कैरसेट बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | निर्दिष्ट करता है कि डेटा को **CODE 93** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | निर्दिष्ट करता है कि डेटा को **CompactPdf417** (Pdf417Truncated) बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | निर्दिष्ट करता है कि डेटा को **GS1 DATABAR expanded** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | निर्दिष्ट करता है कि डेटा को **GS1 DATABAR expanded stacked** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | निर्दिष्ट करता है कि डेटा को **GS1 DATABAR limited** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | निर्दिष्ट करता है कि डेटा को **GS1 DATABAR omni-directional** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DATABAR_STACKED](#DATABAR-STACKED) | निर्दिष्ट करता है कि डेटा को **GS1 DATABAR stacked** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | निर्दिष्ट करता है कि डेटा को **GS1 DATABAR stacked omni-directional** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | निर्दिष्ट करता है कि डेटा को **GS1 DATABAR truncated** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | निर्दिष्ट करता है कि डेटा को **DataLogic 2 of 5** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DATA_MATRIX](#DATA-MATRIX) | निर्दिष्ट करता है कि डेटा को **DataMatrix** बारकोड सिम्बोलॉजी के साथ डिकोड किया जाना चाहिए |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | निर्दिष्ट करता है कि डेटा को **DeutschePost Ident code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | निर्दिष्ट करता है कि डेटा को **DeutschePost Leit code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DOT_CODE](#DOT-CODE) | निर्दिष्ट करता है कि डेटा को **DotCode** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [DUTCH_KIX](#DUTCH-KIX) | निर्दिष्ट करता है कि डेटा को **DotCode** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [EAN_13](#EAN-13) | निर्दिष्ट करता है कि डेटा को **EAN-13** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [EAN_14](#EAN-14) | निर्दिष्ट करता है कि डेटा को **EAN14** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [EAN_8](#EAN-8) | निर्दिष्ट करता है कि डेटा को **EAN-8** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [GS_1_AZTEC](#GS-1-AZTEC) | निर्दिष्ट करता है कि डेटा को **GS1 Aztec** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [GS_1_CODE_128](#GS-1-CODE-128) | निर्दिष्ट करता है कि डेटा को **GS1 CODE 128** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | निर्दिष्ट करता है कि डेटा को **GS1 Composite Bar** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | निर्दिष्ट करता है कि डेटा को  **GS1DataMatrix**  बारकोड प्रतीक के साथ डिकोड किया जाना चाहिए |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | निर्दिष्ट करता है कि डेटा को  **GS1 DotCode**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | निर्दिष्ट करता है कि डेटा को **GS1 Han Xin Code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | निर्दिष्ट करता है कि डेटा को **MicroPdf417** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [GS_1_QR](#GS-1-QR) | निर्दिष्ट करता है कि डेटा को  **GS1 QR**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [HAN_XIN](#HAN-XIN) | निर्दिष्ट करता है कि डेटा को **Han Xin Code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [HIBCQRLIC](#HIBCQRLIC) | निर्दिष्ट करता है कि डेटा को  **HIBC LIC QR**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [HIBCQRPAS](#HIBCQRPAS) | निर्दिष्ट करता है कि डेटा को  **HIBC PAS QR**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | निर्दिष्ट करता है कि डेटा को  **HIBC LIC Aztec**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | निर्दिष्ट करता है कि डेटा को  **HIBC PAS Aztec**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | निर्दिष्ट करता है कि डेटा को  **HIBC LIC Code128**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | निर्दिष्ट करता है कि डेटा को  **HIBC PAS Code128**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | निर्दिष्ट करता है कि डेटा को  **HIBC LIC Code39**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | निर्दिष्ट करता है कि डेटा को  **HIBC PAS Code39**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | निर्दिष्ट करता है कि डेटा को  **HIBC LIC DataMatrix**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | निर्दिष्ट करता है कि डेटा को  **HIBC PAS DataMatrix**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [IATA_2_OF_5](#IATA-2-OF-5) | निर्दिष्ट करता है कि डेटा को  **IATA 2 of 5**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | निर्दिष्ट करता है कि डेटा को  **INTERLEAVED 2 of 5**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [ISBN](#ISBN) | निर्दिष्ट करता है कि डेटा को  **ISBN**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [ISMN](#ISMN) | निर्दिष्ट करता है कि डेटा को  **ISMN**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [ISSN](#ISSN) | निर्दिष्ट करता है कि डेटा को  **ISSN**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | निर्दिष्ट करता है कि डेटा को  **Italian Post 25**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [ITF_14](#ITF-14) | निर्दिष्ट करता है कि डेटा को  **ITF14**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [ITF_6](#ITF-6) | निर्दिष्ट करता है कि डेटा को  **ITF6**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [MACRO_PDF_417](#MACRO-PDF-417) | निर्दिष्ट करता है कि डेटा को  **MacroPdf417**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [MAILMARK](#MAILMARK) | निर्दिष्ट करता है कि डेटा को **Royal Mail Mailmark** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | निर्दिष्ट करता है कि डेटा को  **Matrix 2 of 5**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [MAXI_CODE](#MAXI-CODE) | निर्दिष्ट करता है कि डेटा को  **MaxiCode**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [MICRO_PDF_417](#MICRO-PDF-417) | निर्दिष्ट करता है कि डेटा को  **MicroPdf417**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [MICRO_QR](#MICRO-QR) | निर्दिष्ट करता है कि डेटा को  **MicroQR Code**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [MICR_E_13_B](#MICR-E-13-B) | निर्दिष्ट करता है कि डेटा को  **MICR E-13B**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | निर्दिष्ट करता है कि डेटा को सबसे अधिक प्रयुक्त प्रतीकों के साथ जाँच किया जाएगा |
| [MSI](#MSI) | निर्दिष्ट करता है कि डेटा को  **MSI Plessey**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [NONE](#NONE) | अस्पष्ट डिकोड प्रकार। |
| [ONE_CODE](#ONE-CODE) | निर्दिष्ट करता है कि डेटा को USPS  **OneCode**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [OPC](#OPC) | निर्दिष्ट करता है कि डेटा को  **OPC**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [PATCH_CODE](#PATCH-CODE) | निर्दिष्ट करता है कि डेटा को  **Patch code**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। |
| [PDF_417](#PDF-417) | निर्दिष्ट करता है कि डेटा को  **Pdf417**  बारकोड प्रतीक के साथ डिकोड किया जाना चाहिए |
| [PHARMACODE](#PHARMACODE) | निर्दिष्ट करता है कि डेटा को  **Pharmacode**  बारकोड के साथ डिकोड किया जाना चाहिए। |
| [PLANET](#PLANET) | निर्दिष्ट करता है कि डेटा को  **Planet**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [POSTAL_TYPES](#POSTAL-TYPES) | निर्दिष्ट करता है कि डेटा को सभी **1.5D POSTAL** बारकोड प्रतीकों के साथ जाँच किया जाएगा, जैसे **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | निर्दिष्ट करता है कि डेटा को  **Postnet**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [PZN](#PZN) | निर्दिष्ट करता है कि डेटा को  **PZN**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। |
| [QR](#QR) | निर्दिष्ट करता है कि डेटा को  **QR Code**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | निर्दिष्ट करता है कि डेटा को **RectMicroQR (rMQR) Code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [RM_4_SCC](#RM-4-SCC) | निर्दिष्ट करता है कि डेटा को  **RM4SCC**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। |
| [SCC_14](#SCC-14) | निर्दिष्ट करता है कि डेटा को  **SCC14**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [SSCC_18](#SSCC-18) | निर्दिष्ट करता है कि डेटा को  **SSCC18**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | निर्दिष्ट करता है कि डेटा को  **Standard 2 of 5**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [SUPPLEMENT](#SUPPLEMENT) | निर्दिष्ट करता है कि डेटा को  **Supplement(EAN2, EAN5)**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | निर्दिष्ट करता है कि डेटा को  **Swiss Post Parcel Barcode**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [TYPES_1D](#TYPES-1D) | निर्दिष्ट करता है कि डेटा को सभी **1D** बारकोड सिम्बोलॉजीज़ के साथ जाँच किया जाएगा |
| [TYPES_2D](#TYPES-2D) | निर्दिष्ट करता है कि डेटा को सभी **2D** बारकोड सिम्बोलॉजीज़ के साथ जाँच किया जाएगा |
| [UPCA](#UPCA) | निर्दिष्ट करता है कि डेटा को  **UPC-A**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [UPCE](#UPCE) | निर्दिष्ट करता है कि डेटा को  **UPC-E**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
| [VIN](#VIN) | निर्दिष्ट करता है कि डेटा को  **VIN**  (वाहन पहचान संख्या) बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | AllSupportedTypes को दर्शाने वाला एक एरे प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | डिकोड प्रकारों के नामों का एरे पुनः प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | निर्धारित करता है कि निर्दिष्ट BaseDecodeType में कोई भी 1D बारकोड सिम्बोलॉजी है या नहीं |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | निर्धारित करता है कि निर्दिष्ट BaseDecodeType में कोई भी 2D बारकोड सिम्बोलॉजी है या नहीं |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | निर्धारित करता है कि निर्दिष्ट BaseDecodeType में कोई भी डाक बारकोड सिम्बोलॉजी है या नहीं |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | बारकोड प्रकारों द्वारा स्कैन सेट निर्दिष्ट करें |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
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


निर्दिष्ट करता है कि डेटा सभी उपलब्ध सिम्बोलॉजीज के साथ जांचा जाएगा

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


निर्दिष्ट करता है कि डेटा को  **Australian Post Domestic eParcel Barcode**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


निर्दिष्ट करता है कि डेटा को  **Australia Post**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


निर्दिष्ट करता है कि डेटा को  **Aztec**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


निर्दिष्ट करता है कि डेटा को  **CODABAR**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


निर्दिष्ट करता है कि डेटा को  **CodablockF**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


निर्दिष्ट करता है कि डेटा को  **CODE 11**  बारकोड विनिर्देश के साथ डिकोड किया जाना चाहिए

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


निर्दिष्ट करता है कि डेटा को **CODE 128** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


निर्दिष्ट करता है कि डेटा को **SCode16K** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


निर्दिष्ट करता है कि डेटा को **Code32** बारकोड विनिर्�्देशन के साथ डिकोड किया जाना चाहिए

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


निर्दिष्ट करता है कि डेटा को **Code 39** बेसिक कैरसेट बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


निर्दिष्ट करता है कि डेटा को **Code 39** फुल ASCII कैरसेट बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


निर्दिष्ट करता है कि डेटा को **CODE 93** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


निर्दिष्ट करता है कि डेटा को **CompactPdf417** (Pdf417Truncated) बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


निर्दिष्ट करता है कि डेटा को **GS1 DATABAR expanded** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


निर्दिष्ट करता है कि डेटा को **GS1 DATABAR expanded stacked** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


निर्दिष्ट करता है कि डेटा को **GS1 DATABAR limited** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


निर्दिष्ट करता है कि डेटा को **GS1 DATABAR omni-directional** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


निर्दिष्ट करता है कि डेटा को **GS1 DATABAR stacked** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


निर्दिष्ट करता है कि डेटा को **GS1 DATABAR stacked omni-directional** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


निर्दिष्ट करता है कि डेटा को **GS1 DATABAR truncated** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


निर्दिष्ट करता है कि डेटा को **DataLogic 2 of 5** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


निर्दिष्ट करता है कि डेटा को **DataMatrix** बारकोड सिम्बोलॉजी के साथ डिकोड किया जाना चाहिए

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


निर्दिष्ट करता है कि डेटा को **DeutschePost Ident code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


निर्दिष्ट करता है कि डेटा को **DeutschePost Leit code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


निर्दिष्ट करता है कि डेटा को **DotCode** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


निर्दिष्ट करता है कि डेटा को **DotCode** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


निर्दिष्ट करता है कि डेटा को **EAN-13** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


निर्दिष्ट करता है कि डेटा को **EAN14** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


निर्दिष्ट करता है कि डेटा को **EAN-8** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


निर्दिष्ट करता है कि डेटा को **GS1 Aztec** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


निर्दिष्ट करता है कि डेटा को **GS1 CODE 128** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


निर्दिष्ट करता है कि डेटा को **GS1 Composite Bar** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


निर्दिष्ट करता है कि डेटा को  **GS1DataMatrix**  बारकोड प्रतीक के साथ डिकोड किया जाना चाहिए

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


निर्दिष्ट करता है कि डेटा को  **GS1 DotCode**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


निर्दिष्ट करता है कि डेटा को **GS1 Han Xin Code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


निर्दिष्ट करता है कि डेटा को **MicroPdf417** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


निर्दिष्ट करता है कि डेटा को  **GS1 QR**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


निर्दिष्ट करता है कि डेटा को **Han Xin Code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


निर्दिष्ट करता है कि डेटा को  **HIBC LIC QR**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


निर्दिष्ट करता है कि डेटा को  **HIBC PAS QR**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


निर्दिष्ट करता है कि डेटा को  **HIBC LIC Aztec**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


निर्दिष्ट करता है कि डेटा को  **HIBC PAS Aztec**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


निर्दिष्ट करता है कि डेटा को  **HIBC LIC Code128**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


निर्दिष्ट करता है कि डेटा को  **HIBC PAS Code128**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


निर्दिष्ट करता है कि डेटा को  **HIBC LIC Code39**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


निर्दिष्ट करता है कि डेटा को  **HIBC PAS Code39**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


निर्दिष्ट करता है कि डेटा को  **HIBC LIC DataMatrix**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


निर्दिष्ट करता है कि डेटा को  **HIBC PAS DataMatrix**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


निर्दिष्ट करता है कि डेटा को  **IATA 2 of 5**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। IATA (अंतर्राष्ट्रीय हवाई परिवहन संघ) इस बारकोड का उपयोग हवाई माल के प्रबंधन के लिए करता है।

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


निर्दिष्ट करता है कि डेटा को  **INTERLEAVED 2 of 5**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


निर्दिष्ट करता है कि डेटा को  **ISBN**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


निर्दिष्ट करता है कि डेटा को  **ISMN**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


निर्दिष्ट करता है कि डेटा को  **ISSN**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


निर्दिष्ट करता है कि डेटा को  **Italian Post 25**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


निर्दिष्ट करता है कि डेटा को  **ITF14**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


निर्दिष्ट करता है कि डेटा को  **ITF6**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


निर्दिष्ट करता है कि डेटा को  **MacroPdf417**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


निर्दिष्ट करता है कि डेटा को **Royal Mail Mailmark** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए।

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


निर्दिष्ट करता है कि डेटा को  **Matrix 2 of 5**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


निर्दिष्ट करता है कि डेटा को  **MaxiCode**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


निर्दिष्ट करता है कि डेटा को  **MicroPdf417**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


निर्दिष्ट करता है कि डेटा को  **MicroQR Code**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


निर्दिष्ट करता है कि डेटा को  **MICR E-13B**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


निर्दिष्ट करता है कि डेटा को सबसे अधिक प्रयुक्त प्रतीकों के साथ जाँच किया जाएगा

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


निर्दिष्ट करता है कि डेटा को  **MSI Plessey**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


अस्पष्ट डिकोड प्रकार।

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


निर्दिष्ट करता है कि डेटा को USPS  **OneCode**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


निर्दिष्ट करता है कि डेटा को  **OPC**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


निर्दिष्ट करता है कि डेटा को  **Patch code**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। बारकोड सिम्बोलॉजी स्वचालित स्कैनिंग के लिए उपयोग की जाती है

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


निर्दिष्ट करता है कि डेटा को  **Pdf417**  बारकोड प्रतीक के साथ डिकोड किया जाना चाहिए

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


निर्दिष्ट करता है कि डेटा को  **Pharmacode**  बारकोड के साथ डिकोड किया जाना चाहिए। यह सिम्बोलॉजी फ़ार्मास्यूटिकल बाइनरी कोड के नाम से भी जानी जाती है

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


निर्दिष्ट करता है कि डेटा को  **Planet**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


निर्दिष्ट करता है कि डेटा को सभी **1.5D POSTAL** बारकोड प्रतीकों के साथ जाँच किया जाएगा, जैसे **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


निर्दिष्ट करता है कि डेटा को  **Postnet**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


निर्दिष्ट करता है कि डेटा को  **PZN**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। यह सिम्बोलॉजी Pharma Zentral Nummer के नाम से भी जानी जाती है। PZN7 और PZN8 समर्थित हैं।

### QR {#QR}
```
public static final SingleDecodeType QR
```


निर्दिष्ट करता है कि डेटा को  **QR Code**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


निर्दिष्ट करता है कि डेटा को **RectMicroQR (rMQR) Code** बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


निर्दिष्ट करता है कि डेटा को  **RM4SCC**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए। RM4SCC (रॉयल मेल 4-स्टेट कस्टमर कोड) यूके में स्वचालित मेल सॉर्ट प्रक्रिया के लिए उपयोग किया जाता है।

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


निर्दिष्ट करता है कि डेटा को  **SCC14**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


निर्दिष्ट करता है कि डेटा को  **SSCC18**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


निर्दिष्ट करता है कि डेटा को  **Standard 2 of 5**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


निर्दिष्ट करता है कि डेटा को  **Supplement(EAN2, EAN5)**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


निर्दिष्ट करता है कि डेटा को  **Swiss Post Parcel Barcode**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


निर्दिष्ट करता है कि डेटा को सभी **1D** बारकोड सिम्बोलॉजीज़ के साथ जाँच किया जाएगा

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


निर्दिष्ट करता है कि डेटा को सभी **2D** बारकोड सिम्बोलॉजीज़ के साथ जाँच किया जाएगा

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


निर्दिष्ट करता है कि डेटा को  **UPC-A**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


निर्दिष्ट करता है कि डेटा को  **UPC-E**  बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


निर्दिष्ट करता है कि डेटा को  **VIN**  (वाहन पहचान संख्या) बारकोड विनिर्देशन के साथ डिकोड किया जाना चाहिए

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


AllSupportedTypes को दर्शाने वाला एक एरे प्राप्त करता है

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


डिकोड प्रकारों के नामों का एरे पुनः प्राप्त करता है।

**Returns:**
java.lang.String[] - डिकोड प्रकारों के नामों का स्ट्रिंग एरे।
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


निर्धारित करता है कि निर्दिष्ट BaseDecodeType में कोई भी 1D बारकोड सिम्बोलॉजी है या नहीं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | परीक्षण के लिए BaseDecodeType। |

**Returns:**
boolean - यदि BaseDecodeType में कोई भी 1D बारकोड सिम्बोलॉजी है तो **true** लौटाता है; अन्यथा **false** लौटाता है।
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


निर्धारित करता है कि निर्दिष्ट BaseDecodeType में कोई भी 2D बारकोड सिम्बोलॉजी है या नहीं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | परीक्षण के लिए BaseDecodeType। |

**Returns:**
boolean - यदि BaseDecodeTypeddddddddw में कोई भी 2D बारकोड सिम्बोलॉजी है तो **true** लौटाता है; अन्यथा **false** लौटाता है।
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


निर्धारित करता है कि निर्दिष्ट BaseDecodeType में कोई भी डाक बारकोड सिम्बोलॉजी है या नहीं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | परीक्षण के लिए BaseDecodeType |

**Returns:**
boolean - यदि BaseDecodeType में कोई भी डाक बारकोड सिम्बोलॉजी है तो **true** लौटाता है; अन्यथा **false** लौटाता है।
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


SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें परिवर्तित करने के लिए SingleDecodeType प्रतिनिधित्व शामिल है। |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

अन्यथा यह अनिश्चित प्रकार लौटाता है। या SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें \"EAN8\" या \"EAN13\" या \"CodaBar\"... के रूप में SingleDecodeType होता है, जिसे परिवर्तित किया जाना है। |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - यदि s सफलतापूर्वक परिवर्तित हुआ तो **true**; अन्यथा, **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


बारकोड प्रकारों द्वारा स्कैन सेट निर्दिष्ट करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | एकल और मल्टी डिकोड प्रकारों की सरणी |

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


MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | परिवर्तित करने के लिए एक स्ट्रिंग जिसका स्वरूप "AllSupportedTypes" या "EAN8,EAN13,CodaBar" हो। |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - जब रूपांतरण सफलतापूर्वक पूरा हो जाता है तो वास्तविक MultiDecodeType लौटाया जाता है; अन्यथा यह अनिश्चित प्रकार लौटाता है: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें \"EAN8\" या \"EAN13\" या \"CodaBar\"... के रूप में SingleDecodeType होता है, जिसे परिवर्तित किया जाना है। |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

