---
title: "MaxiCodeExtCodetextBuilder"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "MaxiCode 바코드용 확장 코드텍스트 생성기(ExtendedCodetext Mode의 MaxiCodeEncodeMode). BarcodeGenerator의 TwoDDisplayText 속성을 사용하여 표시되는 텍스트를 설정합니다."
type: docs
weight: 630
url: /ko/nodejs/aspose.barcode/maxicodeextcodetextbuilder/
---

## MaxiCodeExtCodetextBuilder class

MaxiCode 바코드용 확장 코드텍스트 생성기(ExtendedCodetext Mode의 MaxiCodeEncodeMode). BarcodeGenerator의 TwoDDisplayText 속성을 사용하여 관리 문자를 제거한 표시 텍스트를 설정합니다. 이 샘플은 Extended Mode에서 MaxiCodeExtCodetextBuilder를 사용하는 방법을 보여줍니다.

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

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |

### getExtendedCodetext() {#getextendedcodetext}

확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다.

**Returns:** Extended codetext as string
