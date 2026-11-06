---
title: "طريقة"
linktitle: "set_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام طريقة set_EncodeGS1SeparatorInByteMode في فئة Aspose::BarCode::Generation::QrParameters في C++."
type: docs
weight: 1800
url: /ar/cpp/aspose.barcode.generation/qrparameters/set_encodegs1separatorinbytemode/
---
## QrParameters::set_EncodeGS1SeparatorInByteMode method




```cpp
void Aspose::BarCode::Generation::QrParameters::set_EncodeGS1SeparatorInByteMode(bool value)
```

## ملاحظات


يضبط قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة بـ GS1 في وضع البايت للباركود QR و RectMicroQR.

إذا كان false، قد يتم ترميز فواصل GS1 كـ '' في وضع الحروف الأبجدية الرقمية وفقًا لمواصفة QR.

إذا كان true، يتم ترميز فواصل مجموعة GS1 في وضع البايت كحرف 0x1D، وتُرمَّز الأحرف '' أيضًا في وضع البايت للحفاظ عليها كبيانات.

قد يحسن هذا الخيار التوافق مع أجهزة فك الترميز التي تتوقع فواصل مجموعة GS1 على مستوى البايت ويمنع تفسير أحرف البيانات '' كفواصل GS1.
## انظر أيضًا

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
