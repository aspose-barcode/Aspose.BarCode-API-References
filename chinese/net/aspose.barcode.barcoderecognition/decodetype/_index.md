---
title: DecodeType
second_title: Aspose.BarCode for .NET API 参考
description: 指定要读取的条形码类型
type: docs
weight: 190
url: /zh/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

指定要读取的条形码类型。

```csharp
public static class DecodeType
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray) { get; } | 获取表示 AllSupportedTypes 的数组 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames)() | 检索解码类型名称的数组。 |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d)(BaseDecodeType) | 确定是否指定[`BaseDecodeType`](../basedecodetype)包含任何一维条码 symbology |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d)(BaseDecodeType) | 确定是否指定[`BaseDecodeType`](../basedecodetype)包含任何二维条码 symbology |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal)(BaseDecodeType) | 确定是否指定[`BaseDecodeType`](../basedecodetype)包含任何邮政条码 symbology |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse)(string, out SingleDecodeType) | 将 SingleDecodeType 的字符串表示形式转换为其实例。 返回值指示转换是成功还是失败。 |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets)(params BaseDecodeType[]) | 按barcodeTypes指定扫描集 |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse)(string, out MultyDecodeType) | 将 MultyDecodeType 的字符串表示形式转换为其实例。 返回值指示转换是成功还是失败。 |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse_1)(string, out SingleDecodeType) | 将 SingleDecodeType 的字符串表示形式转换为其实例。 返回值指示转换是成功还是失败。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes) | 指定将使用所有可用符号检查数据 |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel) | 指定数据应该被解码 **澳大利亚邮政国内电子包裹条形码**条码规格 |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost) | 指定数据应该被解码 **澳大利亚邮政**条码规格 |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec) | 指定数据应该被解码 **阿兹台克人**条码规格 |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar) | 指定数据应该被解码 **科达巴**条码规格 |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf) | 指定数据应该被解码 **CodablockF**条码规格 |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11) | 指定数据应该被解码 **代码 11**条码规格 |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128) | 指定数据应该被解码 **代码 128**条码规格 |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k) | 指定数据应该被解码 **SCode16K**条码规格 |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32) | 指定数据应该被解码 **代码 32**空白规范 |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended) | 指定数据应该被解码 **扩展代码 39**条码规格 |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard) | 指定数据应该被解码 **标准代码 39**条码规格 |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended) | 指定数据应该被解码 **扩展代码 93**条码规格 |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard) | 指定数据应该被解码 **标准代码 93**条码规格 |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417) | 指定数据应该被解码 **压缩PDF417**(pdf417截断) 条码规范 |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded) | 指定数据应该被解码 **GS1 数据栏展开**条码规格 |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked) | 指定数据应该被解码 **GS1 Databar 扩展堆叠**条码规格 |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited) | 指定数据应该被解码 **GS1 Databar 有限**条码规格 |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional) | 指定数据应该被解码 **GS1 Databar 全向**条码规格 |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked) | 指定数据应该被解码 **GS1 Databar 堆叠**条码规格 |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional) | 指定数据应该被解码 **GS1 Databar 堆叠式全方位**条码规格 |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated) | 指定数据应该被解码 **GS1 数据栏被截断**条码规格 |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5) | 指定数据应该被解码 **数据逻辑 2 of 5**空白规范 |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix) | 指定数据应该被解码 **数据矩阵**条码符号 |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode) | 指定数据应该被解码 **德国邮政识别码**条码规格 |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode) | 指定数据应该被解码 **德国邮政 Leit 代码**条码规格 |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode) | 指定数据应该被解码 **点码**空白规范 |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix) | 指定数据应该被解码 **点码**空白规范 |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13) | 指定数据应该被解码 **EAN-13**条码规格 |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14) | 指定数据应该被解码 **EAN14**条码规格 |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8) | 指定数据应该被解码 **EAN-8**条码规格 |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128) | 指定数据应该被解码 **GS1 代码 128**条码规格 |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix) | 指定数据应该被解码 **GS1DataMatrix**条码符号 |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr) | 指定数据应该被解码 **GS1 二维码**条码规格 |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5) | 指定数据应该被解码 **国际航空运输协会 2 个，共 5 个**条码规范。 IATA（国际航空运输协会）使用此条码管理空运货物。 |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5) | 指定数据应该被解码 **交错的 2 的 5**条码规格 |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn) | 指定数据应该被解码 **国际标准书号**条码规格 |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn) | 指定数据应该被解码 **ISMN**条码规格 |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn) | 指定数据应该被解码 **ISSN**条码规格 |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25) | 指定数据应该被解码 **意大利邮政 25**条码规格 |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14) | 指定数据应该被解码 **ITF14**条码规格 |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6) | 指定数据应该被解码 **ITF6**条码规格 |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417) | 指定数据应该被解码 **宏PDF417**条码规格 |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark) | 指定数据应该被解码 **皇家邮政邮戳**条码规范. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5) | 指定数据应该被解码 **矩阵 2 的 5**条码规格 |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode) | 指定数据应该被解码 **大码**条码规格 |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b) | 指定数据应该被解码 **MICR E-13B**空白规范 |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417) | 指定数据应该被解码 **微型PDF417**条码规格 |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr) | 指定数据应该被解码 **微二维码**条码规格 |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes) | 指定将使用最常用的符号检查数据 |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi) | 指定数据应该被解码 **微星普莱西**条码规格 |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none) | 未指定的解码类型。 |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode) | 指定数据应使用 USPS 解码 **一码**条码规格 |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc) | 指定数据应该被解码 **OPC**条码规格 |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode) | 指定数据应该被解码 **补丁代码**条码规范。条码符号用于自动扫描 |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417) | 指定数据应该被解码 **PDF417**条码符号 |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode) | 指定数据应该被解码 **药典**条码。此符号系统也称为制药二进制代码 |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet) | 指定数据应该被解码 **行星**条码规格 |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes) | 指定将使用所有 **1.5D邮政**条形码符号，如 **Planet, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet) | 指定数据应该被解码 **邮政网**条码规格 |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn) | 指定数据应该被解码 **PZN**条码规范。此符号系统也称为 Pharma Zentral Nummer |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr) | 指定数据应该被解码 **二维码**条码规格 |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc) | 指定数据应该被解码 **RM4SCC**条码规范。 RM4SCC（皇家邮政 4 州客户代码）用于英国的自动邮件分类流程。 |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14) | 指定数据应该被解码 **SCC14**条码规格 |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18) | 指定数据应该被解码 **SSCC18**条码规格 |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5) | 指定数据应该被解码 **标准 2 的 5**条码规格 |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement) | 指定数据应该被解码 **补充（EAN2，EAN5）**条码规格 |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel) | 指定数据应该被解码 **瑞士邮政包裹条码**条码规格 |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d) | 指定将使用所有 **一维**条码符号 |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d) | 指定将使用所有 **二维**条码符号 |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca) | 指定数据应该被解码 **UPC-A**条码规格 |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce) | 指定数据应该被解码 **UPC-E**条码规格 |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin) | 指定数据应该被解码 **车辆识别号** （车辆识别号）条码规范 |

### 例子

此示例展示了如何检测 Code39 和 Code128 条码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 也可以看看

* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* 部件 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
