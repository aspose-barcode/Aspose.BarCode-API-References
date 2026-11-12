---
title: "PrimaryData"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "HIBC LIC 기본 데이터를 저장하기 위한 클래스."
type: docs
weight: 800
url: /ko/nodejs/aspose.barcode/primarydata/
---

## PrimaryData class

HIBC LIC 기본 데이터를 저장하기 위한 클래스.

```js
new PrimaryData()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 이 인스턴스가 지정된 `PrimaryData` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getLabelerIdentificationCode()](#getlabeleridentificationcode) | 라벨러 식별 코드의 날짜를 식별합니다. 라벨러 식별 코드는 4자리 알파벳 및 숫자 문자열이어야 하며, |
| [getProductOrCatalogNumber()](#getproductorcatalognumber) | 제품 또는 카탈로그 번호를 식별합니다. 제품 또는 카탈로그 번호는 최대 18자까지의 알파벳 및 숫자 문자열이어야 합니다. |
| [getUnitOfMeasureID()](#getunitofmeasureid) | 측정 단위 ID를 식별합니다. 측정 단위 ID는 0부터 9까지의 정수 값이어야 합니다. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [parseFromString(primaryDataCodetext)](#parsefromstring) | HIBC LIC 사양에 따라 문자열 형식에서 기본 데이터를 인스턴스화합니다. |
| [setLabelerIdentificationCode()](#setlabeleridentificationcode) | 라벨러 식별 코드의 날짜를 식별합니다. 라벨러 식별 코드는 4자리 알파벳 및 숫자 문자열이어야 하며, |
| [setProductOrCatalogNumber()](#setproductorcatalognumber) | 제품 또는 카탈로그 번호를 식별합니다. 제품 또는 카탈로그 번호는 최대 18자까지의 알파벳 및 숫자 문자열이어야 합니다. |
| [setUnitOfMeasureID()](#setunitofmeasureid) | 측정 단위 ID를 식별합니다. 측정 단위 ID는 0부터 9까지의 정수 값이어야 합니다. |
| [toString()](#tostring) | 데이터를 HIBC LIC 사양에 따라 문자열 형식으로 변환합니다. |

### equals(obj) {#equals}

이 인스턴스가 지정된 `PrimaryData` 값과 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교하기 위한 `PrimaryData` 값입니다. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getLabelerIdentificationCode() {#getlabeleridentificationcode}

라벨러 식별 코드의 날짜를 식별합니다. 라벨러 식별 코드는 4자리 알파벳 및 숫자 문자열이어야 하며, 첫 번째 문자는 항상 알파벳이어야 합니다.

### getProductOrCatalogNumber() {#getproductorcatalognumber}

제품 또는 카탈로그 번호를 식별합니다. 제품 또는 카탈로그 번호는 최대 18자까지의 알파벳 및 숫자 문자열이어야 합니다.

### getUnitOfMeasureID() {#getunitofmeasureid}

측정 단위 ID를 식별합니다. 측정 단위 ID는 0부터 9까지의 정수 값이어야 합니다.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### parseFromString(primaryDataCodetext) {#parsefromstring}

HIBC LIC 사양에 따라 문자열 형식에서 기본 데이터를 인스턴스화합니다.

| 매개변수 | 설명 |
| --- | --- |
| primaryDataCodetext | 포맷된 문자열. |

### setLabelerIdentificationCode() {#setlabeleridentificationcode}

라벨러 식별 코드의 날짜를 식별합니다. 라벨러 식별 코드는 4자리 알파벳 및 숫자 문자열이어야 하며, 첫 번째 문자는 항상 알파벳이어야 합니다.

### setProductOrCatalogNumber() {#setproductorcatalognumber}

제품 또는 카탈로그 번호를 식별합니다. 제품 또는 카탈로그 번호는 최대 18자까지의 알파벳 및 숫자 문자열이어야 합니다.

### setUnitOfMeasureID() {#setunitofmeasureid}

측정 단위 ID를 식별합니다. 측정 단위 ID는 0부터 9까지의 정수 값이어야 합니다.

### toString() {#tostring}

데이터를 HIBC LIC 사양에 따라 문자열 형식으로 변환합니다.

**Returns:** Formatted string.
