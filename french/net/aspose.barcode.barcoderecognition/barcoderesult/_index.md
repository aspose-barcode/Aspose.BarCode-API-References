---
title: BarCodeResult
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Stocke les données de code-barres reconnues telles queSingleDecodeType./singledecodetype taperString texte codé BarCodeRegionParameters./barcoderegionparameters région et autres paramètres
type: docs
weight: 90
url: /fr/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Stocke les données de code-barres reconnues telles que[`SingleDecodeType`](../singledecodetype) taper,String texte codé, [`BarCodeRegionParameters`](../barcoderegionparameters) région et autres paramètres

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [BarCodeResult](barcoderesult)(BarCodeResult) | Crée une copie du[`BarCodeResult`](../barcoderesult) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes) { get; } | Obtient les octets de code encodés |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext) { get; } | Obtient le texte du code |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype) { get; } | Obtient le type de code-barres |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename) { get; } | Obtient le nom du type de code-barres |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence) { get; } | Obtient le niveau de confiance de reconnaissance du code-barres reconnu |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended) { get; } | Obtient les paramètres étendus du code-barres reconnu |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality) { get; } | Obtient la qualité de lecture. Fonctionne pour les codes-barres 1D et postaux. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region) { get; } | Obtient la région du code-barres |

## Méthodes

| Nom | La description |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone)() | Crée une copie de[`BarCodeResult`](../barcoderesult) classe. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals)(BarCodeResult) | Renvoie une valeur indiquant si cette instance est égale à un spécifié[`BarCodeResult`](../barcoderesult) valeur. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals#equals_1)(object) | Renvoie une valeur indiquant si cette instance est égale à un spécifié[`BarCodeResult`](../barcoderesult) valeur. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext)(Encoding) | Obtient le texte du code avec encoding. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode)() | Renvoie le code de hachage pour cette instance. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce[`BarCodeResult`](../barcoderesult) . |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality) | Renvoie une valeur indiquant si le premier[`BarCodeResult`](../barcoderesult) la valeur est égale à la seconde. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality) | Renvoie une valeur indiquant si le premier[`BarCodeResult`](../barcoderesult) la valeur est différente de la seconde. |

### Exemples

Cet exemple montre comment obtenir BarCodeResult.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
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
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### Voir également

* espace de noms [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
