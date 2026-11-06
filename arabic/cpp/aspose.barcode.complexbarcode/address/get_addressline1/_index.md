---
title: "طريقة"
linktitle: "get_AddressLine1"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " الطريقة. تسترجع السطر الأول للعنوان في C++."
type: docs
weight: 400
url: /ar/cpp/aspose.barcode.complexbarcode/address/get_addressline1/
---
## Address::get_AddressLine1 method


يحصل على السطر الأول من العنوان.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine1() const
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
