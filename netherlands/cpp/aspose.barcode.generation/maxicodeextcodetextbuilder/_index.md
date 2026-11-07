---
title: "Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder klasse"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je de Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder klasse in C++."
type: docs
weight: 3500
url: /nl/cpp/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class




```cpp
class MaxiCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
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


Uitgebreide codetextgenerator voor MaxiCode-barcodes voor de ExtendedCodetext-modus van MaxiCodeEncodeMode

Gebruik de TwoDDisplayText‑eigenschap van [BarcodeGenerator](../barcodegenerator/) om de zichtbare tekst in te stellen op het verwijderen van beheer‑tekens.

Dit voorbeeld toont hoe je [MaxiCodeExtCodetextBuilder](./) gebruikt in de Uitgebreide modus.
```cpp
[C#]
//codetext maken
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//codetext genereren
string codetext = textBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Zie ook

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
