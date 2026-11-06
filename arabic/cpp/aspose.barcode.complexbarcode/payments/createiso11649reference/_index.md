---
title: "طريقة"
linktitle: "CreateIso11649Reference"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. ينشئ إشارة دائن ISO11649 من سلسلة خام عن طريق إضافة البادئة \\\"RF\\\" إلى السلسلة وحساب المجموع الاختباري modulo 97 في C++."
type: docs
weight: 500
url: /ar/cpp/aspose.barcode.complexbarcode/payments/createiso11649reference/
---
## Payments::CreateIso11649Reference method


ينشئ مرجع دائن ISO11649 من سلسلة خام عن طريق إضافة البادئة "RF" وحساب المجموع المتبقي modulo 97.

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::CreateIso11649Reference(System::String rawReference)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| rawReference | System::String | الإشارة الخام. |

### ReturnValue

المرجع الدائن المُنشأ.
## ملاحظات


يتم إزالة المسافات البيضاء من المرجع.

## انظر أيضًا

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
