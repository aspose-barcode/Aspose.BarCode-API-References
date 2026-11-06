---
title: "طريقة"
linktitle: "CleanValue"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. ينظف قيمة سلسلة لجعلها صالحة لمعايير الدفع السويسرية 2018 في C++."
type: docs
weight: 100
url: /ar/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


ينظف قيمة سلسلة لجعلها صالحة لمعايير الدفع السويسرية 2018.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | System::String | قيمة السلسلة التي يجب تنظيفها. |
| result | Payments::CleaningResult\& | النتيجة التي سيتم ملؤها بالسلسلة المنظفة والعلم. |
## ملاحظات


يتم استبدال الأحرف غير المدعومة (وفقًا لمعايير الدفع السويسرية 2018، الفصل 2.4.1 والملحق D) بالمسافات (مسافات غير مدعومة) أو بالنقاط (جميع الأحرف غير المدعومة الأخرى). يتم إزالة المسافات الفارغة في البداية والنهاية.

إذا تم اكتشاف أحرف تتجاوز 0xff، يتم أولاً تطبيع السلسلة بحيث يتم دمج الحروف ذات العلامات أو النبرات المكتوبة بنقطتي رمز إلى نقطة رمز واحدة (إن أمكن)، وقد يصبح بعضها صالحًا.

إذا كانت السلسلة الناتجة مكوّنة بالكامل من مسافات فارغة، يتم إرجاع **null**.

## انظر أيضًا

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
