---
title: "Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder klass"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder klass i C++."
type: docs
weight: 3500
url: /sv/cpp/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class




```cpp
class MaxiCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
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


Utökad kodtextgenerator för MaxiCode-streckkoder för ExtendedCodetext-läge i MaxiCodeEncodeMode

Använd egenskapen TwoDDisplayText för [BarcodeGenerator](../barcodegenerator/) för att ange synlig text genom att ta bort styrtecken.

Detta exempel visar hur man använder [MaxiCodeExtCodetextBuilder](./) i Utökat läge.
```cpp
[C#]
//skapa kodtext
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generera kodtext
string codetext = textBuilder.GetExtendedCodetext();

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Se även

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
