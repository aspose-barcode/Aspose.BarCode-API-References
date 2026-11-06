---
title: "طريقة"
linktitle: "IsValidQrReference"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يتحقق مما إذا كانت السلسلة إشارة QR صالحة في C++."
type: docs
weight: 600
url: /ar/cpp/aspose.barcode.complexbarcode/payments/isvalidqrreference/
---
## Payments::IsValidQrReference method


يتحقق مما إذا كانت السلسلة مرجع QR صالح.

```cpp
static bool Aspose::BarCode::ComplexBarcode::Payments::IsValidQrReference(System::String reference)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| مرجع | System::String | رقم إشارة QR للتحقق منه. |

### ReturnValue

**true** if the reference number is valid, **false** otherwise.
## ملاحظات


إشارة QR صالحة هي إشارة ISR صالحة.

يتم فحص السلسلة للتحقق من الأحرف الصالحة، الطول الصالح ورقم التحقق الصالح. يتم تجاهل المسافات الفارغة.

## انظر أيضًا

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
