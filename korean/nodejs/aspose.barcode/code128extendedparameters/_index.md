---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "인식된 Code128 바코드의 특수 데이터를 저장합니다. 인식된 바코드의 영역 및 바코드 각도를 나타냅니다"
type: docs
weight: 240
url: /ko/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

인식된 Code128 바코드의 특수 데이터를 저장합니다. 인식된 바코드의 영역 및 바코드 각도를 나타냅니다

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 이 인스턴스가 지정된 Code128ExtendedParameters 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getCode128DataPortions()](#getcode128dataportions) | 인식된 Code128 바코드의 Code128DataPortion 배열을 가져옵니다. Code128DataPortion의 값. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [toString()](#tostring) | 이 Code128ExtendedParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### equals(obj) {#equals}

이 인스턴스가 지정된 Code128ExtendedParameters 값과 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 System.Object 값을 제공합니다. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

인식된 Code128 바코드의 Code128DataPortion 배열을 가져옵니다. Code128DataPortion의 값.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

이 Code128ExtendedParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this Code128ExtendedParameters.
