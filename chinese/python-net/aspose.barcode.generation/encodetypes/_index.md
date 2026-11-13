---
title: "EncodeTypes"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.generation/encodetypes/
---

## EncodeTypes class

指定要编码的条码类型。

EncodeTypes 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| all_encode_types | 指定将使用所有可用的符号系统检查数据。 |
| NONE | 未指定的编码类型。 |
| CODABAR | 指定应使用 CODABAR 条码规范对数据进行编码 |
| CODE11 | 指定应使用 CODE 11 条码规范对数据进行编码 |
| CODE39 | 指定应使用 Code 39 基本字符集条码规范对数据进行编码：ISO/IEC 16388 |
| CODE_39_FULL_ASCII | 指定应使用 Code 39 完整 ASCII 字符集条码规范对数据进行编码：ISO/IEC 16388 |
| CODE93 | 指定应使用 CODE 93 条码规范对数据进行编码 |
| CODE128 | 指定应使用 CODE 128 条码规范对数据进行编码 |
| GS1_CODE_128 | 指定应使用 GS1 Code 128 条码规范对数据进行编码。代码文本必须包含用于 AI 的括号。 |
| EAN8 | 指定应使用 EAN-8 条码规范对数据进行编码 |
| EAN13 | 指定应使用 EAN-13 条码规范对数据进行编码 |
| EAN14 | 指定应使用 EAN14 条码规范对数据进行编码 |
| SCC14 | 指定应使用 SCC14 条码规范对数据进行编码 |
| SSCC18 | 指定应使用 SSCC18 条码规范对数据进行编码 |
| UPCA | 指定应使用 UPC-A 条码规范对数据进行编码 |
| UPCE | 指定应使用 UPC-E 条码规范对数据进行编码 |
| ISBN | 指定应使用 ISBN 条码规范对数据进行编码 |
| ISSN | 指定应使用 ISSN 条码规范对数据进行编码 |
| ISMN | 指定应使用 ISMN 条码规范对数据进行编码 |
| STANDARD_2OF_5 | 指定应使用 Standard 2 of 5 条码规范对数据进行编码 |
| INTERLEAVED_2OF_5 | 指定应使用 INTERLEAVED 2 of 5 条码规范对数据进行编码 |
| MATRIX_2OF_5 | 表示 Matrix 2 of 5 条码 |
| ITALIAN_POST25 | 表示意大利邮政 25 条码。 |
| IATA2OF_5 | 表示 IATA 2 of 5 条码。IATA（International Air Transport Association，国际航空运输协会）使用此条码来管理航空货物。 |
| ITF14 | 指定应使用 ITF14 条形码规范对数据进行编码 |
| ITF6 | 表示 ITF-6 条形码。 |
| MSI | 指定应使用 MSI Plessey 条形码规范对数据进行编码 |
| VIN | 表示 VIN（车辆识别号码）条形码。 |
| DEUTSCHE_POST_IDENTCODE | 表示 Deutsch Post 条形码，此符号也称为 Identcode、CodeIdentcode、German Postal 2 of 5 Identcode，<br/>            Deutsch Post AG Identcode，Deutsch Frachtpost Identcode，Deutsch Post AG (DHL)。 |
| DEUTSCHE_POST_LEITCODE | 表示 Deutsch Post Leitcode 条形码，也称为 German Postal 2 of 5 Leitcode、CodeLeitcode、Leitcode、Deutsch Post AG (DHL)。 |
| OPC | 表示 OPC（光学产品代码）条形码，也称为 VCA Barcode VCA OPC，Vision Council of America OPC Barcode。 |
| PZN | 表示 PZN 条形码。此符号也称为 Pharmacy central number、Pharmazentralnummer。支持 PZN7 和 PZN8。<br/>            PZN7 由 6 位或更少数字生成，例如 "123456"。PZN8 由 7 位或更多数字生成，例如 "1234567"。<br/>            提供的最后校验位将被忽略，由条形码引擎生成。 |
| CODE_16K | 表示 Code 16K 条形码。 |
| PHARMACODE | 表示 Pharmacode 条形码。 |
| DATA_MATRIX | 二维条形码符号 DataMatrix |
| QR | 指定应使用 QR Code 条形码规范对数据进行编码 |
| AZTEC | 指定应使用 Aztec 条形码规范对数据进行编码 |
| GS1_AZTEC | 指定应使用 GS1 Aztec 条形码规范对数据进行编码。代码文本必须包含 AI 的括号。 |
| PDF417 | 指定应使用 Pdf417 条形码规范对数据进行编码 |
| MACRO_PDF417 | 指定应使用 MacroPdf417 条形码规范对数据进行编码 |
| GS1_DATA_MATRIX | 具有 GS1 字符串格式的二维条形码符号 DataMatrix |
| MICRO_PDF417 | 指定应使用 MicroPdf417 条形码规范对数据进行编码 |
| GS1_MICRO_PDF_417 | 指定应使用 GS1MicroPdf417 条形码规范对数据进行编码 |
| GS1QR | 具有 GS1 字符串格式的二维条形码符号 QR |
| MAXI_CODE | 指定应使用 MaxiCode 条形码规范对数据进行编码 |
| DOT_CODE | 指定应使用 DotCode 条形码规范对数据进行编码 |
| HAN_XIN | 指定应使用 Han Xin 条形码规范对数据进行编码 |
| GS1_HAN_XIN | 具有 GS1 字符串格式的二维条形码符号 HanXin |
| MICRO_QR | 指定应使用 MicroQR Code 条形码规范对数据进行编码 |
| RECT_MICRO_QR | 指定应使用 RectMicroQR (rMQR) Code 条码规范对数据进行编码 |
| AUSTRALIA_POST | 表示 Australia Post Customer BarCode |
| JAPAN_POST | 表示 Japan Post BarCode |
| POSTNET | 指定应使用 Postnet 条码规范对数据进行编码 |
| PLANET | 指定应使用 Planet 条码规范对数据进行编码 |
| ONE_CODE | 指定应使用 USPS OneCode 条码规范对数据进行编码 |
| RM4SCC | 表示 RM4SCC 条码。RM4SCC（Royal Mail 4-state Customer Code）用于英国的自动邮件分拣过程。 |
| MAILMARK | 表示 Royal Mail Mailmark 条码。 |
| DATABAR_OMNI_DIRECTIONAL | 指定应使用 GS1 Databar omni-directional 条码规范对数据进行编码。 |
| DATABAR_TRUNCATED | 指定应使用 GS1 Databar truncated 条码规范对数据进行编码。 |
| DATABAR_LIMITED | 表示 GS1 Databar limited 条码。 |
| DATABAR_EXPANDED | 表示 GS1 Databar expanded 条码。 |
| DATABAR_EXPANDED_STACKED | 表示 GS1 Databar expanded stacked 条码。 |
| DATABAR_STACKED | 表示 GS1 Databar stacked 条码。 |
| DATABAR_STACKED_OMNI_DIRECTIONAL | 表示 GS1 Databar stacked omni-directional 条码。 |
| SINGAPORE_POST | 指定应使用 Singapore Post Barcode 条码规范对数据进行编码 |
| AUSTRALIAN_POSTE_PARCEL | 指定应使用 Australian Post Domestic eParcel Barcode 条码规范对数据进行编码 |
| SWISS_POST_PARCEL | 指定应使用 Swiss Post Parcel Barcode 条码规范对数据进行编码。支持的类型：Domestic Mail、International Mail、Additional Services（new） |
| PATCH_CODE | 表示 Patch code 条码 |
| CODE32 | 指定应使用 Code32 条码规范对数据进行编码 |
| DATA_LOGIC_2OF_5 | 指定应使用 DataLogic 2 of 5 条码规范对数据进行编码 |
| DUTCH_KIX | 指定应使用 Dutch KIX 条码规范对数据进行编码 |
| UPCA_GS_1_CODE_128_COUPON | 指定应使用带有 GS1-128 扩展代码的 UPC 优惠券条码规范对数据进行编码。<br/>            输入字符串示例：<br/>            BarcodeGenerator.Codetext = "514141100906(8102)03",<br/>            其中 UPCA 部分为 "514141100906"，GS1Code128 部分为 (8102)03。 |
| UPCA_GS_1_DATABAR_COUPON | 指定应使用带有 GS1 DataBar 附加条码规范的 UPC 优惠券对数据进行编码。<br/>            输入字符串示例：<br/>            BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000",<br/>            其中 UPCA 部分为 "514141100906"，Databar 部分为 "(8110)106141416543213500110000310123196000"。<br/>            若要更改标题，请使用 Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| CODABLOCK_F | 指定应使用 Codablock-F 条码规范对数据进行编码。 |
| GS1_CODABLOCK_F | 指定应使用 GS1 Codablock-F 条码规范对数据进行编码。编码文本必须包含 AI 的括号。 |
| GS1_COMPOSITE_BAR | 指定应使用 GS1 Composite Bar 条码规范对数据进行编码。编码文本必须包含 AI 的括号。1D 编码文本和 2D 编码文本必须使用符号 '/' 分隔。 |
| HIBC_CODE_39LIC | 指定应使用 HIBC LIC Code39 条码规范对数据进行编码。 |
| HIBC_CODE_128LIC | 指定应使用 HIBC LIC Code128 条码规范对数据进行编码。 |
| HIBC_AZTEC_LIC | 指定应使用 HIBC LIC Aztec 条码规范对数据进行编码。 |
| HIBC_DATA_MATRIX_LIC | 指定应使用 HIBC LIC DataMatrix 条码规范对数据进行编码。 |
| HIBCQRLIC | 指定应使用 HIBC LIC QR 条码规范对数据进行编码。 |
| HIBC_CODE_39PAS | 指定应使用 HIBC PAS Code39 条码规范对数据进行编码。 |
| HIBC_CODE_128PAS | 指定应使用 HIBC PAS Code128 条码规范对数据进行编码。 |
| HIBC_AZTEC_PAS | 指定应使用 HIBC PAS Aztec 条码规范对数据进行编码。 |
| HIBC_DATA_MATRIX_PAS | 指定应使用 HIBC PAS DataMatrix 条码规范对数据进行编码。 |
| HIBCQRPAS | 指定应使用 HIBC PAS QR 条码规范对数据进行编码。 |
| GS1_DOT_CODE | 指定应使用 GS1 DotCode 条码规范对数据进行编码。编码文本必须包含 AI 的括号。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| get_names() | 检索编码类型名称的数组。 |
| parse(parsing_type, result) | 将 BaseEncodeType 的字符串表示转换为其实例。<br/>            返回值指示转换是成功还是失败。 |
| try_parse(parsing_type, result) | 将 BaseEncodeType 的字符串表示转换为其实例。<br/>            返回值指示转换是成功还是失败。 |

### 另见

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

