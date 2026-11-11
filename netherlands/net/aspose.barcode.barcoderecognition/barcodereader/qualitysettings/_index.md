---
title: "BarCodeReader.QualitySettings"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarCodeReader eigenschap. QualitySettings maakt handmatige configuratie van herkenningskwaliteit en -snelheid mogelijk. Je kunt QualitySettings snel instellen via ingebouwde presets HighPerformance, NormalQuality, HighQuality, MaxBarCodes, of je kunt afzonderlijke opties handmatig configureren. De standaardwaarde van QualitySettings is NormalQuality."
type: docs
weight: 70
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/qualitysettings/
---
## BarCodeReader.QualitySettings property

QualitySettings maakt het mogelijk om de herkenningskwaliteit en -snelheid handmatig te configureren. Je kunt QualitySettings snel instellen met ingebouwde presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes of je kunt afzonderlijke opties handmatig configureren. De standaardwaarde van QualitySettings is NormalQuality.

```csharp
public QualitySettings QualitySettings { get; set; }
```

### Property Value

QualitySettings om herkenningskwaliteit en -snelheid te configureren.

## Voorbeelden

Dit voorbeeld laat zien hoe QualitySettings te gebruiken met BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //zet high performance-modus
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //normale kwaliteitsmodus is standaard ingesteld
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //zet high performance-modus
   reader.QualitySettings = QualitySettings.HighPerformance;
   //stel afzonderlijke opties in
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    'set high performance mode
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    'normal quality mode is set by default
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
   'set high performance mode
   reader.QualitySettings = QualitySettings.HighPerformance
   'set separate options
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Zie ook

* class [QualitySettings](../../qualitysettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


