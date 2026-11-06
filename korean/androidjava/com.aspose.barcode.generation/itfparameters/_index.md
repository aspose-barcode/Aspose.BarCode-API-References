---
title: "ITFParameters"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "ITF 매개변수."
type: docs
weight: 50
url: /ko/androidjava/com.aspose.barcode.generation/itfparameters/
---
**Inheritance:**
java.lang.Object
```
public class ITFParameters
```

ITF 매개변수.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBorderThickness()](#getBorderThickness--) | ITF 테두리(베어러 바)의 두께를 Unit 값으로 가져옵니다. |
| [getBorderType()](#getBorderType--) | ITF 바코드의 테두리 유형. |
| [getClass()](#getClass--) |  |
| [getQuietZoneCoef()](#getQuietZoneCoef--) | xDimension에서 정지 구역의 크기. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBorderThickness(Unit value)](#setBorderThickness-com.aspose.barcode.generation.Unit-) | ITF 테두리(베어러 바)의 두께를 Unit 값으로 설정합니다. |
| [setBorderType(ITF14BorderType value)](#setBorderType-com.aspose.barcode.generation.ITF14BorderType-) | ITF 바코드의 테두리 유형. |
| [setQuietZoneCoef(int value)](#setQuietZoneCoef-int-) | xDimension에서 정지 구역의 크기. |
| [toString()](#toString--) | 이 [ITFParameters](../../com.aspose.barcode.generation/itfparameters)의 사람 친화적인 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBorderThickness() {#getBorderThickness--}
```
public final Unit getBorderThickness()
```


ITF 테두리(베어러 바)의 두께를 Unit 값으로 가져옵니다. 기본값: 12pt.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - an ITF border (bearer bar) thickness in Unit value.
### getBorderType() {#getBorderType--}
```
public final ITF14BorderType getBorderType()
```


ITF 바코드의 테두리 유형. 기본값: ITF14BorderType.Bar.

**Returns:**
[ITF14BorderType](../../com.aspose.barcode.generation/itf14bordertype)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getQuietZoneCoef() {#getQuietZoneCoef--}
```
public final int getQuietZoneCoef()
```


xDimension에서 정지 구역의 크기. 기본값: 10, 즉 xDimension = 2px이면 정지 구역은 20px이 됩니다.

**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
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




### setBorderThickness(Unit value) {#setBorderThickness-com.aspose.barcode.generation.Unit-}
```
public final void setBorderThickness(Unit value)
```


ITF 테두리(베어러 바)의 두께를 Unit 값으로 설정합니다. 기본값: 12pt.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | ITF 테두리(베어러 바)의 두께(Unit 값). |

### setBorderType(ITF14BorderType value) {#setBorderType-com.aspose.barcode.generation.ITF14BorderType-}
```
public final void setBorderType(ITF14BorderType value)
```


ITF 바코드의 테두리 유형. 기본값: ITF14BorderType.Bar.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ITF14BorderType](../../com.aspose.barcode.generation/itf14bordertype) |  |

### setQuietZoneCoef(int value) {#setQuietZoneCoef-int-}
```
public final void setQuietZoneCoef(int value)
```


xDimension에서 정지 구역의 크기. 기본값: 10, 즉 xDimension = 2px이면 정지 구역은 20px이 됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### toString() {#toString--}
```
public String toString()
```


이 [ITFParameters](../../com.aspose.barcode.generation/itfparameters)의 사람 친화적인 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [ITFParameters](../../com.aspose.barcode.generation/itfparameters)를 나타내는 문자열.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

