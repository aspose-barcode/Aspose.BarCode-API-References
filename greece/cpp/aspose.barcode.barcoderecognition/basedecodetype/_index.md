---
title: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType κλάση"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType κλάση. Βασική κλάση για MultiDecodeType και SingleDecodeType σε C++."
type: docs
weight: 900
url: /el/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


Βασική κλάση για [MultiDecodeType](../multidecodetype/) και [SingleDecodeType](../singledecodetype/).

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Καθορίζει εάν οποιοσδήποτε από τους δοθέντες τύπους αποκωδικοποίησης περιλαμβάνεται στο |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [SingleDecodeType](../singledecodetype/). |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [MultiDecodeType](../multidecodetype/). |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [BaseDecodeType](./). |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [SingleDecodeType](../singledecodetype/) σε παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [MultiDecodeType](../multidecodetype/) στην παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός [BaseDecodeType](./) σε παρουσία του, αφού έχει προσδιοριστεί ο συγκεκριμένος τύπος. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το [BaseDecodeType](./) με το [SingleDecodeType](../singledecodetype/) και το [MultiDecodeType](../multidecodetype/)
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
