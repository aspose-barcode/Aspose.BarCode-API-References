---
title: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext κλάση"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext κλάση. Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC PAS σε C++."
type: docs
weight: 1100
url: /el/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC PAS.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | Προσθέτει νέα εγγραφή |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | Προσθέτει νέα εγγραφή |
| [Clear](./clear/)() | Καθαρίζει τη λίστα εγγραφών |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [HIBCPASCodetext](./). |
| [get_BarcodeType](./get_barcodetype/)() const | Λαμβάνει τον τύπο barcode. HIBC PAS codetext μπορεί να κωδικοποιηθεί χρησιμοποιώντας τους τύπους κωδικοποίησης HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS και HIBCQRPAS. Προεπιλεγμένη τιμή: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | Αναγνωρίζει τη θέση των δεδομένων. |
| [GetBarcodeType](./getbarcodetype/)() override | Λαμβάνει τον τύπο barcode. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Δημιουργεί κείμενο κώδικα |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [GetRecords](./getrecords/)() | Λαμβάνει τη λίστα εγγραφών |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Αρχικοποιεί την παρουσία από το δημιουργημένο κείμενο κώδικα. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Ορίζει τον τύπο barcode. HIBC PAS codetext μπορεί να κωδικοποιηθεί χρησιμοποιώντας τους τύπους κωδικοποίησης HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS και HIBCQRPAS. Προεπιλεγμένη τιμή: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | Αναγνωρίζει τη θέση των δεδομένων. |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να κωδικοποιήσετε και να αποκωδικοποιήσετε HIBC PAS χρησιμοποιώντας το [HIBCPASCodetext](./).
```cpp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
            HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
        Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

## Δείτε επίσης

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
