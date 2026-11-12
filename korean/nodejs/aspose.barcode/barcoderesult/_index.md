---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "SingleDecodeType 유형, `string` codetext, BarCodeRegionParameters 영역 및 기타 매개변수와 같은 인식된 바코드 데이터를 저장합니다."
type: docs
weight: 110
url: /ko/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

SingleDecodeType 유형, `string` codetext, BarCodeRegionParameters 영역 및 기타 매개변수와 같은 인식된 바코드 데이터를 저장합니다.

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [deepClone()](#deepclone) | BarCodeResult 클래스의 복사본을 생성합니다. |
| [equals(other)](#equals) | 이 인스턴스가 지정된 BarCodeResult 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getCodeBytes()](#getcodebytes) | 인코딩된 코드 바이트를 가져옵니다 값: 바코드의 코드 바이트 |
| [getCodeText(encoding)](#getcodetext) | 인코딩된 코드 텍스트를 가져옵니다. 이 예제는 `getCodeText` 사용 방법을 보여줍니다: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | 바코드 유형을 가져옵니다 값: 인식된 바코드의 유형 정보 |
| [getCodeTypeName()](#getcodetypename) | 바코드 유형의 이름을 가져옵니다 값: 인식된 바코드의 유형 이름 |
| [getConfidence()](#getconfidence) | 인식된 바코드의 인식 신뢰도 수준을 가져옵니다 값: BarCodeConfidence.Strong은 위조나 오인식이 없습니다. |
| [getExtended()](#getextended) | 인식된 바코드의 확장 매개변수를 가져옵니다 값: 인식된 바코드의 확장 매개변수 |
| [getReadingQuality()](#getreadingquality) | 읽기 품질을 가져옵니다. 1D 및 우편 바코드에 적용됩니다. 값: 읽기 품질 백분율 |
| [getRegion()](#getregion) | 바코드 영역을 가져옵니다 값: 인식된 바코드의 영역 |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [toString()](#tostring) | 이 BarCodeResult의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### deepClone() {#deepclone}

BarCodeResult 클래스의 복사본을 생성합니다.

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

이 인스턴스가 지정된 BarCodeResult 값과 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| 기타 | 이 인스턴스와 비교할 BarCodeResult 값. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

인코딩된 코드 바이트를 가져옵니다 값: 바코드의 코드 바이트

### getCodeText(encoding) {#getcodetext}

인코딩된 코드 텍스트를 가져옵니다. 이 예제는 `getCodeText` 사용 방법을 보여줍니다: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| 매개변수 | 설명 |
| --- | --- |
| 인코딩 | codetext에 대한 인코딩. |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

바코드 유형을 가져옵니다 값: 인식된 바코드의 유형 정보

### getCodeTypeName() {#getcodetypename}

바코드 유형의 이름을 가져옵니다 값: 인식된 바코드의 유형 이름

### getConfidence() {#getconfidence}

인식된 바코드의 인식 신뢰도 수준을 가져옵니다 값: BarCodeConfidence.Strong은 위조나 오인식이 없으며, BarCodeConfidence.Moderate는 약한 체크섬 또는 체크섬이 없는 바코드의 경우 가끔 위조나 잘못된 codetext가 있을 수 있고, BarCodeConfidence.NONE는 항상 잘못된 codetext를 가지고 가짜 인식일 수 있습니다.

### getExtended() {#getextended}

인식된 바코드의 확장 매개변수를 가져옵니다 값: 인식된 바코드의 확장 매개변수

### getReadingQuality() {#getreadingquality}

읽기 품질을 가져옵니다. 1D 및 우편 바코드에 적용됩니다. 값: 읽기 품질 백분율

### getRegion() {#getregion}

바코드 영역을 가져옵니다 값: 인식된 바코드의 영역

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

이 BarCodeResult의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this BarCodeResult.
