---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 3."
type: docs
weight: 620
url: /ru/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

Класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 3. Этот пример показывает, как кодировать и декодировать текст MaxiCode для режима 3.

```js
new MaxiCodeCodetextMode3()
```

**Example:**

```js
//Mode 3 with standart second message
 let maxiCodeCodetext = new MaxiCodeCodetextMode3();
 maxiCodeCodetext.setPostalCode("B1050");
 maxiCodeCodetext.setCountryCode(056);
 maxiCodeCodetext.setServiceCategory(999);
 let MaxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
 MaxiCodeStandardSecondMessage.setMessage("Test message");
 maxiCodeCodetext.setSecondMessage(MaxiCodeStandardSecondMessage);
 let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
 complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Методы

| Имя | Описание |
| --- | --- |
| [getMode()](#getmode) | Получает режим MaxiCode. |

### getMode() {#getmode}

Получает режим MaxiCode.

**Returns:** MaxiCode mode
