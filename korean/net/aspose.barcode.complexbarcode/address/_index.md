---
title: "클래스 Address"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.Address 클래스. 채권자 또는 채무자의 주소"
type: docs
weight: 480
url: /ko/net/aspose.barcode.complexbarcode/address/
---
## Address class

채권자 또는 채무자의 주소.

거리, 건물 번호, 우편 번호 및 도시(구조화된 주소 유형)를 설정하거나 주소 라인 1 및 2(결합된 주소 요소 유형)를 설정할 수 있습니다. 이러한 필드 중 하나가 설정되면 유형이 자동으로 지정됩니다. 필드를 설정하기 전에는 주소 유형이 미정입니다. 두 유형의 필드가 모두 설정되면 주소 유형이 충돌하게 됩니다. 모든 필드가 비어 있지 않은 한 이름과 국가 코드는 항상 설정되어야 합니다.

```csharp
public sealed class Address : IEquatable<Address>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Address](address/)() | Address 인스턴스를 생성합니다 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1/) { get; set; } | 주소 라인 1을 가져오거나 설정합니다. |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2/) { get; set; } | 주소 라인 2를 가져오거나 설정합니다. |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode/) { get; set; } | 두 글자 ISO 국가 코드를 가져오거나 설정합니다. |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno/) { get; set; } | 건물 번호를 가져오거나 설정합니다. |
| [Name](../../aspose.barcode.complexbarcode/address/name/) { get; set; } | 자연인의 이름(성 및 이름) 또는 법인의 회사명을 가져오거나 설정합니다. |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode/) { get; set; } | 우편 코드를 가져오거나 설정합니다. |
| [Street](../../aspose.barcode.complexbarcode/address/street/) { get; set; } | 거리를 가져오거나 설정합니다. |
| [Town](../../aspose.barcode.complexbarcode/address/town/) { get; set; } | 도시 또는 읍을 가져오거나 설정합니다. |
| [Type](../../aspose.barcode.complexbarcode/address/type/) { get; } | 주소 유형을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear/)() | 모든 필드를 지우고 유형을 미정으로 설정합니다. |
| [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals)(Address) | 지정된 주소가 현재 주소와 같은지 여부를 판단합니다. |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals_1)(object) | 지정된 객체가 현재 객체와 동일한지 확인합니다. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode/)() | 이 인스턴스의 해시 코드를 가져옵니다. |

### 또 보기

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


