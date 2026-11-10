---
title: "Classe FontUnit"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.Generation.FontUnit classe. Définit un format particulier pour le texte incluant la taille de la police et les attributs de style où la taille se trouve dans la propriété Unit value."
type: docs
weight: 1320
url: /fr/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

Définit un format particulier pour le texte, incluant la police, la taille et les attributs de style où la taille se trouve dans la propriété Unit value.

```csharp
public sealed class FontUnit
```

## Propriétés

| Nom | Description |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname/) { get; set; } | Obtient ou définit le nom de la police de ce Font. |
| [Size](../../aspose.barcode.generation/fontunit/size/) { get; } | Obtient ou définit la taille de ce FontUnit dans la propriété Unit value. |
| [Style](../../aspose.barcode.generation/fontunit/style/) { get; set; } | Obtient ou définit les informations de style pour ce FontUnit. |

## Exemples

Cet exemple montre comment créer et enregistrer une image BarCode.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


