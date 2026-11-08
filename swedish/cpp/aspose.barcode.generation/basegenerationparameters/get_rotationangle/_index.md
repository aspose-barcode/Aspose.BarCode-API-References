---
title: "metod"
linktitle: "get_RotationAngle"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. BarCode-bildens rotationsvinkel, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation. Om RotationAngle INTE är lika med 90, 180, 270 eller 0 kan det öka svårigheten för skannern att läsa bilden. Standardvärde: 0 i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.barcode.generation/basegenerationparameters/get_rotationangle/
---
## BaseGenerationParameters::get_RotationAngle method


[BarCode](../../../aspose.barcode/) image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```cpp
float Aspose::BarCode::Generation::BaseGenerationParameters::get_RotationAngle() const
```

## Anmärkningar


Detta exempel visar hur man skapar och sparar en [BarCode](../../../aspose.barcode/) bild.
```cpp
[C#]
      using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
      {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

## Se även

* Class [BaseGenerationParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
