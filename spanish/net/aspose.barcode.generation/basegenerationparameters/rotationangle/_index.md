---
title: "BaseGenerationParameters.RotationAngle"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad BaseGenerationParameters. Ángulo de rotación de la imagen del código de barras medido en grados, p. ej. RotationAngle 0 o RotationAngle 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. Valor predeterminado 0"
type: docs
weight: 110
url: /es/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

Ángulo de rotación de la imagen del código de barras, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación. Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen. Valor predeterminado: 0.

```csharp
public float RotationAngle { get; set; }
```

## Ejemplos

Este ejemplo muestra cómo crear y guardar una imagen BarCode.

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### Ver también

* class [BaseGenerationParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


