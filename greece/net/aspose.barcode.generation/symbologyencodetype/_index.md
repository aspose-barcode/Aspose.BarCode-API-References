---
title: "Κλάση SymbologyEncodeType"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.SymbologyEncodeType κλάση. Τύπος κωδικοποίησης συμβολισμού. Δείτε το EncodeTypes για να λάβετε ένα στιγμιότυπο."
type: docs
weight: 1710
url: /el/net/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class

Τύπος κωδικοποίησης συμβολισμού. Δείτε το EncodeTypes για να λάβετε την παρουσία.

```csharp
public class SymbologyEncodeType : BaseEncodeType
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Classification](../../aspose.barcode.generation/baseencodetype/classification/) { get; } | Λαμβάνει μια ταξινόμηση αυτού του συμβολισμού. |
| [TypeIndex](../../aspose.barcode.generation/baseencodetype/typeindex/) { get; } | Λαμβάνει έναν δείκτη τύπου κωδικοποίησης. |
| [TypeName](../../aspose.barcode.generation/baseencodetype/typename/) { get; } | Λαμβάνει ένα όνομα τύπου κωδικοποίησης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(BaseEncodeType) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [`BaseEncodeType`](../baseencodetype/). |
| override [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(object) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [`BaseEncodeType`](../baseencodetype/). |
| override [GetHashCode](../../aspose.barcode.generation/baseencodetype/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [GetString](../../aspose.barcode.generation/baseencodetype/getstring/)() | Μετατρέπει την παρουσία του BaseEncodeType στην ισοδύναμη συμβολοσειρά του. Η μορφή της συμβολοσειράς είναι: "Index:0; Name:Codabar". |
| override [ToString](../../aspose.barcode.generation/baseencodetype/tostring/)() | Επιστρέφει το όνομα του δεδομένου BaseEncodeType ως συμβολοσειρά. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να λάβετε μια παρουσία της κλάσης SymbologyEncodeType.

```csharp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 
 
[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

### Δείτε επίσης

* class [BaseEncodeType](../baseencodetype/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


