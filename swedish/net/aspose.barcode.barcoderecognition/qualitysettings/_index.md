---
title: QualitySettings
second_title: Aspose.BarCode för .NET API-referens
description: QualitySettings gör det möjligt att konfigurera igenkänningskvalitet och -hastighet manuellt. Du kan snabbt ställa in QualitySettings genom inbäddade förinställningar HighPerformance NormalQuality HighQuality MaxBarCodes eller så kan du manuellt konfigurera separata alternativ. Settings.
type: docs
weight: 250
url: /sv/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings gör det möjligt att konfigurera igenkänningskvalitet och -hastighet manuellt. Du kan snabbt ställa in QualitySettings genom inbäddade förinställningar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes eller så kan du manuellt konfigurera separata alternativ. Settings.

```csharp
public sealed class QualitySettings
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance) { get; } | Högpresterande igenkänningskvalitet förinställd. Högkvalitativa streckkoder känns igen väl i detta läge. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality) { get; } | Förinställd kvalitet för igenkänning av hög kvalitet. Denna förinställning är utvecklad för streckkoder av låg kvalitet. Gör det möjligt att upptäcka diagonala och mycket skadade streckkoder. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection) { get; } | HighQualityDetection igenkänningskvalitet förinställd. Samma som NormalQuality men med hög kvalitet[`DetectorSettings`](./detectorsettings) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes) { get; } | MaxBarCodes igenkänningskvalitet förinställd. Denna förinställning är utvecklad för att känna igen alla möjliga streckkoder, även felaktiga streckkoder. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection) { get; } | MaxQualityDetection igenkänningskvalitet förinställd. Samma som NormalQuality men med högsta kvalitet[`DetectorSettings`](./detectorsettings). Gör det möjligt att upptäcka diagonala och skadade streckkoder. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality) { get; } | Normal Kvalitetsigenkänningskvalitet förinställd. Lämplig för de flesta streckkoder |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground) { get; set; } | Låter motorn känna igen färgstreckkoder på färgbakgrund som ytterligare skanning. Extremt långsamt läge. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes) { get; set; } | Tillåter motorn för Datamatrix att känna igen streckade industriella Datamatrix-streckkoder. Långsamt läge som endast hjälper för streckade streckkoder som består av fläckar. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage) { get; set; } | Låter motorn känna igen minskad bild som ytterligare skanning. Storleken för minskning väljs av interna motoralgoritmer. Läget hjälper till att känna igen streckkoder som brusar och är suddiga men fångas med hög upplösning. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap) { get; set; } | Låter motorn använda gapet mellan skanningarna för att öka igenkänningshastigheten. Läget kan göra igenkänningsproblem med låga streckkoder. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes) { get; set; } | Låter motorn känna igen streckkoder som har felaktig checksumm eller felaktiga värden. Läget kan användas för att känna igen skadade streckkoder med felaktig text. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage) { get; set; } | Låter motorn känna igen omvänd färgbild som ytterligare skanning. Läget kan användas när streckkoden är vit på svart bakgrund. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing) { get; set; } | Låter motorn aktivera medianutjämning som ytterligare skanning. Läget hjälper till att känna igen brusade streckkoder. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving) { get; set; } | Tillåter motor för poststreckkoder att känna igen bilder med lite brus. Läget hjälper till att känna igen lätt skadade poststreckkoder. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector) { get; set; } | Låter motorn för 1D-streckkoder snabbt känna igen högkvalitativa streckkoder som fyller nästan hela bilden. Läget hjälper till att snabbt känna igen genererade streckkoder från Internet. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration) { get; set; } | Tillåter motorn för 1D-streckkoder att känna igen streckkoder med enstaka avtorkade/limmade streck i mönstret. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration) { get; set; } | Låter motorn för QR/MicroQR känna igen skadade MicroQR-streckkoder. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage) { get; set; } | Låter motorn känna igen vanlig bild utan några återställningar som huvudskanning. Läge för att känna igen bilden som den är. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering) { get; set; } | Låter motorn känna igen streckkoder med salt- och pappersbrustyp. Läget kan ta bort litet brus med vita och svarta prickar. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving) { get; set; } | Låter motorn känna igen bilden utan små vita fläckar som ytterligare skanning. Läget hjälper till att känna igen störd bild samt medianutjämningsfiltrering. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants) { get; set; } | Låter motorn känna igen 1D-streckkoder med kontrollsumma genom att kontrollera fler igenkänningsvarianter. Standardvärde: False. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings) { get; set; } | Inställningar för streckkodsdetektor. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly) { get; set; } | Låter motorn för 1D-streckkoder snabbt känna igen mitten av en bild och returnera resultatet utan att använda några tidskrävande algoritmer. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize) { get; set; } | Fönsterstorlek för medianutjämning. Typiska värden är 3 eller 4. Standardvärdet är 3. AllowMedianSmoothing måste ställas in. |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes) { get; set; } | Låter motorn känna igen små streckkoder på stora bilder. Ignorerade om[`AllowIncorrectBarcodes`](./allowincorrectbarcodes) är satt till True. Standardvärde: False. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector) { get; set; } | Växlar till den gamla streckkodsdetektorn. |

### Exempel

Detta exempel visar hur du använder QualitySettings med BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //ställ högpresterande läge
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //normalt kvalitetsläge är inställt som standard
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //ställ högkvalitativt läge med låghastighetsigenkänning 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //set max streckkoder läge, som försöker hitta alla möjliga streckkoder, även felaktiga. Det långsammaste igenkänningsläget
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //ställ högpresterande läge
   reader.QualitySettings = QualitySettings.HighPerformance;
   //ställ in separata alternativ
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //standardläget är NormalQuality
   //ställ in separata alternativ
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'ställ in högpresterande läge
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'normalt kvalitetsläge är inställt som standard
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'ställ in högkvalitetsläge med låghastighetsigenkänning
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'ställ in läget för max streckkoder, som försöker hitta alla möjliga streckkoder, även felaktiga. Det långsammaste igenkänningsläget
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'ställ in högpresterande läge
   reader.QualitySettings = QualitySettings.HighPerformance
   'ställ in separata alternativ
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'standardläget är NormalQuality
   'ställ in separata alternativ
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Se även

* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
