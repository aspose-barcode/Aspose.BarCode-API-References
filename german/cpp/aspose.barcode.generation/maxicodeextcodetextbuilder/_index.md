---
title: "Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder Klasse"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man die Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder Klasse in C++ verwendet."
type: docs
weight: 3500
url: /de/cpp/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class




```cpp
class MaxiCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Fügt Codetext mit erweitertem Kanalbezeichner hinzu |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu |
| virtual [Clear](../extcodetextbuilder/clear/)() | Löscht erweiterte Codetext-Elemente |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Generiert erweiterten Codetext aus der erweiterten Codetext-Liste. |
## Hinweise


Erweiterter Codetext-Generator für MaxiCode-Barcodes für den ExtendedCodetext-Modus von MaxiCodeEncodeMode

Verwenden Sie die Eigenschaft TwoDDisplayText von [BarcodeGenerator](../barcodegenerator/), um den sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen.

Dieses Beispiel zeigt, wie man [MaxiCodeExtCodetextBuilder](./) im erweiterten Modus verwendet.
```cpp
[C#]
//Codetext erstellen
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//Codetext generieren
string codetext = textBuilder.GetExtendedCodetext();

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Siehe auch

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
