---
title: "فئة Aspose::BarCode::ComplexBarcode::GS1Codetext"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::ComplexBarcode::GS1Codetext. تمثّل نصًا رمزيًا لـ GS1 للتشفير وفك التشفير كسلسلة مرتبة من عناصر معرف التطبيق. يتم الحفاظ على ترتيب المصدر ومعرفات التطبيقات المتكررة. التمثيل بين الأقواس له الشكل (AI)value(AI)value. القوس الافتتاحي الحرفي ''('' داخل القيمة يجب كتابته كـ (; هذا هو تسلسل الهروب الوحيد المدعوم. القوس الإغلاق '')'' داخل القيمة لا يتطلب هروبًا في C++."
type: docs
weight: 500
url: /ar/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


يمثل نص GS1 للتشفير وفك التشفير كسلسلة مرتبة من عناصر معرف التطبيق. يتم الحفاظ على ترتيب المصدر ومعرفات التطبيق المتكررة. التمثيل بين الأقواس له الشكل (AI)القيمة(AI)القيمة. يجب كتابة القوس الافتتاحي '(' داخل قيمة كـ (; هذا هو تسلسل الهروب الوحيد المدعوم. القوس الإغلاقي ')' داخل قيمة لا يتطلب هروبًا.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Add](./add/)(System::String, System::String) | يضيف عنصر Application Identifier مُتحقق منه. |
| [get_BarcodeType](./get_barcodetype/)() const | يحصل على نوع الباركود المستخدم لتشفير هذا النص الرمزي GS1. الأنواع المدعومة هي GS1Aztec وGS1CodablockF وGS1Code128 وGS1DataMatrix وGS1DotCode وGS1HanXin وGS1MicroPdf417 وGS1QR وأنواع GS1 DataBar. القيمة الافتراضية هي GS1Code128. |
| [get_Count](./get_count/)() | يحصل على عدد عناصر Application Identifier. |
| [get_Elements](./get_elements/)() | يحصل على نسخة من جميع العناصر بترتيب المصدر. |
| [GetAll](./getall/)(System::String) | يحصل على جميع القيم لمعرّف التطبيق بترتيب المصدر. |
| [GetBarcodeType](./getbarcodetype/)() override | يحصل على نوع الباركود المستخدم لتشفير هذا النص الرمزي GS1. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | يبني النص الرمزي GS1 بين الأقواس بالشكل (AI)value(AI)value. الأقواس الافتتاحية الحرفية في القيم تُهرب كـ (. |
| [GetFirst](./getfirst/)(System::String) | يحصل على القيمة الأولى لمعرّف التطبيق. |
| [GS1Codetext](./gs1codetext/)() | يُهيئ نصًا رمزيًا فارغًا لـ GS1. |
| [idx_get](./idx_get/)(int32_t) | يحصل على عنصر حسب موقعه في التسلسل المرتب. |
| [InitFromString](./initfromstring/)(System::String) override | يُهيئ هذه الحالة من نص GS1 رمزي بين الأقواس بالشكل (AI)value(AI)value. يتم استبدال العناصر الحالية فقط بعد أن يتم تحليل النص الرمزي المقدم بنجاح. |
| static [Parse](./parse/)(System::String) | يحلل سلسلة عنصر GS1 بين الأقواس بالشكل (AI)value(AI)value. القوس الحرفي '(' داخل القيمة يجب كتابته كـ (; لا توجد تسلسلات هروب أخرى مدعومة، والقوس ')' لا يتطلب هروبًا. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | يضبط نوع الباركود المستخدم لتشفير هذا النص الرمزي GS1. الأنواع المدعومة هي GS1Aztec وGS1CodablockF وGS1Code128 وGS1DataMatrix وGS1DotCode وGS1HanXin وGS1MicroPdf417 وGS1QR وأنواع GS1 DataBar. القيمة الافتراضية هي GS1Code128. |
| [ToString](./tostring/)() const override | يعيد تمثيل GS1 بين الأقواس بالشكل (AI)value(AI)value. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | يحاول تحليل سلسلة عنصر GS1 بين الأقواس بالشكل (AI)value(AI)value ويعيد أخطاء التحقق المهيكلة. يجب كتابة '(' حرفيًا داخل القيمة كـ (; لا يتم دعم أي تسلسل هروب آخر، ولا يلزم هروب ')' . |
| static [Validate](./validate/)(System::String) | يتحقق من صحة سلسلة عنصر GS1 بين الأقواس بالشكل (AI)value(AI)value دون إنشاء كائن. يجب كتابة '(' حرفيًا داخل القيمة كـ (; لا يتم دعم أي تسلسل هروب آخر، ولا يلزم هروب ')' . |
## انظر أيضًا

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
