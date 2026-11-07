---
title: "Aspose::BarCode::Generation::QrExtCodetextBuilder κλάση"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε την κλάση Aspose::BarCode::Generation::QrExtCodetextBuilder σε C++."
type: docs
weight: 4300
url: /el/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | Προσθέτει κείμενο κώδικα με την καθορισμένη λειτουργία συμπίεσης QR στα στοιχεία εκτεταμένου κειμένου κώδικα. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Προσθέτει κείμενο κώδικα με εκτεταμένο αναγνωριστικό καναλιού |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | Ορίζει το FNC1 στην πρώτη θέση. Εάν είχε οριστεί προηγούμενη λειτουργία FNC1, αυτή αντικαθίσταται. |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | Προσθέτει το Διαχωριστικό Ομάδας (GS - '\u001D') στα στοιχεία εκτεταμένου κώδικα κειμένου. |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | Ορίζει το FNC1 στη δεύτερη θέση. Εάν είχε οριστεί προηγούμενη λειτουργία FNC1, αυτή αντικαθίσταται. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Προσθέτει απλό κείμενο κώδικα στα στοιχεία του εκτεταμένου κειμένου κώδικα |
| [Clear](./clear/)() override | Καθαρίζει τα στοιχεία του εκτεταμένου κειμένου κώδικα |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Δημιουργεί εκτεταμένο κείμενο κώδικα από τη λίστα του εκτεταμένου κειμένου κώδικα. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## Σχόλια


Γεννήτρια εκτεταμένου κώδικα κειμένου για 2D QR barcode για τη λειτουργία ExtendedCodetext του EncodeMode.

Χρησιμοποιήστε την ιδιότητα TwoDDisplayText του [BarcodeGenerator](../barcodegenerator/) για να ορίσετε το ορατό κείμενο αφαιρώντας χαρακτήρες διαχείρισης.

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη θέση FNC1 πρώτη σε Επεκταμένη Λειτουργία.
```cpp
[C#]
//δημιουργία κειμένου κώδικα
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//δημιουργία κειμένου κώδικα
string codetext = TextBuilder.GetExtendedCodetext();

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη θέση FNC1 δεύτερη σε Επεκταμένη Λειτουργία.
```cpp
[C#]
//δημιουργία κειμένου κώδικα
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//δημιουργία κειμένου κώδικα
string codetext = TextBuilder.GetExtendedCodetext();

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία multi ECI σε Επεκταμένη Λειτουργία.
```cpp
[C#]
//δημιουργία κειμένου κώδικα
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//δημιουργία κειμένου κώδικα
string codetext = TextBuilder.GetExtendedCodetext();

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Δείτε επίσης

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
