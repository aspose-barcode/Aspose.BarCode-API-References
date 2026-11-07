---
title: "Aspose::BarCode::Generation::AztecExtCodetextBuilder class"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man die Klasse Aspose::BarCode::Generation::AztecExtCodetextBuilder in C++ verwendet."
type: docs
weight: 200
url: /de/cpp/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class




```cpp
class AztecExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
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


Erweiterter Codetext-Generator für Aztec-Barcodes für den ExtendedCodetext-Modus von AztecEncodeMode

Verwenden Sie die Eigenschaft TwoDDisplayText von [BarcodeGenerator](../barcodegenerator/), um den sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen.

Dieses Beispiel zeigt, wie man [AztecExtCodetextBuilder](./) im erweiterten Modus verwendet.
```cpp
[C#]
//Codetext erstellen
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//Codetext generieren
string codetext = textBuilder.GetExtendedCodetext();

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Siehe auch

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
