---
title: OneDExtendedParameters
second_title: Aspose.BarCode für .NET-API-Referenz
description: Speichert spezielle Daten von 1D-erkannten Barcodes wie separaten Codetext und Prüfsumme
type: docs
weight: 210
url: /de/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

Speichert spezielle Daten von 1D-erkannten Barcodes wie separaten Codetext und Prüfsumme

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum) { get; } | Ruft die Prüfsumme für 1D-Barcodes ab. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty) { get; } | Testet, ob alle Parameter nur Standardwerte haben |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value) { get; } | Ruft den Codetext von 1D-Barcodes ohne Prüfsumme ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einer angegebenen ist[`OneDExtendedParameters`](../onedextendedparameters) wert. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode)() | Gibt den Hashcode für diese Instanz zurück. |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring)() | Gibt eine für Menschen lesbare Zeichenfolgendarstellung davon zurück[`OneDExtendedParameters`](../onedextendedparameters) . |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality) | Gibt einen Wert zurück, der angibt, ob der erste[`OneDExtendedParameters`](../onedextendedparameters) Wert ist gleich der Sekunde. |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality) | Gibt einen Wert zurück, der angibt, ob der erste[`OneDExtendedParameters`](../onedextendedparameters) Wert unterscheidet sich vom zweiten. |

### Beispiele

Dieses Beispiel zeigt, wie man den 1D-Barcodewert und die Prüfsumme erhält

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

* class [BaseExtendedParameters](../baseextendedparameters)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* Montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->