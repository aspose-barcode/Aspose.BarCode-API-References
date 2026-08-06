---
title: DecodeType
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Καθορίστε τον τύπο του barcode που θα διαβαστεί.
type: docs
weight: 32
url: /el/androidjava/com.aspose.barcode.barcoderecognition/decodetype/
---
**Inheritance:**
java.lang.Object
```
public class DecodeType
```

Καθορίστε τον τύπο του barcode που θα διαβαστεί.

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

| Constructor | Περιγραφή |
| --- | --- |
| [DecodeType()](#DecodeType--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ALL_SUPPORTED_TYPES](#ALL-SUPPORTED-TYPES) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλες τις διαθέσιμες συμβολισμούς. |
| [AUSTRALIAN_POSTE_PARCEL](#AUSTRALIAN-POSTE-PARCEL) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Australian Post Domestic eParcel Barcode** |
| [AUSTRALIA_POST](#AUSTRALIA-POST) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Australia Post** |
| [AZTEC](#AZTEC) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Aztec** |
| [CODABAR](#CODABAR) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **CODABAR** |
| [CODABLOCK_F](#CODABLOCK-F) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **CodablockF** |
| [CODE_11](#CODE-11) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **CODE 11** |
| [CODE_128](#CODE-128) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **CODE 128**  προδιαγραφή barcode |
| [CODE_16_K](#CODE-16-K) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **SCode16K**  προδιαγραφή barcode |
| [CODE_32](#CODE-32) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **Code32**  προδιαγραφή barcode |
| [CODE_39](#CODE-39) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **Code 39**  προδιαγραφή barcode βασικού συνόλου χαρακτήρων: ISO/IEC 16388 |
| [CODE_39_FULL_ASCII](#CODE-39-FULL-ASCII) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **Code 39**  προδιαγραφή barcode πλήρους συνόλου χαρακτήρων ASCII: ISO/IEC 16388 |
| [CODE_93](#CODE-93) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **CODE 93**  προδιαγραφή barcode |
| [COMPACT_PDF_417](#COMPACT-PDF-417) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **CompactPdf417**  (Pdf417Truncated) προδιαγραφή barcode |
| [DATABAR_EXPANDED](#DATABAR-EXPANDED) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR expanded**  προδιαγραφή barcode |
| [DATABAR_EXPANDED_STACKED](#DATABAR-EXPANDED-STACKED) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR expanded stacked**  προδιαγραφή barcode |
| [DATABAR_LIMITED](#DATABAR-LIMITED) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR limited**  προδιαγραφή barcode |
| [DATABAR_OMNI_DIRECTIONAL](#DATABAR-OMNI-DIRECTIONAL) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR omni-directional**  προδιαγραφή barcode |
| [DATABAR_STACKED](#DATABAR-STACKED) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR stacked**  προδιαγραφή barcode |
| [DATABAR_STACKED_OMNI_DIRECTIONAL](#DATABAR-STACKED-OMNI-DIRECTIONAL) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR stacked omni-directional**  προδιαγραφή barcode |
| [DATABAR_TRUNCATED](#DATABAR-TRUNCATED) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR truncated**  προδιαγραφή barcode |
| [DATA_LOGIC_2_OF_5](#DATA-LOGIC-2-OF-5) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DataLogic 2 of 5**  προδιαγραφή barcode |
| [DATA_MATRIX](#DATA-MATRIX) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DataMatrix**  συμβολική αναπαράσταση barcode |
| [DEUTSCHE_POST_IDENTCODE](#DEUTSCHE-POST-IDENTCODE) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DeutschePost Ident code**  προδιαγραφή barcode |
| [DEUTSCHE_POST_LEITCODE](#DEUTSCHE-POST-LEITCODE) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DeutschePost Leit code**  προδιαγραφή barcode |
| [DOT_CODE](#DOT-CODE) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DotCode**  προδιαγραφή barcode |
| [DUTCH_KIX](#DUTCH-KIX) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DotCode**  προδιαγραφή barcode |
| [EAN_13](#EAN-13) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **EAN-13**  προδιαγραφή barcode |
| [EAN_14](#EAN-14) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **EAN14**  προδιαγραφή barcode |
| [EAN_8](#EAN-8) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **EAN-8**  προδιαγραφή barcode |
| [GS_1_AZTEC](#GS-1-AZTEC) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 Aztec**  προδιαγραφή barcode |
| [GS_1_CODE_128](#GS-1-CODE-128) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 CODE 128**  προδιαγραφή barcode |
| [GS_1_COMPOSITE_BAR](#GS-1-COMPOSITE-BAR) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 Composite Bar**  προδιαγραφή barcode |
| [GS_1_DATA_MATRIX](#GS-1-DATA-MATRIX) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1DataMatrix**  συμβολοσειρά barcode |
| [GS_1_DOT_CODE](#GS-1-DOT-CODE) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DotCode**  προδιαγραφή barcode |
| [GS_1_HAN_XIN](#GS-1-HAN-XIN) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **GS1 Han Xin Code** προδιαγραφή barcode |
| [GS_1_MICRO_PDF_417](#GS-1-MICRO-PDF-417) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **MicroPdf417** προδιαγραφή barcode |
| [GS_1_QR](#GS-1-QR) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 QR**  προδιαγραφή barcode |
| [HAN_XIN](#HAN-XIN) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **Han Xin Code** προδιαγραφή barcode |
| [HIBCQRLIC](#HIBCQRLIC) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC LIC QR**  προδιαγραφή barcode |
| [HIBCQRPAS](#HIBCQRPAS) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC PAS QR**  προδιαγραφή barcode |
| [HIBC_AZTEC_LIC](#HIBC-AZTEC-LIC) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC LIC Aztec**  προδιαγραφή barcode |
| [HIBC_AZTEC_PAS](#HIBC-AZTEC-PAS) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC PAS Aztec**  προδιαγραφή barcode |
| [HIBC_CODE_128_LIC](#HIBC-CODE-128-LIC) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC LIC Code128**  προδιαγραφή barcode |
| [HIBC_CODE_128_PAS](#HIBC-CODE-128-PAS) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC PAS Code128**  προδιαγραφή barcode |
| [HIBC_CODE_39_LIC](#HIBC-CODE-39-LIC) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC LIC Code39**  προδιαγραφή barcode |
| [HIBC_CODE_39_PAS](#HIBC-CODE-39-PAS) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC PAS Code39**  προδιαγραφή barcode |
| [HIBC_DATA_MATRIX_LIC](#HIBC-DATA-MATRIX-LIC) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC LIC DataMatrix**  προδιαγραφή barcode |
| [HIBC_DATA_MATRIX_PAS](#HIBC-DATA-MATRIX-PAS) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC PAS DataMatrix**  προδιαγραφή barcode |
| [IATA_2_OF_5](#IATA-2-OF-5) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **IATA 2 of 5**  προδιαγραφή barcode. |
| [INTERLEAVED_2_OF_5](#INTERLEAVED-2-OF-5) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **INTERLEAVED 2 of 5**  προδιαγραφή barcode |
| [ISBN](#ISBN) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **ISBN**  προδιαγραφή barcode |
| [ISMN](#ISMN) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **ISMN**  προδιαγραφή barcode |
| [ISSN](#ISSN) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **ISSN**  προδιαγραφή barcode |
| [ITALIAN_POST_25](#ITALIAN-POST-25) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **Italian Post 25**  προδιαγραφή barcode |
| [ITF_14](#ITF-14) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **ITF14**  προδιαγραφή barcode |
| [ITF_6](#ITF-6) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **ITF6**  προδιαγραφή barcode |
| [MACRO_PDF_417](#MACRO-PDF-417) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **MacroPdf417**  προδιαγραφή barcode |
| [MAILMARK](#MAILMARK) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Royal Mail Mailmark**. |
| [MATRIX_2_OF_5](#MATRIX-2-OF-5) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Matrix 2 of 5** |
| [MAXI_CODE](#MAXI-CODE) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MaxiCode** |
| [MICRO_PDF_417](#MICRO-PDF-417) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MicroPdf417** |
| [MICRO_QR](#MICRO-QR) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MicroQR Code** |
| [MICR_E_13_B](#MICR-E-13-B) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MICR E-13B** |
| [MOST_COMMON_TYPES](#MOST-COMMON-TYPES) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με τις πιο συχνά χρησιμοποιούμενες συμβολές |
| [MSI](#MSI) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MSI Plessey** |
| [NONE](#NONE) | Μη καθορισμένος τύπος αποκωδικοποίησης. |
| [ONE_CODE](#ONE-CODE) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode USPS **OneCode** |
| [OPC](#OPC) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **OPC** |
| [PATCH_CODE](#PATCH-CODE) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Patch code**. |
| [PDF_417](#PDF-417) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με συμβολή barcode **Pdf417** |
| [PHARMACODE](#PHARMACODE) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με barcode **Pharmacode**. |
| [PLANET](#PLANET) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Planet** |
| [POSTAL_TYPES](#POSTAL-TYPES) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλες τις συμβολές barcode **1.5D POSTAL**, όπως **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| [POSTNET](#POSTNET) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Postnet** |
| [PZN](#PZN) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **PZN**. |
| [QR](#QR) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **QR Code** |
| [RECT_MICRO_QR](#RECT-MICRO-QR) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **RectMicroQR (rMQR) Code** |
| [RM_4_SCC](#RM-4-SCC) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **RM4SCC**. |
| [SCC_14](#SCC-14) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **SCC14** |
| [SSCC_18](#SSCC-18) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **SSCC18** |
| [STANDARD_2_OF_5](#STANDARD-2-OF-5) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Standard 2 of 5** |
| [SUPPLEMENT](#SUPPLEMENT) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Supplement(EAN2, EAN5)** |
| [SWISS_POST_PARCEL](#SWISS-POST-PARCEL) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Swiss Post Parcel Barcode**. |
| [TYPES_1D](#TYPES-1D) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλους τους συμβολισμούς barcode **1D**. |
| [TYPES_2D](#TYPES-2D) | Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλους τους συμβολισμούς barcode **2D**. |
| [UPCA](#UPCA) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **UPC-A**. |
| [UPCE](#UPCE) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **UPC-E**. |
| [VIN](#VIN) | Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **VIN** (Αριθμός Αναγνώρισης Οχήματος). |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllSupportedTypesArray()](#getAllSupportedTypesArray--) | Λαμβάνει έναν πίνακα που αντιπροσωπεύει το AllSupportedTypes. |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Ανακτά έναν πίνακα με τα ονόματα των τύπων αποκωδικοποίησης. |
| [hashCode()](#hashCode--) |  |
| [is1D(BaseDecodeType symbology)](#is1D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Καθορίζει εάν το συγκεκριμένο BaseDecodeType περιέχει κάποιον συμβολισμό barcode 1D. |
| [is2D(BaseDecodeType symbology)](#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Καθορίζει εάν το συγκεκριμένο BaseDecodeType περιέχει κάποιον συμβολισμό barcode 2D. |
| [isPostal(BaseDecodeType symbology)](#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-) | Καθορίζει εάν το συγκεκριμένο BaseDecodeType περιέχει κάποιον ταχυδρομικό συμβολισμό barcode. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String parsingType)](#parse-java.lang.String-) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. |
| [parse(String parsingType, SingleDecodeType[] result)](#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. |
| [scanSets(BaseDecodeType[] barcodeTypes)](#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Καθορίστε σύνολα σάρωσης με βάση τα barcodeTypes. |
| [toString()](#toString--) |  |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός MultiDecodeType στην παρουσία του. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. |
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


Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλες τις διαθέσιμες συμβολισμούς.

### AUSTRALIAN_POSTE_PARCEL {#AUSTRALIAN-POSTE-PARCEL}
```
public static final SingleDecodeType AUSTRALIAN_POSTE_PARCEL
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Australian Post Domestic eParcel Barcode**

### AUSTRALIA_POST {#AUSTRALIA-POST}
```
public static final SingleDecodeType AUSTRALIA_POST
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Australia Post**

### AZTEC {#AZTEC}
```
public static final SingleDecodeType AZTEC
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **Aztec**

### CODABAR {#CODABAR}
```
public static final SingleDecodeType CODABAR
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **CODABAR**

### CODABLOCK_F {#CODABLOCK-F}
```
public static final SingleDecodeType CODABLOCK_F
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **CodablockF**

### CODE_11 {#CODE-11}
```
public static final SingleDecodeType CODE_11
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με την προδιαγραφή barcode **CODE 11**

### CODE_128 {#CODE-128}
```
public static final SingleDecodeType CODE_128
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **CODE 128**  προδιαγραφή barcode

### CODE_16_K {#CODE-16-K}
```
public static final SingleDecodeType CODE_16_K
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **SCode16K**  προδιαγραφή barcode

### CODE_32 {#CODE-32}
```
public static final SingleDecodeType CODE_32
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **Code32**  προδιαγραφή barcode

### CODE_39 {#CODE-39}
```
public static final SingleDecodeType CODE_39
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **Code 39**  προδιαγραφή barcode βασικού συνόλου χαρακτήρων: ISO/IEC 16388

### CODE_39_FULL_ASCII {#CODE-39-FULL-ASCII}
```
public static final SingleDecodeType CODE_39_FULL_ASCII
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **Code 39**  προδιαγραφή barcode πλήρους συνόλου χαρακτήρων ASCII: ISO/IEC 16388

### CODE_93 {#CODE-93}
```
public static final SingleDecodeType CODE_93
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **CODE 93**  προδιαγραφή barcode

### COMPACT_PDF_417 {#COMPACT-PDF-417}
```
public static final SingleDecodeType COMPACT_PDF_417
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **CompactPdf417**  (Pdf417Truncated) προδιαγραφή barcode

### DATABAR_EXPANDED {#DATABAR-EXPANDED}
```
public static final SingleDecodeType DATABAR_EXPANDED
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR expanded**  προδιαγραφή barcode

### DATABAR_EXPANDED_STACKED {#DATABAR-EXPANDED-STACKED}
```
public static final SingleDecodeType DATABAR_EXPANDED_STACKED
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR expanded stacked**  προδιαγραφή barcode

### DATABAR_LIMITED {#DATABAR-LIMITED}
```
public static final SingleDecodeType DATABAR_LIMITED
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR limited**  προδιαγραφή barcode

### DATABAR_OMNI_DIRECTIONAL {#DATABAR-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_OMNI_DIRECTIONAL
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR omni-directional**  προδιαγραφή barcode

### DATABAR_STACKED {#DATABAR-STACKED}
```
public static final SingleDecodeType DATABAR_STACKED
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR stacked**  προδιαγραφή barcode

### DATABAR_STACKED_OMNI_DIRECTIONAL {#DATABAR-STACKED-OMNI-DIRECTIONAL}
```
public static final SingleDecodeType DATABAR_STACKED_OMNI_DIRECTIONAL
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR stacked omni-directional**  προδιαγραφή barcode

### DATABAR_TRUNCATED {#DATABAR-TRUNCATED}
```
public static final SingleDecodeType DATABAR_TRUNCATED
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DATABAR truncated**  προδιαγραφή barcode

### DATA_LOGIC_2_OF_5 {#DATA-LOGIC-2-OF-5}
```
public static final SingleDecodeType DATA_LOGIC_2_OF_5
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DataLogic 2 of 5**  προδιαγραφή barcode

### DATA_MATRIX {#DATA-MATRIX}
```
public static final SingleDecodeType DATA_MATRIX
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DataMatrix**  συμβολική αναπαράσταση barcode

### DEUTSCHE_POST_IDENTCODE {#DEUTSCHE-POST-IDENTCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_IDENTCODE
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DeutschePost Ident code**  προδιαγραφή barcode

### DEUTSCHE_POST_LEITCODE {#DEUTSCHE-POST-LEITCODE}
```
public static final SingleDecodeType DEUTSCHE_POST_LEITCODE
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DeutschePost Leit code**  προδιαγραφή barcode

### DOT_CODE {#DOT-CODE}
```
public static final SingleDecodeType DOT_CODE
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DotCode**  προδιαγραφή barcode

### DUTCH_KIX {#DUTCH-KIX}
```
public static final SingleDecodeType DUTCH_KIX
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **DotCode**  προδιαγραφή barcode

### EAN_13 {#EAN-13}
```
public static final SingleDecodeType EAN_13
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **EAN-13**  προδιαγραφή barcode

### EAN_14 {#EAN-14}
```
public static final SingleDecodeType EAN_14
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **EAN14**  προδιαγραφή barcode

### EAN_8 {#EAN-8}
```
public static final SingleDecodeType EAN_8
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **EAN-8**  προδιαγραφή barcode

### GS_1_AZTEC {#GS-1-AZTEC}
```
public static final SingleDecodeType GS_1_AZTEC
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 Aztec**  προδιαγραφή barcode

### GS_1_CODE_128 {#GS-1-CODE-128}
```
public static final SingleDecodeType GS_1_CODE_128
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 CODE 128**  προδιαγραφή barcode

### GS_1_COMPOSITE_BAR {#GS-1-COMPOSITE-BAR}
```
public static final SingleDecodeType GS_1_COMPOSITE_BAR
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 Composite Bar**  προδιαγραφή barcode

### GS_1_DATA_MATRIX {#GS-1-DATA-MATRIX}
```
public static final SingleDecodeType GS_1_DATA_MATRIX
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1DataMatrix**  συμβολοσειρά barcode

### GS_1_DOT_CODE {#GS-1-DOT-CODE}
```
public static final SingleDecodeType GS_1_DOT_CODE
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 DotCode**  προδιαγραφή barcode

### GS_1_HAN_XIN {#GS-1-HAN-XIN}
```
public static final SingleDecodeType GS_1_HAN_XIN
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **GS1 Han Xin Code** προδιαγραφή barcode

### GS_1_MICRO_PDF_417 {#GS-1-MICRO-PDF-417}
```
public static final SingleDecodeType GS_1_MICRO_PDF_417
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **MicroPdf417** προδιαγραφή barcode

### GS_1_QR {#GS-1-QR}
```
public static final SingleDecodeType GS_1_QR
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **GS1 QR**  προδιαγραφή barcode

### HAN_XIN {#HAN-XIN}
```
public static final SingleDecodeType HAN_XIN
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με **Han Xin Code** προδιαγραφή barcode

### HIBCQRLIC {#HIBCQRLIC}
```
public static final SingleDecodeType HIBCQRLIC
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC LIC QR**  προδιαγραφή barcode

### HIBCQRPAS {#HIBCQRPAS}
```
public static final SingleDecodeType HIBCQRPAS
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC PAS QR**  προδιαγραφή barcode

### HIBC_AZTEC_LIC {#HIBC-AZTEC-LIC}
```
public static final SingleDecodeType HIBC_AZTEC_LIC
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC LIC Aztec**  προδιαγραφή barcode

### HIBC_AZTEC_PAS {#HIBC-AZTEC-PAS}
```
public static final SingleDecodeType HIBC_AZTEC_PAS
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC PAS Aztec**  προδιαγραφή barcode

### HIBC_CODE_128_LIC {#HIBC-CODE-128-LIC}
```
public static final SingleDecodeType HIBC_CODE_128_LIC
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC LIC Code128**  προδιαγραφή barcode

### HIBC_CODE_128_PAS {#HIBC-CODE-128-PAS}
```
public static final SingleDecodeType HIBC_CODE_128_PAS
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC PAS Code128**  προδιαγραφή barcode

### HIBC_CODE_39_LIC {#HIBC-CODE-39-LIC}
```
public static final SingleDecodeType HIBC_CODE_39_LIC
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC LIC Code39**  προδιαγραφή barcode

### HIBC_CODE_39_PAS {#HIBC-CODE-39-PAS}
```
public static final SingleDecodeType HIBC_CODE_39_PAS
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC PAS Code39**  προδιαγραφή barcode

### HIBC_DATA_MATRIX_LIC {#HIBC-DATA-MATRIX-LIC}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_LIC
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC LIC DataMatrix**  προδιαγραφή barcode

### HIBC_DATA_MATRIX_PAS {#HIBC-DATA-MATRIX-PAS}
```
public static final SingleDecodeType HIBC_DATA_MATRIX_PAS
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **HIBC PAS DataMatrix**  προδιαγραφή barcode

### IATA_2_OF_5 {#IATA-2-OF-5}
```
public static final SingleDecodeType IATA_2_OF_5
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **IATA 2 of 5**. Η IATA (Διεθνής Ένωση Μεταφορών Αεροπορικού) χρησιμοποιεί αυτό το barcode για τη διαχείριση αεροπορικού φορτίου.

### INTERLEAVED_2_OF_5 {#INTERLEAVED-2-OF-5}
```
public static final SingleDecodeType INTERLEAVED_2_OF_5
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **INTERLEAVED 2 of 5**  προδιαγραφή barcode

### ISBN {#ISBN}
```
public static final SingleDecodeType ISBN
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **ISBN**  προδιαγραφή barcode

### ISMN {#ISMN}
```
public static final SingleDecodeType ISMN
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **ISMN**  προδιαγραφή barcode

### ISSN {#ISSN}
```
public static final SingleDecodeType ISSN
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **ISSN**  προδιαγραφή barcode

### ITALIAN_POST_25 {#ITALIAN-POST-25}
```
public static final SingleDecodeType ITALIAN_POST_25
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **Italian Post 25**  προδιαγραφή barcode

### ITF_14 {#ITF-14}
```
public static final SingleDecodeType ITF_14
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **ITF14**  προδιαγραφή barcode

### ITF_6 {#ITF-6}
```
public static final SingleDecodeType ITF_6
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **ITF6**  προδιαγραφή barcode

### MACRO_PDF_417 {#MACRO-PDF-417}
```
public static final SingleDecodeType MACRO_PDF_417
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με  **MacroPdf417**  προδιαγραφή barcode

### MAILMARK {#MAILMARK}
```
public static final SingleDecodeType MAILMARK
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Royal Mail Mailmark**.

### MATRIX_2_OF_5 {#MATRIX-2-OF-5}
```
public static final SingleDecodeType MATRIX_2_OF_5
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Matrix 2 of 5**

### MAXI_CODE {#MAXI-CODE}
```
public static final SingleDecodeType MAXI_CODE
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MaxiCode**

### MICRO_PDF_417 {#MICRO-PDF-417}
```
public static final SingleDecodeType MICRO_PDF_417
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MicroPdf417**

### MICRO_QR {#MICRO-QR}
```
public static final SingleDecodeType MICRO_QR
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MicroQR Code**

### MICR_E_13_B {#MICR-E-13-B}
```
public static final SingleDecodeType MICR_E_13_B
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MICR E-13B**

### MOST_COMMON_TYPES {#MOST-COMMON-TYPES}
```
public static final MultiDecodeType MOST_COMMON_TYPES
```


Καθορίζει ότι τα δεδομένα θα ελεγχθούν με τις πιο συχνά χρησιμοποιούμενες συμβολές

### MSI {#MSI}
```
public static final SingleDecodeType MSI
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **MSI Plessey**

### NONE {#NONE}
```
public static final SingleDecodeType NONE
```


Μη καθορισμένος τύπος αποκωδικοποίησης.

### ONE_CODE {#ONE-CODE}
```
public static final SingleDecodeType ONE_CODE
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode USPS **OneCode**

### OPC {#OPC}
```
public static final SingleDecodeType OPC
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **OPC**

### PATCH_CODE {#PATCH-CODE}
```
public static final SingleDecodeType PATCH_CODE
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Patch code**. Η συμβολική μορφή barcode χρησιμοποιείται για αυτοματοποιημένη σάρωση.

### PDF_417 {#PDF-417}
```
public static final SingleDecodeType PDF_417
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με συμβολή barcode **Pdf417**

### PHARMACODE {#PHARMACODE}
```
public static final SingleDecodeType PHARMACODE
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με barcode **Pharmacode**. Αυτός ο συμβολισμός είναι επίσης γνωστός ως Φαρμακευτικός Δυαδικός Κώδικας.

### PLANET {#PLANET}
```
public static final SingleDecodeType PLANET
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Planet**

### POSTAL_TYPES {#POSTAL-TYPES}
```
public static final MultiDecodeType POSTAL_TYPES
```


Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλες τις συμβολές barcode **1.5D POSTAL**, όπως **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX**

### POSTNET {#POSTNET}
```
public static final SingleDecodeType POSTNET
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Postnet**

### PZN {#PZN}
```
public static final SingleDecodeType PZN
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **PZN**. Αυτός ο συμβολισμός είναι επίσης γνωστός ως Pharma Zentral Nummer. Υποστηρίζονται τα PZN7 και PZN8.

### QR {#QR}
```
public static final SingleDecodeType QR
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **QR Code**

### RECT_MICRO_QR {#RECT-MICRO-QR}
```
public static final SingleDecodeType RECT_MICRO_QR
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **RectMicroQR (rMQR) Code**

### RM_4_SCC {#RM-4-SCC}
```
public static final SingleDecodeType RM_4_SCC
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **RM4SCC**. Το RM4SCC (Κωδικός Πελάτη 4-Καταστάσεων της Royal Mail) χρησιμοποιείται για αυτοματοποιημένη ταξινόμηση αλληλογραφίας στο Ηνωμένο Βασίλειο.

### SCC_14 {#SCC-14}
```
public static final SingleDecodeType SCC_14
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **SCC14**

### SSCC_18 {#SSCC-18}
```
public static final SingleDecodeType SSCC_18
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **SSCC18**

### STANDARD_2_OF_5 {#STANDARD-2-OF-5}
```
public static final SingleDecodeType STANDARD_2_OF_5
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Standard 2 of 5**

### SUPPLEMENT {#SUPPLEMENT}
```
public static final SingleDecodeType SUPPLEMENT
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Supplement(EAN2, EAN5)**

### SWISS_POST_PARCEL {#SWISS-POST-PARCEL}
```
public static final SingleDecodeType SWISS_POST_PARCEL
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **Swiss Post Parcel Barcode**.

### TYPES_1D {#TYPES-1D}
```
public static final MultiDecodeType TYPES_1D
```


Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλους τους συμβολισμούς barcode **1D**.

### TYPES_2D {#TYPES-2D}
```
public static final MultiDecodeType TYPES_2D
```


Καθορίζει ότι τα δεδομένα θα ελεγχθούν με όλους τους συμβολισμούς barcode **2D**.

### UPCA {#UPCA}
```
public static final SingleDecodeType UPCA
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **UPC-A**.

### UPCE {#UPCE}
```
public static final SingleDecodeType UPCE
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **UPC-E**.

### VIN {#VIN}
```
public static final SingleDecodeType VIN
```


Καθορίζει ότι τα δεδομένα πρέπει να αποκωδικοποιηθούν με προδιαγραφή barcode **VIN** (Αριθμός Αναγνώρισης Οχήματος).

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllSupportedTypesArray() {#getAllSupportedTypesArray--}
```
public static SingleDecodeType[] getAllSupportedTypesArray()
```


Λαμβάνει έναν πίνακα που αντιπροσωπεύει το AllSupportedTypes.

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


Ανακτά έναν πίνακα με τα ονόματα των τύπων αποκωδικοποίησης.

**Returns:**
java.lang.String[] - Ένας πίνακας συμβολοσειρών με τα ονόματα των τύπων αποκωδικοποίησης.
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


Καθορίζει εάν το συγκεκριμένο BaseDecodeType περιέχει κάποιον συμβολισμό barcode 1D.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Το BaseDecodeType προς δοκιμή. |

**Returns:**
boolean - Επιστρέφει **true** εάν το BaseDecodeType περιέχει κάποιον 1D barcode συμβολισμό· διαφορετικά, επιστρέφει **false**.
### is2D(BaseDecodeType symbology) {#is2D-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean is2D(BaseDecodeType symbology)
```


Καθορίζει εάν το συγκεκριμένο BaseDecodeType περιέχει κάποιον συμβολισμό barcode 2D.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Το BaseDecodeType προς δοκιμή. |

**Returns:**
boolean - Επιστρέφει **true** εάν το BaseDecodeTypeddddddddw περιέχει κάποιον 2D barcode συμβολισμό· διαφορετικά, επιστρέφει **false**.
### isPostal(BaseDecodeType symbology) {#isPostal-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public static boolean isPostal(BaseDecodeType symbology)
```


Καθορίζει εάν το συγκεκριμένο BaseDecodeType περιέχει κάποιον ταχυδρομικό συμβολισμό barcode.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| symbology | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Το BaseDecodeType προς δοκιμή |

**Returns:**
boolean - Επιστρέφει **true** εάν το BaseDecodeType περιέχει κάποιον ταχυδρομικό barcode συμβολισμό· διαφορετικά, επιστρέφει **false**.
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


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην αντίστοιχη παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Μια συμβολοσειρά που περιέχει μια αναπαράσταση SingleDecodeType για μετατροπή. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType returns, when conversion has completed successfully;

διαφορετικά επιστρέφει αόριστο τύπο. ή SingleDecodeType (-1, "NONE").
### parse(String parsingType, SingleDecodeType[] result) {#parse-java.lang.String-com.aspose.barcode.barcoderecognition.SingleDecodeType---}
```
public static boolean parse(String parsingType, SingleDecodeType[] result)
```


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην αντίστοιχη παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Συμβολοσειρά που περιέχει ένα SingleDecodeType στη μορφή \"EAN8\" ή \"EAN13\" ή \"CodaBar\"... για μετατροπή. |
| result | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean - **true** εάν το s μετατράπηκε επιτυχώς· διαφορετικά, **false**.
### scanSets(BaseDecodeType[] barcodeTypes) {#scanSets-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public static BaseDecodeType scanSets(BaseDecodeType[] barcodeTypes)
```


Καθορίστε σύνολα σάρωσης με βάση τα barcodeTypes.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Πίνακας με μεμονωμένους και πολλαπλούς τύπους αποκωδικοποίησης |

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


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός MultiDecodeType στην αντίστοιχη παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Μια συμβολοσειρά στη μορφή είτε "AllSupportedTypes" είτε "EAN8,EAN13,CodaBar" για μετατροπή. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Επιστρέφεται ένας πραγματικός MultiDecodeType, όταν η μετατροπή ολοκληρωθεί επιτυχώς· διαφορετικά επιστρέφει αόριστο τύπο: new MultiDecodeType(DecodeType.None)
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην αντίστοιχη παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Συμβολοσειρά που περιέχει ένα SingleDecodeType στη μορφή \"EAN8\" ή \"EAN13\" ή \"CodaBar\"... για μετατροπή. |

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

