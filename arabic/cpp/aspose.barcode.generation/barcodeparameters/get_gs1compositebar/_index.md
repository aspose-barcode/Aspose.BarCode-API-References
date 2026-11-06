---
title: "طريقة"
linktitle: "get_GS1CompositeBar"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. معلمات GS1 Composite Bar في C++."
type: docs
weight: 2500
url: /ar/cpp/aspose.barcode.generation/barcodeparameters/get_gs1compositebar/
---
## BarcodeParameters::get_GS1CompositeBar method


معلمات شريط GS1 Composite.

```cpp
System::SharedPtr<GS1CompositeBarParameters> Aspose::BarCode::Generation::BarcodeParameters::get_GS1CompositeBar() const
```

## ملاحظات


هذا المثال يوضح كيفية إنشاء وحفظ صورة GS1 Composite Bar. لاحظ أن نص الرمز 1D ونص الرمز 2D مفصولان بالرمز '|'
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
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

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
