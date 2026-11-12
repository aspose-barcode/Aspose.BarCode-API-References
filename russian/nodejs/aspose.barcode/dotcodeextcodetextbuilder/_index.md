---
title: "DotCodeExtCodetextBuilder"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Генератор расширенного codetext для 2D штрих‑кодов DotCode в режиме ExtendedCodetext режима DotCodeEncodeMode"
type: docs
weight: 370
url: /ru/nodejs/aspose.barcode/dotcodeextcodetextbuilder/
---

## DotCodeExtCodetextBuilder class

Генератор расширенного codetext для 2D штрих‑кодов DotCode в режиме ExtendedCodetext режима DotCodeEncodeMode

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

## Методы

| Имя | Описание |
| --- | --- |
| [addFNC1FormatIdentifier()](#addfnc1formatidentifier) | Добавляет идентификатор формата FNC1 к элементам расширенного codetext. |
| [addFNC3ReaderInitialization()](#addfnc3readerinitialization) | Добавляет инициализацию считывателя FNC3 к элементам расширенного codetext. |
| [addFNC3SymbolSeparator()](#addfnc3symbolseparator) | Добавляет разделитель символов FNC3 к элементам расширенного codetext. |
| [addStructuredAppendMode(barcodeId, barcodesCount)](#addstructuredappendmode) | Добавляет режим структурного добавления к элементам расширенного codetext. |
| [getExtendedCodetext()](#getextendedcodetext) | Создаёт расширенный код текста из списка расширенных кодов текста. |

### addFNC1FormatIdentifier() {#addfnc1formatidentifier}

Добавляет идентификатор формата FNC1 к элементам расширенного codetext.

### addFNC3ReaderInitialization() {#addfnc3readerinitialization}

Добавляет инициализацию считывателя FNC3 к элементам расширенного codetext.

### addFNC3SymbolSeparator() {#addfnc3symbolseparator}

Добавляет разделитель символов FNC3 к элементам расширенного codetext.

### addStructuredAppendMode(barcodeId, barcodesCount) {#addstructuredappendmode}

Добавляет режим структурного добавления к элементам расширенного codetext.

| Параметр | Описание |
| --- | --- |
| barcodeId | Идентификатор штрихкода. |
| barcodesCount | Количество штрихкодов |

### getExtendedCodetext() {#getextendedcodetext}

Создаёт расширенный код текста из списка расширенных кодов текста.

**Returns:** Extended codetext as string
