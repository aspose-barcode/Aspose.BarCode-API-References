---
title: "BaseGenerationParameters.RotationAngle"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BaseGenerationParameters-Eigenschaft. Rotationswinkel des BarCode-Bildes in Grad gemessen, z. B. RotationAngle 0 oder RotationAngle 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen. Standardwert 0"
type: docs
weight: 110
url: /de/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

BarCode-Bilddrehwinkel, gemessen in Grad, z. B. RotationAngle = 0 oder RotationAngle = 360 bedeutet keine Drehung. Wenn RotationAngle NICHT gleich 90, 180, 270 oder 0 ist, kann dies die Schwierigkeit für den Scanner erhöhen, das Bild zu lesen. Standardwert: 0.

```csharp
public float RotationAngle { get; set; }
```

## Beispiele

Dieses Beispiel zeigt, wie man ein BarCode‑Bild erstellt und speichert.

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### Siehe auch

* class [BaseGenerationParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


