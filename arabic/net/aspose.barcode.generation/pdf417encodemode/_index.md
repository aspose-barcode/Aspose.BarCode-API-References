---
title: "تعداد Pdf417EncodeMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "Aspose.BarCode.Generation.Pdf417EncodeMode enum. وضع ترميز الباركود Pdf417"
type: docs
weight: 1540
url: /ar/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

وضع ترميز الباركود Pdf417

```csharp
public enum Pdf417EncodeMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | في وضع Auto، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. يتم إعادة ترميز الأحرف Unicode باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز ECI المختار، يتم إلقاء استثناء. |
| Binary | `1` | في وضع Binary، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. إذا تم العثور على حرف Unicode، يتم إلقاء استثناء. |
| ECI | `2` | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز ECI المختار، يتم إلقاء استثناء. يرجى ملاحظة أن بعض الماسحات الضوئية القديمة (قبل 2006) قد لا تدعم هذا الوضع. |
| Extended | `3` | الوضع الموسع الذي يدعم أوضاع ECI المتعددة. |

### انظر أيضًا

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


