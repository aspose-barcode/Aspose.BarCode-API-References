---
title: "metot"
linktitle: "set_GS1CompositeBar"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " method. GS1 Composite Bar parametreleri C++'ta."
type: docs
weight: 2600
url: /tr/cpp/aspose.barcode.generation/barcodeparameters/set_gs1compositebar/
---
## BarcodeParameters::set_GS1CompositeBar method


GS1 Composite Bar parametreleri.

```cpp
void Aspose::BarCode::Generation::BarcodeParameters::set_GS1CompositeBar(System::SharedPtr<GS1CompositeBarParameters> value)
```

## Açıklamalar


Bu örnek, bir GS1 Composite Bar görüntüsünün nasıl oluşturulup kaydedileceğini gösterir. 1D kod metni ve 2D kod metninin '|' sembolüyle ayrıldığını unutmayın.
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
      using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
      {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

      // 2D bileşenin en-boy oranı
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

      // 1D ve 2D bileşenlerin X Boyutu
      generator.Parameters.Barcode.XDimension.Pixels = 3;

      // 1D bileşenin yüksekliği
      generator.Parameters.Barcode.BarHeight.Pixels = 100;

      generator.Save("test.png");
  }
```

## Ayrıca Bakınız

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
