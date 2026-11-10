---
title: "تعداد Code128EncodeMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "تعداد Aspose.BarCode.Generation.Code128EncodeMode. وضع الترميز لباركودات Code128. مواصفة Code 128."
type: docs
weight: 1120
url: /ar/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

وضع الترميز لباركودات Code128. مواصفة [Code 128](https://en.wikipedia.org/wiki/Code_128).

```csharp
public enum Code128EncodeMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | ترميز نص الرمز في وضع ISO 15417 الكلاسيكي. يجب استخدام هذا الوضع في جميع الحالات العادية. |
| CodeA | `1` | ترميز نص الرمز فقط في مجموعة الرموز 128A. |
| CodeB | `2` | ترميز نص الرمز فقط في مجموعة الرموز 128B. |
| CodeC | `4` | ترميز نص الرمز فقط في مجموعة الرموز 128C. |
| CodeAB | `3` | ترميز نص الرمز فقط في مجموعتي الرموز 128A و 128B. |
| CodeAC | `5` | ترميز نص الرمز فقط في مجموعتي الرموز 128A و 128C. |
| CodeBC | `6` | ترميز نص الرمز فقط في مجموعتي الرموز 128B و 128C. |

## أمثلة

هذا الكود يوضح كيفية إنشاء code 128 بترميزات مختلفة

```csharp
[C#]
//إنشاء code 128 بترميز ISO 15417
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//إنشاء رمز 128 فقط باستخدام ترميز مجموعة الرموز A
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### انظر أيضًا

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


