---
title: "Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder klass"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder-klass i C++."
type: docs
weight: 1900
url: /sv/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | Lägger till codetext med definierat kodningsläge till de utökade codetext‑objekten |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Lägger till kodtext med Extended Channel Identifier |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | Lägger till codetext med Extended Channel Identifier med definierat kodningsläge |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Lägger till vanlig kodtext till de utökade kodtextobjekten |
| virtual [Clear](../extcodetextbuilder/clear/)() | Rensar utökade kodtextobjekt |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genererar utökad kodtext från den utökade kodtextlistan. |
## Anmärkningar


Utökad codetext‑generator för 2D DataMatrix‑streckkoder för ExtendedCodetext‑läge i EncodeMode


```cpp
[C#]
//Utökad kodtextläge

//skapa kodtext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//generera kodtext
string codetext = textBuilder.GetExtendedCodetext();

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Se även

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
