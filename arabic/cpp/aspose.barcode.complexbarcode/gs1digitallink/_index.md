---
title: "فئة Aspose::BarCode::ComplexBarcode::GS1DigitalLink"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::ComplexBarcode::GS1DigitalLink. تمثل نص رمز GS1 Digital Link للترميز وفك الترميز كسلسلة مرتبة من عناصر Application Identifier. يتم الحفاظ على ترتيب المصدر ومعرفات Application Identifier المتكررة. نص الرمز المُنشأ هو URI غير مضغوط لـ GS1 Digital Link. يتم تجاهل معلمات الاستعلام غير GS1 وقطع URI عند التحليل في C++."
type: docs
weight: 600
url: /ar/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


يمثل نص GS1 Digital Link للتشفير وفك التشفير كسلسلة مرتبة من عناصر معرف التطبيق. يتم الحفاظ على ترتيب المصدر ومعرفات التطبيق المتكررة. النص المُنشأ هو URI غير مضغوط لـ GS1 Digital Link. يتم تجاهل معلمات الاستعلام غير الخاصة بـ GS1 وشرائح URI عند التحليل.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Add](./add/)(System::String, System::String) | يضيف عنصر Application Identifier مُتحقق منه. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | ينشئ GS1 Digital Link بنسخ جميع العناصر من نص رمز GS1 واختيار المفتاح الأساسي المتاح الوحيد. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | ينشئ GS1 Digital Link بنسخ جميع العناصر من نص رمز GS1 واستخدام المفتاح الأساسي المحدد. |
| [get_BarcodeType](./get_barcodetype/)() const | يحصل على نوع الباركود المستخدم لتشفير هذا GS1 Digital Link. الأنواع المدعومة هي QR، DataMatrix، Aztec، Pdf417، MicroPdf417، DotCode، HanXin، CodablockF و Code128. القيمة الافتراضية هي QR. |
| [get_Count](./get_count/)() | يحصل على عدد عناصر Application Identifier. |
| [get_Elements](./get_elements/)() | يحصل على نسخة من جميع العناصر بترتيب المصدر. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | يحصل على Application Identifier المستخدم كمفتاح أساسي لDigital Link. القيمة Null تعني أن المفتاح الأساسي يُختار تلقائيًا عند إنشاء URI. |
| [get_UriStem](./get_uristem/)() const | يحصل على بادئة URI المطلقة قبل مقطع مسار المفتاح الأساسي لـ GS1. الجذر لا يحتوي على سلسلة استعلام أو جزء. |
| [GetAll](./getall/)(System::String) | يحصل على جميع القيم لمعرّف التطبيق بترتيب المصدر. |
| [GetBarcodeType](./getbarcodetype/)() override | يحصل على نوع الباركود المستخدم لتشفير هذا الرابط الرقمي GS1. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | يبني عنوان URI غير مضغوط للرابط الرقمي GS1. |
| [GetFirst](./getfirst/)(System::String) | يحصل على القيمة الأولى لمعرّف التطبيق. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | يُهيئ رابطًا رقميًا GS1 فارغًا مع جذع URI المحدد. يتم اختيار المفتاح الأساسي تلقائيًا عندما يكون هناك مرشح واحد فقط للمفتاح الأساسي. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | يُهيئ رابطًا رقميًا GS1 فارغًا مع جذع URI المحدد والمفتاح الأساسي. |
| [idx_get](./idx_get/)(int32_t) | يحصل على عنصر حسب موقعه في التسلسل المرتب. |
| [InitFromString](./initfromstring/)(System::String) override | يُهيئ هذه الحالة من عنوان URI غير مضغوط للرابط الرقمي GS1. يتم استبدال الحالة الحالية فقط بعد أن يتم تحليل الـ URI المقدم بنجاح. يتم الحفاظ على نوع الباركود المختار. |
| static [Parse](./parse/)(System::String) | يحلل عنوان URI غير مضغوط للرابط الرقمي GS1. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | يضبط نوع الباركود المستخدم لتشفير هذا الرابط الرقمي GS1. الأنواع المدعومة هي QR وDataMatrix وAztec وPdf417 وMicroPdf417 وDotCode وHanXin وCodablockF وCode128. القيمة الافتراضية هي QR. |
| [ToGS1Codetext](./togs1codetext/)() | ينشئ نصًا رمزيًا مستقلًا لـ GS1 يحتوي على عناصر GS1 الحالية. لا يتم تضمين معلومات URI فقط. |
| [ToString](./tostring/)() const override | يعيد عنوان URI غير مضغوط للرابط الرقمي GS1. |
| [ToUriString](./touristring/)() | يصيغ حالة الكائن الحالية كعنوان URI غير مضغوط للرابط الرقمي GS1. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | يحاول تحليل عنوان URI غير مضغوط للرابط الرقمي GS1 ويعيد أخطاء تحقق منظمة. |
| static [Validate](./validate/)(System::String) | يُحقق صحة عنوان URI غير مضغوط للرابط الرقمي GS1 دون إنشاء كائن. |
## انظر أيضًا

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
