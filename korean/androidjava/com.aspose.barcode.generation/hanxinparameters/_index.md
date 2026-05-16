---
title: HanXinParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Han Xin 매개변수.
type: docs
weight: 50
url: /ko/androidjava/com.aspose.barcode.generation/hanxinparameters/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParameters
```

Han Xin 매개변수.
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 확장 채널 해석 식별자. |
| [getEncodeMode()](#getEncodeMode--) | HanXin 인코딩 모드. |
| [getErrorLevel()](#getErrorLevel--) | Han Xin 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [getHanXinECIEncoding()](#getHanXinECIEncoding--) | 확장 채널 해석 식별자. |
| [getHanXinEncodeMode()](#getHanXinEncodeMode--) | HanXin 인코딩 모드. |
| [getHanXinErrorLevel()](#getHanXinErrorLevel--) | Han Xin 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [getHanXinVersion()](#getHanXinVersion--) | HanXin 코드 버전. |
| [getVersion()](#getVersion--) | HanXin 코드 버전. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 확장 채널 해석 식별자. |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | HanXin 인코딩 모드. |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | Han Xin 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | HanXin 코드 버전. |
| [toString()](#toString--) | 이 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


확장 채널 해석 식별자. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더기에 전달하는 데 사용됩니다. 현재 구현은 알려진 모든 문자 집합 인코딩을 포함합니다.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


HanXin 인코딩 모드. 기본값: EncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


Han Xin 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: L1, L2, L3, L4. ErrorLevel을 참조하세요.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinECIEncoding() {#getHanXinECIEncoding--}
```
public final int getHanXinECIEncoding()
```


확장 채널 해석 식별자. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더기에 전달하는 데 사용됩니다. 현재 구현은 알려진 모든 문자 집합 인코딩을 포함합니다.

**Returns:**
int
### getHanXinEncodeMode() {#getHanXinEncodeMode--}
```
public final HanXinEncodeMode getHanXinEncodeMode()
```


HanXin 인코딩 모드. 기본값: EncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getHanXinErrorLevel() {#getHanXinErrorLevel--}
```
public final HanXinErrorLevel getHanXinErrorLevel()
```


Han Xin 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: L1, L2, L3, L4. ErrorLevel을 참조하세요.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinVersion() {#getHanXinVersion--}
```
public final HanXinVersion getHanXinVersion()
```


HanXin 코드 버전. Han Xin 코드의 경우 Version01부터 Version84까지. 기본값은 Version.Auto입니다.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


HanXin 코드 버전. Han Xin 코드의 경우 Version01부터 Version84까지. 기본값은 Version.Auto입니다.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


확장 채널 해석 식별자. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더기에 전달하는 데 사용됩니다. 현재 구현은 알려진 모든 문자 집합 인코딩을 포함합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


HanXin 인코딩 모드. 기본값: EncodeMode.Mixed.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


Han Xin 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: L1, L2, L3, L4. ErrorLevel을 참조하세요.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


HanXin 코드 버전. Han Xin 코드의 경우 Version01부터 Version84까지. 기본값은 Version.Auto입니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


이 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)를 나타내는 문자열입니다.
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

