---
title: "메서드"
linktitle: "get_GS1CompositeBar"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: " 메서드. GS1 Composite Bar 매개변수 C++에서."
type: docs
weight: 2500
url: /ko/cpp/aspose.barcode.generation/barcodeparameters/get_gs1compositebar/
---
## BarcodeParameters::get_GS1CompositeBar method


GS1 복합 바 매개변수.

```cpp
System::SharedPtr<GS1CompositeBarParameters> Aspose::BarCode::Generation::BarcodeParameters::get_GS1CompositeBar() const
```

## 비고


이 샘플은 GS1 Composite Bar 이미지를 생성하고 저장하는 방법을 보여줍니다. 1D 코드텍스트와 2D 코드텍스트가 '|' 기호로 구분된다는 점에 유의하십시오.
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
      using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
      {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

      // 2D 구성 요소의 종횡비
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

      // 1D 및 2D 구성 요소의 X-차원
      generator.Parameters.Barcode.XDimension.Pixels = 3;

      // 1D 구성 요소의 높이
      generator.Parameters.Barcode.BarHeight.Pixels = 100;

      generator.Save("test.png");
  }
```

## 또 보기

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
