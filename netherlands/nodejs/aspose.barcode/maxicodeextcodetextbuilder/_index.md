---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Uitgebreide codetextgenerator voor MaxiCode-barcodes voor ExtendedCodetext-modus van MaxiCodeEncodeMode. Gebruik de TwoDDisplayText‑eigenschap van BarcodeGenerator om zichtbaar te maken."
type: docs
weight: 630
url: /nl/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

Uitgebreide codetekstgenerator voor MaxiCode-barcodes voor de ExtendedCodetext-modus van MaxiCodeEncodeMode. Gebruik de TwoDDisplayText-eigenschap van BarcodeGenerator om zichtbare tekst in te stellen door beheertekens te verwijderen. Deze voorbeeld toont hoe MaxiCodeExtCodetextBuilder te gebruiken in de uitgebreide modus.

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Genereert uitgebreide codetekst vanuit de uitgebreide codetekst‑lijst. |

### getExtendedCodetext() {#getextendedcodetext}

Genereert uitgebreide codetekst vanuit de uitgebreide codetekst‑lijst.

**Returns:** Extended codetext as string
