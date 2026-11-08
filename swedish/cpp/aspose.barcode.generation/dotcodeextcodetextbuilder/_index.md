---
title: "Aspose::BarCode::Generation::DotCodeExtCodetextBuilder class"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder Aspose::BarCode::Generation::DotCodeExtCodetextBuilder klass i C++."
type: docs
weight: 2100
url: /sv/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Lägger till kodtext med Extended Channel Identifier |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | Lägger till FNC1-formatidentifierare till de utökade kodtextobjekten |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | Lägger till FNC3-läsarinitiering till de utökade kodtextobjekten |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | Lägger till FNC3-symbolseparator till de utökade kodtextobjekten |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Lägger till vanlig kodtext till de utökade kodtextobjekten |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | Lägger till strukturerat tilläggsläge till de utökade kodtextobjekten |
| virtual [Clear](../extcodetextbuilder/clear/)() | Rensar utökade kodtextobjekt |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genererar utökad kodtext från den utökade kodtextlistan. |
## Anmärkningar


Utökad kodtextgenerator för 2D DotCode-streckkoder för ExtendedCodetext-läge i DotCodeEncodeMode


```cpp
[C#]
//Utökad kodtextläge
//skapa kodtext
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

//generera kodtext
string codetext = textBuilder.GetExtendedCodetext();

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Se även

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
