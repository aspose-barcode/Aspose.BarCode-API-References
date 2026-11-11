---
title: "Klasse QualitySettings"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.QualitySettings klasse. QualitySettings maakt handmatige configuratie van herkenningskwaliteit en -snelheid mogelijk. Je kunt QualitySettings snel instellen met ingebouwde presets HighPerformance NormalQuality HighQuality MaxQuality of je kunt handmatig afzonderlijke opties configureren. Standaardwaarde van QualitySettings is NormalQuality."
type: docs
weight: 370
url: /nl/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings maakt het mogelijk om de herkenningskwaliteit en -snelheid handmatig te configureren. Je kunt QualitySettings snel instellen met ingebouwde presets: HighPerformance, NormalQuality, HighQuality, MaxQuality, of je kunt handmatig afzonderlijke opties configureren. De standaardwaarde van QualitySettings is NormalQuality.

```csharp
public sealed class QualitySettings
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | HighPerformance herkenningskwaliteitspreset. Barcodes van hoge kwaliteit worden goed herkend in deze modus. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | HighQuality herkenningskwaliteitspreset. Deze preset is ontwikkeld voor barcodes van lage kwaliteit. Maakt het mogelijk om sterk beschadigde barcodes te detecteren. |
| static [MaxQuality](../../aspose.barcode.barcoderecognition/qualitysettings/maxquality/) { get; } | MaxQuality herkenningskwaliteitspreset. Deze preset is ontwikkeld om alle mogelijke barcodes te herkennen, zelfs onjuiste barcodes. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | NormalQuality herkenningskwaliteitspreset. Geschikt voor de meeste barcodes |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | Staat de engine toe barcodes te herkennen die een onjuiste controlesom of onjuiste waarden hebben. De modus kan worden gebruikt om beschadigde barcodes met onjuiste tekst te herkennen. |
| [BarcodeQuality](../../aspose.barcode.barcoderecognition/qualitysettings/barcodequality/) { get; set; } | Modus die methoden inschakelt om barcode‑elementen te herkennen met de geselecteerde kwaliteit. Een barcode‑element met lagere kwaliteit vereist meer intensieve methoden, wat de herkenning vertraagt. |
| [ComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/complexbackground/) { get; set; } | Modus die extra herkenning van gekleurde barcodes op kleurafbeeldingen in- of uitschakelt. |
| [Deconvolution](../../aspose.barcode.barcoderecognition/qualitysettings/deconvolution/) { get; set; } | Deconvolutie‑modus (beeldherstel) die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een door een natuurlijke functie, zoals vervaging, gedegradeerd (geconvolueerd) beeld kan herstellen bij het verkrijgen van een afbeelding met een camera. Omdat we de beeldfunctie die het beeld corrumpeert niet kunnen detecteren, moeten we de meest bekende functies zoals scherpte of wiskundige morfologie controleren. |
| [InverseImage](../../aspose.barcode.barcoderecognition/qualitysettings/inverseimage/) { get; set; } | Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt. |
| [MinimalXDimension](../../aspose.barcode.barcoderecognition/qualitysettings/minimalxdimension/) { get; set; } | Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension. |
| [XDimension](../../aspose.barcode.barcoderecognition/qualitysettings/xdimension/) { get; set; } | Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk. |

## Voorbeelden

Dit voorbeeld laat zien hoe QualitySettings te gebruiken met BarCodeReader

```csharp
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

//stel HighPerformance herkenningsmodus in voor kleine barcodes
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

### Zie ook

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


