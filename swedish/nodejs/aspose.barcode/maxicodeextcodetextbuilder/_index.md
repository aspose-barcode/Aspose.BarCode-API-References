---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Utökad kodtextgenerator för MaxiCode-streckkoder för ExtendedCodetext-läge i MaxiCodeEncodeMode Använd TwoDDisplayText-egenskapen i BarcodeGenerator för att ställa in visibl"
type: docs
weight: 630
url: /sv/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

Utökad kodtextgenerator för MaxiCode-streckkoder för ExtendedCodetext-läge i MaxiCodeEncodeMode Använd TwoDDisplayText-egenskapen i BarcodeGenerator för att ställa in synlig text genom att ta bort hanterande tecken. Detta exempel visar hur man använder MaxiCodeExtCodetextBuilder i Extended-läge.

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Genererar utökad kodtext från den utökade kodtextlistan. |

### getExtendedCodetext() {#getextendedcodetext}

Genererar utökad kodtext från den utökade kodtextlistan.

**Returns:** Extended codetext as string
