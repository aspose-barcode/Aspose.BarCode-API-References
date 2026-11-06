---
title: "فئة Aspose::BarCode::ComplexBarcode::Address"
linktitle: "العنوان"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::ComplexBarcode::Address. عنوان الدائن أو المدين في C++."
type: docs
weight: 100
url: /ar/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Address](./address/)() | ينشئ مثيلة من [Address](./) |
| [Clear](./clear/)() | يمسح جميع الحقول ويضبط النوع إلى [AddressType::Undetermined](../addresstype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | يحدد ما إذا كان الكائن المحدد يساوي الكائن الحالي. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | يحدد ما إذا كان العنوان المحدد مساويًا للعنوان الحالي. |
| [get_AddressLine1](./get_addressline1/)() const | يحصل على السطر الأول من العنوان. |
| [get_AddressLine2](./get_addressline2/)() const | يحصل على السطر الثاني من العنوان. |
| [get_CountryCode](./get_countrycode/)() const | يحصل على رمز الدولة ISO المكوّن من حرفين. |
| [get_HouseNo](./get_houseno/)() const | يحصل على رقم المنزل. |
| [get_Name](./get_name/)() const | يحصل على الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو اسم الشركة لشخص قانوني. |
| [get_PostalCode](./get_postalcode/)() const | يحصل على الرمز البريدي. |
| [get_Street](./get_street/)() const | يحصل على الشارع. |
| [get_Town](./get_town/)() const | يحصل على المدينة أو البلدة. |
| [get_Type](./get_type/)() const | يحصل على نوع العنوان. |
| [GetHashCode](./gethashcode/)() const override | يحصل على قيمة التجزئة لهذا المثيل. |
| [set_AddressLine1](./set_addressline1/)(System::String) | يضبط السطر الأول من العنوان. |
| [set_AddressLine2](./set_addressline2/)(System::String) | يضبط السطر الثاني من العنوان. |
| [set_CountryCode](./set_countrycode/)(System::String) | يضبط رمز الدولة ISO المكوّن من حرفين. |
| [set_HouseNo](./set_houseno/)(System::String) | يضبط رقم المنزل. |
| [set_Name](./set_name/)(System::String) | يضبط الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو اسم الشركة لشخص قانوني. |
| [set_PostalCode](./set_postalcode/)(System::String) | يضبط الرمز البريدي. |
| [set_Street](./set_street/)(System::String) | يضبط الشارع. |
| [set_Town](./set_town/)(System::String) | يضبط المدينة أو البلدة. |
## ملاحظات


يمكنك إما ضبط الشارع ورقم المنزل والرمز البريدي والمدينة (النوع *structured address*) أو سطر العنوان 1 و2 (النوع *combined address elements*). يتم ضبط النوع تلقائيًا بمجرد ضبط أي من هذه الحقول. قبل ضبط الحقول، يكون نوع العنوان *undetermined*. إذا تم ضبط حقول من كلا النوعين، يصبح نوع العنوان *conflicting*. يجب دائمًا ضبط الاسم ورمز الدولة ما لم تكن جميع الحقول فارغة.
## انظر أيضًا

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
