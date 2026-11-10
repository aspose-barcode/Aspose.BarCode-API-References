---
title: "Κλάση DotCodeExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.BarCodeRecognition.DotCodeExtendedParameters. Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode DotCode"
type: docs
weight: 250
url: /el/net/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class

Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode DotCode.

```csharp
public sealed class DotCodeExtendedParameters : BaseExtendedParameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/isreaderinitialization/) { get; } | Υποδεικνύει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι ψευδής. |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodeid/) { get; } | Λαμβάνει το ID του barcode σε λειτουργία δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1. |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodescount/) { get; } | Λαμβάνει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/equals/)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `DotCodeExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| override [ToString](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `DotCodeExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_equality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή `DotCodeExtendedParameters` είναι ίση με τη δεύτερη. |
| [operator !=](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_inequality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή `DotCodeExtendedParameters` διαφέρει από τη δεύτερη. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές DotCode

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

### Δείτε επίσης

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


