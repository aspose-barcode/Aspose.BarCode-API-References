---
title: "methode"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Stel codetext in als een reeks bytes in C++."
type: docs
weight: 700
url: /nl/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


Stel codetext in als een reeks bytes.

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | Bytes van codetext |

## Zie ook

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codeText | System::String | CodeText-tekenreeks |
| codering | System::SharedPtr\<System::Text::Encoding\> | Toegepaste codering |
## Opmerkingen


Codeert de Unicode **codeText** naar een bytevolgorde met behulp van de opgegeven **encoding**. UTF-8 is de meest gebruikte codering. Als de codering dit ondersteunt, voegt de functie automatisch een [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) toe.

Deze functie is uitsluitend bedoeld voor gebruik met 2D-barcodes (bijv. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, enz.). Ze maakt handmatige codering van Unicode-tekst mogelijk met nationale of speciale coderingen; echter, deze methode wordt als verouderd beschouwd in moderne toepassingen. Voor hedendaagse scenario's wordt [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation)-codering aanbevolen voor Unicode-gegevens.

Het gebruik van deze functie met 1D-barcodes, GS1-conforme barcodes (inclusief 2D), of HIBC-barcodes (inclusief 2D) wordt niet ondersteund door de bijbehorende barcode-standaarden en kan leiden tot onvoorspelbare resultaten.


Dit voorbeeld toont hoe **SetCodeText** te gebruiken om Unicode-gecodeerde tekst voor 2D-barcodes in te stellen met verschillende coderingen:


```cpp
[C#]
//QR-code-tekst coderen met UTF-8 en BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //DataMatrix-tekst coderen met Shift-JIS (Japanse codering)
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## Zie ook

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codeText | System::String | CodeText-tekenreeks |
| codering | System::SharedPtr\<System::Text::Encoding\> | Toegepaste codering |
| insertBOM | bool | Geeft aan of een byte order mark (BOM) moet worden ingevoegd wanneer de opgegeven codering dit ondersteunt (bijv. UTF-8, UTF-16, UTF-32). Als ingesteld op **true**, wordt de BOM toegevoegd; als **false**, wordt de BOM weggelaten, zelfs als de codering normaal gesproken een BOM gebruikt. |
## Opmerkingen


Codeert de Unicode **codeText** naar een bytevolgorde met behulp van de opgegeven **encoding**. UTF-8 is de meest gebruikte codering. Als de codering dit ondersteunt en **insertBOM** is ingesteld op **true**, voegt de functie een [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) toe.

Deze functie is uitsluitend bedoeld voor gebruik met 2D-barcodes (bijv. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, enz.). Ze maakt handmatige codering van Unicode-tekst mogelijk met nationale of speciale coderingen; echter, deze methode wordt als verouderd beschouwd in moderne toepassingen. Voor hedendaagse scenario's wordt [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation)-codering aanbevolen voor Unicode-gegevens.

Het gebruik van deze functie met 1D-barcodes, GS1-conforme barcodes (inclusief 2D), of HIBC-barcodes (inclusief 2D) wordt niet ondersteund door de bijbehorende barcode-standaarden en kan leiden tot onvoorspelbare resultaten.


Dit voorbeeld toont hoe **SetCodeText** te gebruiken met of zonder een BOM voor 2D-barcodes.


```cpp
[C#]
    //Codeer codetext met UTF-8 met BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Codeer codetext met UTF-8 zonder BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## Zie ook

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
