---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "모드 2 및 3에 대한 MaxiCode 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스."
type: docs
weight: 700
url: /ko/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

모드 2 및 3에 대한 MaxiCode 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스.

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 이 인스턴스가 지정된 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getConstructedCodetext()](#getconstructedcodetext) | 코드텍스트를 구성합니다 |
| [getCountryCode()](#getcountrycode) | 3자리 국가 코드를 식별합니다. |
| [getHashCode()](#gethashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [getPostalCode()](#getpostalcode) | 우편 번호를 식별합니다. 모드 2에서는 9자리 숫자, 모드 3에서는 6개의 알파벳-숫자 기호여야 합니다. |
| [getSecondMessage()](#getsecondmessage) | 바코드의 두 번째 메시지를 식별합니다. |
| [getServiceCategory()](#getservicecategory) | 3자리 서비스 카테고리를 식별합니다. |
| [initFromString(constructedCodetext)](#initfromstring) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |
| [setCountryCode()](#setcountrycode) | 3자리 국가 코드를 식별합니다. |
| [setPostalCode()](#setpostalcode) | 우편 번호를 식별합니다. 모드 2에서는 9자리 숫자, 모드 3에서는 6개의 알파벳-숫자 기호여야 합니다. |
| [setSecondMessage()](#setsecondmessage) | 바코드의 두 번째 메시지를 식별합니다. |
| [setServiceCategory()](#setservicecategory) | 3자리 서비스 카테고리를 식별합니다. |

### equals(obj) {#equals}

이 인스턴스가 지정된 값과 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 값 |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

코드텍스트를 구성합니다

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

3자리 국가 코드를 식별합니다.

### getHashCode() {#gethashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

우편 번호를 식별합니다. 모드 2에서는 9자리 숫자, 모드 3에서는 6개의 알파벳-숫자 기호여야 합니다.

### getSecondMessage() {#getsecondmessage}

바코드의 두 번째 메시지를 식별합니다.

### getServiceCategory() {#getservicecategory}

3자리 서비스 카테고리를 식별합니다.

### initFromString(constructedCodetext) {#initfromstring}

구성된 코드텍스트에서 인스턴스를 초기화합니다.

| 매개변수 | 설명 |
| --- | --- |
| constructedCodetext | 구성된 코드텍스트. |

### setCountryCode() {#setcountrycode}

3자리 국가 코드를 식별합니다.

### setPostalCode() {#setpostalcode}

우편 번호를 식별합니다. 모드 2에서는 9자리 숫자, 모드 3에서는 6개의 알파벳-숫자 기호여야 합니다.

### setSecondMessage() {#setsecondmessage}

바코드의 두 번째 메시지를 식별합니다.

### setServiceCategory() {#setservicecategory}

3자리 서비스 카테고리를 식별합니다.
