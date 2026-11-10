---
title: "类 EncodeTypes"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.EncodeTypes 类。指定要编码的条码类型"
type: docs
weight: 1290
url: /zh/net/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class

指定要编码的条码类型。

```csharp
public static class EncodeTypes
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [AllEncodeTypes](../../aspose.barcode.generation/encodetypes/allencodetypes/) { get; } | 指定将使用所有可用的符号集检查数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [GetNames](../../aspose.barcode.generation/encodetypes/getnames/)() | 检索编码类型名称的数组。 |
| static [Parse](../../aspose.barcode.generation/encodetypes/parse/)(string, out BaseEncodeType) | 将 BaseEncodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](../../aspose.barcode.generation/encodetypes/tryparse/)(string, out BaseEncodeType) | 将 BaseEncodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [AustralianPosteParcel](../../aspose.barcode.generation/encodetypes/australianposteparcel/) | 指定数据应使用 **Australian Post Domestic eParcel Barcode** 条码规范进行编码 |
| static readonly [AustraliaPost](../../aspose.barcode.generation/encodetypes/australiapost/) | 表示 Australia Post 客户条码 |
| static readonly [Aztec](../../aspose.barcode.generation/encodetypes/aztec/) | 指定数据应使用 **Aztec** 条码规范进行编码 |
| static readonly [Codabar](../../aspose.barcode.generation/encodetypes/codabar/) | 指定数据应使用 **CODABAR** 条码规范进行编码 |
| static readonly [CodablockF](../../aspose.barcode.generation/encodetypes/codablockf/) | 指定数据应使用 **Codablock-F** 条码规范进行编码。 |
| static readonly [Code11](../../aspose.barcode.generation/encodetypes/code11/) | 指定数据应使用 **CODE 11** 条码规范进行编码 |
| static readonly [Code128](../../aspose.barcode.generation/encodetypes/code128/) | 指定应使用 **CODE 128** 条形码规范对数据进行编码 |
| static readonly [Code16K](../../aspose.barcode.generation/encodetypes/code16k/) | 表示 Code 16K 条形码。 |
| static readonly [Code32](../../aspose.barcode.generation/encodetypes/code32/) | 指定应使用 **Code32** 条形码规范对数据进行编码 |
| static readonly [Code39](../../aspose.barcode.generation/encodetypes/code39/) | 指定应使用 **Code 39** 基本字符集条形码规范进行编码：ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.generation/encodetypes/code39fullascii/) | 指定应使用 **Code 39** 完整 ASCII 字符集条形码规范进行编码：ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.generation/encodetypes/code93/) | 指定应使用 **CODE 93** 条形码规范对数据进行编码 |
| static readonly [DatabarExpanded](../../aspose.barcode.generation/encodetypes/databarexpanded/) | 表示 GS1 Databar 扩展条形码。 |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.generation/encodetypes/databarexpandedstacked/) | 表示 GS1 Databar 扩展堆叠条形码。 |
| static readonly [DatabarLimited](../../aspose.barcode.generation/encodetypes/databarlimited/) | 表示 GS1 Databar 限制条形码。 |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.generation/encodetypes/databaromnidirectional/) | 指定应使用 **GS1 Databar omni-directional** 条形码规范对数据进行编码。 |
| static readonly [DatabarStacked](../../aspose.barcode.generation/encodetypes/databarstacked/) | 表示 GS1 Databar 堆叠条形码。 |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.generation/encodetypes/databarstackedomnidirectional/) | 表示 GS1 Databar 堆叠全向条形码。 |
| static readonly [DatabarTruncated](../../aspose.barcode.generation/encodetypes/databartruncated/) | 指定应使用 **GS1 Databar truncated** 条形码规范对数据进行编码。 |
| static readonly [DataLogic2of5](../../aspose.barcode.generation/encodetypes/datalogic2of5/) | 指定应使用 **DataLogic 2 of 5** 条形码规范对数据进行编码 |
| static readonly [DataMatrix](../../aspose.barcode.generation/encodetypes/datamatrix/) | 二维条形码符号 DataMatrix |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.generation/encodetypes/deutschepostidentcode/) | 表示 Deutsch Post 条形码，此符号也称为 Identcode、CodeIdentcode、German Postal 2 of 5 Identcode、Deutsch Post AG Identcode、Deutsch Frachtpost Identcode、Deutsch Post AG (DHL) |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.generation/encodetypes/deutschepostleitcode/) | 表示 Deutsch Post Leitcode 条形码，也称为 German Postal 2 of 5 Leitcode、CodeLeitcode、Leitcode、Deutsch Post AG (DHL)。 |
| static readonly [DotCode](../../aspose.barcode.generation/encodetypes/dotcode/) | 指定应使用 **DotCode** 条形码规范对数据进行编码 |
| static readonly [DutchKIX](../../aspose.barcode.generation/encodetypes/dutchkix/) | 指定应使用 **Dutch KIX** 条形码规范对数据进行编码 |
| static readonly [EAN13](../../aspose.barcode.generation/encodetypes/ean13/) | 指定应使用 **EAN-13** 条形码规范对数据进行编码 |
| static readonly [EAN14](../../aspose.barcode.generation/encodetypes/ean14/) | 指定应使用 **EAN14** 条形码规范对数据进行编码 |
| static readonly [EAN8](../../aspose.barcode.generation/encodetypes/ean8/) | 指定应使用 **EAN-8** 条形码规范对数据进行编码 |
| static readonly [GS1Aztec](../../aspose.barcode.generation/encodetypes/gs1aztec/) | 指定应使用 **GS1 Aztec** 条形码规范对数据进行编码。代码文本必须包含 AI 的括号。 |
| static readonly [GS1CodablockF](../../aspose.barcode.generation/encodetypes/gs1codablockf/) | 指定应使用 **GS1 Codablock-F** 条形码规范对数据进行编码。代码文本必须包含 AI 的括号。 |
| static readonly [GS1Code128](../../aspose.barcode.generation/encodetypes/gs1code128/) | 指定应使用 **GS1 Code 128** 条形码规范对数据进行编码。代码文本必须包含 AI 的括号。 |
| static readonly [GS1CompositeBar](../../aspose.barcode.generation/encodetypes/gs1compositebar/) | 指定应使用 **GS1 Composite Bar** 条码规范对数据进行编码。代码文本必须包含 AI 的括号。1D 代码文本和 2D 代码文本必须用符号 '/' 分隔 |
| static readonly [GS1DataMatrix](../../aspose.barcode.generation/encodetypes/gs1datamatrix/) | 带有 GS1 字符串格式的 2D 条码符号 DataMatrix |
| static readonly [GS1DotCode](../../aspose.barcode.generation/encodetypes/gs1dotcode/) | 指定应使用 **GS1 DotCode** 条码规范对数据进行编码。代码文本必须包含 AI 的括号。 |
| static readonly [GS1HanXin](../../aspose.barcode.generation/encodetypes/gs1hanxin/) | 带有 GS1 字符串格式的 2D 条码符号 HanXin |
| static readonly [GS1MicroPdf417](../../aspose.barcode.generation/encodetypes/gs1micropdf417/) | 指定应使用 **GS1MicroPdf417** 条码规范对数据进行编码 |
| static readonly [GS1QR](../../aspose.barcode.generation/encodetypes/gs1qr/) | 带有 GS1 字符串格式的 2D 条码符号 QR |
| static readonly [HanXin](../../aspose.barcode.generation/encodetypes/hanxin/) | 指定应使用 **Han Xin** 条码规范对数据进行编码 |
| static readonly [HIBCAztecLIC](../../aspose.barcode.generation/encodetypes/hibcazteclic/) | 指定应使用 **HIBC LIC Aztec** 条码规范对数据进行编码。 |
| static readonly [HIBCAztecPAS](../../aspose.barcode.generation/encodetypes/hibcaztecpas/) | 指定应使用 **HIBC PAS Aztec** 条码规范对数据进行编码。 |
| static readonly [HIBCCode128LIC](../../aspose.barcode.generation/encodetypes/hibccode128lic/) | 指定应使用 **HIBC LIC Code128** 条码规范对数据进行编码。 |
| static readonly [HIBCCode128PAS](../../aspose.barcode.generation/encodetypes/hibccode128pas/) | 指定应使用 **HIBC PAS Code128** 条码规范对数据进行编码。 |
| static readonly [HIBCCode39LIC](../../aspose.barcode.generation/encodetypes/hibccode39lic/) | 指定应使用 **HIBC LIC Code39** 条码规范对数据进行编码。 |
| static readonly [HIBCCode39PAS](../../aspose.barcode.generation/encodetypes/hibccode39pas/) | 指定应使用 **HIBC PAS Code39** 条码规范对数据进行编码。 |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.generation/encodetypes/hibcdatamatrixlic/) | 指定应使用 **HIBC LIC DataMatrix** 条码规范对数据进行编码。 |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.generation/encodetypes/hibcdatamatrixpas/) | 指定应使用 **HIBC PAS DataMatrix** 条码规范对数据进行编码。 |
| static readonly [HIBCQRLIC](../../aspose.barcode.generation/encodetypes/hibcqrlic/) | 指定应使用 **HIBC LIC QR** 条码规范对数据进行编码。 |
| static readonly [HIBCQRPAS](../../aspose.barcode.generation/encodetypes/hibcqrpas/) | 指定应使用 **HIBC PAS QR** 条码规范对数据进行编码。 |
| static readonly [IATA2of5](../../aspose.barcode.generation/encodetypes/iata2of5/) | 表示 IATA 2 of 5 条码。IATA（国际航空运输协会）使用此条码来管理航空货物。 |
| static readonly [Interleaved2of5](../../aspose.barcode.generation/encodetypes/interleaved2of5/) | 指定应使用 **INTERLEAVED 2 of 5** 条码规范对数据进行编码 |
| static readonly [ISBN](../../aspose.barcode.generation/encodetypes/isbn/) | 指定应使用 **ISBN** 条码规范对数据进行编码 |
| static readonly [ISMN](../../aspose.barcode.generation/encodetypes/ismn/) | 指定应使用 **ISMN** 条码规范对数据进行编码 |
| static readonly [ISSN](../../aspose.barcode.generation/encodetypes/issn/) | 指定应使用 **ISSN** 条码规范对数据进行编码 |
| static readonly [ItalianPost25](../../aspose.barcode.generation/encodetypes/italianpost25/) | 表示意大利邮政 25 条码。 |
| static readonly [ITF14](../../aspose.barcode.generation/encodetypes/itf14/) | 指定应使用 **ITF14** 条码规范对数据进行编码 |
| static readonly [ITF6](../../aspose.barcode.generation/encodetypes/itf6/) | 表示 ITF-6 条码。 |
| static readonly [JapanPost](../../aspose.barcode.generation/encodetypes/japanpost/) | 表示日本邮政条形码 |
| static readonly [MacroPdf417](../../aspose.barcode.generation/encodetypes/macropdf417/) | 指定应使用 **MacroPdf417** 条形码规范对数据进行编码 |
| static readonly [Mailmark](../../aspose.barcode.generation/encodetypes/mailmark/) | 表示皇家邮政 Mailmark 条形码。 |
| static readonly [Matrix2of5](../../aspose.barcode.generation/encodetypes/matrix2of5/) | 表示 Matrix 2 of 5 条形码 |
| static readonly [MaxiCode](../../aspose.barcode.generation/encodetypes/maxicode/) | 指定应使用 **MaxiCode** 条形码规范对数据进行编码 |
| static readonly [MicroPdf417](../../aspose.barcode.generation/encodetypes/micropdf417/) | 指定应使用 **MicroPdf417** 条形码规范对数据进行编码 |
| static readonly [MicroQR](../../aspose.barcode.generation/encodetypes/microqr/) | 指定应使用 **MicroQR Code** 条形码规范对数据进行编码 |
| static readonly [MSI](../../aspose.barcode.generation/encodetypes/msi/) | 指定应使用 **MSI Plessey** 条形码规范对数据进行编码 |
| static readonly [None](../../aspose.barcode.generation/encodetypes/none/) | 未指定的编码类型。 |
| static readonly [OneCode](../../aspose.barcode.generation/encodetypes/onecode/) | 指定应使用 USPS **OneCode** 条形码规范对数据进行编码 |
| static readonly [OPC](../../aspose.barcode.generation/encodetypes/opc/) | 表示 OPC（光学产品代码）条形码，也称为 VCA 条形码 VCA OPC，Vision Council of America OPC 条形码。 |
| static readonly [PatchCode](../../aspose.barcode.generation/encodetypes/patchcode/) | 表示 Patch code 条形码 |
| static readonly [Pdf417](../../aspose.barcode.generation/encodetypes/pdf417/) | 指定应使用 **Pdf417** 条形码规范对数据进行编码 |
| static readonly [Pharmacode](../../aspose.barcode.generation/encodetypes/pharmacode/) | 表示 Pharmacode 条形码。 |
| static readonly [Planet](../../aspose.barcode.generation/encodetypes/planet/) | 指定应使用 **Planet** 条形码规范对数据进行编码 |
| static readonly [Postnet](../../aspose.barcode.generation/encodetypes/postnet/) | 指定应使用 **Postnet** 条形码规范对数据进行编码 |
| static readonly [PZN](../../aspose.barcode.generation/encodetypes/pzn/) | 表示 PZN 条形码。此符号也称为药房中心号码（Pharmacy central number），Pharmazentralnummer。支持 PZN7 和 PZN8。PZN7 由 6 位或更少的数字生成，例如 "123456"。PZN8 由 7 位或更多的数字生成，例如 "1234567"。提供的最后校验位将被忽略，由条形码引擎生成。 |
| static readonly [QR](../../aspose.barcode.generation/encodetypes/qr/) | 指定应使用 **QR Code** 条形码规范对数据进行编码 |
| static readonly [RectMicroQR](../../aspose.barcode.generation/encodetypes/rectmicroqr/) | 指定应使用 **RectMicroQR (rMQR) Code** 条形码规范对数据进行编码 |
| static readonly [RM4SCC](../../aspose.barcode.generation/encodetypes/rm4scc/) | 表示 RM4SCC 条形码。RM4SCC（Royal Mail 4-state Customer Code）用于英国的自动邮件分拣过程。 |
| static readonly [SCC14](../../aspose.barcode.generation/encodetypes/scc14/) | 指定应使用 **SCC14** 条形码规范对数据进行编码 |
| static readonly [SingaporePost](../../aspose.barcode.generation/encodetypes/singaporepost/) | 指定应使用 **Singapore Post Barcode** 条形码规范对数据进行编码 |
| static readonly [SSCC18](../../aspose.barcode.generation/encodetypes/sscc18/) | 指定应使用 **SSCC18** 条形码规范对数据进行编码 |
| static readonly [Standard2of5](../../aspose.barcode.generation/encodetypes/standard2of5/) | 指定应使用 **Standard 2 of 5** 条形码规范对数据进行编码 |
| static readonly [SwissPostParcel](../../aspose.barcode.generation/encodetypes/swisspostparcel/) | 指定应使用 **Swiss Post Parcel Barcode** 条形码规范对数据进行编码。支持的类型：国内邮件，国际邮件，附加服务（新）。 |
| static readonly [UPCA](../../aspose.barcode.generation/encodetypes/upca/) | 指定应使用 **UPC-A** 条形码规范对数据进行编码 |
| static readonly [UpcaGs1Code128Coupon](../../aspose.barcode.generation/encodetypes/upcags1code128coupon/) | 指定应使用 **UPC coupon with GS1-128 Extended Code** 条形码规范对数据进行编码。输入字符串示例：BarcodeGenerator.Codetext = "514141100906(8102)03"，其中 UPCA 部分为 "514141100906"，GS1Code128 部分为 (8102)03。 |
| static readonly [UpcaGs1DatabarCoupon](../../aspose.barcode.generation/encodetypes/upcags1databarcoupon/) | 指定应使用 **UPC coupon with GS1 DataBar addition** 条形码规范对数据进行编码。输入字符串示例：BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000"，其中 UPCA 部分为 "514141100906"，Databar 部分为 "(8110)106141416543213500110000310123196000"。要更改标题，请使用 Parameters.CaptionAbove.Text = "company prefix + offer code"； |
| static readonly [UPCE](../../aspose.barcode.generation/encodetypes/upce/) | 指定应使用 **UPC-E** 条形码规范对数据进行编码 |
| static readonly [VIN](../../aspose.barcode.generation/encodetypes/vin/) | 表示 VIN（车辆识别号码）条形码。 |

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


