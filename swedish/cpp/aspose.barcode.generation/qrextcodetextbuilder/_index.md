---
title: "Aspose::BarCode::Generation::QrExtCodetextBuilder klass"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder Aspose::BarCode::Generation::QrExtCodetextBuilder-klass i C++."
type: docs
weight: 4300
url: /sv/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | Lägger till kodtext med angivet QR-komprimeringsläge till de utökade kodtextobjekten. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Lägger till kodtext med Extended Channel Identifier |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | Ställer in FNC1 i första positionen. Om ett annat FNC1-läge redan var inställt ersätts det. |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | Lägger till gruppseparator (GS - '\u001D') till de utökade kodtextobjekten |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | Ställer in FNC1 i andra positionen. Om ett annat FNC1-läge redan var inställt ersätts det. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Lägger till vanlig kodtext till de utökade kodtextobjekten |
| [Clear](./clear/)() override | Rensar utökade kodtextobjekt |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genererar utökad kodtext från den utökade kodtextlistan. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## Anmärkningar


Utökad kodtextgenerator för 2D QR-streckkoder för ExtendedCodetext-läge i EncodeMode

Använd egenskapen TwoDDisplayText för [BarcodeGenerator](../barcodegenerator/) för att ange synlig text genom att ta bort styrtecken.

Detta exempel visar hur man använder FNC1 i första positionen i Extended Mode.
```cpp
[C#]
//skapa kodtext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//generera kodtext
string codetext = TextBuilder.GetExtendedCodetext();

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Detta exempel visar hur man använder FNC1 i andra positionen i Extended Mode.
```cpp
[C#]
//skapa kodtext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//generera kodtext
string codetext = TextBuilder.GetExtendedCodetext();

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Detta exempel visar hur man använder multi‑ECI‑läge i Extended Mode.
```cpp
[C#]
//skapa kodtext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//generera kodtext
string codetext = TextBuilder.GetExtendedCodetext();

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Se även

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
