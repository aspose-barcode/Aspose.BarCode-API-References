---
title: "μέθοδος"
linktitle: "set_ChecksumValidation"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε τη μέθοδο set_ChecksumValidation της κλάσης Aspose::BarCode::BarCodeRecognition::BarcodeSettings σε C++."
type: docs
weight: 200
url: /el/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_checksumvalidation/
---
## BarcodeSettings::set_ChecksumValidation method




```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_ChecksumValidation(Aspose::BarCode::BarCodeRecognition::ChecksumValidation value)
```

## Σχόλια


Ενεργοποιήστε την επικύρωση checksum κατά την αναγνώριση για 1D και ταχυδρομικούς barcode.

Η προεπιλογή αντιμετωπίζεται ως Ναι για τις συμβολές που πρέπει να περιέχουν checksum, ως Όχι όπου το checksum είναι μόνο δυνατό.

Checksum δεν χρησιμοποιείται ποτέ: Codabar, PatchCode, Pharmacode, DataLogic2of5

Checksum είναι δυνατό: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum πάντα χρησιμοποιείται: Οι υπόλοιπες συμβολές

Αυτό το παράδειγμα δείχνει την επίδραση του ChecksumValidation στην ποιότητα και τα αποτελέσματα της αναγνώρισης
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //checksum απενεργοποιημένο
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
    //checksum ενεργοποιημένο
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


Ενεργοποιήστε την επικύρωση checksum κατά την αναγνώριση για 1D και ταχυδρομικούς barcode.
## Δείτε επίσης

* Enum [ChecksumValidation](../../checksumvalidation/)
* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
