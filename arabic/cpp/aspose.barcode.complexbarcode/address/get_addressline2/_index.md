---
title: "طريقة"
linktitle: "get_AddressLine2"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحصل على سطر العنوان الثاني في C++."
type: docs
weight: 600
url: /ar/cpp/aspose.barcode.complexbarcode/address/get_addressline2/
---
## Address::get_AddressLine2 method


يحصل على السطر الثاني من العنوان.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine2() const
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
