---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings klass"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings klass. QualitySettings möjliggör manuell konfiguration av igenkänningskvalitet och hastighet. Du kan snabbt ställa in QualitySettings med inbyggda förinställningar: HighPerformance, NormalQuality, HighQuality, MaxQuality eller så kan du manuellt konfigurera separata alternativ. Standardvärdet för QualitySettings är NormalQuality i C++."
type: docs
weight: 3100
url: /sv/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | Tillåter motorn att känna igen streckkoder som har felaktig kontrollsumma eller felaktiga värden. Läget kan användas för att känna igen skadade streckkoder med felaktig text. |
| [get_BarcodeQuality](./get_barcodequality/)() const | Läge som möjliggör metoder för att känna igen streckkodselement med den valda kvaliteten. Streckkodselement med lägre kvalitet kräver mer krävande metoder vilket saktar ner igenkänningen. |
| [get_ComplexBackground](./get_complexbackground/)() const | Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder. |
| [get_Deconvolution](./get_deconvolution/)() const | Deconvolution (bildåterställning) läge som definierar nivån av bildnedbrytning. Ursprungligen är dekonvolution en funktion som kan återställa en bild som har försämrats (konvolverats) av någon naturlig funktion som oskärpa, vid bildtagning med kamera. Eftersom vi inte kan upptäcka den bildfunktion som korrumperar bilden, måste vi testa de mest välkända funktionerna som skärpning eller matematisk morfologi. |
| static [get_HighPerformance](./get_highperformance/)() | HighPerformance‑förinställning för igenkänningskvalitet. Högkvalitativa streckkoder känns igen väl i detta läge. |
| static [get_HighQuality](./get_highquality/)() | HighQuality‑förinställning för igenkänningskvalitet. Denna förinställning är utvecklad för lågkvalitativa streckkoder. Gör det möjligt att upptäcka kraftigt skadade streckkoder. |
| [get_InverseImage](./get_inverseimage/)() const | Läge som aktiverar eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans). |
| static [get_MaxQuality](./get_maxquality/)() | MaxQuality igenkänningskvalitetspreset. Detta preset är utvecklat för att känna igen alla möjliga streckkoder, även felaktiga streckkoder. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | Minsta storlek på XDimension i pixlar som används med UseMinimalXDimension. |
| static [get_NormalQuality](./get_normalquality/)() | NormalQuality igenkänningskvalitetspreset. Lämplig för de flesta streckkoder. |
| [get_XDimension](./get_xdimension/)() const | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) läge som anger storlek (från 1 till oändlighet) på streckkodens minsta element: matriscell eller stapel. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | Tillåter motorn att känna igen streckkoder som har felaktig kontrollsumma eller felaktiga värden. Läget kan användas för att känna igen skadade streckkoder med felaktig text. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | Läge som möjliggör metoder för att känna igen streckkodselement med den valda kvaliteten. Streckkodselement med lägre kvalitet kräver mer krävande metoder vilket saktar ner igenkänningen. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | Deconvolution (bildåterställning) läge som definierar nivån av bildnedbrytning. Ursprungligen är dekonvolution en funktion som kan återställa en bild som har försämrats (konvolverats) av någon naturlig funktion som oskärpa, vid bildtagning med kamera. Eftersom vi inte kan upptäcka den bildfunktion som korrumperar bilden, måste vi testa de mest välkända funktionerna som skärpning eller matematisk morfologi. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | Läge som aktiverar eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans). |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | Minsta storlek på XDimension i pixlar som används med UseMinimalXDimension. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) läge som anger storlek (från 1 till oändlighet) på streckkodens minsta element: matriscell eller stapel. |
## Anmärkningar


Detta exempel visar hur man använder [QualitySettings](./) med [BarCodeReader](../barcodereader/)
```cpp
[C#]
//set HighPerformance igenkänningsläge
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//set HighQuality igenkänningsläge
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//set HighPerformance igenkänningsläge för små streckkoder
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//set HighPerformance igenkänningsläge för lågkvalitativa streckkoder
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
