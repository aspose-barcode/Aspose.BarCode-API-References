---
title: "Aspose::BarCode::Generation::QrExtCodetextBuilder class"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe de klasse Aspose::BarCode::Generation::QrExtCodetextBuilder te gebruiken in C++."
type: docs
weight: 4300
url: /nl/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | Voegt codetekst toe met de opgegeven QR-compressiemodus aan de uitgebreide codetekstitems. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Voegt codetext toe met Extended Channel Identifier |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | Stelt FNC1 in op de eerste positie. Als een andere FNC1-modus eerder was ingesteld, wordt deze vervangen. |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | Voegt Group Separator (GS - '\u001D') toe aan de uitgebreide codetextitems |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | Stelt FNC1 in op de tweede positie. Als een andere FNC1-modus eerder was ingesteld, wordt deze vervangen. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Voegt platte codetext toe aan de uitgebreide codetext‑items |
| [Clear](./clear/)() override | Verwijdert uitgebreide codetext‑items |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genereert uitgebreide codetext vanuit de uitgebreide codetext‑lijst. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## Opmerkingen


Uitgebreide codetextgenerator voor 2D QR‑codes voor de ExtendedCodetext-modus van EncodeMode

Gebruik de TwoDDisplayText‑eigenschap van [BarcodeGenerator](../barcodegenerator/) om de zichtbare tekst in te stellen op het verwijderen van beheer‑tekens.

Dit voorbeeld laat zien hoe je FNC1‑eerste positie gebruikt in Uitgebreide Modus.
```cpp
[C#]
//codetext maken
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//codetext genereren
string codetext = TextBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Dit voorbeeld laat zien hoe je FNC1‑tweede positie gebruikt in Uitgebreide Modus.
```cpp
[C#]
//codetext maken
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//codetext genereren
string codetext = TextBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Dit voorbeeld laat zien hoe je multi‑ECI‑modus gebruikt in Uitgebreide Modus.
```cpp
[C#]
//codetext maken
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//codetext genereren
string codetext = TextBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Zie ook

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
