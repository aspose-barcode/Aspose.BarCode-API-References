---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "4단계 Royal Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스."
type: docs
weight: 24
url: /ko/java/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

4단계 Royal Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | MailmarkCodetext 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | 바코드 유형을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | \"0\" - Null 또는 테스트 \"1\" - 1C (소매) \"2\" - 2C (소매) \"3\" - 3C (소매) \"4\" - Premium (RetailPublishing Mail) (잠재적 향후 사용) \"5\" - Deferred (소매) \"6\" - Air (소매) (잠재적 향후 사용) \"7\" - Surface (소매) (잠재적 향후 사용) \"8\" - Premium (네트워크 액세스) \"9\" - Standard (네트워크 액세스) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Mailmark 데이터에서 코드텍스트를 구성합니다. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | PC와 DP는 PAF 형식을 준수해야 합니다. |
| [getFormat()](#getFormat--) | \"0\" \\u2013 Null 또는 테스트 \"1\" \\u2013 편지 \"2\" \\u2013 대형 편지 |
| [getItemID()](#getItemID--) | 최대값은 99999999입니다. |
| [getSupplychainID()](#getSupplychainID--) | Barcode C의 최대값은 99이며 Barcode L의 최대값은 999999입니다. |
| [getVersionID()](#getVersionID--) | 현재 "1" \\u2013 Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 남겨 둠) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 구성된 코드텍스트에서 Mailmark 데이터를 초기화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | \"0\" - Null 또는 테스트 \"1\" - 1C (소매) \"2\" - 2C (소매) \"3\" - 3C (소매) \"4\" - Premium (RetailPublishing Mail) (잠재적 향후 사용) \"5\" - Deferred (소매) \"6\" - Air (소매) (잠재적 향후 사용) \"7\" - Surface (소매) (잠재적 향후 사용) \"8\" - Premium (네트워크 액세스) \"9\" - Standard (네트워크 액세스) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | PC와 DP는 PAF 형식을 준수해야 합니다. |
| [setFormat(int value)](#setFormat-int-) | \"0\" \\u2013 Null 또는 테스트 \"1\" \\u2013 편지 \"2\" \\u2013 대형 편지 |
| [setItemID(int value)](#setItemID-int-) | 최대값은 99999999입니다. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Barcode C의 최대값은 99이며 Barcode L의 최대값은 999999입니다. |
| [setVersionID(int value)](#setVersionID-int-) | 현재 "1" \\u2013 Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 남겨 둠) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


MailmarkCodetext 클래스의 새 인스턴스를 초기화합니다.

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


바코드 유형을 가져옵니다.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


\"0\" - Null 또는 테스트 \"1\" - 1C (소매) \"2\" - 2C (소매) \"3\" - 3C (소매) \"4\" - Premium (RetailPublishing Mail) (잠재적 향후 사용) \"5\" - Deferred (소매) \"6\" - Air (소매) (잠재적 향후 사용) \"7\" - Surface (소매) (잠재적 향후 사용) \"8\" - Premium (네트워크 액세스) \"9\" - Standard (네트워크 액세스)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Mailmark 데이터에서 코드텍스트를 구성합니다.

**Returns:**
java.lang.String - 구성된 코드 텍스트
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


PC와 DP는 PAF 형식을 따라야 합니다. 국제 "XY11 "(뒤에 5개의 공백 포함)를 나타내는 9자 문자열 또는 국내 정렬 코드를 나타내는 문자 패턴 중 하나입니다. 국내 정렬 코드는 외부 우편번호, 내부 우편번호 및 배달 지점 접미사로 구성됩니다.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


\"0\" \\u2013 Null 또는 테스트 \"1\" \\u2013 편지 \"2\" \\u2013 대형 편지

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


최대값은 99999999입니다.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Barcode C의 최대값은 99이며 Barcode L의 최대값은 999999입니다.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


현재 "1" \\u2013 Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 남겨 둠)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


구성된 코드텍스트에서 Mailmark 데이터를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 구성된 코드 텍스트. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


\"0\" - Null 또는 테스트 \"1\" - 1C (소매) \"2\" - 2C (소매) \"3\" - 3C (소매) \"4\" - Premium (RetailPublishing Mail) (잠재적 향후 사용) \"5\" - Deferred (소매) \"6\" - Air (소매) (잠재적 향후 사용) \"7\" - Surface (소매) (잠재적 향후 사용) \"8\" - Premium (네트워크 액세스) \"9\" - Standard (네트워크 액세스)

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


PC와 DP는 PAF 형식을 따라야 합니다. 국제 "XY11 "(뒤에 5개의 공백 포함)를 나타내는 9자 문자열 또는 국내 정렬 코드를 나타내는 문자 패턴 중 하나입니다. 국내 정렬 코드는 외부 우편번호, 내부 우편번호 및 배달 지점 접미사로 구성됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


\"0\" \\u2013 Null 또는 테스트 \"1\" \\u2013 편지 \"2\" \\u2013 대형 편지

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


최대값은 99999999입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Barcode C의 최대값은 99이며 Barcode L의 최대값은 999999입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


현재 "1" \\u2013 Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 남겨 둠)

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

