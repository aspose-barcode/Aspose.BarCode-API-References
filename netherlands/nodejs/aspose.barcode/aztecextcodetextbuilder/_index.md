---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Uitgebreide codetekstgenerator voor Aztec‑barcodes voor de ExtendedCodetext‑modus van AztecEncodeMode. Gebruik de TwoDDisplayText‑eigenschap van BarcodeGenerator om de zichtbare tekst in te stellen."
type: docs
weight: 50
url: /nl/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Uitgebreide codetekstgenerator voor Aztec‑barcodes voor de ExtendedCodetext‑modus van AztecEncodeMode. Gebruik de TwoDDisplayText‑eigenschap van BarcodeGenerator om de zichtbare tekst in te stellen en beheer‑tekens te verwijderen. Deze voorbeeld toont hoe AztecExtCodetextBuilder te gebruiken in de Extended‑modus.

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Genereert uitgebreide codetekst vanuit de uitgebreide codetekst‑lijst. |

### getExtendedCodetext() {#getextendedcodetext}

Genereert uitgebreide codetekst vanuit de uitgebreide codetekst‑lijst.

**Returns:** Extended codetext as string
