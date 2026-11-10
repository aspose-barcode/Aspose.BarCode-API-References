---
title: "Classe DotCodeExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.DotCodeExtendedParameters. Stocke les données spéciales du code‑barres DotCode reconnu"
type: docs
weight: 250
url: /fr/net/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class

Stocke les données spéciales du code‑barres DotCode reconnu

```csharp
public sealed class DotCodeExtendedParameters : BaseExtendedParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Teste si tous les paramètres n’ont que les valeurs par défaut |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/isreaderinitialization/) { get; } | Indique si le code est utilisé pour instruire le lecteur à interpréter les données suivantes comme des instructions d’initialisation ou de reprogrammation du lecteur de code‑barres. La valeur par défaut est false. |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodeid/) { get; } | Obtient l’ID du code‑barres DotCode en mode d’ajout structuré. L’ID commence à 1 et doit être inférieur ou égal au nombre de codes‑barres. La valeur par défaut est -1. |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodescount/) { get; } | Obtient le nombre de codes‑barres DotCode en mode d’ajout structuré. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/equals/)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de `DotCodeExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l’homme de ce `DotCodeExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_equality/) | Renvoie une valeur indiquant si la première valeur de `DotCodeExtendedParameters` est égale à la seconde. |
| [operator !=](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_inequality/) | Renvoie une valeur indiquant si la première valeur de `DotCodeExtendedParameters` est différente de la seconde. |

## Exemples

Cet exemple montre comment obtenir les valeurs brutes de DotCode

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

### Voir aussi

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


