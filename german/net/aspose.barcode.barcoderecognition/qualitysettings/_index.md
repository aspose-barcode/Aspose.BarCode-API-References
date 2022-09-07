---
title: QualitySettings
second_title: Aspose.BarCode für .NET-API-Referenz
description: QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. Sie können QualitySettings schnell durch eingebettete Voreinstellungen einrichten HighPerformance NormalQuality HighQuality MaxBarCodes oder Sie können separate Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality.
type: docs
weight: 250
url: /de/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. Sie können QualitySettings schnell durch eingebettete Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oder Sie können separate Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality.

```csharp
public sealed class QualitySettings
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance) { get; } | HighPerformance Erkennungsqualität voreingestellt. Hochwertige Barcodes werden in diesem Modus gut erkannt. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality) { get; } | HighQuality Erkennungsqualität voreingestellt. Diese Voreinstellung wurde für Barcodes niedriger Qualität entwickelt. Ermöglicht die Erkennung diagonaler und stark beschädigter Barcodes. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection) { get; } | HighQualityDetection Erkennungsqualität voreingestellt. Gleich wie NormalQuality, aber mit hoher Qualität[`DetectorSettings`](./detectorsettings) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes) { get; } | MaxBarCodes Erkennungsqualität voreingestellt. Diese Voreinstellung wurde entwickelt, um alle möglichen Barcodes zu erkennen, sogar falsche Barcodes. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection) { get; } | MaxQualityDetection Erkennungsqualität voreingestellt. Wie NormalQuality, aber mit höchster Qualität[`DetectorSettings`](./detectorsettings). Ermöglicht die Erkennung diagonaler und beschädigter Barcodes. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality) { get; } | Voreingestellte Erkennungsqualität NormalQuality. Geeignet für die meisten Barcodes |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground) { get; set; } | Ermöglicht der Engine, farbige Barcodes auf farbigem Hintergrund als zusätzlichen Scan zu erkennen. Extrem langsamer Modus. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes) { get; set; } | Ermöglicht der Engine für Datamatrix, gestrichelte industrielle Datamatrix-Barcodes zu erkennen. Langsamer Modus, der nur bei Strichcodes hilft, die aus Punkten bestehen. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage) { get; set; } | Ermöglicht der Engine, ein verkleinertes Bild als zusätzlichen Scan zu erkennen. Die Größe zum Verkleinern wird von internen Engine-Algorithmen ausgewählt. Der Modus hilft bei der Erkennung von Barcodes, die verrauscht und verschwommen sind, aber mit hoher Auflösung erfasst werden. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap) { get; set; } | Ermöglicht der Engine, Lücken zwischen Scans zu verwenden, um die Erkennungsgeschwindigkeit zu erhöhen. Der Modus kann Erkennungsprobleme bei Barcodes mit geringer Höhe verursachen. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes) { get; set; } | Ermöglicht der Engine, Barcodes mit falscher Prüfsumme oder falschen Werten zu erkennen. Modus kann verwendet werden, um beschädigte Barcodes mit falschem Text zu erkennen. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage) { get; set; } | Ermöglicht der Engine, ein inverses Farbbild als zusätzlichen Scan zu erkennen. Der Modus kann verwendet werden, wenn der Barcode weiß auf schwarzem Hintergrund ist. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing) { get; set; } | Ermöglicht der Engine, Median-Glättung als zusätzlichen Scan zu aktivieren. Der Modus hilft, verrauschte Barcodes zu erkennen. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving) { get; set; } | Ermöglicht der Engine für postalische Barcodes, Bilder mit leichtem Rauschen zu erkennen. Modus hilft, leicht beschädigte Postbarcodes zu erkennen. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector) { get; set; } | Ermöglicht der Engine für 1D-Barcodes, schnell hochwertige Barcodes zu erkennen, die fast das gesamte Bild ausfüllen. Der -Modus hilft, generierte Barcodes aus dem Internet schnell zu erkennen. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration) { get; set; } | Ermöglicht der Engine für 1D-Barcodes die Erkennung von Barcodes mit einzelnen gewischten/geklebten Strichen im Muster. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration) { get; set; } | Ermöglicht der Engine für QR/MicroQR, beschädigte MicroQR-Barcodes zu erkennen. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage) { get; set; } | Ermöglicht der Engine, normale Bilder ohne Wiederherstellungen als Hauptscan zu erkennen. Modus, um das Bild so zu erkennen, wie es ist. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering) { get; set; } | Ermöglicht der Engine, Barcodes mit Salz- und Papierrauschen zu erkennen. Modus kann kleines Rauschen mit weißen und schwarzen Punkten entfernen. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving) { get; set; } | Ermöglicht der Engine, Bilder ohne kleine weiße Flecken als zusätzlichen Scan zu erkennen. Der Modus hilft bei der Erkennung von verrauschten Bildern sowie bei der Median-Glättungsfilterung. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants) { get; set; } | Ermöglicht der Engine, 1D-Barcodes mit Prüfsumme zu erkennen, indem mehr Erkennungsvarianten überprüft werden. Standardwert: Falsch. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings) { get; set; } | Barcode-Erkennungseinstellungen. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly) { get; set; } | Ermöglicht der Engine für 1D-Barcodes die schnelle Erkennung des mittleren Abschnitts eines Bildes und die Rückgabe des Ergebnisses ohne Verwendung zeitaufwändiger Algorithmen. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize) { get; set; } | Fenstergröße für Medianglättung. Typische Werte sind 3 oder 4. Der Standardwert ist 3. AllowMedianSmoothing muss festgelegt werden. |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes) { get; set; } | Ermöglicht der Engine, winzige Barcodes auf großen Bildern zu erkennen. Ignoriert, wenn[`AllowIncorrectBarcodes`](./allowincorrectbarcodes) auf True gesetzt ist. Standardwert: Falsch. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector) { get; set; } | Wechselt zum alten Barcode-Detektor. |

### Beispiele

Dieses Beispiel zeigt die Verwendung von QualitySettings mit BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // Hochleistungsmodus einstellen
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //normaler Qualitätsmodus ist standardmäßig eingestellt
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // hohen Qualitätsmodus mit langsamer Erkennung einstellen 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //Max. Barcodes-Modus einstellen, der versucht, alle möglichen Barcodes zu finden, auch falsche. Der langsamste Erkennungsmodus
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // Hochleistungsmodus einstellen
   reader.QualitySettings = QualitySettings.HighPerformance;
   // separate Optionen setzen
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //Standardmodus ist NormalQuality
   // separate Optionen setzen
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'Hochleistungsmodus einstellen
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'Standardmäßig ist der normale Qualitätsmodus eingestellt
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'Stellen Sie den Qualitätsmodus mit langsamer Erkennung ein
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'set max barcodes mode, der versucht, alle möglichen Barcodes zu finden, auch falsche. Der langsamste Erkennungsmodus
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'Hochleistungsmodus einstellen
   reader.QualitySettings = QualitySettings.HighPerformance
   'separate Optionen festlegen
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'Der Standardmodus ist NormalQuality
   'separate Optionen festlegen
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Siehe auch

* namensraum [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* Montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
