---
title: "Klasse QRExtendedParameters"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.QRExtendedParameters class. Slaat QR Structured Append-informatie op van de herkende barcode."
type: docs
weight: 350
url: /nl/net/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class

Slaat QR Structured Append-informatie op van de herkende barcode

```csharp
public sealed class QRExtendedParameters : BaseExtendedParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ErrorLevel](../../aspose.barcode.barcoderecognition/qrextendedparameters/errorlevel/) { get; } | Reed-Solomon-foutcorrectieniveau van de herkende barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Test of alle parameters alleen standaardwaarden hebben |
| [MicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/microqrversion/) { get; } | Versie van de herkende MicroQR Code. Van M1 tot M4. |
| [RectMicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/rectmicroqrversion/) { get; } | Versie van de herkende RectMicroQR Code. Van R7x43 tot R17x139. |
| [StructuredAppendModeBarCodeIndex](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodeindex/) { get; } | Haalt de index op van de QR structured append-modusbarcode. Index begint bij 0. Standaardwaarde is -1. |
| [StructuredAppendModeBarCodesQuantity](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodesquantity/) { get; } | Haalt de hoeveelheid QR structured append-modusbarcodes op. Standaardwaarde is -1. |
| [StructuredAppendModeParityData](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodeparitydata/) { get; } | Haalt de pariteitsgegevens van de QR structured append-modus op. Standaardwaarde is -1. |
| [Version](../../aspose.barcode.barcoderecognition/qrextendedparameters/version/) { get; } | Versie van de herkende QR Code. Van Versie1 tot Versie40. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/qrextendedparameters/equals/)(object) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `QRExtendedParameters`-waarde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/qrextendedparameters/gethashcode/)() | Retourneert de hashcode voor deze instantie. |
| override [ToString](../../aspose.barcode.barcoderecognition/qrextendedparameters/tostring/)() | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `QRExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_equality/) | Geeft een waarde terug die aangeeft of de eerste `QRExtendedParameters`-waarde gelijk is aan de tweede. |
| [operator !=](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_inequality/) | Geeft een waarde terug die aangeeft of de eerste `QRExtendedParameters`-waarde verschilt van de tweede. |

## Voorbeelden

Dit voorbeeld toont hoe QR Structured Append-gegevens op te halen

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

### Zie ook

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


