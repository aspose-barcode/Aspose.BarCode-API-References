---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Almacena información de metadatos MacroPdf417 del código de barras reconocido"
type: docs
weight: 760
url: /es/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

Almacena información de metadatos MacroPdf417 del código de barras reconocido

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor Pdf417ExtendedParameters especificado. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Nombre del destinatario Macro PDF417 (opcional). |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Checksum Macro PDF417 (opcional). |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | Obtiene el ID de archivo del código de barras, solo disponible con MacroPdf417. Valor: El ID de archivo para MacroPdf417 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Nombre de archivo Macro PDF417 (opcional). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Tamaño de archivo Macro PDF417 (opcional). |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | Obtiene el ID del segmento del código de barras, solo disponible con MacroPdf417. Valor: El ID del segmento del código de barras. |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Obtiene el recuento de segmentos del código de barras macro pdf417. El valor predeterminado es -1. Valor: Recuento de segmentos. |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Nombre del remitente Macro PDF417 (opcional). |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Marca de tiempo Macro PDF417 (opcional). |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [isCode128Emulation()](#iscode128emulation) | Indicador que señala que el código de barras MicroPdf417 está codificado con las palabras de código de emulación Code 128 908, 909, 910 o 911. |
| [isLinked()](#islinked) | Indicador que señala que el código de barras debe estar vinculado a un código de barras 1D. Valor: Indicador de enlace. |
| [isReaderInitialization()](#isreaderinitialization) | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este Pdf417ExtendedParameters. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor Pdf417ExtendedParameters especificado.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor System.Object para comparar con esta instancia. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Nombre del destinatario Macro PDF417 (opcional).

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Checksum Macro PDF417 (opcional).

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

Obtiene el ID de archivo del código de barras, solo disponible con MacroPdf417. Valor: El ID de archivo para MacroPdf417

### getMacroPdf417FileName() {#getmacropdf417filename}

Nombre de archivo Macro PDF417 (opcional).

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Tamaño de archivo Macro PDF417 (opcional).

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

Obtiene el ID del segmento del código de barras, solo disponible con MacroPdf417. Valor: El ID del segmento del código de barras.

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Obtiene el recuento de segmentos del código de barras macro pdf417. El valor predeterminado es -1. Valor: Recuento de segmentos.

### getMacroPdf417Sender() {#getmacropdf417sender}

Nombre del remitente Macro PDF417 (opcional).

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector.

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Marca de tiempo Macro PDF417 (opcional).

**Returns:** Time stamp.

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

Indicador que señala que el código de barras MicroPdf417 está codificado con las palabras de código de emulación Code 128 908, 909, 910 o 911.

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

Indicador que señala que el código de barras debe estar vinculado a un código de barras 1D. Valor: Indicador de enlace.

### isReaderInitialization() {#isreaderinitialization}

Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector.

**Returns:** Reader initialization flag

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este Pdf417ExtendedParameters.

**Returns:** A string that represents this Pdf417ExtendedParameters.
