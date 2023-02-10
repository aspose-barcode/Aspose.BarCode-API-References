---
title: BarCodeResult
second_title: Aspose.BarCode για Αναφορά API .NET
description: Αποθηκεύει αναγνωρισμένα δεδομένα γραμμικού κώδικα όπωςSingleDecodeType./singledecodetype/ τύποςString κείμενο κώδικα BarCodeRegionParameters./barcoderegionparameters/ περιοχή και άλλες παράμετροι
type: docs
weight: 90
url: /el/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Αποθηκεύει αναγνωρισμένα δεδομένα γραμμικού κώδικα όπως[`SingleDecodeType`](../singledecodetype/) τύπος,String κείμενο κώδικα, [`BarCodeRegionParameters`](../barcoderegionparameters/) περιοχή και άλλες παράμετροι

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [BarCodeResult](barcoderesult/)(BarCodeResult) | Δημιουργεί ένα αντίγραφο του`BarCodeResult` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes/) { get; } | Λαμβάνει τα κωδικοποιημένα byte κώδικα |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext/) { get; } | Λαμβάνει το κείμενο του κώδικα |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype/) { get; } | Λαμβάνει τον τύπο barcode |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename/) { get; } | Παίρνει το όνομα του τύπου barcode |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence/) { get; } | Λαμβάνει το επίπεδο εμπιστοσύνης αναγνώρισης του αναγνωρισμένου γραμμικού κώδικα |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended/) { get; } | Λαμβάνει εκτεταμένες παραμέτρους αναγνωρισμένου γραμμικού κώδικα |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality/) { get; } | Αποκτά την ποιότητα ανάγνωσης. Λειτουργεί για 1D και ταχυδρομικούς κώδικες. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region/) { get; } | Λαμβάνει την περιοχή του γραμμικού κώδικα |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone/)() | Δημιουργεί ένα αντίγραφο του`BarCodeResult` τάξη. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals)(BarCodeResult) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη`BarCodeResult` τιμή. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals_1)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη`BarCodeResult` τιμή. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext/)(Encoding) | Λαμβάνει το κείμενο του κώδικα με κωδικοποίηση. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την εμφάνιση. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring/)() | Επιστρέφει μια αναπαράσταση συμβολοσειράς αναγνώσιμη από τον άνθρωπο`BarCodeResult` . |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη`BarCodeResult` η τιμή είναι ίση με τη δεύτερη. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality/) | Επιστρέφει μια τιμή που υποδεικνύει αν είναι η πρώτη`BarCodeResult` η τιμή είναι διαφορετική από τη δεύτερη. |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να αποκτήσετε BarCodeResult.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* συνέλευση [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
