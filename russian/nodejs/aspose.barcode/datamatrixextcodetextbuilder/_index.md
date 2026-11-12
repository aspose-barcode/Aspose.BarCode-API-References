---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Генератор расширенного текста кода для 2D DataMatrix штрихкодов в режиме ExtendedCodetext режима DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuil"
type: docs
weight: 340
url: /ru/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

Генератор расширенного текста кода для 2D DataMatrix штрихкодов в режиме ExtendedCodetext режима DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## Методы

| Имя | Описание |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | Добавляет текст кода с заданным режимом кодирования к элементам расширенного текста кода |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | Добавляет текст кода с расширенным идентификатором канала и заданным режимом кодирования |
| [getExtendedCodetext()](#getextendedcodetext) | Создаёт расширенный код текста из списка расширенных кодов текста. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

Добавляет текст кода с заданным режимом кодирования к элементам расширенного текста кода

| Параметр | Описание |
| --- | --- |
| encodeMode | Значение режима кодирования |
| codetext | Текст кода в Unicode для добавления как элемент расширенного текста кода |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

Добавляет текст кода с расширенным идентификатором канала и заданным режимом кодирования

| Параметр | Описание |
| --- | --- |
| ECIEncoding | Расширенный идентификатор канала |
| encodeMode | Значение режима кодирования |
| codetext | Текст кода в Unicode для добавления как элемент расширенного текста кода с расширенным идентификатором канала и заданным режимом кодирования |

### getExtendedCodetext() {#getextendedcodetext}

Создаёт расширенный код текста из списка расширенных кодов текста.

**Returns:** Extended codetext as string
