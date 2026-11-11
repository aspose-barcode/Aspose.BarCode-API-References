---
title: "Klasse OneDExtendedParameters"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.OneDExtendedParameters‑klasse. Slaat speciale gegevens van een herkende 1D‑barcode op, zoals afzonderlijke codetekst en controlegetal."
type: docs
weight: 330
url: /nl/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

Slaat speciale gegevens op van de herkende 1D-barcode, zoals afzonderlijke codetekst en controlesom

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum/) { get; } | Haalt het controlegetal op voor 1D‑barcodes. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Test of alle parameters alleen standaardwaarden hebben |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value/) { get; } | Haalt de codetekst op van 1D‑barcodes zonder controlegetal. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals/)(object) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `OneDExtendedParameters`‑waarde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode/)() | Retourneert de hashcode voor deze instantie. |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring/)() | Retourneert een menselijk leesbare stringrepresentatie van deze `OneDExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality/) | Retourneert een waarde die aangeeft of de eerste `OneDExtendedParameters`‑waarde gelijk is aan de tweede. |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality/) | Retourneert een waarde die aangeeft of de eerste `OneDExtendedParameters`‑waarde verschilt van de tweede. |

## Voorbeelden

Dit voorbeeld toont hoe de waarde en het controlegetal van een 1D‑barcode op te halen.

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

### Zie ook

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


