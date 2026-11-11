---
title: "BarcodeParameters.GS1CompositeBar"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarcodeParameters 속성. GS1 Composite Bar 매개변수"
type: docs
weight: 180
url: /ko/net/aspose.barcode.generation/barcodeparameters/gs1compositebar/
---
## BarcodeParameters.GS1CompositeBar property

GS1 복합 바 매개변수.

```csharp
public GS1CompositeBarParameters GS1CompositeBar { get; set; }
```

## 예제

이 샘플은 GS1 Composite Bar 이미지를 생성하고 저장하는 방법을 보여줍니다. 1D codetext와 2D codetext가 '&#x7C;' 기호로 구분된다는 점에 유의하십시오.

```csharp
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

### 또 보기

* class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


