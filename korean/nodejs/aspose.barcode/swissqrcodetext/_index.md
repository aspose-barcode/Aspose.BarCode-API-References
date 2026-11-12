---
title: "SwissQRCodetext"
linktitle: "SwissQRCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "SwissQR 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스."
type: docs
weight: 930
url: /ko/nodejs/aspose.barcode/swissqrcodetext/
---

## SwissQRCodetext class

SwissQR 코드에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스.

```js
new SwissQRCodetext(bill)
```

SwissQRCodetext의 인스턴스를 생성합니다.

| 매개변수 | 설명 |
| --- | --- |
| bill | SwissQR 청구서 데이터 |

**Throws:** BarcodeException

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | 바코드 유형을 가져옵니다. |
| [getBill()](#getbill) | SwissQR 청구서 데이터 |
| [getConstructedCodetext()](#getconstructedcodetext) | SwissQR bill 데이터에서 codetext를 구성합니다. |
| [initFromString(constructedCodetext)](#initfromstring) | 구성된 codetext로 Bill을 초기화합니다. |

### getBarcodeType() {#getbarcodetype}

바코드 유형을 가져옵니다.

**Returns:** Barcode type.

### getBill() {#getbill}

SwissQR 청구서 데이터

### getConstructedCodetext() {#getconstructedcodetext}

SwissQR bill 데이터에서 codetext를 구성합니다.

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

구성된 codetext로 Bill을 초기화합니다.

| 매개변수 | 설명 |
| --- | --- |
| constructedCodetext | 구성된 코드텍스트. |
