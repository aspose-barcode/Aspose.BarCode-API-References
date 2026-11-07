---
title: "메서드"
linktitle: "IsValidQrReference"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " method. 문자열이 C++에서 유효한 QR 레퍼런스인지 확인합니다."
type: docs
weight: 600
url: /ko/cpp/aspose.barcode.complexbarcode/payments/isvalidqrreference/
---
## Payments::IsValidQrReference method


문자열이 유효한 QR 참조인지 검증합니다.

```cpp
static bool Aspose::BarCode::ComplexBarcode::Payments::IsValidQrReference(System::String reference)
```


| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 참조 | System::String | 검증할 QR 레퍼런스 번호. |

### ReturnValue

**true** if the reference number is valid, **false** otherwise.
## 비고


유효한 QR 레퍼런스는 유효한 ISR 레퍼런스입니다.

문자열은 유효한 문자, 유효한 길이 및 유효한 체크 디지털을 확인합니다. 공백은 무시됩니다.

## 또 보기

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
