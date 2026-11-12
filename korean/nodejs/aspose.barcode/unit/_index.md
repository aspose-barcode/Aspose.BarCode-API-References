---
title: "Unit"
linktitle: "Unit"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "다양한 단위(Pixel, Inches 등)로 크기 값을 지정합니다."
type: docs
weight: 960
url: /ko/nodejs/aspose.barcode/unit/
---

## Unit class

다양한 단위(Pixel, Inches 등)로 크기 값을 지정합니다.

```js
new Unit()
```

**Example:**

```js
//This sample shows how to create and save a BarCode image.
   let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
   generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
   generator.save("test.png", BarcodeImageFormat.PNG);
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 이 인스턴스와 지정된 객체(또한 Unit 객체여야 함)가 동일한 값을 갖는지 여부를 결정합니다. |
| [getDocument()](#getdocument) | 문서 단위로 크기 값을 가져옵니다. |
| [getInches()](#getinches) | 인치 단위로 크기 값을 가져옵니다. |
| [getMillimeters()](#getmillimeters) | 밀리미터 단위로 크기 값을 가져옵니다. |
| [getPixels()](#getpixels) | 픽셀 단위로 크기 값을 가져옵니다. |
| [getPoint()](#getpoint) | 포인트 단위로 크기 값을 가져옵니다. |
| [setDocument()](#setdocument) | 문서 단위로 크기 값을 설정합니다. |
| [setInches()](#setinches) | 인치 단위로 크기 값을 설정합니다. |
| [setMillimeters()](#setmillimeters) | 밀리미터 단위로 크기 값을 설정합니다. |
| [setPixels()](#setpixels) | 픽셀 단위로 크기 값을 설정합니다. |
| [setPoint()](#setpoint) | 포인트 단위로 크기 값을 설정합니다. |
| [toString()](#tostring) | 이 Unit의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### equals(obj) {#equals}

이 인스턴스와 지정된 객체(또한 Unit 객체여야 함)가 동일한 값을 갖는지 여부를 결정합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 Unit. |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

문서 단위로 크기 값을 가져옵니다.

### getInches() {#getinches}

인치 단위로 크기 값을 가져옵니다.

### getMillimeters() {#getmillimeters}

밀리미터 단위로 크기 값을 가져옵니다.

### getPixels() {#getpixels}

픽셀 단위로 크기 값을 가져옵니다.

### getPoint() {#getpoint}

포인트 단위로 크기 값을 가져옵니다.

### setDocument() {#setdocument}

문서 단위로 크기 값을 설정합니다.

### setInches() {#setinches}

인치 단위로 크기 값을 설정합니다.

### setMillimeters() {#setmillimeters}

밀리미터 단위로 크기 값을 설정합니다.

### setPixels() {#setpixels}

픽셀 단위로 크기 값을 설정합니다.

### setPoint() {#setpoint}

포인트 단위로 크기 값을 설정합니다.

### toString() {#tostring}

이 Unit의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this Unit.
