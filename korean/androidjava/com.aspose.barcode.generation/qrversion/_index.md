---
title: QRVersion
second_title: Aspose.BarCode for Android via Java API Reference
description: QR Code 버전.
type: docs
weight: 105
url: /ko/androidjava/com.aspose.barcode.generation/qrversion/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRVersion extends Enum<QRVersion>
```

QR 코드의 버전입니다. QR 코드는 Version1부터 Version40까지, MicroQr은 M1부터 M4까지 지원합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [AUTO](#AUTO) | QR에 대해 최적의 버전을 자동으로 선택하도록 지정합니다. |
| [VERSION_01](#VERSION-01) | 21 x 21 모듈인 버전 1을 지정합니다. |
| [VERSION_02](#VERSION-02) | 25 x 25 모듈인 버전 2를 지정합니다. |
| [VERSION_03](#VERSION-03) | 29 x 29 모듈인 버전 3을 지정합니다. |
| [VERSION_04](#VERSION-04) | 33 x 33 모듈인 버전 4를 지정합니다. |
| [VERSION_05](#VERSION-05) | 37 x 37 모듈인 버전 5를 지정합니다. |
| [VERSION_06](#VERSION-06) | 41 x 41 모듈인 버전 6을 지정합니다. |
| [VERSION_07](#VERSION-07) | 45 x 45 모듈인 버전 7을 지정합니다. |
| [VERSION_08](#VERSION-08) | 49 x 49 모듈인 버전 8을 지정합니다. |
| [VERSION_09](#VERSION-09) | 53 x 53 모듈인 버전 9를 지정합니다. |
| [VERSION_10](#VERSION-10) | 57 x 57 모듈인 버전 10을 지정합니다. |
| [VERSION_11](#VERSION-11) | 61 x 61 모듈인 버전 11을 지정합니다. |
| [VERSION_12](#VERSION-12) | 65 x 65 모듈인 버전 12를 지정합니다. |
| [VERSION_13](#VERSION-13) | 69 x 69 모듈인 버전 13을 지정합니다. |
| [VERSION_14](#VERSION-14) | 73 x 73 모듈인 버전 14를 지정합니다. |
| [VERSION_15](#VERSION-15) | 77 x 77 모듈인 버전 15를 지정합니다. |
| [VERSION_16](#VERSION-16) | 81 x 81 모듈인 버전 16을 지정합니다. |
| [VERSION_17](#VERSION-17) | 85 x 85 모듈인 버전 17을 지정합니다. |
| [VERSION_18](#VERSION-18) | 89 x 89 모듈인 버전 18을 지정합니다. |
| [VERSION_19](#VERSION-19) | 93 x 93 모듈인 버전 19를 지정합니다. |
| [VERSION_20](#VERSION-20) | 97 x 97 모듈인 버전 20을 지정합니다. |
| [VERSION_21](#VERSION-21) | 101 x 101 모듈인 버전 21을 지정합니다. |
| [VERSION_22](#VERSION-22) | 버전 22를 지정하고 105 x 105 모듈을 사용합니다. |
| [VERSION_23](#VERSION-23) | 버전 23를 지정하고 109 x 109 모듈을 사용합니다. |
| [VERSION_24](#VERSION-24) | 버전 24를 지정하고 113 x 113 모듈을 사용합니다. |
| [VERSION_25](#VERSION-25) | 버전 25를 지정하고 117 x 117 모듈을 사용합니다. |
| [VERSION_26](#VERSION-26) | 버전 26를 지정하고 121 x 121 모듈을 사용합니다. |
| [VERSION_27](#VERSION-27) | 버전 27를 지정하고 125 x 125 모듈을 사용합니다. |
| [VERSION_28](#VERSION-28) | 버전 28를 지정하고 129 x 129 모듈을 사용합니다. |
| [VERSION_29](#VERSION-29) | 버전 29를 지정하고 133 x 133 모듈을 사용합니다. |
| [VERSION_30](#VERSION-30) | 버전 30를 지정하고 137 x 137 모듈을 사용합니다. |
| [VERSION_31](#VERSION-31) | 버전 31를 지정하고 141 x 141 모듈을 사용합니다. |
| [VERSION_32](#VERSION-32) | 버전 32를 지정하고 145 x 145 모듈을 사용합니다. |
| [VERSION_33](#VERSION-33) | 버전 33를 지정하고 149 x 149 모듈을 사용합니다. |
| [VERSION_34](#VERSION-34) | 버전 34를 지정하고 153 x 153 모듈을 사용합니다. |
| [VERSION_35](#VERSION-35) | 버전 35를 지정하고 157 x 157 모듈을 사용합니다. |
| [VERSION_36](#VERSION-36) | 버전 36를 지정하고 161 x 161 모듈을 사용합니다. |
| [VERSION_37](#VERSION-37) | 버전 37를 지정하고 165 x 165 모듈을 사용합니다. |
| [VERSION_38](#VERSION-38) | 버전 38를 지정하고 169 x 169 모듈을 사용합니다. |
| [VERSION_39](#VERSION-39) | 버전 39를 지정하고 173 x 173 모듈을 사용합니다. |
| [VERSION_40](#VERSION-40) | 버전 40를 지정하고 177 x 177 모듈을 사용합니다. |
| [VERSION_M1](#VERSION-M1) | 11 x 11 모듈을 가진 Micro QR에 대해 버전 M1을 지정합니다. |
| [VERSION_M2](#VERSION-M2) | 13 x 13 모듈을 가진 Micro QR에 대해 버전 M2를 지정합니다. |
| [VERSION_M3](#VERSION-M3) | 15 x 15 모듈을 가진 Micro QR에 대해 버전 M3을 지정합니다. |
| [VERSION_M4](#VERSION-M4) | 17 x 17 모듈을 가진 Micro QR에 대해 버전 M4를 지정합니다. |
## Methods

| Method | 설명 |
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
public static final QRVersion AUTO
```


