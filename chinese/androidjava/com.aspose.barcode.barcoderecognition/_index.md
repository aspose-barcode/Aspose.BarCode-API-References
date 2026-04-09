---
title: com.aspose.barcode.barcoderecognition
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 此包包含用于 1D/2D 条码识别的工具。
type: docs
weight: 11
url: /zh/androidjava/com.aspose.barcode.barcoderecognition/
---

此包包含用于 1D/2D 条码识别的工具。


## 类

| 类 | 描述 |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost 解码参数。 |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | 存储 Aztec 识别条码的特殊数据 |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | 包含识别置信度水平 |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | 存储已识别条码的扩展参数 |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader 封装可能包含一个或多个条码的图像，然后可以执行 ReadBarCodes 操作来检测条码。 |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | BarCodeReader 抛出的通用异常，继承自 BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | 表示已识别条码的区域和条码角度 |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | 存储已识别条码数据，如 SingleDecodeType 类型、string codetext、BarCodeRegionParameters 区域以及其他参数 |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | 主要的 BarCode 解码参数。 |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | 条码检测器设置。 |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | MultiDecodeType 和 SingleDecodeType 的基类。 |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | 用于存储已识别条码扩展参数的基础类 |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | 存储已识别条码的 Codabar 附加信息 |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | 包含 Code128 类型条码的子类型数据 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | 存储已识别的 Code128 条形码的特殊数据 |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | 包含 Code128 子集的类型 |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | 存储已识别的条形码的 DataBar 附加信息 BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | 存储已识别的 DataMatrix 条形码的特殊数据 |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | 指定要读取的条形码类型。 |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | 存储已识别的 DotCode 条形码的特殊数据 |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | 存储已识别的  **GS1 Composite Bar**  条形码的特殊数据 |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | 存储已识别的条形码的 MaxiCode 附加信息 |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | 复合解码类型。 |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) | 复合解码类型。 |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | 存储已识别的 1D 条形码的特殊数据，例如分离的代码文本和校验和 |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | 存储已识别的条形码的 MacroPdf417 元数据 |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings 允许通过多线程提升性能来识别条形码 |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | 存储已识别的条形码的 QR Structured Append 信息 |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | 存储一组四个 Point，表示一个 Quadrangle 区域。 |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings 允许手动配置识别质量和速度。 |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | 表示在使用 BarCodeReader 进行识别时因超时而抛出的识别中止异常。 |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | 单一解码类型。 |
| [TextEncodingDetection](../com.aspose.barcode.barcoderecognition/textencodingdetection) |  |

## 接口

| 接口 | 描述 |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | 用于 AustraliaPost 符号系统的客户信息字段解码的公共接口。 |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | 定义 AustralianPost 条形码的客户信息的解释类型（C\_TABLE 或 N\_TABLE）。 |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | 指定缩放图像的大小 |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
