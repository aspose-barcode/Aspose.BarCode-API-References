---
title: "Class Code128ExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.BarCodeRecognition.Code128ExtendedParameters class. Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου κωδικού Code128"
type: docs
weight: 180
url: /el/net/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class

Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Code128.

Αναπαριστά την περιοχή του αναγνωρισμένου barcode και τη γωνία του barcode.

```csharp
public sealed class Code128ExtendedParameters : BaseExtendedParameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Code128DataPortions](../../aspose.barcode.barcoderecognition/code128extendedparameters/code128dataportions/) { get; } | Λαμβάνει τον πίνακα [`Code128DataPortion`](../code128dataportion/) του αναγνωρισμένου κωδικού Code128 |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/code128extendedparameters/equals/)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `Code128ExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/code128extendedparameters/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| override [ToString](../../aspose.barcode.barcoderecognition/code128extendedparameters/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς του `Code128ExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_equality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή `Code128ExtendedParameters` είναι ίση με τη δεύτερη. |
| [operator !=](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_inequality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή `Code128ExtendedParameters` διαφέρει από τη δεύτερη. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές του code128

```csharp
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

### Δείτε επίσης

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


