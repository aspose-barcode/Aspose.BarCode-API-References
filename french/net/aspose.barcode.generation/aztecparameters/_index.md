---
title: "Classe AztecParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Generation.AztecParameters. Paramètres Aztec"
type: docs
weight: 960
url: /fr/net/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class

Paramètres Aztec.

```csharp
public class AztecParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/aztecparameters/aspectratio/) { get; set; } | Ratio hauteur/largeur du module de code-barres 2D. |
| [ECIEncoding](../../aspose.barcode.generation/aztecparameters/eciencoding/) { get; set; } | Obtient ou définit le codage ECI. Utilisé lorsque AztecEncodeMode est Auto. Valeur par défaut : ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/aztecparameters/encodemode/) { get; set; } | Obtient ou définit un mode d’encodage Aztec. Valeur par défaut : Auto. |
| [ErrorLevel](../../aspose.barcode.generation/aztecparameters/errorlevel/) { get; set; } | Niveau de correction d'erreur des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95. |
| [IsReaderInitialization](../../aspose.barcode.generation/aztecparameters/isreaderinitialization/) { get; set; } | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [LayersCount](../../aspose.barcode.generation/aztecparameters/layerscount/) { get; set; } | Obtient ou définit le nombre de couches du symbole Aztec. Le nombre de couches doit être compris entre 1 et 3 pour le mode Compact et entre 1 et 32 pour le mode Full Range. Valeur par défaut : 0 (auto). |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/aztecparameters/structuredappendbarcodeid/) { get; set; } | Identifiant du code-barres pour le mode Structured Append du code-barres Aztec. L’identifiant du code-barres doit être compris entre 1 et le nombre de codes-barres. Valeur par défaut : 0 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/aztecparameters/structuredappendbarcodescount/) { get; set; } | Nombre de codes-barres pour le mode Structured Append du code Aztec. Le nombre de codes-barres doit être compris entre 1 et 26. Valeur par défaut : 0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/aztecparameters/structuredappendfileid/) { get; set; } | Identifiant de fichier pour le mode Structured Append du code Aztec (champ facultatif). L'identifiant de fichier ne doit pas contenir d'espaces. Valeur par défaut : chaîne vide |
| [SymbolMode](../../aspose.barcode.generation/aztecparameters/symbolmode/) { get; set; } | Obtient ou définit le mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/aztecparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible de cet `AztecParameters`. |

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


