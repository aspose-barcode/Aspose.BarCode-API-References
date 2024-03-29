---
title: ChecksumValidation
second_title: Aspose.BarCode für .NET-API-Referenz
description: Aktivieren Sie die Prüfsummenvalidierung während der Erkennung für 1D- und Post-Barcodes.
type: docs
weight: 20
url: /de/net/aspose.barcode.barcoderecognition/barcodesettings/checksumvalidation/
---
## BarcodeSettings.ChecksumValidation property

Aktivieren Sie die Prüfsummenvalidierung während der Erkennung für 1D- und Post-Barcodes.

Der Standardwert wird für Symbologien, die eine Prüfsumme enthalten müssen, als Ja behandelt, als Nein, wenn nur eine Prüfsumme möglich ist.

Nie verwendete Prüfsumme: Codabar, PatchCode, Pharmacode, DataLogic2of5

Prüfsumme möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Immer verwendete Prüfsumme: Restsymbologien

```csharp
public ChecksumValidation ChecksumValidation { get; set; }
```

### Eigentumswert

Aktivieren Sie die Prüfsummenvalidierung während der Erkennung für 1D- und Post-Barcodes.

### Beispiele

Dieses Beispiel zeigt den Einfluss von ChecksumValidation auf die Erkennungsqualität und die Ergebnisse

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    // Prüfsumme deaktiviert
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
    // Prüfsumme aktiviert
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
    'Prüfsumme deaktiviert
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'Prüfsumme aktiviert
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### Siehe auch

* enum [ChecksumValidation](../../checksumvalidation)
* class [BarcodeSettings](../../barcodesettings)
* namensraum [Aspose.BarCode.BarCodeRecognition](../../barcodesettings)
* Montage [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
