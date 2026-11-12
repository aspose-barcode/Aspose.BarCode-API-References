---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Générateur de texte de code étendu pour les codes-barres MaxiCode pour le mode ExtendedCodetext de MaxiCodeEncodeMode. Utilisez la propriété TwoDDisplayText de BarcodeGenerator pour définir visibl"
type: docs
weight: 630
url: /fr/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

Générateur de codetext étendu pour les codes-barres MaxiCode en mode ExtendedCodetext de MaxiCodeEncodeMode. Utilisez la propriété TwoDDisplayText de BarcodeGenerator pour définir le texte visible en supprimant les caractères de gestion. Cet exemple montre comment utiliser MaxiCodeExtCodetextBuilder en mode étendu.

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

## Méthodes

| Nom | Description |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Génère le codetext étendu à partir de la liste de codetext étendu. |

### getExtendedCodetext() {#getextendedcodetext}

Génère le codetext étendu à partir de la liste de codetext étendu.

**Returns:** Extended codetext as string
