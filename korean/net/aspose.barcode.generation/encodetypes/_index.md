---
title: "클래스 EncodeTypes"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.EncodeTypes 클래스. 인코딩할 바코드 유형을 지정합니다."
type: docs
weight: 1290
url: /ko/net/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class

인코딩할 바코드 유형을 지정합니다.

```csharp
public static class EncodeTypes
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [AllEncodeTypes](../../aspose.barcode.generation/encodetypes/allencodetypes/) { get; } | 데이터가 사용 가능한 모든 심볼로지를 사용해 검사된다는 것을 지정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [GetNames](../../aspose.barcode.generation/encodetypes/getnames/)() | 인코드 유형 이름들의 배열을 검색합니다. |
| static [Parse](../../aspose.barcode.generation/encodetypes/parse/)(string, out BaseEncodeType) | BaseEncodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](../../aspose.barcode.generation/encodetypes/tryparse/)(string, out BaseEncodeType) | BaseEncodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [AustralianPosteParcel](../../aspose.barcode.generation/encodetypes/australianposteparcel/) | 데이터를 **Australian Post Domestic eParcel Barcode** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [AustraliaPost](../../aspose.barcode.generation/encodetypes/australiapost/) | Australia Post Customer BarCode를 나타냅니다. |
| static readonly [Aztec](../../aspose.barcode.generation/encodetypes/aztec/) | 데이터를 **Aztec** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [Codabar](../../aspose.barcode.generation/encodetypes/codabar/) | 데이터를 **CODABAR** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [CodablockF](../../aspose.barcode.generation/encodetypes/codablockf/) | 데이터를 **Codablock-F** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [Code11](../../aspose.barcode.generation/encodetypes/code11/) | 데이터를 **CODE 11** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [Code128](../../aspose.barcode.generation/encodetypes/code128/) | 데이터를 **CODE 128** 바코드 사양으로 인코딩하도록 지정합니다. |
| static readonly [Code16K](../../aspose.barcode.generation/encodetypes/code16k/) | Code 16K 바코드를 나타냅니다. |
| static readonly [Code32](../../aspose.barcode.generation/encodetypes/code32/) | 데이터를 **Code32** 바코드 사양으로 인코딩하도록 지정합니다. |
| static readonly [Code39](../../aspose.barcode.generation/encodetypes/code39/) | 데이터를 **Code 39** 기본 문자 집합 바코드 사양(ISO/IEC 16388)으로 인코딩하도록 지정합니다. |
| static readonly [Code39FullASCII](../../aspose.barcode.generation/encodetypes/code39fullascii/) | 데이터를 **Code 39** 전체 ASCII 문자 집합 바코드 사양(ISO/IEC 16388)으로 인코딩하도록 지정합니다. |
| static readonly [Code93](../../aspose.barcode.generation/encodetypes/code93/) | 데이터를 **CODE 93** 바코드 사양으로 인코딩하도록 지정합니다. |
| static readonly [DatabarExpanded](../../aspose.barcode.generation/encodetypes/databarexpanded/) | GS1 Databar 확장 바코드를 나타냅니다. |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.generation/encodetypes/databarexpandedstacked/) | GS1 Databar 확장 스택형 바코드를 나타냅니다. |
| static readonly [DatabarLimited](../../aspose.barcode.generation/encodetypes/databarlimited/) | GS1 Databar 제한 바코드를 나타냅니다. |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.generation/encodetypes/databaromnidirectional/) | 데이터를 **GS1 Databar omni-directional** 바코드 사양으로 인코딩하도록 지정합니다. |
| static readonly [DatabarStacked](../../aspose.barcode.generation/encodetypes/databarstacked/) | GS1 Databar 스택형 바코드를 나타냅니다. |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.generation/encodetypes/databarstackedomnidirectional/) | GS1 Databar 스택형 전방향 바코드를 나타냅니다. |
| static readonly [DatabarTruncated](../../aspose.barcode.generation/encodetypes/databartruncated/) | 데이터를 **GS1 Databar truncated** 바코드 사양으로 인코딩하도록 지정합니다. |
| static readonly [DataLogic2of5](../../aspose.barcode.generation/encodetypes/datalogic2of5/) | 데이터를 **DataLogic 2 of 5** 바코드 사양으로 인코딩하도록 지정합니다. |
| static readonly [DataMatrix](../../aspose.barcode.generation/encodetypes/datamatrix/) | 2D 바코드 심볼인 DataMatrix |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.generation/encodetypes/deutschepostidentcode/) | Deutsch Post 바코드를 나타냅니다. 이 심볼은 Identcode, CodeIdentcode, German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) 로도 알려져 있습니다. |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.generation/encodetypes/deutschepostleitcode/) | Deutsch Post Leitcode 바코드를 나타냅니다. 또한 German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL) 로도 알려져 있습니다. |
| static readonly [DotCode](../../aspose.barcode.generation/encodetypes/dotcode/) | 데이터를 **DotCode** 바코드 사양으로 인코딩하도록 지정합니다. |
| static readonly [DutchKIX](../../aspose.barcode.generation/encodetypes/dutchkix/) | 데이터를 **Dutch KIX** 바코드 사양으로 인코딩하도록 지정합니다. |
| static readonly [EAN13](../../aspose.barcode.generation/encodetypes/ean13/) | 데이터를 **EAN-13** 바코드 사양으로 인코딩하도록 지정합니다. |
| static readonly [EAN14](../../aspose.barcode.generation/encodetypes/ean14/) | 데이터를 **EAN14** 바코드 사양으로 인코딩하도록 지정합니다. |
| static readonly [EAN8](../../aspose.barcode.generation/encodetypes/ean8/) | 데이터를 **EAN-8** 바코드 사양으로 인코딩하도록 지정합니다. |
| static readonly [GS1Aztec](../../aspose.barcode.generation/encodetypes/gs1aztec/) | 데이터를 **GS1 Aztec** 바코드 사양으로 인코딩하도록 지정합니다. 코드 텍스트는 AI를 위해 괄호를 포함해야 합니다. |
| static readonly [GS1CodablockF](../../aspose.barcode.generation/encodetypes/gs1codablockf/) | 데이터를 **GS1 Codablock-F** 바코드 사양으로 인코딩하도록 지정합니다. 코드 텍스트는 AI를 위해 괄호를 포함해야 합니다. |
| static readonly [GS1Code128](../../aspose.barcode.generation/encodetypes/gs1code128/) | 데이터를 **GS1 Code 128** 바코드 사양으로 인코딩하도록 지정합니다. 코드 텍스트는 AI를 위해 괄호를 포함해야 합니다. |
| static readonly [GS1CompositeBar](../../aspose.barcode.generation/encodetypes/gs1compositebar/) | 데이터를 **GS1 Composite Bar** 바코드 사양으로 인코딩해야 함을 지정합니다. 코드텍스트는 AI를 위해 괄호를 포함해야 합니다. 1D 코드텍스트와 2D 코드텍스트는 '/' 기호로 구분되어야 합니다. |
| static readonly [GS1DataMatrix](../../aspose.barcode.generation/encodetypes/gs1datamatrix/) | GS1 문자열 형식이 적용된 2D 바코드 심볼 DataMatrix |
| static readonly [GS1DotCode](../../aspose.barcode.generation/encodetypes/gs1dotcode/) | 데이터를 **GS1 DotCode** 바코드 사양으로 인코딩해야 함을 지정합니다. 코드텍스트는 AI를 위해 괄호를 포함해야 합니다. |
| static readonly [GS1HanXin](../../aspose.barcode.generation/encodetypes/gs1hanxin/) | GS1 문자열 형식이 적용된 2D 바코드 심볼 HanXin |
| static readonly [GS1MicroPdf417](../../aspose.barcode.generation/encodetypes/gs1micropdf417/) | 데이터를 **GS1MicroPdf417** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [GS1QR](../../aspose.barcode.generation/encodetypes/gs1qr/) | GS1 문자열 형식이 적용된 2D 바코드 심볼 QR |
| static readonly [HanXin](../../aspose.barcode.generation/encodetypes/hanxin/) | 데이터를 **Han Xin** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [HIBCAztecLIC](../../aspose.barcode.generation/encodetypes/hibcazteclic/) | 데이터를 **HIBC LIC Aztec** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [HIBCAztecPAS](../../aspose.barcode.generation/encodetypes/hibcaztecpas/) | 데이터를 **HIBC PAS Aztec** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [HIBCCode128LIC](../../aspose.barcode.generation/encodetypes/hibccode128lic/) | 데이터를 **HIBC LIC Code128** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [HIBCCode128PAS](../../aspose.barcode.generation/encodetypes/hibccode128pas/) | 데이터를 **HIBC PAS Code128** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [HIBCCode39LIC](../../aspose.barcode.generation/encodetypes/hibccode39lic/) | 데이터를 **HIBC LIC Code39** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [HIBCCode39PAS](../../aspose.barcode.generation/encodetypes/hibccode39pas/) | 데이터를 **HIBC PAS Code39** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.generation/encodetypes/hibcdatamatrixlic/) | 데이터를 **HIBC LIC DataMatrix** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.generation/encodetypes/hibcdatamatrixpas/) | 데이터를 **HIBC PAS DataMatrix** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [HIBCQRLIC](../../aspose.barcode.generation/encodetypes/hibcqrlic/) | 데이터를 **HIBC LIC QR** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [HIBCQRPAS](../../aspose.barcode.generation/encodetypes/hibcqrpas/) | 데이터를 **HIBC PAS QR** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [IATA2of5](../../aspose.barcode.generation/encodetypes/iata2of5/) | IATA 2 of 5 바코드를 나타냅니다. IATA(International Air Transport Association)는 항공 화물 관리를 위해 이 바코드를 사용합니다. |
| static readonly [Interleaved2of5](../../aspose.barcode.generation/encodetypes/interleaved2of5/) | 데이터를 **INTERLEAVED 2 of 5** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [ISBN](../../aspose.barcode.generation/encodetypes/isbn/) | 데이터를 **ISBN** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [ISMN](../../aspose.barcode.generation/encodetypes/ismn/) | 데이터를 **ISMN** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [ISSN](../../aspose.barcode.generation/encodetypes/issn/) | 데이터를 **ISSN** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [ItalianPost25](../../aspose.barcode.generation/encodetypes/italianpost25/) | Italian Post 25 바코드를 나타냅니다. |
| static readonly [ITF14](../../aspose.barcode.generation/encodetypes/itf14/) | 데이터를 **ITF14** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static readonly [ITF6](../../aspose.barcode.generation/encodetypes/itf6/) | ITF-6 바코드를 나타냅니다. |
| static readonly [JapanPost](../../aspose.barcode.generation/encodetypes/japanpost/) | 일본 우편 바코드를 나타냅니다 |
| static readonly [MacroPdf417](../../aspose.barcode.generation/encodetypes/macropdf417/) | 데이터를 **MacroPdf417** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [Mailmark](../../aspose.barcode.generation/encodetypes/mailmark/) | Royal Mail Mailmark 바코드를 나타냅니다. |
| static readonly [Matrix2of5](../../aspose.barcode.generation/encodetypes/matrix2of5/) | Matrix 2 of 5 바코드를 나타냅니다 |
| static readonly [MaxiCode](../../aspose.barcode.generation/encodetypes/maxicode/) | 데이터를 **MaxiCode** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [MicroPdf417](../../aspose.barcode.generation/encodetypes/micropdf417/) | 데이터를 **MicroPdf417** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [MicroQR](../../aspose.barcode.generation/encodetypes/microqr/) | 데이터를 **MicroQR Code** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [MSI](../../aspose.barcode.generation/encodetypes/msi/) | 데이터를 **MSI Plessey** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [None](../../aspose.barcode.generation/encodetypes/none/) | 지정되지 않은 인코드 유형입니다. |
| static readonly [OneCode](../../aspose.barcode.generation/encodetypes/onecode/) | 데이터를 USPS **OneCode** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [OPC](../../aspose.barcode.generation/encodetypes/opc/) | OPC(Optical Product Code) 바코드를 나타냅니다. 또한 VCA Barcode VCA OPC, Vision Council of America OPC 바코드로도 알려져 있습니다. |
| static readonly [PatchCode](../../aspose.barcode.generation/encodetypes/patchcode/) | Patch code 바코드를 나타냅니다 |
| static readonly [Pdf417](../../aspose.barcode.generation/encodetypes/pdf417/) | 데이터를 **Pdf417** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [Pharmacode](../../aspose.barcode.generation/encodetypes/pharmacode/) | Pharmacode 바코드를 나타냅니다. |
| static readonly [Planet](../../aspose.barcode.generation/encodetypes/planet/) | 데이터를 **Planet** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [Postnet](../../aspose.barcode.generation/encodetypes/postnet/) | 데이터를 **Postnet** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [PZN](../../aspose.barcode.generation/encodetypes/pzn/) | PZN 바코드를 나타냅니다. 이 기호는 Pharmacy central number, Pharmazentralnummer 로도 알려져 있습니다. PZN7 및 PZN8을 지원합니다. PZN7은 6자리 이하의 숫자로 생성되며, 예: "123456". PZN8은 7자리 이상의 숫자로 생성되며, 예: "1234567". 제공된 마지막 체크섬 숫자는 무시되고 바코드 엔진에 의해 생성됩니다. |
| static readonly [QR](../../aspose.barcode.generation/encodetypes/qr/) | 데이터를 **QR Code** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [RectMicroQR](../../aspose.barcode.generation/encodetypes/rectmicroqr/) | 데이터를 **RectMicroQR (rMQR) Code** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [RM4SCC](../../aspose.barcode.generation/encodetypes/rm4scc/) | RM4SCC 바코드를 나타냅니다. RM4SCC (Royal Mail 4-state Customer Code)는 영국의 자동 우편 분류 과정에 사용됩니다. |
| static readonly [SCC14](../../aspose.barcode.generation/encodetypes/scc14/) | 데이터를 **SCC14** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [SingaporePost](../../aspose.barcode.generation/encodetypes/singaporepost/) | 데이터를 **Singapore Post Barcode** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [SSCC18](../../aspose.barcode.generation/encodetypes/sscc18/) | 데이터를 **SSCC18** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [Standard2of5](../../aspose.barcode.generation/encodetypes/standard2of5/) | 데이터를 **Standard 2 of 5** 바코드 사양으로 인코딩해야 함을 지정합니다 |
| static readonly [SwissPostParcel](../../aspose.barcode.generation/encodetypes/swisspostparcel/) | 데이터를 **Swiss Post Parcel Barcode** 바코드 사양으로 인코딩해야 함을 지정합니다. 지원되는 유형: 국내 우편, 국제 우편, 추가 서비스 (new) |
| static readonly [UPCA](../../aspose.barcode.generation/encodetypes/upca/) | 데이터가 **UPC-A** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static readonly [UpcaGs1Code128Coupon](../../aspose.barcode.generation/encodetypes/upcags1code128coupon/) | 데이터가 **UPC coupon with GS1-128 Extended Code** 바코드 사양으로 인코딩되어야 함을 지정합니다. 입력 문자열의 예: BarcodeGenerator.Codetext = "514141100906(8102)03", 여기서 UPCA 부분은 "514141100906", GS1Code128 부분은 (8102)03. |
| static readonly [UpcaGs1DatabarCoupon](../../aspose.barcode.generation/encodetypes/upcags1databarcoupon/) | 데이터가 **UPC coupon with GS1 DataBar addition** 바코드 사양으로 인코딩되어야 함을 지정합니다. 입력 문자열의 예: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", 여기서 UPCA 부분은 "514141100906", Databar 부분은 "(8110)106141416543213500110000310123196000" 입니다. 캡션을 변경하려면 Parameters.CaptionAbove.Text = "company prefix + offer code"; 를 사용하십시오. |
| static readonly [UPCE](../../aspose.barcode.generation/encodetypes/upce/) | 데이터가 **UPC-E** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static readonly [VIN](../../aspose.barcode.generation/encodetypes/vin/) | VIN(차량 식별 번호) 바코드를 나타냅니다. |

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


