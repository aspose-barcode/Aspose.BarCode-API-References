---
title: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters κλάση"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters κλάση. Αποθηκεύει ειδικά δεδομένα του barcode 1D που αναγνωρίστηκε, όπως ξεχωριστό κείμενο κώδικα και άθροισμα ελέγχου σε C++."
type: docs
weight: 2700
url: /el/cpp/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class


Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode 1D, όπως ξεχωριστό κείμενο κώδικα και άθροισμα ελέγχου

```cpp
class OneDExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_CheckSum](./get_checksum/)() const | Λαμβάνει το άθροισμα ελέγχου για τα 1D barcodes. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** αν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [get_Value](./get_value/)() const | Λαμβάνει το κείμενο κώδικα των 1D barcodes χωρίς άθροισμα ελέγχου. |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά αυτού του [OneDExtendedParameters](./). |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να λάβετε την τιμή και το άθροισμα ελέγχου του 1D barcode.
```cpp
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

## Δείτε επίσης

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
