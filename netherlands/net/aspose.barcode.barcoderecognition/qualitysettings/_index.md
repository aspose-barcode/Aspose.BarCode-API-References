---
title: QualitySettings
second_title: Aspose.BarCode voor .NET API-referentie
description: Met QualitySettings kunt u de herkenningskwaliteit en snelheid handmatig configureren. U kunt QualitySettings snel instellen met ingesloten presets HighPerformance NormalQuality HighQuality MaxBarCodes of u kunt handmatig afzonderlijke opties configureren. De standaardwaarde van QualitySettings is NormalQuality.
type: docs
weight: 270
url: /nl/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

Met QualitySettings kunt u de herkenningskwaliteit en -snelheid handmatig configureren. U kunt QualitySettings snel instellen met ingesloten presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes of u kunt handmatig afzonderlijke opties configureren. De standaardwaarde van QualitySettings is NormalQuality.

```csharp
public sealed class QualitySettings
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | HighPerformance herkenningskwaliteit vooraf ingesteld. Barcodes van hoge kwaliteit worden in deze modus goed herkend. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | HighQuality herkenningskwaliteit vooraf ingesteld. Deze preset is ontwikkeld voor barcodes van lage kwaliteit. Maakt het mogelijk om diagonale en sterk beschadigde barcodes te detecteren. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection/) { get; } | HighQualityDetection herkenningskwaliteit vooraf ingesteld. Hetzelfde als NormalQuality maar met een hoge kwaliteit[`DetectorSettings`](./detectorsettings/) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes/) { get; } | MaxBarCodes herkenningskwaliteit vooraf ingesteld. Deze preset is ontwikkeld om alle mogelijke barcodes te herkennen, zelfs incorrecte barcodes. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection/) { get; } | MaxQualityDetection herkenningskwaliteit vooraf ingesteld. Hetzelfde als NormalQuality maar met de hoogste kwaliteit[`DetectorSettings`](./detectorsettings/) . Maakt het mogelijk om diagonale en beschadigde streepjescodes te detecteren. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | NormalQuality herkenningskwaliteit vooraf ingesteld. Geschikt voor de meeste barcodes |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground/) { get; set; } | Hiermee kan de engine kleurbarcodes op een gekleurde achtergrond herkennen als extra scan. Extreem langzame modus. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes/) { get; set; } | Hiermee kan de engine voor Datamatrix onderbroken industriële Datamatrix-streepjescodes herkennen. Langzame modus die alleen helpt voor streepjescodes die uit vlekken bestaan. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage/) { get; set; } | Hiermee kan de engine een verkleind beeld herkennen als extra scan. Grootte voor verkleinen wordt geselecteerd door interne engine-algoritmen. Mode helpt bij het herkennen van streepjescodes die geruisloos en wazig zijn, maar vastgelegd met een hoge resolutie. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap/) { get; set; } | Hiermee kan de engine de ruimte tussen scans gebruiken om de herkenningssnelheid te verhogen. Modus kan herkenningsproblemen veroorzaken met streepjescodes van lage hoogte. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | Hiermee kan de engine streepjescodes herkennen die een onjuiste controlesom of onjuiste waarden hebben. De -modus kan worden gebruikt om beschadigde streepjescodes met onjuiste tekst te herkennen. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage/) { get; set; } | Hiermee kan de engine een afbeelding met omgekeerde kleuren herkennen als extra scan. Modus kan worden gebruikt wanneer de streepjescode wit is op een zwarte achtergrond. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing/) { get; set; } | Hiermee kan de engine mediaan smoothing inschakelen als aanvullende scan. De modus helpt bij het herkennen van streepjescodes met ruis. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving/) { get; set; } | Zorgt ervoor dat de engine voor Postal-barcodes afbeeldingen met licht ruis herkent. Modus helpt bij het herkennen van licht beschadigde Postal-barcodes. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector/) { get; set; } | Hiermee kan de engine voor 1D-streepjescodes snel streepjescodes van hoge kwaliteit herkennen die bijna het hele beeld vullen. De -modus helpt bij het snel herkennen van gegenereerde streepjescodes van internet. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration/) { get; set; } | Maakt het mogelijk dat de engine voor 1D-streepjescodes streepjescodes herkent met enkele geveegde/gelijmde staven in patroon. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration/) { get; set; } | Hiermee kan de engine voor QR/MicroQR beschadigde MicroQR-barcodes herkennen. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage/) { get; set; } | Hiermee kan de engine een normaal beeld herkennen zonder enige restauratie als hoofdscan. Modus om afbeelding te herkennen zoals het is. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering/) { get; set; } | Hiermee kan de engine streepjescodes herkennen met het type zout en papierruis. Modus kan kleine ruis verwijderen met witte en zwarte stippen. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving/) { get; set; } | Hiermee kan de engine een afbeelding herkennen zonder kleine witte vlekken als extra scan. De modus helpt bij het herkennen van beelden met ruis en mediaan-afvlakkingsfiltering. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants/) { get; set; } | Hiermee kan de engine 1D-barcodes met checksum herkennen door meer herkenningsvarianten te controleren. Standaardwaarde: False. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings/) { get; set; } | Instellingen streepjescodedetector. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly/) { get; set; } | Hiermee kan de engine voor 1D-streepjescodes snel het middelste deel van een afbeelding herkennen en het resultaat retourneren zonder gebruik te maken van tijdrovende algoritmen. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize/) { get; set; } | Venstergrootte voor mediane afvlakking. Typische waarden zijn 3 of 4. De standaardwaarde is 3. AllowMedianSmoothing moet worden ingesteld. |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes/) { get; set; } | Hiermee kan de engine kleine streepjescodes op grote afbeeldingen herkennen. Genegeerd als[`AllowIncorrectBarcodes`](./allowincorrectbarcodes/) is ingesteld op Waar. Standaardwaarde: False. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector/) { get; set; } | Schakelt over naar de oude streepjescodedetector. |

### Voorbeelden

Dit voorbeeld laat zien hoe u QualitySettings gebruikt met BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // stel de hoge prestatiemodus in
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //normale kwaliteitsmodus is standaard ingesteld
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // stel de modus voor hoge kwaliteit in met herkenning op lage snelheid 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // stel max barcodes-modus in, die probeert alle mogelijke barcodes te vinden, zelfs onjuiste. De langzaamste herkenningsmodus
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // stel de hoge prestatiemodus in
   reader.QualitySettings = QualitySettings.HighPerformance;
   // stel aparte opties in
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // standaardmodus is NormalQuality
   // stel aparte opties in
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'stel de high performance-modus in
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'standaard is de normale kwaliteitsmodus ingesteld
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'stel de modus voor hoge kwaliteit in met herkenning op lage snelheid
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'stel max barcodes-modus in, die probeert alle mogelijke barcodes te vinden, zelfs onjuiste. De langzaamste herkenningsmodus
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'stel de high performance-modus in
   reader.QualitySettings = QualitySettings.HighPerformance
   'afzonderlijke opties instellen
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'standaardmodus is NormalQuality
   'afzonderlijke opties instellen
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Zie ook

* naamruimte [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
