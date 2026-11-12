---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Generador de codetext extendido para códigos de barras Aztec en modo ExtendedCodetext de AztecEncodeMode. Use la propiedad TwoDDisplayText de BarcodeGenerator para establecer el texto visible."
type: docs
weight: 50
url: /es/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Generador de codetext extendido para códigos de barras Aztec en modo ExtendedCodetext de AztecEncodeMode. Use la propiedad TwoDDisplayText de BarcodeGenerator para establecer el texto visible eliminando caracteres de gestión. Este ejemplo muestra cómo usar AztecExtCodetextBuilder en modo Extended.

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

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Genera codetext extendido a partir de la lista de codetext extendido. |

### getExtendedCodetext() {#getextendedcodetext}

Genera codetext extendido a partir de la lista de codetext extendido.

**Returns:** Extended codetext as string
