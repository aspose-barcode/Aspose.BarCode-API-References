---
title: "BarcodeParameters.IsChecksumEnabled"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "BarcodeParameters propriété. Activer la somme de contrôle lors de la génération de codes-barres 1D"
type: docs
weight: 200
url: /fr/net/aspose.barcode.generation/barcodeparameters/ischecksumenabled/
---
## BarcodeParameters.IsChecksumEnabled property

Activer la somme de contrôle lors de la génération des codes-barres 1D.

Par défaut, il est considéré comme Oui pour les symbologies qui doivent contenir une somme de contrôle, et comme Non lorsque la somme de contrôle n'est possible que facultativement.

La somme de contrôle est possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Somme de contrôle toujours utilisée : le reste des symbologies

```csharp
public EnableChecksum IsChecksumEnabled { get; set; }
```

### Voir aussi

* enum [EnableChecksum](../../enablechecksum/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


