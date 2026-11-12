---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "사각형 영역을 나타내는 네 개의 포인트 집합을 저장합니다"
type: docs
weight: 850
url: /ko/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

사각형 영역을 나타내는 네 개의 포인트 집합을 저장합니다

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

설명 포인트를 사용하여 Quadrangle 구조의 새 인스턴스를 초기화합니다.

| 매개변수 | 설명 |
| --- | --- |
| leftTop | Quadrangle의 왼쪽 위 모서리를 나타내는 Point입니다. |
| rightTop | Quadrangle의 오른쪽 위 모서리를 나타내는 Point입니다. |
| rightBottom | Quadrangle의 오른쪽 아래 모서리를 나타내는 Point입니다. |
| leftBottom | Quadrangle의 왼쪽 아래 모서리를 나타내는 Point입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [contains(pt)](#contains) | 지정된 Point가 이 Quadrangle 구조 내에 포함되는지 확인합니다. |
| [containsPoint(x, y)](#containspoint) | 지정된 포인트가 이 Quadrangle 구조 내에 포함되는지 확인합니다. |
| [containsQuadrangle(quad)](#containsquadrangle) | 지정된 Quadrangle이 이 Quadrangle 구조에 포함되거나 교차하는지 확인합니다. |
| [containsRectangle(rect)](#containsrectangle) | 지정된 Rectangle이 이 Quadrangle 구조에 포함되거나 교차하는지 확인합니다. |
| [equals(other)](#equals) | 이 인스턴스가 지정된 Quadrangle 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getBoundingRectangle()](#getboundingrectangle) | 이 Quadrangle을 둘러싸는 Rectangle을 생성합니다. |
| [getLeftBottom()](#getleftbottom) | Quadrangle 영역의 왼쪽 아래 모서리 Point를 가져옵니다Value: Quadrangle 영역의 왼쪽 아래 모서리 Point입니다. |
| [getLeftTop()](#getlefttop) | Quadrangle 영역의 왼쪽 위 모서리 Point를 가져옵니다Value: Quadrangle 영역의 왼쪽 위 모서리 Point입니다. |
| [getRightBottom()](#getrightbottom) | Quadrangle 영역의 오른쪽 아래 모서리 Point를 가져옵니다Value: Quadrangle 영역의 오른쪽 아래 모서리 Point입니다. |
| [getRightTop()](#getrighttop) | Quadrangle 영역의 오른쪽 위 모서리 Point를 가져옵니다Value: Quadrangle 영역의 오른쪽 위 모서리 Point입니다. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isEmpty()](#isempty) | 이 Quadrangle의 모든 Point가 0값인지 테스트합니다.값: 모든 Point가 0값이면 true를 반환합니다. |
| [setLeftBottom()](#setleftbottom) | Quadrangle 영역의 왼쪽 아래 모서리 Point를 설정합니다.값: Quadrangle 영역의 왼쪽 아래 모서리 Point |
| [setLeftTop()](#setlefttop) | Quadrangle 영역의 왼쪽 위 모서리 Point를 설정합니다.값: Quadrangle 영역의 왼쪽 위 모서리 Point |
| [setRightBottom()](#setrightbottom) | Quadrangle 영역의 오른쪽 아래 모서리 Point를 설정합니다.값: Quadrangle 영역의 오른쪽 아래 모서리 Point |
| [setRightTop()](#setrighttop) | Quadrangle 영역의 오른쪽 위 모서리 Point를 설정합니다.값: Quadrangle 영역의 오른쪽 위 모서리 Point |
| [toString()](#tostring) | 이 Quadrangle의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### contains(pt) {#contains}

지정된 Point가 이 Quadrangle 구조 내에 포함되는지 확인합니다.

| 매개변수 | 설명 |
| --- | --- |
| pt | 테스트할 Point. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

지정된 포인트가 이 Quadrangle 구조 내에 포함되는지 확인합니다.

| 매개변수 | 설명 |
| --- | --- |
| x | x 좌표. |
| y | y 좌표. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

지정된 Quadrangle이 이 Quadrangle 구조에 포함되거나 교차하는지 확인합니다.

| 매개변수 | 설명 |
| --- | --- |
| quad | 테스트할 Quadrangle. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

지정된 Rectangle이 이 Quadrangle 구조에 포함되거나 교차하는지 확인합니다.

| 매개변수 | 설명 |
| --- | --- |
| rect | 테스트할 Rectangle. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

이 인스턴스가 지정된 Quadrangle 값과 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| 기타 | 이 인스턴스와 비교할 Quadrangle 값. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

이 Quadrangle을 둘러싸는 Rectangle을 생성합니다.

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Quadrangle 영역의 왼쪽 아래 모서리 Point를 가져옵니다Value: Quadrangle 영역의 왼쪽 아래 모서리 Point입니다.

### getLeftTop() {#getlefttop}

Quadrangle 영역의 왼쪽 위 모서리 Point를 가져옵니다Value: Quadrangle 영역의 왼쪽 위 모서리 Point입니다.

### getRightBottom() {#getrightbottom}

Quadrangle 영역의 오른쪽 아래 모서리 Point를 가져옵니다Value: Quadrangle 영역의 오른쪽 아래 모서리 Point입니다.

### getRightTop() {#getrighttop}

Quadrangle 영역의 오른쪽 위 모서리 Point를 가져옵니다Value: Quadrangle 영역의 오른쪽 위 모서리 Point입니다.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

이 Quadrangle의 모든 Point가 0값인지 테스트합니다.값: 모든 Point가 0값이면 true를 반환하고, 그렇지 않으면 false를 반환합니다.

### setLeftBottom() {#setleftbottom}

Quadrangle 영역의 왼쪽 아래 모서리 Point를 설정합니다.값: Quadrangle 영역의 왼쪽 아래 모서리 Point

### setLeftTop() {#setlefttop}

Quadrangle 영역의 왼쪽 위 모서리 Point를 설정합니다.값: Quadrangle 영역의 왼쪽 위 모서리 Point

### setRightBottom() {#setrightbottom}

Quadrangle 영역의 오른쪽 아래 모서리 Point를 설정합니다.값: Quadrangle 영역의 오른쪽 아래 모서리 Point

### setRightTop() {#setrighttop}

Quadrangle 영역의 오른쪽 위 모서리 Point를 설정합니다.값: Quadrangle 영역의 오른쪽 위 모서리 Point

### toString() {#tostring}

이 Quadrangle의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this Quadrangle.
