---
title: "Aspose::BarCode::Generation::EncodeTypes 类"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::EncodeTypes 类。指定在 C++ 中要编码的条码类型。"
type: docs
weight: 2300
url: /zh/cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


指定要编码的条形码类型。

```cpp
class EncodeTypes
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | 指定将使用所有可用的符号系统检查数据。 |
| static [GetNames](./getnames/)() | 检索编码类型名称的数组。 |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | 将 [BaseEncodeType](../baseencodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | 将 [BaseEncodeType](../baseencodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | 指定数据应使用 **Australian Post Domestic eParcel Barcode** 条码规范进行编码 |
| static [AustraliaPost](./australiapost/) | 表示 Australia Post 客户的 [BarCode](../../aspose.barcode/) |
| static [Aztec](./aztec/) | 指定数据应使用 **Aztec** 条码规范进行编码 |
| static [Codabar](./codabar/) | 指定应使用 **CODABAR** 条形码规范对数据进行编码 |
| static [CodablockF](./codablockf/) | 指定应使用 **Codablock-F** 条形码规范对数据进行编码。 |
| static [Code11](./code11/) | 指定应使用 **CODE 11** 条形码规范对数据进行编码 |
| static [Code128](./code128/) | 指定应使用 **CODE 128** 条形码规范对数据进行编码 |
| static [Code16K](./code16k/) | 表示 Code 16K 条形码。 |
| static [Code32](./code32/) | 指定应使用 **Code32** 条形码规范对数据进行编码 |
| static [Code39](./code39/) | 指定应使用 **Code 39** 基本字符集条形码规范：ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | 指定应使用 **Code 39** 完整 ASCII 字符集条形码规范：ISO/IEC 16388 |
| static [Code93](./code93/) | 指定应使用 **CODE 93** 条形码规范对数据进行编码 |
| static [DatabarExpanded](./databarexpanded/) | 表示 GS1 Databar 扩展条形码。 |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | 表示 GS1 Databar 扩展堆叠条形码。 |
| static [DatabarLimited](./databarlimited/) | 表示 GS1 Databar 限制条形码。 |
| static [DatabarOmniDirectional](./databaromnidirectional/) | 指定应使用 **GS1 Databar omni-directional** 条形码规范对数据进行编码。 |
| static [DatabarStacked](./databarstacked/) | 表示 GS1 Databar 堆叠条形码。 |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | 表示 GS1 Databar 堆叠全向条形码。 |
| static [DatabarTruncated](./databartruncated/) | 指定应使用 **GS1 Databar truncated** 条形码规范对数据进行编码。 |
| static [DataLogic2of5](./datalogic2of5/) | 指定应使用 **DataLogic 2 of 5** 条形码规范对数据进行编码 |
| static [DataMatrix](./datamatrix/) | 2D 条形码符号 DataMatrix |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | 表示 Deutsch Post 条形码，此符号也称为 Identcode、CodeIdentcode、German Postal 2 of 5 Identcode、Deutsch Post AG Identcode、Deutsch Frachtpost Identcode、Deutsch Post AG (DHL) |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | 表示 Deutsch Post Leitcode 条形码，也称为 German Postal 2 of 5 Leitcode、CodeLeitcode、Leitcode、Deutsch Post AG (DHL)。 |
| static [DotCode](./dotcode/) | 指定应使用 **DotCode** 条形码规范对数据进行编码 |
| static [DutchKIX](./dutchkix/) | 指定应使用 **Dutch KIX** 条形码规范对数据进行编码 |
| static [EAN13](./ean13/) | 指定应使用 **EAN-13** 条形码规范对数据进行编码 |
| static [EAN14](./ean14/) | 指定应使用 **EAN14** 条形码规范对数据进行编码 |
| static [EAN8](./ean8/) | 指定应使用 **EAN-8** 条形码规范对数据进行编码 |
| static [GS1Aztec](./gs1aztec/) | 指定应使用 **GS1 Aztec** 条形码规范对数据进行编码。编码文本必须包含 AI 的括号。 |
| static [GS1CodablockF](./gs1codablockf/) | 指定应使用 **GS1 Codablock-F** 条形码规范对数据进行编码。编码文本必须包含 AI 的括号。 |
| static [GS1Code128](./gs1code128/) | 指定应使用 **GS1 Code 128** 条形码规范对数据进行编码。编码文本必须包含 AI 的括号。 |
| static [GS1CompositeBar](./gs1compositebar/) | 指定应使用 **GS1 Composite Bar** 条形码规范对数据进行编码。编码文本必须包含 AI 的括号。1D 编码文本和 2D 编码文本必须用符号 '/' 分隔。 |
| static [GS1DataMatrix](./gs1datamatrix/) | 带有 GS1 字符串格式的 2D 条形码符号 DataMatrix |
| static [GS1DotCode](./gs1dotcode/) | 指定应使用 **GS1 DotCode** 条形码规范对数据进行编码。编码文本必须包含 AI 的括号。 |
| static [GS1HanXin](./gs1hanxin/) | 带有 GS1 字符串格式的 2D 条形码符号 HanXin |
| static [GS1MicroPdf417](./gs1micropdf417/) | 指定应使用 **GS1MicroPdf417** 条形码规范对数据进行编码 |
| static [GS1QR](./gs1qr/) | 带有 GS1 字符串格式的 2D 条形码符号 QR |
| static [HanXin](./hanxin/) | 指定应使用 **Han Xin** 条形码规范对数据进行编码 |
| static [HIBCAztecLIC](./hibcazteclic/) | 指定应使用 **HIBC LIC Aztec** 条形码规范对数据进行编码。 |
| static [HIBCAztecPAS](./hibcaztecpas/) | 指定应使用 **HIBC PAS Aztec** 条形码规范对数据进行编码。 |
| static [HIBCCode128LIC](./hibccode128lic/) | 指定应使用 **HIBC LIC Code128** 条形码规范对数据进行编码。 |
| static [HIBCCode128PAS](./hibccode128pas/) | 指定应使用 **HIBC PAS Code128** 条形码规范对数据进行编码。 |
| static [HIBCCode39LIC](./hibccode39lic/) | 指定应使用 **HIBC LIC Code39** 条形码规范对数据进行编码。 |
| static [HIBCCode39PAS](./hibccode39pas/) | 指定应使用 **HIBC PAS Code39** 条形码规范对数据进行编码。 |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | 指定应使用 **HIBC LIC DataMatrix** 条形码规范对数据进行编码。 |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | 指定应使用 **HIBC PAS DataMatrix** 条形码规范对数据进行编码。 |
| static [HIBCQRLIC](./hibcqrlic/) | 指定应使用 **HIBC LIC QR** 条形码规范对数据进行编码。 |
| static [HIBCQRPAS](./hibcqrpas/) | 指定应使用 **HIBC PAS QR** 条形码规范对数据进行编码。 |
| static [IATA2of5](./iata2of5/) | 表示 IATA 2 of 5 条形码。IATA（国际航空运输协会）使用此条形码来管理航空货物。 |
| static [Interleaved2of5](./interleaved2of5/) | 指定应使用 **INTERLEAVED 2 of 5** 条形码规范对数据进行编码 |
| static [ISBN](./isbn/) | 指定应使用 **ISBN** 条形码规范对数据进行编码 |
| static [ISMN](./ismn/) | 指定应使用 **ISMN** 条形码规范对数据进行编码 |
| static [ISSN](./issn/) | 指定应使用 **ISSN** 条形码规范对数据进行编码 |
| static [ItalianPost25](./italianpost25/) | 表示意大利邮政 25 条形码。 |
| static [ITF14](./itf14/) | 指定数据应使用 **ITF14** 条形码规范进行编码 |
| static [ITF6](./itf6/) | 表示 ITF-6 条形码。 |
| static [JapanPost](./japanpost/) | 表示日本邮政 [BarCode](../../aspose.barcode/) |
| static [MacroPdf417](./macropdf417/) | 指定数据应使用 **MacroPdf417** 条形码规范进行编码 |
| static [Mailmark](./mailmark/) | 表示皇家邮政 Mailmark 条形码。 |
| static [Matrix2of5](./matrix2of5/) | 表示 Matrix 2 of 5 [BarCode](../../aspose.barcode/) |
| static [MaxiCode](./maxicode/) | 指定数据应使用 **MaxiCode** 条形码规范进行编码 |
| static [MicroPdf417](./micropdf417/) | 指定数据应使用 **MicroPdf417** 条形码规范进行编码 |
| static [MicroQR](./microqr/) | 指定数据应使用 **MicroQR Code** 条形码规范进行编码 |
| static [MSI](./msi/) | 指定数据应使用 **MSI Plessey** 条形码规范进行编码 |
| static [None](./none/) | 未指定的编码类型。 |
| static [OneCode](./onecode/) | 指定数据应使用 USPS **OneCode** 条形码规范进行编码 |
| static [OPC](./opc/) | 表示 OPC（光学产品代码）条形码，也称为 VCA 条形码 VCA OPC，Vision Council of America OPC 条形码。 |
| static [PatchCode](./patchcode/) | 表示 Patch code 条形码 |
| static [Pdf417](./pdf417/) | 指定数据应使用 **Pdf417** 条形码规范进行编码 |
| static [Pharmacode](./pharmacode/) | 表示 Pharmacode 条形码。 |
| static [Planet](./planet/) | 指定数据应使用 **Planet** 条形码规范进行编码 |
| static [Postnet](./postnet/) | 指定数据应使用 **Postnet** 条形码规范进行编码 |
| static [PZN](./pzn/) | 表示 PZN 条形码。此符号也称为 Pharmacy central number（药房中心编号），Pharmazentralnummer（药房中心编号德文）。支持 PZN7 和 PZN8。PZN7 由 6 位或更少数字生成，例如 "123456"。PZN8 由 7 位或更多数字生成，例如 "1234567"。提供的最后校验位将被忽略，由条形码引擎生成。 |
| static [QR](./qr/) | 指定数据应使用 **QR Code** 条形码规范进行编码 |
| static [RectMicroQR](./rectmicroqr/) | 指定数据应使用 **RectMicroQR (rMQR) Code** 条形码规范进行编码 |
| static [RM4SCC](./rm4scc/) | 表示 RM4SCC 条形码。RM4SCC（皇家邮政 4 状态客户代码）用于英国的自动邮件分拣过程。 |
| static [SCC14](./scc14/) | 指定数据应使用 **SCC14** 条形码规范进行编码 |
| static [SingaporePost](./singaporepost/) | 指定数据应使用 **Singapore Post Barcode** 条形码规范进行编码 |
| static [SSCC18](./sscc18/) | 指定应使用 **SSCC18** 条形码规范对数据进行编码 |
| static [Standard2of5](./standard2of5/) | 指定应使用 **Standard 2 of 5** 条形码规范对数据进行编码 |
| static [SwissPostParcel](./swisspostparcel/) | 指定应使用 **Swiss Post Parcel Barcode** 条形码规范对数据进行编码。支持的类型：国内邮件、国际邮件、附加服务（new） |
| static [UPCA](./upca/) | 指定应使用 **UPC-A** 条形码规范对数据进行编码 |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | 指定应使用 **UPC coupon with GS1-128 Extended Code** 条形码规范对数据进行编码。示例输入字符串：BarcodeGenerator.Codetext = "514141100906(8102)03"，其中 UPCA 部分为 "514141100906"，GS1Code128 部分为 (8102)03。 |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | 指定应使用 **UPC coupon with GS1 DataBar addition** 条形码规范对数据进行编码。示例输入字符串：BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000"，其中 UPCA 部分为 "514141100906"，Databar 部分为 "(8110)106141416543213500110000310123196000"。要更改标题，请使用 Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static [UPCE](./upce/) | 指定应使用 **UPC-E** 条形码规范对数据进行编码 |
| static [VIN](./vin/) | 表示 VIN（车辆识别号码）条形码。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
