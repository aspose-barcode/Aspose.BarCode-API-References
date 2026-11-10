---
title: "Απαρίθμηση BarCodeConfidence"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeConfidence απαρίθμηση. Περιέχει το επίπεδο εμπιστοσύνης αναγνώρισης."
type: docs
weight: 50
url: /el/net/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enumeration

Περιέχει το επίπεδο εμπιστοσύνης αναγνώρισης.

```csharp
public enum BarCodeConfidence
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | `0` | Εμπιστοσύνη αναγνώρισης του barcode όπου το κείμενο κώδικα δεν αναγνωρίστηκε σωστά ή το barcode εντοπίστηκε ως πιθανό ψεύτικο. |
| Moderate | `80` | Εμπιστοσύνη αναγνώρισης του barcode (κυρίως 1D barcodes) με αδύναμο άθροισμα ελέγχου ή ακόμη και χωρίς αυτό. Μπορεί να περιέχει κάποιες λανθασμένες αναγνώσεις στο κείμενο κώδικα ή ακόμη και ψεύτικες αναγνώσεις εάν είναι χαμηλό. |
| Strong | `100` | Εμπιστοσύνη αναγνώρισης που επιβεβαιώθηκε με κώδικες BCH όπως Reed–Solomon. Δεν πρέπει να υπάρχουν σφάλματα στο αναγνωσμένο κείμενο κώδικα ή ψεύτικες αναγνώσεις. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς η BarCodeConfidence άλλαξε, ανάλογα με τον τύπο του barcode.

```csharp
[C#]
//Μέτρια εμπιστοσύνη
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
    }
}

//Ισχυρή εμπιστοσύνη
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}
[VB.NET]
'Moderate confidence
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using

'Strong confidence
Using generator As New BarcodeGenerator(EncodeTypes.QR, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using
```

### Δείτε επίσης

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


