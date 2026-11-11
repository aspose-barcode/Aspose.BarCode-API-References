---
title: "BarCodeReader.QualitySettings"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Propiedad BarCodeReader. QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante los preajustes incorporados HighPerformance, NormalQuality, HighQuality, MaxBarCodes, o puede configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality."
type: docs
weight: 70
url: /es/net/aspose.barcode.barcoderecognition/barcodereader/qualitysettings/
---
## BarCodeReader.QualitySettings property

QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puedes configurar rápidamente QualitySettings mediante los presets integrados: HighPerformance, NormalQuality, HighQuality, MaxBarCodes o puedes configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality.

```csharp
public QualitySettings QualitySettings { get; set; }
```

### Property Value

QualitySettings para configurar la calidad y velocidad del reconocimiento.

## Ejemplos

Este ejemplo muestra cómo usar QualitySettings con BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //establecer modo HighPerformance
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //el modo NormalQuality está establecido por defecto
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //establecer modo HighPerformance
   reader.QualitySettings = QualitySettings.HighPerformance;
   //establecer opciones separadas
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

### Ver también

* class [QualitySettings](../../qualitysettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


