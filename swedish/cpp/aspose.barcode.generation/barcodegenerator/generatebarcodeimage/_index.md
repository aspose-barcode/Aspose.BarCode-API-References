---
title: "metod"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Generera streckkodsbild med aktuella inställningar i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


Generera streckkodsbilden med de aktuella inställningarna.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

Streckkodbild. Se [Bitmap](../).
## Anmärkningar



Detta exempel visar hur man skapar och sparar en streckkodsbild.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## Se även

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
