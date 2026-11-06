---
title: "طريقة"
linktitle: "get_Reference"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحصل على مرجع دفع الدائن في C++."
type: docs
weight: 1100
url: /ar/cpp/aspose.barcode.complexbarcode/swissqrbill/get_reference/
---
## SwissQRBill::get_Reference method


يحصل على مرجع دفع الدائن.

```cpp
System::String Aspose::BarCode::ComplexBarcode::SwissQRBill::get_Reference() const
```

## ملاحظات


المرجع إلزامي لـ IBANs SwissQR، أي IBANs في النطاق CHxx30000xxxxxx إلى CHxx31999xxxxx.

إذا تم تحديده، يجب أن يكون المرجع إما مرجع SwissQR صالح (مطابق لنموذج مرجع ISR) أو مرجع دائن صالح وفقًا لـ ISO 11649 (\"RFxxxx\"). كلاهما قد يحتوي على مسافات للتنسيق.

مرجع دفع الدائن.
## انظر أيضًا

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
