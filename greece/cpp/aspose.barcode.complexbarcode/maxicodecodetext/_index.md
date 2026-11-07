---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext κλάση"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext κλάση. Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode σε C++."
type: docs
weight: 1600
url: /el/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


Βασική κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα MaxiCode.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Λαμβάνει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto. |
| [GetBarcodeType](./getbarcodetype/)() override | Λαμβάνει τον τύπο barcode. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Δημιουργεί κείμενο κώδικα |
| virtual [GetMode](./getmode/)() const | Λαμβάνει τη λειτουργία MaxiCode. |
| virtual [InitFromString](./initfromstring/)(System::String) | Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | Ορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto. |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να αποκωδικοποιήσετε ακατέργαστο κείμενο MaxiCode σε αντικείμενο [MaxiCodeCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## Δείτε επίσης

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
