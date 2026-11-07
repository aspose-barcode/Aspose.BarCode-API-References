---
title: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class. Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Code128 σε C++."
type: docs
weight: 1300
url: /el/cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Code128

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() const | Λαμβάνει τον πίνακα [Code128DataPortion](../code128dataportion/) του αναγνωρισμένου barcode Code128. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** αν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά αυτού του [Code128ExtendedParameters](./). |
## Σχόλια


Αντιπροσωπεύει την περιοχή του αναγνωρισμένου barcode και τη γωνία του barcode

Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές του code128
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

## Δείτε επίσης

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
