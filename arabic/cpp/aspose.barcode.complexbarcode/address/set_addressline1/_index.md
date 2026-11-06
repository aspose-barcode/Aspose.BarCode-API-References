---
title: "طريقة"
linktitle: "set_AddressLine1"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " الطريقة. تقوم بتعيين السطر الأول للعنوان في C++."
type: docs
weight: 500
url: /ar/cpp/aspose.barcode.complexbarcode/address/set_addressline1/
---
## Address::set_AddressLine1 method


يضبط السطر الأول من العنوان.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine1(System::String value)
```

## ملاحظات


[Address](../) line 1 contains street name, house number or P.O. box. 

تعيين هذا الحقل يحدد نوع العنوان إلى [AddressType::CombinedElements](../../addresstype/) ما لم يكن بالفعل [AddressType::Structured](../../addresstype/)، وفي هذه الحالة يصبح [AddressType::Conflicting](../../addresstype/).

يُستخدم هذا الحقل فقط لعناوين العناصر المدمجة وهو اختياري.

السطر الأول للعنوان.
## انظر أيضًا

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
