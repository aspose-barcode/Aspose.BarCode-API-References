---
title: "Classe OneDExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.OneDExtendedParameters. Stocke des données spéciales du code-barres 1D reconnu comme le texte du code séparé et la somme de contrôle."
type: docs
weight: 330
url: /fr/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

Stocke les données spéciales du code‑à‑barres 1D reconnu, comme le texte du code séparé et la somme de contrôle.

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum/) { get; } | Obtient la somme de contrôle pour les codes-barres 1D. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Teste si tous les paramètres n’ont que les valeurs par défaut |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value/) { get; } | Obtient le texte du code des codes-barres 1D sans somme de contrôle. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals/)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur `OneDExtendedParameters` spécifiée. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `OneDExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality/) | Renvoie une valeur indiquant si la première valeur `OneDExtendedParameters` est égale à la seconde. |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality/) | Renvoie une valeur indiquant si la première valeur `OneDExtendedParameters` est différente de la seconde. |

## Exemples

Cet exemple montre comment obtenir la valeur et la somme de contrôle d'un code-barres 1D.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### Voir aussi

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


