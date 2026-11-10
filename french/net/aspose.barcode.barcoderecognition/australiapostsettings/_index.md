---
title: "Classe AustraliaPostSettings"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.AustraliaPostSettings. Paramètres de décodage AustraliaPost. Contient des paramètres qui influencent les données reconnues de la symbologie AustraliaPost"
type: docs
weight: 30
url: /fr/net/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class

Paramètres de décodage AustraliaPost. Contient des paramètres qui influencent les données reconnues de la symbologie AustraliaPost.

```csharp
public sealed class AustraliaPostSettings
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CustomerInformationDecoder](../../aspose.barcode.barcoderecognition/australiapostsettings/customerinformationdecoder/) { get; set; } | Interface publique pour le décodage du champ d'information client utilisé dans la symbologie AustraliaPost. |
| [CustomerInformationInterpretingType](../../aspose.barcode.barcoderecognition/australiapostsettings/customerinformationinterpretingtype/) { get; set; } | Obtient ou définit le type d'interprétation pour l'information client du code-barres AustralianPost. La valeur par défaut est CustomerInformationInterpretingType.Other. |
| [IgnoreEndingFillingPatternsForCTable](../../aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/) { get; set; } | Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage dans le champ d'information client lors du décodage selon la méthode CTable. La méthode d'encodage CTable n'a aucun vide dans la table d'encodage et la séquence "333" des motifs de remplissage est décodée comme la lettre "z". |

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


