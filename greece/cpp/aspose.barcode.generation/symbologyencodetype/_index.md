---
title: "κλάση Aspose::BarCode::Generation::SymbologyEncodeType"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "κλάση Aspose::BarCode::Generation::SymbologyEncodeType. Τύπος κωδικοποίησης συμβολισμού. Δείτε το EncodeTypes για να λάβετε την παρουσία σε C++."
type: docs
weight: 4900
url: /el/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


Τύπος κωδικοποίησης συμβολισμού. Δείτε το [EncodeTypes](../encodetypes/) για να λάβετε την παρουσία.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή του [BaseEncodeType](../baseencodetype/). |
| [get_Classification](../baseencodetype/get_classification/)() const | Λαμβάνει μια ταξινόμηση αυτού του συμβολισμού. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | Λαμβάνει έναν δείκτη του τύπου κωδικοποίησης |
| [get_TypeName](../baseencodetype/get_typename/)() const | Λαμβάνει ένα όνομα του τύπου κωδικοποίησης |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [GetString](../baseencodetype/getstring/)() | Μετατρέπει την παρουσία του [BaseEncodeType](../baseencodetype/) στην ισοδύναμη συμβολοσειρά του. Η μορφή της συμβολοσειράς είναι: "Index:0; Name:Codabar". |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | Μετατρέπει την παρουσία του [BaseEncodeType](../baseencodetype/) στην ισοδύναμη συμβολοσειρά του. Η μορφή της συμβολοσειράς είναι: "Index:-1; Name:None". |
| static [Parse](../baseencodetype/parse/)(System::String) | Μετατρέπει τη συμβολοσειρά που αντιπροσωπεύει το όνομα ενός [BaseEncodeType](../baseencodetype/) στην παρουσία του. |
| [ToString](../baseencodetype/tostring/)() const override | Επιστρέφει το όνομα του δεδομένου [BaseEncodeType](../baseencodetype/) ως συμβολοσειρά. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Μετατρέπει τη συμβολοσειρά ενός [BaseEncodeType](../baseencodetype/) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Μετατρέπει τη συμβολοσειρά ενός [BaseEncodeType](../baseencodetype/) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να αποκτήσετε μια παρουσία της κλάσης [SymbologyEncodeType](./).
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## Δείτε επίσης

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
