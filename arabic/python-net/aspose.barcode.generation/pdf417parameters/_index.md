---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

معلمات PDF417. يحتوي على معلمات PDF417 و MacroPDF417 و MicroPDF417 و GS1MicroPdf417.<br/>            يتطلب MacroPDF417 حقلين: Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية.<br/>            يتطلب MicroPDF417 في وضع الإلحاق المُنظم (نفس وضع MacroPDF417) حقلين: Pdf417MacroFileID و Pdf417MacroSegmentID. جميع الحقول الأخرى اختيارية.

يعرض نوع Pdf417Parameters الأعضاء التالية:
## الخصائص
| الاسم | الوصف |
| :- | :- |
| encode_mode | يحدد وضع ترميز Pdf417. <br/>            القيمة الافتراضية: Auto. |
| error_level | يحصل أو يضبط نوع ترميز Pdf417 لمستوى تصحيح الأخطاء لباركود<br/>            يتراوح من level0 إلى level8، level0 يعني عدم وجود معلومات تصحيح أخطاء،<br/>            level8 يعني أفضل تصحيح أخطاء مما يعني صورة أكبر. |
| truncate | ما إذا كان نوع ترميز Pdf417 للباركود مقصوصًا (لتقليل المساحة). <br/>            يُعرف أيضًا باسم CompactPDF417. يتم إزالة مؤشر الصف الأيمن ونمط الإيقاف الأيمن في هذا الوضع. |
| الأعمدة | عدد الأعمدة. |
| الصفوف | عدد الصفوف. |
| aspect_ratio | نسبة الارتفاع إلى العرض لوحدة باركود 2D. |
| macro_pdf_417_file_id | معرّف ملف الباركود MacroPdf417 (حقل مطلوب).<br/>            معرّف ملف الباركود MicroPDF417 (حقل مطلوب لوضع Structured Append). |
| macro_pdf_417_segment_id | معرّف الجزء للباركود MacroPdf417 (حقل مطلوب)، يبدأ من 0 إلى MacroSegmentsCount - 1.<br/>            معرّف الجزء للباركود MicroPDF417 (حقل مطلوب لوضع Structured Append). |
| macro_pdf_417_segments_count | عدد أجزاء الباركود MacroPdf417 (حقل اختياري).<br/>            عدد أجزاء الباركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| macro_pdf_417_file_name | اسم ملف الباركود MacroPdf417 (حقل اختياري).<br/>            اسم ملف الباركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| macro_pdf_417_time_stamp | الطابع الزمني للباركود MacroPdf417 (حقل اختياري).<br/>            الطابع الزمني للباركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| macro_pdf_417_sender | اسم مرسل الباركود MacroPdf417 (حقل اختياري).<br/>            اسم مرسل الباركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| macro_pdf_417_addressee | اسم المستلم للباركود MacroPdf417 (حقل اختياري).<br/>            اسم المستلم للباركود MicroPDF417 (حقل اختياري لوضع Structured Append). |
| macro_pdf_417_file_size | حجم ملف MacroPdf417 (حقل اختياري).<br/>            حجم ملف MicroPDF417 (حقل اختياري لوضع الإضافة المهيكلة)<br/>            يحتوي حقل حجم الملف على الحجم بالبايت للملف المصدر بالكامل. |
| macro_pdf_417_checksum | التحقق من صحة الباركود MacroPdf417 (حقل اختياري).<br/>            التحقق من صحة الباركود MicroPDF417 (حقل اختياري لوضع الإضافة المهيكلة)<br/>            يحتوي حقل التحقق من الصحة على قيمة التحقق من CRC 16‑بت (2 بايت) باستخدام كثير الحدود CCITT-16. x^16 + x^12 + x^5 + 1 |
| eci_encoding | معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بالتفاصيل<br/>            حول المراجع المستخدمة لتشفير البيانات في الرمز. لا تُطبق على حقول نص Macro PDF417.<br/>            يتضمن التنفيذ الحالي جميع ترميزات مجموعة الأحرف المعروفة. |
| macro_pdf_417eci_encoding | معرفات تفسير القناة الموسعة. تُطبق على حقول نص Macro PDF417. |
| macro_pdf_417_terminator | يُستخدم لإخبار المُرمّز ما إذا كان يجب إضافة مُنهي Macro PDF417 (كلمة الشيفرة 922) إلى الجزء.<br/>            يُطبق فقط على Macro PDF417. |
| is_reader_initialization | يُستخدم لتوجيه القارئ لتفسير البيانات الموجودة داخل الرمز<br/>            كبرمجة لتهيئة القارئ. |
| macro_characters | تُستخدم قيم الأحرف الماكرو 05 و06 للحصول على ترميز أكثر تكثيفًا في أوضاع خاصة.<br/>            يمكن استخدامها فقط مع MicroPdf417 وتشفير أوضاع MicroPdf417 916 و917<br/>            القيمة الافتراضية: MacroCharacters.None. |
| is_linked | يحدد أوضاع الربط مع رموز GS1MicroPdf417 وMicroPdf417 وPdf417<br/>            مع ترميز GS1MicroPdf417 يتم ترميز أوضاع UCC/EAN-128 “المربوطة” 906، 907، 912، 913، 914، 915<br/>            مع ترميزات MicroPdf417 وPdf417 يتم ترميز علم الربط 918 للمكوّن الخطي المرتبط غير EAN.UCC |
| is_code_128_emulation | يمكن استخدامها فقط مع MicroPdf417 وتشفير أوضاع محاكاة Code 128<br/>            يمكن ترميز FNC1 في الوضع الثاني 908 و909، ويمكن أيضًا ترميز 910 و911 التي تشير فقط إلى أن MicroPdf417 المعترف به يمكن تفسيره كـ Code 128 |

### انظر أيضًا

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

