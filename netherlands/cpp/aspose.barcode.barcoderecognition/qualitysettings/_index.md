---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings klasse"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings klasse. QualitySettings maakt het mogelijk om de herkenningskwaliteit en -snelheid handmatig te configureren. Je kunt QualitySettings snel instellen met ingebouwde presets: HighPerformance, NormalQuality, HighQuality, MaxQuality of je kunt handmatig afzonderlijke opties configureren. Standaardwaarde van QualitySettings is NormalQuality in C++."
type: docs
weight: 3100
url: /nl/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | Staat de engine toe barcodes te herkennen die een onjuiste controlesom of onjuiste waarden hebben. De modus kan worden gebruikt om beschadigde barcodes met onjuiste tekst te herkennen. |
| [get_BarcodeQuality](./get_barcodequality/)() const | Modus die methoden inschakelt om barcode‑elementen te herkennen met de geselecteerde kwaliteit. Een barcode‑element met lagere kwaliteit vereist meer intensieve methoden, wat de herkenning vertraagt. |
| [get_ComplexBackground](./get_complexbackground/)() const | Modus die extra herkenning van gekleurde barcodes op kleurafbeeldingen in- of uitschakelt. |
| [get_Deconvolution](./get_deconvolution/)() const | Deconvolutie‑modus (beeldherstel) die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een beeld kan herstellen dat is gedegradeerd (geconvolueerd) door een natuurlijke functie zoals vervaging, bij het verkrijgen van een beeld met een camera. Omdat we de beeldfunctie die het beeld corrumpeert niet kunnen detecteren, moeten we de meest bekende functies controleren, zoals verscherpen of wiskundige morfologie. |
| static [get_HighPerformance](./get_highperformance/)() | HighPerformance herkenningskwaliteitspreset. Hoogwaardige barcodes worden goed herkend in deze modus. |
| static [get_HighQuality](./get_highquality/)() | HighQuality herkenningskwaliteitspreset. Deze preset is ontwikkeld voor barcodes van lage kwaliteit. Maakt het mogelijk om sterk beschadigde barcodes te detecteren. |
| [get_InverseImage](./get_inverseimage/)() const | Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt. |
| static [get_MaxQuality](./get_maxquality/)() | MaxQuality herkenningskwaliteitsvoorkeur. Deze voorkeur is ontwikkeld om alle mogelijke barcodes te herkennen, zelfs onjuiste barcodes. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension. |
| static [get_NormalQuality](./get_normalquality/)() | NormalQuality herkenningskwaliteitsvoorkeur. Geschikt voor de meeste barcodes |
| [get_XDimension](./get_xdimension/)() const | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) modus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | Staat de engine toe barcodes te herkennen die een onjuiste controlesom of onjuiste waarden hebben. De modus kan worden gebruikt om beschadigde barcodes met onjuiste tekst te herkennen. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | Modus die methoden inschakelt om barcode‑elementen te herkennen met de geselecteerde kwaliteit. Een barcode‑element met lagere kwaliteit vereist meer intensieve methoden, wat de herkenning vertraagt. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | Modus die extra herkenning van gekleurde barcodes op kleurafbeeldingen in- of uitschakelt. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | Deconvolutie‑modus (beeldherstel) die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een beeld kan herstellen dat is gedegradeerd (geconvolueerd) door een natuurlijke functie zoals vervaging, bij het verkrijgen van een beeld met een camera. Omdat we de beeldfunctie die het beeld corrumpeert niet kunnen detecteren, moeten we de meest bekende functies controleren, zoals verscherpen of wiskundige morfologie. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt. |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) modus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk. |
## Opmerkingen


Dit voorbeeld toont hoe [QualitySettings](./) te gebruiken met [BarCodeReader](../barcodereader/)
```cpp
[C#]
//stel HighPerformance herkenningsmodus in
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//stel HighQuality herkenningsmodus in
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//stel HighPerformance herkenningsmodus in voor barcodes met een kleine afmeting
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//stel HighPerformance herkenningsmodus in voor barcodes van lage kwaliteit
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
