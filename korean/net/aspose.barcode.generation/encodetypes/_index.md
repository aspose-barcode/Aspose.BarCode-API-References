---
title: EncodeTypes
second_title: .NET API 참조용 Aspose.BarCode
description: 인코딩할 바코드 유형을 지정합니다.
type: docs
weight: 950
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
| static [AllEncodeTypes](../../aspose.barcode.generation/encodetypes/allencodetypes/) { get; } | 사용 가능한 모든 기호로 데이터를 확인하도록 지정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [GetNames](../../aspose.barcode.generation/encodetypes/getnames/)() | 인코딩 유형의 이름 배열을 검색합니다. |
| static [Parse](../../aspose.barcode.generation/encodetypes/parse/)(string, out BaseEncodeType) | BaseEncodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환의 성공 또는 실패 여부를 나타냅니다. |
| static [TryParse](../../aspose.barcode.generation/encodetypes/tryparse/)(string, out BaseEncodeType) | BaseEncodeType의 문자열 표현을 해당 인스턴스로 변환합니다. 반환 값은 변환의 성공 또는 실패 여부를 나타냅니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [AustralianPosteParcel](../../aspose.barcode.generation/encodetypes/australianposteparcel/) | 데이터가 인코딩되어야 함을 지정합니다. **호주 우체국 국내 전자소포 바코드** 바코드 사양 |
| static readonly [AustraliaPost](../../aspose.barcode.generation/encodetypes/australiapost/) | 는 Australia Post 고객 BarCode 를 나타냅니다. |
| static readonly [Aztec](../../aspose.barcode.generation/encodetypes/aztec/) | 데이터가 인코딩되어야 함을 지정합니다. **아즈텍** 바코드 사양 |
| static readonly [Codabar](../../aspose.barcode.generation/encodetypes/codabar/) | 데이터가 인코딩되어야 함을 지정합니다. **코다바** 바코드 사양 |
| static readonly [CodablockF](../../aspose.barcode.generation/encodetypes/codablockf/) | 데이터가 인코딩되어야 함을 지정합니다. **코다블럭-F** 바코드 사양. |
| static readonly [Code11](../../aspose.barcode.generation/encodetypes/code11/) | 데이터가 인코딩되어야 함을 지정합니다. **코드 11** 바코드 사양 |
| static readonly [Code128](../../aspose.barcode.generation/encodetypes/code128/) | 데이터가 인코딩되어야 함을 지정합니다. **코드 128** 바코드 사양 |
| static readonly [Code16K](../../aspose.barcode.generation/encodetypes/code16k/) | 는 코드 16K 바코드를 나타냅니다. |
| static readonly [Code32](../../aspose.barcode.generation/encodetypes/code32/) | 데이터가 인코딩되어야 함을 지정합니다. **코드32** 바코드 사양 |
| static readonly [Code39Extended](../../aspose.barcode.generation/encodetypes/code39extended/) | 데이터가 인코딩되어야 함을 지정합니다. **확장 코드 39** 바코드 사양 |
| static readonly [Code39Standard](../../aspose.barcode.generation/encodetypes/code39standard/) | 데이터가 인코딩되어야 함을 지정합니다. **표준 코드 39** 바코드 사양 |
| static readonly [Code93Extended](../../aspose.barcode.generation/encodetypes/code93extended/) | 데이터가 인코딩되어야 함을 지정합니다. **확장 코드 93** 바코드 사양 |
| static readonly [Code93Standard](../../aspose.barcode.generation/encodetypes/code93standard/) | 데이터가 인코딩되어야 함을 지정합니다. **표준 코드 93** 바코드 사양 |
| static readonly [DatabarExpanded](../../aspose.barcode.generation/encodetypes/databarexpanded/) | GS1 Databar 확장 바코드를 나타냅니다. |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.generation/encodetypes/databarexpandedstacked/) | GS1 Databar 확장 스택 바코드를 나타냅니다. |
| static readonly [DatabarLimited](../../aspose.barcode.generation/encodetypes/databarlimited/) | GS1 Databar 제한 바코드를 나타냅니다. |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.generation/encodetypes/databaromnidirectional/) | 데이터가 인코딩되어야 함을 지정합니다. **GS1 Databar 전방향성** 바코드 사양. |
| static readonly [DatabarStacked](../../aspose.barcode.generation/encodetypes/databarstacked/) | GS1 Databar 스택 바코드를 나타냅니다. |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.generation/encodetypes/databarstackedomnidirectional/) | GS1 Databar 누적 전방향 바코드를 나타냅니다. |
| static readonly [DatabarTruncated](../../aspose.barcode.generation/encodetypes/databartruncated/) | 데이터가 인코딩되어야 함을 지정합니다. **GS1 데이터바 잘림** 바코드 사양. |
| static readonly [DataLogic2of5](../../aspose.barcode.generation/encodetypes/datalogic2of5/) | 데이터가 인코딩되어야 함을 지정합니다. **데이터로직 2/5** 바코드 사양 |
| static readonly [DataMatrix](../../aspose.barcode.generation/encodetypes/datamatrix/) | 2D 바코드 기호 DataMatrix |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.generation/encodetypes/deutschepostidentcode/) | Deutsch Post 바코드를 나타냅니다. 이 기호는 Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG(DHL) 라고도 합니다. |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.generation/encodetypes/deutschepostleitcode/) | 독일 우편 2/5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG(DHL)로도 알려진 Deutsch Post Leitcode 바코드를 나타냅니다. |
| static readonly [DotCode](../../aspose.barcode.generation/encodetypes/dotcode/) | 데이터가 인코딩되어야 함을 지정합니다. **도트코드** 바코드 사양 |
| static readonly [DutchKIX](../../aspose.barcode.generation/encodetypes/dutchkix/) | 데이터가 인코딩되어야 함을 지정합니다. **네덜란드 KIX** 바코드 사양 |
| static readonly [EAN13](../../aspose.barcode.generation/encodetypes/ean13/) | 데이터가 인코딩되어야 함을 지정합니다. **EAN-13** 바코드 사양 |
| static readonly [EAN14](../../aspose.barcode.generation/encodetypes/ean14/) | 데이터가 인코딩되어야 함을 지정합니다. **EAN14** 바코드 사양 |
| static readonly [EAN8](../../aspose.barcode.generation/encodetypes/ean8/) | 데이터가 인코딩되어야 함을 지정합니다. **EAN-8** 바코드 사양 |
| static readonly [GS1CodablockF](../../aspose.barcode.generation/encodetypes/gs1codablockf/) | 데이터가 인코딩되어야 함을 지정합니다. **GS1 코다블록-F** 바코드 사양. 코드 텍스트에는 AI. 에 대한 괄호가 포함되어야 합니다. |
| static readonly [GS1Code128](../../aspose.barcode.generation/encodetypes/gs1code128/) | 데이터가 인코딩되어야 함을 지정합니다. **GS1 코드 128** 바코드 사양. 코드 텍스트에는 AI. 에 대한 괄호가 포함되어야 합니다. |
| static readonly [GS1CompositeBar](../../aspose.barcode.generation/encodetypes/gs1compositebar/) | 데이터가 인코딩되어야 함을 지정합니다. **GS1 합성 바** 바코드 사양. 코드 텍스트에는 AI에 대한 괄호가 포함되어야 합니다. 1D 코드텍스트와 2D 코드텍스트는 '/' 기호로 구분해야 합니다. |
| static readonly [GS1DataMatrix](../../aspose.barcode.generation/encodetypes/gs1datamatrix/) | 2D 바코드 기호 DataMatrix with GS1 문자열 format |
| static readonly [GS1DotCode](../../aspose.barcode.generation/encodetypes/gs1dotcode/) | 데이터가 인코딩되어야 함을 지정합니다. **GS1 도트코드** 바코드 사양. 코드 텍스트에는 AI. 에 대한 괄호가 포함되어야 합니다. |
| static readonly [GS1QR](../../aspose.barcode.generation/encodetypes/gs1qr/) | GS1 문자열이 포함된 2D 바코드 심볼로지 QR format |
| static readonly [HIBCAztecLIC](../../aspose.barcode.generation/encodetypes/hibcazteclic/) | 데이터가 인코딩되어야 함을 지정합니다. **HIBC LIC 아즈텍** 바코드 사양. |
| static readonly [HIBCAztecPAS](../../aspose.barcode.generation/encodetypes/hibcaztecpas/) | 데이터가 인코딩되어야 함을 지정합니다. **HIBC PAS 아즈텍** 바코드 사양. |
| static readonly [HIBCCode128LIC](../../aspose.barcode.generation/encodetypes/hibccode128lic/) | 데이터가 인코딩되어야 함을 지정합니다. **HIBC LIC 코드128** 바코드 사양. |
| static readonly [HIBCCode128PAS](../../aspose.barcode.generation/encodetypes/hibccode128pas/) | 데이터가 인코딩되어야 함을 지정합니다. **HIBC PAS 코드128** 바코드 사양. |
| static readonly [HIBCCode39LIC](../../aspose.barcode.generation/encodetypes/hibccode39lic/) | 데이터가 인코딩되어야 함을 지정합니다. **HIBC LIC Code39표준** 바코드 사양. |
| static readonly [HIBCCode39PAS](../../aspose.barcode.generation/encodetypes/hibccode39pas/) | 데이터가 인코딩되어야 함을 지정합니다. **HIBC PAS Code39표준** 바코드 사양. |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.generation/encodetypes/hibcdatamatrixlic/) | 데이터가 인코딩되어야 함을 지정합니다. **HIBC LIC 데이터매트릭스** 바코드 사양. |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.generation/encodetypes/hibcdatamatrixpas/) | 데이터가 인코딩되어야 함을 지정합니다. **HIBC PAS 데이터매트릭스** 바코드 사양. |
| static readonly [HIBCQRLIC](../../aspose.barcode.generation/encodetypes/hibcqrlic/) | 데이터가 인코딩되어야 함을 지정합니다. **HIBC LIC QR** 바코드 사양. |
| static readonly [HIBCQRPAS](../../aspose.barcode.generation/encodetypes/hibcqrpas/) | 데이터가 인코딩되어야 함을 지정합니다. **HIBC PAS QR** 바코드 사양. |
| static readonly [IATA2of5](../../aspose.barcode.generation/encodetypes/iata2of5/) | IATA 2 of 5 바코드를 나타냅니다.IATA(국제 항공 운송 협회)는 항공 화물 관리에 이 바코드를 사용합니다. |
| static readonly [Interleaved2of5](../../aspose.barcode.generation/encodetypes/interleaved2of5/) | 데이터가 인코딩되어야 함을 지정합니다. **인터리브 2/5** 바코드 사양 |
| static readonly [ISBN](../../aspose.barcode.generation/encodetypes/isbn/) | 데이터가 인코딩되어야 함을 지정합니다. **ISBN** 바코드 사양 |
| static readonly [ISMN](../../aspose.barcode.generation/encodetypes/ismn/) | 데이터가 인코딩되어야 함을 지정합니다. **ISMN** 바코드 사양 |
| static readonly [ISSN](../../aspose.barcode.generation/encodetypes/issn/) | 데이터가 인코딩되어야 함을 지정합니다. **ISSN** 바코드 사양 |
| static readonly [ItalianPost25](../../aspose.barcode.generation/encodetypes/italianpost25/) | 이탈리아 우편 25 바코드를 나타냅니다. |
| static readonly [ITF14](../../aspose.barcode.generation/encodetypes/itf14/) | 데이터가 인코딩되어야 함을 지정합니다. **ITF14** 바코드 사양 |
| static readonly [ITF6](../../aspose.barcode.generation/encodetypes/itf6/) | 는 ITF-6 바코드를 나타냅니다. |
| static readonly [MacroPdf417](../../aspose.barcode.generation/encodetypes/macropdf417/) | 데이터가 인코딩되어야 함을 지정합니다. **매크로Pdf417** 바코드 사양 |
| static readonly [Mailmark](../../aspose.barcode.generation/encodetypes/mailmark/) | Royal Mail Mailmark 바코드를 나타냅니다. |
| static readonly [Matrix2of5](../../aspose.barcode.generation/encodetypes/matrix2of5/) | 는 BarCode 5개 중 매트릭스 2를 나타냅니다. |
| static readonly [MaxiCode](../../aspose.barcode.generation/encodetypes/maxicode/) | 데이터가 인코딩되어야 함을 지정합니다. **맥시코드** 바코드 사양 |
| static readonly [MicroPdf417](../../aspose.barcode.generation/encodetypes/micropdf417/) | 데이터가 인코딩되어야 함을 지정합니다. **마이크로 PDF417** 바코드 사양 |
| static readonly [MSI](../../aspose.barcode.generation/encodetypes/msi/) | 데이터가 인코딩되어야 함을 지정합니다. **MSI 플레시** 바코드 사양 |
| static readonly [None](../../aspose.barcode.generation/encodetypes/none/) | 지정되지 않은 인코딩 유형입니다. |
| static readonly [OneCode](../../aspose.barcode.generation/encodetypes/onecode/) | 데이터가 USPS로 인코딩되어야 함을 지정합니다. **원코드** 바코드 사양 |
| static readonly [OPC](../../aspose.barcode.generation/encodetypes/opc/) | VCA 바코드 VCA OPC, Vision Council of America OPC 바코드로도 알려진 OPC(광 제품 코드) 바코드를 나타냅니다. |
| static readonly [PatchCode](../../aspose.barcode.generation/encodetypes/patchcode/) | 는 패치 코드 barcode 를 나타냅니다. |
| static readonly [Pdf417](../../aspose.barcode.generation/encodetypes/pdf417/) | 데이터가 인코딩되어야 함을 지정합니다. **PDF417** 바코드 사양 |
| static readonly [Pharmacode](../../aspose.barcode.generation/encodetypes/pharmacode/) | Pharmacode 바코드를 나타냅니다. |
| static readonly [Planet](../../aspose.barcode.generation/encodetypes/planet/) | 데이터가 인코딩되어야 함을 지정합니다. **행성** 바코드 사양 |
| static readonly [Postnet](../../aspose.barcode.generation/encodetypes/postnet/) | 데이터가 인코딩되어야 함을 지정합니다. **포스트넷** 바코드 사양 |
| static readonly [PZN](../../aspose.barcode.generation/encodetypes/pzn/) | PZN 바코드를 나타냅니다. 이 기호는 약국 중심 번호인 Pharmazentralnummer 라고도 합니다. |
| static readonly [QR](../../aspose.barcode.generation/encodetypes/qr/) | 데이터가 인코딩되어야 함을 지정합니다. **QR 코드** 바코드 사양 |
| static readonly [RM4SCC](../../aspose.barcode.generation/encodetypes/rm4scc/) | RM4SCC 바코드를 나타냅니다. RM4SCC(Royal Mail 4-state Customer Code)는 영국에서 자동화된 메일 정렬 프로세스에 사용됩니다. |
| static readonly [SCC14](../../aspose.barcode.generation/encodetypes/scc14/) | 데이터가 인코딩되어야 함을 지정합니다. **SCC14** 바코드 사양 |
| static readonly [SingaporePost](../../aspose.barcode.generation/encodetypes/singaporepost/) | 데이터가 인코딩되어야 함을 지정합니다. **싱가포르 포스트 바코드** 바코드 사양 |
| static readonly [SSCC18](../../aspose.barcode.generation/encodetypes/sscc18/) | 데이터가 인코딩되어야 함을 지정합니다. **SSCC18** 바코드 사양 |
| static readonly [Standard2of5](../../aspose.barcode.generation/encodetypes/standard2of5/) | 데이터가 인코딩되어야 함을 지정합니다. **표준 2/5** 바코드 사양 |
| static readonly [SwissPostParcel](../../aspose.barcode.generation/encodetypes/swisspostparcel/) | 데이터가 인코딩되어야 함을 지정합니다. **스위스 우편 소포 바코드**바코드 사양. 지원종류 : 국내우편, 국제우편, 부가서비스(신규) |
| static readonly [UPCA](../../aspose.barcode.generation/encodetypes/upca/) | 데이터가 인코딩되어야 함을 지정합니다. **UPC-A** 바코드 사양 |
| static readonly [UpcaGs1Code128Coupon](../../aspose.barcode.generation/encodetypes/upcags1code128coupon/) | 데이터가 인코딩되어야 함을 지정합니다. **GS1-128 확장 코드가 포함된 UPC 쿠폰** 바코드 사양. 입력 문자열의 예: BarcodeGenerator.Codetext = "514141100906(8102)03", 여기서 UPCA 부분은 "514141100906", GS1Code128 부분은 (8102)03입니다. |
| static readonly [UpcaGs1DatabarCoupon](../../aspose.barcode.generation/encodetypes/upcags1databarcoupon/) | 데이터가 인코딩되어야 함을 지정합니다. **GS1 DataBar가 추가된 UPC 쿠폰**barcode specification. An example of the input string: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", where UPCA part is "514141100906", Databar part is "(8110)106141416543213500110000310123196000". To change the caption, use Parameters.CaptionAbove.Text = "회사 접두사 + 제안 코드"; |
| static readonly [UPCE](../../aspose.barcode.generation/encodetypes/upce/) | 데이터가 인코딩되어야 함을 지정합니다. **UPC-E** 바코드 사양 |
| static readonly [VIN](../../aspose.barcode.generation/encodetypes/vin/) | VIN(차량 식별 번호) 바코드를 나타냅니다. |

### 또한보십시오

* 네임스페이스 [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* 집회 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
