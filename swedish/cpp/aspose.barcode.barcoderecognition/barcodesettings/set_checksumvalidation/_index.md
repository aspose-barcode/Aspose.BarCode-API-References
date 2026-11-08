---
title: "metod"
linktitle: "set_ChecksumValidation"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder set_ChecksumValidation‑metoden i klassen Aspose::BarCode::BarCodeRecognition::BarcodeSettings i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_checksumvalidation/
---
## BarcodeSettings::set_ChecksumValidation method




```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_ChecksumValidation(Aspose::BarCode::BarCodeRecognition::ChecksumValidation value)
```

## Anmärkningar


Aktivera validering av kontrollsumma under igenkänning för 1D- och poststreckkoder.

Standard behandlas som Ja för symbologier som måste innehålla kontrollsumma, och som Nej där kontrollsumma endast är möjlig.

Kontrollsumma används aldrig: Codabar, PatchCode, Pharmacode, DataLogic2of5

Kontrollsumma är möjlig: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Kontrollsumma används alltid: Övriga symbologier

Detta exempel visar hur ChecksumValidation påverkar igenkänningskvalitet och resultat.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //kontrollsumma inaktiverad
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
    //kontrollsumma aktiverad
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


Aktivera validering av kontrollsumma under igenkänning för 1D- och poststreckkoder.
## Se även

* Enum [ChecksumValidation](../../checksumvalidation/)
* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
