---
title: "Κλάση OneDExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.BarCodeRecognition.OneDExtendedParameters. Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου 1D barcode όπως το ξεχωριστό κείμενο κώδικα και το checksum."
type: docs
weight: 330
url: /el/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

Αποθηκεύει ειδικά δεδομένα του 1D barcode που αναγνωρίστηκε, όπως ξεχωριστό κείμενο κώδικα και checksum.

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum/) { get; } | Λαμβάνει το checksum για 1D barcodes. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value/) { get; } | Λαμβάνει το κείμενο κώδικα των 1D barcodes χωρίς checksum. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals/)(object) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `OneDExtendedParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `OneDExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality/) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρώτη τιμή `OneDExtendedParameters` είναι ίση με τη δεύτερη. |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality/) | Επιστρέφει μια τιμή που υποδεικνύει αν η πρώτη τιμή `OneDExtendedParameters` διαφέρει από τη δεύτερη. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να λάβετε την τιμή και το checksum του 1D barcode.

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
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


