---
title: "BaseGenerationParameters.RotationAngle"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BaseGenerationParameters eigenschap. Rotatiehoek van de BarCode-afbeelding gemeten in graden, bijv. RotationAngle 0 of RotationAngle 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om de afbeelding te lezen verhogen. Standaardwaarde 0"
type: docs
weight: 110
url: /nl/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

BarCode-beeldrotatiehoek, gemeten in graden, bv. RotationAngle = 0 of RotationAngle = 360 betekent geen rotatie. Als RotationAngle NIET gelijk is aan 90, 180, 270 of 0, kan dit de moeilijkheid voor de scanner om het beeld te lezen verhogen. Standaardwaarde: 0.

```csharp
public float RotationAngle { get; set; }
```

## Voorbeelden

Dit voorbeeld laat zien hoe u een BarCode‑afbeelding maakt en opslaat.

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### Zie ook

* class [BaseGenerationParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


