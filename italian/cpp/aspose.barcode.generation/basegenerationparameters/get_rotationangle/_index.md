---
title: "method"
linktitle: "get_RotationAngle"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Angolo di rotazione dell'immagine BarCode, misurato in gradi, ad es. RotationAngle = 0 o RotationAngle = 360 significa nessuna rotazione. Se RotationAngle NON è uguale a 90, 180, 270 o 0, può aumentare la difficoltà per lo scanner nel leggere l'immagine. Valore predefinito: 0 in C++."
type: docs
weight: 700
url: /it/cpp/aspose.barcode.generation/basegenerationparameters/get_rotationangle/
---
## BaseGenerationParameters::get_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
float Aspose::BarCode::Generation::BaseGenerationParameters::get_RotationAngle() const
```

## Osservazioni


Questo esempio mostra come creare e salvare un'immagine [BarCode](../../../aspose.barcode/).
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## Vedi anche

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
