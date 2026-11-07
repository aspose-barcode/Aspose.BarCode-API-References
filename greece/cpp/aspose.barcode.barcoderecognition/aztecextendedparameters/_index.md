---
title: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class. Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Aztec σε C++."
type: docs
weight: 300
url: /el/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Aztec

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** αν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Υποδεικνύει αν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Λαμβάνει το ID του barcode σε λειτουργία δομημένης προσθήκης Aztec. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι 0. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Λαμβάνει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης Aztec. Η προεπιλεγμένη τιμή είναι 0. Ο αριθμός πρέπει να είναι τιμή από 1 έως 26. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Λαμβάνει το ID αρχείου της λειτουργίας δομημένης προσθήκης Aztec. Η προεπιλεγμένη τιμή είναι κενή συμβολοσειρά |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [AztecExtendedParameters](./). |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές Aztec.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## Δείτε επίσης

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
