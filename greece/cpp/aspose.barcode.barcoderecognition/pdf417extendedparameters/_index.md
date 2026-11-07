---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters κλάση"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters κλάση. Αποθηκεύει πληροφορίες μεταδεδομένων MacroPdf417 ενός αναγνωρισμένου barcode σε C++."
type: docs
weight: 2800
url: /el/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


Αποθηκεύει μεταδεδομένα MacroPdf417 του αναγνωρισμένου barcode

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Σημαία που υποδεικνύει ότι το MicroPdf417 barcode κωδικοποιήθηκε με τις λέξεις κώδικα 908, 909, 910 ή 911 προσομοίωσης Code 128. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** αν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [get_IsLinked](./get_islinked/)() const | Σημαία που υποδεικνύει ότι το barcode πρέπει να συνδεθεί με 1D barcode. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Όνομα παραλήπτη Macro PDF417 (προαιρετικό). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Άθροισμα ελέγχου Macro PDF417 (προαιρετικό). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | Λαμβάνει το ID αρχείου του barcode, διαθέσιμο μόνο με MacroPdf417. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Όνομα αρχείου Macro PDF417 (προαιρετικό). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Μέγεθος αρχείου Macro PDF417 (προαιρετικό). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | Λαμβάνει το ID τμήματος του barcode, διαθέσιμο μόνο με MacroPdf417. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Λαμβάνει τον αριθμό τμημάτων του macro pdf417 barcode. Η προεπιλεγμένη τιμή είναι -1. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Όνομα αποστολέα Macro PDF417 (προαιρετικό). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Δείχνει αν το τμήμα είναι το τελευταίο τμήμα ενός αρχείου Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Χρονική σήμανση Macro PDF417 (προαιρετικό). |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά αυτού του [Pdf417ExtendedParameters](./). |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να λάβετε τα μεταδεδομένα Macro Pdf417
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

## Δείτε επίσης

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
