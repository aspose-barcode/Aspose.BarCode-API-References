---
title: BarCodeRegionParameters
second_title: Aspose.BarCode voor .NET API-referentie
description: Vertegenwoordigt het herkende streepjescodegebied en de hoek van de streepjescode
type: docs
weight: 80
url: /nl/net/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class

Vertegenwoordigt het herkende streepjescodegebied en de hoek van de streepjescode

```csharp
public sealed class BarCodeRegionParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Angle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/angle/) { get; } | Krijgt de hoek van de streepjescode (0-360). |
| [Points](../../aspose.barcode.barcoderecognition/barcoderegionparameters/points/) { get; } | KrijgtPoints array begrenzend streepjescodegebied |
| [Quadrangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/quadrangle/) { get; } | Krijgt[`Quadrangle`](../quadrangle/) begrenzend streepjescodegebied |
| [Rectangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/rectangle/) { get; } | KrijgtRectangle begrenzend streepjescodegebied |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderegionparameters/equals/)(object) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven`BarCodeRegionParameters` waarde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderegionparameters/gethashcode/)() | Retourneert de hash-code voor deze instantie. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderegionparameters/tostring/)() | Retourneert hiervan een door mensen leesbare tekenreeksrepresentatie`BarCodeRegionParameters` . |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_equality/) | Retourneert een waarde die aangeeft of de eerste`BarCodeRegionParameters` waarde is gelijk aan de seconde. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_inequality/) | Retourneert een waarde die aangeeft of de eerste`BarCodeRegionParameters` waarde is anders dan de tweede. |

### Voorbeelden

Dit voorbeeld laat zien hoe u waarden voor een streepjescodehoek en begrenzende vierhoek kunt verkrijgen

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
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

### Zie ook

* naamruimte [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
