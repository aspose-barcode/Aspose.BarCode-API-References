---
title: "메서드"
linktitle: "get_Reference"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " method. C++에서 채권자 결제 참조를 가져옵니다."
type: docs
weight: 1100
url: /ko/cpp/aspose.barcode.complexbarcode/swissqrbill/get_reference/
---
## SwissQRBill::get_Reference method


채권자 결제 참조를 가져옵니다.

```cpp
System::String Aspose::BarCode::ComplexBarcode::SwissQRBill::get_Reference() const
```

## 비고


SwissQR IBAN에 대해 참조는 필수이며, 예를 들어 CHxx30000xxxxxx부터 CHxx31999xxxxx까지의 범위에 해당하는 IBAN이 해당됩니다.

지정된 경우, 참조는 유효한 SwissQR 참조(ISR 참조 양식에 해당) 또는 ISO 11649("RFxxxx")에 따른 유효한 채권자 참조여야 합니다. 두 경우 모두 서식을 위해 공백을 포함할 수 있습니다.

채권자 결제 참조입니다.
## 또 보기

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
