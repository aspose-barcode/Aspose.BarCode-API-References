---
title: Quadrangle
second_title: Aspose.BarCode for Android via Java API Reference
description: Quadrangle 영역을 나타내는 네 개의 Point 집합을 저장합니다.
type: docs
weight: 43
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

네 개의  Point  로 구성된  Quadrangle  영역을 저장합니다.
## Constructors

| Constructor | 설명 |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | 설명 포인트를 사용하여 Quadrangle 구조의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [EMPTY](#EMPTY) | 속성이 초기화되지 않은 Quadrangle 클래스를 나타냅니다. |
## Methods

| Method | 설명 |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | 지정된 Point가 이 Quadrangle 클래스에 포함되는지 확인합니다. |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | 지정된 Rectangle이 이 Quadrangle 클래스에 포함되거나 교차하는지 확인합니다. |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | 지정된 Quadrangle이 이 Quadrangle 클래스에 포함되거나 교차하는지 확인합니다. |
| [contains(int x, int y)](#contains-int-int-) | 지정된 포인트가 이 Quadrangle 클래스에 포함되는지 확인합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 Quadrangle 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getBoundingRectangle()](#getBoundingRectangle--) | 이 Quadrangle을 둘러싸는 Rectangle을 생성합니다. |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Quadrangle 영역의 왼쪽 하단 코너 Point를 가져옵니다. |
| [getLeftTop()](#getLeftTop--) | Quadrangle 영역의 왼쪽 위 모서리 Point를 가져옵니다. |
| [getRightBottom()](#getRightBottom--) | Quadrangle 영역의 오른쪽 아래 모서리 Point를 가져옵니다. |
| [getRightTop()](#getRightTop--) | Quadrangle 영역의 오른쪽 위 모서리 Point를 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isEmpty()](#isEmpty--) | 이 Quadrangle의 모든 Point가 값이 0인지 테스트합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Quadrangle 영역의 왼쪽 하단 코너 Point를 가져옵니다. |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Quadrangle 영역의 왼쪽 위 모서리 Point를 가져옵니다. |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Quadrangle 영역의 오른쪽 아래 모서리 Point를 가져옵니다. |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Quadrangle 영역의 오른쪽 위 모서리 Point를 가져옵니다. |
| [toString()](#toString--) | 이 Quadrangle의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


설명 포인트를 사용하여 Quadrangle 구조의 새 인스턴스를 초기화합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| leftTop | android.graphics.Point | Quadrangle의 왼쪽 위 모서리를 나타내는 Point입니다. |
| rightTop | android.graphics.Point | Quadrangle의 오른쪽 위 모서리를 나타내는 Point입니다. |
| rightBottom | android.graphics.Point | Quadrangle의 오른쪽 아래 모서리를 나타내는 Point입니다. |
| leftBottom | android.graphics.Point | Quadrangle의 왼쪽 아래 모서리를 나타내는 Point입니다. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


속성이 초기화되지 않은 Quadrangle 클래스를 나타냅니다.

값: Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Point pt) {#contains-android.graphics.Point-}
```
public boolean contains(Point pt)
```


지정된 Point가 이 Quadrangle 클래스에 포함되는지 확인합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| pt | android.graphics.Point | 테스트할 Point입니다. |

**Returns:**
boolean - Point가 이 Quadrangle 클래스에 포함되어 있으면 **true**를 반환하고, 그렇지 않으면 **false**를 반환합니다.
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


지정된 Rectangle이 이 Quadrangle 클래스에 포함되거나 교차하는지 확인합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| rect | android.graphics.Rect | 테스트할 Rectangle입니다. |

**Returns:**
boolean - Rectangle이 이 Quadrangle 클래스에 포함되거나 교차하면 **true**를 반환하고, 그렇지 않으면 **false**를 반환합니다.
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


지정된 Quadrangle이 이 Quadrangle 클래스에 포함되거나 교차하는지 확인합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | 테스트할 Quadrangle입니다. |

**Returns:**
boolean - Quadrangle이 이 Quadrangle 클래스에 포함되거나 교차하면 **true**를 반환하고, 그렇지 않으면 **false**를 반환합니다.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


지정된 포인트가 이 Quadrangle 클래스에 포함되는지 확인합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| x | int | x 좌표 점입니다. |
| y | int | y 점 좌표. |

**Returns:**
boolean - 점이 이 **Quadrangle** 클래스에 포함되어 있으면 **true** 를 반환하고, 그렇지 않으면 **false** 를 반환합니다.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 Quadrangle 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 **Quadrangle** 값. |

**Returns:**
boolean -  **true**  if obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않은 경우 **false**.
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


이 Quadrangle을 둘러싸는 Rectangle을 생성합니다.

**Returns:**
android.graphics.Rect - 이 **Quadrangle**을 둘러싼 **Rectangle**를 반환합니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public Point getLeftBottom()
```


Quadrangle 영역의 왼쪽 하단 코너 Point를 가져옵니다.

값: **Quadrangle** 영역의 왼쪽 하단 모서리 **Point**

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Quadrangle 영역의 왼쪽 위 모서리 Point를 가져옵니다.

값: **Quadrangle** 영역의 왼쪽 상단 모서리 **Point**

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Quadrangle 영역의 오른쪽 아래 모서리 Point를 가져옵니다.

값: **Quadrangle** 영역의 오른쪽 하단 모서리 **Point**

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Quadrangle 영역의 오른쪽 위 모서리 Point를 가져옵니다.

값: **Quadrangle** 영역의 오른쪽 상단 모서리 **Point**

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드입니다.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


이 Quadrangle의 모든 Point가 값이 0인지 테스트합니다.

값: 이 **Quadrangle**의 모든 **Point**가 값이 0이면 **true** 를 반환하고, 그렇지 않으면 **false** 를 반환합니다.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLeftBottom(Point value) {#setLeftBottom-android.graphics.Point-}
```
public void setLeftBottom(Point value)
```


Quadrangle 영역의 왼쪽 하단 코너 Point를 가져옵니다.

값: **Quadrangle** 영역의 왼쪽 하단 모서리 **Point**

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Quadrangle 영역의 왼쪽 위 모서리 Point를 가져옵니다.

값: **Quadrangle** 영역의 왼쪽 상단 모서리 **Point**

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Quadrangle 영역의 오른쪽 아래 모서리 Point를 가져옵니다.

값: **Quadrangle** 영역의 오른쪽 하단 모서리 **Point**

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Quadrangle 영역의 오른쪽 위 모서리 Point를 가져옵니다.

값: **Quadrangle** 영역의 오른쪽 상단 모서리 **Point**

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


이 Quadrangle의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 **Quadrangle**을 나타내는 문자열.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

