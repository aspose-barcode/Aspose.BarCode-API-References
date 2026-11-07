---
title: "Aspose::BarCode::Generation::AztecExtCodetextBuilder class"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je de Aspose::BarCode::Generation::AztecExtCodetextBuilder class in C++."
type: docs
weight: 200
url: /nl/cpp/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class




```cpp
class AztecExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Voegt codetext toe met Extended Channel Identifier |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Voegt platte codetext toe aan de uitgebreide codetext‑items |
| virtual [Clear](../extcodetextbuilder/clear/)() | Verwijdert uitgebreide codetext‑items |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genereert uitgebreide codetext vanuit de uitgebreide codetext‑lijst. |
## Opmerkingen


Uitgebreide codetextgenerator voor Aztec-streepjescodes voor de ExtendedCodetext-modus van AztecEncodeMode

Gebruik de TwoDDisplayText‑eigenschap van [BarcodeGenerator](../barcodegenerator/) om de zichtbare tekst in te stellen op het verwijderen van beheer‑tekens.

Dit voorbeeld toont hoe je [AztecExtCodetextBuilder](./) gebruikt in de Extended-modus.
```cpp
[C#]
//codetext maken
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//codetext genereren
string codetext = textBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Zie ook

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
