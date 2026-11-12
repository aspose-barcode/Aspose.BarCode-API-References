---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Generatore di codetext esteso per codici a barre DataMatrix 2D per la modalità ExtendedCodetext di DataMatrixEncodeMode //modalità codetext esteso //crea codetext let textBuil"
type: docs
weight: 340
url: /it/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

Generatore di codetext esteso per codici a barre DataMatrix 2D per la modalità ExtendedCodetext di DataMatrixEncodeMode //modalità codetext esteso //crea codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //genera codetext let codetext = textBuilder.getExtendedCodetext(); //genera let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | Aggiunge codetext con modalità di codifica definita agli elementi di codetext esteso |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | Aggiunge codetext con Identificatore di Canale Esteso con modalità di codifica definita |
| [getExtendedCodetext()](#getextendedcodetext) | Genera il codetext esteso dall'elenco di codetext esteso. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

Aggiunge codetext con modalità di codifica definita agli elementi di codetext esteso

| Parametro | Descrizione |
| --- | --- |
| encodeMode | Valore della modalità di codifica |
| codetext | Codetext in Unicode da aggiungere come elemento di codetext esteso |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

Aggiunge codetext con Identificatore di Canale Esteso con modalità di codifica definita

| Parametro | Descrizione |
| --- | --- |
| ECIEncoding | Identificatore di Canale Esteso |
| encodeMode | Valore della modalità di codifica |
| codetext | Codetext in Unicode da aggiungere come elemento di codetext esteso con Identificatore di Canale Esteso con modalità di codifica definita |

### getExtendedCodetext() {#getextendedcodetext}

Genera il codetext esteso dall'elenco di codetext esteso.

**Returns:** Extended codetext as string
