---
title: "Classe ComplexBarcodeGenerator"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.ComplexBarcodeGenerator. ComplexBarcodeGenerator pour la génération d'images de codes-barres complexes en backend, par ex. génération d'images SwissQR"
type: docs
weight: 510
url: /fr/net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

ComplexBarcodeGenerator pour la génération d'images de codes-barres complexes côté serveur (p. ex. SwissQR).

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator/)(IComplexCodetext) | Crée une instance de ComplexBarcodeGenerator. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters/) { get; } | Paramètres de génération. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage/)() | Génère une image de code-barres complexe avec les paramètres actuels. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_1)(string) | Génère et enregistre une image de code-barres complexe avec les paramètres actuels. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Génère et enregistre une image de code-barres complexe avec les paramètres actuels. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Génère et enregistre une image de code-barres complexe avec les paramètres actuels. |

## Exemples

Cet exemple montre comment créer et enregistrer une image SwissQR.

```csharp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // initialiser le reste des champs
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

### Voir aussi

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


