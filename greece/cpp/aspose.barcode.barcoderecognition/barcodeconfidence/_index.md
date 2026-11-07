---
title: "enum"
linktitle: "BarCodeConfidence"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " enum. Περιέχει το επίπεδο εμπιστοσύνης αναγνώρισης σε C++."
type: docs
weight: 3500
url: /el/cpp/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enum


Περιέχει το επίπεδο εμπιστοσύνης αναγνώρισης

```cpp
enum class BarCodeConfidence : int32_t
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | 0 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) εμπιστοσύνη του barcode όπου το κείμενο κώδικα δεν αναγνωρίστηκε σωστά ή το barcode εντοπίστηκε ως πιθανή ψεύτικη |
|  | Moderate | 80 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) εμπιστοσύνη του barcode (κυρίως 1D barcodes) με αδύναμο checksum ή ακόμη και χωρίς αυτό. Μπορεί να περιέχει κάποιες λανθασμένες αναγνώσεις στο κείμενο κώδικα ή ακόμη και ψεύτικες αναγνώσεις εάν |

είναι χαμηλή |
| Strong | 100 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) εμπιστοσύνη που επιβεβαιώθηκε με κώδικες BCH όπως Reed–Solomon. Δεν πρέπει να υπάρχουν σφάλματα στο αναγνωσμένο κείμενο κώδικα ή ψεύτικες αναγνώσεις |

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς η BarCodeConfidence άλλαξε, ανάλογα με τον τύπο του barcode
```cpp
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

## Δείτε επίσης

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
