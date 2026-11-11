---
title: "Class Code128ExtendedParameters"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.Code128ExtendedParameters class. Slaat speciale gegevens op van de herkende Code128-barcode."
type: docs
weight: 180
url: /nl/net/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class

Slaat speciale gegevens op van de herkende Code128 barcode

Stelt de regio en hoek van de herkende barcode voor

```csharp
public sealed class Code128ExtendedParameters : BaseExtendedParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Code128DataPortions](../../aspose.barcode.barcoderecognition/code128extendedparameters/code128dataportions/) { get; } | Haalt de [`Code128DataPortion`](../code128dataportion/) array op van de herkende Code128-barcode |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Test of alle parameters alleen standaardwaarden hebben |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/code128extendedparameters/equals/)(object) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `Code128ExtendedParameters`‑waarde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/code128extendedparameters/gethashcode/)() | Retourneert de hashcode voor deze instantie. |
| override [ToString](../../aspose.barcode.barcoderecognition/code128extendedparameters/tostring/)() | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `Code128ExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_equality/) | Retourneert een waarde die aangeeft of de eerste `Code128ExtendedParameters`‑waarde gelijk is aan de tweede. |
| [operator !=](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_inequality/) | Retourneert een waarde die aangeeft of de eerste `Code128ExtendedParameters`‑waarde verschilt van de tweede. |

## Voorbeelden

Deze voorbeeld toont hoe ruwe code128‑waarden op te halen

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

### Zie ook

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


