---
title: "الفئة GS1DigitalLink"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "Aspose.BarCode.ComplexBarcode.GS1DigitalLink class. يمثل نص رمز GS1 Digital Link للتشفير وفك التشفير كسلسلة مرتبة من عناصر معرف التطبيق. يتم الحفاظ على ترتيب المصدر ومعرفات التطبيق المتكررة. النص المُنشأ هو URI غير مضغوط لـ GS1 Digital Link. يتم تجاهل معلمات الاستعلام غير GS1 وشرائح URI عند التحليل"
type: docs
weight: 540
url: /ar/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

يمثل نص رمز GS1 Digital Link للتشفير وفك التشفير كسلسلة مرتبة من عناصر معرف التطبيق. يتم الحفاظ على ترتيب المصدر ومعرفات التطبيق المتكررة. النص المُنشأ هو URI غير مضغوط لـ GS1 Digital Link. يتم تجاهل معلمات الاستعلام غير GS1 وشرائح URI عند التحليل.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | يفّتح رابط GS1 Digital Link فارغ مع جذع URI المحدد. يتم اختيار المفتاح الأساسي تلقائيًا عندما يكون هناك مرشح مفتاح أساسي واحد فقط. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | يفّتح رابط GS1 Digital Link فارغ مع جذع URI المحدد والمفتاح الأساسي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | يحصل أو يعيّن نوع الباركود المستخدم لتشفير هذا GS1 Digital Link. الأنواع المدعومة هي QR وDataMatrix وAztec وPdf417 وMicroPdf417 وDotCode وHanXin وCodablockF وCode128. القيمة الافتراضية هي QR. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | يحصل على عدد عناصر معرف التطبيق. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | يحصل على نسخة من جميع العناصر بترتيب المصدر. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | يحصل على عنصر حسب موقعه في السلسلة المرتبة. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | يحصل على معرف التطبيق المستخدم كمفتاح أساسي لرابط Digital Link. القيمة Null تعني أن المفتاح الأساسي يُختار تلقائيًا عند إنشاء URI. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | يحصل على بادئة URI المطلقة قبل مقطع مسار المفتاح الأساسي لـ GS1. الجذع لا يحتوي على سلسلة استعلام أو شريحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | ينشئ GS1 Digital Link بنسخ جميع العناصر من نص رمز GS1 واختيار المفتاح الأساسي المتاح الوحيد. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | ينشئ GS1 Digital Link بنسخ جميع العناصر من نص رمز GS1 واستخدام المفتاح الأساسي المحدد. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | يحلل URI غير مضغوط لـ GS1 Digital Link. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | يضيف عنصر معرف تطبيق تم التحقق منه. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | يحصل على جميع القيم لمعرف التطبيق بترتيب المصدر. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | يحصل على نوع الباركود المستخدم لتشفير هذا GS1 Digital Link. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | يبني URI غير مضغوط لـ GS1 Digital Link. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | يحصل على القيمة الأولى لمعرف التطبيق. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | يفّتح هذه الحالة من URI غير مضغوط لـ GS1 Digital Link. يتم استبدال الحالة الحالية فقط بعد أن يتم تحليل URI المقدم بنجاح. يتم الحفاظ على نوع الباركود المختار. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | ينشئ نص شفرة GS1 مستقل يحتوي على عناصر GS1 الحالية. لا يتم تضمين معلومات URI فقط. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | يعيد URI رابط GS1 الرقمي غير المضغوط. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | يقوم بتنسيق حالة الكائن الحالية كـ URI رابط GS1 الرقمي غير المضغوط. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | يحاول تحليل URI رابط GS1 الرقمي غير المضغوط ويعيد أخطاء تحقق منظمة. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | يقوم بالتحقق من صحة URI رابط GS1 الرقمي غير المضغوط دون إنشاء كائن. |

### انظر أيضًا

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


