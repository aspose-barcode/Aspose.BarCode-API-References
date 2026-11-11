---
title: "클래스 MailmarkCodetext"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.MailmarkCodetext 클래스. 4state Royal Mailmark 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스"
type: docs
weight: 670
url: /ko/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

4단계 Royal Mailmark 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스입니다.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | "0" - Null 또는 테스트 "1" - 1C (소매) "2" - 2C (소매) "3" - 3C (소매) "4" - 프리미엄 (RetailPublishing 메일) (잠재적 향후 사용을 위해) "5" - 연기 (소매) "6" - 항공 (소매) (잠재적 향후 사용을 위해) "7" - 지상 (소매) (잠재적 향후 사용을 위해) "8" - 프리미엄 (네트워크 액세스) "9" - 표준 (네트워크 액세스) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | PC와 DP는 PAF 형식을 따라야 합니다. 국제 "XY11 "을 나타내는 9자 문자열(뒤에 공백 5개 포함) 또는 국내 정렬 코드를 나타내는 문자 패턴입니다. 국내 정렬 코드는 외부 우편번호, 내부 우편번호 및 Delivery Point Suffix로 구성됩니다. |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | "0" – Null 또는 테스트 "1" – 편지 "2" – 대형 편지 |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | 최대값은 99999999입니다. |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | Barcode C의 최대값은 99이고 Barcode L의 최대값은 999999입니다. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | 현재 "1" – Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 예약됨) |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | 바코드 유형을 가져옵니다. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | Mailmark 데이터에서 코드텍스트를 구성합니다. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | 구성된 코드텍스트에서 Mailmark 데이터를 초기화합니다. |

### 또 보기

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


