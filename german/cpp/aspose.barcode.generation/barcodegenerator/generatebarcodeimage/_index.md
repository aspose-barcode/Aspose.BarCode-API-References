---
title: "Methode"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Barcode-Bild mit den aktuellen Einstellungen in C++ erzeugen."
type: docs
weight: 800
url: /de/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


Erstelle das Barcode-Bild mit den aktuellen Einstellungen.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

Barcode-Bild. Siehe [Bitmap](../).
## Hinweise



Dieses Beispiel zeigt, wie man ein Barcode-Bild erstellt und speichert.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## Siehe auch

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
