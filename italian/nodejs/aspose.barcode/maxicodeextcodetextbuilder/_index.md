---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Generatore di codetext esteso per i codici a barre MaxiCode per la modalità ExtendedCodetext di MaxiCodeEncodeMode. Usa la proprietà TwoDDisplayText di BarcodeGenerator per impostare visibl"
type: docs
weight: 630
url: /it/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

Generatore di codetext esteso per i codici a barre MaxiCode per la modalità ExtendedCodetext di MaxiCodeEncodeMode. Usa la proprietà TwoDDisplayText di BarcodeGenerator per impostare il testo visibile rimuovendo i caratteri di gestione. Questo esempio mostra come utilizzare MaxiCodeExtCodetextBuilder in modalità Extended.

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Genera il codetext esteso dall'elenco di codetext esteso. |

### getExtendedCodetext() {#getextendedcodetext}

Genera il codetext esteso dall'elenco di codetext esteso.

**Returns:** Extended codetext as string
