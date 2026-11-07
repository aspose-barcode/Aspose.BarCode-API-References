---
title: "Aspose::BarCode::Metered 클래스"
linktitle: "계량"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Metered 클래스. C++에서 계량 키를 설정하는 메서드를 제공합니다."
type: docs
weight: 500
url: /ko/cpp/aspose.barcode/metered/
---
## Metered class


계량 키를 설정하는 메서드를 제공합니다.

```cpp
class Metered : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | 소비 크레딧을 가져옵니다 |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | 소비 파일 크기를 가져옵니다 |
| [GetProductName](./getproductname/)() | 라이선스가 적용된 제품 이름을 가져옵니다 |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | 계량이 라이선스가 부여되었는지 확인합니다 |
| [Metered](./metered/)() | 이 클래스의 새 인스턴스를 초기화합니다. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | 계량 라이선스를 구매한 경우, 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. 그러나 소비 데이터를 업로드하는 데 계속 실패하고 24시간을 초과하면 라이선스가 평가 상태로 설정됩니다. 이러한 경우를 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 다시 이 API를 호출해야 합니다. |
## 비고


이 예제에서는 계량 공개 키와 개인 키를 설정하려고 시도합니다.

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> 구성 요소 jar 파일:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## 또 보기

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
