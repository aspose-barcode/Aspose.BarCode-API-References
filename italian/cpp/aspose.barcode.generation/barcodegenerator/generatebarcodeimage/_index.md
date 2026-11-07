---
title: "method"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Genera l'immagine del codice a barre con le impostazioni correnti in C++."
type: docs
weight: 800
url: /it/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


Genera l'immagine del codice a barre con le impostazioni correnti.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

Immagine del codice a barre. Vedi [Bitmap](../).
## Osservazioni



Questo esempio mostra come creare e salvare un'immagine di codice a barre.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## Vedi anche

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
