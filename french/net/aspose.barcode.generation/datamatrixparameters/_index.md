---
title: "Classe DataMatrixParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Generation.DataMatrixParameters. Paramètres DataMatrix"
type: docs
weight: 1220
url: /fr/net/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class

Paramètres DataMatrix.

```csharp
public class DataMatrixParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/datamatrixparameters/aspectratio/) { get; set; } | Ratio hauteur/largeur du module de code-barres 2D. |
| [EccType](../../aspose.barcode.generation/datamatrixparameters/ecctype/) { get; set; } | Obtient ou définit un type ECC Datamatrix. Valeur par défaut : DataMatrixEccType.Ecc200. |
| [ECIEncoding](../../aspose.barcode.generation/datamatrixparameters/eciencoding/) { get; set; } | Obtient ou définit l'encodage ECI. Utilisé lorsque EncodeMode est Auto. Valeur par défaut : ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/datamatrixparameters/encodemode/) { get; set; } | Mode d’encodage du code-barres Datamatrix. Valeur par défaut : EncodeMode.Auto. |
| [IsReaderProgramming](../../aspose.barcode.generation/datamatrixparameters/isreaderprogramming/) { get; set; } | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. Valeur par défaut : false |
| [MacroCharacters](../../aspose.barcode.generation/datamatrixparameters/macrocharacters/) { get; set; } | Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Ne peut être utilisé qu'avec DataMatrixEccType.Ecc200 ou DataMatrixEccType.EccAuto. Ne peut pas être utilisé avec EncodeTypes.GS1DataMatrix Valeur par défaut : MacroCharacters.None. |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodeid/) { get; set; } | ID du code-barres pour le mode Structured Append du code-barres Datamatrix. Valeur par défaut : 0 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodescount/) { get; set; } | Nombre de codes-barres pour le mode Structured Append du code-barres Datamatrix. Valeur par défaut : 0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/datamatrixparameters/structuredappendfileid/) { get; set; } | ID de fichier pour le mode Structured Append du code-barres Datamatrix. Valeur par défaut : 0 |
| [Version](../../aspose.barcode.generation/datamatrixparameters/version/) { get; set; } | Obtient ou définit une taille de symbole Datamatrix. Valeur par défaut : Version.Auto. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/datamatrixparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `DataMatrixParameters`. |

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


