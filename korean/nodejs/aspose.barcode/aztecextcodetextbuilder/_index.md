---
title: "AztecExtCodetextBuilder"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "Aztec 바코드의 ExtendedCodetext 모드(AztecEncodeMode)를 위한 확장 코드텍스트 생성기. 가시 텍스트를 설정하려면 BarcodeGenerator의 TwoDDisplayText 속성을 사용합니다."
type: docs
weight: 50
url: /ko/nodejs/aspose.barcode/aztecextcodetextbuilder/
---

## AztecExtCodetextBuilder class

Aztec 바코드의 ExtendedCodetext 모드(AztecEncodeMode)를 위한 확장 코드텍스트 생성기. 가시 텍스트를 설정하고 관리 문자를 제거하려면 BarcodeGenerator의 TwoDDisplayText 속성을 사용합니다. 이 샘플은 Extended 모드에서 AztecExtCodetextBuilder를 사용하는 방법을 보여줍니다.

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

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getExtendedCodetext()](#getextendedcodetext) | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |

### getExtendedCodetext() {#getextendedcodetext}

확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다.

**Returns:** Extended codetext as string
