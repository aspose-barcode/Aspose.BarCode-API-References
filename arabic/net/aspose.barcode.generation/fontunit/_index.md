---
title: FontUnit
second_title: Aspose.BarCode لمرجع .NET API
description: يحدد تنسيقًا معينًا للنص  بما في ذلك سمات الخط والحجم والنمط حيث الحجم في خاصية قيمة الوحدة.
type: docs
weight: 750
url: /ar/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

يحدد تنسيقًا معينًا للنص ، بما في ذلك سمات الخط والحجم والنمط حيث الحجم في خاصية قيمة الوحدة.

```csharp
public sealed class FontUnit
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname) { get; set; } | الحصول على أو تحديد اسم الوجه لهذا الخط . |
| [Size](../../aspose.barcode.generation/fontunit/size) { get; } | الحصول على أو تعيين حجم FontUnit في قيمة الوحدة. |
| [Style](../../aspose.barcode.generation/fontunit/style) { get; set; } | الحصول على معلومات النمط أو تعيينها لوحدة الخط هذه. |

### أمثلة

يوضح هذا النموذج كيفية إنشاء صورة BarCode وحفظها.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### أنظر أيضا

* مساحة الاسم [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* المجسم [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
