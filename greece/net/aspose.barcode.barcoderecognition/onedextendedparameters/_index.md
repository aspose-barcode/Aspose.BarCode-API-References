---
title: OneDExtendedParameters
second_title: Aspose.BarCode για Αναφορά API .NET
description: Αποθηκεύει ειδικά δεδομένα αναγνωρισμένου γραμμωτού κώδικα 1D όπως ξεχωριστό κείμενο κωδικού και checksum
type: docs
weight: 230
url: /el/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

Αποθηκεύει ειδικά δεδομένα αναγνωρισμένου γραμμωτού κώδικα 1D, όπως ξεχωριστό κείμενο κωδικού και checksum

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum/) { get; } | Λαμβάνει το άθροισμα ελέγχου για γραμμωτούς κώδικες 1D. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Ελέγχει εάν όλες οι παράμετροι έχουν μόνο προεπιλεγμένες τιμές |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value/) { get; } | Λαμβάνει το κωδικοποιημένο κείμενο των γραμμωτών κωδίκων 1D χωρίς άθροισμα ελέγχου. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals/)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη`OneDExtendedParameters` τιμή. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την εμφάνιση. |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring/)() | Επιστρέφει μια αναπαράσταση συμβολοσειράς αναγνώσιμη από τον άνθρωπο`OneDExtendedParameters` . |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη`OneDExtendedParameters` η τιμή είναι ίση με τη δεύτερη. |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality/) | Επιστρέφει μια τιμή που υποδεικνύει αν είναι η πρώτη`OneDExtendedParameters` η τιμή είναι διαφορετική από τη δεύτερη. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να λάβετε τιμή γραμμικού κώδικα 1D και checksum

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### Δείτε επίσης

* class [BaseExtendedParameters](../baseextendedparameters/)
* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* συνέλευση [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->