QR에 대해 최적 버전을 자동으로 선택하도록 지정합니다. 기본값입니다.

### VERSION_01 {#VERSION-01}
```
public static final QRVersion VERSION_01
```


21 x 21 모듈인 버전 1을 지정합니다.

### VERSION_02 {#VERSION-02}
```
public static final QRVersion VERSION_02
```


25 x 25 모듈인 버전 2를 지정합니다.

### VERSION_03 {#VERSION-03}
```
public static final QRVersion VERSION_03
```


29 x 29 모듈인 버전 3을 지정합니다.

### VERSION_04 {#VERSION-04}
```
public static final QRVersion VERSION_04
```


33 x 33 모듈인 버전 4를 지정합니다.

### VERSION_05 {#VERSION-05}
```
public static final QRVersion VERSION_05
```


37 x 37 모듈인 버전 5를 지정합니다.

### VERSION_06 {#VERSION-06}
```
public static final QRVersion VERSION_06
```


41 x 41 모듈인 버전 6을 지정합니다.

### VERSION_07 {#VERSION-07}
```
public static final QRVersion VERSION_07
```


45 x 45 모듈인 버전 7을 지정합니다.

### VERSION_08 {#VERSION-08}
```
public static final QRVersion VERSION_08
```


49 x 49 모듈인 버전 8을 지정합니다.

### VERSION_09 {#VERSION-09}
```
public static final QRVersion VERSION_09
```


53 x 53 모듈인 버전 9를 지정합니다.

### VERSION_10 {#VERSION-10}
```
public static final QRVersion VERSION_10
```


57 x 57 모듈인 버전 10을 지정합니다.

### VERSION_11 {#VERSION-11}
```
public static final QRVersion VERSION_11
```


61 x 61 모듈인 버전 11을 지정합니다.

### VERSION_12 {#VERSION-12}
```
public static final QRVersion VERSION_12
```


65 x 65 모듈인 버전 12를 지정합니다.

### VERSION_13 {#VERSION-13}
```
public static final QRVersion VERSION_13
```


69 x 69 모듈인 버전 13을 지정합니다.

### VERSION_14 {#VERSION-14}
```
public static final QRVersion VERSION_14
```


73 x 73 모듈인 버전 14를 지정합니다.

### VERSION_15 {#VERSION-15}
```
public static final QRVersion VERSION_15
```


77 x 77 모듈인 버전 15를 지정합니다.

### VERSION_16 {#VERSION-16}
```
public static final QRVersion VERSION_16
```


81 x 81 모듈인 버전 16을 지정합니다.

### VERSION_17 {#VERSION-17}
```
public static final QRVersion VERSION_17
```


85 x 85 모듈인 버전 17을 지정합니다.

### VERSION_18 {#VERSION-18}
```
public static final QRVersion VERSION_18
```


89 x 89 모듈인 버전 18을 지정합니다.

### VERSION_19 {#VERSION-19}
```
public static final QRVersion VERSION_19
```


93 x 93 모듈인 버전 19를 지정합니다.

