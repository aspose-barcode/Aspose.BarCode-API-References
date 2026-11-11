---
title: "클래스 USADriveIdCodetext"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetext 클래스. 미국 운전 면허 PDF417 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스"
type: docs
weight: 810
url: /ko/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

USA 운전 면허 PDF417 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스입니다.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | AAMVA 버전 번호 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | 이 번호는 발행 관할 구역을 고유하게 식별하며 ISO 발행 기관(AAMVA)에 문의하여 얻을 수 있습니다. 전체 6자리 IIN을 인코딩해야 합니다. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | 관할 구역별 필드 |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | 관할 구역 버전 번호 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | 카드의 필수 요소 (필드) |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | 하위 파일 번호 00-99 |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | 카드의 선택적 요소(필드) |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | 다음 하위 파일, 유형, 오프셋 및 길이에 대한 정보를 포함합니다. 중요: 유형만 설정하면 오프셋과 길이는 자동으로 설정됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | USA DL(Pdf417)의 바코드 유형을 반환합니다 |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | USA DL 데이터에서 코드텍스트를 구성합니다 |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | 코드텍스트에서 USA DL 객체를 초기화합니다 |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | XML에 저장 |

## 다른 멤버

| 이름 | 설명 |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | 카드의 필수 요소 (필드) |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | 카드의 선택적 요소(필드) |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | USA DL 서브파일 속성, 오프셋 및 길이는 자동으로 설정됩니다. |

### 또 보기

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


