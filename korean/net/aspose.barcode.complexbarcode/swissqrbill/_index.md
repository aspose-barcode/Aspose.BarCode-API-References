---
title: "클래스 SwissQRBill"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.SwissQRBill 클래스. SwissQR 청구서 데이터"
type: docs
weight: 780
url: /ko/net/aspose.barcode.complexbarcode/swissqrbill/
---
## SwissQRBill class

SwissQR 청구서 데이터

```csharp
public sealed class SwissQRBill : IEquatable<SwissQRBill>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Account](../../aspose.barcode.complexbarcode/swissqrbill/account/) { get; set; } | 채권자의 계좌 번호를 가져오거나 설정합니다. |
| [AlternativeSchemes](../../aspose.barcode.complexbarcode/swissqrbill/alternativeschemes/) { get; set; } | 대체 결제 방식을 가져오거나 설정합니다. |
| [Amount](../../aspose.barcode.complexbarcode/swissqrbill/amount/) { get; set; } | 결제 금액을 가져오거나 설정합니다. |
| [BillInformation](../../aspose.barcode.complexbarcode/swissqrbill/billinformation/) { get; set; } | 추가 구조화된 청구서 정보를 가져오거나 설정합니다. |
| [Creditor](../../aspose.barcode.complexbarcode/swissqrbill/creditor/) { get; set; } | 채권자 주소를 가져오거나 설정합니다. |
| [Currency](../../aspose.barcode.complexbarcode/swissqrbill/currency/) { get; set; } | 결제 통화를 가져오거나 설정합니다. |
| [Debtor](../../aspose.barcode.complexbarcode/swissqrbill/debtor/) { get; set; } | 채무자 주소를 가져오거나 설정합니다. |
| [Reference](../../aspose.barcode.complexbarcode/swissqrbill/reference/) { get; set; } | 채권자 결제 참조를 가져오거나 설정합니다. |
| [UnstructuredMessage](../../aspose.barcode.complexbarcode/swissqrbill/unstructuredmessage/) { get; set; } | 추가 비구조화 메시지를 가져오거나 설정합니다. |
| [Version](../../aspose.barcode.complexbarcode/swissqrbill/version/) { get; set; } | SwissQR 청구서 표준 버전을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CreateAndSetCreditorReference](../../aspose.barcode.complexbarcode/swissqrbill/createandsetcreditorreference/)(string) | 문자열 앞에 \"RF\"를 붙이고 modulo 97 체크섬을 적용하여 원시 문자열에서 ISO11649 채권자 참조를 생성하고 설정합니다. |
| override [Equals](../../aspose.barcode.complexbarcode/swissqrbill/equals/#equals_1)(object) | 지정된 객체가 현재 객체와 동일한지 확인합니다. |
| [Equals](../../aspose.barcode.complexbarcode/swissqrbill/equals/#equals)(SwissQRBill) | 지정된 청구서가 현재 청구서와 동일한지 여부를 결정합니다. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/swissqrbill/gethashcode/)() | 이 인스턴스의 해시 코드를 가져옵니다. |

## 다른 멤버

| 이름 | 설명 |
| --- | --- |
| enum [QrBillStandardVersion](../../aspose.barcode.complexbarcode/swissqrbill.qrbillstandardversion) | SwissQR 청구서 표준 버전 |

### 또 보기

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


