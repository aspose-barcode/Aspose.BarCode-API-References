---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Генератор расширенного текста кода для штрихкодов MaxiCode в режиме ExtendedCodetext параметра MaxiCodeEncodeMode. Используйте свойство TwoDDisplayText класса BarcodeGenerator для установки видимости."
type: docs
weight: 630
url: /ru/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

Расширенный генератор кодового текста для штрихкодов MaxiCode в режиме ExtendedCodetext режима MaxiCodeEncodeMode. Используйте свойство TwoDDisplayText класса BarcodeGenerator, чтобы установить видимый текст, удаляя управляющие символы. Этот пример показывает, как использовать MaxiCodeExtCodetextBuilder в расширенном режиме.

```js
new MaxiCodeExtCodetextBuilder()
```

**Example:**

```js
//create codetext
let textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");

//generate codetext
let codetext = textBuilder.getExtendedCodetext();

//generate
let generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

## Методы

| Имя | Описание |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Создаёт расширенный код текста из списка расширенных кодов текста. |

### getExtendedCodetext() {#getextendedcodetext}

Создаёт расширенный код текста из списка расширенных кодов текста.

**Returns:** Extended codetext as string
