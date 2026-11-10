---
title: "Κλάση BaseDecodeType"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.BarCodeRecognition.BaseDecodeType κλάση. Βασική κλάση για MultiDecodeType και SingleDecodeType"
type: docs
weight: 130
url: /el/net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

Βασική κλάση για MultiDecodeType και SingleDecodeType.

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany/)(params BaseDecodeType[]) | Καθορίζει εάν κάποιο από τους δεδομένους τύπους αποκωδικοποίησης περιλαμβάνεται στο |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals)(BaseDecodeType) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `BaseDecodeType`. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_1)(MultiDecodeType) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [`MultiDecodeType`](../multidecodetype/). |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_3)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `BaseDecodeType`. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_2)(SingleDecodeType) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [`SingleDecodeType`](../singledecodetype/). |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse)(string, out BaseDecodeType) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός BaseDecodeType στην παρουσία του, αφού έχει προσδιοριστεί ο συγκεκριμένος τύπος. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_1)(string, out MultiDecodeType) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός MultiDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_2)(string, out SingleDecodeType) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το BaseDecodeType με το SingleDecodeType και το MultiDecodeType.

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

### Δείτε επίσης

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


