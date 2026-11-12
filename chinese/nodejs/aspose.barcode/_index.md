---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "aspose.barcode 命名空间提供用于在 Node.js via Java 中创建、定制和解码各种条码类型的类和枚举。"
type: docs
weight: 10
url: /zh/nodejs/aspose.barcode/
---
使用这些类型来配置条码生成设置，例如地址格式、地区规范以及 Aztec 等符号的高级参数。该命名空间包括用于构建扩展代码文本和处理专用邮政标准的帮助程序。

## 类

| 类 | 描述 |
| --- | --- |
| [Address](./address/) | 债权人或债务人的地址。您可以设置街道、门牌号、邮政编码和城镇（结构化地址类型） |
| [AlternativeScheme](./alternativescheme/) | 替代付款方案说明 |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost 解码参数。包含影响 AustraliaPost 符号识别数据的参数 |
| [AustralianPostParameters](./australianpostparameters/) | AustralianPost 条码参数。 |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Aztec 条码的扩展代码文本生成器，用于 AztecEncodeMode 的 ExtendedCodetext 模式，使用 TwoDDisplayText 属性 |
| [AztecExtendedParameters](./aztecextendedparameters/) | 存储 Aztec 识别条码的特殊数据。本示例展示如何获取 Aztec 原始值 let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Aztec 参数。 |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | 存储已识别条码的扩展参数 |
| [BarCodeReader](./barcodereader/) | BarCodeReader 封装可能包含一个或多个条码的图像，然后可以执行 ReadBarCodes 操作 |
| [BarCodeRegionParameters](./barcoderegionparameters/) | 表示已识别条码的区域和条码角度 |
| [BarCodeResult](./barcoderesult/) | 存储已识别条码的数据，如 SingleDecodeType 类型、`string` 代码文本、BarCodeRegionParameters 区域以及其他 |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator 用于后端条码图像生成。支持的符号：1D：Codabar、Code11、Code128、Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | 条形码生成参数。 |
| [BarcodeSettings](./barcodesettings/) | 主要的 BarCode 解码参数。包含对识别数据产生影响的参数。 |
| [BaseGenerationParameters](./basegenerationparameters/) | 条形码图像生成参数。 |
| [BorderParameters](./borderparameters/) | 条形码图像边框参数 |
| [CMYKColor](./cmykcolor/) | 用于 CMYK 颜色的类。空实例表示不使用 CMYK，使用默认的 RGB 颜色。 |
| [CaptionParameters](./captionparameters/) | 标题参数。 |
| [CodabarExtendedParameters](./codabarextendedparameters/) | 存储已识别条形码的 Codabar 附加信息 |
| [CodabarParameters](./codabarparameters/) | Codabar 参数。 |
| [CodablockParameters](./codablockparameters/) | Codablock 参数。 |
| [Code128DataPortion](./code128dataportion/) | 包含 Code128 类型条形码的子类型数据 |
| [Code128ExtendedParameters](./code128extendedparameters/) | 存储已识别 Code128 条形码的特殊数据。表示已识别条形码的区域和条形码角度 |
| [Code128Parameters](./code128parameters/) | Code128 参数。 |
| [Code16KParameters](./code16kparameters/) | Code16K 参数。 |
| [CodetextParameters](./codetextparameters/) | Codetext 参数。 |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | 用于后端复杂条形码（例如 SwissQR）图像生成的 ComplexBarcodeGenerator。 |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader 将 codetext 解码为指定的复杂条形码类型。 |
| [CouponParameters](./couponparameters/) | 优惠券参数。用于 UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon。 |
| [DataBarExtendedParameters](./databarextendedparameters/) | 存储已识别条形码的 DataBar 附加信息 |
| [DataBarParameters](./databarparameters/) | Databar 参数。 |
| [DataElement](./dataelement/) | 表示文档中使用的特定司法管辖区数据字段，例如 ElementID = "ZVA" 且 Value = "01"。 |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | 用于 DataMatrixEncodeMode 的 ExtendedCodetext 模式的 2D DataMatrix 条形码的扩展 codetext 生成器 //Extended code |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | 存储已识别 DataMatrix 条形码的特殊数据。此示例展示如何获取 DataMatrix 原始值 let generator = |
| [DataMatrixParameters](./datamatrixparameters/) | DataMatrix 参数。 |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | 用于 DotCodeEncodeMode 的 ExtendedCodetext 模式的 2D DotCode 条形码的扩展 codetext 生成器 |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | 存储已识别 DotCode 条形码的特殊数据。此示例展示如何获取 DotCode 原始值 |
| [DotCodeParameters](./dotcodeparameters/) | DotCode 参数。 |
| [ExtCodetextBuilder](./extcodetextbuilder/) | 用于自动生成扩展码文本模式的帮助类。 |
| [FontUnit](./fontunit/) | 定义文本的特定格式，包括字体、大小和样式属性，其中大小在 Unit 值属性中。 |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | 存储已识别的 `GS1 Composite Bar ` 条形码的特殊数据。 |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | GS1 Composite 条形码参数。 |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | 用于对嵌入 HIBC LIC 代码中的文本进行编码和解码的类，该代码存储主数据和次要数据。此示例。 |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | 用于对嵌入 HIBC LIC 代码中的文本进行编码和解码的基类。此示例展示了如何解码原始 HIBC LI。 |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | 用于对嵌入 HIBC LIC 代码中的文本进行编码和解码的类，该代码存储主数据。此示例展示了如何。 |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | 用于对嵌入 HIBC LIC 代码中的文本进行编码和解码的类，该代码存储次要数据。 |
| [HIBCPASCodetext](./hibcpascodetext/) | 用于对嵌入 HIBC PAS 代码中的文本进行编码和解码的类。 |
| [HIBCPASRecord](./hibcpasrecord/) | 用于存储 HIBC PAS 记录的类。 |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | 用于 Han Xin 码的扩展码文本生成器，适用于 HanXinEncodeMode 的扩展模式 //Extended codetext mode //create cod。 |
| [HanXinParameters](./hanxinparameters/) | Han Xin 参数。 |
| [HslaColor](./hslacolor/) | 用于表示 HSLA 颜色（色相、饱和度、亮度、透明度）的类。 |
| [IComplexCodetext](./icomplexcodetext/) | 用于与 ComplexBarcodeGenerator 一起使用的复杂码文本接口。 |
| [ITFParameters](./itfparameters/) | ITF 参数。 |
| [ImageParameters](./imageparameters/) | 图像参数。 |
| [License](./license/) | 提供对组件授权的方法。 |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | 用于对嵌入 Royal Mail 2D Mailmark 代码中的文本进行编码和解码的类。 |
| [MailmarkCodetext](./mailmarkcodetext/) | 用于对嵌入 4 状态 Royal Mailmark 代码中的文本进行编码和解码的类。 |
| [MandatoryFields](./mandatoryfields/) | 卡片的必填元素（字段）。 |
| [MaxiCodeCodetext](./maxicodecodetext/) | 用于对嵌入 MaxiCode 代码中的文本进行编码和解码的基类。此示例展示了如何解码原始 MaxiCod。 |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | 用于对嵌入 MaxiCode 代码中模式 2 的文本进行编码和解码的类。 |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | 用于对嵌入 MaxiCode 代码中模式 3 的文本进行编码和解码的类。此示例展示了如何编码和。 |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | 用于 MaxiCode 条码的扩展码文本生成器，适用于 MaxiCodeEncodeMode 的 ExtendedCodetext 模式，使用 TwoDDisplayText pr。 |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | 存储已识别条形码的 MaxiCode 附加信息 |
| [MaxiCodeParameters](./maxicodeparameters/) | MaxiCode 参数。 |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | 用于对模式 4、5 和 6 的 MaxiCode 编码文本进行编码和解码的类。 |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | 用于对模式 4、5 和 6 的 MaxiCode 编码文本进行编码和解码的类。 |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | 用于对 MaxiCode 条形码的标准第二消息进行编码和解码的类。 |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | 用于对 MaxiCode 条形码的标准第二消息进行编码和解码的类。 |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | 用于对模式 2 和 3 的 MaxiCode 代码中嵌入的文本进行编码和解码的基类。 |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | 用于对 MaxiCode 条形码的结构化第二消息进行编码和解码的类。 |
| [OneDExtendedParameters](./onedextendedparameters/) | 存储已识别 1D 条形码的特殊数据，如独立的编码文本和校验和 |
| [OptionalFields](./optionalfields/) | 卡片的可选元素（字段） |
| [Padding](./padding/) | 填充参数。 |
| [PatchCodeParameters](./patchcodeparameters/) | PatchCode 参数。 |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | 存储已识别条形码的 MacroPdf417 元数据 |
| [Pdf417Parameters](./pdf417parameters/) | PDF417 参数。包含 PDF417、MacroPDF417、MicroPDF417 和 GS1MicroPdf417 参数。MacroPDF417 需要两个 fie |
| [PdfParameters](./pdfparameters/) | PDF 参数包装器。期望底层提供相应 getter/setter 方法的 `mwObject` 实例 |
| [PostalParameters](./postalparameters/) | 邮政参数。用于 Postnet、Planet。 |
| [PrimaryData](./primarydata/) | 用于存储 HIBC LIC 主数据的类。 |
| [QRExtendedParameters](./qrextendedparameters/) | 存储已识别条形码的 QR 结构化追加信息 |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | 用于 QREncodeMode 的 ExtendedCodetext 模式的 2D QR 条形码扩展编码文本生成器，使用 B 的 Display2DText 属性 |
| [QrParameters](./qrparameters/) | QR 参数。 |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | QR 结构化追加参数。 |
| [Quadrangle](./quadrangle/) | 存储一组由四个点组成的表示四边形区域的点集合。 |
| [QualitySettings](./qualitysettings/) | QualitySettings 允许手动配置识别质量和速度。您可以通过 em 快速设置 QualitySettings |
| [RecognitionAbortedException](./recognitionabortedexception/) | 表示在使用 BarCodeReader 进行识别时超时导致抛出的识别中止异常。 |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | 用于存储 HIBC LIC 次要和附加数据的类。 |
| [SubfileProperties](./subfileproperties/) | USA DL 子文件属性、偏移量和长度会自动设置。 |
| [SupplementParameters](./supplementparameters/) | 补充参数。用于 Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN。 |
| [SvgParameters](./svgparameters/) | SVG 参数。 |
| [SwissQRBill](./swissqrbill/) | SwissQR 账单数据 |
| [SwissQRCodetext](./swissqrcodetext/) | 用于对嵌入在 SwissQR 代码中的文本进行编码和解码的类。 |
| [USADriveIdCodetext](./usadriveidcodetext/) | 用于对嵌入在美国驾驶执照 PDF417 代码中的文本进行编码和解码的类。 |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | 用于美国驾驶执照特定司法辖区字段的类 |
| [Unit](./unit/) | 指定不同单位（像素、英寸等）中的尺寸值。 |
