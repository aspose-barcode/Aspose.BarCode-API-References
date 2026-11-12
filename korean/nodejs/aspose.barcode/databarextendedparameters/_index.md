---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "인식된 바코드의 DataBar 추가 정보를 저장합니다"
type: docs
weight: 310
url: /ko/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

인식된 바코드의 DataBar 추가 정보를 저장합니다

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 이 인스턴스가 지정된 DataBarExtendedParameters 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [is2DCompositeComponent()](#is2dcompositecomponent) | DataBar 2D 복합 구성 요소 플래그를 가져옵니다. 기본값은 false입니다. |
| [toString()](#tostring) | 이 객체의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### equals(obj) {#equals}

이 인스턴스가 지정된 DataBarExtendedParameters 값과 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 DataBarExtendedParameters 값. |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

DataBar 2D 복합 구성 요소 플래그를 가져옵니다. 기본값은 false입니다.

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

이 객체의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this .
