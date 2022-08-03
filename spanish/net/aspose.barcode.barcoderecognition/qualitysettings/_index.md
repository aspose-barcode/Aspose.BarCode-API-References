---
title: QualitySettings
second_title: Referencia de API de Aspose.BarCode para .NET
description: QualitySettings permite configurar manualmente la calidad y la velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante ajustes preestablecidos integrados HighPerformance NormalQuality HighQuality MaxBarCodes o puede configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality.
type: docs
weight: 250
url: /es/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings permite configurar manualmente la calidad y la velocidad del reconocimiento. Puede configurar rápidamente QualitySettings mediante ajustes preestablecidos integrados: HighPerformance, NormalQuality, HighQuality, MaxBarCodes o puede configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality.

```csharp
public sealed class QualitySettings
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance) { get; } | Valor predeterminado de calidad de reconocimiento de alto rendimiento. Los códigos de barras de alta calidad se reconocen bien en este modo. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality) { get; } | Valor predeterminado de calidad de reconocimiento HighQuality. Este preajuste está desarrollado para códigos de barras de baja calidad. Permite detectar códigos de barras diagonales y muy dañados. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection) { get; } | Valor predeterminado de calidad de reconocimiento HighQualityDetection. Igual que NormalQuality pero con alta calidad[`DetectorSettings`](./detectorsettings) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes) { get; } | Valor predeterminado de calidad de reconocimiento de MaxBarCodes. Este preajuste está desarrollado para reconocer todos los códigos de barras posibles, incluso los códigos de barras incorrectos. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection) { get; } | Valor predeterminado de calidad de reconocimiento MaxQualityDetection. Igual que NormalQuality pero con la más alta calidad[`DetectorSettings`](./detectorsettings). Permite detectar códigos de barras diagonales y dañados. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality) { get; } | Valor predeterminado de calidad de reconocimiento de NormalQuality. Adecuado para la mayoría de códigos de barras |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground) { get; set; } | Permite que el motor reconozca códigos de barras de color sobre fondo de color como escaneo adicional. Modo extremadamente lento. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes) { get; set; } | Permite que el motor de Datamatrix reconozca códigos de barras industriales de Datamatrix discontinuos. Modo lento que ayuda solo para códigos de barras discontinuos que consisten en puntos. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage) { get; set; } | Permite que el motor reconozca una imagen disminuida como escaneo adicional. Los algoritmos internos del motor seleccionan el tamaño para disminuir. El modo ayuda a reconocer los códigos de barras que tienen ruido y están borrosos pero capturados con alta resolución. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap) { get; set; } | Permite que el motor use la brecha entre escaneos para aumentar la velocidad de reconocimiento. El modo puede generar problemas de reconocimiento con códigos de barras de baja altura. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes) { get; set; } | Permite que el motor reconozca los códigos de barras que tienen una suma de verificación incorrecta o valores incorrectos. El modo se puede utilizar para reconocer códigos de barras dañados con texto incorrecto. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage) { get; set; } | Permite que el motor reconozca la imagen de color inverso como escaneo adicional. El modo se puede usar cuando el código de barras es blanco sobre fondo negro. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing) { get; set; } | Permite que el motor habilite el suavizado de la mediana como exploración adicional. El modo ayuda a reconocer los códigos de barras ruidosos. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving) { get; set; } | Permite que el motor de códigos de barras postales reconozca imágenes ligeramente ruidosas. El modo ayuda a reconocer códigos de barras postales ligeramente dañados. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector) { get; set; } | Permite que el motor de códigos de barras 1D reconozca rápidamente códigos de barras de alta calidad que llenan casi toda la imagen. El modo ayuda a reconocer rápidamente los códigos de barras generados desde Internet. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration) { get; set; } | Permite que el motor para códigos de barras 1D reconozca códigos de barras con barras limpias/pegadas individuales en patrón. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration) { get; set; } | Permite que el motor para QR/MicroQR reconozca códigos de barras MicroQR dañados. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage) { get; set; } | Permite que el motor reconozca una imagen normal sin ninguna restauración como exploración principal. Modo para reconocer la imagen tal cual. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering) { get; set; } | Permite que el motor reconozca códigos de barras con sal y ruido de papel. El modo puede eliminar pequeños ruidos con puntos blancos y negros. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving) { get; set; } | Permite que el motor reconozca la imagen sin pequeños puntos blancos como exploración adicional. El modo ayuda a reconocer la imagen con ruido, así como el filtrado de suavizado medio. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants) { get; set; } | Permite que el motor reconozca códigos de barras 1D con suma de verificación al verificar más variantes de reconocimiento. Valor por defecto: Falso. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings) { get; set; } | Configuración del detector de código de barras. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly) { get; set; } | Permite que el motor de códigos de barras 1D reconozca rápidamente el segmento medio de una imagen y devuelva el resultado sin usar ningún algoritmo que requiera mucho tiempo. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize) { get; set; } | Tamaño de la ventana para suavizar la mediana. Los valores típicos son 3 o 4. El valor predeterminado es 3. Debe establecerse AllowMedianSmoothing. |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes) { get; set; } | Permite que el motor reconozca códigos de barras diminutos en imágenes grandes. ignorado si[`AllowIncorrectBarcodes`](./allowincorrectbarcodes) se establece en Verdadero. Valor por defecto: Falso. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector) { get; set; } | Cambia al antiguo detector de código de barras. |

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
   // establecer el modo de alta calidad con reconocimiento de baja velocidad 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // establece el modo de códigos de barras máximos, que intenta encontrar todos los códigos de barras posibles, incluso los incorrectos. El modo de reconocimiento más lento
   reader.QualitySettings = QualitySettings.MaxBarCodes;
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
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //el modo predeterminado es NormalQuality
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
    'establecer el modo de alta calidad con reconocimiento de baja velocidad
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'establezca el modo de códigos de barras máximos, que intenta encontrar todos los códigos de barras posibles, incluso los incorrectos. El modo de reconocimiento más lento
    reader.QualitySettings = QualitySettings.MaxBarCodes
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
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'el modo predeterminado es NormalQuality
   'establecer opciones separadas
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Ver también

* espacio de nombres [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
