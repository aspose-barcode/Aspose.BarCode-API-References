---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeReader klasse"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeReader klasse. BarCodeReader omvat een afbeelding die één of meerdere barcodes kan bevatten, en kan vervolgens de ReadBarCodes‑bewerking uitvoeren om barcodes te detecteren in C++."
type: docs
weight: 500
url: /nl/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Abort](./abort/)() | Functie vraagt beëindiging van de huidige herkenningssessie vanaf een andere thread. Abort is een ononderbreekbare methode en geeft de controle terug direct na het aanroepen. De methode moet worden gebruikt wanneer het herkenningsproces te lang duurt. |
| [BarCodeReader](./barcodereader/)() | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse met standaardwaarden. Vereist dat de afbeelding (SetBitmapImage()) wordt ingesteld voordat de [ReadBarCodes()](./readbarcodes/) methode wordt aangeroepen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse vanuit een afbeelding. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::String) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse vanuit een bestand. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | Initialiseert een nieuw exemplaar van de [BarCodeReader](./) klasse vanuit een luminantie‑frame. |
| [Dispose](./dispose/)() override | Resource vrijgeven |
| [ExportToXml](./exporttoxml/)(System::String) | Exporteert [BarCode](../../aspose.barcode/) eigenschappen naar het opgegeven xml‑bestand |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Exporteert [BarCode](../../aspose.barcode/) eigenschappen naar de opgegeven xml‑stream |
| [get_BarCodeReadType](./get_barcodereadtype/)() | Haalt het barcode‑decodeertype op dat wordt gebruikt voor herkenning. Moet worden ingesteld voordat [ReadBarCodes](./readbarcodes/) wordt aangeroepen. |
| [get_BarcodeSettings](./get_barcodesettings/)() | De belangrijkste [BarCode](../../aspose.barcode/) decodeerparameters. Bevat parameters die invloed hebben op de herkende gegevens. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | Haalt de array met herkende [BarCodeResult](../barcoderesult/)s op |
| [get_FoundCount](./get_foundcount/)() | Haalt het aantal herkende barcodes op |
| static [get_ProcessorSettings](./get_processorsettings/)() | Haalt een instelling op voor het gebruik van processorcores. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) staat toe om de herkenningskwaliteit en -snelheid handmatig te configureren. Je kunt snel [QualitySettings](../qualitysettings/) instellen via ingebedde presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes of je kunt handmatig afzonderlijke opties configureren. De standaardwaarde van [QualitySettings](../qualitysettings/) is NormalQuality. |
| [get_Timeout](./get_timeout/)() | Haalt de time-out van het herkenningsproces op in milliseconden. |
| static [ImportFromXml](./importfromxml/)(System::String) | Importeert de eigenschappen van [BarCode](../../aspose.barcode/) uit het opgegeven xml-bestand en past ze toe op de huidige [BarCodeReader](./) instantie. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Importeert de eigenschappen van [BarCode](../../aspose.barcode/) uit de opgegeven xml-stream en past ze toe op de huidige [BarCodeReader](./) instantie. |
| [ReadBarCodes](./readbarcodes/)() | Leest [BarCodeResult](../barcoderesult/)s van de afbeelding. |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | Stelt het barcode-decodeertype in dat wordt gebruikt voor herkenning. Moet worden ingesteld vóór het aanroepen van [ReadBarCodes](./readbarcodes/). |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) staat toe om de herkenningskwaliteit en -snelheid handmatig te configureren. Je kunt snel [QualitySettings](../qualitysettings/) instellen via ingebedde presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes of je kunt handmatig afzonderlijke opties configureren. De standaardwaarde van [QualitySettings](../qualitysettings/) is NormalQuality. |
| [set_Timeout](./set_timeout/)(int32_t) | Stelt de time-out van het herkenningsproces in milliseconden in. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Stelt de bitmap-afbeelding in voor herkenning. Moet worden aangeroepen vóór de [ReadBarCodes()](./readbarcodes/) methode. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Stelt de bitmap-afbeelding en gebieden in voor herkenning. Moet worden aangeroepen vóór de [ReadBarCodes()](./readbarcodes/) methode. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | Stelt de bitmap-afbeelding en het gebied in voor herkenning. Moet worden aangeroepen vóór de [ReadBarCodes()](./readbarcodes/) methode. |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | Stelt het afbeeldingsbestand in voor herkenning. Moet worden aangeroepen vóór de [ReadBarCodes()](./readbarcodes/) methode. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | Stelt de afbeeldingstroom in voor herkenning. Moet worden aangeroepen vóór de [ReadBarCodes()](./readbarcodes/) methode. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | Stelt het luminantiekader en het gebied in voor herkenning. Moet worden aangeroepen vóór de [ReadBarCodes](./readbarcodes/) methode. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Stelt het luminantiekader en de gebieden in voor herkenning. Moet worden aangeroepen vóór de [ReadBarCodes](./readbarcodes/) methode. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | Stelt het luminantiekader in voor herkenning. Moet worden aangeroepen vóór de [ReadBarCodes](./readbarcodes/) methode. |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Stelt de type-array van [SingleDecodeType](../singledecodetype/) in voor herkenning. Moet worden aangeroepen vóór de [ReadBarCodes()](./readbarcodes/) methode. |
## Opmerkingen


Dit voorbeeld laat zien hoe Code39- en Code128-barcodes te detecteren.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
