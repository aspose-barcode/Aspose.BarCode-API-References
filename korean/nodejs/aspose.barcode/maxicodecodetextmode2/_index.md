---
title: "MaxiCodeCodetextMode2"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "모드 2용 MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다."
type: docs
weight: 610
url: /ko/nodejs/aspose.barcode/maxicodecodetextmode2/
---

## MaxiCodeCodetextMode2 class

모드 2용 MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다.

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

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getMode()](#getmode) | MaxiCode 모드를 가져옵니다. |

### getMode() {#getmode}

MaxiCode 모드를 가져옵니다.

**Returns:** MaxiCode mode
