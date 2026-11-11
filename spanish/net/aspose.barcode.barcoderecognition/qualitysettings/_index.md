---
title: "Clase QualitySettings"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.BarCodeRecognition.QualitySettings. QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puede configurar rápidamente QualitySettings con los preajustes integrados HighPerformance NormalQuality HighQuality MaxQuality o puede configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality"
type: docs
weight: 370
url: /es/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puedes configurar rápidamente QualitySettings con los preajustes integrados: HighPerformance, NormalQuality, HighQuality, MaxQuality, o puedes configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality.

```csharp
public sealed class QualitySettings
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | Preajuste de calidad de reconocimiento HighPerformance. Los códigos de barras de alta calidad se reconocen bien en este modo. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | Preajuste de calidad de reconocimiento HighQuality. Este preajuste está desarrollado para códigos de barras de baja calidad. Permite detectar códigos de barras altamente dañados. |
| static [MaxQuality](../../aspose.barcode.barcoderecognition/qualitysettings/maxquality/) { get; } | Preajuste de calidad de reconocimiento MaxQuality. Este preajuste está desarrollado para reconocer todos los códigos de barras posibles, incluso códigos de barras incorrectos. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | Preajuste de calidad de reconocimiento NormalQuality. Adecuado para la mayoría de los códigos de barras |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | Permite al motor reconocer códigos de barras que tienen suma de verificación incorrecta o valores incorrectos. El modo puede usarse para reconocer códigos de barras dañados con texto incorrecto. |
| [BarcodeQuality](../../aspose.barcode.barcoderecognition/qualitysettings/barcodequality/) { get; set; } | Modo que permite a los métodos reconocer elementos de código de barras con la calidad seleccionada. Un elemento de código de barras con calidad inferior requiere métodos más complejos, lo que ralentiza el reconocimiento. |
| [ComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/complexbackground/) { get; set; } | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color. |
| [Deconvolution](../../aspose.barcode.barcoderecognition/qualitysettings/deconvolution/) { get; set; } | Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente, la deconvolución es una función que puede restaurar una imagen degradada (convolucionada) por cualquier función natural como el desenfoque, al obtener la imagen con una cámara. Como no podemos detectar la función que corrompe la imagen, debemos comprobar las funciones más conocidas, como sharpen o la morfología matemática. |
| [InverseImage](../../aspose.barcode.barcoderecognition/qualitysettings/inverseimage/) { get; set; } | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia). |
| [MinimalXDimension](../../aspose.barcode.barcoderecognition/qualitysettings/minimalxdimension/) { get; set; } | Tamaño mínimo de XDimension en píxeles que se usa con UseMinimalXDimension. |
| [XDimension](../../aspose.barcode.barcoderecognition/qualitysettings/xdimension/) { get; set; } | Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra. |

## Ejemplos

Este ejemplo muestra cómo usar QualitySettings con BarCodeReader

```csharp
[C#]
//establecer modo de reconocimiento HighPerformance
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//establecer modo de reconocimiento HighQuality
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//establecer modo de reconocimiento HighPerformance para códigos de barras de tamaño reducido
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//establecer modo de reconocimiento HighPerformance para códigos de barras de baja calidad
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}    
```

### Ver también

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


