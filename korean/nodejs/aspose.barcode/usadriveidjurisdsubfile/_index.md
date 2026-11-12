---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "USA DL에 대한 관할 구역별 필드용 클래스."
type: docs
weight: 950
url: /ko/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

USA DL에 대한 관할 구역별 필드용 클래스.

```js
new USADriveIdJurisdSubfile()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | 지정된 식별자와 값을 가진 새 DataElement를 추가하거나, 동일한 식별자를 가진 항목이 있는 경우 기존 요소를 교체합니다. |
| [addOrReplaceNode(node)](#addorreplacenode) | ElementID가 이미 존재하면 새 DataElement를 추가하거나 교체합니다. |
| [clear()](#clear) | 모든 데이터 요소를 삭제합니다. |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | 3자리 ID로 데이터 요소를 검색합니다. |
| [get(indexOrId)](#get) | 인덱스 또는 3자리 ID로 데이터 요소를 가져옵니다. |
| [insert(index, node)](#insert) | 지정된 DataElement를 주어진 인덱스에 삽입합니다. 동일한 ElementID를 가진 DataElement가 이미 존재하면 교체됩니다. |
| [remove(indexOrId)](#remove) | 인덱스 또는 3자리 ID로 요소를 제거하려고 시도합니다. |
| [set(indexOrId, value)](#set) | 인덱스 또는 3자리 ID로 데이터 요소를 설정합니다. |
| [size()](#size) | 데이터 요소의 개수를 반환합니다. |

### addOrReplace(id, value) {#addorreplace}

지정된 식별자와 값을 가진 새 DataElement를 추가하거나, 동일한 ElementID를 가진 항목이 이미 존재하면 기존 요소를 교체합니다.

| 매개변수 | 설명 |
| --- | --- |
| 아이디 | 관할 관련 데이터 요소를 고유하게 지정하는 3자리 식별자입니다. |
| 값 | 데이터 요소에 할당된 텍스트 값; 요소가 이미 존재하면 이 값이 기존 값을 덮어씁니다. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

ElementID가 이미 존재하면 새 DataElement를 추가하거나 교체합니다.

| 매개변수 | 설명 |
| --- | --- |
| 노드 | 추가할 DataElement |

**Returns:** Added/replaced data element

### clear() {#clear}

모든 데이터 요소를 삭제합니다.

### findDataElement(id, isOpenOrCreate) {#finddataelement}

3자리 ID로 데이터 요소를 검색합니다.

| 매개변수 | 설명 |
| --- | --- |
| 아이디 | 3자리 아이디 |
| isOpenOrCreate | true이면, 찾지 못했을 때 생성됩니다. |

**Returns:** Found data element

### get(indexOrId) {#get}

인덱스 또는 3자리 ID로 데이터 요소를 가져옵니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| indexOrId | number\\ | string | 정수 인덱스 또는 3자리 요소 ID. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

지정된 DataElement를 주어진 인덱스에 삽입합니다. 동일한 ElementID를 가진 DataElement가 이미 존재하면 교체됩니다.

| 매개변수 | 설명 |
| --- | --- |
| 인덱스 | 요소를 삽입해야 하는 0부터 시작하는 인덱스입니다. |
| 노드 | 대상 위치에 삽입하거나 교체할 DataElement 인스턴스입니다. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

인덱스 또는 3자리 ID로 요소를 제거하려고 시도합니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| indexOrId | number\\ | string | 정수 인덱스 또는 3자리 요소 ID. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

인덱스 또는 3자리 ID로 데이터 요소를 설정합니다.

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| indexOrId | number\\ | string | 정수 인덱스 또는 3자리 요소 ID. |
| 값 | DataElement | 설정할 데이터 요소. |

### size() {#size}

데이터 요소의 개수를 반환합니다.
