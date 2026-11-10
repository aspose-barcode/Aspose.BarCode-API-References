---
title: "الفئة GS1Codetext"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "الفئة Aspose.BarCode.ComplexBarcode.GS1Codetext. تمثل نص شفرة GS1 للتشفير وفك التشفير كسلسلة مرتبة من عناصر معرف التطبيق. يتم الحفاظ على ترتيب المصدر ومعرفات التطبيق المتكررة. تمثيل القوسين له الشكل AIvalueAIvalue. قوس فتح حرفي داخل قيمة يجب كتابته كـ  هذا هو تسلسل الهروب الوحيد المدعوم. قوس إغلاق داخل قيمة لا يتطلب الهروب."
type: docs
weight: 530
url: /ar/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

تمثل نص شفرة GS1 للتشفير وفك التشفير كسلسلة مرتبة من عناصر معرف التطبيق. يتم الحفاظ على ترتيب المصدر ومعرفات التطبيق المتكررة. تمثيل القوسين له الشكل (AI)value(AI)value. قوس فتح حرفي '(' داخل قيمة يجب كتابته كـ \\(; هذا هو تسلسل الهروب الوحيد المدعوم. قوس إغلاق ')' داخل قيمة لا يتطلب الهروب.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | يحصل أو يضبط نوع الباركود المستخدم لتشفير نص شفرة GS1 هذا. الأنواع المدعومة هي GS1Aztec و GS1CodablockF و GS1Code128 و GS1DataMatrix و GS1DotCode و GS1HanXin و GS1MicroPdf417 و GS1QR وأنواع GS1 DataBar. القيمة الافتراضية هي GS1Code128. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | يحصل على عدد عناصر معرف التطبيق. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | يحصل على نسخة من جميع العناصر بترتيب المصدر. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | يحصل على عنصر حسب موقعه في السلسلة المرتبة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | يقوم بتحليل سلسلة عنصر GS1 محصورة في الشكل (AI)value(AI)value. يجب كتابة '(' حرفيًا داخل قيمة كـ \\(; لا يتم دعم أي تسلسل هروب آخر، ولا يتطلب ')' الهروب. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | يضيف عنصر معرف تطبيق تم التحقق منه. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | يحصل على جميع القيم لمعرف التطبيق بترتيب المصدر. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | يحصل على نوع الباركود المستخدم لتشفير نص شفرة GS1 هذا. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | يبني نص شفرة GS1 محصورًا في الشكل (AI)value(AI)value. يتم هروب أقواس الفتح الحرفية في القيم كـ \\( |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | يحصل على القيمة الأولى لمعرف التطبيق. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | يُهيئ هذه المثيلة من نص شفرة GS1 المحصور في الشكل (AI)value(AI)value. يتم استبدال العناصر الموجودة فقط بعد أن يتم تحليل النص المقدم بنجاح. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | يعيد تمثيل GS1 المحصور في الشكل (AI)value(AI)value. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | يحاول تحليل سلسلة عنصر GS1 محصورة في الشكل (AI)value(AI)value ويعيد أخطاء تحقق منظمة. يجب كتابة '(' حرفيًا داخل قيمة كـ \\(; لا يتم دعم أي تسلسل هروب آخر، ولا يتطلب ')' الهروب. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | يقوم بالتحقق من صحة سلسلة عنصر GS1 محصورة في الشكل (AI)value(AI)value دون إنشاء كائن. يجب كتابة '(' حرفيًا داخل قيمة كـ \\(; لا يتم دعم أي تسلسل هروب آخر، ولا يتطلب ')' الهروب. |

### انظر أيضًا

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


