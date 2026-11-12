---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Erweiterter Codetext‑Generator für MaxiCode‑Barcodes für den ExtendedCodetext‑Modus von MaxiCodeEncodeMode. Verwenden Sie die Eigenschaft TwoDDisplayText des BarcodeGenerator, um die Sichtbarkeit festzulegen."
type: docs
weight: 630
url: /de/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

Erweiterter Codetext-Generator für MaxiCode-Barcodes für den ExtendedCodetext‑Modus von MaxiCodeEncodeMode. Verwenden Sie die TwoDDisplayText‑Eigenschaft von BarcodeGenerator, um den sichtbaren Text festzulegen und verwaltende Zeichen zu entfernen. Dieses Beispiel zeigt, wie man MaxiCodeExtCodetextBuilder im erweiterten Modus verwendet.

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

| Name | Beschreibung |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Erzeugt erweiterten Codetext aus der erweiterten Codetext‑Liste. |

### getExtendedCodetext() {#getextendedcodetext}

Erzeugt erweiterten Codetext aus der erweiterten Codetext‑Liste.

**Returns:** Extended codetext as string
