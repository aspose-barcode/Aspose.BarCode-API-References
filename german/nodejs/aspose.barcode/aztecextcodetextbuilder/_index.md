---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Erweiterter Codetext‑Generator für Aztec‑Barcodes im ExtendedCodetext‑Modus von AztecEncodeMode. Verwenden Sie die Eigenschaft TwoDDisplayText von BarcodeGenerator, um den sichtbaren Text festzulegen."
type: docs
weight: 50
url: /de/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Erweiterter Codetext‑Generator für Aztec‑Barcodes im ExtendedCodetext‑Modus von AztecEncodeMode. Verwenden Sie die Eigenschaft TwoDDisplayText von BarcodeGenerator, um den sichtbaren Text zu setzen und verwaltende Zeichen zu entfernen. Dieses Beispiel zeigt, wie man AztecExtCodetextBuilder im Extended‑Modus verwendet.

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

| Name | Beschreibung |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Erzeugt erweiterten Codetext aus der erweiterten Codetext‑Liste. |

### getExtendedCodetext() {#getextendedcodetext}

Erzeugt erweiterten Codetext aus der erweiterten Codetext‑Liste.

**Returns:** Extended codetext as string
