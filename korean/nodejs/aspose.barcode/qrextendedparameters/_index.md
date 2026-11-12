---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "인식된 바코드의 QR Structured Append 정보를 저장합니다"
type: docs
weight: 810
url: /ko/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

인식된 바코드의 QR Structured Append 정보를 저장합니다

```js
new QRExtendedParameters()
```

**Example:**

```js
//This sample shows how to get QR Structured Append data

let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
   console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
   console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 이 인스턴스가 지정된 QRExtendedParameters 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getErrorLevel()](#geterrorlevel) | 인식된 바코드의 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | 인식된 MicroQR 코드의 버전. M1부터 M4까지. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | 인식된 바코드의 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | QR 구조 추가 모드 바코드의 인덱스를 가져옵니다. 인덱스는 0부터 시작합니다. 기본값은 -1입니다. 값: 수량 |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | QR 구조 추가 모드 바코드 수량을 가져옵니다. 기본값은 -1입니다. 값: QR 구조 추가 모드의 수량 |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | QR 구조 추가 모드 패리티 데이터를 가져옵니다. 기본값은 -1입니다. 값: QR 구조 추가 모드의 인덱스 |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | 인식된 QR 코드의 버전. Version1부터 Version40까지. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | 인식된 RectMicroQR 코드의 버전. R7x43부터 R17x139까지. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | QR 구조 추가 모드 바코드의 인덱스를 가져옵니다. 인덱스는 0부터 시작합니다. 기본값은 -1입니다. 값: 수량 |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | QR 구조 추가 모드 바코드 수량을 가져옵니다. 기본값은 -1입니다. 값: QR 구조 추가 모드의 수량 |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | QR 구조 추가 모드 패리티 데이터를 가져옵니다. 기본값은 -1입니다. 값: QR 구조 추가 모드의 인덱스 |
| [getVersion()](#getversion) | 인식된 QR 코드의 버전. Version1부터 Version40까지. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isEmpty()](#isempty) | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. 값 |
| [toString()](#tostring) | QRExtendedParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### equals(obj) {#equals}

이 인스턴스가 지정된 QRExtendedParameters 값과 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 객체 값. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

인식된 바코드의 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH.

### getMicroQRVersion() {#getmicroqrversion}

인식된 MicroQR 코드의 버전. M1부터 M4까지.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

인식된 바코드의 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

QR 구조 추가 모드 바코드의 인덱스를 가져옵니다. 인덱스는 0부터 시작합니다. 기본값은 -1입니다. 값: QR 구조 추가 모드 바코드의 수량.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

QR 구조 추가 모드 바코드 수량을 가져옵니다. 기본값은 -1입니다. 값: QR 구조 추가 모드 바코드의 수량.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

QR 구조 추가 모드 패리티 데이터를 가져옵니다. 기본값은 -1입니다. 값: QR 구조 추가 모드 바코드의 인덱스.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

인식된 QR 코드의 버전. Version1부터 Version40까지.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

인식된 RectMicroQR 코드의 버전. R7x43부터 R17x139까지.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

QR 구조적 추가 모드 바코드의 인덱스를 가져옵니다. 인덱스는 0부터 시작합니다. 기본값은 -1입니다. 값: QR 구조적 추가 모드 바코드의 수량.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

QR 구조적 추가 모드 바코드 수량을 가져옵니다. 기본값은 -1입니다. 값: QR 구조적 추가 모드 바코드의 수량.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

QR 구조적 추가 모드 패리티 데이터를 가져옵니다. 기본값은 -1입니다. 값: QR 구조적 추가 모드 바코드의 인덱스.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

인식된 QR 코드의 버전. Version1부터 Version40까지.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

모든 매개변수가 기본값만 가지고 있는지 테스트합니다. 값

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

QRExtendedParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this QRExtendedParameters.
