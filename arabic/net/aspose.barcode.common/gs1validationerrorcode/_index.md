---
title: "تعداد GS1ValidationErrorCode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "تعداد Aspose.BarCode.Common.GS1ValidationErrorCode. يحدد خطأ في التحقق من صحة سلسلة عنصر GS1 أو URI للربط الرقمي أو القيمة"
type: docs
weight: 430
url: /ar/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

يحدد خطأ في التحقق من صحة سلسلة عنصر GS1 أو URI للربط الرقمي أو القيمة.

```csharp
public enum GS1ValidationErrorCode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| EmptyElementString | `0` | سلسلة عنصر GS1 المقدمة فارغة. |
| MissingOpeningParenthesis | `1` | القوس الافتتاحي الذي يجب أن يبدأ معرف التطبيق مفقود. |
| MissingClosingParenthesis | `2` | معرف التطبيق لا يحتوي على قوس إغلاق. |
| InvalidApplicationIdentifier | `3` | معرف التطبيق لا يحتوي على رقمين إلى أربعة أرقام ASCII. |
| UnknownApplicationIdentifier | `4` | معرف التطبيق المقدم غير معرف في قاموس بنية GS1 المدعوم. |
| MissingValue | `5` | معرف التطبيق موجود بدون قيمة. |
| InvalidEscapeSequence | `6` | القيمة تحتوي على تسلسل هروب غير مدعوم. فقط \\( مدعوم. |
| ValueTooShort | `7` | القيمة أقصر من الحد الأدنى للطول المحدد لمعرف التطبيق الخاص بها. |
| ValueTooLong | `8` | القيمة أطول من الحد الأقصى للطول المحدد لمعرف التطبيق الخاص بها. |
| InvalidCharacter | `9` | القيمة تحتوي على حرف خارج مجموعة الأحرف المسموح بها لمكونها. |
| InvalidChecksum | `10` | المجموع الاختباري الرقمي أو الأبجدي غير صالح. |
| InvalidDate | `11` | مكون التاريخ ليس تاريخًا ذا معنى وفقًا للقواعد المحددة لمعرف التطبيق الخاص به. |
| InvalidTime | `12` | مكون الوقت خارج النطاق المسموح به أو لديه بنية غير صالحة. |
| InvalidCodeListValue | `13` | قيمة المكون غير موجودة في قائمة الرموز المغلقة المسموح بها. |
| InvalidComponentLength | `14` | المكون لا يفي ببنية الطول الخاصة به. |
| TruncatedComponent | `15` | مكون ثابت الطول ينتهي قبل وجود جميع الأحرف المطلوبة. |
| UnexpectedData | `16` | تبقى بيانات بعد استهلاك جميع المكونات المعرفة لمعرف التطبيق. |
| InvalidValue | `17` | مكوّن ينتهك قاعدة محتوى لا يوجد لها رمز خطأ تحقق أكثر تحديدًا. |
| GcpPrefixTooShort | `18` | المكوّن قصير جدًا لاحتواء الحد الأدنى المكوّن من أربعة أرقام للبادئة الهيكلية لشركة GS1. |
| InvalidGcpPrefix | `19` | البادئة الهيكلية لشركة GS1 تحتوي على حرف غير رقم ASCII. |
| InvalidDigitalLinkUri | `20` | القيمة المقدَّمة ليست URI مطلقًا مُشكلًا بشكل صحيح لـ GS1 Digital Link. |
| UnsupportedDigitalLinkScheme | `21` | URI لـ GS1 Digital Link يستخدم مخططًا غير HTTP أو HTTPS. |
| MissingDigitalLinkPrimaryKey | `22` | مسار URI لـ GS1 Digital Link لا يحتوي على مفتاح أساسي مدعوم. |
| InvalidDigitalLinkPath | `23` | مسار URI لـ GS1 Digital Link لا يتكوّن من أزواج صالحة من معرف التطبيق (AI) والقيمة. |
| InvalidDigitalLinkQualifier | `24` | معرّف التطبيق في المسار ليس مؤهلاً مسموحًا به في ذلك الموضع. |
| InvalidDigitalLinkQueryParameter | `25` | معامل استعلام GS1 Digital Link غير مُشكل بشكل صحيح. |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | معرّف التطبيق غير مسموح به كخاصية بيانات لـ GS1 Digital Link. |
| InvalidPercentEncoding | `27` | مكوّن URI لـ GS1 Digital Link يحتوي على ترميز نسبة مئوية غير مُشكل بشكل صحيح. |
| MultipleDigitalLinkPrimaryKeys | `28` | يمكن اختيار أكثر من عنصر كمفتاح أساسي لـ GS1 Digital Link. |
| UnsupportedElementCombination | `29` | المجموعة المقدَّمة من عناصر GS1 غير مدعومة من قبل الترميز أو وضع الترميز المختار. |

### انظر أيضًا

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


