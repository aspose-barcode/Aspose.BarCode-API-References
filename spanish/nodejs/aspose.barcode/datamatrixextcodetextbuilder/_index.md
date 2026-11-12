---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Generador de codetext extendido para códigos de barras DataMatrix 2D para el modo ExtendedCodetext de DataMatrixEncodeMode //Modo de codetext extendido //crear codetext let textBuil"
type: docs
weight: 340
url: /es/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

Generador de codetext extendido para códigos de barras DataMatrix 2D para el modo ExtendedCodetext de DataMatrixEncodeMode //Modo de codetext extendido //crear codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | Agrega codetext con modo de codificación definido a los elementos de codetext extendido |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | Agrega codetext con Identificador de Canal Extendido con modo de codificación definido |
| [getExtendedCodetext()](#getextendedcodetext) | Genera codetext extendido a partir de la lista de codetext extendido. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

Agrega codetext con modo de codificación definido a los elementos de codetext extendido

| Parámetro | Descripción |
| --- | --- |
| encodeMode | Valor del modo de codificación |
| codetext | Codetext en Unicode para agregar como elemento de codetext extendido |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

Agrega codetext con Identificador de Canal Extendido con modo de codificación definido

| Parámetro | Descripción |
| --- | --- |
| ECIEncoding | Identificador de Canal Extendido |
| encodeMode | Valor del modo de codificación |
| codetext | Codetext en Unicode para agregar como elemento de codetext extendido con Identificador de Canal Extendido con modo de codificación definido |

### getExtendedCodetext() {#getextendedcodetext}

Genera codetext extendido a partir de la lista de codetext extendido.

**Returns:** Extended codetext as string
