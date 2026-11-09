---
title: "HanXinParametersUI"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: 
type: docs
weight: 15
url: /ko/java/com.aspose.barcode.barcodecontrol/hanxinparametersui/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParametersUI
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation 식별자. |
| [getEncodeMode()](#getEncodeMode--) | BarCode의 인코딩 모드에 대한 HanXin 심볼 유형. |
| [getErrorLevel()](#getErrorLevel--) | HanXin 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [getVersion()](#getVersion--) | HanXin 코드 버전. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation 식별자. |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | BarCode의 인코딩 모드에 대한 HanXin 심볼 유형. |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | HanXin 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | HanXin 코드 버전. |
| [toString()](#toString--) | 이 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Extended Channel Interpretation Identifiers. 바코드 리더에게 심볼에 데이터를 인코딩하는 데 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


BarCode의 인코딩 모드에 대한 HanXin 심볼 유형. 기본값: EncodeMode.Auto.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


HanXin 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: L1 - L4. ErrorLevel을 참조하십시오.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


HanXin 코드의 버전입니다. HanXin 코드에 대해 Version01부터 Version84까지 사용할 수 있습니다. 기본값은 Version.Auto입니다.

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


Extended Channel Interpretation Identifiers. 바코드 리더에게 심볼에 데이터를 인코딩하는 데 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


BarCode의 인코딩 모드에 대한 HanXin 심볼 유형. 기본값: EncodeMode.Auto.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


HanXin 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: L1 - L4. ErrorLevel을 참조하십시오.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


HanXin 코드의 버전입니다. HanXin 코드에 대해 Version01부터 Version84까지 사용할 수 있습니다. 기본값은 Version.Auto입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


이 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)를 나타내는 문자열입니다.
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

