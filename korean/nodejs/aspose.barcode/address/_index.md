---
title: "주소"
linktitle: "주소"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "채권자 또는 채무자의 주소."
type: docs
weight: 10
url: /ko/nodejs/aspose.barcode/address/
---

## Address class

채권자 또는 채무자의 주소. 거리, 건물 번호, 우편번호 및 도시를 설정하거나(구조화된 주소 유형) 주소 라인 1 및 2을 설정할 수 있습니다(결합된 주소 요소 유형). 이 필드 중 하나가 설정되면 주소 유형이 자동으로 지정됩니다. 필드를 설정하기 전에는 주소 유형이 미정입니다. 두 유형의 필드를 모두 설정하면 주소 유형이 충돌하게 됩니다. 모든 필드가 비어 있지 않은 한 이름과 국가 코드는 항상 설정되어야 합니다.

```js
new Address()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [clear()](#clear) | 모든 필드를 지우고 유형을 AddressType.UNDETERMINED으로 설정합니다. |
| [equals(obj)](#equals) | 지정된 객체가 현재 객체와 같은지 여부를 결정합니다. |
| [getAddressLine1()](#getaddressline1) | 주소 라인 1을 가져옵니다. 주소 라인 1에는 거리 이름, 건물 번호 또는 사서함이 포함됩니다. 이 필드를 설정하면 addr |
| [getAddressLine2()](#getaddressline2) | 주소 라인 2를 가져옵니다. 주소 라인 2에는 우편번호와 도시가 포함됩니다. 이 필드를 설정하면 주소 유형이 Addre |
| [getCountryCode()](#getcountrycode) | 두 글자 ISO 국가 코드를 가져옵니다. 전체 주소에 null 또는 빈 val이 포함되지 않는 한 국가 코드는 필수입니다. |
| [getHouseNo()](#gethouseno) | 건물 번호를 가져옵니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED로 설정됩니다(이미 AddressTyp인 경우 제외). |
| [getName()](#getname) | 이름을 가져옵니다. 자연인의 경우 이름과 성, 법인의 경우 회사명을 의미합니다. |
| [getPostalCode()](#getpostalcode) | 우편번호를 가져옵니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED로 설정됩니다(이미 AddressType인 경우 제외). |
| [getStreet()](#getstreet) | 거리를 가져옵니다. 거리는 건물 번호 없이 지정되어야 합니다. 이 필드를 설정하면 주소 유형이 AddressT로 설정됩니다. |
| [getTown()](#gettown) | 도시 또는 마을을 가져옵니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED로 설정됩니다(이미 AddressTyp인 경우 제외). |
| [getType()](#gettype) | 주소 유형을 가져옵니다. 주소 유형은 거리/건물 번호를 설정하거나 주소 라인 1 a를 설정함으로써 자동으로 지정됩니다. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 가져옵니다. |
| [setAddressLine1(value:)](#setaddressline1) | 주소 라인 1을 설정합니다. 주소 라인 1에는 거리 이름, 건물 번호 또는 사서함이 포함됩니다. 이 필드를 설정하면 addr |
| [setAddressLine2(value:)](#setaddressline2) | 주소 라인 2를 설정합니다. 주소 라인 2에는 우편 번호와 도시가 포함됩니다. 이 필드를 설정하면 주소 유형이 Addre 로 설정됩니다. |
| [setCountryCode(value)](#setcountrycode) | 두 글자 ISO 국가 코드를 설정합니다. 전체 주소에 null 또는 emtpy val 가 포함되지 않은 경우에만 국가 코드는 필수입니다. |
| [setHouseNo(value:)](#sethouseno) | 집 번호를 설정합니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED 로 설정되며, 이미 AddressTyp 인 경우는 제외됩니다. |
| [setName(value:)](#setname) | 이름을 설정합니다. 자연인의 경우 이름과 성, 법인의 경우 회사명을 입력합니다. |
| [setPostalCode(value)](#setpostalcode) | 우편 번호를 설정합니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED 로 설정되며, 이미 AddressType 인 경우는 제외됩니다. |
| [setStreet(value:)](#setstreet) | 거리명을 설정합니다. 거리명은 집 번호 없이 지정해야 합니다. 이 필드를 설정하면 주소 유형이 AddressT 로 설정됩니다. |
| [setTown(value)](#settown) | 도시 또는 마을을 설정합니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED 로 설정되며, 이미 AddressTyp 인 경우는 제외됩니다. |

### clear() {#clear}

모든 필드를 지우고 유형을 AddressType.UNDETERMINED으로 설정합니다.

### equals(obj) {#equals}

지정된 객체가 현재 객체와 같은지 여부를 결정합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 현재 객체와 비교할 객체. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

주소 라인 1을 가져옵니다. 주소 라인 1에는 거리명, 집 번호 또는 사서함이 포함됩니다. 이 필드를 설정하면 주소 유형이 AddressType.COMBINED_ELEMENTS 로 설정되며, 이미 AddressType.STRUCTURED 인 경우에는 AddressType.CONFLICTING 로 변경됩니다. 이 필드는 결합된 요소 주소에만 사용되며 선택 사항입니다.

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

주소 라인 2를 가져옵니다. 주소 라인 2에는 우편 번호와 도시가 포함됩니다. 이 필드를 설정하면 주소 유형이 AddressType.COMBINED_ELEMENTS 로 설정되며, 이미 AddressType.STRUCTURED 인 경우에는 AddressType.CONFLICTING 로 변경됩니다. 이 필드는 결합된 요소 주소에만 사용됩니다. 이 유형에서는 필수입니다.

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

두 글자 ISO 국가 코드를 가져옵니다. 전체 주소에 null 또는 emtpy values 가 포함되지 않은 경우에만 국가 코드는 필수입니다.

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

집 번호를 가져옵니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED 로 설정되며, 이미 AddressType.COMBINED_ELEMENTS 인 경우에는 AddressType.CONFLICTING 로 변경됩니다. 이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.

**Returns:** The house number.

### getName() {#getname}

이름을 가져옵니다. 자연인의 경우 이름과 성, 법인의 경우 회사명을 의미합니다.

**Returns:** The name.

### getPostalCode() {#getpostalcode}

우편 번호를 가져옵니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED 로 설정되며, 이미 AddressType.COMBINED_ELEMENTS 인 경우에는 AddressType.CONFLICTING 로 변경됩니다. 이 필드는 구조화된 주소에만 사용됩니다. 이 유형에서는 필수입니다.

**Returns:** The postal code.

### getStreet() {#getstreet}

거리를 가져옵니다. 거리는 집 번호 없이 지정해야 합니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED 로 설정되며, 이미 AddressType.COMBINED_ELEMENTS 인 경우에는 AddressType.CONFLICTING 로 변경됩니다. 이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.

**Returns:** The street.

### getTown() {#gettown}

도시 또는 마을을 가져옵니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED 로 설정되며, 이미 AddressType.COMBINED_ELEMENTS 인 경우에는 AddressType.CONFLICTING 로 변경됩니다. 이 필드는 구조화된 주소에만 사용됩니다. 이 유형에서는 필수입니다.

**Returns:** The town or city.

### getType() {#gettype}

주소 유형을 가져옵니다. 주소 유형은 거리/집 번호를 설정하거나 주소 라인 1과 2를 설정함으로써 자동으로 지정됩니다. 필드를 설정하기 전에는 주소 유형이 Undetermined 입니다. 두 유형의 필드를 모두 설정하면 주소 유형이 Conflicting 로 변경됩니다.

**Returns:** The address type.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 가져옵니다.

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

주소 라인 1을 설정합니다. 주소 라인 1에는 거리명, 집 번호 또는 사서함이 포함됩니다. 이 필드를 설정하면 주소 유형이 AddressType.COMBINED_ELEMENTS 로 설정되며, 이미 AddressType.STRUCTURED 인 경우에는 AddressType.CONFLICTING 로 변경됩니다. 이 필드는 결합된 요소 주소에만 사용되며 선택 사항입니다.

| 매개변수 | 설명 |
| --- | --- |
| 값: | 주소 라인 1. |

### setAddressLine2(value:) {#setaddressline2}

주소 라인 2를 설정합니다. 주소 라인 2에는 우편 번호와 도시가 포함됩니다. 이 필드를 설정하면 주소 유형이 AddressType.COMBINED_ELEMENTS 로 설정되며, 이미 AddressType.STRUCTURED 인 경우에는 AddressType.CONFLICTING 로 변경됩니다. 이 필드는 결합된 요소 주소에만 사용됩니다. 이 유형에서는 필수입니다.

| 매개변수 | 설명 |
| --- | --- |
| 값: | 주소 라인 2. |

### setCountryCode(value) {#setcountrycode}

두 글자 ISO 국가 코드를 설정합니다. 전체 주소에 null 또는 emtpy values 가 포함되지 않은 경우에만 국가 코드는 필수입니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | ISO 국가 코드. |

### setHouseNo(value:) {#sethouseno}

집 번호를 설정합니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED 로 설정되며, 이미 AddressType.COMBINED_ELEMENTS 인 경우에는 AddressType.CONFLICTING 로 변경됩니다. 이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.

| 매개변수 | 설명 |
| --- | --- |
| 값: | 집 번호. |

### setName(value:) {#setname}

이름을 설정합니다. 자연인의 경우 이름과 성, 법인의 경우 회사명을 입력합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값: | 이름. |

### setPostalCode(value) {#setpostalcode}

우편 번호를 설정합니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED로 설정됩니다. 이미 AddressType.COMBINED_ELEMENTS인 경우에는 AddressType.CONFLICTING이 됩니다. 이 필드는 구조화된 주소에만 사용됩니다. 이 유형의 경우 필수입니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 우편 번호. |

### setStreet(value:) {#setstreet}

거리를 설정합니다. 거리는 건물 번호 없이 지정해야 합니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED로 설정됩니다. 이미 AddressType.COMBINED_ELEMENTS인 경우에는 AddressType.CONFLICTING이 됩니다. 이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.

| 매개변수 | 설명 |
| --- | --- |
| 값: | 거리. |

### setTown(value) {#settown}

도시 또는 마을을 설정합니다. 이 필드를 설정하면 주소 유형이 AddressType.STRUCTURED로 설정됩니다. 이미 AddressType.COMBINED_ELEMENTS인 경우에는 AddressType.CONFLICTING이 됩니다. 이 필드는 구조화된 주소에만 사용됩니다. 이 유형의 경우 필수입니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 도시 또는 마을. |
