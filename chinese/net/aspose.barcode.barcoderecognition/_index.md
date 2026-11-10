---
title: "Aspose.BarCode.BarCodeRecognition"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition 包含用于 1D/2D 条码识别的工具。"
type: docs
weight: 20
url: /zh/net/aspose.barcode.barcoderecognition/
---
该 **Aspose.BarCode.BarCodeRecognition** 包含用于 1D/2D 条码识别的工具。

## 类

| 类 | 描述 |
| --- | --- |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost 解码参数。包含对 AustraliaPost 符号学的已识别数据产生影响的参数。 |
| [AztecExtendedParameters](./aztecextendedparameters/) | 存储已识别 Aztec 条码的特殊数据。 |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | 存储已识别条码的扩展参数。 |
| [BarCodeReader](./barcodereader/) | BarCodeReader 封装可能包含一个或多个条码的图像，然后可以执行 ReadBarCodes 操作来检测条码。 |
| [BarCodeRecognitionException](./barcoderecognitionexception/) | BarCodeReader 抛出的通用异常，继承自 BarCodeException。 |
| [BarCodeRegionParameters](./barcoderegionparameters/) | 表示已识别条码的区域和条码角度。 |
| [BarCodeResult](./barcoderesult/) | 存储已识别条码的数据，例如 [`SingleDecodeType`](../aspose.barcode.barcoderecognition/singledecodetype/) 类型、String codetext、[`BarCodeRegionParameters`](../aspose.barcode.barcoderecognition/barcoderegionparameters/) 区域以及其他参数。 |
| [BarcodeSettings](./barcodesettings/) | 主要的 BarCode 解码参数。包含对已识别数据产生影响的参数。 |
| [BaseDecodeType](./basedecodetype/) | MultiDecodeType 和 SingleDecodeType 的基类。 |
| [BaseExtendedParameters](./baseextendedparameters/) | 用于存储已识别条码的扩展参数的基础类。 |
| [CodabarExtendedParameters](./codabarextendedparameters/) | 存储已识别条码的 Codabar 附加信息。 |
| [Code128DataPortion](./code128dataportion/) | 包含 Code128 类型条码的子类型数据。 |
| [Code128ExtendedParameters](./code128extendedparameters/) | 存储已识别 Code128 条码的特殊数据。 |
| [DataBarExtendedParameters](./databarextendedparameters/) | 存储已识别条码的 DataBar 附加信息。 |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | 存储已识别 DataMatrix 条码的特殊数据。 |
| [DecodeType](./decodetype/) | 指定要读取的条码类型。 |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | 存储已识别 DotCode 条码的特殊数据。 |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | 存储已识别的 **GS1 Composite Bar** 条形码的特殊数据 |
| [Iso15416Quality](./iso15416quality/) | 存储根据 ISO/IEC 15416 标准为 1D 条形码计算的条形码质量等级 |
| [IsoSymbolQuality](./isosymbolquality/) | 存储根据 ISO/IEC 标准的条形码符号质量评估结果 |
| [LuminanceFrame](./luminanceframe/) | 表示一个 8 位灰度图像帧。每个像素由一个包含其亮度值的字节表示 |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | 存储已识别的条形码的 MaxiCode 附加信息 |
| [MultiDecodeType](./multidecodetype/) | 复合解码类型 |
| [OneDExtendedParameters](./onedextendedparameters/) | 存储已识别的 1D 条形码的特殊数据，例如独立的代码文本和校验和 |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | 存储已识别的条形码的 MacroPdf417 元数据 |
| [QRExtendedParameters](./qrextendedparameters/) | 存储已识别的条形码的 QR 结构化追加信息 |
| [Quadrangle](./quadrangle/) | 存储一组四个点，表示一个 [`Quadrangle`](../aspose.barcode.barcoderecognition/quadrangle/) 区域。 |
| [QualitySettings](./qualitysettings/) | QualitySettings 允许手动配置识别质量和速度。您可以使用内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxQuality，或者手动配置各个选项。QualitySettings 的默认值为 NormalQuality。 |
| [RecognitionAbortedException](./recognitionabortedexception/) | 表示在使用 BarCodeReader 进行识别时超时后抛出的识别中止异常。 |
| [SingleDecodeType](./singledecodetype/) | 单一解码类型。请参阅解码类型以获取实例。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | 用于 AustraliaPost 符号中的客户信息字段解码的公共接口。实现应由用户提供。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [BarCodeConfidence](./barcodeconfidence/) | 包含识别置信度水平 |
| [BarcodeQualityMode](./barcodequalitymode/) | 模式，使能够使用所选质量识别条形码元素。质量较低的条形码元素需要更复杂的方法，从而减慢识别速度。 |
| [ChecksumValidation](./checksumvalidation/) | 在识别 1D 和邮政条形码时启用校验和验证。 |
| [Code128SubType](./code128subtype/) | 包含 Code128 子集的类型 |
| [ComplexBackgroundMode](./complexbackgroundmode/) | 模式，启用或禁用对彩色图像中彩色条形码的额外识别。 |
| [DeconvolutionMode](./deconvolutionmode/) | 去卷积（图像恢复）模式，用于定义图像退化的程度。去卷积最初是一种能够恢复因自然函数（如模糊）在相机拍摄时导致的退化（卷积）图像的功能。由于我们无法检测导致图像损坏的函数，只能检查最常见的函数，如锐化或数学形态学。 |
| [InverseImageMode](./inverseimagemode/) | 模式，启用或禁用对颜色反转（亮度）图像中条形码的额外识别。 |
| [XDimensionMode](./xdimensionmode/) | 识别模式，用于设置条形码最小元素（矩阵单元或条）的大小（从 1 到无限大）。 |


