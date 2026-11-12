---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Generador de codetext extendido para códigos de barras 2D DotCode para el modo ExtendedCodetext de DotCodeEncodeMode"
type: docs
weight: 370
url: /es/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

Generador de codetext extendido para códigos de barras 2D DotCode para el modo ExtendedCodetext de DotCodeEncodeMode

```js
new DotCodeExtCodetextBuilder()
```

**Example:**

```js
//Extended codetext mode
//create codetext
let textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");
textBuilder.addFNC3SymbolSeparator();
textBuilder.addFNC3ReaderInitialization();
textBuilder.addPlainCodetext("Reader initialization info");
//generate codetext
let codetext = textBuilder.getExtendedCodetext();
//generate
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
generator.save("test.bmp", BarCodeImageFormat.BMP);
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | Agrega el identificador de formato FNC1 a los elementos de codetext extendidos |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | Agrega la inicialización del lector FNC3 a los elementos de codetext extendidos |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | Agrega el separador de símbolo FNC3 a los elementos de codetext extendidos |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | Agrega el modo de anexado estructurado a los elementos de codetext extendidos |
| [getExtendedCodetext()](#getextendedcodetext) | Genera codetext extendido a partir de la lista de codetext extendido. |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

Agrega el identificador de formato FNC1 a los elementos de codetext extendidos

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

Agrega la inicialización del lector FNC3 a los elementos de codetext extendidos

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

Agrega el separador de símbolo FNC3 a los elementos de codetext extendidos

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

Agrega el modo de anexado estructurado a los elementos de codetext extendidos

| Parámetro | Descripción |
| --- | --- |
| barcodeId | ID del código de barras |
| barcodesCount | Recuento de códigos de barras |

### getExtendedCodetext() {#getextendedcodetext}

Genera codetext extendido a partir de la lista de codetext extendido.

**Returns:** Extended codetext as string
