---
title: QualitySettings
second_title: Aspose.BarCode for .NET API Reference
description: 
type: docs
weight: 250
url: /net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality.

```csharp
public sealed class QualitySettings
```

## Properties

| Name | Description |
| --- | --- |
| static [HighPerformance](highperformance) { get; } | HighPerformance recognition quality preset. High quality barcodes are recognized well in this mode. |
| static [HighQuality](highquality) { get; } | HighQuality recognition quality preset. This preset is developed for low quality barcodes. Allows to detect diagonal and highly damaged barcodes. |
| static [HighQualityDetection](highqualitydetection) { get; } | HighQualityDetection recognition quality preset. Same as NormalQuality but with high quality [`DetectorSettings`](./detectorsettings) |
| static [MaxBarCodes](maxbarcodes) { get; } | MaxBarCodes recognition quality preset. This preset is developed to recognize all possible barcodes, even incorrect barcodes. |
| static [MaxQualityDetection](maxqualitydetection) { get; } | MaxQualityDetection recognition quality preset. Same as NormalQuality but with highest quality [`DetectorSettings`](./detectorsettings). Allows to detect diagonal and damaged barcodes. |
| static [NormalQuality](normalquality) { get; } | NormalQuality recognition quality preset. Suitable for the most of barcodes |
| [AllowComplexBackground](allowcomplexbackground) { get; set; } | Allows engine to recognize color barcodes on color background as additional scan. Extremely slow mode. |
| [AllowDatamatrixIndustrialBarcodes](allowdatamatrixindustrialbarcodes) { get; set; } | Allows engine for Datamatrix to recognize dashed industrial Datamatrix barcodes. Slow mode which helps only for dashed barcodes which consist from spots. |
| [AllowDecreasedImage](allowdecreasedimage) { get; set; } | Allows engine to recognize decreased image as additional scan. Size for decreasing is selected by internal engine algorithms. Mode helps to recognize barcodes which are noised and blurred but captured with high resolution. |
| [AllowDetectScanGap](allowdetectscangap) { get; set; } | Allows engine to use gap between scans to increase recognition speed. Mode can make recognition problems with low height barcodes. |
| [AllowIncorrectBarcodes](allowincorrectbarcodes) { get; set; } | Allows engine to recognize barcodes which has incorrect checksumm or incorrect values. Mode can be used to recognize damaged barcodes with incorrect text. |
| [AllowInvertImage](allowinvertimage) { get; set; } | Allows engine to recognize inverse color image as additional scan. Mode can be used when barcode is white on black background. |
| [AllowMedianSmoothing](allowmediansmoothing) { get; set; } | Allows engine to enable median smoothing as additional scan. Mode helps to recognize noised barcodes. |
| [AllowMicroWhiteSpotsRemoving](allowmicrowhitespotsremoving) { get; set; } | Allows engine for Postal barcodes to recognize slightly noised images. Mode helps to recognize sligtly damaged Postal barcodes. |
| [AllowOneDFastBarcodesDetector](allowonedfastbarcodesdetector) { get; set; } | Allows engine for 1D barcodes to quickly recognize high quality barcodes which fill almost whole image. Mode helps to quickly recognize generated barcodes from Internet. |
| [AllowOneDWipedBarsRestoration](allowonedwipedbarsrestoration) { get; set; } | Allows engine for 1D barcodes to recognize barcodes with single wiped/glued bars in pattern. |
| [AllowQRMicroQrRestoration](allowqrmicroqrrestoration) { get; set; } | Allows engine for QR/MicroQR to recognize damaged MicroQR barcodes. |
| [AllowRegularImage](allowregularimage) { get; set; } | Allows engine to recognize regular image without any restorations as main scan. Mode to recognize image as is. |
| [AllowSaltAndPaperFiltering](allowsaltandpaperfiltering) { get; set; } | Allows engine to recognize barcodes with salt and paper noise type. Mode can remove small noise with white and black dots. |
| [AllowWhiteSpotsRemoving](allowwhitespotsremoving) { get; set; } | Allows engine to recognize image without small white spots as additional scan. Mode helps to recognize noised image as well as median smoothing filtering. |
| [CheckMore1DVariants](checkmore1dvariants) { get; set; } | Allows engine to recognize 1D barcodes with checksum by checking more recognition variants. Default value: False. |
| [DetectorSettings](detectorsettings) { get; set; } | Barcode detector settings. |
| [FastScanOnly](fastscanonly) { get; set; } | Allows engine for 1D barcodes to quickly recognize middle slice of an image and return result without using any time-consuming algorithms. |
| [MedianSmoothingWindowSize](mediansmoothingwindowsize) { get; set; } | Window size for median smoothing. Typical values are 3 or 4. Default value is 3. AllowMedianSmoothing must be set. |
| [ReadTinyBarcodes](readtinybarcodes) { get; set; } | Allows engine to recognize tiny barcodes on large images. Ignored if [`AllowIncorrectBarcodes`](./allowincorrectbarcodes) is set to True. Default value: False. |
| [UseOldBarcodeDetector](useoldbarcodedetector) { get; set; } | Switches to the old barcode detector. |

### Examples

This sample shows how to use QualitySettings with BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //set high performance mode
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //normal quality mode is set by default
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //set high quality mode with low speed recognition 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //set max barcodes mode, which tries to find all possible barcodes, even incorrect. The slowest recognition mode
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //set high performance mode
   reader.QualitySettings = QualitySettings.HighPerformance;
   //set separate options
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //default mode is NormalQuality
   //set separate options
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'set high performance mode
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'normal quality mode is set by default
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'set high quality mode with low speed recognition
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'set max barcodes mode, which tries to find all possible barcodes, even incorrect. The slowest recognition mode
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'set high performance mode
   reader.QualitySettings = QualitySettings.HighPerformance
   'set separate options
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'default mode is NormalQuality
   'set separate options
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* assembly [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
