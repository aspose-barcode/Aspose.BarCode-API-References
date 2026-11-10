---
title: "Classe DataBarExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.DataBarExtendedParameters. Stocke des informations supplémentaires DataBar du code-barres reconnu"
type: docs
weight: 210
url: /fr/net/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class

Stocke une information supplémentaire DataBar du code‑barres reconnu

```csharp
public sealed class DataBarExtendedParameters : BaseExtendedParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Is2DCompositeComponent](../../aspose.barcode.barcoderecognition/databarextendedparameters/is2dcompositecomponent/) { get; } | Obtient le drapeau du composant composite 2D DataBar. La valeur par défaut est false. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Teste si tous les paramètres n’ont que les valeurs par défaut |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/databarextendedparameters/equals/)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur `DataBarExtendedParameters` spécifiée. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/databarextendedparameters/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/databarextendedparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `DataBarExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_equality/) | Renvoie une valeur indiquant si la première valeur `DataBarExtendedParameters` est égale à la seconde. |
| [operator !=](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_inequality/) | Renvoie une valeur indiquant si la première valeur `DataBarExtendedParameters` est différente de la seconde. |

## Exemples

Cet exemple montre comment obtenir les informations supplémentaires DataBar

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

### Voir aussi

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


