---
title: "BarCodeReader.QualitySettings"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété BarCodeReader. QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings à l'aide des préréglages intégrés HighPerformance, NormalQuality, HighQuality, MaxBarCodes ou configurer manuellement des options séparées. La valeur par défaut de QualitySettings est NormalQuality."
type: docs
weight: 70
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/qualitysettings/
---
## BarCodeReader.QualitySettings property

QualitySettings permet de configurer manuellement la qualité et la vitesse de la reconnaissance. Vous pouvez rapidement configurer QualitySettings à l'aide des préréglages intégrés : HighPerformance, NormalQuality, HighQuality, MaxBarCodes ou vous pouvez configurer manuellement des options séparées. La valeur par défaut de QualitySettings est NormalQuality.

```csharp
public QualitySettings QualitySettings { get; set; }
```

### Property Value

QualitySettings pour configurer la qualité et la vitesse de reconnaissance.

## Exemples

Cet exemple montre comment utiliser QualitySettings avec BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //définir le mode haute performance
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //le mode qualité normale est défini par défaut
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //définir le mode haute performance
   reader.QualitySettings = QualitySettings.HighPerformance;
   //définir des options séparées
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

### Voir aussi

* class [QualitySettings](../../qualitysettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


