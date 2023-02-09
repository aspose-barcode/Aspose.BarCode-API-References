---
title: RotationAngle
second_title: Aspose.BarCode för .NET API-referens
description: BarCode bildrotationsvinkel mätt i grader t.ex. RotationAngle  0 eller RotationAngle  360 betyder ingen rotation. Om RotationAngle INTE är lika med 90 180 270 eller 0 kan det öka svårigheten för skannern att läsa bilden._x000 Standardvärde 0.
type: docs
weight: 100
url: /sv/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

BarCode bildrotationsvinkel, mätt i grader, t.ex. RotationAngle = 0 eller RotationAngle = 360 betyder ingen rotation. Om RotationAngle INTE är lika med 90, 180, 270 eller 0, kan det öka svårigheten för skannern att läsa bilden._x000 Standardvärde: 0.

```csharp
public float RotationAngle { get; set; }
```

### Exempel

Detta exempel visar hur man skapar och sparar en streckkodsbild.

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### Se även

* class [BaseGenerationParameters](../../basegenerationparameters)
* namnutrymme [Aspose.BarCode.Generation](../../basegenerationparameters)
* hopsättning [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->