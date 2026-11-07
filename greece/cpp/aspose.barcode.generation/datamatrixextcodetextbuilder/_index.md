---
title: "Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder κλάση"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Πώς να χρησιμοποιήσετε την κλάση Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder σε C++."
type: docs
weight: 1900
url: /el/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | Προσθέτει codetext με ορισμένο τρόπο κωδικοποίησης στα στοιχεία εκτεταμένου codetext. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Προσθέτει κείμενο κώδικα με εκτεταμένο αναγνωριστικό καναλιού |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | Προσθέτει codetext με Extended Channel Identifier με ορισμένο τρόπο κωδικοποίησης. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Προσθέτει απλό κείμενο κώδικα στα στοιχεία του εκτεταμένου κειμένου κώδικα |
| virtual [Clear](../extcodetextbuilder/clear/)() | Καθαρίζει τα στοιχεία του εκτεταμένου κειμένου κώδικα |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Δημιουργεί εκτεταμένο κείμενο κώδικα από τη λίστα του εκτεταμένου κειμένου κώδικα. |
## Σχόλια


Γεννήτρια εκτεταμένου codetext για 2D DataMatrix barcode για λειτουργία ExtendedCodetext του EncodeMode.


```cpp
[C#]
//Λειτουργία εκτεταμένου κειμένου κώδικα

//δημιουργία κειμένου κώδικα
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//δημιουργία κειμένου κώδικα
string codetext = textBuilder.GetExtendedCodetext();

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Δείτε επίσης

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
