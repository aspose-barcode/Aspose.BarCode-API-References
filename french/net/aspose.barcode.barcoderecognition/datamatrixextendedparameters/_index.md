---
title: "Classe DataMatrixExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters. Stocke les données spéciales du code-barres DataMatrix reconnu"
type: docs
weight: 220
url: /fr/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

Stocke les données spéciales du code‑barres DataMatrix reconnu

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Teste si tous les paramètres n’ont que les valeurs par défaut |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | Indique si le code est utilisé pour instruire le lecteur à interpréter les données suivantes comme des instructions d’initialisation ou de reprogrammation du lecteur de code‑barres. La valeur par défaut est false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | Obtient l'ID du code-barres en mode Structured Append DataMatrix. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est -1. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | Obtient le nombre de codes-barres en mode Structured Append DataMatrix. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | Obtient l'ID du code-barres en mode Structured Append DataMatrix. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est -1. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée `DataMatrixExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet `DataMatrixExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | Renvoie une valeur indiquant si la première valeur `DataMatrixExtendedParameters` est égale à la seconde. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | Renvoie une valeur indiquant si la première valeur `DataMatrixExtendedParameters` est différente de la seconde. |

## Exemples

Cet exemple montre comment obtenir les valeurs brutes de DataMatrix

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

### Voir aussi

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


