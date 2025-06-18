---
title: BarcodeGenerator.GenerateBarCodeImage
second_title: Aspose.BarCode for .NET API Reference
description: BarcodeGenerator method. Generate the barcode image under current settings
type: docs
weight: 80
url: /net/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator.GenerateBarCodeImage method

Generate the barcode image under current settings.

```csharp
public Bitmap GenerateBarCodeImage()
```

### Return Value

Barcode image. See Bitmap.

## Examples

This sample shows how to create and save a barcode image.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

### See Also

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


