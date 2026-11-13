---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Utökad kodtextgenerator för Aztec-streckkoder för ExtendedCodetext-läge i AztecEncodeMode. Använd egenskapen TwoDDisplayText i BarcodeGenerator för att ange synlig text."
type: docs
weight: 50
url: /sv/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Utökad kodtextgenerator för Aztec-streckkoder för ExtendedCodetext-läge i AztecEncodeMode. Använd egenskapen TwoDDisplayText i BarcodeGenerator för att ange synlig text och ta bort styrtecken. Detta exempel visar hur man använder AztecExtCodetextBuilder i Extended-läge.

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Genererar utökad kodtext från den utökade kodtextlistan. |

### getExtendedCodetext() {#getextendedcodetext}

Genererar utökad kodtext från den utökade kodtextlistan.

**Returns:** Extended codetext as string
