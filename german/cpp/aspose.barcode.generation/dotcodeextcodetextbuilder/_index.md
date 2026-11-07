---
title: "Aspose::BarCode::Generation::DotCodeExtCodetextBuilder Klasse"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man die Aspose::BarCode::Generation::DotCodeExtCodetextBuilder Klasse in C++ verwendet."
type: docs
weight: 2100
url: /de/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Fügt Codetext mit erweitertem Kanalbezeichner hinzu |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | Fügt den FNC1‑Formatbezeichner zu den erweiterten Codetext‑Elementen hinzu |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | Fügt die FNC3‑Leserinitialisierung zu den erweiterten Codetext‑Elementen hinzu |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | Fügt den FNC3‑Symboltrenner zu den erweiterten Codetext‑Elementen hinzu |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | Fügt den strukturierten Anfügemodus zu den erweiterten Codetext‑Elementen hinzu |
| virtual [Clear](../extcodetextbuilder/clear/)() | Löscht erweiterte Codetext-Elemente |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Generiert erweiterten Codetext aus der erweiterten Codetext-Liste. |
## Hinweise


Erweiterter Codetext‑Generator für 2D DotCode‑Barcodes für den ExtendedCodetext‑Modus von DotCodeEncodeMode


```cpp
[C#]
//Erweiterter Codetext-Modus
//Codetext erstellen
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

//Codetext generieren
string codetext = textBuilder.GetExtendedCodetext();

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Siehe auch

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
