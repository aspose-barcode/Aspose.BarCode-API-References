---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings clase"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings clase. QualitySettings permite configurar manualmente la calidad y velocidad del reconocimiento. Puedes configurar rápidamente QualitySettings con los presets integrados: HighPerformance, NormalQuality, HighQuality, MaxQuality o puedes configurar manualmente opciones separadas. El valor predeterminado de QualitySettings es NormalQuality en C++."
type: docs
weight: 3100
url: /es/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | Permite al motor reconocer códigos de barras que tienen checksum incorrecto o valores incorrectos. El modo puede usarse para reconocer códigos de barras dañados con texto incorrecto. |
| [get_BarcodeQuality](./get_barcodequality/)() const | Modo que habilita métodos para reconocer elementos de códigos de barras con la calidad seleccionada. Un elemento de código de barras con calidad inferior requiere métodos más complejos, lo que ralentiza el reconocimiento. |
| [get_ComplexBackground](./get_complexbackground/)() const | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes en color. |
| [get_Deconvolution](./get_deconvolution/)() const | Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente, la deconvolución es una función que puede restaurar una imagen degradada (convolucionada) por cualquier función natural como el desenfoque, al obtener la imagen con una cámara. Como no podemos detectar la función que corrompe la imagen, debemos comprobar las funciones más conocidas como sharp o la morfología matemática. |
| static [get_HighPerformance](./get_highperformance/)() | Preset de calidad de reconocimiento HighPerformance. Los códigos de barras de alta calidad se reconocen bien en este modo. |
| static [get_HighQuality](./get_highquality/)() | Preset de calidad de reconocimiento HighQuality. Este preset está desarrollado para códigos de barras de baja calidad. Permite detectar códigos de barras altamente dañados. |
| [get_InverseImage](./get_inverseimage/)() const | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia). |
| static [get_MaxQuality](./get_maxquality/)() | Preajuste de calidad de reconocimiento MaxQuality. Este preajuste está desarrollado para reconocer todos los códigos de barras posibles, incluso códigos de barras incorrectos. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | Tamaño mínimo de XDimension en píxeles que se utiliza con UseMinimalXDimension. |
| static [get_NormalQuality](./get_normalquality/)() | Preajuste de calidad de reconocimiento NormalQuality. Adecuado para la mayoría de los códigos de barras. |
| [get_XDimension](./get_xdimension/)() const | Modo [Recognition](../../aspose.barcode.barcoderecognition.recognition/) que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | Permite al motor reconocer códigos de barras que tienen checksum incorrecto o valores incorrectos. El modo puede usarse para reconocer códigos de barras dañados con texto incorrecto. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | Modo que habilita métodos para reconocer elementos de códigos de barras con la calidad seleccionada. Un elemento de código de barras con calidad inferior requiere métodos más complejos, lo que ralentiza el reconocimiento. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes en color. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente, la deconvolución es una función que puede restaurar una imagen degradada (convolucionada) por cualquier función natural como el desenfoque, al obtener la imagen con una cámara. Como no podemos detectar la función que corrompe la imagen, debemos comprobar las funciones más conocidas como sharp o la morfología matemática. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia). |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | Tamaño mínimo de XDimension en píxeles que se utiliza con UseMinimalXDimension. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | Modo [Recognition](../../aspose.barcode.barcoderecognition.recognition/) que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra. |
## Observaciones


Este ejemplo muestra cómo usar [QualitySettings](./) con [BarCodeReader](../barcodereader/)
```cpp
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

## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
