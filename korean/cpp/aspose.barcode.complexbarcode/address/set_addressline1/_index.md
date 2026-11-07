---
title: "메서드"
linktitle: "set_AddressLine1"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. C++에서 주소 라인 1을 설정합니다."
type: docs
weight: 500
url: /ko/cpp/aspose.barcode.complexbarcode/address/set_addressline1/
---
## Address::set_AddressLine1 method


주소 라인 1을 설정합니다.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine1(System::String value)
```

## 비고


[Address](../) line 1 contains street name, house number or P.O. box. 

이 필드를 설정하면 주소 유형이 이미 [AddressType::Structured](../../addresstype/)가 아닌 경우 [AddressType::CombinedElements](../../addresstype/)으로 설정되고, 이미 [AddressType::Structured](../../addresstype/)인 경우 [AddressType::Conflicting](../../addresstype/)이 됩니다.

이 필드는 결합된 요소 주소에만 사용되며 선택 사항입니다.

주소 라인 1.
## 또 보기

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