### VERSION_20 {#VERSION-20}
```
public static final QRVersion VERSION_20
```


97 x 97 모듈인 버전 20을 지정합니다.

### VERSION_21 {#VERSION-21}
```
public static final QRVersion VERSION_21
```


101 x 101 모듈인 버전 21을 지정합니다.

### VERSION_22 {#VERSION-22}
```
public static final QRVersion VERSION_22
```


버전 22를 지정하고 105 x 105 모듈을 사용합니다.

### VERSION_23 {#VERSION-23}
```
public static final QRVersion VERSION_23
```


버전 23를 지정하고 109 x 109 모듈을 사용합니다.

### VERSION_24 {#VERSION-24}
```
public static final QRVersion VERSION_24
```


버전 24를 지정하고 113 x 113 모듈을 사용합니다.

### VERSION_25 {#VERSION-25}
```
public static final QRVersion VERSION_25
```


버전 25를 지정하고 117 x 117 모듈을 사용합니다.

### VERSION_26 {#VERSION-26}
```
public static final QRVersion VERSION_26
```


버전 26를 지정하고 121 x 121 모듈을 사용합니다.

### VERSION_27 {#VERSION-27}
```
public static final QRVersion VERSION_27
```


버전 27를 지정하고 125 x 125 모듈을 사용합니다.

### VERSION_28 {#VERSION-28}
```
public static final QRVersion VERSION_28
```


버전 28를 지정하고 129 x 129 모듈을 사용합니다.

### VERSION_29 {#VERSION-29}
```
public static final QRVersion VERSION_29
```


버전 29를 지정하고 133 x 133 모듈을 사용합니다.

### VERSION_30 {#VERSION-30}
```
public static final QRVersion VERSION_30
```


버전 30를 지정하고 137 x 137 모듈을 사용합니다.

### VERSION_31 {#VERSION-31}
```
public static final QRVersion VERSION_31
```


버전 31를 지정하고 141 x 141 모듈을 사용합니다.

### VERSION_32 {#VERSION-32}
```
public static final QRVersion VERSION_32
```


버전 32를 지정하고 145 x 145 모듈을 사용합니다.

### VERSION_33 {#VERSION-33}
```
public static final QRVersion VERSION_33
```


버전 33를 지정하고 149 x 149 모듈을 사용합니다.

### VERSION_34 {#VERSION-34}
```
public static final QRVersion VERSION_34
```


버전 34를 지정하고 153 x 153 모듈을 사용합니다.

### VERSION_35 {#VERSION-35}
```
public static final QRVersion VERSION_35
```


버전 35를 지정하고 157 x 157 모듈을 사용합니다.

### VERSION_36 {#VERSION-36}
```
public static final QRVersion VERSION_36
```


버전 36를 지정하고 161 x 161 모듈을 사용합니다.

### VERSION_37 {#VERSION-37}
```
public static final QRVersion VERSION_37
```


버전 37를 지정하고 165 x 165 모듈을 사용합니다.

### VERSION_38 {#VERSION-38}
```
public static final QRVersion VERSION_38
```


버전 38를 지정하고 169 x 169 모듈을 사용합니다.

### VERSION_39 {#VERSION-39}
```
public static final QRVersion VERSION_39
```


버전 39를 지정하고 173 x 173 모듈을 사용합니다.

### VERSION_40 {#VERSION-40}
```
public static final QRVersion VERSION_40
```


버전 40를 지정하고 177 x 177 모듈을 사용합니다.

### VERSION_M1 {#VERSION-M1}
```
public static final QRVersion VERSION_M1
```


11 x 11 모듈을 가진 Micro QR에 대해 버전 M1을 지정합니다.

### VERSION_M2 {#VERSION-M2}
```
public static final QRVersion VERSION_M2
```


13 x 13 모듈을 가진 Micro QR에 대해 버전 M2를 지정합니다.

### VERSION_M3 {#VERSION-M3}
```
public static final QRVersion VERSION_M3
```


15 x 15 모듈을 가진 Micro QR에 대해 버전 M3을 지정합니다.

### VERSION_M4 {#VERSION-M4}
```
public static final QRVersion VERSION_M4
```


17 x 17 모듈을 가진 Micro QR에 대해 버전 M4를 지정합니다.

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
### fromValue(int value) {#fromValue-int-}
```
public static QRVersion fromValue(int value)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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
public static QRVersion valueOf(String name)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### values() {#values--}
```
public static QRVersion[] values()
```




**Returns:**
com.aspose.barcode.generation.QRVersion[]
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

