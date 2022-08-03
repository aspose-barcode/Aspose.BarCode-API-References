---
title: QualitySettings
second_title: Riferimento all'API Aspose.BarCode per .NET
description: QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente QualitySettings tramite i preset incorporati HighPerformance NormalQuality HighQuality MaxBarCodes oppure è possibile configurare manualmente opzioni separate. Il valore predefinito di QualitySettings è NormalQuality.
type: docs
weight: 250
url: /it/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente QualitySettings tramite i preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oppure è possibile configurare manualmente opzioni separate. Il valore predefinito di QualitySettings è NormalQuality.

```csharp
public sealed class QualitySettings
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance) { get; } | Preimpostazione della qualità di riconoscimento HighPerformance. I codici a barre di alta qualità vengono riconosciuti bene in questa modalità. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality) { get; } | Preimpostazione della qualità di riconoscimento HighQuality. Questo preset è stato sviluppato per codici a barre di bassa qualità. Consente di rilevare codici a barre diagonali e molto danneggiati. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection) { get; } | Preimpostazione della qualità di riconoscimento HighQualityDetection. Come NormalQuality ma con alta qualità[`DetectorSettings`](./detectorsettings) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes) { get; } | Preimpostazione della qualità di riconoscimento di MaxBarCodes. Questo preset è stato sviluppato per riconoscere tutti i codici a barre possibili, anche quelli errati. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection) { get; } | Preimpostazione della qualità di riconoscimento MaxQualityDetection. Come NormalQuality ma con la massima qualità[`DetectorSettings`](./detectorsettings). Consente di rilevare codici a barre diagonali e danneggiati. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality) { get; } | Preimpostazione della qualità di riconoscimento NormalQuality. Adatto per la maggior parte dei codici a barre |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground) { get; set; } | Consente al motore di riconoscere i codici a barre a colori su uno sfondo colorato come scansione aggiuntiva. Modalità estremamente lenta. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes) { get; set; } | Consente al motore di Datamatrix di riconoscere i codici a barre Datamatrix industriali tratteggiati. Modalità lenta che aiuta solo per codici a barre tratteggiati costituiti da punti. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage) { get; set; } | Consente al motore di riconoscere l'immagine ridotta come scansione aggiuntiva. La dimensione per la diminuzione è selezionata dagli algoritmi interni del motore. La modalità aiuta a riconoscere i codici a barre che sono disturbati e sfocati ma catturati ad alta risoluzione. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap) { get; set; } | Consente al motore di utilizzare lo spazio tra le scansioni per aumentare la velocità di riconoscimento. La modalità può creare problemi di riconoscimento con codici a barre di altezza ridotta. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes) { get; set; } | Consente al motore di riconoscere codici a barre con checksum errati o valori errati. La modalità può essere utilizzata per riconoscere codici a barre danneggiati con testo errato. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage) { get; set; } | Consente al motore di riconoscere l'immagine a colori inversi come scansione aggiuntiva. La modalità può essere utilizzata quando il codice a barre è bianco su sfondo nero. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing) { get; set; } | Consente al motore di abilitare il livellamento mediano come scansione aggiuntiva. La modalità aiuta a riconoscere i codici a barre rumorosi. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving) { get; set; } | Consente al motore di codici a barre postali di riconoscere immagini leggermente disturbate. La modalità aiuta a riconoscere i codici a barre postali leggermente danneggiati. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector) { get; set; } | Consente al motore per codici a barre 1D di riconoscere rapidamente codici a barre di alta qualità che riempiono quasi l'intera immagine. La modalità aiuta a riconoscere rapidamente i codici a barre generati da Internet. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration) { get; set; } | Consente al motore per codici a barre 1D di riconoscere i codici a barre con singole barre cancellate/incollate nello schema. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration) { get; set; } | Consente al motore di QR/MicroQR di riconoscere i codici a barre MicroQR danneggiati. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage) { get; set; } | Consente al motore di riconoscere un'immagine normale senza alcun ripristino come scansione principale. Modalità per riconoscere l'immagine così com'è. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering) { get; set; } | Consente al motore di riconoscere i codici a barre con tipo di rumore sale e carta. La modalità può rimuovere piccoli disturbi con punti bianchi e neri. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving) { get; set; } | Consente al motore di riconoscere l'immagine senza piccoli punti bianchi come scansione aggiuntiva. La modalità aiuta a riconoscere l'immagine disturbata e il filtraggio di attenuazione mediana. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants) { get; set; } | Consente al motore di riconoscere codici a barre 1D con checksum controllando più varianti di riconoscimento. Valore predefinito: False. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings) { get; set; } | Impostazioni del rilevatore di codici a barre. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly) { get; set; } | Consente al motore per codici a barre 1D di riconoscere rapidamente la parte centrale di un'immagine e restituire il risultato senza utilizzare algoritmi che richiedono tempo. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize) { get; set; } | Dimensioni della finestra per l'arrotondamento mediano. I valori tipici sono 3 o 4. Il valore predefinito è 3. È necessario impostare AllowMedianSmoothing. |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes) { get; set; } | Consente al motore di riconoscere codici a barre minuscoli su immagini di grandi dimensioni. Ignorato se[`AllowIncorrectBarcodes`](./allowincorrectbarcodes) è impostato su Vero. Valore predefinito: False. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector) { get; set; } | Passa al vecchio rilevatore di codici a barre. |

### Esempi

Questo esempio mostra come utilizzare QualitySettings con BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //imposta la modalità ad alte prestazioni
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //la modalità di qualità normale è impostata per impostazione predefinita
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //imposta la modalità di alta qualità con il riconoscimento a bassa velocità 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //imposta la modalità max codici a barre, che cerca di trovare tutti i codici a barre possibili, anche errati. La modalità di riconoscimento più lenta
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //imposta la modalità ad alte prestazioni
   reader.QualitySettings = QualitySettings.HighPerformance;
   //imposta opzioni separate
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //la modalità predefinita è NormalQuality
   //imposta opzioni separate
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'impostare la modalità ad alte prestazioni
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'la modalità di qualità normale è impostata per impostazione predefinita
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'impostare la modalità alta qualità con riconoscimento a bassa velocità
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'imposta la modalità max codici a barre, che cerca di trovare tutti i codici a barre possibili, anche errati. La modalità di riconoscimento più lenta
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'impostare la modalità ad alte prestazioni
   reader.QualitySettings = QualitySettings.HighPerformance
   'impostare opzioni separate
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'la modalità predefinita è NormalQuality
   'impostare opzioni separate
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Guarda anche

* spazio dei nomi [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
