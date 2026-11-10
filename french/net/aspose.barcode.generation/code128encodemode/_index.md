---
title: "Énumération Code128EncodeMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Énumération Aspose.BarCode.Generation.Code128EncodeMode. Mode d'encodage pour les codes-barres Code128. Spécification Code 128"
type: docs
weight: 1120
url: /fr/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Mode d'encodage pour les codes-barres Code128. Spécification [Code 128](https://en.wikipedia.org/wiki/Code_128).

```csharp
public enum Code128EncodeMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | Encode le texte du code en mode ISO 15417 classique. Ce mode doit être utilisé dans tous les cas ordinaires. |
| CodeA | `1` | Encode le texte du code uniquement dans le jeu de codes 128A. |
| CodeB | `2` | Encode le texte du code uniquement dans le jeu de codes 128B. |
| CodeC | `4` | Encode le texte du code uniquement dans le jeu de codes 128C. |
| CodeAB | `3` | Encode le texte du code uniquement dans les jeux de codes 128A et 128B. |
| CodeAC | `5` | Encode le texte du code uniquement dans les jeux de codes 128A et 128C. |
| CodeBC | `6` | Encode le texte du code uniquement dans les jeux de codes 128B et 128C. |

## Exemples

Ce code montre comment générer le code 128 avec différents encodages

```csharp
[C#]
//Générer le code 128 avec l'encodage ISO 15417
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Générer le code 128 uniquement avec l'encodage du jeu de codes A
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


