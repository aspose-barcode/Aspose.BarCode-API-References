---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType 类"
linktitle: "DecodeType"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType 类。指定在 C++ 中读取的条码类型。"
type: docs
weight: 1600
url: /zh/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


指定要读取的条码类型。

```cpp
class DecodeType
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | 获取表示 AllSupportedTypes 的数组 |
| static [GetNames](./getnames/)() | 检索解码类型名称的数组。 |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | 确定指定的 [BaseDecodeType](../basedecodetype/) 是否包含任何 1D 条码符号 |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | 确定指定的 [BaseDecodeType](../basedecodetype/) 是否包含任何 2D 条码符号 |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | 确定指定的 [BaseDecodeType](../basedecodetype/) 是否包含任何邮政条码符号 |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | 将 [SingleDecodeType](../singledecodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 通过 barcodeTypes 指定扫描集 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | 将 [SingleDecodeType](../singledecodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | 将 [MultiDecodeType](../multidecodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | 指定将使用所有可用的符号检查数据 |
| static [AustralianPosteParcel](./australianposteparcel/) | 指定应使用 **Australian Post Domestic eParcel Barcode** 条码规范对数据进行解码 |
| static [AustraliaPost](./australiapost/) | 指定应使用 **Australia Post** 条码规范对数据进行解码 |
| static [Aztec](./aztec/) | 指定应使用 **Aztec** 条码规范对数据进行解码 |
| static [Codabar](./codabar/) | 指定应使用 **CODABAR** 条码规范对数据进行解码 |
| static [CodablockF](./codablockf/) | 指定应使用 **CodablockF** 条码规范对数据进行解码 |
| static [Code11](./code11/) | 指定应使用 **CODE 11** 条码规范对数据进行解码 |
| static [Code128](./code128/) | 指定应使用 **CODE 128** 条码规范对数据进行解码 |
| static [Code16K](./code16k/) | 指定应使用 **SCode16K** 条码规范对数据进行解码 |
| static [Code32](./code32/) | 指定应使用 **Code32** 条码规范对数据进行解码 |
| static [Code39](./code39/) | 指定应使用 **Code 39** 基本字符集条码规范：ISO/IEC 16388 对数据进行解码 |
| static [Code39FullASCII](./code39fullascii/) | 指定应使用 **Code 39** 完整 ASCII 字符集条码规范：ISO/IEC 16388 对数据进行解码 |
| static [Code93](./code93/) | 指定应使用 **CODE 93** 条码规范对数据进行解码 |
| static [CompactPdf417](./compactpdf417/) | 指定应使用 **CompactPdf417** (Pdf417Truncated) 条码规范对数据进行解码 |
| static [DatabarExpanded](./databarexpanded/) | 指定应使用 **GS1 Databar expanded** 条码规范对数据进行解码 |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | 指定应使用 **GS1 Databar expanded stacked** 条码规范对数据进行解码 |
| static [DatabarLimited](./databarlimited/) | 指定应使用 **GS1 Databar limited** 条码规范对数据进行解码 |
| static [DatabarOmniDirectional](./databaromnidirectional/) | 指定应使用 **GS1 Databar omni-directional** 条码规范对数据进行解码 |
| static [DatabarStacked](./databarstacked/) | 指定应使用 **GS1 Databar stacked** 条码规范对数据进行解码 |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | 指定应使用 **GS1 Databar stacked omni-directional** 条码规范对数据进行解码 |
| static [DatabarTruncated](./databartruncated/) | 指定应使用 **GS1 Databar truncated** 条码规范对数据进行解码 |
| static [DataLogic2of5](./datalogic2of5/) | 指定应使用 **DataLogic 2 of 5** 条形码规范对数据进行解码 |
| static [DataMatrix](./datamatrix/) | 指定应使用 **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** 条形码符号对数据进行解码 |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | 指定应使用 **DeutschePost Ident code** 条形码规范对数据进行解码 |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | 指定应使用 **DeutschePost Leit code** 条形码规范对数据进行解码 |
| static [DotCode](./dotcode/) | 指定应使用 **DotCode** 条形码规范对数据进行解码 |
| static [DutchKIX](./dutchkix/) | 指定应使用 **DotCode** 条形码规范对数据进行解码 |
| static [EAN13](./ean13/) | 指定应使用 **EAN-13** 条形码规范对数据进行解码 |
| static [EAN14](./ean14/) | 指定应使用 **EAN14** 条形码规范对数据进行解码 |
| static [EAN8](./ean8/) | 指定应使用 **EAN-8** 条形码规范对数据进行解码 |
| static [GS1Aztec](./gs1aztec/) | 指定应使用 **GS1 Aztec** 条形码规范对数据进行解码 |
| static [GS1Code128](./gs1code128/) | 指定应使用 **GS1 CODE 128** 条形码规范对数据进行解码 |
| static [GS1CompositeBar](./gs1compositebar/) | 指定应使用 **GS1 Composite Bar** 条形码规范对数据进行解码 |
| static [GS1DataMatrix](./gs1datamatrix/) | 指定应使用 **GS1DataMatrix** 条形码符号对数据进行解码 |
| static [GS1DotCode](./gs1dotcode/) | 指定应使用 **GS1 DotCode** 条形码规范对数据进行解码 |
| static [GS1HanXin](./gs1hanxin/) | 指定应使用 **GS1 Han Xin Code** 条形码规范对数据进行解码 |
| static [GS1MicroPdf417](./gs1micropdf417/) | 指定应使用 **MicroPdf417** 条形码规范对数据进行解码 |
| static [GS1QR](./gs1qr/) | 指定应使用 **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** 条形码规范对数据进行解码 |
| static [HanXin](./hanxin/) | 指定应使用 **Han Xin Code** 条形码规范对数据进行解码 |
| static [HIBCAztecLIC](./hibcazteclic/) | 指定应使用 **HIBC LIC Aztec** 条形码规范对数据进行解码 |
| static [HIBCAztecPAS](./hibcaztecpas/) | 指定应使用 **HIBC PAS Aztec** 条形码规范对数据进行解码 |
| static [HIBCCode128LIC](./hibccode128lic/) | 指定应使用 **HIBC LIC Code128** 条形码规范对数据进行解码 |
| static [HIBCCode128PAS](./hibccode128pas/) | 指定应使用 **HIBC PAS Code128** 条形码规范对数据进行解码 |
| static [HIBCCode39LIC](./hibccode39lic/) | 指定应使用 **HIBC LIC Code39** 条形码规范对数据进行解码 |
| static [HIBCCode39PAS](./hibccode39pas/) | 指定应使用 **HIBC PAS Code39** 条形码规范对数据进行解码 |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | 指定应使用 **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** 条形码规范对数据进行解码 |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | 指定应使用 **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** 条形码规范对数据进行解码 |
| static [HIBCQRLIC](./hibcqrlic/) | 指定应使用 **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** 条形码规范对数据进行解码 |
| static [HIBCQRPAS](./hibcqrpas/) | 指定应使用 **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** 条形码规范对数据进行解码 |
| static [IATA2of5](./iata2of5/) | 指定应使用 **IATA 2 of 5** 条形码规范对数据进行解码。IATA（国际航空运输协会）使用此条形码来管理航空货物。 |
| static [Interleaved2of5](./interleaved2of5/) | 指定应使用 **INTERLEAVED 2 of 5** 条形码规范对数据进行解码 |
| static [ISBN](./isbn/) | 指定应使用 **ISBN** 条形码规范对数据进行解码 |
| static [ISMN](./ismn/) | 指定应使用 **ISMN** 条形码规范对数据进行解码 |
| static [ISSN](./issn/) | 指定应使用 **ISSN** 条形码规范对数据进行解码 |
| static [ItalianPost25](./italianpost25/) | 指定应使用 **Italian Post 25** 条形码规范对数据进行解码 |
| static [ITF14](./itf14/) | 指定应使用 **ITF14** 条形码规范对数据进行解码 |
| static [ITF6](./itf6/) | 指定应使用 **ITF6** 条形码规范对数据进行解码 |
| static [JapanPost](./japanpost/) | 指定应使用 **Japan Post** 条形码规范对数据进行解码 |
| static [MacroPdf417](./macropdf417/) | 指定应使用 **MacroPdf417** 条形码规范对数据进行解码 |
| static [Mailmark](./mailmark/) | 指定应使用 **Royal Mail Mailmark** 条形码规范对数据进行解码。 |
| static [Matrix2of5](./matrix2of5/) | 指定应使用 **Matrix 2 of 5** 条形码规范对数据进行解码 |
| static [MaxiCode](./maxicode/) | 指定应使用 **MaxiCode** 条形码规范对数据进行解码 |
| static [MicrE13B](./micre13b/) | 指定应使用 **MICR E-13B** 条形码规范对数据进行解码 |
| static [MicroPdf417](./micropdf417/) | 指定应使用 **MicroPdf417** 条形码规范对数据进行解码 |
| static [MicroQR](./microqr/) | 指定应使用 **MicroQR Code** 条形码规范对数据进行解码 |
| static [MostCommonTypes](./mostcommontypes/) | 指定将使用最常用的符号对数据进行检查 |
| static [MSI](./msi/) | 指定应使用 **MSI Plessey** 条形码规范对数据进行解码 |
| static [None](./none/) | 未指定的解码类型。 |
| static [OneCode](./onecode/) | 指定应使用 USPS **OneCode** 条形码规范对数据进行解码 |
| static [OPC](./opc/) | 指定应使用 **OPC** 条形码规范对数据进行解码 |
| static [PatchCode](./patchcode/) | 指定应使用 **Patch code** 条形码规范对数据进行解码。条形码符号用于自动扫描 |
| static [Pdf417](./pdf417/) | 指定应使用 **Pdf417** 条形码符号对数据进行解码 |
| static [Pharmacode](./pharmacode/) | 指定应使用 **Pharmacode** 条形码对数据进行解码。该符号也称为药品二进制码 |
| static [Planet](./planet/) | 指定应使用 **Planet** 条码规范进行解码 |
| static [PostalTypes](./postaltypes/) | 指定将使用所有 **1.5D Postal** 条码符号进行检查，例如 **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** |
| static [Postnet](./postnet/) | 指定应使用 **Postnet** 条码规范进行解码 |
| static [PZN](./pzn/) | 指定应使用 **PZN** 条码规范进行解码。该符号也称为 Pharma Zentral Nummer。支持 PZN7 和 PZN8。 |
| static [QR](./qr/) | 指定应使用 **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** 条码规范进行解码 |
| static [RectMicroQR](./rectmicroqr/) | 指定应使用 **RectMicroQR (rMQR) Code** 条码规范进行解码 |
| static [RM4SCC](./rm4scc/) | 指定应使用 **RM4SCC** 条码规范进行解码。RM4SCC（Royal Mail 4-state Customer Code）用于英国的自动邮件分拣过程。 |
| static [SCC14](./scc14/) | 指定应使用 **SCC14** 条码规范进行解码 |
| static [SSCC18](./sscc18/) | 指定应使用 **SSCC18** 条码规范进行解码 |
| static [Standard2of5](./standard2of5/) | 指定应使用 **Standard 2 of 5** 条码规范进行解码 |
| static [Supplement](./supplement/) | 指定应使用 **Supplement(EAN2, EAN5)** 条码规范进行解码 |
| static [SwissPostParcel](./swisspostparcel/) | 指定应使用 **Swiss Post Parcel Barcode** 条码规范进行解码 |
| static [Types1D](./types1d/) | 指定将使用所有 **1D** 条码符号进行检查 |
| static [Types2D](./types2d/) | 指定将使用所有 **2D** 条码符号进行检查 |
| static [UPCA](./upca/) | 指定应使用 **UPC-A** 条码规范进行解码 |
| static [UPCE](./upce/) | 指定应使用 **UPC-E** 条码规范进行解码 |
| static [VIN](./vin/) | 指定应使用 **VIN**（Vehicle Identification Number）条码规范进行解码 |
## 备注


此示例展示了如何检测 Code39 和 Code128 条码。
```cpp
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

## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
