---
title: "DataMatrixEncodeMode"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "DataMatrix エンコーダのエンコーディングモードで、デフォルトは Auto です。このサンプルは Extended Mode でコードテキストを使用する方法を示します。"
type: docs
weight: 190
url: /ja/nodejs/global/datamatrixencodemode/
---

## DataMatrixEncodeMode

DataMatrix エンコーダのエンコーディングモードで、デフォルトは Auto です。このサンプルは Extended Mode でコードテキストを使用する方法を示します。 //Auto モード let codetext = "犬Right狗"; let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext); generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8); generator.save("test.bmp", BarcodeImageFormat.PNG); //バイトモード let encodedArr = [ 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 ]; let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, encodedArr); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.BINARY); generator.save("test.bmp", BarcodeImageFormat.PNG); //拡張コードテキストモード //コードテキスト作成 let codetextBuilder=new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,DataMatrixEncodeMode.BYTES,"World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF8,"犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C40,"ABCDE"); //コードテキスト生成 let codetext=codetextBuilder.getExtended(); //生成 let generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.PNG);

## 値

| 名前 | 説明 |
| --- | --- |
| なし | 指定されていないデコードタイプです。 |
| CODABAR | データを `CODABAR ` バーコード仕様でデコードすることを指定します |
| CODE_11 | データを `CODE 11 ` バーコード仕様でデコードすることを指定します |
| CODE_39 | データを `Code 39 ` 基本文字セットのバーコード仕様でデコードすることを指定します: ISO/IEC 16388 |
| CODE_39_FULL_ASCII | データを `Code 39 ` フルASCII文字セットのバーコード仕様でデコードすることを指定します: ISO/IEC 16388 |
| CODE_93 | データを `CODE 93 ` バーコード仕様でデコードすることを指定します |
| CODE_128 | データを `CODE 128 ` バーコード仕様でデコードすることを指定します |
| GS_1_CODE_128 | データを `GS1 CODE 128 ` バーコード仕様でデコードすることを指定します |
| EAN_8 | データを `EAN-8 ` バーコード仕様でデコードすることを指定します |
| EAN_13 | データを `EAN-13 ` バーコード仕様でデコードすることを指定します |
| EAN_14 | データを `EAN14 ` バーコード仕様でデコードすることを指定します |
| SCC_14 | データを `SCC14 ` バーコード仕様でデコードすることを指定します |
| SSCC_18 | データは `SSCC18 ` バーコード仕様でデコードされることを指定します |
| UPCA | データは `UPC-A ` バーコード仕様でデコードされることを指定します |
| UPCE | データは `UPC-E ` バーコード仕様でデコードされることを指定します |
| ISBN | データは `ISBN ` バーコード仕様でデコードされることを指定します |
| STANDARD_2_OF_5 | データは `Standard 2 of 5 ` バーコード仕様でデコードされることを指定します |
| INTERLEAVED_2_OF_5 | データは `INTERLEAVED 2 of 5 ` バーコード仕様でデコードされることを指定します |
| MATRIX_2_OF_5 | データは `Matrix 2 of 5 ` バーコード仕様でデコードされることを指定します |
| ITALIAN_POST_25 | データは `Italian Post 25 ` バーコード仕様でデコードされることを指定します |
| IATA_2_OF_5 | データは `IATA 2 of 5 ` バーコード仕様でデコードされることを指定します。IATA（International Air Transport Association）はこのバーコードを航空貨物の管理に使用します。 |
| ITF_14 | データは `ITF14 ` バーコード仕様でデコードされることを指定します |
| ITF_6 | データは `ITF6 ` バーコード仕様でデコードされることを指定します |
| MSI | データは `MSI Plessey ` バーコード仕様でデコードされることを指定します |
| VIN | データは `VIN ` （車両識別番号） バーコード仕様でデコードされることを指定します |
| DEUTSCHE_POST_IDENTCODE | データは `DeutschePost Ident code ` バーコード仕様でデコードされることを指定します |
| DEUTSCHE_POST_LEITCODE | データは `DeutschePost Leit code ` バーコード仕様でデコードされることを指定します |
| OPC | データは `OPC ` バーコード仕様でデコードされることを指定します |
| PZN | データは `PZN ` バーコード仕様でデコードされることを指定します。このシンボルは Pharma Zentral Nummer とも呼ばれます |
| PHARMACODE | データは `Pharmacode ` バーコードでデコードされることを指定します。このシンボルは Pharmaceutical BINARY Code とも呼ばれます |
| DATA_MATRIX | データは `DataMatrix ` バーコードシンボルでデコードされることを指定します |
| GS_1_DATA_MATRIX | データは `GS1DataMatrix ` バーコードシンボルでデコードされることを指定します |
| QR | データは `QR Code ` バーコード仕様でデコードされることを指定します |
| AZTEC | データは `Aztec ` バーコード仕様でデコードされることを指定します |
| GS_1_AZTEC | データは `GS1 Aztec ` バーコード仕様でデコードされることを指定します |
| PDF_417 | データは `Pdf417 ` バーコードシンボルでデコードされることを指定します |
| MACRO_PDF_417 | データは `MacroPdf417 ` バーコード仕様でデコードされることを指定します |
| MICRO_PDF_417 | データは `MicroPdf417 ` バーコード仕様でデコードされるように指定します |
| GS_1_MICRO_PDF_417 | データは MicroPdf417 バーコード仕様でデコードされるように指定します |
| CODABLOCK_F | データは `CodablockF ` バーコード仕様でデコードされるように指定します |
| MAILMARK | データは Royal Mail Mailmark バーコード仕様でデコードされるように指定します。 |
| AUSTRALIA_POST | データは `Australia Post ` バーコード仕様でデコードされるように指定します |
| POSTNET | データは `Postnet ` バーコード仕様でデコードされるように指定します |
| PLANET | データは `Planet ` バーコード仕様でデコードされるように指定します |
| ONE_CODE | データは USPS `OneCode ` バーコード仕様でデコードされるように指定します |
| RM_4_SCC | データは `RM4SCC ` バーコード仕様でデコードされるように指定します。RM4SCC（Royal Mail 4-state Customer Code）は英国の自動郵便仕分けプロセスで使用されます。 |
| DATABAR_OMNI_DIRECTIONAL | データは `GS1 DATABAR omni-directional ` バーコード仕様でデコードされるように指定します |
| DATABAR_TRUNCATED | データは `GS1 DATABAR truncated ` バーコード仕様でデコードされるように指定します |
| DATABAR_LIMITED | データは `GS1 DATABAR limited ` バーコード仕様でデコードされるように指定します |
| DATABAR_EXPANDED | データは `GS1 DATABAR expanded ` バーコード仕様でデコードされるように指定します |
| DATABAR_STACKED_OMNI_DIRECTIONAL | データは `GS1 DATABAR stacked omni-directional ` バーコード仕様でデコードされることを指定します |
| DATABAR_STACKED | データは `GS1 DATABAR stacked ` バーコード仕様でデコードされることを指定します |
| DATABAR_EXPANDED_STACKED | データは `GS1 DATABAR expanded stacked ` バーコード仕様でデコードされることを指定します |
| PATCH_CODE | データは `Patch code ` バーコード仕様でデコードされることを指定します。バーコードシンボルは自動スキャンに使用されます |
| ISSN | データは `ISSN ` バーコード仕様でデコードされることを指定します |
| ISMN | データは `ISMN ` バーコード仕様でデコードされることを指定します |
| SUPPLEMENT | データは `Supplement(EAN2, EAN5) ` バーコード仕様でデコードされることを指定します |
| AUSTRALIAN_POSTE_PARCEL | データは `Australian Post Domestic eParcel Barcode ` バーコード仕様でデコードされることを指定します |
| SWISS_POST_PARCEL | データは `Swiss Post Parcel Barcode ` バーコード仕様でデコードされることを指定します |
| CODE_16_K | データは `SCode16K ` バーコード仕様でデコードされることを指定します |
| MICRO_QR | データは `MicroQR Code ` バーコード仕様でデコードされることを指定します |
| RECT_MICRO_QR | データは RectMicroQR (rMQR) Code バーコード仕様でデコードされることを指定します |
| COMPACT_PDF_417 | データを `CompactPdf417 ` (Pdf417Truncated) バーコード仕様でデコードすることを指定します |
| GS_1_QR | データを `GS1 QR ` バーコード仕様でデコードすることを指定します |
| MAXI_CODE | データを `MaxiCode ` バーコード仕様でデコードすることを指定します |
| MICR_E_13_B | データを `MICR E-13B ` ブランク仕様でデコードすることを指定します |
| CODE_32 | データを `Code32 ` ブランク仕様でデコードすることを指定します |
| DATA_LOGIC_2_OF_5 | データを `DataLogic 2 of 5 ` ブランク仕様でデコードすることを指定します |
| DOT_CODE | データを `DotCode ` ブランク仕様でデコードすることを指定します |
| GS_1_DOT_CODE | データを `GS1 DotCode ` ブランク仕様でデコードすることを指定します |
| DUTCH_KIX | データを `DotCode ` ブランク仕様でデコードすることを指定します |
| HIBC_CODE_39_LIC | データを `HIBC LIC Code39 ` ブランク仕様でデコードすることを指定します |
| HIBC_CODE_128_LIC | データを `HIBC LIC Code128 ` ブランク仕様でデコードすることを指定します |
| HIBC_AZTEC_LIC | データを `HIBC LIC Aztec ` ブランク仕様でデコードすることを指定します |
| HIBC_DATA_MATRIX_LIC | データを `HIBC LIC DataMatrix ` ブランク仕様でデコードすることを指定します |
| HIBCQRLIC | データは `HIBC LIC QR ` 空白仕様でデコードされることを指定します |
| HIBC_CODE_39_PAS | データは `HIBC PAS Code39 ` 空白仕様でデコードされることを指定します |
| HIBC_CODE_128_PAS | データは `HIBC PAS Code128 ` 空白仕様でデコードされることを指定します |
| HIBC_AZTEC_PAS | データは `HIBC PAS Aztec ` 空白仕様でデコードされることを指定します |
| HIBC_DATA_MATRIX_PAS | データは `HIBC PAS DataMatrix ` 空白仕様でデコードされることを指定します |
| HIBCQRPAS | データは `HIBC PAS QR ` 空白仕様でデコードされることを指定します |
| HAN_XIN | データは Han Xin Code 空白仕様でデコードされることを指定します |
| GS_1_HAN_XIN | データは Han Xin Code 空白仕様でデコードされることを指定します |
| GS_1_COMPOSITE_BAR | データは `GS1 Composite Bar ` バーコード仕様でデコードされることを指定します |
| TYPES_1D | データはすべての1Dバーコードシンボルでチェックされることを指定します |
| POSTAL_TYPES | データはPlanet、Postnet、AustraliaPost、OneCode、RM4SCC、DutchKIXなどのすべての1.5D POSTALバーコードシンボルでチェックされることを指定します |
| MOST_COMMON_TYPES | データは最も一般的に使用されるシンボルでチェックされることを指定します |
| TYPES_2D | データはすべての2Dバーコードシンボルでチェックされることを指定します |
| ALL_SUPPORTED_TYPES | データが利用可能なすべてのシンボロジーでチェックされることを指定します |
| is1D | 指定された BaseDecodeType が 1D バーコードシンボロジーを含むかどうかを判断します |
| isPostal | 指定された BaseDecodeType が郵便バーコードシンボロジーを含むかどうかを判断します |
| is2D | 指定された BaseDecodeType が 2D バーコードシンボロジーを含むかどうかを判断します |
| containsAny |  |
