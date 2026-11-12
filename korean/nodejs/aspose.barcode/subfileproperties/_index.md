---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "USA DL 서브파일 속성, 오프셋 및 길이가 자동으로 설정됩니다."
type: docs
weight: 890
url: /ko/nodejs/aspose.barcode/subfileproperties/
---

## SubfileProperties class

USA DL 서브파일 속성, 오프셋 및 길이가 자동으로 설정됩니다.

```js
new SubfileProperties()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getLength()](#getlength) | 4 이 바이트는 Subfile의 길이를 바이트 단위로 지정하는 4자리 숫자 값을 포함합니다. 세그먼트 종결자 m |
| [getOffset()](#getoffset) | 데이터가 관련된 위치까지 파일의 시작 또는 헤드로부터의 바이트 수를 지정하는 4자리 숫자 값 |
| [getType()](#gettype) | 예: "DL"와 같은 subfile의 2바이트 유형 |
| [setLength()](#setlength) | 4 이 바이트는 Subfile의 길이를 바이트 단위로 지정하는 4자리 숫자 값을 포함합니다. 세그먼트 종결자 m |
| [setOffset()](#setoffset) | 데이터가 관련된 위치까지 파일의 시작 또는 헤드로부터의 바이트 수를 지정하는 4자리 숫자 값 |
| [setType()](#settype) | 예: "DL"와 같은 subfile의 2바이트 유형 |

### getLength() {#getlength}

4 이 바이트는 Subfile의 길이를 바이트 단위로 지정하는 4자리 숫자 값을 포함합니다. 세그먼트 종결자는 subfile 길이를 계산할 때 포함되어야 합니다. 세그먼트 종결자 = 1. 각 subfile은 두 문자로 구성된 Subfile Type으로 시작해야 하며, 이 두 문자도 길이에 포함되어야 합니다.

### getOffset() {#getoffset}

특정 sub-file과 관련된 데이터가 위치한 곳까지 파일의 시작 또는 헤드로부터의 바이트 수를 지정하는 4자리 숫자 값. 파일의 첫 번째 바이트는 오프셋 0에 위치합니다.

### getType() {#gettype}

예: "DL"와 같은 subfile의 2바이트 유형

### setLength() {#setlength}

4 이 바이트는 Subfile의 길이를 바이트 단위로 지정하는 4자리 숫자 값을 포함합니다. 세그먼트 종결자는 subfile 길이를 계산할 때 포함되어야 합니다. 세그먼트 종결자 = 1. 각 subfile은 두 문자로 구성된 Subfile Type으로 시작해야 하며, 이 두 문자도 길이에 포함되어야 합니다.

### setOffset() {#setoffset}

특정 sub-file과 관련된 데이터가 위치한 곳까지 파일의 시작 또는 헤드로부터의 바이트 수를 지정하는 4자리 숫자 값. 파일의 첫 번째 바이트는 오프셋 0에 위치합니다.

### setType() {#settype}

예: "DL"와 같은 subfile의 2바이트 유형
