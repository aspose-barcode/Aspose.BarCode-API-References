---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

فئة لتخزين البيانات الثانوية والإضافية لـ HIBC LIC.

يُظهر نوع SecondaryAndAdditionalData الأعضاء التالية:
## المنشئات
| الاسم | الوصف |
| :- | :- |
| SecondaryAndAdditionalData() | يُهيئ مثيلاً جديداً من فئة SecondaryAndAdditionalData |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| expiry_date_format | يحدد تنسيق تاريخ الانتهاء. |
| expiry_date | يحدد تاريخ الانتهاء. سيُستخدم إذا لم يتم تعيين ExpiryDateFormat إلى None. |
| lot_number | يحدد رقم الدفعة أو اللوت. يجب أن يكون رقم الدفعة/اللوت سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. |
| serial_number | يحدد الرقم التسلسلي. يجب أن يكون الرقم التسلسلي سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا. |
| date_of_manufacture | يحدد تاريخ الصنع.<br/>            يمكن ضبط تاريخ الصنع إلى DateTime.MinValue لعدم استخدام هذا الحقل.<br/>            القيمة الافتراضية: DateTime.MinValue |
| quantity | يحدد الكمية، يجب أن تكون قيمة صحيحة من 0 إلى 500. <br/>            يمكن ضبط الكمية إلى -1 لعدم استخدام هذا الحقل.<br/>            القيمة الافتراضية: -1 |
## الطرق
| الاسم | الوصف |
| :- | :- |
| parse_from_string(secondary_data_codetext) | يقوم بإنشاء بيانات ثانوية وإضافية مكملة من تنسيق سلسلة وفقًا لمواصفات HIBC LIC. |

### انظر أيضًا

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

