---
title: "طريقة"
linktitle: "get_Street"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحصل على الشارع في C++."
type: docs
weight: 800
url: /ar/cpp/aspose.barcode.complexbarcode/address/get_street/
---
## Address::get_Street method


يحصل على الشارع.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Street() const
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
