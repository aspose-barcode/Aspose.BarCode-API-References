---
title: "BorderParameters"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "바코드 이미지 테두리 매개변수"
type: docs
weight: 18
url: /ko/java/com.aspose.barcode.generation/borderparameters/
---
**Inheritance:**
java.lang.Object
```
public class BorderParameters
```

바코드 이미지 테두리 매개변수
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | 테두리 색상. |
| [getDashStyle()](#getDashStyle--) | 테두리 대시 스타일. |
| [getVisible()](#getVisible--) | 테두리 표시 여부. |
| [getWidth()](#getWidth--) | 테두리 두께. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(Color value)](#setColor-java.awt.Color-) | 테두리 색상. |
| [setDashStyle(BorderDashStyle value)](#setDashStyle-com.aspose.barcode.generation.BorderDashStyle-) | 테두리 대시 스타일. |
| [setVisible(boolean value)](#setVisible-boolean-) | 테두리 표시 여부. |
| [setWidth(Unit value)](#setWidth-com.aspose.barcode.generation.Unit-) | 테두리 두께. |
| [toString()](#toString--) | 이 BorderParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


테두리 색상. 기본값: Color.Black.

**Returns:**
java.awt.Color
### getDashStyle() {#getDashStyle--}
```
public BorderDashStyle getDashStyle()
```


테두리 대시 스타일. 기본값: BorderDashStyle.Solid.

**Returns:**
[BorderDashStyle](../../com.aspose.barcode.generation/borderdashstyle)
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


테두리 표시 여부. false인 경우 Width 매개변수가 항상 무시됩니다(0). 기본값: false.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public Unit getWidth()
```


테두리 두께. 기본값: 0. Visible가 false로 설정된 경우 무시됩니다.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


테두리 색상. 기본값: Color.Black.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setDashStyle(BorderDashStyle value) {#setDashStyle-com.aspose.barcode.generation.BorderDashStyle-}
```
public void setDashStyle(BorderDashStyle value)
```


테두리 대시 스타일. 기본값: BorderDashStyle.Solid.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [BorderDashStyle](../../com.aspose.barcode.generation/borderdashstyle) |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


테두리 표시 여부. false인 경우 Width 매개변수가 항상 무시됩니다(0). 기본값: false.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setWidth(Unit value) {#setWidth-com.aspose.barcode.generation.Unit-}
```
public void setWidth(Unit value)
```


테두리 두께. 기본값: 0. Visible가 false로 설정된 경우 무시됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### toString() {#toString--}
```
public String toString()
```


이 BorderParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 BorderParameters를 나타내는 문자열.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

