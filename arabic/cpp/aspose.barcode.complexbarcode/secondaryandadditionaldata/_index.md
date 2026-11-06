---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData فئة"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData فئة. فئة لتخزين البيانات الثانوية والإضافية لـ HIBC LIC في C++."
type: docs
weight: 2600
url: /ar/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


فئة لتخزين البيانات الثانوية والإضافية لـ HIBC LIC.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [SecondaryAndAdditionalData](./) المحددة. |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | يحدد تاريخ الصنع. يمكن ضبط تاريخ الصنع إلى DateTime.MinValue لعدم استخدام هذا الحقل. القيمة الافتراضية: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | يحدد تاريخ الانتهاء. سيُستخدم إذا لم يتم ضبط ExpiryDateFormat إلى بدون. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | يحدد تنسيق تاريخ الانتهاء. |
| [get_LotNumber](./get_lotnumber/)() const | يحدد رقم الدفعة أو اللوط. يجب أن يكون رقم الدفعة/اللوط سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. |
| [get_Quantity](./get_quantity/)() const | يحدد الكمية، يجب أن تكون قيمة صحيحة من 0 إلى 500. يمكن ضبط الكمية إلى -1 لعدم استخدام هذا الحقل. القيمة الافتراضية: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | يحدد الرقم التسلسلي. يجب أن يكون الرقم التسلسلي سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [ParseFromString](./parsefromstring/)(System::String) | ينشئ البيانات الثانوية والإضافية التكميلية من تنسيق سلسلة وفقًا لمواصفات HIBC LIC. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | يحدد تاريخ الصنع. يمكن ضبط تاريخ الصنع إلى DateTime.MinValue لعدم استخدام هذا الحقل. القيمة الافتراضية: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | يحدد تاريخ الانتهاء. سيُستخدم إذا لم يتم ضبط ExpiryDateFormat إلى بدون. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | يحدد تنسيق تاريخ الانتهاء. |
| [set_LotNumber](./set_lotnumber/)(System::String) | يحدد رقم الدفعة أو اللوط. يجب أن يكون رقم الدفعة/اللوط سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. |
| [set_Quantity](./set_quantity/)(int32_t) | يحدد الكمية، يجب أن تكون قيمة صحيحة من 0 إلى 500. يمكن ضبط الكمية إلى -1 لعدم استخدام هذا الحقل. القيمة الافتراضية: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | يحدد الرقم التسلسلي. يجب أن يكون الرقم التسلسلي سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. |
| [ToString](./tostring/)() const override | يحوّل البيانات إلى تنسيق سلسلة وفقًا لمواصفات HIBC LIC. |
## انظر أيضًا

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
