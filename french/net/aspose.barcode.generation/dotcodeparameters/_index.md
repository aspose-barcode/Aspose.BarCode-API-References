---
title: "Classe DotCodeParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.Generation.DotCodeParameters classe. Paramètres DotCode"
type: docs
weight: 1260
url: /fr/net/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class

Paramètres DotCode.

```csharp
public class DotCodeParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/dotcodeparameters/aspectratio/) { get; set; } | Ratio hauteur/largeur du module de code-barres 2D. |
| [Columns](../../aspose.barcode.generation/dotcodeparameters/columns/) { get; set; } | Identifie le nombre de colonnes. La somme du nombre de lignes et du nombre de colonnes d'un symbole DotCode doit être impaire. Le nombre de colonnes doit être au moins de 5. Valeur par défaut : -1 |
| [ECIEncoding](../../aspose.barcode.generation/dotcodeparameters/eciencoding/) { get; set; } | Identifie l'encodage ECI. Utilisé lorsque DotCodeEncodeMode est Auto. Valeur par défaut : ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/dotcodeparameters/encodemode/) { get; set; } | Identifie le mode d'encodage DotCode. Valeur par défaut : Auto. |
| [IsReaderInitialization](../../aspose.barcode.generation/dotcodeparameters/isreaderinitialization/) { get; set; } | Indique si le code est utilisé pour instruire le lecteur à interpréter les données suivantes comme des instructions d’initialisation ou de reprogrammation du lecteur de code‑barres. La valeur par défaut est false. |
| [Rows](../../aspose.barcode.generation/dotcodeparameters/rows/) { get; set; } | Identifie le nombre de lignes. La somme du nombre de lignes et du nombre de colonnes d'un symbole DotCode doit être impaire. Le nombre de lignes doit être au moins de 5. Valeur par défaut : -1 |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.generation/dotcodeparameters/structuredappendmodebarcodeid/) { get; set; } | Identifie l'ID du code-barres en mode d'ajout structuré DotCode. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. Valeur par défaut : -1. |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.generation/dotcodeparameters/structuredappendmodebarcodescount/) { get; set; } | Identifie le nombre de codes-barres en mode d'ajout structuré DotCode. Valeur par défaut : -1. Le nombre doit être compris entre 1 et 35. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/dotcodeparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `DotCodeParameters`. |

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


