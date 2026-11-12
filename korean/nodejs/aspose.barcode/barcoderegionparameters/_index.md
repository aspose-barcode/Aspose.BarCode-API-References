---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "인식된 바코드의 영역 및 바코드 각도를 나타냅니다"
type: docs
weight: 100
url: /ko/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

인식된 바코드의 영역 및 바코드 각도를 나타냅니다

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 이 인스턴스가 지정된 BarCodeRegionParameters 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getAngle()](#getangle) | 바코드의 각도(0-360)를 가져옵니다. 값: 바코드의 각도(0-360). |
| [getPoints()](#getpoints) | 바코드 영역을 둘러싼 Points 배열을 가져옵니다 값: 바코드 영역을 둘러싼 Points 배열을 반환합니다 |
| [getQuadrangle()](#getquadrangle) | 바코드 영역을 둘러싼 Quadrangle을 가져옵니다 값: 바코드 영역을 둘러싼 Quadrangle을 반환합니다 |
| [getRectangle()](#getrectangle) | 바코드 영역을 둘러싼 Rectangle을 가져옵니다 값: 바코드 영역을 둘러싼 Rectangle을 반환합니다 |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [toString()](#tostring) | 이 BarCodeRegionParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### equals(obj) {#equals}

이 인스턴스가 지정된 BarCodeRegionParameters 값과 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 System.Object 값을 제공합니다. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

바코드의 각도(0-360)를 가져옵니다. 값: 바코드의 각도(0-360).

### getPoints() {#getpoints}

바코드 영역을 둘러싼 Points 배열을 가져옵니다 값: 바코드 영역을 둘러싼 Points 배열을 반환합니다

### getQuadrangle() {#getquadrangle}

바코드 영역을 둘러싼 Quadrangle을 가져옵니다 값: 바코드 영역을 둘러싼 Quadrangle을 반환합니다

### getRectangle() {#getrectangle}

바코드 영역을 둘러싼 Rectangle을 가져옵니다 값: 바코드 영역을 둘러싼 Rectangle을 반환합니다

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

이 BarCodeRegionParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this BarCodeRegionParameters.
