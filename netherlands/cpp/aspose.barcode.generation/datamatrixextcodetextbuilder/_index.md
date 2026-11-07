---
title: "Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder klasse"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je de Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder klasse in C++."
type: docs
weight: 1900
url: /nl/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | Voegt codetext met gedefinieerde encode‑modus toe aan de uitgebreide codetext‑items |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Voegt codetext toe met Extended Channel Identifier |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | Voegt codetext met Extended Channel Identifier toe met gedefinieerde encode‑modus |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Voegt platte codetext toe aan de uitgebreide codetext‑items |
| virtual [Clear](../extcodetextbuilder/clear/)() | Verwijdert uitgebreide codetext‑items |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genereert uitgebreide codetext vanuit de uitgebreide codetext‑lijst. |
## Opmerkingen


Uitgebreide codetextgenerator voor 2D DataMatrix‑barcodes voor ExtendedCodetext‑modus van EncodeMode


```cpp
[C#]
//Uitgebreide codetext-modus

//codetext maken
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//codetext genereren
string codetext = textBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Zie ook

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
