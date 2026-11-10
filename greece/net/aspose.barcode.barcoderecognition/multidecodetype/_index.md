---
title: "Κλάση MultiDecodeType"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.BarCodeRecognition.MultiDecodeType. Σύνθετος τύπος αποκωδικοποίησης"
type: docs
weight: 320
url: /el/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

Τύπος αποκωδικοποίησης Composite.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `MultiDecodeType`. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `MultiDecodeType`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | Επιστρέφει έναν αριθμό μεμονωμένων τύπων. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | Προσθέτει έναν ακόμη [`SingleDecodeType`](../singledecodetype/) στο MultiDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | Ελέγξτε αν αυτό περιέχει όλους τους τύπους από τους τύπους barcode. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | Περιέχει κάποιον από τους τύπους |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Επιστρέφει τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [`BaseDecodeType`](../basedecodetype/). |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `MultiDecodeType`. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή `MultiDecodeType`. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η συλλογή τύπων αποκωδικοποίησης περιέχει μόνο την καθορισμένη τιμή [`SingleDecodeType`](../singledecodetype/). |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | Εξαιρεί το [`SingleDecodeType`](../singledecodetype/) από το MultiDecodeType και επιστρέφει νέα παρουσία MultiDecodeType. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Αναπαριστά μια λίστα μεμονωμένων τύπων. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | Υπερκαθορισμένη μέθοδος που αναπαριστά το MultiDecodeType ως συμβολοσειρά. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός MultiDecodeType στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε σύνθετους τύπους MultiDecode που συνδυάζουν SingleDecodeType και τύπους MultiDecode.

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### Δείτε επίσης

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


