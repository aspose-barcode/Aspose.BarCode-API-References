---
title: "ITFParameters"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "ITF 매개변수."
type: docs
weight: 540
url: /ko/nodejs/aspose.barcode/itfparameters/
---

## ITFParameters class

ITF 매개변수.

```js
new ITFParameters()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getBorderThickness()](#getborderthickness) | ITF 경계(베어러 바)의 두께를 Unit 값으로 가져옵니다. 기본값: 12pt. |
| [getBorderType()](#getbordertype) | ITF 바코드의 경계 유형입니다. 기본값: ITF14BorderType.Bar. |
| [getItfBorderThickness()](#getitfborderthickness) ~~(deprecated)~~ | ITF 경계(베어러 바)의 두께를 Unit 값으로 가져옵니다. 기본값: 12pt. |
| [getItfBorderType()](#getitfbordertype) ~~(deprecated)~~ | ITF 바코드의 경계 유형입니다. 기본값: ITF14BorderType.BAR. |
| [getQuietZoneCoef()](#getquietzonecoef) | xDimension에서 정지 구역(quiet zone)의 크기입니다. 기본값: 10, 즉 xDimension = 2px이면 정지 구역이 20px이 됩니다. |
| [setBorderThickness(value)](#setborderthickness) | ITF 경계(베어러 바)의 두께를 Unit 값으로 설정합니다. 기본값: 12pt. |
| [setBorderType()](#setbordertype) | ITF 바코드의 경계 유형입니다. 기본값: ITF14BorderType.Bar. |
| [setItfBorderThickness()](#setitfborderthickness) ~~(deprecated)~~ | ITF 경계(베어러 바)의 두께를 Unit 값으로 설정합니다. 기본값: 12pt. |
| [setItfBorderType()](#setitfbordertype) ~~(deprecated)~~ | ITF 바코드의 경계 유형입니다. 기본값: ITF14BorderType.BAR. |
| [setQuietZoneCoef()](#setquietzonecoef) | xDimension에서 정지 구역(quiet zone)의 크기입니다. 기본값: 10, 즉 xDimension = 2px이면 정지 구역이 20px이 됩니다. |
| [toString()](#tostring) | 이 ITFParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### getBorderThickness() {#getborderthickness}

ITF 경계(베어러 바)의 두께를 Unit 값으로 가져옵니다. 기본값: 12pt.

**Returns:** an ITF border (bearer bar) thickness in Unit value.

### getBorderType() {#getbordertype}

ITF 바코드의 경계 유형입니다. 기본값: ITF14BorderType.Bar.

### getItfBorderThickness() {#getitfborderthickness}

> **Deprecated.** See method description for replacement.

ITF 경계(베어러 바)의 두께를 Unit 값으로 가져옵니다. 기본값: 12pt.

### getItfBorderType() {#getitfbordertype}

> **Deprecated.** See method description for replacement.

ITF 바코드의 경계 유형입니다. 기본값: ITF14BorderType.BAR.

### getQuietZoneCoef() {#getquietzonecoef}

xDimension에서 정지 구역(quiet zone)의 크기입니다. 기본값: 10, 즉 xDimension = 2px이면 정지 구역이 20px이 됩니다.

**Throws:** IllegalArgumentException
QuietZoneCoef 매개변수 값이 10보다 작습니다.

### setBorderThickness(value) {#setborderthickness}

ITF 경계(베어러 바)의 두께를 Unit 값으로 설정합니다. 기본값: 12pt.

| 매개변수 | 설명 |
| --- | --- |
| 값 | ITF 경계(베어러 바)의 두께를 Unit 값으로. |

### setBorderType() {#setbordertype}

ITF 바코드의 경계 유형입니다. 기본값: ITF14BorderType.Bar.

### setItfBorderThickness() {#setitfborderthickness}

> **Deprecated.** See method description for replacement.

ITF 경계(베어러 바)의 두께를 Unit 값으로 설정합니다. 기본값: 12pt.

### setItfBorderType() {#setitfbordertype}

> **Deprecated.** See method description for replacement.

ITF 바코드의 경계 유형입니다. 기본값: ITF14BorderType.BAR.

### setQuietZoneCoef() {#setquietzonecoef}

xDimension에서 정지 구역(quiet zone)의 크기입니다. 기본값: 10, 즉 xDimension = 2px이면 정지 구역이 20px이 됩니다.

**Throws:** IllegalArgumentException
QuietZoneCoef 매개변수 값이 10보다 작습니다.

### toString() {#tostring}

이 ITFParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this ITFParameters.
