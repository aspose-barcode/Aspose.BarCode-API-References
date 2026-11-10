---
title: "Κλάση Pdf417ExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.BarCodeRecognition.Pdf417ExtendedParameters. Αποθηκεύει πληροφορίες μεταδεδομένων MacroPdf417 του αναγνωρισμένου barcode."
type: docs
weight: 340
url: /el/net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

Αποθηκεύει μεταδεδομένα MacroPdf417 του barcode που αναγνωρίστηκε.

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [IsCode128Emulation](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/iscode128emulation/) { get; } | Σημαία που υποδεικνύει ότι το barcode MicroPdf417 κωδικοποιήθηκε με τις λέξεις-κλειδιά εξομοίωσης Code 128 908, 909, 910 ή 911. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [IsLinked](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/islinked/) { get; } | Σημαία που υποδεικνύει ότι το barcode πρέπει να συνδεθεί με 1D barcode. |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/isreaderinitialization/) { get; } | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee/) { get; } | Όνομα παραλήπτη Macro PDF417 (προαιρετικό). |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum/) { get; } | Checksum Macro PDF417 (προαιρετικό). |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid/) { get; } | Λαμβάνει το αναγνωριστικό αρχείου του barcode, διαθέσιμο μόνο με MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename/) { get; } | Όνομα αρχείου Macro PDF417 (προαιρετικό). |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize/) { get; } | Μέγεθος αρχείου Macro PDF417 (προαιρετικό). |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid/) { get; } | Λαμβάνει το αναγνωριστικό τμήματος του barcode, διαθέσιμο μόνο με MacroPdf417. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount/) { get; } | Λαμβάνει τον αριθμό τμημάτων του barcode macro pdf417. Η προεπιλεγμένη τιμή είναι -1. |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender/) { get; } | Όνομα αποστολέα Macro PDF417 (προαιρετικό). |
| [MacroPdf417Terminator](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417terminator/) { get; } | Δείχνει αν το τμήμα είναι το τελευταίο τμήμα ενός αρχείου Macro PDF417. |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp/) { get; } | Χρονική σήμανση Macro PDF417 (προαιρετικό). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals/)(object) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `Pdf417ExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `Pdf417ExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality/) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρώτη τιμή `Pdf417ExtendedParameters` είναι ίση με τη δεύτερη. |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality/) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρώτη τιμή `Pdf417ExtendedParameters` διαφέρει από τη δεύτερη. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να λάβετε τα μεταδεδομένα Macro Pdf417

```csharp
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

### Δείτε επίσης

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


