---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "HIBC LIC 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스입니다."
type: docs
weight: 450
url: /ko/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

HIBC LIC 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스입니다. 이 샘플은 원시 HIBC LIC 코텍스트를 HIBCLICComplexCodetext 인스턴스로 디코딩하는 방법을 보여줍니다.

```js
new HIBCLICComplexCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.HIBC_AZTEC_LIC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
   let resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
   print("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
   print("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | 바코드 유형을 가져오거나 설정합니다. HIBC LIC 코텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM을 사용하여 인코딩할 수 있습니다. |
| [getConstructedCodetext()](#getconstructedcodetext) | 코드텍스트를 구성합니다 |
| [initFromString(constructedCodetext)](#initfromstring) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |
| [setBarcodeType()](#setbarcodetype) | 바코드 유형을 가져오거나 설정합니다. HIBC LIC 코텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM을 사용하여 인코딩할 수 있습니다. |

### getBarcodeType() {#getbarcodetype}

바코드 유형을 가져오거나 설정합니다. HIBC LIC 코텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC 및 HIBCQRLIC 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39LIC.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

코드텍스트를 구성합니다

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

구성된 코드텍스트에서 인스턴스를 초기화합니다.

| 매개변수 | 설명 |
| --- | --- |
| constructedCodetext | 구성된 코드텍스트. |

### setBarcodeType() {#setbarcodetype}

바코드 유형을 가져오거나 설정합니다. HIBC LIC 코텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC 및 HIBCQRLIC 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39LIC.

**Returns:** Barcode type.
