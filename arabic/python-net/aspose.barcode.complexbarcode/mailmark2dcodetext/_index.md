---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

فئة لتشفير وفك تشفير النص المضمن في رمز Royal Mail 2D Mailmark.

يعرض نوع Mailmark2DCodetext الأعضاء التالية:
## المنشئات
| الاسم | الوصف |
| :- | :- |
| Mailmark2DCodetext() | ينشئ مثلاً جديداً من الفئة Mailmark2DCodetext |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| upu_country_id | يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف. |
| information_type_id | يحدد حمولة الباركود Mailmark الخاص بـ Royal Mail لكل نوع منتج. |
| version_id | يحدد إصدار الباركود المتعلق بكل معرف نوع المعلومات. |
| klass | يحدد فئة العنصر. |
| supply_chain_id | يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال.<br/>            القيمة القصوى: 9999999. |
| item_id | يحدد العنصر الفريد داخل معرف سلسلة التوريد.<br/>            يجب أن يحمل كل باركود Mailmark معرفًا<br/>            حتى يمكن التعرف عليه بشكل فريد لمدة لا تقل عن 90 يومًا.<br/>            القيمة القصوى: 99999999. |
| destination_post_code_and_dps | يحتوي على الرمز البريدي لعنوان التسليم مع DPS<br/>            إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي.<br/>            المنطقة (حرف أو حرفين) الحي (حرف أو حرفين)<br/>            القطاع (حرف واحد) الوحدة (حرفان) DPS (حرفان).<br/>            يجب أن يتوافق الرمز البريدي وDPS مع تنسيق PAF® صالح. |
| rts_flag | علامة تشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب. |
| return_to_sender_post_code | يحتوي على رمز البريد للإرجاع إلى المرسل دون DPS.<br/>            يجب أن يتوافق الرمز البريدي (بدون DPS) مع تنسيق PAF®. |
| customer_content | مساحة اختيارية لاستخدام العميل. |
| customer_content_encode_mode | وضع الترميز لباركود Datamatrix.<br/>            القيمة الافتراضية: EncodeMode.C40. |
| data_matrix_type | نوع Mailmark ثنائي الأبعاد يحدد حجم باركود Data Matrix. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| get_constructed_codetext() | إنشاء نص رمز من بيانات Mailmark. |
| init_from_string(constructed_codetext) | ينشئ بيانات Mailmark من نص الرمز المُنشأ. |
| get_barcode_type() | يحصل على نوع الباركود. |

### انظر أيضًا

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

