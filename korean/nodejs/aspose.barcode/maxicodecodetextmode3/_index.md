---
title: "MaxiCodeCodetextMode3"
linktitle: "MaxiCodeCodetextMode3"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "모드 3용 MaxiCode 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 클래스."
type: docs
weight: 620
url: /ko/nodejs/aspose.barcode/maxicodecodetextmode3/
---

## MaxiCodeCodetextMode3 class

모드 3에 대한 MaxiCode 코드에 포함된 텍스트를 인코딩하고 디코딩하기 위한 클래스입니다. 이 샘플은 모드 3에 대한 MaxiCode 코드텍스트를 인코딩하고 디코딩하는 방법을 보여줍니다.

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

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getMode()](#getmode) | MaxiCode 모드를 가져옵니다. |

### getMode() {#getmode}

MaxiCode 모드를 가져옵니다.

**Returns:** MaxiCode mode
