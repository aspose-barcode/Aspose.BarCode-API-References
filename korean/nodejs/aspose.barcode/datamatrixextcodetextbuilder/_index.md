---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "DataMatrixEncodeMode의 ExtendedCodetext 모드용 2D DataMatrix 바코드용 확장 코드텍스트 생성기 //Extended codetext mode //create codetext let textBuil"
type: docs
weight: 340
url: /ko/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

DataMatrixEncodeMode의 ExtendedCodetext 모드용 2D DataMatrix 바코드용 확장 코드텍스트 생성기 //Extended codetext mode //create codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | 정의된 인코드 모드와 함께 코드텍스트를 확장 코드텍스트 항목에 추가합니다. |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | 정의된 인코드 모드와 함께 확장 채널 식별자를 사용하여 코드텍스트를 추가합니다. |
| [getExtendedCodetext()](#getextendedcodetext) | 확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

정의된 인코드 모드와 함께 코드텍스트를 확장 코드텍스트 항목에 추가합니다.

| 매개변수 | 설명 |
| --- | --- |
| encodeMode | 인코드 모드 값 |
| codetext | 확장 코드텍스트 항목으로 추가할 유니코드 코드텍스트 |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

정의된 인코드 모드와 함께 확장 채널 식별자를 사용하여 코드텍스트를 추가합니다.

| 매개변수 | 설명 |
| --- | --- |
| ECIEncoding | 확장 채널 식별자 |
| encodeMode | 인코드 모드 값 |
| codetext | 정의된 인코드 모드와 확장 채널 식별자를 사용하여 추가할 유니코드 코드텍스트 |

### getExtendedCodetext() {#getextendedcodetext}

확장 코드텍스트 목록에서 확장 코드텍스트를 생성합니다.

**Returns:** Extended codetext as string
