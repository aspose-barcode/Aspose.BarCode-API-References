---
title: DecodeType
second_title: .NET API 참조용 Aspose.BarCode
description: 읽을 바코드 유형을 지정합니다.
type: docs
weight: 190
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
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | AllSupportedTypes 를 나타내는 배열을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | 디코드 유형의 이름 배열을 검색합니다. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | 지정된[`BaseDecodeType`](../basedecodetype/) 모든 1D 바코드 포함 symbology |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | 지정된[`BaseDecodeType`](../basedecodetype/) 모든 2D 바코드 포함 symbology |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | 지정된[`BaseDecodeType`](../basedecodetype/) 우편 바코드 symbology 를 포함합니다. |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환의 성공 또는 실패 여부를 나타냅니다. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | barcodeTypes 로 스캔 세트 지정 |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultyDecodeType) | MultyDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환의 성공 또는 실패 여부를 나타냅니다. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | SingleDecodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환의 성공 또는 실패 여부를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | 사용 가능한 모든 symbologies 로 데이터를 확인하도록 지정합니다. |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | 데이터를 디코딩해야 함을 지정합니다. **호주 우체국 국내 전자소포 바코드** 바코드 사양 |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | 데이터를 디코딩해야 함을 지정합니다. **오스트레일리아 포스트** 바코드 사양 |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | 데이터를 디코딩해야 함을 지정합니다. **아즈텍** 바코드 사양 |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | 데이터를 디코딩해야 함을 지정합니다. **코다바** 바코드 사양 |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | 데이터를 디코딩해야 함을 지정합니다. **코다블럭F** 바코드 사양 |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | 데이터를 디코딩해야 함을 지정합니다. **코드 11** 바코드 사양 |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | 데이터를 디코딩해야 함을 지정합니다. **코드 128** 바코드 사양 |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | 데이터를 디코딩해야 함을 지정합니다. **SCode16K** 바코드 사양 |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | 데이터를 디코딩해야 함을 지정합니다. **코드32** 블랭크 사양 |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended/) | 데이터를 디코딩해야 함을 지정합니다. **확장 코드 39** 바코드 사양 |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard/) | 데이터를 디코딩해야 함을 지정합니다. **표준 코드 39** 바코드 사양 |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended/) | 데이터를 디코딩해야 함을 지정합니다. **확장 코드 93** 바코드 사양 |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard/) | 데이터를 디코딩해야 함을 지정합니다. **표준 코드 93** 바코드 사양 |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | 데이터를 디코딩해야 함을 지정합니다. **콤팩트Pdf417** (Pdf417잘림) 바코드 사양 |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | 데이터를 디코딩해야 함을 지정합니다. **GS1 데이터바 확장** 바코드 사양 |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | 데이터를 디코딩해야 함을 지정합니다. **GS1 Databar 확장 스택** 바코드 사양 |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | 데이터를 디코딩해야 함을 지정합니다. **GS1 데이터바 제한** 바코드 사양 |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | 데이터를 디코딩해야 함을 지정합니다. **GS1 Databar 전방향성** 바코드 사양 |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | 데이터를 디코딩해야 함을 지정합니다. **GS1 Databar 스택** 바코드 사양 |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | 데이터를 디코딩해야 함을 지정합니다. **GS1 Databar 적층 전방향성** 바코드 사양 |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | 데이터를 디코딩해야 함을 지정합니다. **GS1 데이터바 잘림** 바코드 사양 |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | 데이터를 디코딩해야 함을 지정합니다. **데이터로직 2/5** 블랭크 사양 |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | 데이터를 디코딩해야 함을 지정합니다. **데이터매트릭스** 바코드 symbology |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | 데이터를 디코딩해야 함을 지정합니다. **DeutschePost 식별 코드** 바코드 사양 |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | 데이터를 디코딩해야 함을 지정합니다. **DeutschePost Leit 코드** 바코드 사양 |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | 데이터를 디코딩해야 함을 지정합니다. **도트코드** 블랭크 사양 |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | 데이터를 디코딩해야 함을 지정합니다. **도트코드** 블랭크 사양 |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | 데이터를 디코딩해야 함을 지정합니다. **EAN-13** 바코드 사양 |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | 데이터를 디코딩해야 함을 지정합니다. **EAN14** 바코드 사양 |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | 데이터를 디코딩해야 함을 지정합니다. **EAN-8** 바코드 사양 |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | 데이터를 디코딩해야 함을 지정합니다. **GS1 코드 128** 바코드 사양 |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | 데이터를 디코딩해야 함을 지정합니다. **GS1DataMatrix** 바코드 symbology |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | 데이터를 디코딩해야 함을 지정합니다. **GS1 도트코드** 블랭크 사양 |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | 데이터를 디코딩해야 함을 지정합니다. **GS1 QR** 바코드 사양 |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | 데이터를 디코딩해야 함을 지정합니다. **HIBC LIC 아즈텍** 블랭크 사양 |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | 데이터를 디코딩해야 함을 지정합니다. **HIBC PAS 아즈텍** 블랭크 사양 |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | 데이터를 디코딩해야 함을 지정합니다. **HIBC LIC 코드128** 블랭크 사양 |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | 데이터를 디코딩해야 함을 지정합니다. **HIBC PAS 코드128** 블랭크 사양 |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | 데이터를 디코딩해야 함을 지정합니다. **HIBC LIC 코드39** 블랭크 사양 |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | 데이터를 디코딩해야 함을 지정합니다. **HIBC PAS 코드39** 블랭크 사양 |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | 데이터를 디코딩해야 함을 지정합니다. **HIBC LIC 데이터매트릭스** 블랭크 사양 |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | 데이터를 디코딩해야 함을 지정합니다. **HIBC PAS 데이터매트릭스** 블랭크 사양 |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | 데이터를 디코딩해야 함을 지정합니다. **HIBC LIC QR** 블랭크 사양 |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | 데이터를 디코딩해야 함을 지정합니다. **HIBC PAS QR** 블랭크 사양 |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | 데이터를 디코딩해야 함을 지정합니다. **IATA 2/5**바코드 사양. IATA(International Air Transport Association)에서 항공 화물 관리를 위해 이 바코드를 사용합니다. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | 데이터를 디코딩해야 함을 지정합니다. **인터리브 2/5** 바코드 사양 |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | 데이터를 디코딩해야 함을 지정합니다. **ISBN** 바코드 사양 |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | 데이터를 디코딩해야 함을 지정합니다. **ISMN** 바코드 사양 |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | 데이터를 디코딩해야 함을 지정합니다. **ISSN** 바코드 사양 |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | 데이터를 디코딩해야 함을 지정합니다. **이탈리아 포스트 25** 바코드 사양 |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | 데이터를 디코딩해야 함을 지정합니다. **ITF14** 바코드 사양 |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | 데이터를 디코딩해야 함을 지정합니다. **ITF6** 바코드 사양 |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | 데이터를 디코딩해야 함을 지정합니다. **매크로Pdf417** 바코드 사양 |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | 데이터를 디코딩해야 함을 지정합니다. **왕실 우편물 표식** 바코드 사양. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | 데이터를 디코딩해야 함을 지정합니다. **매트릭스 2/5** 바코드 사양 |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | 데이터를 디코딩해야 함을 지정합니다. **맥시코드** 바코드 사양 |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | 데이터를 디코딩해야 함을 지정합니다. **MICR E-13B** 블랭크 사양 |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | 데이터를 디코딩해야 함을 지정합니다. **마이크로 PDF417** 바코드 사양 |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | 데이터를 디코딩해야 함을 지정합니다. **마이크로QR 코드** 바코드 사양 |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | 가장 일반적으로 사용되는 symbologies 로 데이터를 확인하도록 지정합니다. |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | 데이터를 디코딩해야 함을 지정합니다. **MSI 플레시** 바코드 사양 |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | 지정되지 않은 디코드 유형입니다. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | 데이터가 USPS로 디코딩되어야 함을 지정합니다. **원코드** 바코드 사양 |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | 데이터를 디코딩해야 함을 지정합니다. **OPC** 바코드 사양 |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | 데이터를 디코딩해야 함을 지정합니다. **패치 코드** 바코드 사양. 자동 스캐닝 에 바코드 기호가 사용됩니다. |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | 데이터를 디코딩해야 함을 지정합니다. **PDF417** 바코드 symbology |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | 데이터를 디코딩해야 함을 지정합니다. **약어 코드** 바코드. 이 기호는 제약 바이너리 코드 라고도 합니다. |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | 데이터를 디코딩해야 함을 지정합니다. **행성** 바코드 사양 |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | 데이터가 모든 **1.5D 우편** 다음과 같은 바코드 기호 **플래닛, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | 데이터를 디코딩해야 함을 지정합니다. **포스트넷** 바코드 사양 |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | 데이터를 디코딩해야 함을 지정합니다. **PZN** 바코드 사양. 이 기호는 Pharma Zentral Nummer 라고도 합니다. |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | 데이터를 디코딩해야 함을 지정합니다. **QR 코드** 바코드 사양 |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | 데이터를 디코딩해야 함을 지정합니다. **RM4SCC** 바코드 사양. RM4SCC(Royal Mail 4-state Customer Code)는 영국에서 자동화된 메일 정렬 프로세스에 사용됩니다. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | 데이터를 디코딩해야 함을 지정합니다. **SCC14** 바코드 사양 |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | 데이터를 디코딩해야 함을 지정합니다. **SSCC18** 바코드 사양 |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | 데이터를 디코딩해야 함을 지정합니다. **표준 2/5** 바코드 사양 |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | 데이터를 디코딩해야 함을 지정합니다. **보충(EAN2, EAN5)** 바코드 사양 |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | 데이터를 디코딩해야 함을 지정합니다. **스위스 우편 소포 바코드** 바코드 사양 |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | 데이터가 모든 **1D** 바코드 기호학 |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | 데이터가 모든 **2D** 바코드 기호학 |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | 데이터를 디코딩해야 함을 지정합니다. **UPC-A** 바코드 사양 |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | 데이터를 디코딩해야 함을 지정합니다. **UPC-E** 바코드 사양 |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | 데이터를 디코딩해야 함을 지정합니다. **빈** (차량 식별 번호) 바코드 사양 |

### 예

이 샘플은 Code39 및 Code128 바코드를 감지하는 방법을 보여줍니다.

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

### 또한보십시오

* 네임스페이스 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
