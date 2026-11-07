---
title: "methode"
linktitle: "set_RotationAngle"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. BarCode-beeldrotatiehoek, gemeten in graden, bijv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om het beeld te lezen verhogen. Standaardwaarde: 0 in C++."
type: docs
weight: 800
url: /nl/cpp/aspose.barcode.generation/basegenerationparameters/set_rotationangle/
---
## BaseGenerationParameters::set_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
void Aspose::BarCode::Generation::BaseGenerationParameters::set_RotationAngle(float value)
```

## Opmerkingen


Dit voorbeeld toont hoe een [BarCode](../../../aspose.barcode/) afbeelding te maken en op te slaan.
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## Zie ook

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
