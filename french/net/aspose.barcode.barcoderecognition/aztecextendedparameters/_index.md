---
title: "Classe AztecExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.BarCodeRecognition.AztecExtendedParameters classe. Stocke les données spéciales du code‑à‑barres Aztec reconnu"
type: docs
weight: 40
url: /fr/net/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class

Stocke les données spéciales du code‑barres Aztec reconnu

```csharp
public sealed class AztecExtendedParameters : BaseExtendedParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Teste si tous les paramètres n’ont que les valeurs par défaut |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/aztecextendedparameters/isreaderinitialization/) { get; } | Indique si le code est utilisé pour instruire le lecteur à interpréter les données suivantes comme des instructions d’initialisation ou de reprogrammation du lecteur de code‑barres. La valeur par défaut est false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodeid/) { get; } | Obtient l'ID du code‑à‑barres Aztec en mode ajout structuré. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes‑à‑barres. La valeur par défaut est 0. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodescount/) { get; } | Obtient le nombre de codes‑à‑barres Aztec en mode ajout structuré. La valeur par défaut est 0. Le nombre doit être compris entre 1 et 26. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendfileid/) { get; } | Obtient l'ID du fichier du mode ajout structuré Aztec. La valeur par défaut est une chaîne vide |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/aztecextendedparameters/equals/)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de `AztecExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/aztecextendedparameters/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/aztecextendedparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible de cet `AztecExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_equality/) | Renvoie une valeur indiquant si la première valeur `AztecExtendedParameters` est égale à la seconde. |
| [operator !=](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_inequality/) | Renvoie une valeur indiquant si la première valeur `AztecExtendedParameters` est différente de la seconde. |

## Exemples

Cet exemple montre comment obtenir les valeurs brutes Aztec

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

### Voir aussi

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


