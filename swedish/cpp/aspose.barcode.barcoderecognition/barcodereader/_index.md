---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeReader klass"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeReader klass. BarCodeReader kapslar in en bild som kan innehålla en eller flera streckkoder, den kan sedan utföra ReadBarCodes operation för att upptäcka streckkoder i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Abort](./abort/)() | Funktionen begär avslutning av den aktuella igenkänningssessionen från en annan tråd. Abort är en odelbar metod och återgår kontrollen omedelbart efter anropet. Metoden bör användas när igenkänningsprocessen är för lång. |
| [BarCodeReader](./barcodereader/)() | Initierar en ny instans av [BarCodeReader](./) klassen med standardvärden. Kräver att bilden (SetBitmapImage()) sätts innan [ReadBarCodes()](./readbarcodes/) metoden anropas. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Initierar en ny instans av [BarCodeReader](./) klassen från en bild. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::String) | Initierar en ny instans av [BarCodeReader](./) klassen från en fil. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initierar en ny instans av [BarCodeReader](./) klassen. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | Initierar en ny instans av [BarCodeReader](./) klassen från en luminansram. |
| [Dispose](./dispose/)() override | Frigör resurs |
| [ExportToXml](./exporttoxml/)(System::String) | Exporterar [BarCode](../../aspose.barcode/) egenskaper till den angivna xml-filen |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Exporterar [BarCode](../../aspose.barcode/) egenskaper till den angivna xml-strömmen |
| [get_BarCodeReadType](./get_barcodereadtype/)() | Hämtar streckkodens avkodningstyp som används för igenkänning. Måste sättas innan [ReadBarCodes](./readbarcodes/) anropas. |
| [get_BarcodeSettings](./get_barcodesettings/)() | De viktigaste [BarCode](../../aspose.barcode/) avkodningsparametrarna. Innehåller parametrar som påverkar den igenkända datan. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | Hämtar en array med igenkända [BarCodeResult](../barcoderesult/) |
| [get_FoundCount](./get_foundcount/)() | Hämtar antalet igenkända streckkoder |
| static [get_ProcessorSettings](./get_processorsettings/)() | Hämtar en inställning för att använda processorkärnor. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) tillåter att konfigurera igenkänningskvalitet och hastighet manuellt. Du kan snabbt ställa in [QualitySettings](../qualitysettings/) med inbäddade förinställningar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes eller så kan du manuellt konfigurera separata alternativ. Standardvärdet för [QualitySettings](../qualitysettings/) är NormalQuality. |
| [get_Timeout](./get_timeout/)() | Hämtar tidsgränsen för igenkänningsprocessen i millisekunder. |
| static [ImportFromXml](./importfromxml/)(System::String) | Importerar [BarCode](../../aspose.barcode/) egenskaper från den angivna xml-filen och tillämpar dem på den aktuella [BarCodeReader](./) instansen. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Importerar [BarCode](../../aspose.barcode/) egenskaper från den angivna xml-strömmen och tillämpar dem på den aktuella [BarCodeReader](./) instansen. |
| [ReadBarCodes](./readbarcodes/)() | Läser [BarCodeResult](../barcoderesult/)s från bilden. |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | Ställer in avkodningstypen för streckkoden som används för igenkänning. Måste anges innan [ReadBarCodes](./readbarcodes/) anropas. |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) tillåter att konfigurera igenkänningskvalitet och hastighet manuellt. Du kan snabbt ställa in [QualitySettings](../qualitysettings/) med inbäddade förinställningar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes eller så kan du manuellt konfigurera separata alternativ. Standardvärdet för [QualitySettings](../qualitysettings/) är NormalQuality. |
| [set_Timeout](./set_timeout/)(int32_t) | Ställer in tidsgränsen för igenkänningsprocessen i millisekunder. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Ställer in bitmap-bild för igenkänning. Måste anropas innan metoden [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Ställer in bitmap-bild och områden för igenkänning. Måste anropas innan metoden [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | Ställer in bitmap-bild och område för igenkänning. Måste anropas innan metoden [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | Ställer in bildfil för igenkänning. Måste anropas innan metoden [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | Ställer in bildström för igenkänning. Måste anropas innan metoden [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | Ställer in luminansramen och området för igenkänning. Måste anropas innan [ReadBarCodes](./readbarcodes/) metoden. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Ställer in luminansramen och områdena för igenkänning. Måste anropas innan [ReadBarCodes](./readbarcodes/) metoden. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | Ställer in luminansramen för igenkänning. Måste anropas innan [ReadBarCodes](./readbarcodes/) metoden. |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Ställer in en typarray av [SingleDecodeType](../singledecodetype/) för igenkänning. Måste anropas innan [ReadBarCodes()](./readbarcodes/) metoden. |
## Anmärkningar


Detta exempel visar hur man upptäcker Code39- och Code128-streckkoder.
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

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
