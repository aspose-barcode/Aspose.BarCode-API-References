---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "주 데이터를 저장하는 HIBC LIC 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 클래스입니다."
type: docs
weight: 460
url: /ko/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

주 데이터를 저장하는 HIBC LIC 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 클래스입니다. 이 샘플은 HIBCLICPrimaryCodetext를 사용하여 HIBC LIC를 인코딩하고 디코딩하는 방법을 보여줍니다.

```js
new HIBCLICPrimaryDataCodetext()
```

**Example:**

```js
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 이 인스턴스가 지정된 `HIBCLICPrimaryDataCodetext` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getConstructedCodetext()](#getconstructedcodetext) | 코드텍스트를 구성합니다 |
| [getData()](#getdata) | 주요 데이터를 식별합니다. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [initFromString(constructedCodetext)](#initfromstring) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |
| [setData()](#setdata) | 주요 데이터를 식별합니다. |

### equals(obj) {#equals}

이 인스턴스가 지정된 `HIBCLICPrimaryDataCodetext` 값과 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 `HIBCLICPrimaryDataCodetext` 값. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

코드텍스트를 구성합니다

**Returns:** Constructed codetext

### getData() {#getdata}

주요 데이터를 식별합니다.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

구성된 코드텍스트에서 인스턴스를 초기화합니다.

| 매개변수 | 설명 |
| --- | --- |
| constructedCodetext | 구성된 코드텍스트. |

### setData() {#setdata}

주요 데이터를 식별합니다.
