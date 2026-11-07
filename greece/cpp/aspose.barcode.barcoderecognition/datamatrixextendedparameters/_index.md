---
title: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters κλάση"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters κλάση. Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode DataMatrix σε C++."
type: docs
weight: 1500
url: /el/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** αν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Υποδεικνύει αν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Λαμβάνει το ID του barcode [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Λαμβάνει τον αριθμό των barcode [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) σε λειτουργία structured append. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Λαμβάνει το ID του barcode [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1. |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [ToString](./tostring/)() const override | Επιστρέφει μια ανθρώπινα αναγνώσιμη αναπαράσταση συμβολοσειράς αυτού του [DataMatrixExtendedParameters](./). |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές του [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

## Δείτε επίσης

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
