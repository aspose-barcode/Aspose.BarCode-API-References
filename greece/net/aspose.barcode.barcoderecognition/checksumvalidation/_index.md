---
title: "Απαρίθμηση ChecksumValidation"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Απαρίθμηση Aspose.BarCode.BarCodeRecognition.ChecksumValidation. Ενεργοποιεί την επικύρωση του αθροίσματος ελέγχου κατά την αναγνώριση για 1D και ταχυδρομικούς κωδικούς."
type: docs
weight: 150
url: /el/net/aspose.barcode.barcoderecognition/checksumvalidation/
---
## ChecksumValidation enumeration

Ενεργοποίηση επικύρωσης checksum κατά την αναγνώριση για 1D και Postal barcodes.

Η προεπιλογή θεωρείται Ναι για συμβολισμούς που πρέπει να περιέχουν άθροισμα ελέγχου, και Όχι όπου το άθροισμα ελέγχου είναι μόνο δυνατό.

Το άθροισμα ελέγχου δεν χρησιμοποιείται ποτέ: Codabar, PatchCode, Pharmacode, DataLogic2of5

Το checksum είναι δυνατό: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Το checksum χρησιμοποιείται πάντα: υπόλοιπες συμβολισμοί

```csharp
public enum ChecksumValidation
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Default | `0` | Εάν το checksum απαιτείται από την προδιαγραφή - θα επικυρωθεί. |
| On | `1` | Πάντα επικυρώστε το checksum εάν είναι δυνατόν. |
| Off | `2` | Μην επικυρώνετε το checksum. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει την επίδραση του ChecksumValidation στην ποιότητα και τα αποτελέσματα της αναγνώρισης

```csharp
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

### Δείτε επίσης

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


