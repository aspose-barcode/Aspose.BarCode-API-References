---
title: "Clase Pdf417ParametersUI"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Windows.Forms.Pdf417ParametersUI. Contenedor UI para la clase Pdf417Parameters"
type: docs
weight: 1860
url: /es/net/aspose.barcode.windows.forms/pdf417parametersui/
---
## Pdf417ParametersUI class

Contenedor UI para la clase [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/).

```csharp
public class Pdf417ParametersUI
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/pdf417parametersui/aspectratio/) { get; set; } | Relación altura/ancho del módulo de código de barras 2D. |
| [Columns](../../aspose.barcode.windows.forms/pdf417parametersui/columns/) { get; set; } | Recuento de columnas. |
| [ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/eciencoding/) { get; set; } | Identificadores de Interpretación de Canal Extendida. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. No se aplican a los campos de texto Macro PDF417. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas. |
| [EncodeMode](../../aspose.barcode.windows.forms/pdf417parametersui/encodemode/) { get; set; } | Tipo de simbología Pdf417 del modo de codificación de BarCode. Valor predeterminado: Pdf417EncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.windows.forms/pdf417parametersui/errorlevel/) { get; set; } | Obtiene o establece el tipo de simbología Pdf417 del nivel de corrección de errores de BarCode, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección, lo que implica una imagen más grande. |
| [IsCode128Emulation](../../aspose.barcode.windows.forms/pdf417parametersui/iscode128emulation/) { get; set; } | Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en modos de segunda posición 908 y 909, también puede codificar 910 y 911 que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128. |
| [IsLinked](../../aspose.barcode.windows.forms/pdf417parametersui/islinked/) { get; set; } | Define modos vinculados con códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado que no sea un EAN.UCC. |
| [IsReaderInitialization](../../aspose.barcode.windows.forms/pdf417parametersui/isreaderinitialization/) { get; set; } | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [MacroCharacters](../../aspose.barcode.windows.forms/pdf417parametersui/macrocharacters/) { get; set; } | Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Solo se pueden usar con MicroPdf417 y codifican los modos 916 y 917 de MicroPdf417. Valor predeterminado: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417addressee/) { get; set; } | Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [MacroPdf417Checksum](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417checksum/) { get; set; } | Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append). El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) usando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417eciencoding/) { get; set; } | Identificadores de Interpretación de Canal Extendida. Se aplican a los campos de texto Macro PDF417. |
| [MacroPdf417FileID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417fileid/) { get; set; } | Obtiene o establece el ID de archivo del código de barras macro Pdf417. Utilizado para MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filename/) { get; set; } | Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [MacroPdf417FileSize](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filesize/) { get; set; } | Tamaño de archivo MacroPdf417 (campo opcional). Tamaño de archivo MicroPDF417 (campo opcional para el modo Structured Append) El campo de tamaño de archivo contiene el tamaño en bytes de todo el archivo fuente. |
| [MacroPdf417SegmentID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentid/) { get; set; } | Obtiene o establece el ID de segmento del código de barras macro Pdf417, que comienza en 0, hasta MacroSegmentsCount - 1. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentscount/) { get; set; } | Obtiene o establece el recuento de segmentos del código de barras macro Pdf417. |
| [MacroPdf417Sender](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417sender/) { get; set; } | Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [MacroPdf417Terminator](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417terminator/) { get; set; } | Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. Aplicado solo para Macro PDF417. |
| [MacroPdf417TimeStamp](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417timestamp/) { get; set; } | Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [Rows](../../aspose.barcode.windows.forms/pdf417parametersui/rows/) { get; set; } | Recuento de filas. |
| [Truncate](../../aspose.barcode.windows.forms/pdf417parametersui/truncate/) { get; set; } | Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/pdf417parametersui/tostring/)() | Devuelve una representación de cadena legible para humanos de este [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/). |

### Ver también

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


