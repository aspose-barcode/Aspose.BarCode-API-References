---
title: "CMYKColor"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "CMYK 색상에 대한 클래스."
type: docs
weight: 19
url: /ko/androidjava/com.aspose.barcode.generation/cmykcolor/
---
**Inheritance:**
java.lang.Object
```
public class CMYKColor
```

CMYK 색상을 위한 클래스입니다. Null은 CMYK가 사용되지 않음을 의미하며, 기본 RGB 색상이 사용됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CMYKColor(int c, int m, int y, int k)](#CMYKColor-int-int-int-int-) | CMYK 값을 사용하여  CMYKColor  클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [C](#C) |  |
| [K](#K) |  |
| [M](#M) |  |
| [Y](#Y) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 색상 값이 동일한지 비교합니다. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | CMYKColor의 해시 코드 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CMYKColor(int c, int m, int y, int k) {#CMYKColor-int-int-int-int-}
```
public CMYKColor(int c, int m, int y, int k)
```


CMYK 값을 사용하여  CMYKColor  클래스의 새 인스턴스를 초기화합니다. CMYK 값은 0-100입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | int | 시안 값 [0, 100] |
| m | int | 마젠타 값 [0, 100] |
| y | int | 노란색 값 [0, 100] |
| k | int | 검은색 값 [0, 100] |

### C {#C}
```
public float C
```


### K {#K}
```
public float K
```


### M {#M}
```
public float M
```


### Y {#Y}
```
public float Y
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


색상 값이 동일한지 비교합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 CMYKColor |

**Returns:**
boolean - 값이 동일한가요
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


CMYKColor의 해시 코드

**Returns:**
int - CMYKColor의 해시 코드
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

