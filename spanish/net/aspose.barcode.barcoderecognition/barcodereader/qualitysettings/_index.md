---
title: QualitySettings
second_title: Referencia de API de Aspose.BarCode para .NET
description: QualitySettings permite configurar manualmente la calidad y la velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante ajustes preestablecidos integrados HighPerformance NormalQuality HighQuality MaxBarCodes o puede configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality.
type: docs
weight: 60
url: /es/net/aspose.barcode.barcoderecognition/barcodereader/qualitysettings/
---
## BarCodeReader.QualitySettings property

QualitySettings permite configurar manualmente la calidad y la velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante ajustes preestablecidos integrados: HighPerformance, NormalQuality, HighQuality, MaxBarCodes o puede configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality.

```csharp
public QualitySettings QualitySettings { get; set; }
```

### El valor de la propiedad

QualitySettings para configurar la calidad y velocidad del reconocimiento.

### Ejemplos

Este ejemplo muestra cómo usar QualitySettings con BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // establecer el modo de alto rendimiento
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //el modo de calidad normal está configurado por defecto
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // establecer el modo de alto rendimiento
   reader.QualitySettings = QualitySettings.HighPerformance;
   // establecer opciones separadas
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'configurar el modo de alto rendimiento
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'el modo de calidad normal está configurado de forma predeterminada
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'configurar el modo de alto rendimiento
   reader.QualitySettings = QualitySettings.HighPerformance
   'establecer opciones separadas
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Ver también

* class [QualitySettings](../../qualitysettings)
* class [BarCodeReader](../../barcodereader)
* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* asamblea [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->