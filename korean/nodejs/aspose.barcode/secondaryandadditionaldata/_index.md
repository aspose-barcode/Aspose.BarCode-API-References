---
title: "SecondaryAndAdditionalData"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "HIBC LIC 보조 및 추가 데이터를 저장하기 위한 클래스."
type: docs
weight: 880
url: /ko/nodejs/aspose.barcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

HIBC LIC 보조 및 추가 데이터를 저장하기 위한 클래스.

```js
new SecondaryAndAdditionalData()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 지정된 `SecondaryAndAdditionalData` 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| [getDateOfManufacture()](#getdateofmanufacture) | 제조 날짜를 식별합니다. 이 필드를 사용하지 않으려면 제조 날짜를 DateTime.MinValue로 설정할 수 있습니다. Defa |
| [getExpiryDate()](#getexpirydate) | 만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우 사용됩니다. |
| [getExpiryDateFormat()](#getexpirydateformat) | 만료 날짜 형식을 식별합니다. |
| [getLotNumber()](#getlotnumber) | LOT 또는 배치 번호를 식별합니다. Lot/batch 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. . |
| [getQuantity()](#getquantity) | 수량을 식별합니다. 0에서 500 사이의 정수값이어야 합니다. 이 필드를 사용하지 않으려면 수량을 -1로 설정할 수 있습니다. Defa |
| [getSerialNumber()](#getserialnumber) | 시리얼 번호를 식별합니다. 시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [parseFromString(secondaryDataCodetext)](#parsefromstring) | HIBC LIC 사양에 따라 문자열 형식에서 보조 및 추가 보충 데이터를 인스턴스화합니다. |
| [setDateOfManufacture()](#setdateofmanufacture) | 제조 날짜를 식별합니다. 이 필드를 사용하지 않으려면 제조 날짜를 DateTime.MinValue로 설정할 수 있습니다. Defa |
| [setExpiryDate()](#setexpirydate) | 만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우 사용됩니다. |
| [setExpiryDateFormat()](#setexpirydateformat) | 만료 날짜 형식을 식별합니다. |
| [setLotNumber()](#setlotnumber) | LOT 또는 배치 번호를 식별합니다. Lot/batch 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. . |
| [setQuantity()](#setquantity) | 수량을 식별합니다. 0에서 500 사이의 정수값이어야 합니다. 이 필드를 사용하지 않으려면 수량을 -1로 설정할 수 있습니다. Defa |
| [setSerialNumber()](#setserialnumber) | 시리얼 번호를 식별합니다. 시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. |
| [toString()](#tostring) | 데이터를 HIBC LIC 사양에 따라 문자열 형식으로 변환합니다. |

### equals(obj) {#equals}

지정된 `SecondaryAndAdditionalData` 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | `SecondaryAndAdditionalData` 값을 이 인스턴스와 비교합니다. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDateOfManufacture() {#getdateofmanufacture}

제조 날짜를 식별합니다. 이 필드를 사용하지 않으려면 제조 날짜를 DateTime.MinValue로 설정할 수 있습니다. 기본값: DateTime.MinValue

### getExpiryDate() {#getexpirydate}

만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우 사용됩니다.

### getExpiryDateFormat() {#getexpirydateformat}

만료 날짜 형식을 식별합니다.

### getLotNumber() {#getlotnumber}

LOT 또는 배치 번호를 식별합니다. Lot/batch 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. .

### getQuantity() {#getquantity}

수량을 식별합니다. 0에서 500 사이의 정수값이어야 합니다. 이 필드를 사용하지 않으려면 수량을 -1로 설정할 수 있습니다. 기본값: -1

### getSerialNumber() {#getserialnumber}

시리얼 번호를 식별합니다. 시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### parseFromString(secondaryDataCodetext) {#parsefromstring}

HIBC LIC 사양에 따라 문자열 형식에서 보조 및 추가 보충 데이터를 인스턴스화합니다.

| 매개변수 | 설명 |
| --- | --- |
| secondaryDataCodetext | 포맷된 문자열. |

### setDateOfManufacture() {#setdateofmanufacture}

제조 날짜를 식별합니다. 이 필드를 사용하지 않으려면 제조 날짜를 DateTime.MinValue로 설정할 수 있습니다. 기본값: DateTime.MinValue

### setExpiryDate() {#setexpirydate}

만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우 사용됩니다.

### setExpiryDateFormat() {#setexpirydateformat}

만료 날짜 형식을 식별합니다.

### setLotNumber() {#setlotnumber}

LOT 또는 배치 번호를 식별합니다. Lot/batch 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다. .

### setQuantity() {#setquantity}

수량을 식별합니다. 0에서 500 사이의 정수값이어야 합니다. 이 필드를 사용하지 않으려면 수량을 -1로 설정할 수 있습니다. 기본값: -1

### setSerialNumber() {#setserialnumber}

시리얼 번호를 식별합니다. 시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다.

### toString() {#tostring}

데이터를 HIBC LIC 사양에 따라 문자열 형식으로 변환합니다.

**Returns:** Formatted string.
