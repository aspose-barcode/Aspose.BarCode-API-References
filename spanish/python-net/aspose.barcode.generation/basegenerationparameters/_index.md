---
title: "BaseGenerationParameters"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/basegenerationparameters/
---

## BaseGenerationParameters class

Parámetros de generación de imágenes de códigos de barras.

El tipo BaseGenerationParameters expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| use_anti_alias | Obtiene o establece un valor que indica si se utiliza el modo anti-aliasing para renderizar la imagen |
| back_color | Color de fondo de la imagen del código de barras.<br/>            Valor predeterminado: Color.White.<br/>            Ver [Color](/barcode/python-net/aspose.drawing/color/). |
| resolución | Obtiene o establece la resolución de la imagen BarCode.<br/>            Un valor para ambas dimensiones.<br/>            Valor predeterminado: 96 dpi. |
| rotation_angle | Ángulo de rotación de la imagen BarCode, medido en grados, p. ej. RotationAngle = 0 o RotationAngle = 360 significa sin rotación.<br/>            Si RotationAngle NO es igual a 90, 180, 270 o 0, puede aumentar la dificultad para que el escáner lea la imagen.<br/>            Valor predeterminado: 0. |
| caption_above | Título encima de la imagen BarCode. Ver [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| caption_below | Título debajo de la imagen BarCode. Ver [CaptionParameters](/barcode/python-net/aspose.barcode.generation/captionparameters/). |
| image | Parámetros de imagen. Ver [ImageParameters](/barcode/python-net/aspose.barcode.generation/imageparameters/). |
| auto_size_mode | Especifica los diferentes tipos de modos de dimensionado automático.<br/>            Valor predeterminado: AutoSizeMode.None. |
| image_height | Altura de la imagen BarCode cuando la propiedad [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) está configurada a AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| image_width | Ancho de la imagen BarCode cuando la propiedad [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) está configurada a AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| barcode | Obtiene los [BarcodeParameters](/barcode/python-net/aspose.barcode.generation/barcodeparameters/) que contiene todas las propiedades del código de barras. |
| border | Obtiene los [BorderParameters](/barcode/python-net/aspose.barcode.generation/borderparameters/) que contiene todas las propiedades de configuración para el borde del código de barras. |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

