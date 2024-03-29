---
title: AustraliaPostSettings
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Paramètres de décodage AustraliaPost. Contient des paramètres qui ont une influence sur les données reconnues de la symbologie AustraliaPost.
type: docs
weight: 30
url: /fr/net/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class

Paramètres de décodage AustraliaPost. Contient des paramètres qui ont une influence sur les données reconnues de la symbologie AustraliaPost.

```csharp
public sealed class AustraliaPostSettings
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CustomerInformationDecoder](../../aspose.barcode.barcoderecognition/australiapostsettings/customerinformationdecoder) { get; set; } | Interface publique pour le décodage des champs d'informations client qui est utilisé dans la symbologie AustraliaPost. |
| [CustomerInformationInterpretingType](../../aspose.barcode.barcoderecognition/australiapostsettings/customerinformationinterpretingtype) { get; set; } | Obtient ou définit le type d'interprétation des informations client d'AustralianPost BarCode. La valeur par défaut est CustomerInformationInterpretingType.Other. |
| [IgnoreEndingFillingPatternsForCTable](../../aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable) { get; set; } | Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers modèles de remplissage dans le champ d'informations client lors du décodage en tant que méthode CTable. La méthode d'encodage CTable n'a pas de lacunes dans la table d'encodage et la séquence "333" des modèles de remplissage est décodée en tant que lettre "z". |

### Voir également

* espace de noms [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
