---
title: "Metered"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode/metered/
---

## Metered class

يوفر طرقًا لتعيين المفتاح القائم على القياس.

يعرض نوع Metered الأعضاء التالية:
## المنشئات
| الاسم | الوصف |
| :- | :- |
| Metered() | يُنشئ نسخة جديدة من فئة Metered |
## الطرق
| الاسم | الوصف |
| :- | :- |
| set_metered_key(public_key, private_key) | يضبط المفتاح العام والخاص للترخيص القائم على الاستهلاك.<br/>            إذا قمت بشراء ترخيص قائم على الاستهلاك، عند بدء التطبيق، يجب استدعاء هذه الواجهة البرمجية، عادةً هذا يكفي. <br/>            ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم ضبط الترخيص إلى حالة التقييم، <br/>            لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت في حالة التقييم، استدعِ هذه الواجهة البرمجية مرة أخرى. |
| get_consumption_quantity() | يحصل على حجم ملف الاستهلاك |
| get_consumption_credit() | يحصل على رصيد الاستهلاك |
| get_product_name() | يحصل على اسم المنتج المرخص |
| is_metered_licensed() | تحقق مما إذا كان الترخيص القائم على الاستهلاك مفعلًا |

### انظر أيضًا

* namespace [aspose.barcode](/barcode/python-net/aspose.barcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

