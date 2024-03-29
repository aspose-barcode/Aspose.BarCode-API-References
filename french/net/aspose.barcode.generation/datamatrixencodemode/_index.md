---
title: DataMatrixEncodeMode
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Mode dencodage de lencodeur DataMatrix par défaut Auto
type: docs
weight: 670
url: /fr/net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

Mode d'encodage de l'encodeur DataMatrix, par défaut Auto

```csharp
public enum DataMatrixEncodeMode
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Auto | `0` | Sélectionne automatiquement le meilleur mode d'encodage pour l'encodage Datamatrix |
| ASCII | `1` | Encode un caractère alphanumérique ou deux caractères numériques par octet |
| Full | `6` | Encoder les valeurs 8 bits |
| Custom | `7` | Encoder avec l'encodage spécifié dans BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| C40 | `8` | Utilise l'encodage C40. Encode les caractères alphanumériques majuscules, minuscules et spéciaux |
| Text | `9` | Utilise l'encodage de texte. Encode les caractères alphanumériques minuscules, majuscules et spéciaux |
| EDIFACT | `10` | Utilise le codage EDIFACT. Utilise six bits par caractère, encode les chiffres, les lettres majuscules et de nombreux signes de ponctuation, mais ne prend pas en charge les lettres minuscules. |
| ANSIX12 | `11` | Utilise l'encodage ANSI X12. |
| ExtendedCodetext | `12` | Le mode ExtendedCodetext permet de changer manuellement les schémas d'encodage dans le codetext. |

### Voir également

* espace de noms [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
