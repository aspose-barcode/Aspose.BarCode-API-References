---
title: "Unit"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "픽셀, 인치 등 다양한 단위로 크기 값을 지정합니다."
type: docs
weight: 67
url: /ko/java/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

다양한 단위(픽셀, 인치 등)로 크기 값을 지정합니다.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스와 지정된 객체(또한 Unit 객체여야 함)가 동일한 값을 갖는지 여부를 결정합니다. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | 문서 단위로 크기 값을 가져옵니다. |
| [getInches()](#getInches--) | 인치 단위로 크기 값을 가져옵니다. |
| [getMillimeters()](#getMillimeters--) | 밀리미터 단위로 크기 값을 가져옵니다. |
| [getPixels()](#getPixels--) | 픽셀 단위로 크기 값을 가져옵니다. |
| [getPoint()](#getPoint--) | 포인트 단위로 크기 값을 가져옵니다. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | 이 객체의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | 문서 단위로 크기 값을 설정합니다. |
| [setInches(float value)](#setInches-float-) | 인치 단위로 크기 값을 설정합니다. |
| [setMillimeters(float value)](#setMillimeters-float-) | 밀리미터 단위로 크기 값을 설정합니다. |
| [setPixels(float value)](#setPixels-float-) | 픽셀 단위로 크기 값을 설정합니다. |
| [setPoint(float value)](#setPoint-float-) | 포인트 단위로 크기 값을 설정합니다. |
| [toString()](#toString--) | 이 Unit의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스와 지정된 객체(또한 Unit 객체여야 함)가 동일한 값을 갖는지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 Unit. |

**Returns:**
boolean - obj가 Unit이며 그 값이 이 인스턴스와 동일하면 true; 그렇지 않으면 false. obj가 null이면 메서드는 false를 반환합니다.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


문서 단위로 크기 값을 가져옵니다.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


인치 단위로 크기 값을 가져옵니다.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


밀리미터 단위로 크기 값을 가져옵니다.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


픽셀 단위로 크기 값을 가져옵니다.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


포인트 단위로 크기 값을 가져옵니다.

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 객체의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


문서 단위로 크기 값을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


인치 단위로 크기 값을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


밀리미터 단위로 크기 값을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


픽셀 단위로 크기 값을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


포인트 단위로 크기 값을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### toString() {#toString--}
```
public String toString()
```


이 Unit의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 Unit을 나타내는 문자열.
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| dpi | float |  |

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

