---
title: "Klasse OneDExtendedParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.OneDExtendedParameters Klasse. Speichert spezielle Daten von 1D‑erkannten Barcodes, wie separaten Codetext und Prüfsumme."
type: docs
weight: 330
url: /de/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

Speichert spezielle Daten des erkannten 1D‑Barcodes, wie separaten Codetext und Prüfsumme.

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum/) { get; } | Ermittelt die Prüfsumme für 1D‑Barcodes. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Prüft, ob alle Parameter nur Standardwerte haben |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value/) { get; } | Ermittelt den Codetext von 1D‑Barcodes ohne Prüfsumme. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `OneDExtendedParameters`‑Wert entspricht. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `OneDExtendedParameters` zurück. |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality/) | Gibt einen Wert zurück, der angibt, ob der erste `OneDExtendedParameters`‑Wert dem zweiten entspricht. |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality/) | Gibt einen Wert zurück, der angibt, ob der erste `OneDExtendedParameters`‑Wert vom zweiten abweicht. |

## Beispiele

Dieses Beispiel zeigt, wie man den Wert und die Prüfsumme eines 1D‑Barcodes erhält.

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

### Siehe auch

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


