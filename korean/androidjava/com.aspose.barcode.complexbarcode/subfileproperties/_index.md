---
title: USADriveIdCodetext.SubfileProperties
second_title: Aspose.BarCode for Android via Java API Reference
description: USA DL 서브파일 속성의 오프셋과 길이가 자동으로 설정됩니다.
type: docs
weight: 12
url: /ko/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

USA DL 하위 파일 속성, 오프셋 및 길이가 자동으로 설정됩니다.
## Constructors

| Constructor | 설명 |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 이 바이트는 서브파일의 길이를 바이트 단위로 지정하는 4자리 숫자 값을 포함합니다. 세그먼트 종결자는 서브파일 길이를 계산할 때 포함되어야 합니다. 세그먼트 종결자 = 1. |
| [getOffset()](#getOffset--) | 4자리 숫자 값은 파일의 시작(헤드)부터 특정 서브파일과 관련된 데이터가 위치한 바이트 수를 지정합니다. 파일의 첫 번째 바이트는 오프셋 0에 위치합니다. |
| [getType()](#getType--) | 예: "DL"와 같은 2바이트 서브파일 유형 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 이 바이트는 서브파일의 길이를 바이트 단위로 지정하는 4자리 숫자 값을 포함합니다. 세그먼트 종결자는 서브파일 길이를 계산할 때 포함되어야 합니다. 세그먼트 종결자 = 1. |
| [setOffset(int value)](#setOffset-int-) | 4자리 숫자 값은 파일의 시작(헤드)부터 특정 서브파일과 관련된 데이터가 위치한 바이트 수를 지정합니다. 파일의 첫 번째 바이트는 오프셋 0에 위치합니다. |
| [setType(String value)](#setType-java.lang.String-) | 예: "DL"와 같은 2바이트 서브파일 유형 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 유형 | java.lang.String |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
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
### getLength() {#getLength--}
```
public final int getLength()
```


4 이 바이트는 서브파일의 길이를 바이트 단위로 지정하는 4자리 숫자 값을 포함합니다. 세그먼트 종결자는 서브파일 길이를 계산할 때 포함되어야 합니다. 세그먼트 종결자 = 1. 각 서브파일은 두 문자로 된 서브파일 유형으로 시작해야 하며, 이 두 문자는 길이에 포함되어야 합니다.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4자리 숫자 값은 파일의 시작(헤드)부터 특정 서브파일과 관련된 데이터가 위치한 바이트 수를 지정합니다. 파일의 첫 번째 바이트는 오프셋 0에 위치합니다.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


예: "DL"와 같은 2바이트 서브파일 유형

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
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




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 이 바이트는 서브파일의 길이를 바이트 단위로 지정하는 4자리 숫자 값을 포함합니다. 세그먼트 종결자는 서브파일 길이를 계산할 때 포함되어야 합니다. 세그먼트 종결자 = 1. 각 서브파일은 두 문자로 된 서브파일 유형으로 시작해야 하며, 이 두 문자는 길이에 포함되어야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4자리 숫자 값은 파일의 시작(헤드)부터 특정 서브파일과 관련된 데이터가 위치한 바이트 수를 지정합니다. 파일의 첫 번째 바이트는 오프셋 0에 위치합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


예: "DL"와 같은 2바이트 서브파일 유형

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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

