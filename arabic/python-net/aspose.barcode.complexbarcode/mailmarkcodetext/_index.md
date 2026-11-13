---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

فئة لتشفير وفك تشفير النص المضمن في رمز Royal Mailmark ذو الأربع حالات.

يعرض نوع MailmarkCodetext الأعضاء التالية:
## المنشئات
| الاسم | الوصف |
| :- | :- |
| MailmarkCodetext() | ينشئ مثلاً جديداً من الفئة MailmarkCodetext |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| التنسيق | "0" – فارغ أو اختبار<br/>            "1" – حرف<br/>            "2" – حرف كبير |
| version_id | حاليًا "1" – لباركود Mailmark (0 و 2 إلى 9 و A إلى Z محجوز للاستخدام المستقبلي) |
| klass | "0" - فارغ أو اختبار<br/>            "1" - 1C (تجزئة)<br/>            "2" - 2C (تجزئة)<br/>            "3" - 3C (تجزئة)<br/>            "4" - مميز (بريد النشر التجزئة) (للاستخدام المستقبلي المحتمل)<br/>            "5" - مؤجل (تجزئة)<br/>            "6" - جوي (تجزئة) (للاستخدام المستقبلي المحتمل)<br/>            "7" - سطحي (تجزئة) (للاستخدام المستقبلي المحتمل)<br/>            "8" - مميز (الوصول إلى الشبكة)<br/>            "9" - قياسي (الوصول إلى الشبكة) |
| supply_chain_id | القيم القصوى هي 99 للباركود C و 999999 للباركود L. |
| item_id | القيمة القصوى هي 99999999. |
| destination_post_code_and_dps | يجب أن يتوافق كل من PC و DP مع تنسيق PAF.<br/>            سلسلة مكوّنة من تسعة أحرف تمثل "XY11     " دوليًا (لاحظ المسافات الخمس الأخيرة) أو نمط<br/>            من الأحرف يمثل رمز فرز محلي.<br/>            يتكون رمز الفرز المحلي من رمز بريد خارجي، رمز بريد داخلي، ولاحقة نقطة التسليم. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| get_constructed_codetext() | إنشاء نص رمز من بيانات Mailmark. |
| init_from_string(constructed_codetext) | ينشئ بيانات Mailmark من نص الرمز المُنشأ. |
| get_barcode_type() | يحصل على نوع الباركود. |

### انظر أيضًا

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

