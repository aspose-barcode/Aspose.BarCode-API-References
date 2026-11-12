---
title: "EncodeTypes"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "指定要编码的条码类型。"
type: docs
weight: 260
url: /zh/nodejs/global/encodetypes/
---

## EncodeTypes

指定要编码的条码类型。

## 值

| 名称 | 描述 |
| --- | --- |
| 无 | 未指定的编码类型。 |
| CODABAR | 指定数据应使用 CODABAR 条码规范进行编码 |
| CODE_11 | 指定数据应使用 CODE 11 条码规范进行编码 |
| CODE_39 | 指定数据应使用 `Code 39 ` 基本字符集条码规范：ISO/IEC 16388 |
| CODE_39_FULL_ASCII | 指定数据应使用 `Code 39 ` 完整 ASCII 字符集条码规范：ISO/IEC 16388 |
| CODE_93 | 指定数据应使用 `CODE 93 ` 条码规范进行编码 |
| CODE_128 | 指定数据应使用 CODE 128 条码规范进行编码 |
| GS_1_CODE_128 | 指定数据应使用 GS1 Code 128 条码规范进行编码。编码文本必须包含用于 AI 的括号。 |
| EAN_8 | 指定数据应使用 EAN-8 条码规范进行编码 |
| EAN_13 | 指定数据应使用 EAN-13 条码规范进行编码 |
| EAN_14 | 指定数据应使用 EAN14 条码规范进行编码 |
| SCC_14 | 指定数据应使用 SCC14 条码规范进行编码 |
| SSCC_18 | 指定数据应使用 SSCC18 条码规范进行编码 |
| UPCA | 指定应使用 UPC-A 条形码规范对数据进行编码 |
| UPCE | 指定应使用 UPC-E 条形码规范对数据进行编码 |
| ISBN | 指定应使用 isBN 条形码规范对数据进行编码 |
| ISSN | 指定应使用 ISSN 条形码规范对数据进行编码 |
| ISMN | 指定应使用 ISMN 条形码规范对数据进行编码 |
| STANDARD_2_OF_5 | 指定应使用 Standard 2 of 5 条形码规范对数据进行编码 |
| INTERLEAVED_2_OF_5 | 指定应使用 INTERLEAVED 2 of 5 条形码规范对数据进行编码 |
| MATRIX_2_OF_5 | 表示 Matrix 2 of 5 条形码 |
| ITALIAN_POST_25 | 表示 Italian Post 25 条形码。 |
| IATA_2_OF_5 | 表示 IATA 2 of 5 条形码。IATA（International Air Transport Assosiation）使用此条形码来管理航空货物。 |
| ITF_14 | 指定应使用 ITF14 条形码规范对数据进行编码 |
| ITF_6 | 表示 ITF-6 条形码。 |
| MSI | 指定应使用 MSI Plessey 条形码规范对数据进行编码 |
| VIN | 表示 VIN（Vehicle Identification Number）条形码。 |
| DEUTSCHE_POST_IDENTCODE | 表示 Deutsch Post 条形码，此 EncodeType 也称为 Identcode、CodeIdentcode、German Postal 2 of 5 Identcode、Deutsch Post AG Identcode、Deutsch Frachtpost Identcode、Deutsch Post AG（DHL） |
| DEUTSCHE_POST_LEITCODE | 表示 Deutsch Post Leitcode 条形码，也称为 German Postal 2 of 5 Leitcode、CodeLeitcode、Leitcode、Deutsch Post AG（DHL）。 |
| OPC | 表示 OPC（Optical Product Code）条形码，也称为 , VCA Barcode VCA OPC、Vision Council of America OPC Barcode。 |
| PZN | 表示 PZN 条形码。此 EncodeType 也称为 Pharmacy central number、Pharmazentralnummer |
| CODE_16_K | 表示 Code 16K 条形码。 |
| PHARMACODE | 表示 Pharmacode 条形码。 |
| DATA_MATRIX | 2D 条形码符号 DataMatrix |
| QR | 指定应使用 QR Code 条形码规范对数据进行编码 |
| AZTEC | 指定应使用 Aztec 条形码规范对数据进行编码 |
| GS_1_AZTEC | 指定应使用 `GS1 Aztec ` 条形码规范对数据进行编码。代码文本必须包含 AI 的括号。 |
| PDF_417 | 指定应使用 Pdf417 条形码规范对数据进行编码 |
| MACRO_PDF_417 | 指定应使用 MacroPdf417 条码规范对数据进行编码 |
| GS_1_DATA_MATRIX | 使用 GS1 字符串格式的 2D 条码符号 DataMatrix |
| MICRO_PDF_417 | 指定应使用 MicroPdf417 条码规范对数据进行编码 |
| GS_1_MICRO_PDF_417 | 指定应使用 GS1MicroPdf417 条码规范对数据进行编码 |
| GS_1_QR | 使用 GS1 字符串格式的 2D 条码符号 QR |
| MAXI_CODE | 指定应使用 MaxiCode 条码规范对数据进行编码 |
| DOT_CODE | 指定应使用 DotCode 条码规范对数据进行编码 |
| AUSTRALIA_POST | 表示 Australia Post 客户条码 |
| POSTNET | 指定应使用 Postnet 条码规范对数据进行编码 |
| PLANET | 指定应使用 Planet 条码规范对数据进行编码 |
| ONE_CODE | 指定应使用 USPS OneCode 条码规范对数据进行编码 |
| RM_4_SCC | 表示 RM4SCC 条码。RM4SCC（Royal Mail 4-state Customer Code）用于英国的自动邮件分拣过程。 |
| MAILMARK | 表示 Royal Mail Mailmark 条码。 |
| DATABAR_OMNI_DIRECTIONAL | 指定应使用 GS1 Databar 全向条码规范对数据进行编码。 |
| DATABAR_TRUNCATED | 指定应使用 GS1 Databar 截断条码规范对数据进行编码。 |
| DATABAR_LIMITED | 表示 GS1 DATABAR 限制条码。 |
| DATABAR_EXPANDED | 表示 GS1 Databar 扩展条码。 |
| DATABAR_EXPANDED_STACKED | 表示 GS1 Databar 扩展堆叠条码。 |
| DATABAR_STACKED | 表示 GS1 Databar 堆叠条码。 |
| DATABAR_STACKED_OMNI_DIRECTIONAL | 表示 GS1 Databar 堆叠全向条码。 |
| SINGAPORE_POST | 指定应使用 Singapore Post Barcode 条码规范对数据进行编码。 |
| AUSTRALIAN_POSTE_PARCEL | 指定应使用 Australian Post Domestic eParcel Barcode 条码规范对数据进行编码。 |
| SWISS_POST_PARCEL | 指定应使用 Swiss Post Parcel Barcode 条码规范对数据进行编码。支持的类型：Domestic Mail、International Mail、Additional Services（new）。 |
| PATCH_CODE | 表示 Patch code 条码 |
| CODE_32 | 指定应使用 Code32 条码规范对数据进行编码 |
| DATA_LOGIC_2_OF_5 | 指定应使用 DataLogic 2 of 5 条码规范对数据进行编码 |
| DUTCH_KIX | 指定应使用 Dutch KIX 条码规范对数据进行编码 |
| UPCA_GS_1_CODE_128_COUPON | 指定应使用带有 GS1-128 扩展代码的 UPC 优惠券条码规范对数据进行编码。 |
| UPCA_GS_1_DATABAR_COUPON | 指定应使用带有 GS1 DataBar 附加的 UPC 优惠券条码规范对数据进行编码。 |
| CODABLOCK_F | 指定应使用 Codablock-F 条码规范对数据进行编码。 |
| GS_1_CODABLOCK_F | 指定应使用 GS1 Codablock-F 条码规范对数据进行编码。代码文本必须包含 AI 的括号。 |
| GS_1_COMPOSITE_BAR | 指定应使用 GS1 Composite Bar 条码规范对数据进行编码。代码文本必须包含 AI 的括号。1D 代码文本和 2D 代码文本必须使用符号 '/' 分隔。 |
| HIBC_CODE_39_LIC | 指定应使用 `HIBC LIC Code39Standart ` 条码规范对数据进行编码。 |
| HIBC_CODE_128_LIC | 指定应使用 `HIBC LIC Code128 ` 条码规范对数据进行编码。 |
| HIBC_AZTEC_LIC | 指定应使用 `HIBC LIC Aztec ` 条码规范对数据进行编码。 |
| HIBC_DATA_MATRIX_LIC | 指定应使用 `HIBC LIC DataMatrix ` 条码规范对数据进行编码。 |
| HIBCQRLIC | 指定应使用 `HIBC LIC QR ` 条码规范对数据进行编码。 |
| HIBC_CODE_39_PAS | 指定应使用 `HIBC PAS Code39Standart ` 条码规范对数据进行编码。 |
| HIBC_CODE_128_PAS | 指定应使用 `HIBC PAS Code128 ` 条码规范对数据进行编码。 |
| HIBC_AZTEC_PAS | 指定应使用 `HIBC PAS Aztec ` 条码规范对数据进行编码。 |
| HIBC_DATA_MATRIX_PAS | 指定应使用 `HIBC PAS DataMatrix ` 条码规范对数据进行编码。 |
| HIBCQRPAS | 指定应使用 `HIBC PAS QR ` 条码规范对数据进行编码。 |
| GS_1_DOT_CODE | 指定应使用 `GS1 DotCode ` 条码规范对数据进行编码。代码文本必须包含 AI 的括号。 |
| HAN_XIN | 指定应使用 Han Xin 条码规范对数据进行编码 |
| GS_1_HAN_XIN | 使用 GS1 字符串格式的 2D 条码符号 QR |
| MICRO_QR | 指定应使用 MicroQR Code 条码规范对数据进行编码 |
| RECT_MICRO_QR | 指定应使用 RectMicroQR (rMQR) Code 条码规范对数据进行编码 |
| 解析 |  |
