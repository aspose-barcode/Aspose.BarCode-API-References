---
title: "Aspose::BarCode::Generation::DotCodeExtCodetextBuilder class"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε την κλάση Aspose::BarCode::Generation::DotCodeExtCodetextBuilder σε C++."
type: docs
weight: 2100
url: /el/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Προσθέτει κείμενο κώδικα με εκτεταμένο αναγνωριστικό καναλιού |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | Προσθέτει το αναγνωριστικό μορφής FNC1 στα extended codetext items. |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | Προσθέτει την αρχικοποίηση του αναγνώστη FNC3 στα extended codetext items. |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | Προσθέτει το διαχωριστικό συμβόλου FNC3 στα extended codetext items. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Προσθέτει απλό κείμενο κώδικα στα στοιχεία του εκτεταμένου κειμένου κώδικα |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | Προσθέτει τη λειτουργία structured append στα extended codetext items. |
| virtual [Clear](../extcodetextbuilder/clear/)() | Καθαρίζει τα στοιχεία του εκτεταμένου κειμένου κώδικα |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Δημιουργεί εκτεταμένο κείμενο κώδικα από τη λίστα του εκτεταμένου κειμένου κώδικα. |
## Σχόλια


Γεννήτρια extended codetext για 2D DotCode barcode για τη λειτουργία ExtendedCodetext του DotCodeEncodeMode.


```cpp
[C#]
//Λειτουργία εκτεταμένου κειμένου κώδικα
//δημιουργία κειμένου κώδικα
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//δημιουργία κειμένου κώδικα
string codetext = textBuilder.GetExtendedCodetext();

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Δείτε επίσης

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
