---
title: "GS1Codetext"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

يمثل نص ترميز GS1 للتشفير وفك التشفير كسلسلة مرتبة من<br/>            عناصر معرف التطبيق. يتم الحفاظ على ترتيب المصدر ومعرفات التطبيق المتكررة.<br/>            يتم تمثيل الشكل المرفوع على الأقواس بالشكل (AI)value(AI)value.<br/>            يجب كتابة القوس الافتتاحي الحرفي '(' داخل القيمة كـ \\(; هذا هو<br/>            تسلسل الهروب الوحيد المدعوم. القوس الإغلاق ')' داخل القيمة لا<br/>            يتطلب هروبًا.

يعرض نوع GS1Codetext الأعضاء التالية:
## المنشئات
| الاسم | الوصف |
| :- | :- |
| GS1Codetext() | ينشئ نسخة جديدة من فئة GS1Codetext |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| barcode_type | يحصل أو يعيّن نوع الباركود المستخدم لتشفير هذا النص GS1.<br/>            الأنواع المدعومة هي GS1Aztec، GS1CodablockF، GS1Code128، GS1DataMatrix،<br/>            GS1DotCode، GS1HanXin، GS1MicroPdf417، GS1QR وأنواع GS1 DataBar.<br/>            القيمة الافتراضية هي GS1Code128. |
| العدد | يحصل على عدد عناصر Application Identifier. |
| العناصر | يحصل على نسخة من جميع العناصر بترتيب المصدر. |
## Indexer
| الاسم | الوصف |
| :- | :- |
| [index] | يحصل على عنصر حسب موقعه في التسلسل المرتب. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| get_first(application_identifier) | يحصل على القيمة الأولى لمعرّف التطبيق. |
| get_all(application_identifier) | يحصل على جميع القيم لمعرّف التطبيق بترتيب المصدر. |
| add(application_identifier, value) | يضيف عنصر معرّف تطبيق تم التحقق منه. |
| validate(value) | يتحقق من صحة سلسلة عنصر GS1 محصورة في الشكل (AI)value(AI)value دون<br/>            إنشاء كائن. يجب كتابة '(' حرفيًا داخل القيمة كـ \(; لا<br/>            توجد أي تسلسلات هروب أخرى مدعومة، ولا يلزم هروب ')'. |
| parse(value) | يفكّ تحليل سلسلة عنصر GS1 محصورة في الشكل (AI)value(AI)value. يجب كتابة '(' حرفيًا داخل القيمة كـ \(; لا توجد أي تسلسلات هروب أخرى مدعومة، ولا يلزم هروب ')'. |
| try_parse(value, result, validation_result) | يحاول تحليل سلسلة عنصر GS1 محصورة في الشكل (AI)value(AI)value<br/>            ويعيد أخطاء تحقق منظمة. يجب كتابة '(' حرفيًا داخل القيمة كـ \(; لا توجد أي تسلسلات هروب أخرى مدعومة، ولا يلزم هروب ')'. |
| get_constructed_codetext() | يبني النص GS1 المحصور في الشكل (AI)value(AI)value.<br/>            الأقواس الافتتاحية الحرفية في القيم تُهَرّب كـ \(. |
| init_from_string(constructed_codetext) | يُهيئ هذه النسخة من النص GS1 المحصور في الشكل (AI)value(AI)value.<br/>            يتم استبدال العناصر الموجودة فقط بعد أن يتم تحليل النص المزوّد بنجاح. |
| get_barcode_type() | يحصل على نوع الباركود المستخدم لتشفير هذا النص GS1. |

### انظر أيضًا

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

