---
title: "类 DecodeType"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.DecodeType 类。 指定要读取的条形码类型"
type: docs
weight: 230
url: /zh/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

指定要读取的条码类型。

```csharp
public static class DecodeType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | 获取表示 AllSupportedTypes 的数组 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | 检索解码类型名称的数组。 |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | 确定指定的 [`BaseDecodeType`](../basedecodetype/) 是否包含任何 1D 条码符号 |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | 确定指定的 [`BaseDecodeType`](../basedecodetype/) 是否包含任何 2D 条码符号 |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | 确定指定的 [`BaseDecodeType`](../basedecodetype/) 是否包含任何邮政条码符号 |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | 将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | 通过 barcodeTypes 指定扫描集 |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultiDecodeType) | 将 MultiDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | 将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | 指定将使用所有可用的符号检查数据 |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | 指定应使用 **Australian Post Domestic eParcel Barcode** 条码规范对数据进行解码 |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | 指定应使用 **Australia Post** 条码规范对数据进行解码 |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | 指定应使用 **Aztec** 条码规范对数据进行解码 |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | 指定应使用 **CODABAR** 条码规范对数据进行解码 |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | 指定应使用 **CodablockF** 条码规范对数据进行解码 |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | 指定应使用 **CODE 11** 条码规范对数据进行解码 |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | 指定应使用 **CODE 128** 条码规范对数据进行解码 |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | 指定应使用 **SCode16K** 条码规范对数据进行解码 |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | 指定应使用 **Code32** 条码规范对数据进行解码 |
| static readonly [Code39](../../aspose.barcode.barcoderecognition/decodetype/code39/) | 指定应使用 **Code 39** 基本字符集条码规范进行解码：ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.barcoderecognition/decodetype/code39fullascii/) | 指定应使用 **Code 39** 完整 ASCII 字符集条码规范进行解码：ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.barcoderecognition/decodetype/code93/) | 指定数据应使用 **CODE 93** 条形码规范进行解码 |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | 指定数据应使用 **CompactPdf417** (Pdf417Truncated) 条形码规范进行解码 |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | 指定数据应使用 **GS1 Databar expanded** 条形码规范进行解码 |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | 指定数据应使用 **GS1 Databar expanded stacked** 条形码规范进行解码 |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | 指定数据应使用 **GS1 Databar limited** 条形码规范进行解码 |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | 指定数据应使用 **GS1 Databar omni-directional** 条形码规范进行解码 |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | 指定数据应使用 **GS1 Databar stacked** 条形码规范进行解码 |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | 指定数据应使用 **GS1 Databar stacked omni-directional** 条形码规范进行解码 |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | 指定数据应使用 **GS1 Databar truncated** 条形码规范进行解码 |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | 指定数据应使用 **DataLogic 2 of 5** 条形码规范进行解码 |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | 指定数据应使用 **DataMatrix** 条形码符号进行解码 |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | 指定数据应使用 **DeutschePost Ident code** 条形码规范进行解码 |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | 指定数据应使用 **DeutschePost Leit code** 条形码规范进行解码 |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | 指定数据应使用 **DotCode** 条形码规范进行解码 |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | 指定数据应使用 **DotCode** 条形码规范进行解码 |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | 指定数据应使用 **EAN-13** 条形码规范进行解码 |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | 指定数据应使用 **EAN14** 条形码规范进行解码 |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | 指定数据应使用 **EAN-8** 条形码规范进行解码 |
| static readonly [GS1Aztec](../../aspose.barcode.barcoderecognition/decodetype/gs1aztec/) | 指定数据应使用 **GS1 Aztec** 条形码规范进行解码 |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | 指定数据应使用 **GS1 CODE 128** 条形码规范进行解码 |
| static readonly [GS1CompositeBar](../../aspose.barcode.barcoderecognition/decodetype/gs1compositebar/) | 指定数据应使用 **GS1 Composite Bar** 条形码规范进行解码 |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | 指定数据应使用 **GS1DataMatrix** 条形码符号进行解码 |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | 指定数据应使用 **GS1 DotCode** 条形码规范进行解码 |
| static readonly [GS1HanXin](../../aspose.barcode.barcoderecognition/decodetype/gs1hanxin/) | 指定数据应使用 **GS1 Han Xin Code** 条形码规范进行解码 |
| static readonly [GS1MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/gs1micropdf417/) | 指定数据应使用 **MicroPdf417** 条形码规范进行解码 |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | 指定数据应使用 **GS1 QR** 条形码规范进行解码 |
| static readonly [HanXin](../../aspose.barcode.barcoderecognition/decodetype/hanxin/) | 指定数据应使用 **Han Xin Code** 条形码规范进行解码 |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | 指定数据应使用 **HIBC LIC Aztec** 条形码规范进行解码 |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | 指定数据应使用 **HIBC PAS Aztec** 条形码规范进行解码 |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | 指定数据应使用 **HIBC LIC Code128** 条形码规范进行解码 |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | 指定数据应使用 **HIBC PAS Code128** 条形码规范进行解码 |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | 指定数据应使用 **HIBC LIC Code39** 条形码规范进行解码 |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | 指定数据应使用 **HIBC PAS Code39** 条形码规范进行解码 |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | 指定数据应使用 **HIBC LIC DataMatrix** 条形码规范进行解码 |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | 指定数据应使用 **HIBC PAS DataMatrix** 条形码规范进行解码 |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | 指定数据应使用 **HIBC LIC QR** 条形码规范进行解码 |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | 指定数据应使用 **HIBC PAS QR** 条形码规范进行解码 |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | 指定数据应使用 **IATA 2 of 5** 条形码规范进行解码。IATA（International Air Transport Association）使用此条形码来管理航空货物。 |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | 指定数据应使用 **INTERLEAVED 2 of 5** 条形码规范进行解码 |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | 指定数据应使用 **ISBN** 条形码规范进行解码 |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | 指定数据应使用 **ISMN** 条形码规范进行解码 |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | 指定数据应使用 **ISSN** 条形码规范进行解码 |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | 指定数据应使用 **Italian Post 25** 条形码规范进行解码 |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | 指定数据应使用 **ITF14** 条形码规范进行解码 |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | 指定数据应使用 **ITF6** 条形码规范进行解码 |
| static readonly [JapanPost](../../aspose.barcode.barcoderecognition/decodetype/japanpost/) | 指定数据应使用 **Japan Post** 条形码规范进行解码 |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | 指定数据应使用 **MacroPdf417** 条形码规范进行解码 |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | 指定数据应使用 **Royal Mail Mailmark** 条形码规范进行解码。 |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | 指定数据应使用 **Matrix 2 of 5** 条形码规范进行解码 |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | 指定数据应使用 **MaxiCode** 条形码规范进行解码 |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | 指定数据应使用 **MICR E-13B** 条形码规范进行解码 |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | 指定数据应使用 **MicroPdf417** 条形码规范进行解码 |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | 指定应使用 **MicroQR Code** 条码规范对数据进行解码。 |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | 指定将使用最常用的符号系统检查数据。 |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | 指定应使用 **MSI Plessey** 条码规范对数据进行解码。 |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | 未指定的解码类型。 |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | 指定应使用 USPS **OneCode** 条码规范对数据进行解码。 |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | 指定应使用 **OPC** 条码规范对数据进行解码。 |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | 指定应使用 **Patch code** 条码规范对数据进行解码。条码符号系统用于自动扫描。 |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | 指定应使用 **Pdf417** 条码符号系统对数据进行解码。 |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | 指定应使用 **Pharmacode** 条码对数据进行解码。此符号系统也称为药品二进制码。 |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | 指定应使用 **Planet** 条码规范对数据进行解码。 |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | 指定将使用所有 **1.5D Postal** 条码符号系统检查数据，例如 **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX**。 |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | 指定应使用 **Postnet** 条码规范对数据进行解码。 |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | 指定应使用 **PZN** 条码规范对数据进行解码。此符号系统也称为 Pharma Zentral Nummer。支持 PZN7 和 PZN8。 |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | 指定应使用 **QR Code** 条码规范对数据进行解码。 |
| static readonly [RectMicroQR](../../aspose.barcode.barcoderecognition/decodetype/rectmicroqr/) | 指定应使用 **RectMicroQR (rMQR) Code** 条码规范对数据进行解码。 |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | 指定应使用 **RM4SCC** 条码规范对数据进行解码。RM4SCC（Royal Mail 4-state Customer Code）用于英国的自动邮件分拣过程。 |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | 指定应使用 **SCC14** 条码规范对数据进行解码。 |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | 指定应使用 **SSCC18** 条码规范对数据进行解码。 |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | 指定应使用 **Standard 2 of 5** 条码规范对数据进行解码。 |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | 指定应使用 **Supplement(EAN2, EAN5)** 条码规范对数据进行解码。 |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | 指定应使用 **Swiss Post Parcel Barcode** 条码规范对数据进行解码。 |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | 指定将使用所有 **1D** 条码符号系统检查数据。 |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | 指定将使用所有 **2D** 条码符号系统检查数据。 |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | 指定应使用 **UPC-A** 条码规范对数据进行解码。 |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | 指定应使用 **UPC-E** 条码规范对数据进行解码。 |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | 指定应使用 **VIN**（车辆识别号码）条码规范对数据进行解码 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


