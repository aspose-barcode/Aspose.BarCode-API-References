---
title: "MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2."
type: docs
weight: 610
url: /es/nodejs/aspose.barcode/maxicodecodetextmode2/
---

## MaxiCodeCodetextMode2 class

Clase para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2.

```js
new MaxiCodeCodetextMode2()
```

**Example:**

```js
This sample shows how to encode and decode MaxiCode codetext for mode 2.
 //Mode 2 with standart second message
 let maxiCodeCodetext = new MaxiCodeCodetextMode2();
 maxiCodeCodetext.setPostalCode("524032140");
 maxiCodeCodetext.setCountryCode(056);
 maxiCodeCodetext.setServiceCategory(999);
 let MaxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
 MaxiCodeStandardSecondMessage.setMessage("Test message");
 maxiCodeCodetext.setSecondMessage(MaxiCodeStandardSecondMessage);
 let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
 complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getMode()](#getmode) | Obtiene el modo MaxiCode. |

### getMode() {#getmode}

Obtiene el modo MaxiCode.

**Returns:** MaxiCode mode
