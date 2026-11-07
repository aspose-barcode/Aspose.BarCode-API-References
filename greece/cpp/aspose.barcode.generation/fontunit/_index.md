---
title: "Aspose::BarCode::Generation::FontUnit class"
linktitle: "FontUnit"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::FontUnit class. Ορίζει μια συγκεκριμένη μορφή για το κείμενο, συμπεριλαμβανομένης της γραμματοσειράς, του μεγέθους και των χαρακτηριστικών στυλ, όπου το μέγεθος βρίσκεται στην ιδιότητα τιμής Unit σε C++."
type: docs
weight: 2500
url: /el/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


Ορίζει μια συγκεκριμένη μορφή για το κείμενο, συμπεριλαμβανομένης της γραμματοσειράς, του μεγέθους και των χαρακτηριστικών στυλ, όπου το μέγεθος βρίσκεται στην ιδιότητα τιμής [Unit](../unit/).

```cpp
class FontUnit : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | Αποκτά το όνομα γραμματοσειράς αυτού του Font. |
| [get_Size](./get_size/)() const | Λαμβάνει το μέγεθος αυτού του [FontUnit](./) σε τιμή [Unit](../unit/). |
| [get_Style](./get_style/)() const | Λαμβάνει πληροφορίες στυλ για αυτό το [FontUnit](./). |
| [set_FamilyName](./set_familyname/)(System::String) | Ορίζει το όνομα γραμματοσειράς αυτού του Font. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | Ορίζει πληροφορίες στυλ για αυτό το [FontUnit](./). |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
