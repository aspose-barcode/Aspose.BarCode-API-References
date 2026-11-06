---
title: "enum"
linktitle: "GS1ValidationErrorCode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " تعداد. يحدد خطأ في التحقق من سلسلة عنصر GS1 أو URI للربط الرقمي أو القيمة في C++."
type: docs
weight: 600
url: /ar/cpp/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enum


يحدد خطأ تحقق في سلسلة عنصر GS1 أو رابط Digital Link URI أو القيمة.

```cpp
enum class GS1ValidationErrorCode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| EmptyElementString | 0 | سلسلة عنصر GS1 المقدمة فارغة. |
| MissingOpeningParenthesis | 1 | القوس الافتتاحي الذي يجب أن يبدأ معرف التطبيق مفقود. |
| MissingClosingParenthesis | 2 | معرف التطبيق لا يحتوي على قوس إغلاق. |
| InvalidApplicationIdentifier | 3 | معرف التطبيق لا يحتوي على رقمين إلى أربعة أرقام ASCII. |
| UnknownApplicationIdentifier | 4 | معرف التطبيق المقدم غير معرف في القاموس المدعوم لصياغة GS1. |
| MissingValue | 5 | معرف التطبيق موجود بدون قيمة. |
| InvalidEscapeSequence | 6 | القيمة تحتوي على تسلسل هروب غير مدعوم. فقط ( مدعوم. |
| ValueTooShort | 7 | القيمة أقصر من الحد الأدنى للطول المحدد لمعرف التطبيق الخاص بها. |
| ValueTooLong | 8 | القيمة أطول من الحد الأقصى للطول المحدد لمعرّف التطبيق الخاص بها. |
| InvalidCharacter | 9 | القيمة تحتوي على حرف خارج مجموعة الأحرف المسموح بها لمكوّنها. |
| InvalidChecksum | 10 | المجموع الاختباري الرقمي أو الأبجدي غير صالح. |
| InvalidDate | 11 | مكوّن التاريخ ليس تاريخًا ذا معنى وفقًا للقواعد المحددة لمعرّف التطبيق. |
| InvalidTime | 12 | مكوّن الوقت خارج النطاق المسموح به أو لديه بنية غير صالحة. |
| InvalidCodeListValue | 13 | قيمة المكوّن غير موجودة في قائمة الرموز المغلقة المسموح بها. |
| InvalidComponentLength | 14 | المكوّن لا يفي ببنية الطول الخاصة به. |
| TruncatedComponent | 15 | المكوّن ذو الطول الثابت ينتهي قبل وجود جميع الأحرف المطلوبة. |
| UnexpectedData | 16 | تبقى بيانات بعد استهلاك جميع المكوّنات المحددة لمعرّف التطبيق. |
| InvalidValue | 17 | مكوّن ينتهك قاعدة محتوى لا يحتوي على رمز خطأ تحقق أكثر تحديدًا. |
| GcpPrefixTooShort | 18 | المكوّن قصير جدًا لاحتواء الحد الأدنى من بادئة الشركة الهيكلية GS1 المكوّنة من أربعة أرقام. |
| InvalidGcpPrefix | 19 | بادئة الشركة الهيكلية GS1 تحتوي على حرف غير رقم ASCII. |
| InvalidDigitalLinkUri | 20 | القيمة المقدَّمة ليست URI رقمي GS1 مطلقًا مُشكلًا بشكل صحيح. |
| UnsupportedDigitalLinkScheme | 21 | URI الرقمي GS1 يستخدم مخططًا غير HTTP أو HTTPS. |
| MissingDigitalLinkPrimaryKey | 22 | مسار URI الرقمي GS1 لا يحتوي على مفتاح أساسي مدعوم. |
| InvalidDigitalLinkPath | 23 | مسار URI الرقمي GS1 لا يتكون من أزواج صالحة من معرف التطبيق (AI) والقيمة. |
| InvalidDigitalLinkQualifier | 24 | معرّف التطبيق في المسار ليس مؤهلاً مسموحًا به في ذلك الموضع. |
| InvalidDigitalLinkQueryParameter | 25 | معامل استعلام GS1 Digital Link غير صالح. |
| ApplicationIdentifierNotAllowedInDigitalLink | 26 | معرف التطبيق غير مسموح به كخاصية بيانات GS1 Digital Link. |
| InvalidPercentEncoding | 27 | مكوّن URI الخاص بـ GS1 Digital Link يحتوي على ترميز نسبة مئوية غير صالح. |
| MultipleDigitalLinkPrimaryKeys | 28 | يمكن اختيار أكثر من عنصر كمفتاح أساسي لـ GS1 Digital Link. |
| UnsupportedElementCombination | 29 | التوليفة المقدمة من عناصر GS1 غير مدعومة من قبل الترميز أو وضع الترميز المختار. |

## انظر أيضًا

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
