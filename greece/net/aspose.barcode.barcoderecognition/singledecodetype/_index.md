---
title: "Κλάση SingleDecodeType"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.BarCodeRecognition.SingleDecodeType κλάση. Τύπος μονής αποκωδικοποίησης. Δείτε τον τύπο αποκωδικοποίησης για να λάβετε την παρουσία."
type: docs
weight: 390
url: /el/net/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class

Τύπος αποκωδικοποίησης Single. Δείτε τον τύπο αποκωδικοποίησης για να λάβετε την παρουσία.

```csharp
public sealed class SingleDecodeType : BaseDecodeType, IEquatable<SingleDecodeType>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | Λαμβάνει έναν δείκτη του τύπου αποκωδικοποίησης |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | Λαμβάνει ένα όνομα του τύπου αποκωδικοποίησης |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | Μετατρέπει την αναπαράσταση συμβολοσειράς του ονόματος ενός SingleDecodeType στην παρουσία του. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | Επιστρέφει τιμή που υποδεικνύει εάν αυτή η παρουσία περιλαμβάνεται στη συγκεκριμένη λίστα. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Επιστρέφει τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [`BaseDecodeType`](../basedecodetype/). |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_1)(MultiDecodeType) | Επιστρέφει τιμή που υποδεικνύει εάν η καθορισμένη συλλογή [`MultiDecodeType`](../multidecodetype/) περιέχει μόνο αυτόν τον τύπο αποκωδικοποίησης. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | Επιστρέφει τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `SingleDecodeType`. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | Επιστρέφει τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `SingleDecodeType`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | Μετατρέπει την παρουσία του SingleDecodeType στην ισοδύναμη αναπαράσταση συμβολοσειράς. Η μορφή συμβολοσειράς είναι: "Index:-1; Name:None". |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | Επιστρέφει το όνομα του δεδομένου SingleDecodeType ως συμβολοσειρά. |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | Μετατρέπει την παρουσία του SingleDecodeType στην ισοδύναμη αναπαράσταση συμβολοσειράς. Η μορφή συμβολοσειράς είναι: "Index:-1; Name:None". |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να λάβετε την παρουσία του τύπου μονής αποκωδικοποίησης.

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### Δείτε επίσης

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


