---
title: "Classe BarCodeResult"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeResult class. Stocke les données de code-barres reconnues comme le type SingleDecodeType, String codetext, BarCodeRegionParameters region et d'autres paramètres."
type: docs
weight: 100
url: /fr/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Stocke les données de code-barres reconnues comme le type [`SingleDecodeType`](../singledecodetype/), String codetext, [`BarCodeRegionParameters`](../barcoderegionparameters/) region et d'autres paramètres.

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BarCodeResult](barcoderesult/)(BarCodeResult) | Crée une copie de la classe `BarCodeResult`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes/) { get; } | Obtient les octets du code encodé |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext/) { get; } | Obtient le texte du code |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype/) { get; } | Obtient le type de code-barres |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename/) { get; } | Obtient le nom du type de code-barres |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence/) { get; } | Obtient le niveau de confiance de la reconnaissance du code-barres reconnu |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended/) { get; } | Obtient les paramètres étendus du code-barres reconnu |
| [IsoSymbolQuality](../../aspose.barcode.barcoderecognition/barcoderesult/isosymbolquality/) { get; } | Obtient les résultats d'évaluation de la qualité du symbole ISO/IEC pour le code-barres reconnu. |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality/) { get; } | Obtient la qualité de lecture. Fonctionne pour les codes-barres 1D et postaux. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region/) { get; } | Obtient la région du code-barres |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone/)() | Crée une copie de la classe `BarCodeResult`. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals)(BarCodeResult) | Renvoie une valeur indiquant si cette instance est égale à une valeur `BarCodeResult` spécifiée. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals_1)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur `BarCodeResult` spécifiée. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext/)(Encoding) | Obtient le texte du code avec l'encodage. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `BarCodeResult`. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality/) | Renvoie une valeur indiquant si la première valeur `BarCodeResult` est égale à la seconde. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality/) | Renvoie une valeur indiquant si la première valeur `BarCodeResult` est différente de la seconde. |

## Exemples

Cet exemple montre comment obtenir BarCodeResult.

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
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


