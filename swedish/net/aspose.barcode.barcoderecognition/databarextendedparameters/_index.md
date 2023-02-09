---
title: DataBarExtendedParameters
second_title: Aspose.BarCode för .NET API-referens
description: Lagrar en DataBar ytterligare information om igenkänd streckkod
type: docs
weight: 180
url: /sv/net/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class

Lagrar en DataBar ytterligare information om igenkänd streckkod

```csharp
public sealed class DataBarExtendedParameters : BaseExtendedParameters
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Is2DCompositeComponent](../../aspose.barcode.barcoderecognition/databarextendedparameters/is2dcompositecomponent) { get; } | Hämtar DataBar 2D-kompositkomponentflaggan. Standardvärdet är falskt. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | Testar om alla parametrar bara har standardvärden |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/databarextendedparameters/equals)(object) | Returnerar ett värde som anger om denna instans är lika med en specificerad[`DataBarExtendedParameters`](../databarextendedparameters) värde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/databarextendedparameters/gethashcode)() | Returnerar hashkoden för denna instans. |
| override [ToString](../../aspose.barcode.barcoderecognition/databarextendedparameters/tostring)() | Returnerar en mänsklig läsbar strängrepresentation av detta[`DataBarExtendedParameters`](../databarextendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_equality) | Returnerar ett värde som anger om det första[`DataBarExtendedParameters`](../databarextendedparameters) värdet är lika med sekunden. |
| [operator !=](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_inequality) | Returnerar ett värde som anger om det första[`DataBarExtendedParameters`](../databarextendedparameters) värdet skiljer sig från det andra. |

### Exempel

Detta exempel visar hur du får DataBar ytterligare information

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

### Se även

* class [BaseExtendedParameters](../baseextendedparameters)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->