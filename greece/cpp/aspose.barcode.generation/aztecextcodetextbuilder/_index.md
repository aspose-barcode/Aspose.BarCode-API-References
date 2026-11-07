---
title: "Aspose::BarCode::Generation::AztecExtCodetextBuilder class"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε την κλάση Aspose::BarCode::Generation::AztecExtCodetextBuilder σε C++."
type: docs
weight: 200
url: /el/cpp/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class




```cpp
class AztecExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Προσθέτει κείμενο κώδικα με εκτεταμένο αναγνωριστικό καναλιού |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Προσθέτει απλό κείμενο κώδικα στα στοιχεία του εκτεταμένου κειμένου κώδικα |
| virtual [Clear](../extcodetextbuilder/clear/)() | Καθαρίζει τα στοιχεία του εκτεταμένου κειμένου κώδικα |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Δημιουργεί εκτεταμένο κείμενο κώδικα από τη λίστα του εκτεταμένου κειμένου κώδικα. |
## Σχόλια


Γεννήτρια εκτεταμένου κειμένου κώδικα για γραμμωτούς κώδικες Aztec για τη λειτουργία ExtendedCodetext του AztecEncodeMode

Χρησιμοποιήστε την ιδιότητα TwoDDisplayText του [BarcodeGenerator](../barcodegenerator/) για να ορίσετε το ορατό κείμενο αφαιρώντας χαρακτήρες διαχείρισης.

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το [AztecExtCodetextBuilder](./) σε εκτεταμένη λειτουργία.
```cpp
[C#]
//δημιουργία κειμένου κώδικα
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//δημιουργία κειμένου κώδικα
string codetext = textBuilder.GetExtendedCodetext();

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Δείτε επίσης

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
