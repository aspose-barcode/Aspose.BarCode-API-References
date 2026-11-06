---
title: "PrimaryData"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "HIBC LIC 기본 데이터를 저장하는 클래스."
type: docs
weight: 33
url: /ko/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

HIBC LIC 기본 데이터를 저장하는 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된  PrimaryData  값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | 라벨러 식별 코드의 날짜를 식별합니다. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | 제품 또는 카탈로그 번호를 식별합니다. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | 측정 단위 ID를 식별합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | HIBC LIC 사양에 따라 문자열 형식에서 기본 데이터를 인스턴스화합니다. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | 라벨러 식별 코드의 날짜를 식별합니다. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | 제품 또는 카탈로그 번호를 식별합니다. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | 측정 단위 ID를 식별합니다. |
| [toString()](#toString--) | HIBC LIC 사양에 따라 데이터를 문자열 형식으로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된  PrimaryData  값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할  PrimaryData  값. |

**Returns:**
boolean -  **true**  obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않으면 **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


라벨러 식별 코드의 날짜를 식별합니다. 라벨러 식별 코드는 4개의 알파벳·숫자 문자열이어야 하며, 첫 번째 문자는 항상 알파벳이어야 합니다.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


제품 또는 카탈로그 번호를 식별합니다. 제품 또는 카탈로그 번호는 최대 18자 길이의 알파벳·숫자 문자열이어야 합니다.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


측정 단위 ID를 식별합니다. 측정 단위 ID는 0부터 9까지의 정수 값이어야 합니다.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


HIBC LIC 사양에 따라 문자열 형식에서 기본 데이터를 인스턴스화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | 형식이 지정된 문자열. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


라벨러 식별 코드의 날짜를 식별합니다. 라벨러 식별 코드는 4개의 알파벳·숫자 문자열이어야 하며, 첫 번째 문자는 항상 알파벳이어야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


제품 또는 카탈로그 번호를 식별합니다. 제품 또는 카탈로그 번호는 최대 18자 길이의 알파벳·숫자 문자열이어야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


측정 단위 ID를 식별합니다. 측정 단위 ID는 0부터 9까지의 정수 값이어야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### toString() {#toString--}
```
public String toString()
```


HIBC LIC 사양에 따라 데이터를 문자열 형식으로 변환합니다.

**Returns:**
java.lang.String - 형식화된 문자열.
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

