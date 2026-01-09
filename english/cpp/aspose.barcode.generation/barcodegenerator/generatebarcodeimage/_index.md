---
title:  method
linktitle: GenerateBarCodeImage
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Generate the barcode image under current settings in C++.'
type: docs
weight: 800
url: /cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


Generate the barcode image under current settings.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

Barcode image. See [Bitmap](../).
## Remarks



This sample shows how to create and save a barcode image. 
```cpp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## See Also

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
