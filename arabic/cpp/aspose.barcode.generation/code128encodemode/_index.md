---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "enum. وضع الترميز للباركودات Code128. مواصفة Code128 في C++."
type: docs
weight: 5900
url: /ar/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


وضع الترميز لباركودات Code128. Code 128

مواصفة.

```cpp
enum class Code128EncodeMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| تلقائي | 0 | تشفير نص الكود في وضع ISO 15417 الكلاسيكي. يجب استخدام هذا الوضع في جميع الحالات العادية. |
| CodeA | 1 | تشفير نص الكود فقط في مجموعة الرموز 128A. |
| CodeB | 2 | تشفير نص الكود فقط في مجموعة الرموز 128B. |
| CodeC | 4 | تشفير نص الكود فقط في مجموعة الرموز 128C. |
| CodeAB | 3 | تشفير نص الكود فقط في مجموعتي الرموز 128A و 128B. |
| CodeAC | 5 | تشفير نص الكود فقط في مجموعتي الرموز 128A و 128C. |
| CodeBC | 6 | تشفير نص الكود فقط في مجموعتي الرموز 128B و 128C. |

## ملاحظات


هذا الكود يوضح كيفية إنشاء رمز 128 بترميزات مختلفة
```cpp
[C#]
//إنشاء رمز 128 باستخدام ترميز ISO 15417
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//إنشاء رمز 128 فقط باستخدام ترميز مجموعة الرموز A
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
