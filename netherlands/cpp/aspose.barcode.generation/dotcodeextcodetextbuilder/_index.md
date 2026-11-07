---
title: "Aspose::BarCode::Generation::DotCodeExtCodetextBuilder klasse"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je de Aspose::BarCode::Generation::DotCodeExtCodetextBuilder klasse in C++."
type: docs
weight: 2100
url: /nl/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Voegt codetext toe met Extended Channel Identifier |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | Voegt FNC1-formaatidentificatie toe aan de uitgebreide codetextitems |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | Voegt FNC3-lezerinitialisatie toe aan de uitgebreide codetextitems |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | Voegt FNC3-symboolscheidingsteken toe aan de uitgebreide codetextitems |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Voegt platte codetext toe aan de uitgebreide codetext‑items |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | Voegt gestructureerde toevoegingsmodus toe aan de uitgebreide codetextitems |
| virtual [Clear](../extcodetextbuilder/clear/)() | Verwijdert uitgebreide codetext‑items |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genereert uitgebreide codetext vanuit de uitgebreide codetext‑lijst. |
## Opmerkingen


Uitgebreide codetextgenerator voor 2D DotCode barcodes voor de ExtendedCodetext-modus van DotCodeEncodeMode


```cpp
[C#]
//Uitgebreide codetext-modus
//codetext maken
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

//codetext genereren
string codetext = textBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Zie ook

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
