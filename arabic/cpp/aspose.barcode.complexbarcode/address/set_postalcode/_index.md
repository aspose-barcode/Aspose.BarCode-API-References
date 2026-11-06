---
title: "طريقة"
linktitle: "set_PostalCode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحدد الرمز البريدي في C++."
type: docs
weight: 1300
url: /ar/cpp/aspose.barcode.complexbarcode/address/set_postalcode/
---
## Address::set_PostalCode method


يضبط الرمز البريدي.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_PostalCode(System::String value)
```

## ملاحظات


تعيين هذا الحقل يحدد نوع العنوان إلى [AddressType::Structured](../../addresstype/) ما لم يكن بالفعل [AddressType::CombinedElements](../../addresstype/)، وفي هذه الحالة يصبح [AddressType::Conflicting](../../addresstype/).

هذا الحقل يُستخدم فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

الرمز البريدي.
## انظر أيضًا

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
