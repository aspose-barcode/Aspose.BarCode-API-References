---
title: "Énumération MaxiCodeMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Enum Aspose.BarCode.Generation.MaxiCodeMode. Mode d'encodage pour les codes-barres MaxiCode"
type: docs
weight: 1480
url: /fr/net/aspose.barcode.generation/maxicodemode/
---
## MaxiCodeMode enumeration

Mode d'encodage pour les codes-barres MaxiCode.

```csharp
public enum MaxiCodeMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Mode2 | `2` | Le mode 2 encode les informations postales dans le premier message et les données dans le deuxième message. Il possède un code postal à 9 chiffres (utilisé uniquement aux États‑Unis). |
| Mode3 | `3` | Le mode 3 encode les informations postales dans le premier message et les données dans le deuxième message. Il possède un code postal alphanumérique à 6 caractères, utilisé dans le monde. |
| Mode4 | `4` | Le mode 4 encode les données dans le premier et le deuxième message, avec une correction ECC courte. |
| Mode5 | `5` | Le mode 5 encode les données dans le premier et le deuxième message, avec une correction ECC longue. |
| Mode6 | `6` | Le mode 6 encode les données dans le premier et le deuxième message, avec une correction ECC courte. Utilisé pour encoder l'appareil. |

## Exemples

Cet exemple montre comment générer des codes-barres MaxiCode en utilisant ComplexBarcodeGenerator

```csharp
[C#]
//Mode 2 avec message secondaire standard
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 2 avec message secondaire structuré
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 3 avec message secondaire standard
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 3 avec message secondaire structuré
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 4
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode4;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//Mode 5
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode5;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
} 
//Mode 6
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode6;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
} 
```

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


