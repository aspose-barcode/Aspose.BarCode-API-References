---
title: "Aufzählung ChecksumValidation"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.BarCodeRecognition.ChecksumValidation-Enum. Aktivieren Sie die Prüfsummenvalidierung während der Erkennung für 1D- und Post-Barcode."
type: docs
weight: 150
url: /de/net/aspose.barcode.barcoderecognition/checksumvalidation/
---
## ChecksumValidation enumeration

Aktiviert die Prüfsummenvalidierung während der Erkennung für 1D‑ und Post‑Barcodes.

Standard wird als Ja behandelt für Symbologien, die eine Prüfsumme enthalten müssen, und als Nein, wo eine Prüfsumme nur möglich ist.

Prüfsumme wird nie verwendet: Codabar, PatchCode, Pharmacode, DataLogic2of5

Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Prüfsumme wird immer verwendet: übrige Symbologien

```csharp
public enum ChecksumValidation
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Default | `0` | Wenn die Prüfsumme gemäß der Spezifikation erforderlich ist, wird sie validiert. |
| On | `1` | Prüfsumme immer validieren, wenn möglich. |
| Off | `2` | Prüfsumme nicht validieren. |

## Beispiele

Dieses Beispiel zeigt den Einfluss von ChecksumValidation auf die Erkennungsqualität und die Ergebnisse

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //Prüfsumme deaktiviert
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //Prüfsumme aktiviert
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
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
    'checksum disabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum enabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### Siehe auch

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


