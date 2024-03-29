---
title: Unit
second_title: Aspose.BarCode لمرجع .NET API
description: يحدد قيمة الحجم بوحدات مختلفة بكسل  بوصة  إلخ. .
type: docs
weight: 990
url: /ar/net/aspose.barcode.generation/unit/
---
## Unit class

يحدد قيمة الحجم بوحدات مختلفة (بكسل ، بوصة ، إلخ.) .

```csharp
public sealed class Unit
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document) { get; set; } | الحصول على أو تعيين قيمة الحجم في وحدات المستند. |
| [Inches](../../aspose.barcode.generation/unit/inches) { get; set; } | الحصول على أو تعيين قيمة الحجم بالبوصة . |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters) { get; set; } | الحصول على أو تعيين قيمة الحجم بالميليمترات . |
| [Pixels](../../aspose.barcode.generation/unit/pixels) { get; set; } | الحصول على أو تعيين قيمة الحجم بالبكسل . |
| [Point](../../aspose.barcode.generation/unit/point) { get; set; } | الحصول على أو تعيين قيمة الحجم بالنقطة . |
| [Resolution](../../aspose.barcode.generation/unit/resolution) { get; } | القرار |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals)(object) | لتحديد ما إذا كان هذا المثيل وكائن محدد ، والذي يجب أن يكون أيضًا ملف[`Unit`](../unit) الكائن ، له نفس القيمة. |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode)() | إرجاع رمز التجزئة لهذا الكائن. |
| override [ToString](../../aspose.barcode.generation/unit/tostring)() | إرجاع تمثيل سلسلة يمكن قراءته من قبل الإنسان[`Unit`](../unit) . |

### أمثلة

يوضح هذا النموذج كيفية إنشاء صورة BarCode وحفظها.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### أنظر أيضا

* مساحة الاسم [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* المجسم [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
