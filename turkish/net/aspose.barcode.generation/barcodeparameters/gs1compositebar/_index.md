---
title: "BarcodeParameters.GS1CompositeBar"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarcodeParameters özelliği. GS1 Composite Bar parametreleri"
type: docs
weight: 180
url: /tr/net/aspose.barcode.generation/barcodeparameters/gs1compositebar/
---
## BarcodeParameters.GS1CompositeBar property

GS1 Bileşik Çubuk parametreleri.

```csharp
public GS1CompositeBarParameters GS1CompositeBar { get; set; }
```

## Örnekler

Bu örnek, bir GS1 Composite Bar görüntüsü oluşturmayı ve kaydetmeyi gösterir. 1D kod metni ve 2D kod metninin '&#x7C;' sembolüyle ayrıldığını unutmayın.

```csharp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
  {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
      
      // 2D bileşenin en-boy oranı
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
          
      // 1D ve 2D bileşenlerin X-Boyutu
      generator.Parameters.Barcode.XDimension.Pixels = 3;
          
      // 1D bileşenin yüksekliği
      generator.Parameters.Barcode.BarHeight.Pixels = 100;
      
      generator.Save("test.png");
  }
```

### Ayrıca Bakınız

* class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


