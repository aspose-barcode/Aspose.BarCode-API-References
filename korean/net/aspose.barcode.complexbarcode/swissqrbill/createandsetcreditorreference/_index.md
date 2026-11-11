---
title: "SwissQRBill.CreateAndSetCreditorReference"
second_title: "Aspose.BarCode for .NET API 참조"
description: "SwissQRBill 메서드. 원시 문자열에 'RF'를 접두사로 붙이고 modulo 97 체크섬을 적용하여 ISO11649 채권자 참조를 생성하고 설정합니다."
type: docs
weight: 110
url: /ko/net/aspose.barcode.complexbarcode/swissqrbill/createandsetcreditorreference/
---
## SwissQRBill.CreateAndSetCreditorReference method

문자열 앞에 \"RF\"를 붙이고 modulo 97 체크섬을 적용하여 원시 문자열에서 ISO11649 채권자 참조를 생성하고 설정합니다.

참조에서 공백이 제거됩니다.

```csharp
public void CreateAndSetCreditorReference(string rawReference)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rawReference | String | 원시 참조. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | `rawReference`에 잘못된 문자가 포함되어 있습니다. |

### 또 보기

* class [SwissQRBill](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


