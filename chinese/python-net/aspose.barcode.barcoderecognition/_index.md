---
title: "aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.barcoderecognition/
---


包含用于 1D/2D 条形码识别的工具。

## 类
| 类 | 描述 |
| :- | :- |
| [AustraliaPostCustomerInformationDecoder](/barcode/python-net/aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder/) | 公共接口用于 Customer Information Field 解码，该接口用于 AustraliaPost 符号。实现应由用户提供。 |
| [AustraliaPostSettings](/barcode/python-net/aspose.barcode.barcoderecognition/australiapostsettings/) | AustraliaPost 解码参数。包含对 AustraliaPost 符号的已识别数据产生影响的参数。 |
| [AztecExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/aztecextendedparameters/) | 存储已识别的 Aztec 条码的特殊数据 |
| [BarCodeExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/barcodeextendedparameters/) | 存储已识别条码的扩展参数 |
| [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) | BarCodeReader 封装可能包含一个或多个条码的图像，然后可以执行 ReadBarCodes 操作来检测条码。 |
| [BarCodeRegionParameters](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderegionparameters/) | 表示已识别条码的区域和条码角度 |
| [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) | 存储已识别条码的数据，例如 [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) 类型、字符串 codetext、<br/>            [BarCodeRegionParameters](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderegionparameters/) 区域以及其他参数 |
| [BarcodeSettings](/barcode/python-net/aspose.barcode.barcoderecognition/barcodesettings/) | 主要的 BarCode 解码参数。包含对已识别数据产生影响的参数。 |
| [BaseDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/basedecodetype/) | MultiDecodeType 和 SingleDecodeType 的基类。 |
| [BaseExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/baseextendedparameters/) | 用于存储已识别条码的扩展参数的基础类 |
| [CodabarExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/codabarextendedparameters/) | 存储已识别条码的 Codabar 附加信息 |
| [Code128DataPortion](/barcode/python-net/aspose.barcode.barcoderecognition/code128dataportion/) | 包含 Code128 类型条码的子类型数据 |
| [Code128ExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/code128extendedparameters/) | 存储已识别的 Code128 条码的特殊数据 |
| [DataBarExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/databarextendedparameters/) | 存储已识别条码的 DataBar 附加信息 |
| [DataMatrixExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/) | 存储已识别的 DataMatrix 条码的特殊数据 |
| [DecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/decodetype/) | 指定要读取的条形码类型。 |
| [DotCodeExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/dotcodeextendedparameters/) | 存储 DotCode 识别的条形码的特殊数据 |
| [GS1CompositeBarExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/gs1compositebarextendedparameters/) | 存储 GS1 Composite Bar 识别的条形码的特殊数据 |
| [Iso15416Quality](/barcode/python-net/aspose.barcode.barcoderecognition/iso15416quality/) | 存储根据 ISO/IEC 15416 标准为 1D 条形码计算的条形码质量等级。 |
| [IsoSymbolQuality](/barcode/python-net/aspose.barcode.barcoderecognition/isosymbolquality/) | 根据 ISO/IEC 标准存储条形码符号质量评估结果。 |
| [LuminanceFrame](/barcode/python-net/aspose.barcode.barcoderecognition/luminanceframe/) | 表示一个 8 位灰度图像帧。每个像素由一个包含其亮度值的字节表示。 |
| [MaxiCodeExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/maxicodeextendedparameters/) | 存储已识别条形码的 MaxiCode 附加信息 |
| [MultiDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/multidecodetype/) | 复合解码类型。 |
| [OneDExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/onedextendedparameters/) | 存储 1D 已识别条形码的特殊数据，例如单独的代码文本和校验和 |
| [Pdf417ExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/pdf417extendedparameters/) | 存储已识别条形码的 MacroPdf417 元数据 |
| [QRExtendedParameters](/barcode/python-net/aspose.barcode.barcoderecognition/qrextendedparameters/) | 存储已识别条形码的 QR 结构化追加信息 |
| [Quadrangle](/barcode/python-net/aspose.barcode.barcoderecognition/quadrangle/) | 存储一组四个 [Point](/barcode/python-net/aspose.drawing/point/) ，它们表示一个 [Quadrangle](/barcode/python-net/aspose.barcode.barcoderecognition/quadrangle/) 区域。 |
| [QualitySettings](/barcode/python-net/aspose.barcode.barcoderecognition/qualitysettings/) | QualitySettings 允许手动配置识别质量和速度。<br/> 您可以使用内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxQuality，或者手动配置各个选项。<br/> QualitySettings 的默认值为 NormalQuality。 |
| [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) | 单一解码类型。参见 decode type 获取实例。 |
## 枚举
| 枚举 | 描述 |
| :- | :- |
| [BarCodeConfidence](/barcode/python-net/aspose.barcode.barcoderecognition/barcodeconfidence/) | 包含识别置信度水平 |
|[BarcodeQualityMode](/barcode/python-net/aspose.barcode.barcoderecognition/barcodequalitymode/)||
|[ChecksumValidation](/barcode/python-net/aspose.barcode.barcoderecognition/checksumvalidation/)||
| [Code128SubType](/barcode/python-net/aspose.barcode.barcoderecognition/code128subtype/) | 包含 Code128 子集的类型 |
|[ComplexBackgroundMode](/barcode/python-net/aspose.barcode.barcoderecognition/complexbackgroundmode/)||
|[DeconvolutionMode](/barcode/python-net/aspose.barcode.barcoderecognition/deconvolutionmode/)||
|[InverseImageMode](/barcode/python-net/aspose.barcode.barcoderecognition/inverseimagemode/)||
|[XDimensionMode](/barcode/python-net/aspose.barcode.barcoderecognition/xdimensionmode/)||
