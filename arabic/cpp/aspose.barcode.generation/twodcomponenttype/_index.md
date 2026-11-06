---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " enum. نوع المكوّن ثنائي الأبعاد في C++."
type: docs
weight: 8700
url: /ar/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


نوع المكوّن ثنائي الأبعاد

```cpp
enum class TwoDComponentType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| تلقائي | 0 | اختيار تلقائي لنوع المكوّن ثنائي الأبعاد |
| CC_A | 1 | نوع المكوّن ثنائي الأبعاد CC-A. هو متغيّر هيكلي من MicroPDF417 |
| CC_B | 2 | نوع المكوّن ثنائي الأبعاد CC-B. هو رمز MicroPDF417. |
| CC_C | 3 | نوع المكوّن ثنائي الأبعاد CC-C. هو رمز PDF417. |

## ملاحظات


يعرض هذا المثال كيفية إنشاء وحفظ صورة شريط مركب GS1. لاحظ أن نص الشيفرة 1D ونص الشيفرة 2D مفصولان بالرمز '/'
```cpp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
    using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
    {
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

    // نسبة العرض إلى الارتفاع للمكوّن ثنائي الأبعاد
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

    // البُعد X للمكوّنات 1D و 2D
    generator.Parameters.Barcode.XDimension.Pixels = 3;

    // ارتفاع المكوّن 1D
    generator.Parameters.Barcode.BarHeight.Pixels = 100;

    generator.Save("test.png");
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
