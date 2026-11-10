---
title: "Klasse BarCodeRegionParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeRegionParameters Klasse. Stellt den erkannten Barcode‑Bereich und den Barcode‑Winkel dar."
type: docs
weight: 90
url: /de/net/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class

Stellt die Region des erkannten Barcodes und den Barcode‑Winkel dar.

```csharp
public sealed class BarCodeRegionParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Angle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/angle/) { get; } | Gibt den Winkel des Barcodes (0‑360) zurück. |
| [Points](../../aspose.barcode.barcoderecognition/barcoderegionparameters/points/) { get; } | Gibt das Points‑Array zurück, das den Barcode‑Bereich begrenzt. |
| [Quadrangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/quadrangle/) { get; } | Gibt [`Quadrangle`](../quadrangle/) zurück, das den Barcode‑Bereich begrenzt. |
| [Rectangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/rectangle/) { get; } | Gibt das Rectangle zurück, das den Barcode‑Bereich begrenzt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderegionparameters/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `BarCodeRegionParameters`‑Wert entspricht. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderegionparameters/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderegionparameters/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `BarCodeRegionParameters` zurück. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_equality/) | Gibt einen Wert zurück, der angibt, ob der erste `BarCodeRegionParameters`‑Wert dem zweiten entspricht. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_inequality/) | Gibt einen Wert zurück, der angibt, ob der erste `BarCodeRegionParameters`‑Wert vom zweiten abweicht. |

## Beispiele

Dieses Beispiel zeigt, wie man den Barcode‑Winkel und die begrenzenden Quadrangle‑Werte erhält.

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

### Siehe auch

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


