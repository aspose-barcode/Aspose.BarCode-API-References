---
title: "Aspose::BarCode::BarCodeRecognition::DecodeType 클래스"
linktitle: "DecodeType"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::DecodeType 클래스. C++에서 읽을 바코드 유형을 지정합니다."
type: docs
weight: 1600
url: /ko/cpp/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class


읽을 바코드 유형을 지정합니다.

```cpp
class DecodeType
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [DecodeType](./decodetype/)() |  |
| static [get_AllSupportedTypesArray](./get_allsupportedtypesarray/)() | AllSupportedTypes를 나타내는 배열을 가져옵니다. |
| static [GetNames](./getnames/)() | 디코드 유형 이름들의 배열을 검색합니다. |
| static [Is1D](./is1d/)(System::SharedPtr\<BaseDecodeType\>) | 지정된 [BaseDecodeType](../basedecodetype/)에 1D 바코드 심볼이 포함되어 있는지 확인합니다 |
| static [Is2D](./is2d/)(System::SharedPtr\<BaseDecodeType\>) | 지정된 [BaseDecodeType](../basedecodetype/)에 2D 바코드 심볼이 포함되어 있는지 확인합니다 |
| static [IsPostal](./ispostal/)(System::SharedPtr\<BaseDecodeType\>) | 지정된 [BaseDecodeType](../basedecodetype/)에 우편 바코드 심볼이 포함되어 있는지 확인합니다 |
| static [Parse](./parse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [ScanSets](./scansets/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | barcodeTypes별로 스캔 세트를 지정합니다 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](../singledecodetype/)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/)의 문자열 표현을 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| static [AllSupportedTypes](./allsupportedtypes/) | 데이터가 사용 가능한 모든 심볼을 사용하여 검사된다고 지정합니다 |
| static [AustralianPosteParcel](./australianposteparcel/) | 데이터를 **Australian Post Domestic eParcel Barcode** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [AustraliaPost](./australiapost/) | 데이터를 **Australia Post** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [Aztec](./aztec/) | 데이터를 **Aztec** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [Codabar](./codabar/) | 데이터를 **CODABAR** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [CodablockF](./codablockf/) | 데이터를 **CodablockF** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [Code11](./code11/) | 데이터를 **CODE 11** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [Code128](./code128/) | 데이터를 **CODE 128** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [Code16K](./code16k/) | 데이터를 **SCode16K** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [Code32](./code32/) | 데이터를 **Code32** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [Code39](./code39/) | 데이터를 **Code 39** 기본 문자 집합 바코드 사양으로 디코딩해야 함을 지정합니다: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | 데이터를 **Code 39** 전체 ASCII 문자 집합 바코드 사양으로 디코딩해야 함을 지정합니다: ISO/IEC 16388 |
| static [Code93](./code93/) | 데이터를 **CODE 93** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [CompactPdf417](./compactpdf417/) | 데이터를 **CompactPdf417** (Pdf417Truncated) 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [DatabarExpanded](./databarexpanded/) | 데이터를 **GS1 Databar expanded** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | 데이터를 **GS1 Databar expanded stacked** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [DatabarLimited](./databarlimited/) | 데이터를 **GS1 Databar limited** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [DatabarOmniDirectional](./databaromnidirectional/) | 데이터를 **GS1 Databar omni-directional** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [DatabarStacked](./databarstacked/) | 데이터를 **GS1 Databar stacked** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | 데이터를 **GS1 Databar stacked omni-directional** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [DatabarTruncated](./databartruncated/) | 데이터를 **GS1 Databar truncated** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static [DataLogic2of5](./datalogic2of5/) | 데이터를 **DataLogic 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [DataMatrix](./datamatrix/) | 데이터를 **[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** 바코드 심볼로지로 디코딩하도록 지정합니다 |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | 데이터를 **DeutschePost Ident code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | 데이터를 **DeutschePost Leit code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [DotCode](./dotcode/) | 데이터를 **DotCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [DutchKIX](./dutchkix/) | 데이터를 **DotCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [EAN13](./ean13/) | 데이터를 **EAN-13** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [EAN14](./ean14/) | 데이터를 **EAN14** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [EAN8](./ean8/) | 데이터를 **EAN-8** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [GS1Aztec](./gs1aztec/) | 데이터를 **GS1 Aztec** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [GS1Code128](./gs1code128/) | 데이터를 **GS1 CODE 128** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [GS1CompositeBar](./gs1compositebar/) | 데이터를 **GS1 Composite Bar** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [GS1DataMatrix](./gs1datamatrix/) | 데이터를 **GS1DataMatrix** 바코드 심볼로지로 디코딩하도록 지정합니다 |
| static [GS1DotCode](./gs1dotcode/) | 데이터를 **GS1 DotCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [GS1HanXin](./gs1hanxin/) | 데이터를 **GS1 Han Xin Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [GS1MicroPdf417](./gs1micropdf417/) | 데이터를 **MicroPdf417** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [GS1QR](./gs1qr/) | 데이터를 **GS1 [QR](../../aspose.barcode.barcoderecognition.qr/)** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [HanXin](./hanxin/) | 데이터를 **Han Xin Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [HIBCAztecLIC](./hibcazteclic/) | 데이터를 **HIBC LIC Aztec** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [HIBCAztecPAS](./hibcaztecpas/) | 데이터를 **HIBC PAS Aztec** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [HIBCCode128LIC](./hibccode128lic/) | 데이터를 **HIBC LIC Code128** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [HIBCCode128PAS](./hibccode128pas/) | 데이터를 **HIBC PAS Code128** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [HIBCCode39LIC](./hibccode39lic/) | 데이터를 **HIBC LIC Code39** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [HIBCCode39PAS](./hibccode39pas/) | 데이터를 **HIBC PAS Code39** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | 데이터를 **HIBC LIC [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | 데이터를 **HIBC PAS [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [HIBCQRLIC](./hibcqrlic/) | 데이터를 **HIBC LIC [QR](../../aspose.barcode.barcoderecognition.qr/)** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [HIBCQRPAS](./hibcqrpas/) | 데이터를 **HIBC PAS [QR](../../aspose.barcode.barcoderecognition.qr/)** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [IATA2of5](./iata2of5/) | 데이터를 **IATA 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다. IATA(International Air Transport Association)는 항공 화물 관리에 이 바코드를 사용합니다. |
| static [Interleaved2of5](./interleaved2of5/) | 데이터를 **INTERLEAVED 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [ISBN](./isbn/) | 데이터를 **ISBN** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [ISMN](./ismn/) | 데이터를 **ISMN** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [ISSN](./issn/) | 데이터를 **ISSN** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [ItalianPost25](./italianpost25/) | 데이터를 **Italian Post 25** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [ITF14](./itf14/) | 데이터를 **ITF14** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [ITF6](./itf6/) | 데이터를 **ITF6** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [JapanPost](./japanpost/) | 데이터를 **Japan Post** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [MacroPdf417](./macropdf417/) | 데이터를 **MacroPdf417** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [Mailmark](./mailmark/) | 데이터를 **Royal Mail Mailmark** 바코드 사양으로 디코딩하도록 지정합니다. |
| static [Matrix2of5](./matrix2of5/) | 데이터를 **Matrix 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [MaxiCode](./maxicode/) | 데이터를 **MaxiCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [MicrE13B](./micre13b/) | 데이터를 **MICR E-13B** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [MicroPdf417](./micropdf417/) | 데이터를 **MicroPdf417** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [MicroQR](./microqr/) | 데이터를 **MicroQR Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [MostCommonTypes](./mostcommontypes/) | 데이터가 가장 일반적으로 사용되는 심볼로지를 사용해 검사되도록 지정합니다 |
| static [MSI](./msi/) | 데이터를 **MSI Plessey** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [None](./none/) | 지정되지 않은 디코드 유형입니다. |
| static [OneCode](./onecode/) | 데이터를 USPS **OneCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [OPC](./opc/) | 데이터를 **OPC** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [PatchCode](./patchcode/) | 데이터를 **Patch code** 바코드 사양으로 디코딩하도록 지정합니다. 바코드 심볼로지는 자동 스캔에 사용됩니다 |
| static [Pdf417](./pdf417/) | 데이터를 **Pdf417** 바코드 심볼로지로 디코딩하도록 지정합니다 |
| static [Pharmacode](./pharmacode/) | 데이터를 **Pharmacode** 바코드로 디코딩하도록 지정합니다. 이 심볼로지는 Pharmaceutical Binary Code라고도 알려져 있습니다 |
| static [Planet](./planet/) | 데이터를 **Planet** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [PostalTypes](./postaltypes/) | 데이터를 **1.5D Postal** 바코드 심볼 전체와 **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX**와 같은 심볼로 검사하도록 지정합니다 |
| static [Postnet](./postnet/) | 데이터를 **Postnet** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [PZN](./pzn/) | 데이터를 **PZN** 바코드 사양으로 디코딩하도록 지정합니다. 이 심볼은 Pharma Zentral Nummer로도 알려져 있습니다. PZN7 및 PZN8이 지원됩니다. |
| static [QR](./qr/) | 데이터를 **[QR](../../aspose.barcode.barcoderecognition.qr/) Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [RectMicroQR](./rectmicroqr/) | 데이터를 **RectMicroQR (rMQR) Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [RM4SCC](./rm4scc/) | 데이터를 **RM4SCC** 바코드 사양으로 디코딩하도록 지정합니다. RM4SCC (Royal Mail 4-state Customer Code)는 영국의 자동 우편 분류 프로세스에 사용됩니다. |
| static [SCC14](./scc14/) | 데이터를 **SCC14** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [SSCC18](./sscc18/) | 데이터를 **SSCC18** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [Standard2of5](./standard2of5/) | 데이터를 **Standard 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [Supplement](./supplement/) | 데이터를 **Supplement(EAN2, EAN5)** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [SwissPostParcel](./swisspostparcel/) | 데이터를 **Swiss Post Parcel Barcode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [Types1D](./types1d/) | 데이터를 **1D** 바코드 심볼 전체와 함께 검사하도록 지정합니다 |
| static [Types2D](./types2d/) | 데이터를 **2D** 바코드 심볼 전체와 함께 검사하도록 지정합니다 |
| static [UPCA](./upca/) | 데이터를 **UPC-A** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [UPCE](./upce/) | 데이터를 **UPC-E** 바코드 사양으로 디코딩하도록 지정합니다 |
| static [VIN](./vin/) | 데이터를 **VIN** (Vehicle Identification Number) 바코드 사양으로 디코딩하도록 지정합니다 |
## 비고


이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.
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

## 또 보기

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
