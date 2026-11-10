---
title: "Κλάση DataMatrixExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters. Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode DataMatrix"
type: docs
weight: 220
url: /el/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode DataMatrix.

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | Υποδεικνύει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι ψευδής. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | Λαμβάνει το ID του barcode DataMatrix σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | Λαμβάνει τον αριθμό των barcode σε λειτουργία structured append του DataMatrix. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | Λαμβάνει το ID του barcode DataMatrix σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το αντικείμενο είναι ίσο με μια καθορισμένη τιμή `DataMatrixExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς του `DataMatrixExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του `DataMatrixExtendedParameters` είναι ίση με τη δεύτερη. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του `DataMatrixExtendedParameters` διαφέρει από τη δεύτερη. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές του DataMatrix

```csharp
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

### Δείτε επίσης

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


