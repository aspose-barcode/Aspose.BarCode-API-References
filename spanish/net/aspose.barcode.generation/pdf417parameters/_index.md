---
title: Pdf417Parameters
second_title: Referencia de API de Aspose.BarCode para .NET
description: Parámetros de PDF417. Contiene parámetros PDF417 MacroPDF417 y MicroPDF417. MacroPDF417 requiere dos campos Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales. MicroPDF417 en el modo Anexo estructurado igual que el modo MacroPDF417 requiere dos campos Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales.
type: docs
weight: 860
url: /es/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

Parámetros de PDF417. Contiene parámetros PDF417, MacroPDF417 y MicroPDF417. MacroPDF417 requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales. MicroPDF417 en el modo Anexo estructurado (igual que el modo MacroPDF417) requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales.

```csharp
public class Pdf417Parameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio) { get; set; } | Relación alto/ancho del módulo de código de barras 2D. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation) { get; set; } | Código de función para la emulación del Código 128. Aplicado solo para MicroPDF417. Ignorado para códigos de barras PDF417 y MacroPDF417. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding) { get; set; } | Obtiene o establece la codificación de codetext. Valor predeterminado: UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns) { get; set; } | Número de columnas. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization) { get; set; } | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode) { get; set; } | Pdf417 tipo de simbología del modo de compactación de BarCode. Valor por defecto: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding) { get; set; } | Identificadores de interpretación de canal extendido. Se utiliza para informar al lector de código de barras detalles sobre las referencias utilizadas para codificar los datos en el símbolo. No se aplica a los campos de texto Macro PDF417. La implementación actual consta de todas las codificaciones de conjuntos de caracteres bien conocidas. |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel) { get; set; } | Obtiene o establece el tipo de simbología Pdf417 del nivel de corrección de errores de BarCode que va desde level0 a level8, level0 significa que no hay información de corrección de errores, level8 significa la mejor corrección de errores, lo que significa una imagen más grande. |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee) { get; set; } | Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Anexo estructurado) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum) { get; set; } | Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo de adición estructurada) El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) utilizando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding) { get; set; } | Identificadores de interpretación de canal extendido. Aplica para campos de texto Macro PDF417. |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid) { get; set; } | Id. de archivo del código de barras MacroPdf417 (campo obligatorio). Id. de archivo del código de barras MicroPDF417 (campo obligatorio para el modo de anexo estructurado) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename) { get; set; } | Nombre del archivo de código de barras MacroPdf417 (campo opcional). Nombre del archivo de código de barras MicroPDF417 (campo opcional para el modo Anexo estructurado) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize) { get; set; } | Tamaño del archivo MacroPdf417 (campo opcional). Tamaño del archivo MicroPDF417 (campo opcional para el modo Anexo estructurado) El campo de tamaño del archivo contiene el tamaño en bytes de todo el archivo de origen. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid) { get; set; } | Id. de segmento del código de barras MacroPdf417 (campo obligatorio), que comienza desde 0, hasta MacroSegmentsCount - 1. Id. de segmento del código de barras MicroPDF417 (campo obligatorio para el modo de anexo estructurado) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount) { get; set; } | Recuento de segmentos de código de barras MacroPdf417 (campo opcional). Recuento de segmentos de código de barras MicroPDF417 (campo opcional para modo Anexo estructurado) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender) { get; set; } | Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Anexo estructurado) |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp) { get; set; } | Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Anexo estructurado) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate) { get; set; } | Si el tipo de simbología Pdf417 de BarCode está truncado (para reducir el espacio). También conocido como CompactPDF417. El indicador de fila derecha y el patrón de parada derecha se eliminan en este modo. |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows) { get; set; } | Recuento de filas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring)() | Devuelve una representación de cadena legible por humanos de este[`Pdf417Parameters`](../pdf417parameters) . |

### Ver también

* espacio de nombres [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* asamblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
