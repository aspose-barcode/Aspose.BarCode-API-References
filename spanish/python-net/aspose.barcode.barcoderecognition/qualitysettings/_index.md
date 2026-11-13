---
title: "QualitySettings"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

QualitySettings permite configurar la calidad y velocidad del reconocimiento manualmente.<br/>            Puede configurar rápidamente QualitySettings con los preajustes integrados: HighPerformance, NormalQuality, HighQuality, MaxQuality o puede configurar manualmente opciones separadas.<br/>            El valor predeterminado de QualitySettings es NormalQuality.

El tipo QualitySettings expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| high_performance | Preajuste de calidad de reconocimiento HighPerformance. Los códigos de barras de alta calidad se reconocen bien en este modo. |
| normal_quality | Preajuste de calidad de reconocimiento NormalQuality. Adecuado para la mayoría de los códigos de barras |
| high_quality | Preajuste de calidad de reconocimiento HighQuality. Este preajuste está desarrollado para códigos de barras de baja calidad. Permite detectar códigos de barras muy dañados. |
| max_quality | Preajuste de calidad de reconocimiento MaxQuality. Este preajuste está desarrollado para reconocer todos los códigos de barras posibles, incluso códigos de barras incorrectos. |
| x_dimension | Modo de reconocimiento que establece el tamaño (de 1 a infinito) del elemento mínimo del código de barras: celda de matriz o barra. |
| minimal_x_dimension | Tamaño mínimo de XDimension en píxeles que se utiliza con UseMinimalXDimension. |
| barcode_quality | Modo que habilita métodos para reconocer elementos del código de barras con la calidad seleccionada. Un elemento del código de barras con calidad inferior requiere métodos más complejos, lo que ralentiza el reconocimiento. |
| deconvolution | Modo de deconvolución (restauración de imágenes) que define el nivel de degradación de la imagen. Originalmente, la deconvolución es una función que puede restaurar una imagen degradada <br/>            (convolucionada) por cualquier función natural como el desenfoque, al obtener la imagen con una cámara. Debido a que no podemos detectar la función de imagen que corrompe la imagen, <br/>            debemos comprobar las funciones más conocidas como nitidez o morfología matemática. |
| inverse_image | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras en imágenes con colores invertidos (luminancia). |
| complex_background | Modo que habilita o deshabilita el reconocimiento adicional de códigos de barras de color en imágenes a color. |
| allow_incorrect_barcodes | Permite que el motor reconozca códigos de barras que tienen checksumm incorrecto o valores incorrectos. El modo puede usarse para reconocer códigos de barras dañados con texto incorrecto. |

### Ver también

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

