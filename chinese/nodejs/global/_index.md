---
title: "全局"
linktitle: "全局"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "Global 命名空间将跨 Aspose.BarCode for Node.js via Java 使用的核心枚举和实用类进行分组。"
type: docs
weight: 20
url: /zh/nodejs/global/
---
Global 命名空间提供了一组基本枚举和辅助类型，用于定义条码属性，例如编码模式、符号大小、置信水平和图像格式。这些定义在 Aspose.BarCode API 中被广泛引用，以配置和解释条码的生成和识别。

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AddressType](./addresstype/) | 地址类型 |
| [AutoSizeMode](./autosizemode/) | 指定不同类型的自动尺寸模式。默认值为 AutoSizeMode.NONE。 |
| [AztecEncodeMode](./aztecencodemode/) | Aztec 条码的编码模式。 |
| [AztecSymbolMode](./aztecsymbolmode/) | 指定 Aztec 符号模式。 |
| [BarCodeConfidence](./barcodeconfidence/) | 包含识别置信水平 |
| [BarCodeImageFormat](./barcodeimageformat/) | 指定图像的文件格式。 |
| [BarcodeClassifications](./barcodeclassifications/) | BarcodeClassifications EncodeTypes 分类 |
| [BarcodeQualityMode](./barcodequalitymode/) | 启用方法以使用所选质量识别条码元素的模式。质量较低的条码元素 r |
| [BorderDashStyle](./borderdashstyle/) | 指定虚线边框的样式。 |
| [ChecksumValidation](./checksumvalidation/) | 在识别 1D 条码时启用校验和验证。默认情况下，对于必须包含校验和的符号系统，视为是。 |
| [CodabarChecksumMode](./codabarchecksummode/) | 指定 Codabar 的校验和算法 |
| [CodabarSymbol](./codabarsymbol/) | 指定 Codabar 条码规范的起始或结束符号。 |
| [Code128EncodeMode](./code128encodemode/) | Code128 条码的编码模式。`Code 128` 规范。此代码演示如何使用不同的方式生成 Code 128。 |
| [Code128SubType](./code128subtype/) | 包含 Code128 子集的类型 |
| [CodeLocation](./codelocation/) | 代码文本位置 |
| [ComplexBackgroundMode](./complexbackgroundmode/) | 在彩色图像上启用或禁用额外颜色条码识别的模式。此示例展示了如何使用 Co |
| [CustomerInformationInterpretingType](./customerinformationinterpretingtype/) | 定义 AustralianPost 条码的客户信息解释类型（C_TABLE 或 N_TABLE）。 |
| [DataMatrixEccType](./datamatrixecctype/) | 指定要编码的 ECC 类型。 |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | DataMatrix 编码器的编码模式，默认自动。此示例展示了如何在扩展模式下进行代码文本。//Auto mode l |
| [DataMatrixVersion](./datamatrixversion/) | 指定要编码的 ECC 类型。 |
| [DecodeType](./decodetype/) | 指定要读取的条码类型。 |
| [DeconvolutionMode](./deconvolutionmode/) | 去卷积（图像恢复）模式，定义图像退化的程度。最初去卷积是一个函数 |
| [DotCodeEncodeMode](./dotcodeencodemode/) | DotCode 条码的编码模式。 |
| [ECIEncodings](./eciencodings/) | 扩展通道解释标识符。用于向条码读取器提供有关所使用参考的详细信息。 |
| [EnableChecksum](./enablechecksum/) | 在生成 1D 条码时启用校验和。对于必须包含校验和的符号，默认视为是。 |
| [EncodeTypes](./encodetypes/) | 指定要编码的条码类型。 |
| [FontMode](./fontmode/) | 字体大小模式。 |
| [FontStyle](./fontstyle/) | 字体样式分类 |
| [GraphicsUnit](./graphicsunit/) | 指定给定数据的计量单位。 |
| [HIBCLICDateFormat](./hibclicdateformat/) | 指定 HIBC LIC 的不同日期格式类型。 |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | HIBC PAS 数据位置类型。 |
| [HIBCPASDataType](./hibcpasdatatype/) | HIBC PAS 记录的数据类型。 |
| [HanXinEncodeMode](./hanxinencodemode/) | 汉信码编码模式。建议在使用 ASCII/中文字符时选择自动，或在 Unicode 字符时使用 Unicode。 |
| [HanXinErrorLevel](./hanxinerrorlevel/) | Reed-Solomon 错误更正级别。从低到高：L1、L2、L3、L4。 |
| [HanXinVersion](./hanxinversion/) | 汉信码的版本。从 Version01（23×23 模块）到 Version84（189×189 模块），每次增加 2 模块。 |
| [ITF14BorderType](./itf14bordertype/) | ITF14 条码的边框类型 |
| [InverseImageMode](./inverseimagemode/) | 在颜色反转（亮度）图像上启用或禁用额外条码识别的模式。此示例 |
| [MacroCharacter](./macrocharacter/) | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。05 宏字符是 |
| [Mailmark2DType](./mailmark2dtype/) | 2D Mailmark 类型定义 Data Matrix 条码的大小 |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | MaxiCode 条码的编码模式。 |
| [MaxiCodeMode](./maxicodemode/) | MaxiCode 条码的编码模式。 |
| [MicroQRVersion](./microqrversion/) | MicroQR Code 的版本。从 M1 到 M4。 |
| [PatchFormat](./patchformat/) | PatchCode 格式。选择 PatchOnly 生成单个 PatchCode。使用 page 格式生成包含 PatchCodes 的 Patch 页面。 |
| [Pdf417CompactionMode](./pdf417compactionmode/) | Pdf417 条码的压缩模式 |
| [Pdf417EncodeMode](./pdf417encodemode/) | Pdf417 条码的编码模式 |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | pdf417 条码的错误纠正级别，范围从 0 级到 9 级，0 级表示无错误纠正，9 级表示最佳。 |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | 用于告知编码器是否在段中添加 Macro PDF417 终止符（codeword 922）。仅在 Macro PD 中适用。 |
| [QREncodeMode](./qrencodemode/) | QR 条码的编码模式。示例如何使用 ECI 编码 generator = new BarcodeGenerator(EncodeTypes.QR, \"12345TE |
| [QREncodeType](./qrencodetype/) | QR / MicroQR 选择模式。选择 FORCE_QR 以获取标准 QR 符号，AUTO 用于 MicroQR。FORCE_MICRO_QR 用于强制。 |
| [QRErrorLevel](./qrerrorlevel/) | Reed-Solomon 错误纠正的级别。从低到高：LEVEL_L、LEVEL_M、LEVEL_Q、LEVEL_H。 |
| [QRVersion](./qrversion/) | QR 码的版本。从 Version1 到 Version40 适用于 QR 码，M1 到 M4 适用于 MicroQr。 |
| [QrBillStandardVersion](./qrbillstandardversion/) | SwissQR 账单标准版本 |
| [QrExtCompactionMode](./qrextcompactionmode/) | 指定由 QrExtCodetextBuilder 添加的代码文本的 QR 压缩模式。 |
| [RectMicroQRVersion](./rectmicroqrversion/) | RectMicroQR 码的版本。从 R7x43 版本到 R17x139 版本。 |
| [SvgColorMode](./svgcolormode/) | svg 文件中填充颜色的可能模式，RGB 为默认且受 SVG 1.1 支持。SVG 还允许使用 RGBA、HSL、HSLA。 |
| [TextAlignment](./textalignment/) | 文本对齐。 |
