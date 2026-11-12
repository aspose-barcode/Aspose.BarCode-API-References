---
title: "DataMatrixEncodeMode"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "DataMatrix 인코더의 인코딩 모드이며 기본값은 Auto입니다. 이 예제는 확장 모드에서 코드텍스트를 사용하는 방법을 보여줍니다."
type: docs
weight: 190
url: /ko/nodejs/global/datamatrixencodemode/
---

## DataMatrixEncodeMode

DataMatrix 인코더의 인코딩 모드이며 기본값은 Auto입니다. 이 예제는 확장 모드에서 코드텍스트를 사용하는 방법을 보여줍니다. //Auto mode let codetext = "犬Right狗"; let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext); generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8); generator.save("test.bmp", BarcodeImageFormat.PNG); //Bytes mode let encodedArr = [ 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 ]; let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, encodedArr); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.BINARY); generator.save("test.bmp", BarcodeImageFormat.PNG); //Extended codetext mode //create codetext let codetextBuilder=new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,DataMatrixEncodeMode.BYTES,"World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF8,"犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C40,"ABCDE"); //generate codetext let codetext=codetextBuilder.getExtended(); //generate let generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.PNG);

## 값

| 이름 | 설명 |
| --- | --- |
| NONE | 지정되지 않은 디코드 유형입니다. |
| CODABAR | 데이터를 `CODABAR ` 바코드 사양으로 디코딩해야 함을 지정합니다 |
| CODE_11 | 데이터를 `CODE 11 ` 바코드 사양으로 디코딩해야 함을 지정합니다 |
| CODE_39 | 데이터를 `Code 39 ` 기본 문자 집합 바코드 사양으로 디코딩해야 함을 지정합니다: ISO/IEC 16388 |
| CODE_39_FULL_ASCII | 데이터를 `Code 39 ` 전체 ASCII 문자 집합 바코드 사양으로 디코딩해야 함을 지정합니다: ISO/IEC 16388 |
| CODE_93 | 데이터를 `CODE 93 ` 바코드 사양으로 디코딩해야 함을 지정합니다 |
| CODE_128 | 데이터를 `CODE 128 ` 바코드 사양으로 디코딩해야 함을 지정합니다 |
| GS_1_CODE_128 | 데이터를 `GS1 CODE 128 ` 바코드 사양으로 디코딩해야 함을 지정합니다 |
| EAN_8 | 데이터를 `EAN-8 ` 바코드 사양으로 디코딩해야 함을 지정합니다 |
| EAN_13 | 데이터를 `EAN-13 ` 바코드 사양으로 디코딩해야 함을 지정합니다 |
| EAN_14 | 데이터를 `EAN14 ` 바코드 사양으로 디코딩해야 함을 지정합니다 |
| SCC_14 | 데이터를 `SCC14 ` 바코드 사양으로 디코딩해야 함을 지정합니다 |
| SSCC_18 | 데이터를 `SSCC18 ` 바코드 사양으로 디코딩하도록 지정합니다 |
| UPCA | 데이터를 `UPC-A ` 바코드 사양으로 디코딩하도록 지정합니다 |
| UPCE | 데이터를 `UPC-E ` 바코드 사양으로 디코딩하도록 지정합니다 |
| ISBN | 데이터를 `ISBN ` 바코드 사양으로 디코딩하도록 지정합니다 |
| STANDARD_2_OF_5 | 데이터를 `Standard 2 of 5 ` 바코드 사양으로 디코딩하도록 지정합니다 |
| INTERLEAVED_2_OF_5 | 데이터를 `INTERLEAVED 2 of 5 ` 바코드 사양으로 디코딩하도록 지정합니다 |
| MATRIX_2_OF_5 | 데이터를 `Matrix 2 of 5 ` 바코드 사양으로 디코딩하도록 지정합니다 |
| ITALIAN_POST_25 | 데이터를 `Italian Post 25 ` 바코드 사양으로 디코딩하도록 지정합니다 |
| IATA_2_OF_5 | 데이터를 `IATA 2 of 5 ` 바코드 사양으로 디코딩하도록 지정합니다. IATA (International Air Transport Association)는 항공 화물 관리에 이 바코드를 사용합니다. |
| ITF_14 | 데이터를 `ITF14 ` 바코드 사양으로 디코딩하도록 지정합니다 |
| ITF_6 | 데이터를 `ITF6 ` 바코드 사양으로 디코딩하도록 지정합니다 |
| MSI | 데이터를 `MSI Plessey ` 바코드 사양으로 디코딩하도록 지정합니다 |
| VIN | 데이터를 `VIN ` (Vehicle Identification Number) 바코드 사양으로 디코딩하도록 지정합니다 |
| DEUTSCHE_POST_IDENTCODE | 데이터를 `DeutschePost Ident code ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| DEUTSCHE_POST_LEITCODE | 데이터를 `DeutschePost Leit code ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| OPC | 데이터를 `OPC ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| PZN | 데이터를 `PZN ` 바코드 사양으로 디코딩해야 함을 지정합니다. 이 기호는 Pharma Zentral Nummer 라고도 알려져 있습니다 |
| PHARMACODE | 데이터를 `Pharmacode ` 바코드로 디코딩해야 함을 지정합니다. 이 기호는 Pharmaceutical BINARY Code 라고도 알려져 있습니다 |
| DATA_MATRIX | 데이터를 `DataMatrix ` 바코드 기호로 디코딩해야 함을 지정합니다. |
| GS_1_DATA_MATRIX | 데이터를 `GS1DataMatrix ` 바코드 기호로 디코딩해야 함을 지정합니다. |
| QR | 데이터를 `QR Code ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| AZTEC | 데이터를 `Aztec ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| GS_1_AZTEC | 데이터를 `GS1 Aztec ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| PDF_417 | 데이터를 `Pdf417 ` 바코드 기호로 디코딩해야 함을 지정합니다. |
| MACRO_PDF_417 | 데이터를 `MacroPdf417 ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| MICRO_PDF_417 | 데이터를 `MicroPdf417 ` 바코드 사양으로 디코딩하도록 지정합니다 |
| GS_1_MICRO_PDF_417 | 데이터를 MicroPdf417 바코드 사양으로 디코딩하도록 지정합니다 |
| CODABLOCK_F | 데이터를 `CodablockF ` 바코드 사양으로 디코딩하도록 지정합니다 |
| MAILMARK | 데이터를 Royal Mail Mailmark 바코드 사양으로 디코딩하도록 지정합니다. |
| AUSTRALIA_POST | 데이터를 `Australia Post ` 바코드 사양으로 디코딩하도록 지정합니다 |
| POSTNET | 데이터를 `Postnet ` 바코드 사양으로 디코딩하도록 지정합니다 |
| PLANET | 데이터를 `Planet ` 바코드 사양으로 디코딩하도록 지정합니다 |
| ONE_CODE | 데이터를 USPS `OneCode ` 바코드 사양으로 디코딩하도록 지정합니다 |
| RM_4_SCC | 데이터를 `RM4SCC ` 바코드 사양으로 디코딩하도록 지정합니다. RM4SCC (Royal Mail 4-state Customer Code)는 영국의 자동 우편 분류 프로세스에 사용됩니다. |
| DATABAR_OMNI_DIRECTIONAL | 데이터를 `GS1 DATABAR omni-directional ` 바코드 사양으로 디코딩하도록 지정합니다 |
| DATABAR_TRUNCATED | 데이터를 `GS1 DATABAR truncated ` 바코드 사양으로 디코딩하도록 지정합니다 |
| DATABAR_LIMITED | 데이터를 `GS1 DATABAR limited ` 바코드 사양으로 디코딩하도록 지정합니다 |
| DATABAR_EXPANDED | 데이터를 `GS1 DATABAR expanded ` 바코드 사양으로 디코딩하도록 지정합니다 |
| DATABAR_STACKED_OMNI_DIRECTIONAL | 데이터를 `GS1 DATABAR stacked omni-directional ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| DATABAR_STACKED | 데이터를 `GS1 DATABAR stacked ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| DATABAR_EXPANDED_STACKED | 데이터를 `GS1 DATABAR expanded stacked ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| PATCH_CODE | 데이터를 `Patch code ` 바코드 사양으로 디코딩해야 함을 지정합니다. 바코드 기호는 자동 스캔에 사용됩니다. |
| ISSN | 데이터를 `ISSN ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| ISMN | 데이터를 `ISMN ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| SUPPLEMENT | 데이터를 `Supplement(EAN2, EAN5) ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| AUSTRALIAN_POSTE_PARCEL | 데이터를 `Australian Post Domestic eParcel Barcode ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| SWISS_POST_PARCEL | 데이터를 `Swiss Post Parcel Barcode ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| CODE_16_K | 데이터를 `SCode16K ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| MICRO_QR | 데이터를 `MicroQR Code ` 바코드 사양으로 디코딩해야 함을 지정합니다. |
| RECT_MICRO_QR | 데이터를 RectMicroQR (rMQR) Code 바코드 사양으로 디코딩해야 함을 지정합니다. |
| COMPACT_PDF_417 | 데이터를 `CompactPdf417 ` (Pdf417Truncated) 바코드 사양으로 디코딩하도록 지정합니다. |
| GS_1_QR | 데이터를 `GS1 QR ` 바코드 사양으로 디코딩하도록 지정합니다. |
| MAXI_CODE | 데이터를 `MaxiCode ` 바코드 사양으로 디코딩하도록 지정합니다. |
| MICR_E_13_B | 데이터를 `MICR E-13B ` 빈 사양으로 디코딩하도록 지정합니다. |
| CODE_32 | 데이터를 `Code32 ` 빈 사양으로 디코딩하도록 지정합니다. |
| DATA_LOGIC_2_OF_5 | 데이터를 `DataLogic 2 of 5 ` 빈 사양으로 디코딩하도록 지정합니다. |
| DOT_CODE | 데이터를 `DotCode ` 빈 사양으로 디코딩하도록 지정합니다. |
| GS_1_DOT_CODE | 데이터를 `GS1 DotCode ` 빈 사양으로 디코딩하도록 지정합니다. |
| DUTCH_KIX | 데이터를 `DotCode ` 빈 사양으로 디코딩하도록 지정합니다. |
| HIBC_CODE_39_LIC | 데이터를 `HIBC LIC Code39 ` 빈 사양으로 디코딩하도록 지정합니다. |
| HIBC_CODE_128_LIC | 데이터를 `HIBC LIC Code128 ` 빈 사양으로 디코딩하도록 지정합니다. |
| HIBC_AZTEC_LIC | 데이터를 `HIBC LIC Aztec ` 빈 사양으로 디코딩하도록 지정합니다. |
| HIBC_DATA_MATRIX_LIC | 데이터를 `HIBC LIC DataMatrix ` 빈 사양으로 디코딩하도록 지정합니다. |
| HIBCQRLIC | 데이터를 `HIBC LIC QR ` 빈 사양으로 디코딩하도록 지정합니다 |
| HIBC_CODE_39_PAS | 데이터를 `HIBC PAS Code39 ` 빈 사양으로 디코딩하도록 지정합니다 |
| HIBC_CODE_128_PAS | 데이터를 `HIBC PAS Code128 ` 빈 사양으로 디코딩하도록 지정합니다 |
| HIBC_AZTEC_PAS | 데이터를 `HIBC PAS Aztec ` 빈 사양으로 디코딩하도록 지정합니다 |
| HIBC_DATA_MATRIX_PAS | 데이터를 `HIBC PAS DataMatrix ` 빈 사양으로 디코딩하도록 지정합니다 |
| HIBCQRPAS | 데이터를 `HIBC PAS QR ` 빈 사양으로 디코딩하도록 지정합니다 |
| HAN_XIN | 데이터를 Han Xin Code 빈 사양으로 디코딩하도록 지정합니다 |
| GS_1_HAN_XIN | 데이터를 Han Xin Code 빈 사양으로 디코딩하도록 지정합니다 |
| GS_1_COMPOSITE_BAR | 데이터를 `GS1 Composite Bar ` 바코드 사양으로 디코딩하도록 지정합니다 |
| TYPES_1D | 데이터가 모든 1D 바코드 심볼을 사용하여 검사되도록 지정합니다 |
| POSTAL_TYPES | 데이터가 Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX와 같은 모든 1.5D POSTAL 바코드 심볼을 사용하여 검사되도록 지정합니다 |
| MOST_COMMON_TYPES | 데이터가 가장 일반적으로 사용되는 심볼을 사용하여 검사되도록 지정합니다 |
| TYPES_2D | 데이터가 모든 2D 바코드 심볼을 사용하여 검사되도록 지정합니다 |
| ALL_SUPPORTED_TYPES | 데이터가 모든 사용 가능한 심볼을 사용하여 검사된다는 것을 지정합니다 |
| is1D | 지정된 BaseDecodeType에 1D 바코드 심볼이 포함되어 있는지 확인합니다 |
| isPostal | 지정된 BaseDecodeType에 우편 바코드 심볼이 포함되어 있는지 확인합니다 |
| is2D | 지정된 BaseDecodeType에 2D 바코드 심볼이 포함되어 있는지 확인합니다 |
| containsAny |  |
