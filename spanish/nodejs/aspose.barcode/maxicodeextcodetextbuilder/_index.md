---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Generador de codetexto extendido para códigos de barras MaxiCode para el modo ExtendedCodetext de MaxiCodeEncodeMode Use la propiedad TwoDDisplayText de BarcodeGenerator para establecer visibl"
type: docs
weight: 630
url: /es/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

Generador de codetexto extendido para códigos de barras MaxiCode para el modo ExtendedCodetext de MaxiCodeEncodeMode. Use la propiedad TwoDDisplayText de BarcodeGenerator para establecer el texto visible eliminando caracteres de gestión. Este ejemplo muestra cómo usar MaxiCodeExtCodetextBuilder en modo extendido.

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

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | Genera codetext extendido a partir de la lista de codetext extendido. |

### getExtendedCodetext() {#getextendedcodetext}

Genera codetext extendido a partir de la lista de codetext extendido.

**Returns:** Extended codetext as string
