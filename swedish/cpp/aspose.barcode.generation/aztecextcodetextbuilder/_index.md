---
title: "Aspose::BarCode::Generation::AztecExtCodetextBuilder klass"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder Aspose::BarCode::Generation::AztecExtCodetextBuilder klass i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class




```cpp
class AztecExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Lägger till kodtext med Extended Channel Identifier |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Lägger till vanlig kodtext till de utökade kodtextobjekten |
| virtual [Clear](../extcodetextbuilder/clear/)() | Rensar utökade kodtextobjekt |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genererar utökad kodtext från den utökade kodtextlistan. |
## Anmärkningar


Utökad kodtextgenerator för Aztec-streckkoder för ExtendedCodetext-läge i AztecEncodeMode

Använd egenskapen TwoDDisplayText för [BarcodeGenerator](../barcodegenerator/) för att ange synlig text genom att ta bort styrtecken.

Detta exempel visar hur man använder [AztecExtCodetextBuilder](./) i Utökat läge.
```cpp
[C#]
//skapa kodtext
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generera kodtext
string codetext = textBuilder.GetExtendedCodetext();

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Se även

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
