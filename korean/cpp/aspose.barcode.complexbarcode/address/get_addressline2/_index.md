---
title: "메서드"
linktitle: "get_AddressLine2"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. C++에서 주소 라인 2를 가져옵니다."
type: docs
weight: 600
url: /ko/cpp/aspose.barcode.complexbarcode/address/get_addressline2/
---
## Address::get_AddressLine2 method


주소 라인 2를 가져옵니다.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine2() const
```

## 비고


[Address](../) line 2 contains postal code and town. 

이 필드를 설정하면 주소 유형이 이미 [AddressType::Structured](../../addresstype/)가 아닌 경우 [AddressType::CombinedElements](../../addresstype/)으로 설정되고, 이미 [AddressType::Structured](../../addresstype/)인 경우 [AddressType::Conflicting](../../addresstype/)이 됩니다.

이 필드는 결합된 요소 주소에만 사용됩니다. 이 유형의 경우 필수입니다.

주소 라인 2.
## 또 보기

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
