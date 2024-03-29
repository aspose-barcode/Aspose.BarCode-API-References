---
title: FontUnit
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Définit un format particulier pour le texte y compris le type de police la taille et les attributs de style où taille dans la propriété de valeur dunité.
type: docs
weight: 750
url: /fr/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

Définit un format particulier pour le texte, y compris le type de police, la taille et les attributs de style où taille dans la propriété de valeur d'unité.

```csharp
public sealed class FontUnit
```

## Propriétés

| Nom | La description |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname) { get; set; } | Obtient ou définit le nom du visage de cette police. |
| [Size](../../aspose.barcode.generation/fontunit/size) { get; } | Obtient ou définit la taille de cette FontUnit en valeur d'unité. |
| [Style](../../aspose.barcode.generation/fontunit/style) { get; set; } | Obtient ou définit les informations de style pour cette FontUnit. |

### Exemples

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

### Voir également

* espace de noms [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
