---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Generatore di codetext esteso per codici a barre Aztec in modalità ExtendedCodetext di AztecEncodeMode. Usa la proprietà TwoDDisplayText di BarcodeGenerator per impostare il testo visibile."
type: docs
weight: 50
url: /it/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Generatore di codetext esteso per codici a barre Aztec in modalità ExtendedCodetext di AztecEncodeMode. Usa la proprietà TwoDDisplayText di BarcodeGenerator per impostare il testo visibile rimuovendo i caratteri di gestione. Questo esempio mostra come utilizzare AztecExtCodetextBuilder in modalità Extended.

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Genera il codetext esteso dall'elenco di codetext esteso. |

### getExtendedCodetext() {#getextendedcodetext}

Genera il codetext esteso dall'elenco di codetext esteso.

**Returns:** Extended codetext as string
