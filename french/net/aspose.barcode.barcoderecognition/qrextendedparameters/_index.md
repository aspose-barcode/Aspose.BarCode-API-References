---
title: "Classe QRExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.QRExtendedParameters. Stocke les informations de QR Structured Append du code-barres reconnu"
type: docs
weight: 350
url: /fr/net/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class

Stocke les informations d'ajout structuré QR du code‑à‑barres reconnu.

```csharp
public sealed class QRExtendedParameters : BaseExtendedParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ErrorLevel](../../aspose.barcode.barcoderecognition/qrextendedparameters/errorlevel/) { get; } | Niveau de correction d'erreurs Reed‑Solomon du code-barres reconnu. Du plus bas au plus haut : LevelL, LevelM, LevelQ, LevelH. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Teste si tous les paramètres n’ont que les valeurs par défaut |
| [MicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/microqrversion/) { get; } | Version du MicroQR Code reconnu. De M1 à M4. |
| [RectMicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/rectmicroqrversion/) { get; } | Version du RectMicroQR Code reconnu. De R7x43 à R17x139. |
| [StructuredAppendModeBarCodeIndex](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodeindex/) { get; } | Obtient l'index du code-barres en mode QR structured append. L'index commence à 0. La valeur par défaut est -1. |
| [StructuredAppendModeBarCodesQuantity](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodesquantity/) { get; } | Obtient la quantité de codes-barres en mode QR structured append. La valeur par défaut est -1. |
| [StructuredAppendModeParityData](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodeparitydata/) { get; } | Obtient les données de parité du mode QR structured append. La valeur par défaut est -1. |
| [Version](../../aspose.barcode.barcoderecognition/qrextendedparameters/version/) { get; } | Version du QR Code reconnu. De Version1 à Version40. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/qrextendedparameters/equals/)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de `QRExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/qrextendedparameters/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/qrextendedparameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `QRExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_equality/) | Renvoie une valeur indiquant si la première valeur `QRExtendedParameters` est égale à la seconde. |
| [operator !=](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_inequality/) | Renvoie une valeur indiquant si la première valeur `QRExtendedParameters` est différente de la seconde. |

## Exemples

Cet exemple montre comment obtenir les données QR Structured Append

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

### Voir aussi

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


