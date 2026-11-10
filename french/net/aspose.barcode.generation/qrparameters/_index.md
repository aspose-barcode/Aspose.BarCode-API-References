---
title: "Classe QrParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Generation.QrParameters. Paramètres QR"
type: docs
weight: 1650
url: /fr/net/aspose.barcode.generation/qrparameters/
---
## QrParameters class

Paramètres QR.

```csharp
public class QrParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/qrparameters/aspectratio/) { get; set; } | Ratio hauteur/largeur du module de code-barres 2D. |
| [ECIEncoding](../../aspose.barcode.generation/qrparameters/eciencoding/) { get; set; } | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus. Non pris en charge par MicroQR. |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/) { get; set; } | Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes-barres QR et RectMicroQR. |
| [EncodeMode](../../aspose.barcode.generation/qrparameters/encodemode/) { get; set; } | Type de symbologie QR du mode d'encodage du BarCode. Valeur par défaut : QREncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.generation/qrparameters/errorlevel/) { get; set; } | Niveau de correction d'erreur Reed-Solomon pour les codes-barres QR, MicroQR et RectMicroQR. Du plus bas au plus haut : LevelL, LevelM, LevelQ, LevelH. Voir QRErrorLevel. |
| [MicroQRVersion](../../aspose.barcode.generation/qrparameters/microqrversion/) { get; set; } | Version du code MicroQR. De la version M1 à la version M4. Valeur par défaut : MicroQRVersion.Auto. |
| [RectMicroQrVersion](../../aspose.barcode.generation/qrparameters/rectmicroqrversion/) { get; set; } | Version du code RectMicroQR. De la version R7x59 à la version R17x139. Valeur par défaut : RectMicroQRVersion.Auto. |
| [StructuredAppend](../../aspose.barcode.generation/qrparameters/structuredappend/) { get; set; } | Paramètres d'ajout structuré QR. Le mode d'ajout structuré n'est pas pris en charge par les codes-barres MicroQR et RectMicroQR. |
| [Version](../../aspose.barcode.generation/qrparameters/version/) { get; set; } | Version du code QR. De Version1 à Version40. La valeur par défaut est QRVersion.Auto. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/qrparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `QrParameters`. |

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


