---
title: "Enum EnableChecksum"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.Generation.EnableChecksum enum. Activer la somme de contrôle pendant la génération pour les codes-barres 1D"
type: docs
weight: 1280
url: /fr/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

Activer la somme de contrôle lors de la génération des codes-barres 1D.

Par défaut, il est considéré comme Oui pour les symbologies qui doivent contenir un checksum, et comme Non lorsque le checksum n'est possible que.

Somme de contrôle jamais utilisée : Codabar

La somme de contrôle est possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Somme de contrôle toujours utilisée : le reste des symbologies

```csharp
public enum EnableChecksum
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Default | `0` | Si la somme de contrôle est requise par la spécification, elle sera ajoutée. |
| Yes | `1` | Utilisez toujours la somme de contrôle si possible. |
| No | `2` | N'utilisez pas la somme de contrôle. |

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


