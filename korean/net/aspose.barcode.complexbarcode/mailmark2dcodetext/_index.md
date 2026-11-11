---
title: "클래스 Mailmark2DCodetext"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.Mailmark2DCodetext 클래스. Royal Mail 2D Mailmark 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스"
type: docs
weight: 650
url: /ko/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Royal Mail 2D Mailmark 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스입니다.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class/) { get; set; } | 항목의 클래스를 식별합니다. |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent/) { get; set; } | 고객이 사용할 수 있는 선택적 공간입니다. |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode/) { get; set; } | Datamatrix 바코드의 인코드 모드입니다. 기본값: EncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype/) { get; set; } | 2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다. |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps/) { get; set; } | 배송 주소의 우편번호와 DPS를 포함합니다. 내륙인 경우 우편번호/DP는 다음과 같은 문자 수를 포함합니다. 지역(1~2자) 구역(1~2자) 섹터(1자) 유닛(2자) DPS(2자). 우편번호와 DPS는 유효한 PAF® 형식에 맞아야 합니다. |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid/) { get; set; } | 각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다. |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid/) { get; set; } | 공급망 ID 내에서 고유 항목을 식별합니다. 모든 Mailmark 바코드에는 최소 90일 동안 고유하게 식별될 수 있도록 ID가 포함되어야 합니다. 최대값: 99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode/) { get; set; } | 반송 수신자 우편번호를 포함하지만 DPS는 포함하지 않습니다. DPS가 없는 우편번호(PC)는 PAF® 형식에 맞아야 합니다. |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag/) { get; set; } | 요청된 반송 서비스 수준을 나타내는 플래그입니다. |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid/) { get; set; } | 메일링에 참여하는 고유 고객 그룹을 식별합니다. 최대값: 9999999. |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid/) { get; set; } | UPU 국가 ID를 식별합니다. 최대 길이: 4자. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid/) { get; set; } | 각 정보 유형 ID와 관련된 바코드 버전을 식별합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype/)() | 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext/)() | Mailmark 데이터에서 코드텍스트를 구성합니다. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring/)(string) | 구성된 코드텍스트에서 Mailmark 데이터를 초기화합니다. |

### 또 보기

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


