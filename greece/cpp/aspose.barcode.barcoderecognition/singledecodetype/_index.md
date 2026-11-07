---
title: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType κλάση"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType κλάση. Μοναδικός τύπος αποκωδικοποίησης. Δείτε τον τύπο αποκωδικοποίησης για να λάβετε την παρουσία σε C++."
type: docs
weight: 3200
url: /el/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


Μοναδικός τύπος αποκωδικοποίησης. Δείτε τον τύπο αποκωδικοποίησης για να λάβετε ένα αντικείμενο.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία περιλαμβάνεται στη συγκεκριμένη λίστα. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [SingleDecodeType](./). |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν η καθορισμένη συλλογή [MultiDecodeType](../multidecodetype/) περιέχει μόνο αυτόν τον τύπο αποκωδικοποίησης. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [SingleDecodeType](./). |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [BaseDecodeType](../basedecodetype/). |
| [get_TypeIndex](./get_typeindex/)() const | Λαμβάνει έναν δείκτη του τύπου αποκωδικοποίησης |
| [get_TypeName](./get_typename/)() const | Λαμβάνει ένα όνομα του τύπου αποκωδικοποίησης |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [GetString](./getstring/)() | Μετατρέπει την παρουσία του [SingleDecodeType](./) στην ισοδύναμη αναπαράσταση συμβολοσειράς της. Η μορφή της συμβολοσειράς είναι: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | Μετατρέπει την παρουσία του [SingleDecodeType](./) στην ισοδύναμη αναπαράσταση συμβολοσειράς της. Η μορφή της συμβολοσειράς είναι: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Μετατρέπει την αναπαράσταση συμβολοσειράς του ονόματος ενός [SingleDecodeType](./) στην παρουσία του. |
| [ToString](./tostring/)() const override | Επιστρέφει το όνομα του δεδομένου [SingleDecodeType](./) ως συμβολοσειρά. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [SingleDecodeType](./) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [MultiDecodeType](../multidecodetype/) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [BaseDecodeType](../basedecodetype/) στην παρουσία του, αφού έχει προσδιοριστεί ο συγκεκριμένος τύπος. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να λάβετε την παρουσία ενός μοναδικού τύπου αποκωδικοποίησης.
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## Δείτε επίσης

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
