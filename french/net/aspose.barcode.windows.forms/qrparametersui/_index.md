---
title: "Classe QrParametersUI"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Windows.Forms.QrParametersUI. Enveloppe UI pour la classe QrParameters"
type: docs
weight: 1870
url: /fr/net/aspose.barcode.windows.forms/qrparametersui/
---
## QrParametersUI class

Enveloppe UI pour la classe [`QrParameters`](../../aspose.barcode.generation/qrparameters/).

```csharp
public class QrParametersUI
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/qrparametersui/aspectratio/) { get; set; } | Ratio hauteur/largeur du module de code-barres 2D. |
| [ECIEncoding](../../aspose.barcode.windows.forms/qrparametersui/eciencoding/) { get; set; } | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus. Non pris en charge par MicroQR. |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.windows.forms/qrparametersui/encodegs1separatorinbytemode/) { get; set; } | Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes-barres QR et RectMicroQR. |
| [EncodeMode](../../aspose.barcode.windows.forms/qrparametersui/encodemode/) { get; set; } | Type de symbologie QR du mode d'encodage du BarCode. Valeur par défaut : QREncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.windows.forms/qrparametersui/errorlevel/) { get; set; } | Niveau de correction d'erreurs Reed‑Solomon pour les codes-barres QR, MicroQR et RectMicroQR. Du plus bas au plus haut : LevelL, LevelM, LevelQ, LevelH. voir QRErrorLevel. |
| [MicroQrVersion](../../aspose.barcode.windows.forms/qrparametersui/microqrversion/) { get; set; } | Version du code MicroQR. De la version M1 à la version M4. Valeur par défaut : MicroQRVersion.Auto. |
| [RectMicroQrVersion](../../aspose.barcode.windows.forms/qrparametersui/rectmicroqrversion/) { get; set; } | Version du code RectMicroQR. De la version R7x59 à la version R17x139. Valeur par défaut : RectMicroQRVersion.Auto. |
| [Version](../../aspose.barcode.windows.forms/qrparametersui/version/) { get; set; } | Version du code QR. De Version1 à Version40 pour le code QR et de M1 à M4 pour MicroQr. Valeur par défaut : QRVersion.Auto. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/qrparametersui/tostring/)() | Renvoie une représentation sous forme de chaîne lisible de cet [`QrParameters`](../../aspose.barcode.generation/qrparameters/). |

### Voir aussi

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


