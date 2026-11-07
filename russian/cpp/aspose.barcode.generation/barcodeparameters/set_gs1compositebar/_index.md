---
title: "method"
linktitle: "set_GS1CompositeBar"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Параметры GS1 Composite Bar в C++."
type: docs
weight: 2600
url: /ru/cpp/aspose.barcode.generation/barcodeparameters/set_gs1compositebar/
---
## BarcodeParameters::set_GS1CompositeBar method


Параметры GS1 Composite Bar.

```cpp
void Aspose::BarCode::Generation::BarcodeParameters::set_GS1CompositeBar(System::SharedPtr<GS1CompositeBarParameters> value)
```

## Примечания


Этот пример показывает, как создать и сохранить изображение GS1 Composite Bar. Обратите внимание, что 1D codetext и 2D codetext разделены символом '|'
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
      using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
      {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

      // Соотношение сторон 2D компонента
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

      // X-Размер 1D и 2D компонентов
      generator.Parameters.Barcode.XDimension.Pixels = 3;

      // Высота 1D компонента
      generator.Parameters.Barcode.BarHeight.Pixels = 100;

      generator.Save("test.png");
  }
```

## См. также

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
