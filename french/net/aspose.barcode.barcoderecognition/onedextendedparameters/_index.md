---
title: OneDExtendedParameters
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Stocke les données spéciales du code-barres reconnu 1D comme le texte de code séparé et la somme de contrôle
type: docs
weight: 210
url: /fr/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

Stocke les données spéciales du code-barres reconnu 1D comme le texte de code séparé et la somme de contrôle

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## Propriétés

| Nom | La description |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum) { get; } | Obtient la somme de contrôle pour les codes-barres 1D. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | Teste si tous les paramètres n'ont que des valeurs par défaut |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value) { get; } | Obtient le texte de code des codes-barres 1D sans somme de contrôle. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals)(object) | Renvoie une valeur indiquant si cette instance est égale à un spécifié[`OneDExtendedParameters`](../onedextendedparameters) valeur. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode)() | Renvoie le code de hachage pour cette instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce[`OneDExtendedParameters`](../onedextendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality) | Renvoie une valeur indiquant si le premier[`OneDExtendedParameters`](../onedextendedparameters) la valeur est égale à la seconde. |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality) | Renvoie une valeur indiquant si le premier[`OneDExtendedParameters`](../onedextendedparameters) la valeur est différente de la seconde. |

### Exemples

Cet exemple montre comment obtenir la valeur du code-barres 1D et la somme de contrôle

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

### Voir également

* class [BaseExtendedParameters](../baseextendedparameters)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
