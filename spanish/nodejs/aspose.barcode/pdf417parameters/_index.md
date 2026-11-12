---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Parámetros PDF417."
type: docs
weight: 770
url: /es/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

Parámetros PDF417. Contiene los parámetros PDF417, MacroPDF417, MicroPDF417 y GS1MicroPdf417. MacroPDF417 requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales. MicroPDF417 en modo Structured Append (igual que el modo MacroPDF417) requiere dos campos: Pdf417MacroFileID y Pdf417MacroSegmentID. Todos los demás campos son opcionales. Estos ejemplos muestran cómo codificar modos no vinculados UCC/EAN-128 en GS1MicroPdf417

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Relación altura/ancho del módulo de código de barras 2D. |
| [getColumns()](#getcolumns) | Recuento de columnas. |
| [getECIEncoding()](#geteciencoding) | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para |
| [getEncodeMode()](#getencodemode) | Identifica el modo de codificación Pdf417. Valor predeterminado: Auto. |
| [getErrorLevel()](#geterrorlevel) | Obtiene el tipo de simbología Pdf417 del nivel de corrección de errores del BarCode, que varía de level0 a level8, level0 significa sin corrección de errores |
| [getMacroCharacters()](#getmacrocharacters) | Los valores de los caracteres Macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Sólo se pueden usar con Micro |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para Structured A |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417. |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | ID de archivo del código de barras MacroPdf417 (campo obligatorio). ID de archivo del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append) |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Tamaño de archivo MacroPdf417 (campo opcional). Tamaño de archivo MicroPDF417 (campo opcional para el modo Structured Append) El tamaño de archivo |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | ID de segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0, hasta MacroSegmentsCount - 1. del código de barras MicroPDF417 |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Recuento de segmentos del código de barras MacroPdf417 (campo opcional). Recuento de segmentos del código de barras MicroPDF417 (campo opcional para Structured A |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para Structured Append) |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. Aplicado solo para Macro PD |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para Structured Append mo |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | Tipo de simbología Pdf417 del modo de compactación del código de barras. Valor predeterminado: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Identifica el modo de codificación Pdf417. Valor predeterminado: Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | Obtiene el tipo de simbología Pdf417 del nivel de corrección de errores del BarCode, que varía de level0 a level8, level0 significa sin corrección de errores |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | Obtiene el nombre del destinatario del código de barras macro Pdf417. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | Obtiene la suma de verificación del código de barras macro Pdf417. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417. |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Obtiene la ID de archivo del código de barras Pdf417. Se usa para MacroPdf417. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | Obtiene el nombre de archivo del código de barras macro Pdf417. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | Obtiene el tamaño de archivo del macro Pdf417. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | Obtiene el ID de segmento del código de barras macro Pdf417, que comienza en 0, hasta MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | Obtiene el recuento de segmentos del código de barras macro Pdf417. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | Obtiene el nombre del remitente del código de barras macro Pdf417. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. Aplicado solo para Macro PD |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | Obtiene la marca de tiempo del código de barras macro Pdf417. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). |
| [getRows()](#getrows) | Recuento de filas. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Identifica la ID del código de barras en modo de apéndice estructurado DotCode. La ID comienza en 1 y debe ser menor o igual que los códigos de barras |
| [getTruncate()](#gettruncate) | Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). También conocido como CompactPDF417. Indicador de fila derecha |
| [isCode128Emulation()](#iscode128emulation) | Sólo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en la segunda posición en los modos 908 y |
| [isLinked()](#islinked) | Define modos vinculados con códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417 con la simbología GS1MicroPdf417 codifica 906, 907 |
| [isReaderInitialization()](#isreaderinitialization) | Se utiliza para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector |
| [setAspectRatio()](#setaspectratio) | Relación altura/ancho del módulo de código de barras 2D. |
| [setCode128Emulation()](#setcode128emulation) | Sólo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en la segunda posición en los modos 908 y |
| [setColumns()](#setcolumns) | Recuento de columnas. |
| [setECIEncoding()](#seteciencoding) | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para |
| [setEncodeMode()](#setencodemode) | Identifica el modo de codificación Pdf417. Valor predeterminado: Auto. |
| [setErrorLevel(value)](#seterrorlevel) | Establece el tipo de simbología Pdf417 del nivel de corrección de errores del código de barras, que varía de level0 a level8; level0 significa sin corrección de errores |
| [setLinked()](#setlinked) | Define modos vinculados con códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417 con la simbología GS1MicroPdf417 codifica 906, 907 |
| [setMacroCharacters()](#setmacrocharacters) | Los valores de los caracteres Macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Sólo se pueden usar con Micro |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para Structured A |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417. |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | ID de archivo del código de barras MacroPdf417 (campo obligatorio). ID de archivo del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append) |
| [setMacroPdf417FileName()](#setmacropdf417filename) | Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append) |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | Tamaño de archivo MacroPdf417 (campo opcional). Tamaño de archivo MicroPDF417 (campo opcional para el modo Structured Append) El tamaño de archivo |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | ID de segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0, hasta MacroSegmentsCount - 1. del código de barras MicroPDF417 |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | Recuento de segmentos del código de barras MacroPdf417 (campo opcional). Recuento de segmentos del código de barras MicroPDF417 (campo opcional para Structured A |
| [setMacroPdf417Sender()](#setmacropdf417sender) | Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para Structured Append) |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. Aplicado solo para Macro PD |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para Structured Append mo |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | Tipo de simbología Pdf417 del modo de compactación del código de barras. Valor predeterminado: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Identifica el modo de codificación Pdf417. Valor predeterminado: Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Establece el tipo de simbología Pdf417 del nivel de corrección de errores del código de barras, que varía de level0 a level8; level0 significa sin corrección de errores |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | Establece el nombre del destinatario del código de barras macro Pdf417. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | Establece la suma de verificación del código de barras macro Pdf417. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417. |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | Establece el ID de archivo del código de barras macro Pdf417. Se utiliza para MacroPdf417. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | Establece el nombre de archivo del código de barras macro Pdf417. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | Establece el tamaño de archivo del macro Pdf417. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | Establece el ID de segmento del código de barras macro Pdf417, que comienza en 0 y llega a MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | Establece el recuento de segmentos del código de barras macro Pdf417. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | Establece el nombre del remitente del código de barras macro Pdf417. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código de palabra 922) al segmento. Aplicado solo para Macro PD |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | Establece la marca de tiempo del código de barras macro Pdf417. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). |
| [setReaderInitialization(value)](#setreaderinitialization) | Se utiliza para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector |
| [setRows()](#setrows) | Recuento de filas. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Identifica la ID del código de barras en modo de apéndice estructurado DotCode. La ID comienza en 1 y debe ser menor o igual que los códigos de barras |
| [setTruncate()](#settruncate) | Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio). También conocido como CompactPDF417. Indicador de fila derecha |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este Pdf417Parameters. |

### getAspectRatio() {#getaspectratio}

Relación altura/ancho del módulo de código de barras 2D.

### getColumns() {#getcolumns}

Recuento de columnas.

### getECIEncoding() {#geteciencoding}

Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. No se aplican a los campos de texto Macro PDF417. La implementación actual incluye todas las codificaciones de conjunto de caracteres bien conocidas.

### getEncodeMode() {#getencodemode}

Identifica el modo de codificación Pdf417. Valor predeterminado: Auto.

### getErrorLevel() {#geterrorlevel}

Obtiene el tipo de simbología Pdf417 del nivel de corrección de errores del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

Los valores de los Caracteres Macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Sólo pueden usarse con MicroPdf417 y codifican los modos 916 y 917 de MicroPdf417. Valor predeterminado: MacroCharacters.None. Estas muestras muestran cómo codificar Caracteres Macro en MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append). El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) usando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417.

### getMacroPdf417FileID() {#getmacropdf417fileid}

ID de archivo del código de barras MacroPdf417 (campo obligatorio). ID de archivo del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

### getMacroPdf417FileName() {#getmacropdf417filename}

Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Tamaño de archivo MacroPdf417 (campo opcional). Tamaño de archivo MicroPDF417 (campo opcional para el modo Structured Append). El campo de tamaño de archivo contiene el tamaño en bytes de todo el archivo fuente.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

ID de segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0 y llega a MacroSegmentsCount - 1. ID de segmento del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Recuento de segmentos del código de barras MacroPdf417 (campo opcional). Recuento de segmentos del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

### getMacroPdf417Sender() {#getmacropdf417sender}

Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código 922) al segmento. Se aplica solo a Macro PDF417.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Structured Append)

### getPdf417CompactionMode() {#getpdf417compactionmode}

Tipo de simbología Pdf417 del modo de compactación del código de barras. Valor predeterminado: Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual consiste en todas las codificaciones de conjuntos de caracteres bien conocidas.

### getPdf417EncodeMode() {#getpdf417encodemode}

Identifica el modo de codificación Pdf417. Valor predeterminado: Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Obtiene el tipo de simbología Pdf417 del nivel de corrección de errores del código de barras, que varía de level0 a level8; level0 significa sin información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Obtiene el nombre del destinatario del código de barras macro Pdf417.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Obtiene la suma de verificación del código de barras macro Pdf417.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417.

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Obtiene la ID de archivo del código de barras Pdf417. Se usa para MacroPdf417.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Obtiene el nombre de archivo del código de barras macro Pdf417.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Obtiene el tamaño de archivo del macro Pdf417.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Obtiene el ID de segmento del código de barras macro Pdf417, que comienza en 0, hasta MacroSegmentsCount - 1.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Obtiene el recuento de segmentos del código de barras macro Pdf417.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

Obtiene el nombre del remitente del código de barras macro Pdf417.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código 922) al segmento. Se aplica solo a Macro PDF417.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Obtiene la marca de tiempo del código de barras macro Pdf417.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio).

### getRows() {#getrows}

Recuento de filas.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Identifica el ID del código de barras DotCode en modo structured append. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1.

### getTruncate() {#gettruncate}

Indica si el tipo de simbología Pdf417 del BarCode está truncado (para reducir espacio). También conocido como CompactPDF417. El indicador de fila derecha y el patrón de parada derecha se eliminan en este modo.

### isCode128Emulation() {#iscode128emulation}

Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en la segunda posición en los modos 908 y 909, también puede codificar 910 y 911 que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128. Estos ejemplos muestran cómo codificar los modos de emulación Code 128 con FNC1 en la segunda posición y sin él. De esta manera, MicroPdf417 puede decodificarse como un código de barras Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

Define modos vinculados con los códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos \"Linked\" UCC/EAN-128 906, 907, 912, 913, 914, 915. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado que no sea un EAN.UCC. Estos ejemplos muestran cómo codificar los modos \"Linked\" UCC/EAN-128 en GS1MicroPdf417 y la Bandera de Enlace (918) en los códigos de barras MicroPdf417 y Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

Se utiliza para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

Relación altura/ancho del módulo de código de barras 2D.

### setCode128Emulation() {#setcode128emulation}

Solo se puede usar con MicroPdf417 y codifica modos de emulación Code 128. Puede codificar FNC1 en la segunda posición en los modos 908 y 909, también puede codificar 910 y 911 que solo indican que el MicroPdf417 reconocido puede interpretarse como Code 128. Estos ejemplos muestran cómo codificar los modos de emulación Code 128 con FNC1 en la segunda posición y sin él. De esta manera, MicroPdf417 puede decodificarse como un código de barras Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

Recuento de columnas.

### setECIEncoding() {#seteciencoding}

Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. No se aplican a los campos de texto Macro PDF417. La implementación actual incluye todas las codificaciones de conjunto de caracteres bien conocidas.

### setEncodeMode() {#setencodemode}

Identifica el modo de codificación Pdf417. Valor predeterminado: Auto.

### setErrorLevel(value) {#seterrorlevel}

Establece el nivel de corrección de errores del tipo de simbología Pdf417 del BarCode, que varía de level0 a level8; level0 significa que no hay información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande.

| Parámetro | Descripción |
| --- | --- |
| valor | Tipo de simbología Pdf417 del nivel de corrección de errores del BarCode, que varía de level0 a level8; level0 significa que no hay información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande. |

### setLinked() {#setlinked}

Define modos vinculados con los códigos de barras GS1MicroPdf417, MicroPdf417 y Pdf417. Con la simbología GS1MicroPdf417 codifica los modos \"Linked\" UCC/EAN-128 906, 907, 912, 913, 914, 915. Con las simbologías MicroPdf417 y Pdf417 codifica la bandera de enlace 918 al componente lineal asociado que no sea un EAN.UCC. Estos ejemplos muestran cómo codificar los modos \"Linked\" UCC/EAN-128 en GS1MicroPdf417 y la Bandera de Enlace (918) en los códigos de barras MicroPdf417 y Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

Los valores de los Caracteres Macro 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales. Sólo pueden usarse con MicroPdf417 y codifican los modos 916 y 917 de MicroPdf417. Valor predeterminado: MacroCharacters.None. Estas muestras muestran cómo codificar Caracteres Macro en MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

Nombre del destinatario del código de barras MacroPdf417 (campo opcional). Nombre del destinatario del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

### setMacroPdf417Checksum() {#setmacropdf417checksum}

Suma de verificación del código de barras MacroPdf417 (campo opcional). Suma de verificación del código de barras MicroPDF417 (campo opcional para el modo Structured Append). El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) usando el polinomio CCITT-16. x^16 + x^12 + x^5 + 1

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417.

### setMacroPdf417FileID() {#setmacropdf417fileid}

ID de archivo del código de barras MacroPdf417 (campo obligatorio). ID de archivo del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

### setMacroPdf417FileName() {#setmacropdf417filename}

Nombre de archivo del código de barras MacroPdf417 (campo opcional). Nombre de archivo del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

### setMacroPdf417FileSize() {#setmacropdf417filesize}

Tamaño de archivo MacroPdf417 (campo opcional). Tamaño de archivo MicroPDF417 (campo opcional para el modo Structured Append). El campo de tamaño de archivo contiene el tamaño en bytes de todo el archivo fuente.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

ID de segmento del código de barras MacroPdf417 (campo obligatorio), que comienza en 0 y llega a MacroSegmentsCount - 1. ID de segmento del código de barras MicroPDF417 (campo obligatorio para el modo Structured Append).

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

Recuento de segmentos del código de barras MacroPdf417 (campo opcional). Recuento de segmentos del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

### setMacroPdf417Sender() {#setmacropdf417sender}

Nombre del remitente del código de barras MacroPdf417 (campo opcional). Nombre del remitente del código de barras MicroPDF417 (campo opcional para el modo Structured Append).

### setMacroPdf417Terminator() {#setmacropdf417terminator}

Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código 922) al segmento. Se aplica solo a Macro PDF417.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

Marca de tiempo del código de barras MacroPdf417 (campo opcional). Marca de tiempo del código de barras MicroPDF417 (campo opcional para el modo Structured Append)

### setPdf417CompactionMode() {#setpdf417compactionmode}

Tipo de simbología Pdf417 del modo de compactación del código de barras. Valor predeterminado: Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Identificadores de Interpretación de Canal Extendido. Se utilizan para indicar al lector de códigos de barras detalles sobre las referencias usadas para codificar los datos en el símbolo. La implementación actual consiste en todas las codificaciones de conjuntos de caracteres bien conocidas.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Identifica el modo de codificación Pdf417. Valor predeterminado: Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Establece el nivel de corrección de errores del tipo de simbología Pdf417 del BarCode, que varía de level0 a level8; level0 significa que no hay información de corrección de errores, level8 significa la mejor corrección de errores, lo que implica una imagen más grande.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Establece el nombre del destinatario del código de barras macro Pdf417.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Establece la suma de verificación del código de barras macro Pdf417.

| Parámetro | Descripción |
| --- | --- |
| valor | El campo de suma de verificación contiene el valor de la suma de verificación CRC de 16 bits (2 bytes) utilizando el polinomio CCITT-16. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Identificadores de Interpretación de Canal Extendido. Se aplican a los campos de texto Macro PDF417.

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Establece el ID de archivo del código de barras macro Pdf417. Se utiliza para MacroPdf417.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Establece el nombre de archivo del código de barras macro Pdf417.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Establece el tamaño de archivo del macro Pdf417.

| Parámetro | Descripción |
| --- | --- |
| valor | El campo de tamaño de archivo contiene el tamaño en bytes de todo el archivo fuente. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Establece el ID de segmento del código de barras macro Pdf417, que comienza en 0 y llega a MacroSegmentsCount - 1.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Establece el recuento de segmentos del código de barras macro Pdf417.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

Establece el nombre del remitente del código de barras macro Pdf417.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Se utiliza para indicar al codificador si debe agregar el Terminador Macro PDF417 (código 922) al segmento. Se aplica solo a Macro PDF417.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Establece la marca de tiempo del código de barras macro Pdf417.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

Indica si el tipo de simbología Pdf417 del código de barras está truncado (para reducir espacio).

### setReaderInitialization(value) {#setreaderinitialization}

Se utiliza para instruir al lector a interpretar los datos contenidos en el símbolo como programación para la inicialización del lector

| Parámetro | Descripción |
| --- | --- |
| valor |  |

### setRows() {#setrows}

Recuento de filas.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Identifica el ID del código de barras DotCode en modo structured append. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1.

### setTruncate() {#settruncate}

Indica si el tipo de simbología Pdf417 del BarCode está truncado (para reducir espacio). También conocido como CompactPDF417. El indicador de fila derecha y el patrón de parada derecha se eliminan en este modo.

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este Pdf417Parameters.

**Returns:** A string that represents this Pdf417Parameters.
