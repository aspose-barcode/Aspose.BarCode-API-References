---
title: "طريقة"
linktitle: "set_AddressLine2"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " الطريقة. تقوم بتعيين السطر الثاني للعنوان في C++."
type: docs
weight: 700
url: /ar/cpp/aspose.barcode.complexbarcode/address/set_addressline2/
---
## Address::set_AddressLine2 method


يضبط السطر الثاني من العنوان.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine2(System::String value)
```

## ملاحظات


[Address](../) line 2 contains postal code and town. 

تعيين هذا الحقل يحدد نوع العنوان إلى [AddressType::CombinedElements](../../addresstype/) ما لم يكن بالفعل [AddressType::Structured](../../addresstype/)، وفي هذه الحالة يصبح [AddressType::Conflicting](../../addresstype/).

يُستخدم هذا الحقل فقط لعناوين العناصر المدمجة. بالنسبة لهذا النوع، فهو إلزامي.

السطر الثاني للعنوان.
## انظر أيضًا

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
