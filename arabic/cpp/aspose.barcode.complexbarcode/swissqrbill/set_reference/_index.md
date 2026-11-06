---
title: "طريقة"
linktitle: "set_Reference"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحدد مرجع دفع الدائن في C++."
type: docs
weight: 1200
url: /ar/cpp/aspose.barcode.complexbarcode/swissqrbill/set_reference/
---
## SwissQRBill::set_Reference method


يضبط مرجع دفع الدائن.

```cpp
void Aspose::BarCode::ComplexBarcode::SwissQRBill::set_Reference(System::String value)
```

## ملاحظات


المرجع إلزامي لـ IBANs SwissQR، أي IBANs في النطاق CHxx30000xxxxxx إلى CHxx31999xxxxx.

إذا تم تحديده، يجب أن يكون المرجع إما مرجع SwissQR صالح (مطابق لنموذج مرجع ISR) أو مرجع دائن صالح وفقًا لـ ISO 11649 (\"RFxxxx\"). كلاهما قد يحتوي على مسافات للتنسيق.

مرجع دفع الدائن.
## انظر أيضًا

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
