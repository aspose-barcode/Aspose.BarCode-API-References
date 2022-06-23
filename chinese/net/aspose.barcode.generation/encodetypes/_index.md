---
title: EncodeTypes
second_title: Aspose.BarCode for .NET API 参考
description: 指定要编码的条形码类型
type: docs
weight: 720
url: /zh/net/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class

指定要编码的条形码类型。

```csharp
public static class EncodeTypes
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [AllEncodeTypes](../../aspose.barcode.generation/encodetypes/allencodetypes) { get; } | 指定将使用所有可用符号体系检查数据。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [GetNames](../../aspose.barcode.generation/encodetypes/getnames)() | 检索编码类型名称的数组。 |
| static [Parse](../../aspose.barcode.generation/encodetypes/parse)(string, out BaseEncodeType) | 将 BaseEncodeType 的字符串表示形式转换为其实例。 返回值指示转换是成功还是失败。 |
| static [TryParse](../../aspose.barcode.generation/encodetypes/tryparse)(string, out BaseEncodeType) | 将 BaseEncodeType 的字符串表示形式转换为其实例。 返回值指示转换是成功还是失败。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [AustralianPosteParcel](../../aspose.barcode.generation/encodetypes/australianposteparcel) | 指定数据应使用 **澳大利亚邮政国内电子包裹条码** 条码规范 编码 |
| static readonly [AustraliaPost](../../aspose.barcode.generation/encodetypes/australiapost) | 代表澳大利亚邮政客户条形码 |
| static readonly [Aztec](../../aspose.barcode.generation/encodetypes/aztec) | 指定数据应使用 **Aztec** 条形码规范 进行编码 |
| static readonly [Codabar](../../aspose.barcode.generation/encodetypes/codabar) | 指定数据应使用 **CODABAR** 条码规范 进行编码 |
| static readonly [CodablockF](../../aspose.barcode.generation/encodetypes/codablockf) | 指定数据应使用 **Codablock-F** 条形码规范进行编码。 |
| static readonly [Code11](../../aspose.barcode.generation/encodetypes/code11) | 指定数据应使用 **CODE 11** 条码规范 编码 |
| static readonly [Code128](../../aspose.barcode.generation/encodetypes/code128) | 指定数据应使用 **CODE 128** 条码规范 编码 |
| static readonly [Code16K](../../aspose.barcode.generation/encodetypes/code16k) | 代表 Code 16K 条码。 |
| static readonly [Code32](../../aspose.barcode.generation/encodetypes/code32) | 指定数据应使用 **Code32** 条码规范 进行编码 |
| static readonly [Code39Extended](../../aspose.barcode.generation/encodetypes/code39extended) | 指定数据应使用 **Extended CODE 39** 条码规范 编码 |
| static readonly [Code39Standard](../../aspose.barcode.generation/encodetypes/code39standard) | 指定数据应使用 **Standard CODE 39** 条码规范 编码 |
| static readonly [Code93Extended](../../aspose.barcode.generation/encodetypes/code93extended) | 指定数据应使用 **Extended CODE 93** 条码规范 编码 |
| static readonly [Code93Standard](../../aspose.barcode.generation/encodetypes/code93standard) | 指定数据应使用 **Standard CODE 93** 条码规范 编码 |
| static readonly [DatabarExpanded](../../aspose.barcode.generation/encodetypes/databarexpanded) | 代表 GS1 Databar 扩展条码。 |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.generation/encodetypes/databarexpandedstacked) | 表示 GS1 Databar 扩展堆叠条码。 |
| static readonly [DatabarLimited](../../aspose.barcode.generation/encodetypes/databarlimited) | 代表 GS1 Databar 限制条码。 |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.generation/encodetypes/databaromnidirectional) | 指定数据应使用 **GS1 Databar 全向** 条码规范进行编码。 |
| static readonly [DatabarStacked](../../aspose.barcode.generation/encodetypes/databarstacked) | 表示 GS1 Databar 堆叠条码。 |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.generation/encodetypes/databarstackedomnidirectional) | 代表 GS1 Databar 堆叠的全方位条码。 |
| static readonly [DatabarTruncated](../../aspose.barcode.generation/encodetypes/databartruncated) | 指定数据应使用 **GS1 Databar truncated** 条形码规范进行编码。 |
| static readonly [DataLogic2of5](../../aspose.barcode.generation/encodetypes/datalogic2of5) | 指定数据应使用 **DataLogic 2 of 5** 条形码规范 |
| static readonly [DataMatrix](../../aspose.barcode.generation/encodetypes/datamatrix) | 二维条码符号 DataMatrix |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.generation/encodetypes/deutschepostidentcode) | 表示 Deutsch Post 条码，此符号也称为 Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.generation/encodetypes/deutschepostleitcode) | 表示 Deutsch Post Leitcode Barcode，也称为 German Postal 2 of 5 Leitcode、CodeLeitcode、Leitcode、Deutsch Post AG (DHL)。 |
| static readonly [DotCode](../../aspose.barcode.generation/encodetypes/dotcode) | 指定数据应使用 **DotCode** 条码规范 进行编码 |
| static readonly [DutchKIX](../../aspose.barcode.generation/encodetypes/dutchkix) | 指定数据应使用 **Dutch KIX** 条码规范 编码 |
| static readonly [EAN13](../../aspose.barcode.generation/encodetypes/ean13) | 指定数据应使用 **EAN-13** 条码规范 编码 |
| static readonly [EAN14](../../aspose.barcode.generation/encodetypes/ean14) | 指定数据应使用 **EAN14** 条码规范 进行编码 |
| static readonly [EAN8](../../aspose.barcode.generation/encodetypes/ean8) | 指定数据应使用 **EAN-8** 条码规范 编码 |
| static readonly [GS1CodablockF](../../aspose.barcode.generation/encodetypes/gs1codablockf) | 指定数据应使用 **GS1 Codablock-F** 条形码规范进行编码。代码文本必须包含 AI 的括号。 |
| static readonly [GS1Code128](../../aspose.barcode.generation/encodetypes/gs1code128) | 指定数据应使用 **GS1 Code 128** 条形码规范进行编码。代码文本必须包含 AI 的括号。 |
| static readonly [GS1CompositeBar](../../aspose.barcode.generation/encodetypes/gs1compositebar) | 指定数据应使用 **GS1 Composite Bar** 条形码规范进行编码。代码文本必须包含 AI 的括号。 1D codetext 和 2D codetext 必须用符号'/'分隔 |
| static readonly [GS1DataMatrix](../../aspose.barcode.generation/encodetypes/gs1datamatrix) | 具有 GS1 字符串格式的二维条码符号 DataMatrix |
| static readonly [GS1QR](../../aspose.barcode.generation/encodetypes/gs1qr) | GS1 字符串格式的二维条码符号 QR |
| static readonly [IATA2of5](../../aspose.barcode.generation/encodetypes/iata2of5) | 代表 IATA 2 of 5 条码。IATA（国际航空运输协会）使用此条码管理空运货物。 |
| static readonly [Interleaved2of5](../../aspose.barcode.generation/encodetypes/interleaved2of5) | 指定数据应使用 **INTERLEAVED 2 of 5** 条形码规范 |
| static readonly [ISBN](../../aspose.barcode.generation/encodetypes/isbn) | 指定数据应使用 **ISBN** 条码规范 进行编码 |
| static readonly [ISMN](../../aspose.barcode.generation/encodetypes/ismn) | 指定数据应使用 **ISMN** 条码规范 进行编码 |
| static readonly [ISSN](../../aspose.barcode.generation/encodetypes/issn) | 指定数据应使用 **ISSN** 条码规范 进行编码 |
| static readonly [ItalianPost25](../../aspose.barcode.generation/encodetypes/italianpost25) | 表示意大利邮政 25 条码。 |
| static readonly [ITF14](../../aspose.barcode.generation/encodetypes/itf14) | 指定数据应使用 **ITF14** 条码规范 进行编码 |
| static readonly [ITF6](../../aspose.barcode.generation/encodetypes/itf6) | 代表 ITF-6 条形码。 |
| static readonly [MacroPdf417](../../aspose.barcode.generation/encodetypes/macropdf417) | 指定数据应使用 **MacroPdf417** 条码规范 进行编码 |
| static readonly [Mailmark](../../aspose.barcode.generation/encodetypes/mailmark) | 表示 Royal Mail Mailmark 条形码。 |
| static readonly [Matrix2of5](../../aspose.barcode.generation/encodetypes/matrix2of5) | 表示矩阵 2 of 5 BarCode |
| static readonly [MaxiCode](../../aspose.barcode.generation/encodetypes/maxicode) | 指定数据应使用 **MaxiCode** 条码规范 进行编码 |
| static readonly [MicroPdf417](../../aspose.barcode.generation/encodetypes/micropdf417) | 指定数据应使用 **MicroPdf417** 条形码规范 进行编码 |
| static readonly [MSI](../../aspose.barcode.generation/encodetypes/msi) | 指定数据应使用 **MSI Plessey** 条形码规范 编码 |
| static readonly [None](../../aspose.barcode.generation/encodetypes/none) | 未指定的编码类型。 |
| static readonly [OneCode](../../aspose.barcode.generation/encodetypes/onecode) | 指定数据应使用 USPS **OneCode** 条码规范 编码 |
| static readonly [OPC](../../aspose.barcode.generation/encodetypes/opc) | 代表OPC(Optical Product Code) Barcode，也称为VCA Barcode VCA OPC，美国视觉委员会OPC Barcode。 |
| static readonly [PatchCode](../../aspose.barcode.generation/encodetypes/patchcode) | 代表补丁码条码 |
| static readonly [Pdf417](../../aspose.barcode.generation/encodetypes/pdf417) | 指定数据应使用 **Pdf417** 条形码规范 进行编码 |
| static readonly [Pharmacode](../../aspose.barcode.generation/encodetypes/pharmacode) | 代表 Pharmacode 条形码。 |
| static readonly [Planet](../../aspose.barcode.generation/encodetypes/planet) | 指定数据应使用 **Planet** 条形码规范 进行编码 |
| static readonly [Postnet](../../aspose.barcode.generation/encodetypes/postnet) | 指定数据应使用 **Postnet** 条形码规范 进行编码 |
| static readonly [PZN](../../aspose.barcode.generation/encodetypes/pzn) | 表示 PZN 条形码。此符号也称为 Pharmacy 中心编号，Pharmazentralnummer |
| static readonly [QR](../../aspose.barcode.generation/encodetypes/qr) | 指定数据应使用 **QR Code** 条码规范 编码 |
| static readonly [RM4SCC](../../aspose.barcode.generation/encodetypes/rm4scc) | 代表 RM4SCC 条码。 RM4SCC（皇家邮政四州客户代码）用于英国的自动邮件分拣流程。 |
| static readonly [SCC14](../../aspose.barcode.generation/encodetypes/scc14) | 指定数据应使用 **SCC14** 条码规范 进行编码 |
| static readonly [SingaporePost](../../aspose.barcode.generation/encodetypes/singaporepost) | 指定数据应使用 **新加坡邮政条码** 条码规范 进行编码 |
| static readonly [SSCC18](../../aspose.barcode.generation/encodetypes/sscc18) | 指定数据应使用 **SSCC18** 条码规范 进行编码 |
| static readonly [Standard2of5](../../aspose.barcode.generation/encodetypes/standard2of5) | 指定数据应使用 **Standard 2 of 5** 条形码规范 |
| static readonly [SwissPostParcel](../../aspose.barcode.generation/encodetypes/swisspostparcel) | 指定数据应使用 **Swiss Post Parcel Barcode** 条形码规范进行编码。支持的类型:国内邮件、国际邮件、附加服务（新） |
| static readonly [UPCA](../../aspose.barcode.generation/encodetypes/upca) | 指定数据应使用 **UPC-A** 条码规范 编码 |
| static readonly [UpcaGs1Code128Coupon](../../aspose.barcode.generation/encodetypes/upcags1code128coupon) | 指定数据应使用 **UPC coupon 和 GS1-128 Extended Code** 条形码规范进行编码。 输入字符串示例: BarcodeGenerator.Codetext = "514141100906(8102)03", 其中 UPCA 部分为 "514141100906", GS1Code128 部分是（8102）03。 |
| static readonly [UpcaGs1DatabarCoupon](../../aspose.barcode.generation/encodetypes/upcags1databarcoupon) | 指定数据应使用 **UPC coupon 编码，并添加 GS1 DataBar** 条形码规范。 输入字符串示例: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", 其中 UPCA 部分是 "514141100906", Databar 部分是“（8110）106141416543213500110000310123196000”。 要更改标题，请使用 Parameters.CaptionAbove.Text = "company prefix + offer code"; |
| static readonly [UPCE](../../aspose.barcode.generation/encodetypes/upce) | 指定数据应使用 **UPC-E** 条码规范 编码 |
| static readonly [VIN](../../aspose.barcode.generation/encodetypes/vin) | 代表 VIN（车辆识别号）条形码。 |

### 也可以看看

* 命名空间 [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* 部件 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
