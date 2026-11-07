---
title: "Aspose::BarCode::Generation::EncodeTypes class"
linktitle: "EncodeTypes"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::EncodeTypes class. C++에서 인코딩할 바코드 유형을 지정합니다."
type: docs
weight: 2300
url: /ko/cpp/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class


인코딩할 바코드 유형을 지정합니다.

```cpp
class EncodeTypes
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [EncodeTypes](./encodetypes/)() |  |
| static [get_AllEncodeTypes](./get_allencodetypes/)() | 데이터가 사용 가능한 모든 심볼로 검증될 것임을 지정합니다. |
| static [GetNames](./getnames/)() | 인코드 유형 이름들의 배열을 반환합니다. |
| static [Parse](./parse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](../baseencodetype/)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | [BaseEncodeType](../baseencodetype/)의 문자열 표현을 해당 인스턴스로 변환합니다. 반환값은 변환이 성공했는지 실패했는지를 나타냅니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| static [AustralianPosteParcel](./australianposteparcel/) | 데이터를 **Australian Post Domestic eParcel Barcode** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [AustraliaPost](./australiapost/) | Australia Post 고객 [BarCode](../../aspose.barcode/)을 나타냅니다. |
| static [Aztec](./aztec/) | 데이터를 **Aztec** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [Codabar](./codabar/) | 데이터가 **CODABAR** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static [CodablockF](./codablockf/) | 데이터가 **Codablock-F** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [Code11](./code11/) | 데이터가 **CODE 11** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static [Code128](./code128/) | 데이터가 **CODE 128** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static [Code16K](./code16k/) | Code 16K 바코드를 나타냅니다. |
| static [Code32](./code32/) | 데이터가 **Code32** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static [Code39](./code39/) | 데이터가 **Code 39** 기본 문자 집합 바코드 사양으로 인코딩되어야 함을 지정합니다: ISO/IEC 16388 |
| static [Code39FullASCII](./code39fullascii/) | 데이터가 **Code 39** 전체 ASCII 문자 집합 바코드 사양으로 인코딩되어야 함을 지정합니다: ISO/IEC 16388 |
| static [Code93](./code93/) | 데이터가 **CODE 93** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static [DatabarExpanded](./databarexpanded/) | GS1 Databar 확장 바코드를 나타냅니다. |
| static [DatabarExpandedStacked](./databarexpandedstacked/) | GS1 Databar 확장 스택형 바코드를 나타냅니다. |
| static [DatabarLimited](./databarlimited/) | GS1 Databar 제한 바코드를 나타냅니다. |
| static [DatabarOmniDirectional](./databaromnidirectional/) | 데이터가 **GS1 Databar omni-directional** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [DatabarStacked](./databarstacked/) | GS1 Databar 스택형 바코드를 나타냅니다. |
| static [DatabarStackedOmniDirectional](./databarstackedomnidirectional/) | GS1 Databar 스택형 전방향 바코드를 나타냅니다. |
| static [DatabarTruncated](./databartruncated/) | 데이터가 **GS1 Databar truncated** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [DataLogic2of5](./datalogic2of5/) | 데이터가 **DataLogic 2 of 5** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static [DataMatrix](./datamatrix/) | 2D 바코드 심볼인 DataMatrix |
| static [DeutschePostIdentcode](./deutschepostidentcode/) | Deutsch Post 바코드를 나타냅니다, 이 심볼은 Identcode,CodeIdentcode,German Postal 2 of 5 Identcode, Deutsch Post AG Identcode, Deutsch Frachtpost Identcode, Deutsch Post AG (DHL) 로도 알려져 있습니다 |
| static [DeutschePostLeitcode](./deutschepostleitcode/) | Deutsch Post Leitcode 바코드를 나타냅니다, 또한 German Postal 2 of 5 Leitcode, CodeLeitcode, Leitcode, Deutsch Post AG (DHL) 로도 알려져 있습니다. |
| static [DotCode](./dotcode/) | 데이터가 **DotCode** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static [DutchKIX](./dutchkix/) | 데이터가 **Dutch KIX** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static [EAN13](./ean13/) | 데이터가 **EAN-13** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static [EAN14](./ean14/) | 데이터가 **EAN14** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static [EAN8](./ean8/) | 데이터가 **EAN-8** 바코드 사양으로 인코딩되어야 함을 지정합니다 |
| static [GS1Aztec](./gs1aztec/) | 데이터가 **GS1 Aztec** 바코드 사양으로 인코딩되어야 함을 지정합니다. 코덱스트는 AI를 위해 괄호를 포함해야 합니다. |
| static [GS1CodablockF](./gs1codablockf/) | 데이터가 **GS1 Codablock-F** 바코드 사양으로 인코딩되어야 함을 지정합니다. 코덱스트는 AI를 위해 괄호를 포함해야 합니다. |
| static [GS1Code128](./gs1code128/) | 데이터가 **GS1 Code 128** 바코드 사양으로 인코딩되어야 함을 지정합니다. 코덱스트는 AI를 위해 괄호를 포함해야 합니다. |
| static [GS1CompositeBar](./gs1compositebar/) | 데이터가 **GS1 Composite Bar** 바코드 사양으로 인코딩되어야 함을 지정합니다. 코덱스트는 AI를 위해 괄호를 포함해야 합니다. 1D 코덱스트와 2D 코덱스트는 '/' 기호로 구분되어야 합니다. |
| static [GS1DataMatrix](./gs1datamatrix/) | GS1 문자열 형식이 적용된 2D 바코드 심볼 DataMatrix |
| static [GS1DotCode](./gs1dotcode/) | 데이터가 **GS1 DotCode** 바코드 사양으로 인코딩되어야 함을 지정합니다. 코덱스트는 AI를 위해 괄호를 포함해야 합니다. |
| static [GS1HanXin](./gs1hanxin/) | GS1 문자열 형식이 적용된 2D 바코드 심볼 HanXin |
| static [GS1MicroPdf417](./gs1micropdf417/) | 데이터가 **GS1MicroPdf417** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [GS1QR](./gs1qr/) | GS1 문자열 형식이 적용된 2D 바코드 심볼 QR |
| static [HanXin](./hanxin/) | 데이터가 **Han Xin** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [HIBCAztecLIC](./hibcazteclic/) | 데이터가 **HIBC LIC Aztec** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [HIBCAztecPAS](./hibcaztecpas/) | 데이터가 **HIBC PAS Aztec** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [HIBCCode128LIC](./hibccode128lic/) | 데이터가 **HIBC LIC Code128** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [HIBCCode128PAS](./hibccode128pas/) | 데이터가 **HIBC PAS Code128** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [HIBCCode39LIC](./hibccode39lic/) | 데이터가 **HIBC LIC Code39** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [HIBCCode39PAS](./hibccode39pas/) | 데이터가 **HIBC PAS Code39** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [HIBCDataMatrixLIC](./hibcdatamatrixlic/) | 데이터가 **HIBC LIC DataMatrix** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [HIBCDataMatrixPAS](./hibcdatamatrixpas/) | 데이터가 **HIBC PAS DataMatrix** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [HIBCQRLIC](./hibcqrlic/) | 데이터가 **HIBC LIC QR** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [HIBCQRPAS](./hibcqrpas/) | 데이터가 **HIBC PAS QR** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [IATA2of5](./iata2of5/) | IATA 2 of 5 바코드를 나타냅니다. IATA(International Air Transport Association)는 이 바코드를 항공 화물 관리에 사용합니다. |
| static [Interleaved2of5](./interleaved2of5/) | 데이터가 **INTERLEAVED 2 of 5** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [ISBN](./isbn/) | 데이터가 **ISBN** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [ISMN](./ismn/) | 데이터가 **ISMN** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [ISSN](./issn/) | 데이터가 **ISSN** 바코드 사양으로 인코딩되어야 함을 지정합니다. |
| static [ItalianPost25](./italianpost25/) | Italian Post 25 바코드를 나타냅니다. |
| static [ITF14](./itf14/) | 데이터를 **ITF14** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [ITF6](./itf6/) | ITF-6 바코드를 나타냅니다. |
| static [JapanPost](./japanpost/) | Japan Post [BarCode](../../aspose.barcode/)을(를) 나타냅니다. |
| static [MacroPdf417](./macropdf417/) | 데이터를 **MacroPdf417** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [Mailmark](./mailmark/) | Royal Mail Mailmark 바코드를 나타냅니다. |
| static [Matrix2of5](./matrix2of5/) | Matrix 2 of 5 [BarCode](../../aspose.barcode/)을(를) 나타냅니다. |
| static [MaxiCode](./maxicode/) | 데이터를 **MaxiCode** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [MicroPdf417](./micropdf417/) | 데이터를 **MicroPdf417** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [MicroQR](./microqr/) | 데이터를 **MicroQR Code** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [MSI](./msi/) | 데이터를 **MSI Plessey** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [None](./none/) | 인코드 유형이 지정되지 않음. |
| static [OneCode](./onecode/) | 데이터를 USPS **OneCode** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [OPC](./opc/) | OPC(Optical Product Code) 바코드를 나타냅니다. 또한 VCA Barcode VCA OPC, Vision Council of America OPC Barcode 로도 알려져 있습니다. |
| static [PatchCode](./patchcode/) | Patch code 바코드를 나타냅니다. |
| static [Pdf417](./pdf417/) | 데이터를 **Pdf417** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [Pharmacode](./pharmacode/) | Pharmacode 바코드를 나타냅니다. |
| static [Planet](./planet/) | 데이터를 **Planet** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [Postnet](./postnet/) | 데이터를 **Postnet** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [PZN](./pzn/) | PZN 바코드를 나타냅니다. 이 기호는 Pharmacy central number, Pharmazentralnummer 로도 알려져 있습니다. PZN7 및 PZN8을 지원합니다. PZN7은 6자리 이하(예: "123456")에서 생성됩니다. PZN8은 7자리 이상(예: "1234567")에서 생성됩니다. 제공된 마지막 체크섬 숫자는 무시되고 바코드 엔진에 의해 생성됩니다. |
| static [QR](./qr/) | 데이터를 **QR Code** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [RectMicroQR](./rectmicroqr/) | 데이터를 **RectMicroQR (rMQR) Code** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [RM4SCC](./rm4scc/) | RM4SCC 바코드를 나타냅니다. RM4SCC (Royal Mail 4-state Customer Code)는 영국의 자동 우편 분류 프로세스에 사용됩니다. |
| static [SCC14](./scc14/) | 데이터를 **SCC14** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [SingaporePost](./singaporepost/) | 데이터를 **Singapore Post Barcode** 바코드 사양으로 인코딩해야 함을 지정합니다. |
| static [SSCC18](./sscc18/) | 데이터가 **SSCC18** 바코드 사양으로 인코딩되도록 지정합니다 |
| static [Standard2of5](./standard2of5/) | 데이터가 **Standard 2 of 5** 바코드 사양으로 인코딩되도록 지정합니다 |
| static [SwissPostParcel](./swisspostparcel/) | 데이터가 **Swiss Post Parcel Barcode** 바코드 사양으로 인코딩되도록 지정합니다. 지원되는 유형: 국내 우편, 국제 우편, 추가 서비스 (새로운) |
| static [UPCA](./upca/) | 데이터가 **UPC-A** 바코드 사양으로 인코딩되도록 지정합니다 |
| static [UpcaGs1Code128Coupon](./upcags1code128coupon/) | 데이터가 **UPC coupon with GS1-128 Extended Code** 바코드 사양으로 인코딩되도록 지정합니다. 입력 문자열 예시: BarcodeGenerator.Codetext = \"514141100906(8102)03\", 여기서 UPCA 부분은 \"514141100906\", GS1Code128 부분은 (8102)03입니다. |
| static [UpcaGs1DatabarCoupon](./upcags1databarcoupon/) | 데이터가 **UPC coupon with GS1 DataBar addition** 바코드 사양으로 인코딩되도록 지정합니다. 입력 문자열 예시: BarcodeGenerator.Codetext = \"514141100906(8110)106141416543213500110000310123196000\", 여기서 UPCA 부분은 \"514141100906\", Databar 부분은 \"(8110)106141416543213500110000310123196000\"입니다. 캡션을 변경하려면 Parameters.CaptionAbove.Text = \"company prefix + offer code\"; 를 사용하십시오. |
| static [UPCE](./upce/) | 데이터가 **UPC-E** 바코드 사양으로 인코딩되도록 지정합니다 |
| static [VIN](./vin/) | VIN(차량 식별 번호) 바코드를 나타냅니다. |
## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
