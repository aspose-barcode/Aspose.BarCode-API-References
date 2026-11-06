---
title: "طريقة"
linktitle: "set_Street"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحدد الشارع في C++."
type: docs
weight: 900
url: /ar/cpp/aspose.barcode.complexbarcode/address/set_street/
---
## Address::set_Street method


يضبط الشارع.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Street(System::String value)
```

## ملاحظات


يجب تحديد الشارع بدون رقم المنزل.

تعيين هذا الحقل يحدد نوع العنوان إلى [AddressType::Structured](../../addresstype/) ما لم يكن بالفعل [AddressType::CombinedElements](../../addresstype/)، وفي هذه الحالة يصبح [AddressType::Conflicting](../../addresstype/).

يُستخدم هذا الحقل فقط لعناوين منظمة وهو اختياري.

الشارع.
## انظر أيضًا

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
