---
title: "Κλάση BarCodeResult"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeResult class. Αποθηκεύει τα αναγνωρισμένα δεδομένα γραμμωτού κώδικα όπως τύπο SingleDecodeType, κείμενο κώδικα String, περιοχή BarCodeRegionParameters και άλλες παραμέτρους."
type: docs
weight: 100
url: /el/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

Αποθηκεύει τα αναγνωρισμένα δεδομένα γραμμωτού κώδικα όπως τύπο [`SingleDecodeType`](../singledecodetype/), κείμενο κώδικα String, περιοχή [`BarCodeRegionParameters`](../barcoderegionparameters/) και άλλες παραμέτρους.

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [BarCodeResult](barcoderesult/)(BarCodeResult) | Δημιουργεί ένα αντίγραφο της κλάσης `BarCodeResult`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes/) { get; } | Λαμβάνει τα κωδικοποιημένα bytes του κώδικα. |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext/) { get; } | Λαμβάνει το κείμενο του κώδικα. |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype/) { get; } | Λαμβάνει τον τύπο του γραμμωτού κώδικα. |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename/) { get; } | Λαμβάνει το όνομα του τύπου του γραμμωτού κώδικα. |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence/) { get; } | Λαμβάνει το επίπεδο εμπιστοσύνης αναγνώρισης του αναγνωρισμένου γραμμωτού κώδικα. |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended/) { get; } | Λαμβάνει τις εκτεταμένες παραμέτρους του αναγνωρισμένου γραμμωτού κώδικα. |
| [IsoSymbolQuality](../../aspose.barcode.barcoderecognition/barcoderesult/isosymbolquality/) { get; } | Λαμβάνει τα αποτελέσματα αξιολόγησης ποιότητας συμβόλου ISO/IEC για το αναγνωρισμένο barcode. |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality/) { get; } | Λαμβάνει την ποιότητα ανάγνωσης. Λειτουργεί για 1D και ταχυδρομικούς barcode. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region/) { get; } | Λαμβάνει την περιοχή του barcode |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone/)() | Δημιουργεί ένα αντίγραφο της κλάσης `BarCodeResult`. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals)(BarCodeResult) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `BarCodeResult`. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals_1)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `BarCodeResult`. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext/)(Encoding) | Λαμβάνει το κείμενο κώδικα με κωδικοποίηση. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς του `BarCodeResult`. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή `BarCodeResult` είναι ίση με τη δεύτερη. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality/) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή `BarCodeResult` διαφέρει από τη δεύτερη. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να αποκτήσετε το BarCodeResult.

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
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
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

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


