---
title: GS1CompositeBar
second_title: Aspose.BarCode untuk .NET API Referensi
description: Parameter Batang Komposit GS1.
type: docs
weight: 170
url: /id/net/aspose.barcode.generation/barcodeparameters/gs1compositebar/
---
## BarcodeParameters.GS1CompositeBar property

Parameter Batang Komposit GS1.

```csharp
public GS1CompositeBarParameters GS1CompositeBar { get; set; }
```

### Contoh

Contoh ini menunjukkan cara membuat dan menyimpan gambar GS1 Composite Bar. Perhatikan bahwa teks kode 1D dan teks kode 2D dipisahkan dengan simbol '/'

```csharp
[C#]
  var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
  {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
      
      // Rasio aspek komponen 2D
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
          
      // Dimensi-X komponen 1D dan 2D
      generator.Parameters.Barcode.XDimension.Pixels = 3;
          
      // Tinggi komponen 1D
      generator.Parameters.Barcode.BarHeight.Pixels = 100;
      
      generator.Save("test.png");
  }
```

### Lihat juga

* class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* class [BarcodeParameters](../)
* ruang nama [Aspose.BarCode.Generation](../../barcodeparameters/)
* perakitan [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->