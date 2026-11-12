---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Генератор расширенного кода текста для штрихкодов Aztec в режиме ExtendedCodetext режима AztecEncodeMode. Используйте свойство TwoDDisplayText класса BarcodeGenerator для установки видимого текста."
type: docs
weight: 50
url: /ru/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Генератор расширенного кода текста для штрихкодов Aztec в режиме ExtendedCodetext режима AztecEncodeMode. Используйте свойство TwoDDisplayText класса BarcodeGenerator для установки видимого текста с удалением управляющих символов. Этот пример показывает, как использовать AztecExtCodetextBuilder в расширенном режиме.

```js
new AztecExtCodetextBuilder()
```

**Example:**

```js
//create codetext
     let textBuilder = new AztecExtCodetextBuilder();
     textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
     textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
     textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
     textBuilder.addPlainCodetext("Plain text");
     //generate codetext
     let codetext = textBuilder.getExtendedCodetext();
     //generate
     let generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
     generator.getParameters().getBarcode().getCodeTextParameters().setwoDDisplayText("My Text");
     generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## Методы

| Имя | Описание |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Создаёт расширенный код текста из списка расширенных кодов текста. |

### getExtendedCodetext() {#getextendedcodetext}

Создаёт расширенный код текста из списка расширенных кодов текста.

**Returns:** Extended codetext as string
