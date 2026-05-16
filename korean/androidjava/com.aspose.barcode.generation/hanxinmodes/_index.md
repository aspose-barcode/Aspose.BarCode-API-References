---
title: HanXinModes
second_title: Aspose.BarCode for Android via Java API Reference
description: Han Xin Code 인코딩 모드.
type: docs
weight: 91
url: /ko/androidjava/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

Han Xin Code 인코딩 모드입니다. ASCII/중국어 문자 또는 Unicode 문자를 사용할 경우 Auto를 사용하는 것이 권장됩니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [AUTO](#AUTO) | Numeric, Text, ECI, Binary Bytes 및 4 GB18030 모드가 자동으로 전환되는 시퀀스입니다. |
| [BINARY](#BINARY) | Binary byte 모드는 모든 형태의 바이너리 데이터를 인코딩하고 이를 바이너리 바이트로 인코딩합니다. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | Region One에 있는 모든 일반 중국어 문자는 12비트로 표현됩니다. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | Region Two에 있는 모든 일반 중국어 문자는 12비트로 표현됩니다. |
| [ECI](#ECI) | Extended Channel Interpretation (ECI) 모드 |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | GB18030 4바이트 영역 문자는 모두 21비트로 표현됩니다. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | GB18030 2바이트 영역 문자는 모두 15비트로 표현됩니다. |
| [GS_1](#GS-1) | GS1 모드는 Han Xin Code에 표시된 데이터가 GS1 일반 사양에 의해 정의된 GS1 시스템의 GS1 데이터임을 나타냅니다. |
| [NUMERIC](#NUMERIC) | Numeric 모드는 10진 숫자 집합(0-9, 바이트 값 30HEX~39HEX)에서 데이터를 인코딩합니다. |
| [TEXT](#TEXT) | Text 모드는 ISO/IEC 646에 정의된 일반 기호(예: )에서 데이터를 인코딩합니다. |
| [UNICODE](#UNICODE) | Unicode 모드는 Han Xin Code에서 UTF8 인코딩/문자 집합을 참조하는 모든 텍스트 데이터를 표현하는 방식을 설계합니다. |
| [URI](#URI) | URI 모드는 Han Xin Code에 표시된 데이터가 RFC 3986에 정의된 Uniform Resource Identifier (URI)임을 나타냅니다. |
## Methods

| Method | 설명 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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


Numeric, Text, ECI, Binary Bytes 및 4 GB18030 모드가 자동으로 전환되는 시퀀스입니다.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


Binary byte 모드는 모든 형태의 바이너리 데이터를 인코딩하고 이를 바이너리 바이트로 인코딩합니다. Binary Byte 모드의 각 바이트는 8비트로 표현됩니다.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


Region One에 있는 모든 일반 중국어 문자는 12비트로 표현됩니다. Region One의 일반 중국어 문자에는 첫 바이트 값이 B0HEX~D7HEX 범위이고 두 번째 바이트 값이 A1HEX~FEHEX 범위인 문자(3760자), 첫 바이트 값이 A1HEX~A3HEX 범위이고 두 번째 바이트 값이 A1HEX~FEHEX 범위인 문자(282자), 그리고 바이트 값이 A8A1HEX~A8C0HEX 범위인 문자(32자)가 포함됩니다.

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


Region Two에 있는 모든 일반 중국어 문자는 12비트로 표현됩니다. Region Two의 일반 중국어 문자에는 첫 바이트 값이 D8HEX~F7HEX 범위이고 두 번째 바이트 값이 A1HEX~FEHEX 범위인 문자가 포함됩니다.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


Extended Channel Interpretation (ECI) 모드

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


GB18030 4바이트 영역의 모든 문자는 21비트로 표현됩니다. GB18030 4바이트 영역은 GB18030 네 바이트 영역에 포함된 모든 문자(예: 첫 바이트 값이 81HEX~FEHEX, 두 번째 바이트 값이 30HEX~39HEX, 세 번째 바이트 값이 81HEX~FEHEX, 네 번째 바이트 값이 30HEX~39HEX 범위인 문자)에서 데이터를 인코딩합니다.

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


GB18030 2바이트 영역의 모든 문자는 15비트로 표현됩니다. GB18030 2바이트 영역은 GB18030 이중 바이트 영역에 포함된 모든 문자(Region One 및 Region Two의 일반 중국어 문자 포함)에서 데이터를 인코딩합니다(예: 첫 바이트 값이 81HEX~FEHEX이고 두 번째 바이트 값이 40HEX~7EHEX 또는 80HEX~FEHEX 범위인 중국어 문자).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


GS1 모드는 Han Xin Code에 표시된 데이터가 GS1 일반 사양에 의해 정의된 GS1 시스템의 GS1 데이터임을 나타냅니다. 입력 문자열 예시: "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


Numeric 모드는 10진 숫자 집합(0-9, 바이트 값 30HEX~39HEX)에서 데이터를 인코딩합니다. 일반적으로 3개의 데이터 문자는 10비트로 표현됩니다.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


Text 모드는 ISO/IEC 646에 정의된 일반 기호(바이트 값 00HEX~1BHEX 및 20HEX~7FHEX)에서 데이터를 인코딩합니다.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


Unicode 모드는 Han Xin Code에서 UTF8 인코딩/문자 집합을 참조하는 모든 텍스트 데이터를 표현하는 방식을 설계합니다.

### URI {#URI}
```
public static final HanXinModes URI
```


URI 모드는 Han Xin Code에 표시된 데이터가 RFC 3986에 정의된 Uniform Resource Identifier (URI)임을 나타냅니다.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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
| Parameter | Type | 설명 |
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

