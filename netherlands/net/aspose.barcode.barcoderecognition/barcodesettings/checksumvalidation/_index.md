---
title: ChecksumValidation
second_title: Aspose.BarCode voor .NET API-referentie
description: Checksumvalidatie inschakelen tijdens herkenning voor 1D en Postalstreepjescodes.
type: docs
weight: 20
url: /nl/net/aspose.barcode.barcoderecognition/barcodesettings/checksumvalidation/
---
## BarcodeSettings.ChecksumValidation property

Checksum-validatie inschakelen tijdens herkenning voor 1D- en Postal-streepjescodes.

Standaard wordt behandeld als Ja voor symbolieken die checksum moeten bevatten, als Nee waar checksum alleen mogelijk is.

Checksum nooit gebruikt: Codabar, PatchCode, Pharmacode, DataLogic2of5

Checksum is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum altijd gebruikt: Rest symbologieën

```csharp
public ChecksumValidation ChecksumValidation { get; set; }
```

### Eigendoms-waarde

Checksum-validatie inschakelen tijdens herkenning voor 1D- en Postal-streepjescodes.

### Voorbeelden

Dit voorbeeld toont de invloed van ChecksumValidation op de herkenningskwaliteit en resultaten

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    // controlesom uitgeschakeld
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
    // controlesom ingeschakeld
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
    'controlesom uitgeschakeld
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'controlesom ingeschakeld
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### Zie ook

* enum [ChecksumValidation](../../checksumvalidation/)
* class [BarcodeSettings](../)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../barcodesettings/)
* montage [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
