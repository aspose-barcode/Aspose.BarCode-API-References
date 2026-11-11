---
title: "클래스 DecodeType"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.DecodeType 클래스. 읽을 바코드 유형을 지정합니다"
type: docs
weight: 230
url: /ko/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

읽을 바코드 유형을 지정합니다.

```csharp
public static class DecodeType
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | AllSupportedTypes를 나타내는 배열을 가져옵니다 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | 디코드 유형 이름들의 배열을 검색합니다 |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | 지정된 [`BaseDecodeType`](../basedecodetype/)이 1D 바코드 심볼리지를 포함하는지 확인합니다 |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | 지정된 [`BaseDecodeType`](../basedecodetype/)이 2D 바코드 심볼리지를 포함하는지 확인합니다 |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | 지정된 [`BaseDecodeType`](../basedecodetype/)이 우편 바코드 심볼리지를 포함하는지 확인합니다 |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | barcodeTypes별로 스캔 세트를 지정합니다 |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultiDecodeType) | MultiDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환이 성공했는지 실패했는지를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | 데이터가 사용 가능한 모든 심볼리지를 사용하여 검사된다는 것을 지정합니다 |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | 데이터를 **Australian Post Domestic eParcel Barcode** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | 데이터를 **Australia Post** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | 데이터를 **Aztec** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | 데이터를 **CODABAR** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | 데이터를 **CodablockF** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | 데이터를 **CODE 11** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | 데이터를 **CODE 128** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | 데이터를 **SCode16K** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | 데이터를 **Code32** 바코드 사양으로 디코딩해야 함을 지정합니다 |
| static readonly [Code39](../../aspose.barcode.barcoderecognition/decodetype/code39/) | 데이터를 **Code 39** 기본 문자 집합 바코드 사양으로 디코딩해야 함을 지정합니다: ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.barcoderecognition/decodetype/code39fullascii/) | 데이터를 **Code 39** 전체 ASCII 문자 집합 바코드 사양으로 디코딩해야 함을 지정합니다: ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.barcoderecognition/decodetype/code93/) | 데이터를 **CODE 93** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | 데이터를 **CompactPdf417** (Pdf417Truncated) 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | 데이터를 **GS1 Databar expanded** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | 데이터를 **GS1 Databar expanded stacked** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | 데이터를 **GS1 Databar limited** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | 데이터를 **GS1 Databar omni-directional** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | 데이터를 **GS1 Databar stacked** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | 데이터를 **GS1 Databar stacked omni-directional** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | 데이터를 **GS1 Databar truncated** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | 데이터를 **DataLogic 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | 데이터를 **DataMatrix** 바코드 심볼로 디코딩하도록 지정합니다 |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | 데이터를 **DeutschePost Ident code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | 데이터를 **DeutschePost Leit code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | 데이터를 **DotCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | 데이터를 **DotCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | 데이터를 **EAN-13** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | 데이터를 **EAN14** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | 데이터를 **EAN-8** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [GS1Aztec](../../aspose.barcode.barcoderecognition/decodetype/gs1aztec/) | 데이터를 **GS1 Aztec** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | 데이터를 **GS1 CODE 128** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [GS1CompositeBar](../../aspose.barcode.barcoderecognition/decodetype/gs1compositebar/) | 데이터를 **GS1 Composite Bar** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | 데이터를 **GS1DataMatrix** 바코드 심볼로 디코딩하도록 지정합니다 |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | 데이터를 **GS1 DotCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [GS1HanXin](../../aspose.barcode.barcoderecognition/decodetype/gs1hanxin/) | 데이터를 **GS1 Han Xin Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [GS1MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/gs1micropdf417/) | 데이터를 **MicroPdf417** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | 데이터를 **GS1 QR** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [HanXin](../../aspose.barcode.barcoderecognition/decodetype/hanxin/) | 데이터를 **Han Xin Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | 데이터를 **HIBC LIC Aztec** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | 데이터를 **HIBC PAS Aztec** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | 데이터를 **HIBC LIC Code128** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | 데이터를 **HIBC PAS Code128** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | 데이터를 **HIBC LIC Code39** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | 데이터를 **HIBC PAS Code39** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | 데이터를 **HIBC LIC DataMatrix** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | 데이터를 **HIBC PAS DataMatrix** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | 데이터를 **HIBC LIC QR** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | 데이터를 **HIBC PAS QR** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | 데이터를 **IATA 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다. IATA(International Air Transport Association)는 이 바코드를 항공 화물 관리에 사용합니다. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | 데이터를 **INTERLEAVED 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | 데이터를 **ISBN** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | 데이터를 **ISMN** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | 데이터를 **ISSN** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | 데이터를 **Italian Post 25** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | 데이터를 **ITF14** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | 데이터를 **ITF6** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [JapanPost](../../aspose.barcode.barcoderecognition/decodetype/japanpost/) | 데이터를 **Japan Post** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | 데이터를 **MacroPdf417** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | 데이터를 **Royal Mail Mailmark** 바코드 사양으로 디코딩하도록 지정합니다. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | 데이터를 **Matrix 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | 데이터를 **MaxiCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | 데이터를 **MICR E-13B** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | 데이터를 **MicroPdf417** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | 데이터를 **MicroQR Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | 데이터가 가장 일반적으로 사용되는 바코드 심볼로 검사되도록 지정합니다 |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | 데이터를 **MSI Plessey** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | 지정되지 않은 디코드 유형입니다. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | 데이터를 USPS **OneCode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | 데이터를 **OPC** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | 데이터를 **Patch code** 바코드 사양으로 디코딩하도록 지정합니다. 바코드 심볼은 자동 스캔에 사용됩니다 |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | 데이터를 **Pdf417** 바코드 심볼로 디코딩하도록 지정합니다 |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | 데이터를 **Pharmacode** 바코드로 디코딩하도록 지정합니다. 이 심볼은 Pharmaceutical Binary Code로도 알려져 있습니다 |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | 데이터를 **Planet** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | 데이터가 **1.5D Postal** 바코드 심볼 전체와 **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX**와 같은 심볼을 사용하여 검사되도록 지정합니다 |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | 데이터를 **Postnet** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | 데이터를 **PZN** 바코드 사양으로 디코딩하도록 지정합니다. 이 심볼은 Pharma Zentral Nummer로도 알려져 있으며, PZN7 및 PZN8을 지원합니다. |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | 데이터를 **QR Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [RectMicroQR](../../aspose.barcode.barcoderecognition/decodetype/rectmicroqr/) | 데이터를 **RectMicroQR (rMQR) Code** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | 데이터를 **RM4SCC** 바코드 사양으로 디코딩하도록 지정합니다. RM4SCC(Royal Mail 4-state Customer Code)는 영국의 자동 우편 분류 과정에 사용됩니다. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | 데이터를 **SCC14** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | 데이터를 **SSCC18** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | 데이터를 **Standard 2 of 5** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | 데이터를 **Supplement(EAN2, EAN5)** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | 데이터를 **Swiss Post Parcel Barcode** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | 데이터가 **1D** 바코드 심볼 전체를 사용하여 검사되도록 지정합니다 |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | 데이터가 **2D** 바코드 심볼 전체를 사용하여 검사되도록 지정합니다 |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | 데이터를 **UPC-A** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | 데이터를 **UPC-E** 바코드 사양으로 디코딩하도록 지정합니다 |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | 데이터를 **VIN**(Vehicle Identification Number) 바코드 사양으로 디코딩해야 함을 지정합니다 |

## 예제

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


