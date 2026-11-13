---
title: "GS1ValidationErrorCode"
second_title: "Aspose.Sildes للغة Python عبر .NET API Reference"
description: 
type: docs
url: /ar/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

يحدد خطأ تحقق لسلسلة عنصر GS1 أو URI للربط الرقمي أو القيمة.

## Members
| اسم العضو | الوصف |
| :- | :- |
| EMPTY_ELEMENT_STRING | سلسلة عنصر GS1 المقدمة فارغة. |
| MISSING_OPENING_PARENTHESIS | القوس الافتتاحي الذي يجب أن يبدأ معرف التطبيق مفقود. |
| MISSING_CLOSING_PARENTHESIS | معرف التطبيق لا يحتوي على قوس إغلاق. |
| INVALID_APPLICATION_IDENTIFIER | معرف التطبيق لا يحتوي على رقمين إلى أربعة أرقام ASCII. |
| UNKNOWN_APPLICATION_IDENTIFIER | معرف التطبيق المقدم غير معرف في قاموس بنية GS1 المدعوم. |
| MISSING_VALUE | معرف التطبيق موجود بدون قيمة. |
| INVALID_ESCAPE_SEQUENCE | القيمة تحتوي على تسلسل هروب غير مدعوم. فقط \( مدعوم. |
| VALUE_TOO_SHORT | القيمة أقصر من الحد الأدنى للطول المحدد لمعرف التطبيق الخاص بها. |
| VALUE_TOO_LONG | القيمة أطول من الحد الأقصى للطول المحدد لمعرف التطبيق الخاص بها. |
| INVALID_CHARACTER | القيمة تحتوي على حرف خارج مجموعة الأحرف المسموح بها لمكونها. |
| INVALID_CHECKSUM | المجموع الاختباري الرقمي أو الأبجدي غير صالح. |
| INVALID_DATE | مكون التاريخ ليس تاريخًا ذا معنى وفقًا للقواعد المحددة لمعرف التطبيق الخاص به. |
| INVALID_TIME | مكوّن الوقت خارج النطاق المسموح به أو يحتوي على بنية غير صالحة. |
| INVALID_CODE_LIST_VALUE | قيمة المكوّن غير موجودة في قائمة الرموز المغلقة المسموح بها. |
| INVALID_COMPONENT_LENGTH | المكوّن لا يفي ببنية الطول الخاصة به. |
| TRUNCATED_COMPONENT | مكوّن ثابت الطول ينتهي قبل وجود جميع الأحرف المطلوبة. |
| UNEXPECTED_DATA | تبقى بيانات بعد استهلاك جميع المكوّنات المعرفة لمعرّف التطبيق. |
| INVALID_VALUE | المكوّن ينتهك قاعدة محتوى لا يوجد لها رمز خطأ تحقق أكثر تحديدًا. |
| GCP_PREFIX_TOO_SHORT | المكوّن قصير جدًا لاحتواء الحد الأدنى من أربعة أرقام لبادئة شركة GS1 الهيكلية. |
| INVALID_GCP_PREFIX | بادئة شركة GS1 الهيكلية تحتوي على حرف غير رقم ASCII. |
| INVALID_DIGITAL_LINK_URI | القيمة المقدَّمة ليست URI رقمي GS1 مطلقًا مُشكلًا بشكل صحيح. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | URI الرقمي GS1 يستخدم مخططًا غير HTTP أو HTTPS. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | مسار URI الرقمي GS1 لا يحتوي على مفتاح أساسي مدعوم. |
| INVALID_DIGITAL_LINK_PATH | مسار URI الرقمي GS1 لا يتكون من أزواج صالحة من AI والقيمة. |
| INVALID_DIGITAL_LINK_QUALIFIER | معرّف التطبيق في المسار ليس مؤهلاً مسموحًا به في ذلك الموضع. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | معامل استعلام GS1 Digital Link غير صالح. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | معرف التطبيق غير مسموح به كخاصية بيانات GS1 Digital Link. |
| INVALID_PERCENT_ENCODING | مكوّن URI الخاص بـ GS1 Digital Link يحتوي على ترميز نسبة مئوية غير صالح. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | يمكن اختيار أكثر من عنصر كمفتاح أساسي لـ GS1 Digital Link. |
| UNSUPPORTED_ELEMENT_COMBINATION | التوليفة المقدمة من عناصر GS1 غير مدعومة من قبل الترميز أو وضع الترميز المختار. |

### انظر أيضًا

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

