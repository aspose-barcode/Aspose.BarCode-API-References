---
title: "Clase Pdf417Parameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.Pdf417Parameters. Parámetros PDF417. Contiene los parámetros PDF417, MacroPDF417, MicroPDF417 y GS1MicroPdf417. MacroPDF417 requiere dos campos Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales. MicroPDF417 en modo Structured Append, al igual que el modo MacroPDF417, requiere dos campos Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales."
type: docs
weight: 1570
url: /es/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

Parámetros de PDF417. Contiene los parámetros PDF417, MacroPDF417, MicroPDF417 y GS1MicroPdf417. MacroPDF417 requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales. MicroPDF417 en modo Structured Append (igual que el modo MacroPDF417) requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales.

```csharp
public class Pdf417Parameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | Relación altura/ancho del módulo de código de barras 2D. |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | Recuento de columnas. |
| [ECIEncoding](../../aspose.barcode.generation/pdf417parameters/eciencoding/) { get; set; } | Identificadores de Interpretación de Canal Extendida. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. No se aplican a los campos de texto Macro PDF417. La implementación actual incluye todas las codificaciones de conjunto de caracteres conocidas. |
| [EncodeMode](../../aspose.barcode.generation/pdf417parameters/encodemode/) { get; set; } | Identifica el modo de codificación Pdf417. Valor predeterminado: Auto. |
| [ErrorLevel](../../aspose.barcode.generation/pdf417parameters/errorlevel/) { get; set; } | Obtiene o establece el tipo de simbología Pdf417 del nivel de corrección de errores de BarCode, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección, lo que implica una imagen más grande. |
| [IsCode128Emulation](../../aspose.barcode.generation/pdf417parameters/iscode128emulation/) { get; set; } | Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en modos de segunda posición 908 y 909, también puede codificar 910 y 911 que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128. |
| [IsLinked](../../aspose.barcode.generation/pdf417parameters/islinked/) { get; set; } | Define modos vinculados con códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado que no sea un EAN.UCC. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [MacroCharacters](../../aspose.barcode.generation/pdf417parameters/macrocharacters/) { get; set; } | Los valores de los caracteres macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Solo se pueden usar con MicroPdf417 y codifican los modos 916 y 917 de MicroPdf417. Valor predeterminado: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.generation/pdf417parameters/macropdf417addressee/) { get; set; } | Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [MacroPdf417Checksum](../../aspose.barcode.generation/pdf417parameters/macropdf417checksum/) { get; set; } | Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append). El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) usando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/macropdf417eciencoding/) { get; set; } | Identificadores de Interpretación de Canal Extendida. Se aplican a los campos de texto Macro PDF417. |
| [MacroPdf417FileID](../../aspose.barcode.generation/pdf417parameters/macropdf417fileid/) { get; set; } | ID de archivo del código de barras MacroPdf417 (campo requerido). ID de archivo del código de barras MicroPDF417 (campo requerido para el modo Structured Append). |
| [MacroPdf417FileName](../../aspose.barcode.generation/pdf417parameters/macropdf417filename/) { get; set; } | Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [MacroPdf417FileSize](../../aspose.barcode.generation/pdf417parameters/macropdf417filesize/) { get; set; } | Tamaño de archivo MacroPdf417 (campo opcional). Tamaño de archivo MicroPDF417 (campo opcional para el modo Structured Append) El campo de tamaño de archivo contiene el tamaño en bytes de todo el archivo fuente. |
| [MacroPdf417SegmentID](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentid/) { get; set; } | ID de segmento del código de barras MacroPdf417 (campo requerido), que comienza en 0 hasta MacroSegmentsCount - 1. ID de segmento del código de barras MicroPDF417 (campo requerido para el modo Structured Append). |
| [MacroPdf417SegmentsCount](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentscount/) { get; set; } | Recuento de segmentos del código de barras MacroPdf417 (campo opcional). Recuento de segmentos del código de barras MicroPDF417 (campo opcional para el modo Structured Append). |
| [MacroPdf417Sender](../../aspose.barcode.generation/pdf417parameters/macropdf417sender/) { get; set; } | Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [MacroPdf417Terminator](../../aspose.barcode.generation/pdf417parameters/macropdf417terminator/) { get; set; } | Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. Aplicado solo para Macro PDF417. |
| [MacroPdf417TimeStamp](../../aspose.barcode.generation/pdf417parameters/macropdf417timestamp/) { get; set; } | Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | Recuento de filas. |
| [Truncate](../../aspose.barcode.generation/pdf417parameters/truncate/) { get; set; } | Indica si el tipo de simbología Pdf417 del BarCode está truncado (para reducir espacio). También conocido como CompactPDF417. El indicador de fila derecha y el patrón de parada derecha se eliminan en este modo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | Devuelve una representación de cadena legible por humanos de este `Pdf417Parameters`. |

## Ejemplos

Estos ejemplos muestran cómo codificar los modos no vinculados UCC/EAN-128 en GS1MicroPdf417.

```csharp
[C#]
//Codifica el modo no vinculado 905 de GS1 UCC/EAN-128 con AI 01 (GTIN).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Codifica los modos no vinculados 903, 904 de GS1 UCC/EAN-128 con cualquier AI.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


