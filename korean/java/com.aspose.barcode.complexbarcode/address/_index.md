---
title: "주소"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "채권자 또는 채무자의 주소."
type: docs
weight: 10
url: /ko/java/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

채권자 또는 채무자의 주소.

거리, 건물 번호, 우편 번호 및 도시를 설정하거나 (유형 *structured address*) 주소 라인 1과 2를 설정할 수 있습니다 (유형 *combined address elements*). 필드 중 하나가 설정되면 유형이 자동으로 지정됩니다. 필드를 설정하기 전에 주소 유형은 *undetermined* 입니다. 두 유형의 필드를 모두 설정하면 주소 유형이 *conflicting* 로 변경됩니다. 이름과 국가 코드는 모든 필드가 비어 있지 않은 한 항상 설정되어야 합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Address()](#Address--) | Address 인스턴스를 생성합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clear()](#clear--) | 모든 필드를 지우고 유형을 AddressType.Undetermined 로 설정합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 현재 객체와 같은지 여부를 결정합니다. |
| [getAddressLine1()](#getAddressLine1--) | 주소 라인 1을 가져옵니다. |
| [getAddressLine2()](#getAddressLine2--) | 주소 라인 2를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | 두 글자 ISO 국가 코드를 가져옵니다. |
| [getHouseNo()](#getHouseNo--) | 건물 번호를 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. 자연인의 경우 이름과 성, 법인인 경우 회사명을 의미합니다. |
| [getPostalCode()](#getPostalCode--) | 우편 번호를 가져옵니다. |
| [getStreet()](#getStreet--) | 거리명을 가져옵니다. |
| [getTown()](#getTown--) | 도시 또는 읍면을 가져옵니다. |
| [getType()](#getType--) | 주소 유형을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | 주소 라인 1을 설정합니다. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | 주소 라인 2를 설정합니다. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | 두 글자 ISO 국가 코드를 설정합니다. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | 건물 번호를 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 자연인의 이름(이름과 성) 또는 법인의 회사명을 설정합니다. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | 우편 번호를 설정합니다. |
| [setStreet(String value)](#setStreet-java.lang.String-) | 거리명을 설정합니다. |
| [setTown(String value)](#setTown-java.lang.String-) | 도시 또는 시를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Address 인스턴스를 생성합니다

### clear() {#clear--}
```
public void clear()
```


모든 필드를 지우고 유형을 AddressType.Undetermined 로 설정합니다.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가 현재 객체와 같은지 여부를 결정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 현재 객체와 비교할 객체. |

**Returns:**
boolean -  true  지정된 객체가 현재 객체와 같으면; 그렇지 않으면  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


주소 라인 1을 가져옵니다.

주소 라인 1에는 거리명, 건물 번호 또는 사서함이 포함됩니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.Structured  가 아닌 경우  AddressType.CombinedElements  로 설정되고, 이미  AddressType.Structured  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 결합 요소 주소에만 사용되며 선택 사항입니다.

값: 주소 라인 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


주소 라인 2를 가져옵니다.

주소 라인 2에는 우편 번호와 도시가 포함됩니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.Structured  가 아닌 경우  AddressType.CombinedElements  로 설정되고, 이미  AddressType.Structured  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 결합 요소 주소에만 사용됩니다. 이 유형에서는 필수입니다.

값: 주소 라인 2.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


두 글자 ISO 국가 코드를 가져옵니다.

전체 주소에  null  또는  emtpy  값이 포함되지 않는 한 국가 코드는 필수입니다.

값: ISO 국가 코드.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


건물 번호를 가져옵니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.CombinedElements  가 아닌 경우  AddressType.Structured  로 설정되고, 이미  AddressType.CombinedElements  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.

값: 건물 번호.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다. 자연인의 경우 이름과 성, 법인인 경우 회사명을 의미합니다.

값: 이름.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


우편 번호를 가져옵니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.CombinedElements  가 아닌 경우  AddressType.Structured  로 설정되고, 이미  AddressType.CombinedElements  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 구조화된 주소에만 사용됩니다. 이 유형에서는 필수입니다.

값: 우편 번호.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


거리명을 가져옵니다.

거리명은 건물 번호 없이 지정해야 합니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.CombinedElements  가 아닌 경우  AddressType.Structured  로 설정되고, 이미  AddressType.CombinedElements  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.

값: 거리.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


도시 또는 읍면을 가져옵니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.CombinedElements  가 아닌 경우  AddressType.Structured  로 설정되고, 이미  AddressType.CombinedElements  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 구조화된 주소에만 사용됩니다. 이 유형에서는 필수입니다.

값: 마을 또는 도시.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


주소 유형을 가져옵니다.

주소 유형은 거리/건물 번호를 설정하거나 주소 라인 1 및 2를 설정함으로써 자동으로 지정됩니다. 필드를 설정하기 전에 주소 유형은 *Undetermined* 입니다. 두 유형의 필드가 모두 설정되면 주소 유형은 *Conflicting* 이 됩니다.

값: 주소 유형.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 가져옵니다.

**Returns:**
int - 현재 객체에 대한 해시 코드.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


주소 라인 1을 설정합니다.

주소 라인 1에는 거리명, 건물 번호 또는 사서함이 포함됩니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.Structured  가 아닌 경우  AddressType.CombinedElements  로 설정되고, 이미  AddressType.Structured  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 결합 요소 주소에만 사용되며 선택 사항입니다.

값: 주소 라인 1.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


주소 라인 2를 설정합니다.

주소 라인 2에는 우편 번호와 도시가 포함됩니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.Structured  가 아닌 경우  AddressType.CombinedElements  로 설정되고, 이미  AddressType.Structured  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 결합 요소 주소에만 사용됩니다. 이 유형에서는 필수입니다.

값: 주소 라인 2.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


두 글자 ISO 국가 코드를 설정합니다.

전체 주소에  null  또는  emtpy  값이 포함되지 않는 한 국가 코드는 필수입니다.

값: ISO 국가 코드.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


건물 번호를 설정합니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.CombinedElements  가 아닌 경우  AddressType.Structured  로 설정되고, 이미  AddressType.CombinedElements  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.

값: 건물 번호.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


자연인의 이름(이름과 성) 또는 법인의 회사명을 설정합니다.

값: 이름.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


우편 번호를 설정합니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.CombinedElements  가 아닌 경우  AddressType.Structured  로 설정되고, 이미  AddressType.CombinedElements  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 구조화된 주소에만 사용됩니다. 이 유형에서는 필수입니다.

값: 우편 번호.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


거리명을 설정합니다.

거리명은 건물 번호 없이 지정해야 합니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.CombinedElements  가 아닌 경우  AddressType.Structured  로 설정되고, 이미  AddressType.CombinedElements  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.

값: 거리.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


도시 또는 시를 설정합니다.

이 필드를 설정하면 주소 유형이 이미  AddressType.CombinedElements  가 아닌 경우  AddressType.Structured  로 설정되고, 이미  AddressType.CombinedElements  인 경우  AddressType.Conflicting  로 변경됩니다.

이 필드는 구조화된 주소에만 사용됩니다. 이 유형에서는 필수입니다.

값: 마을 또는 도시.

**Parameters:**
| 매개변수 | 유형 | 설명 |
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

