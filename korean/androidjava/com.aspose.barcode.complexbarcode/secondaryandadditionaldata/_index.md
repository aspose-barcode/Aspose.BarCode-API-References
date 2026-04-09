---
title: SecondaryAndAdditionalData
second_title: Aspose.BarCode for Android via Java API Reference
description: HIBC LIC 보조 및 추가 데이터를 저장하기 위한 클래스.
type: docs
weight: 35
url: /ko/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

HIBC LIC 보조 및 추가 데이터를 저장하기 위한 클래스.
## Constructors

| Constructor | 설명 |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 SecondaryAndAdditionalData 값과 동일한지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | 제조 날짜를 식별합니다. |
| [getExpiryDate()](#getExpiryDate--) | 만료 날짜를 식별합니다. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | 만료 날짜 형식을 식별합니다. |
| [getLotNumber()](#getLotNumber--) | LOT 또는 배치 번호를 식별합니다. |
| [getQuantity()](#getQuantity--) | 수량을 식별합니다. 0부터 500까지의 정수값이어야 합니다. |
| [getSerialNumber()](#getSerialNumber--) | 시리얼 번호를 식별합니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | HIBC LIC 사양에 따라 문자열 형식에서 보조 및 추가 보충 데이터를 인스턴스화합니다. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | 제조 날짜를 식별합니다. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | 만료 날짜를 식별합니다. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | 만료 날짜 형식을 식별합니다. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | LOT 또는 배치 번호를 식별합니다. |
| [setQuantity(int value)](#setQuantity-int-) | 수량을 식별합니다. 0부터 500까지의 정수값이어야 합니다. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | 시리얼 번호를 식별합니다. |
| [toString()](#toString--) | 데이터를 HIBC LIC 사양에 따라 문자열 형식으로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 SecondaryAndAdditionalData 값과 동일한지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 SecondaryAndAdditionalData 값. |

**Returns:**
boolean -  **true**  if obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않은 경우 **false**.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


제조 날짜를 식별합니다. 이 필드를 사용하지 않으려면 제조 날짜를 DateTime.MinValue 로 설정할 수 있습니다. 기본값: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우 사용됩니다.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


만료 날짜 형식을 식별합니다.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


LOT 또는 배치 번호를 식별합니다. LOT/배치 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다.

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


수량을 식별합니다. 0부터 500까지의 정수값이어야 합니다. 이 필드를 사용하지 않으려면 수량을 -1 로 설정할 수 있습니다. 기본값: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


시리얼 번호를 식별합니다. 시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드입니다.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


HIBC LIC 사양에 따라 문자열 형식에서 보조 및 추가 보충 데이터를 인스턴스화합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | 포맷된 문자열. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


제조 날짜를 식별합니다. 이 필드를 사용하지 않으려면 제조 날짜를 DateTime.MinValue 로 설정할 수 있습니다. 기본값: DateTime.MinValue

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우 사용됩니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


만료 날짜 형식을 식별합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


LOT 또는 배치 번호를 식별합니다. LOT/배치 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


수량을 식별합니다. 0부터 500까지의 정수값이어야 합니다. 이 필드를 사용하지 않으려면 수량을 -1 로 설정할 수 있습니다. 기본값: -1

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


시리얼 번호를 식별합니다. 시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


데이터를 HIBC LIC 사양에 따라 문자열 형식으로 변환합니다.

**Returns:**
java.lang.String - 포맷된 문자열.
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

