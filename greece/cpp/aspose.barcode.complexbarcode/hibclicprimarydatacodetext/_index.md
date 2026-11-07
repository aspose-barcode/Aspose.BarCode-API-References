---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext κλάση"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext κλάση. Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα HIBC LIC ο οποίος αποθηκεύει τα πρωτεύοντα δεδομένα σε C++."
type: docs
weight: 900
url: /el/cpp/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class


Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC LIC που αποθηκεύει πρωτεύοντα δεδομένα.

```cpp
class HIBCLICPrimaryDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [HIBCLICPrimaryDataCodetext](./). |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Λαμβάνει τον τύπο barcode. Το κείμενο κώδικα HIBC LIC μπορεί να κωδικοποιηθεί χρησιμοποιώντας τους τύπους κωδικοποίησης HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC και HIBCQRLIC. Προεπιλεγμένη τιμή: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | Αναγνωρίζει τα πρωτεύοντα δεδομένα. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Λαμβάνει τον τύπο barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Δημιουργεί κείμενο κώδικα |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Ορίζει τον τύπο barcode. Το κείμενο κώδικα HIBC LIC μπορεί να κωδικοποιηθεί χρησιμοποιώντας τους τύπους κωδικοποίησης HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC και HIBCQRLIC. Προεπιλεγμένη τιμή: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<PrimaryData\>) | Αναγνωρίζει τα πρωτεύοντα δεδομένα. |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε το HIBC LIC χρησιμοποιώντας το [HIBCLICPrimaryDataCodetext](./).
```cpp
[C#]
HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryDataCodetext result = (HIBCLICPrimaryDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

## Δείτε επίσης

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
