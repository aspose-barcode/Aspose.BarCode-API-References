---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "별도의 코드텍스트 및 체크섬과 같은 1D 인식 바코드의 특수 데이터를 저장합니다"
type: docs
weight: 720
url: /ko/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

별도의 코드텍스트 및 체크섬과 같은 1D 인식 바코드의 특수 데이터를 저장합니다

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 지정된 OneDExtendedParameters 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| [getCheckSum()](#getchecksum) | 1D 바코드의 체크섬을 가져옵니다. 값: 1D 바코드의 체크섬. |
| [getValue()](#getvalue) | 체크섬이 없는 1D 바코드의 코드 텍스트를 가져옵니다. 값: 체크섬이 없는 1D 바코드의 코드 텍스트. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isEmpty()](#isempty) | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. 값: 모든 매개변수가 기본값만 가지고 있으면 `true`를 반환합니다; o |
| [toString()](#tostring) | 이 OneDExtendedParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### equals(obj) {#equals}

지정된 OneDExtendedParameters 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 System.Object 값을 제공합니다. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

1D 바코드의 체크섬을 가져옵니다. 값: 1D 바코드의 체크섬.

### getValue() {#getvalue}

체크섬이 없는 1D 바코드의 코드 텍스트를 가져옵니다. 값: 체크섬이 없는 1D 바코드의 코드 텍스트.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

모든 매개변수가 기본값만 가지고 있는지 테스트합니다. 값: 모든 매개변수가 기본값만 가지고 있으면 `true`를 반환하고, 그렇지 않으면 `false`를 반환합니다.

### toString() {#tostring}

이 OneDExtendedParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this OneDExtendedParameters.
