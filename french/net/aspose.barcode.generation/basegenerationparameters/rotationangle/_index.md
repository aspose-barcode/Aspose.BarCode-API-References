---
title: "BaseGenerationParameters.RotationAngle"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété BaseGenerationParameters. Angle de rotation de l'image du code-barres mesuré en degrés, par ex. RotationAngle 0 ou RotationAngle 360 signifie aucune rotation. Si RotationAngle n'est pas égal à 90, 180, 270 ou 0, cela peut augmenter la difficulté pour le scanner de lire l'image. Valeur par défaut 0"
type: docs
weight: 110
url: /fr/net/aspose.barcode.generation/basegenerationparameters/rotationangle/
---
## BaseGenerationParameters.RotationAngle property

Angle de rotation de l'image du code-barres, mesuré en degrés, par ex. RotationAngle = 0 ou RotationAngle = 360 signifie aucune rotation. Si RotationAngle n'est PAS égal à 90, 180, 270 ou 0, cela peut augmenter la difficulté pour le scanner de lire l'image. Valeur par défaut : 0.

```csharp
public float RotationAngle { get; set; }
```

## Exemples

Cet exemple montre comment créer et enregistrer une image BarCode.

```csharp
[C#]
  using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
  {
      generator.Parameters.RotationAngle = 7f;
      generator.Save("test.png");
  }
```

### Voir aussi

* class [BaseGenerationParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


