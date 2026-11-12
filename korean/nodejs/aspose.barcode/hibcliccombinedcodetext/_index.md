---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "주요 및 보조 데이터를 저장하는 HIBC LIC 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 클래스."
type: docs
weight: 440
url: /ko/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

주요 및 보조 데이터를 저장하는 HIBC LIC 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 클래스입니다. 이 샘플은 HIBCLICCombinedCodetext를 사용하여 HIBC LIC를 인코딩하고 디코딩하는 방법을 보여줍니다.

```js
new HIBCLICCombinedCodetext()
```

**Example:**

```js
let combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
combinedCodetext.setPrimaryData(new PrimaryData());
combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
print("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
print("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
print("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
print("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
print("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 이 인스턴스가 지정된 `HIBCLICCombinedCodetext` 값과 동일한지 여부를 나타내는 값을 반환합니다. |
| [getConstructedCodetext()](#getconstructedcodetext) | 코드텍스트를 구성합니다 |
| [getPrimaryData()](#getprimarydata) | 주요 데이터를 식별합니다. |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | 보조 및 추가 보충 데이터를 식별합니다. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [initFromString(constructedCodetext)](#initfromstring) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |
| [setPrimaryData()](#setprimarydata) | 주요 데이터를 식별합니다. |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | 보조 및 추가 보충 데이터를 식별합니다. |

### equals(obj) {#equals}

이 인스턴스가 지정된 `HIBCLICCombinedCodetext` 값과 동일한지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 `HIBCLICCombinedCodetext` 값입니다. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

코드텍스트를 구성합니다

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

주요 데이터를 식별합니다.

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

보조 및 추가 보충 데이터를 식별합니다.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

구성된 코드텍스트에서 인스턴스를 초기화합니다.

| 매개변수 | 설명 |
| --- | --- |
| constructedCodetext | 구성된 코드텍스트. |

### setPrimaryData() {#setprimarydata}

주요 데이터를 식별합니다.

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

보조 및 추가 보충 데이터를 식별합니다.
