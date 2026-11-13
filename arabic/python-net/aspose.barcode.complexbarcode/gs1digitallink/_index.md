---
title: "GS1DigitalLink"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

يمثل نص ترميز GS1 Digital Link للتشفير وفك التشفير كسلسلة مرتبة من<br/>            عناصر معرف التطبيق. يتم الحفاظ على ترتيب المصدر ومعرفات التطبيق المتكررة.<br/>            نص الترميز المُنشأ هو URI غير مضغوط لـ GS1 Digital Link.<br/>            يتم تجاهل معلمات الاستعلام غير GS1 وشرائح URI عند التحليل.

نوع GS1DigitalLink يعرض الأعضاء التالية:
## المنشئات
| الاسم | الوصف |
| :- | :- |
| GS1DigitalLink(uri_stem) | ينشئ مثيلاً جديداً من فئة GS1DigitalLink |
| GS1DigitalLink(uri_stem, primary_application_identifier) | ينشئ مثيلاً جديداً من فئة GS1DigitalLink |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| uri_stem | يحصل على بادئة URI المطلقة قبل مقطع مسار المفتاح الأساسي GS1.<br/> لا يحتوي الساق على سلسلة استعلام أو جزء. |
| primary_application_identifier | يحصل على Application Identifier المستخدم كمفتاح أساسي لـ Digital Link.<br/> يعني Null أن المفتاح الأساسي يتم اختياره تلقائيًا عند إنشاء URI. |
| barcode_type | يحصل على أو يعيّن نوع الباركود المستخدم لتشفير هذا GS1 Digital Link.<br/> الأنواع المدعومة هي QR، DataMatrix، Aztec، Pdf417، MicroPdf417، DotCode، HanXin، CodablockF و Code128.<br/> القيمة الافتراضية هي QR. |
| العدد | يحصل على عدد عناصر Application Identifier. |
| العناصر | يحصل على نسخة من جميع العناصر بترتيب المصدر. |
## Indexer
| الاسم | الوصف |
| :- | :- |
| [index] | يحصل على عنصر حسب موقعه في التسلسل المرتب. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| create(uri_stem, codetext) | ينشئ رابط GS1 الرقمي عن طريق نسخ جميع العناصر من نص GS1 واختيار<br/>            المفتاح الأساسي المتاح الوحيد. |
| create(uri_stem, codetext, primary_application_identifier) | ينشئ رابط GS1 الرقمي عن طريق نسخ جميع العناصر من نص GS1 واختيار<br/>            المفتاح الأساسي المتاح الوحيد. |
| get_first(application_identifier) | يحصل على القيمة الأولى لمعرّف التطبيق. |
| get_all(application_identifier) | يحصل على جميع القيم لمعرّف التطبيق بترتيب المصدر. |
| add(application_identifier, value) | يضيف عنصر معرّف تطبيق تم التحقق منه. |
| validate(value) | يتحقق من صحة URI غير مضغوط لرابط GS1 الرقمي دون إنشاء كائن. |
| parse(value) | يحلل URI غير مضغوط لرابط GS1 الرقمي. |
| try_parse(value, result, validation_result) | يحاول تحليل URI غير مضغوط لرابط GS1 الرقمي ويعيد أخطاء تحقق منظمة. |
| to_gs1_codetext() | ينشئ نص GS1 مستقل يحتوي على العناصر الحالية لـ GS1.<br/>            لا يتم تضمين معلومات URI فقط. |
| to_uri_string() | يصيغ حالة الكائن الحالية كـ URI غير مضغوط لرابط GS1 الرقمي. |
| get_constructed_codetext() | يبني URI غير مضغوط لرابط GS1 الرقمي. |
| init_from_string(constructed_codetext) | يُهيئ هذا المثال من URI غير مضغوط لرابط GS1 الرقمي.<br/>            يتم استبدال الحالة الحالية فقط بعد أن يتم تحليل الـ URI المقدم بنجاح.<br/>            يتم الحفاظ على نوع الباركود المختار. |
| get_barcode_type() | يحصل على نوع الباركود المستخدم لتشفير هذا الرابط الرقمي GS1. |

### انظر أيضًا

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

