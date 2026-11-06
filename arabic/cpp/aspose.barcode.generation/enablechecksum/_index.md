---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام enum في C++."
type: docs
weight: 6700
url: /ar/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| افتراضي | 0 | إذا كان المجموع الاختباري مطلوبًا وفقًا للمواصفة - سيتم إرفاقه. |
| نعم | 1 | استخدم المجموع الاختباري دائمًا إذا كان ذلك ممكنًا. |
| لا | 2 | لا تستخدم المجموع الاختباري. |

## ملاحظات


تمكين المجموع الاختباري أثناء الإنشاء للباركودات أحادية البعد.

يُعامل الافتراضي كـ نعم للرموز التي يجب أن تحتوي على المجموع الاختباري، وكـ لا حيث يكون المجموع الاختباري ممكنًا فقط.

المجموع الاختباري لا يُستخدم أبدًا: Codabar

المجموع الاختباري ممكن: Code39 Standard/Extended، Standard2of5، Interleaved2of5، Matrix2of5، ItalianPost25، DeutschePostIdentcode، DeutschePostLeitcode، VIN

المجموع الاختباري يُستخدم دائمًا: باقي الرموز
## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
