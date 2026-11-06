---
title: "Aspose::BarCode::BarCodeRecognition 命名空间"
linktitle: "Aspose::BarCode::BarCodeRecognition"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用 Aspose::BarCode::BarCodeRecognition 命名空间。"
type: docs
weight: 200
url: /zh/cpp/aspose.barcode.barcoderecognition/
---



## 类

| 类 | 描述 |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | 用于 AustraliaPost 符号系统的客户信息字段解码的公共接口。实现应由用户提供。 |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost 解码参数。包含对 AustraliaPost 符号系统识别数据产生影响的参数。 |
| [AztecExtendedParameters](./aztecextendedparameters/) | 存储 Aztec 识别条码的特殊数据 |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | 存储已识别条码的扩展参数 |
| [BarCodeReader](./barcodereader/) | [BarCodeReader](./barcodereader/) 封装可能包含一个或多个条码的图像，然后可以执行 ReadBarCodes 操作来检测条码。 |
| [BarCodeRegionParameters](./barcoderegionparameters/) | 表示已识别条码的区域和条码角度 |
| [BarCodeResult](./barcoderesult/) | 存储已识别条码的数据，例如 [SingleDecodeType](./singledecodetype/) 类型、**System::String** 代码文本、[BarCodeRegionParameters](./barcoderegionparameters/) 区域以及其他参数。 |
| [BarcodeSettings](./barcodesettings/) | 主要的 [BarCode](../aspose.barcode/) 解码参数。包含对已识别数据产生影响的参数。 |
| [BaseDecodeType](./basedecodetype/) | 用于 [MultiDecodeType](./multidecodetype/) 和 [SingleDecodeType](./singledecodetype/) 的基类。 |
| [BaseExtendedParameters](./baseextendedparameters/) | 用于存储已识别条码的扩展参数的基础类。 |
| [CodabarExtendedParameters](./codabarextendedparameters/) | 存储已识别条码的 Codabar 附加信息。 |
| [Code128DataPortion](./code128dataportion/) | 包含 Code128 类型条码子类型的数据。 |
| [Code128ExtendedParameters](./code128extendedparameters/) | 存储已识别的 Code128 条码的特殊数据。 |
| [DataBarExtendedParameters](./databarextendedparameters/) | 存储已识别条码的 DataBar 附加信息。 |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | 存储已识别的 [DataMatrix](../aspose.barcode.barcoderecognition.datamatrix/) 条码的特殊数据。 |
| [DecodeType](./decodetype/) | 指定要读取的条码类型。 |
| [Details_BarCodeRecognitionException](./details_barcoderecognitionexception/) | 由 [BarCodeReader](./barcodereader/) 抛出的通用异常，继承自 BarCodeException。 |
| [Details_RecognitionAbortedException](./details_recognitionabortedexception/) | 表示在使用 [BarCodeReader](./barcodereader/) 进行识别时超时导致的识别中止异常。 |
| [Details_RecognitionEngineException](./details_recognitionengineexception/) |  |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | 存储已识别的 DotCode 条码的特殊数据。 |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | 存储已识别的 **GS1 Composite Bar** 条码的特殊数据。 |
| [Iso15416Quality](./iso15416quality/) | 根据 ISO/IEC 15416 标准为 1D 条码计算的条码质量等级存储。 |
| [IsoSymbolQuality](./isosymbolquality/) | 根据 ISO/IEC 标准存储条码符号质量评估结果。 |
| [LuminanceFrame](./luminanceframe/) | 表示一个 8 位灰度图像帧。每个像素由包含其亮度值的一个字节表示。 |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | 存储已识别条码的 MaxiCode 附加信息 |
| [MultiDecodeType](./multidecodetype/) | 复合解码类型。 |
| [OneDExtendedParameters](./onedextendedparameters/) | 存储已识别 1D 条码的特殊数据，例如独立的代码文本和校验和 |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | 存储已识别条码的 MacroPdf417 元数据 |
| [QRExtendedParameters](./qrextendedparameters/) | 存储已识别条码的 [QR](../aspose.barcode.barcoderecognition.qr/) 结构追加信息 |
| [Quadrangle](./quadrangle/) | 存储一组四个 [Point](../) ，它们表示一个 [Quadrangle](./quadrangle/) 区域。 |
| [QualitySettings](./qualitysettings/) | [QualitySettings](./qualitysettings/) 允许手动配置识别质量和速度。您可以使用内置预设快速设置 [QualitySettings](./qualitysettings/)：HighPerformance、NormalQuality、HighQuality、MaxQuality，或者手动配置各个选项。[QualitySettings](./qualitysettings/) 的默认值是 NormalQuality。 |
| [SingleDecodeType](./singledecodetype/) | 单一解码类型。请参阅解码类型以获取实例。 |
## Enums

| 枚举 | 描述 |
| --- | --- |
| [ChecksumValidation](./checksumvalidation/) |  |
| [Code128SubType](./code128subtype/) | 包含 Code128 子集的类型 |
| [BarCodeConfidence](./barcodeconfidence/) | 包含识别置信度级别 |
| [BarcodeQualityMode](./barcodequalitymode/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) |  |
| [DeconvolutionMode](./deconvolutionmode/) |  |
| [InverseImageMode](./inverseimagemode/) |  |
| [XDimensionMode](./xdimensionmode/) |  |
## Typedefs

| 类型别名 | 描述 |
| --- | --- |
| [BarCodeRecognitionException](./barcoderecognitionexception/) |  |
| [RecognitionEngineException](./recognitionengineexception/) |  |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |
