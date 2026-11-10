---
title: "Classe BarCodeRegionParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.BarCodeRegionParameters. Représente la région des codes-barres reconnus et l'angle du code-barres"
type: docs
weight: 90
url: /fr/net/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class

Représente la région du code‑barres reconnu et l'angle du code‑barres

```csharp
public sealed class BarCodeRegionParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Angle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/angle/) { get; } | Obtient l'angle du code-barres (0-360). |
| [Points](../../aspose.barcode.barcoderecognition/barcoderegionparameters/points/) { get; } | Obtient le tableau Points délimitant la région du code-barres |
| [Quadrangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/quadrangle/) { get; } | Obtient le [`Quadrangle`](../quadrangle/) délimitant la région du code-barres |
| [Rectangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/rectangle/) { get; } | Obtient le Rectangle délimitant la région du code-barres |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderegionparameters/equals/)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur `BarCodeRegionParameters` spécifiée. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderegionparameters/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderegionparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `BarCodeRegionParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_equality/) | Renvoie une valeur indiquant si la première valeur `BarCodeRegionParameters` est égale à la seconde. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_inequality/) | Renvoie une valeur indiquant si la première valeur `BarCodeRegionParameters` est différente de la seconde. |

## Exemples

Cet exemple montre comment obtenir l'angle du code-barres et les valeurs du quadrilatère délimitant

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


