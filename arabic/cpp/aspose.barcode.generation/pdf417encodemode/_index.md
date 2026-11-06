---
title: "enum"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " تعداد. وضع ترميز الباركود Pdf417 في C++."
type: docs
weight: 7900
url: /ar/cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


وضع ترميز باركود Pdf417

```cpp
enum class Pdf417EncodeMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| تلقائي | 0 | في وضع Auto، يتم ترميز CodeText بأقصى ضغط للبيانات. تُعاد ترميز أحرف Unicode باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز المحدد في ECI، يتم رفع استثناء. |
| ثنائي | 1 | في وضع الثنائي، يتم ترميز CodeText بأقصى ضغط للبيانات. إذا تم العثور على حرف Unicode، يتم رفع استثناء. |
| ECI | 2 | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز المحدد في ECI، يتم رفع استثناء. يرجى ملاحظة أن بعض الماسحات (قبل 2006) قد لا تدعم هذا الوضع. |
| ممتد | 3 |  |

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
