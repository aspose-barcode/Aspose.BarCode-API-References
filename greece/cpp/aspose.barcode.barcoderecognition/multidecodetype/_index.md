---
title: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType κλάση"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType κλάση. Σύνθετος τύπος αποκωδικοποίησης σε C++."
type: docs
weight: 2600
url: /el/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


Σύνθετος τύπος αποκωδικοποίησης.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | Προσθέτει έναν ακόμη [SingleDecodeType](../singledecodetype/) στο [MultiDecodeType](./). |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Ελέγχει αν αυτό περιέχει όλους τους τύπους από τους τύπους barcode. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Περιέχει κάποιον από τους τύπους |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [MultiDecodeType](./). |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η συλλογή τύπων αποκωδικοποίησης περιέχει μόνο την καθορισμένη τιμή [SingleDecodeType](../singledecodetype/). |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [MultiDecodeType](./). |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [BaseDecodeType](../basedecodetype/). |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | Αποκλείει το [SingleDecodeType](../singledecodetype/) από το [MultiDecodeType](./) και επιστρέφει νέα παρουσία [MultiDecodeType](./). |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | Επιστρέφει έναν αριθμό απλών τύπων. |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [GetSingleTypes](./getsingletypes/)() | Αντιπροσωπεύει μια λίστα απλών τύπων. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [MultiDecodeType](./). |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [MultiDecodeType](./). |
| [ToString](./tostring/)() const override | Υπερκαθορισμένη μέθοδος που αντιπροσωπεύει το [MultiDecodeType](./) ως συμβολοσειρά. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [MultiDecodeType](./) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει αν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [SingleDecodeType](../singledecodetype/) σε παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [BaseDecodeType](../basedecodetype/) στην παρουσία του, αφού έχει προσδιοριστεί ο συγκεκριμένος τύπος. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε σύνθετους τύπους MultiDecode που συνδυάζουν το [SingleDecodeType](../singledecodetype/) και τύπους MultiDecode.
```cpp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

## Δείτε επίσης

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
