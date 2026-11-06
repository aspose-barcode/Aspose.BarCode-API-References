---
title: "HanXinModes"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "Han Xin Code 인코딩 모드."
type: docs
weight: 90
url: /ko/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code 인코딩 모드. ASCII/중국어 문자 또는 Unicode 문자에 대해 Auto를 사용하는 것이 권장됩니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [AUTO](#AUTO) | Numeric, Text, ECI, Binary Bytes 및 4 GB18030 모드가 자동으로 변경되는 순서. |
| [BINARY](#BINARY) | Binary byte 모드는 모든 형태의 바이너리 데이터를 인코딩하고 해당 바이너리 바이트로 인코딩합니다. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Region One의 모든 일반 중국어 문자는 12비트로 표현됩니다. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Region Two의 모든 일반 중국어 문자는 12비트로 표현됩니다. |
| [ECI](#ECI) | Extended Channel Interpretation (ECI) 모드 |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | GB18030 4바이트 Region 문자는 21비트로 표현됩니다. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | GB18030 2바이트 Region 문자는 15비트로 표현됩니다. |
| [GS_1](#GS-1) | GS1 모드는 Han Xin Code에 표시된 데이터가 GS1 일반 사양에 정의된 GS1 시스템의 GS1 데이터임을 나타냅니다. |
| [NUMERIC](#NUMERIC) | Numeric 모드는 10진 숫자 집합(0-9 숫자, 30HEX~39HEX 바이트 값)에서 데이터를 인코딩합니다. |
| [TEXT](#TEXT) | Text 모드는 ISO/IEC 646에 정의된 일반 기호에서 데이터를 인코딩합니다, 예를 들어. |
| [UNICODE](#UNICODE) | Unicode 모드는 Han Xin Code에서 UTF8 인코딩/문자 집합을 참조하는 모든 텍스트 데이터를 표현하는 방법을 설계합니다. |
| [URI](#URI) | URI 모드는 Han Xin Code에 표시된 데이터가 RFC 3986에 대한 Uniform Resource Identifier (URI) 참조임을 나타냅니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final HanXinModes AUTO
```


Numeric, Text, ECI, Binary Bytes 및 4 GB18030 모드가 자동으로 변경되는 순서.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Binary byte 모드는 모든 형태의 바이너리 데이터를 인코딩하고 해당 바이너리 바이트로 인코딩합니다. Binary Byte 모드의 모든 바이트는 8비트로 표현됩니다.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Region One의 모든 일반 중국어 문자는 12비트로 표현됩니다. Region One의 일반 중국어 문자에는 첫 번째 바이트 값이 B0HEX에서 D7HEX 범위에 있고 두 번째 바이트 값이 A1HEX에서 FEHEX 범위에 있는 문자(3760자)와 첫 번째 바이트 값이 A1HEX에서 A3HEX 범위에 있고 두 번째 바이트 값이 A1HEX에서 FEHEX 범위에 있는 문자(282자), 그리고 바이트 값이 A8A1HEX에서 A8C0HEX 범위에 있는 문자(32자)가 포함됩니다.

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Region Two의 모든 일반 중국어 문자는 12비트로 표현됩니다. Region Two의 일반 중국어 문자에는 첫 번째 바이트 값이 D8HEX에서 F7HEX 범위에 있고 두 번째 바이트 값이 A1HEX에서 FEHEX 범위에 있는 문자가 포함됩니다.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Extended Channel Interpretation (ECI) 모드

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


GB18030 4바이트 영역의 모든 문자는 21비트로 표현됩니다. GB18030 4바이트 영역은 GB18030 4바이트 영역에 있는 모든 문자(예: 첫 번째 바이트 값이 81HEX에서 FEHEX 범위, 두 번째 바이트 값이 30HEX에서 39HEX 범위, 세 번째 바이트 값이 81HEX에서 FEHEX 범위, 네 번째 바이트 값이 30HEX에서 39HEX 범위에 있는 문자)의 데이터를 인코딩합니다.

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


GB18030 2바이트 영역의 모든 문자는 15비트로 표현됩니다. GB18030 2바이트 영역은 GB18030 이중 바이트 영역에 있는 모든 문자(Region One 및 Region Two의 일반 중국어 문자 포함)를 인코딩합니다(예: 첫 번째 바이트 값이 81HEX에서 FEHEX 범위이고 두 번째 바이트 값이 40HEX에서 7EHEX 또는 80HEX에서 FEHEX 범위에 있는 중국어 문자).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1 모드는 Han Xin Code에 표시된 데이터가 GS1 일반 사양에 의해 정의된 GS1 시스템의 GS1 데이터임을 나타냅니다. 입력 문자열 예시: "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Numeric 모드는 10진 숫자 집합(숫자 0-9, 바이트 값 30HEX에서 39HEX)에서 데이터를 인코딩합니다. 일반적으로 3개의 데이터 문자는 10비트로 표현됩니다.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Text 모드는 ISO/IEC 646에 정의된 일반 기호(바이트 값 00HEX에서 1BHEX 및 20HEX에서 7FHEX)에서 데이터를 인코딩합니다.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode 모드는 Han Xin Code에서 UTF8 인코딩/문자 집합을 참조하는 모든 텍스트 데이터를 표현하는 방법을 설계합니다.

### URI {#URI}
```
public static final HanXinModes URI
```


URI 모드는 Han Xin Code에 표시된 데이터가 RFC 3986에 대한 Uniform Resource Identifier (URI) 참조임을 나타냅니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static HanXinModes fromValue(int value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static HanXinModes valueOf(String name)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
### values() {#values--}
```
public static HanXinModes[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinModes[]
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

