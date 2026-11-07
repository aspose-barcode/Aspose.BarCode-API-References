---
title: "Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder Klasse"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man die Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder Klasse in C++ verwendet."
type: docs
weight: 1900
url: /de/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | Fügt Codetext mit definiertem Kodiermodus zu den erweiterten Codetext-Elementen hinzu |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Fügt Codetext mit erweitertem Kanalbezeichner hinzu |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | Fügt Codetext mit erweitertem Kanalbezeichner und definiertem Kodiermodus hinzu |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu |
| virtual [Clear](../extcodetextbuilder/clear/)() | Löscht erweiterte Codetext-Elemente |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Generiert erweiterten Codetext aus der erweiterten Codetext-Liste. |
## Hinweise


Erweiterter Codetext-Generator für 2D DataMatrix-Barcodes für den ExtendedCodetext-Modus von EncodeMode


```cpp
[C#]
//Erweiterter Codetext-Modus

//Codetext erstellen
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//Codetext generieren
string codetext = textBuilder.GetExtendedCodetext();

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Siehe auch

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
