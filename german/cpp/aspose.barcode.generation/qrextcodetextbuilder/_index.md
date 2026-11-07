---
title: "Aspose::BarCode::Generation::QrExtCodetextBuilder Klasse"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man die Aspose::BarCode::Generation::QrExtCodetextBuilder Klasse in C++ verwendet."
type: docs
weight: 4300
url: /de/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | Fügt den Codetext mit dem angegebenen QR-Komprimierungsmodus zu den erweiterten Codetext-Elementen hinzu. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Fügt Codetext mit erweitertem Kanalbezeichner hinzu |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | Setzt FNC1 an erster Stelle. Wenn zuvor ein anderer FNC1-Modus gesetzt war, wird er ersetzt. |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | Fügt den Gruppentrennzeichen (GS - '\\u001D') zu den erweiterten Codetext-Elementen hinzu. |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | Setzt FNC1 an zweiter Stelle. Wenn zuvor ein anderer FNC1-Modus gesetzt war, wird er ersetzt. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu |
| [Clear](./clear/)() override | Löscht erweiterte Codetext-Elemente |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Generiert erweiterten Codetext aus der erweiterten Codetext-Liste. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## Hinweise


Erweiterter Codetext-Generator für 2D-QR-Barcodes für den ExtendedCodetext-Modus von EncodeMode.

Verwenden Sie die Eigenschaft TwoDDisplayText von [BarcodeGenerator](../barcodegenerator/), um den sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen.

Dieses Beispiel zeigt, wie man die erste Position von FNC1 im erweiterten Modus verwendet.
```cpp
[C#]
//Codetext erstellen
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//Codetext generieren
string codetext = TextBuilder.GetExtendedCodetext();

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Dieses Beispiel zeigt, wie man die zweite Position von FNC1 im erweiterten Modus verwendet.
```cpp
[C#]
//Codetext erstellen
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//Codetext generieren
string codetext = TextBuilder.GetExtendedCodetext();

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Dieses Beispiel zeigt, wie man den Multi‑ECI‑Modus im erweiterten Modus verwendet.
```cpp
[C#]
//Codetext erstellen
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//Codetext generieren
string codetext = TextBuilder.GetExtendedCodetext();

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Siehe auch

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
