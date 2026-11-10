---
title: "Klasse DataBarExtendedParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.DataBarExtendedParameters Klasse. Speichert zusätzliche DataBar-Informationen des erkannten Strichcodes."
type: docs
weight: 210
url: /de/net/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class

Speichert zusätzliche Informationen des erkannten DataBar‑Barcodes.

```csharp
public sealed class DataBarExtendedParameters : BaseExtendedParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Is2DCompositeComponent](../../aspose.barcode.barcoderecognition/databarextendedparameters/is2dcompositecomponent/) { get; } | Liest das DataBar-2D-Komponenten-Flag. Standardwert ist false. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Prüft, ob alle Parameter nur Standardwerte haben |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/databarextendedparameters/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `DataBarExtendedParameters`-Wert entspricht. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/databarextendedparameters/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| override [ToString](../../aspose.barcode.barcoderecognition/databarextendedparameters/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `DataBarExtendedParameters` zurück. |
| [operator ==](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_equality/) | Gibt einen Wert zurück, der angibt, ob der erste `DataBarExtendedParameters`-Wert dem zweiten entspricht. |
| [operator !=](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_inequality/) | Gibt einen Wert zurück, der angibt, ob der erste `DataBarExtendedParameters`-Wert vom zweiten abweicht. |

## Beispiele

Dieses Beispiel zeigt, wie man zusätzliche DataBar-Informationen erhält.

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

### Siehe auch

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


