---
title: "Κλάση BarCodeRegionParameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.BarCodeRecognition.BarCodeRegionParameters. Αντιπροσωπεύει την περιοχή των αναγνωρισμένων barcode και τη γωνία του barcode"
type: docs
weight: 90
url: /el/net/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class

Αναπαριστά την περιοχή του αναγνωρισμένου barcode και τη γωνία του barcode.

```csharp
public sealed class BarCodeRegionParameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Angle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/angle/) { get; } | Λαμβάνει τη γωνία του barcode (0-360). |
| [Points](../../aspose.barcode.barcoderecognition/barcoderegionparameters/points/) { get; } | Λαμβάνει τον πίνακα Points που οριοθετεί την περιοχή του barcode |
| [Quadrangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/quadrangle/) { get; } | Λαμβάνει το [`Quadrangle`](../quadrangle/) που οριοθετεί την περιοχή του barcode |
| [Rectangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/rectangle/) { get; } | Λαμβάνει το Rectangle που οριοθετεί την περιοχή του barcode |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderegionparameters/equals/)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `BarCodeRegionParameters`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderegionparameters/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderegionparameters/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το `BarCodeRegionParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_equality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή `BarCodeRegionParameters` είναι ίση με τη δεύτερη. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_inequality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή `BarCodeRegionParameters` διαφέρει από τη δεύτερη. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να λάβετε τη γωνία του barcode και τις τιμές του οριακού τετραγώνου.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

### Δείτε επίσης

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


