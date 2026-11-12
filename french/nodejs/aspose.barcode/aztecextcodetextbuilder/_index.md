---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Générateur de codetext étendu pour les codes-barres Aztec en mode ExtendedCodetext de AztecEncodeMode. Utilisez la propriété TwoDDisplayText de BarcodeGenerator pour définir le texte visible."
type: docs
weight: 50
url: /fr/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Générateur de codetext étendu pour les codes-barres Aztec en mode ExtendedCodetext de AztecEncodeMode. Utilisez la propriété TwoDDisplayText de BarcodeGenerator pour définir le texte visible en supprimant les caractères de gestion. Cet exemple montre comment utiliser AztecExtCodetextBuilder en mode étendu.

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

## Méthodes

| Nom | Description |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Génère le codetext étendu à partir de la liste de codetext étendu. |

### getExtendedCodetext() {#getextendedcodetext}

Génère le codetext étendu à partir de la liste de codetext étendu.

**Returns:** Extended codetext as string
