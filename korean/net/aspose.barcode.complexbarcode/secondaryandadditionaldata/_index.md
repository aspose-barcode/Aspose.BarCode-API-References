---
title: "Class SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.SecondaryAndAdditionalData 클래스. HIBC LIC 보조 및 추가 데이터를 저장하기 위한 클래스입니다."
type: docs
weight: 770
url: /ko/net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

HIBC LIC 보조 및 추가 데이터를 저장하기 위한 클래스입니다.

```csharp
public class SecondaryAndAdditionalData
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | 제조일자를 식별합니다. 제조일자는 이 필드를 사용하지 않으려면 DateTime.MinValue로 설정할 수 있습니다. 기본값: DateTime.MinValue. |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | 만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우 사용됩니다. |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | 만료 날짜 형식을 식별합니다. |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | Lot 또는 batch 번호를 식별합니다. Lot/배치 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | 수량을 식별합니다. 0에서 500 사이의 정수값이어야 합니다. 이 필드를 사용하지 않으려면 수량을 -1로 설정할 수 있습니다. 기본값: -1 |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | 시리얼 번호를 식별합니다. 시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | 이 인스턴스가 지정된 `SecondaryAndAdditionalData` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | HIBC LIC 사양에 따라 문자열 형식에서 보조 및 추가 보충 데이터를 인스턴스화합니다. |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | 데이터를 HIBC LIC 사양에 따라 문자열 형식으로 변환합니다. |

### 또 보기

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


