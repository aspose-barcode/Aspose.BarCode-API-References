---
title: "فئة Aspose::BarCode::ComplexBarcode::Payments"
linktitle: "Payments"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::ComplexBarcode::Payments. تحقق من صحة الحقول المتعلقة بمعايير الدفع السويسرية في C++."
type: docs
weight: 2400
url: /ar/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


تحقق من صحة الحقول المتعلقة بمعايير الدفع السويسرية.

```cpp
class Payments
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | ينظف قيمة سلسلة لجعلها صالحة لمعايير الدفع السويسرية 2018. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | ينشئ مرجع دائن ISO11649 من سلسلة خام عن طريق إضافة البادئة "RF" وحساب المجموع المتبقي modulo 97. |
| static [FormatIban](./formatiban/)(System::String) | يقوم بتنسيق IBAN أو مرجع الدائن بإدخال مسافات. |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | يقوم بتنسيق رقم مرجع QR بإدخال مسافات. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | يتحقق مما إذا كانت السلسلة رقم IBAN صالح. |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | يتحقق مما إذا كانت السلسلة رقم مرجع ISO 11649 صالح. |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | يتحقق مما إذا كانت السلسلة مرجع QR صالح. |
| [Payments](./payments/)() |  |
## انظر أيضًا

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
