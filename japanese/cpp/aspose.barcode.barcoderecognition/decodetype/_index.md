---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType クラス"
linktitle: "DecodeType"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType クラス。C++ で読み取るバーコードのタイプを指定します。"
type: docs
weight: 1600
url: /ja/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


読み取るバーコードのタイプを指定します。

```cpp
class DecodeType
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | AllSupportedTypes を表す配列を取得します |
| static [GetNames](./getnames/)() | デコードタイプの名前の配列を取得します。 |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | 指定された[BaseDecodeType](../basedecodetype/)が1Dバーコードシンボルを含むかどうかを判断します |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | 指定された[BaseDecodeType](../basedecodetype/)が2Dバーコードシンボルを含むかどうかを判断します |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | 指定された[BaseDecodeType](../basedecodetype/)が郵便バーコードシンボルを含むかどうかを判断します |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | 文字列表現の [SingleDecodeType](../singledecodetype/) をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | barcodeTypesでスキャンセットを指定します |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | 文字列表現の [SingleDecodeType](../singledecodetype/) をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | データが利用可能なすべてのシンボルでチェックされることを指定します |
| static [AustralianPosteParcel](./australianposteparcel/) | データを**Australian Post Domestic eParcel Barcode**バーコード仕様でデコードすべきことを指定します |
| static [AustraliaPost](./australiapost/) | データを**Australia Post**バーコード仕様でデコードすべきことを指定します |
| static [Aztec](./aztec/) | データを**Aztec**バーコード仕様でデコードすべきことを指定します |
| static [Codabar](./codabar/) | データを**CODABAR**バーコード仕様でデコードすべきことを指定します |
| static [CodablockF](./codablockf/) | データを**CodablockF**バーコード仕様でデコードすべきことを指定します |
| static [Code11](./code11/) | データを**CODE 11**バーコード仕様でデコードすべきことを指定します |
| static [Code128](./code128/) | データを**CODE 128**バーコード仕様でデコードすべきことを指定します |
| static [Code16K](./code16k/) | データを**SCode16K**バーコード仕様でデコードすべきことを指定します |
| static [Code32](./code32/) | データを**Code32**バーコード仕様でデコードすべきことを指定します |
| static [Code39](./code39/) | データを**Code 39**基本文字セットバーコード仕様（ISO/IEC 16388）でデコードすべきことを指定します |
| static [Code39FullASCII](./code39fullascii/) | データを**Code 39**フルASCII文字セットバーコード仕様（ISO/IEC 16388）でデコードすべきことを指定します |
| static [Code93](./code93/) | データを**CODE 93**バーコード仕様でデコードすべきことを指定します |
| static [CompactPdf417](./compactpdf417/) | データを**CompactPdf417**（Pdf417Truncated）バーコード仕様でデコードすべきことを指定します |
| static [DatabarExpanded](./databarexpanded/) | データを**GS1 Databar expanded**バーコード仕様でデコードすべきことを指定します |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | データを**GS1 Databar expanded stacked**バーコード仕様でデコードすべきことを指定します |
| static [DatabarLimited](./databarlimited/) | データを**GS1 Databar limited**バーコード仕様でデコードすべきことを指定します |
| static [DatabarOmniDirectional](./databaromnidirectional/) | データを**GS1 Databar omni-directional**バーコード仕様でデコードすべきことを指定します |
| static [DatabarStacked](./databarstacked/) | データを**GS1 Databar stacked**バーコード仕様でデコードすべきことを指定します |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | データを**GS1 Databar stacked omni-directional**バーコード仕様でデコードすべきことを指定します |
| static [DatabarTruncated](./databartruncated/) | データを**GS1 Databar truncated**バーコード仕様でデコードすべきことを指定します |
| static [DataLogic2of5](./datalogic2of5/) | データが **DataLogic 2 of 5** バーコード仕様でデコードされるように指定します |
| static [DataMatrix](./datamatrix/) | データが **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** バーコードシンボルでデコードされるように指定します |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | データが **DeutschePost Ident code** バーコード仕様でデコードされるように指定します |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | データが **DeutschePost Leit code** バーコード仕様でデコードされるように指定します |
| static [DotCode](./dotcode/) | データが **DotCode** バーコード仕様でデコードされるように指定します |
| static [DutchKIX](./dutchkix/) | データが **DotCode** バーコード仕様でデコードされるように指定します |
| static [EAN13](./ean13/) | データが **EAN-13** バーコード仕様でデコードされるように指定します |
| static [EAN14](./ean14/) | データが **EAN14** バーコード仕様でデコードされるように指定します |
| static [EAN8](./ean8/) | データが **EAN-8** バーコード仕様でデコードされるように指定します |
| static [GS1Aztec](./gs1aztec/) | データが **GS1 Aztec** バーコード仕様でデコードされるように指定します |
| static [GS1Code128](./gs1code128/) | データが **GS1 CODE 128** バーコード仕様でデコードされるように指定します |
| static [GS1CompositeBar](./gs1compositebar/) | データが **GS1 Composite Bar** バーコード仕様でデコードされるように指定します |
| static [GS1DataMatrix](./gs1datamatrix/) | データが **GS1DataMatrix** バーコードシンボルでデコードされるように指定します |
| static [GS1DotCode](./gs1dotcode/) | データが **GS1 DotCode** バーコード仕様でデコードされるように指定します |
| static [GS1HanXin](./gs1hanxin/) | データが **GS1 Han Xin Code** バーコード仕様でデコードされるように指定します |
| static [GS1MicroPdf417](./gs1micropdf417/) | データが **MicroPdf417** バーコード仕様でデコードされるように指定します |
| static [GS1QR](./gs1qr/) | データが **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** バーコード仕様でデコードされるように指定します |
| static [HanXin](./hanxin/) | データが **Han Xin Code** バーコード仕様でデコードされるように指定します |
| static [HIBCAztecLIC](./hibcazteclic/) | データが **HIBC LIC Aztec** バーコード仕様でデコードされるように指定します |
| static [HIBCAztecPAS](./hibcaztecpas/) | データが **HIBC PAS Aztec** バーコード仕様でデコードされるように指定します |
| static [HIBCCode128LIC](./hibccode128lic/) | データが **HIBC LIC Code128** バーコード仕様でデコードされるように指定します |
| static [HIBCCode128PAS](./hibccode128pas/) | データが **HIBC PAS Code128** バーコード仕様でデコードされるように指定します |
| static [HIBCCode39LIC](./hibccode39lic/) | データが **HIBC LIC Code39** バーコード仕様でデコードされるように指定します |
| static [HIBCCode39PAS](./hibccode39pas/) | データが **HIBC PAS Code39** バーコード仕様でデコードされるように指定します |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | データが **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** バーコード仕様でデコードされるように指定します |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | データが **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** バーコード仕様でデコードされるように指定します |
| static [HIBCQRLIC](./hibcqrlic/) | データは **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** バーコード仕様でデコードされることを指定します |
| static [HIBCQRPAS](./hibcqrpas/) | データは **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** バーコード仕様でデコードされることを指定します |
| static [IATA2of5](./iata2of5/) | データは **IATA 2 of 5** バーコード仕様でデコードされることを指定します。IATA（International Air Transport Association）はこのバーコードを航空貨物の管理に使用します。 |
| static [Interleaved2of5](./interleaved2of5/) | データは **INTERLEAVED 2 of 5** バーコード仕様でデコードされることを指定します |
| static [ISBN](./isbn/) | データは **ISBN** バーコード仕様でデコードされることを指定します |
| static [ISMN](./ismn/) | データは **ISMN** バーコード仕様でデコードされることを指定します |
| static [ISSN](./issn/) | データは **ISSN** バーコード仕様でデコードされることを指定します |
| static [ItalianPost25](./italianpost25/) | データは **Italian Post 25** バーコード仕様でデコードされることを指定します |
| static [ITF14](./itf14/) | データは **ITF14** バーコード仕様でデコードされることを指定します |
| static [ITF6](./itf6/) | データは **ITF6** バーコード仕様でデコードされることを指定します |
| static [JapanPost](./japanpost/) | データは **Japan Post** バーコード仕様でデコードされることを指定します |
| static [MacroPdf417](./macropdf417/) | データは **MacroPdf417** バーコード仕様でデコードされることを指定します |
| static [Mailmark](./mailmark/) | データは **Royal Mail Mailmark** バーコード仕様でデコードされることを指定します。 |
| static [Matrix2of5](./matrix2of5/) | データは **Matrix 2 of 5** バーコード仕様でデコードされることを指定します |
| static [MaxiCode](./maxicode/) | データは **MaxiCode** バーコード仕様でデコードされることを指定します |
| static [MicrE13B](./micre13b/) | データは **MICR E-13B** バーコード仕様でデコードされることを指定します |
| static [MicroPdf417](./micropdf417/) | データが **MicroPdf417** バーコード仕様でデコードされるように指定します |
| static [MicroQR](./microqr/) | データは **MicroQR Code** バーコード仕様でデコードされることを指定します |
| static [MostCommonTypes](./mostcommontypes/) | データは最も一般的に使用されるシンボルでチェックされることを指定します |
| static [MSI](./msi/) | データは **MSI Plessey** バーコード仕様でデコードされることを指定します |
| static [None](./none/) | デコードタイプが未指定です。 |
| static [OneCode](./onecode/) | データは USPS **OneCode** バーコード仕様でデコードされることを指定します |
| static [OPC](./opc/) | データは **OPC** バーコード仕様でデコードされることを指定します |
| static [PatchCode](./patchcode/) | データは **Patch code** バーコード仕様でデコードされることを指定します。バーコードシンボルは自動スキャンに使用されます |
| static [Pdf417](./pdf417/) | データは **Pdf417** バーコードシンボルでデコードされることを指定します |
| static [Pharmacode](./pharmacode/) | データは **Pharmacode** バーコードでデコードされることを指定します。このシンボルは Pharmaceutical Binary Code とも呼ばれます |
| static [Planet](./planet/) | データを **Planet** バーコード仕様でデコードすることを指定します |
| static [PostalTypes](./postaltypes/) | データが **1.5D Postal** バーコードシンボルすべてでチェックされることを指定します。**Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX** など |
| static [Postnet](./postnet/) | データを **Postnet** バーコード仕様でデコードすることを指定します |
| static [PZN](./pzn/) | データを **PZN** バーコード仕様でデコードすることを指定します。このシンボルは Pharma Zentral Nummer とも呼ばれます。PZN7 と PZN8 がサポートされています。 |
| static [QR](./qr/) | データを **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** バーコード仕様でデコードすることを指定します |
| static [RectMicroQR](./rectmicroqr/) | データを **RectMicroQR (rMQR) Code** バーコード仕様でデコードすることを指定します |
| static [RM4SCC](./rm4scc/) | データを **RM4SCC** バーコード仕様でデコードすることを指定します。RM4SCC（Royal Mail 4-state Customer Code）は、英国の自動郵便仕分けプロセスで使用されます。 |
| static [SCC14](./scc14/) | データを **SCC14** バーコード仕様でデコードすることを指定します |
| static [SSCC18](./sscc18/) | データを **SSCC18** バーコード仕様でデコードすることを指定します |
| static [Standard2of5](./standard2of5/) | データを **Standard 2 of 5** バーコード仕様でデコードすることを指定します |
| static [Supplement](./supplement/) | データを **Supplement(EAN2, EAN5)** バーコード仕様でデコードすることを指定します |
| static [SwissPostParcel](./swisspostparcel/) | データを **Swiss Post Parcel Barcode** バーコード仕様でデコードすることを指定します |
| static [Types1D](./types1d/) | データが **1D** バーコードシンボルすべてでチェックされることを指定します |
| static [Types2D](./types2d/) | データが **2D** バーコードシンボルすべてでチェックされることを指定します |
| static [UPCA](./upca/) | データを **UPC-A** バーコード仕様でデコードすることを指定します |
| static [UPCE](./upce/) | データを **UPC-E** バーコード仕様でデコードすることを指定します |
| static [VIN](./vin/) | データを **VIN**（Vehicle Identification Number）バーコード仕様でデコードすることを指定します |
## 備考


このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
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

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
