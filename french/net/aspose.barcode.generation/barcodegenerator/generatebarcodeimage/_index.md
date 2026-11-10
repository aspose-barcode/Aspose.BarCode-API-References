---
title: "BarcodeGenerator.GenerateBarCodeImage"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Méthode BarcodeGenerator. Génère l’image du code-barres avec les paramètres actuels"
type: docs
weight: 80
url: /fr/net/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator.GenerateBarCodeImage method

Génère l'image du code-barres avec les paramètres actuels.

```csharp
public Bitmap GenerateBarCodeImage()
```

### Valeur de retour

Image de code-barres. Voir Bitmap.

## Exemples

Cet exemple montre comment créer et enregistrer une image de code-barres.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

### Voir aussi

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


