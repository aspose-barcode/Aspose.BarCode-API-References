---
title: "methode"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " method. Genereer de barcode-afbeelding met de huidige instellingen in C++."
type: docs
weight: 800
url: /nl/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


Genereer de barcode‑afbeelding met de huidige instellingen.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

Barcode-afbeelding. Zie [Bitmap](../).
## Opmerkingen



Dit voorbeeld toont hoe een barcode-afbeelding te maken en op te slaan.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## Zie ook

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
