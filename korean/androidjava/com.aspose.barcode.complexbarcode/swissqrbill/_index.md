---
title: SwissQRBill
second_title: Aspose.BarCode for Android via Java API Reference
description: SwissQR 청구서 데이터
type: docs
weight: 36
url: /ko/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

SwissQR 청구서 데이터
## Methods

| Method | 설명 |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | 원시 문자열에 "RF"를 접두사로 붙이고 modulo 97 체크섬을 적용하여 ISO11649 채권자 참조를 생성하고 설정합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 객체가 현재 객체와 같은지 여부를 결정합니다. |
| [getAccount()](#getAccount--) | 채권자의 계좌 번호를 가져옵니다. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | 대체 결제 방식(들을) 가져오거나 설정합니다. |
| [getAmount()](#getAmount--) | 결제 금액을 가져옵니다. |
| [getBillInformation()](#getBillInformation--) | 추가 구조화된 청구서 정보를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | 채권자 주소를 가져옵니다. |
| [getCurrency()](#getCurrency--) | 결제 통화를 가져옵니다. |
| [getDebtor()](#getDebtor--) | 채무자 주소를 가져옵니다. |
| [getReference()](#getReference--) | 채권자 결제 참조를 가져옵니다. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | 추가 비구조화 메시지를 가져옵니다. |
| [getVersion()](#getVersion--) | SwissQR 청구서 표준 버전을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | 채권자 계좌 번호를 설정합니다. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | 대체 결제 방식(들을) 가져오거나 설정합니다. |
| [setAmount(double value)](#setAmount-double-) | 결제 금액을 설정합니다. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | 추가 구조화된 청구서 정보를 설정합니다. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | 채권자 주소를 설정합니다. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | 결제 통화를 설정합니다. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | 채무자 주소를 설정합니다. |
| [setReference(String value)](#setReference-java.lang.String-) | 채권자 결제 참조를 설정합니다. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | 추가 비구조화 메시지를 설정합니다. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | SwissQR 청구서 표준 버전을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


원시 문자열에 "RF"를 접두사로 붙이고 modulo 97 체크섬을 적용하여 ISO11649 채권자 참조를 생성하고 설정합니다.

참조에서 공백이 제거됩니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| rawReference | java.lang.String | 원시 참조입니다. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 객체가 현재 객체와 같은지 여부를 결정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 현재 객체와 비교할 객체. |

**Returns:**
boolean - 지정된 객체가 현재 객체와 같으면  true , 그렇지 않으면  false .
### getAccount() {#getAccount--}
```
public String getAccount()
```


채권자의 계좌 번호를 가져옵니다.

계좌 번호는 스위스 또는 리히텐슈타인 은행의 유효한 IBAN이어야 합니다. 계좌 번호에 공백을 포함할 수 있습니다.

값: 채권자 계좌 번호.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


대체 결제 방식(들을) 가져오거나 설정합니다.

매개변수가 있는 최대 두 개의 방식만 허용됩니다.

값: 대체 결제 방식.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


결제 금액을 가져옵니다.

유효한 값은 0.01에서 999,999,999.99 사이입니다.

값: 결제 금액.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


추가 구조화된 청구서 정보를 가져옵니다.

값: 구조화된 청구서 정보.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreditor() {#getCreditor--}
```
public Address getCreditor()
```


채권자 주소를 가져옵니다.

값: 채권자 주소.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


결제 통화를 가져옵니다.

유효한 값은 "CHF"와 "EUR"입니다.

값: 결제 통화.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


채무자 주소를 가져옵니다.

채무자는 선택 사항입니다. 생략할 경우, 이 필드를  null  로 설정하거나 모든 값이  null  이거나 비어 있는 주소를 설정하는 것이 허용됩니다.

값: 채무자 주소.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


채권자 결제 참조를 가져옵니다.

SwissQR IBAN에 대해 참조는 필수이며, 예를 들어 CHxx30000xxxxxx에서 CHxx31999xxxxx 범위의 IBAN이 해당됩니다.

지정된 경우, 참조는 유효한 SwissQR 참조( ISR 참조 양식에 해당) 또는 ISO 11649에 따른 유효한 채권자 참조("RFxxxx") 중 하나여야 합니다. 두 경우 모두 서식을 위해 공백을 포함할 수 있습니다.

값: 채권자 결제 참조.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


추가 비구조화 메시지를 가져옵니다.

값: 비구조화된 메시지.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


SwissQR 청구서 표준 버전을 가져옵니다.

값: SwissQR 청구서 표준 버전.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 가져옵니다.

**Returns:**
int - 현재 객체의 해시 코드.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAccount(String value) {#setAccount-java.lang.String-}
```
public void setAccount(String value)
```


채권자 계좌 번호를 설정합니다.

계좌 번호는 스위스 또는 리히텐슈타인 은행의 유효한 IBAN이어야 합니다. 계좌 번호에 공백을 포함할 수 있습니다.

값: 채권자 계좌 번호.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


대체 결제 방식(들을) 가져오거나 설정합니다.

매개변수가 있는 최대 두 개의 방식만 허용됩니다.

값: 대체 결제 방식.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


결제 금액을 설정합니다.

유효한 값은 0.01에서 999,999,999.99 사이입니다.

값: 결제 금액.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


추가 구조화된 청구서 정보를 설정합니다.

값: 구조화된 청구서 정보.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


채권자 주소를 설정합니다.

값: 채권자 주소.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


결제 통화를 설정합니다.

유효한 값은 "CHF"와 "EUR"입니다.

값: 결제 통화.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


채무자 주소를 설정합니다.

채무자는 선택 사항입니다. 생략할 경우, 이 필드를  null  로 설정하거나 모든 값이  null  이거나 비어 있는 주소를 설정하는 것이 허용됩니다.

값: 채무자 주소.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


채권자 결제 참조를 설정합니다.

SwissQR IBAN에 대해 참조는 필수이며, 예를 들어 CHxx30000xxxxxx에서 CHxx31999xxxxx 범위의 IBAN이 해당됩니다.

지정된 경우, 참조는 유효한 SwissQR 참조( ISR 참조 양식에 해당) 또는 ISO 11649에 따른 유효한 채권자 참조("RFxxxx") 중 하나여야 합니다. 두 경우 모두 서식을 위해 공백을 포함할 수 있습니다.

값: 채권자 결제 참조.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


추가 비구조화 메시지를 설정합니다.

값: 비구조화된 메시지.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


SwissQR 청구서 표준 버전을 설정합니다.

값: SwissQR 청구서 표준 버전.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion) |  |

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

