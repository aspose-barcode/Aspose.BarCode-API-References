---
title: MaxiCodeParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: MaxiCode 매개변수.
type: docs
weight: 57
url: /ko/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode 매개변수.
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D BarCode 모듈의 높이/너비 비율. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI 인코딩을 가져옵니다. |
| [getEncodeMode()](#getEncodeMode--) | MaxiCode 인코드 모드를 가져옵니다. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | MaxiCode 인코드 모드를 가져옵니다. |
| [getMaxiCodeMode()](#getMaxiCodeMode--) | MaxiCode 인코드 모드를 가져옵니다. |
| [getMaxiCodeStructuredAppendModeBarcodeId()](#getMaxiCodeStructuredAppendModeBarcodeId--) | 구조화된 추가 모드에서 MaxiCode 바코드 ID를 가져옵니다. |
| [getMaxiCodeStructuredAppendModeBarcodesCount()](#getMaxiCodeStructuredAppendModeBarcodesCount--) | 구조화된 추가 모드에서 MaxiCode 바코드 수를 가져옵니다. |
| [getMode()](#getMode--) | MaxiCode 인코드 모드를 가져옵니다. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | 구조화된 추가 모드에서 MaxiCode 바코드 ID를 가져옵니다. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | 구조화된 추가 모드에서 MaxiCode 바코드 수를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D BarCode 모듈의 높이/너비 비율. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI 인코딩을 설정합니다. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode 인코드 모드를 설정합니다. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode 인코드 모드를 설정합니다. |
| [setMaxiCodeMode(int value)](#setMaxiCodeMode-int-) | MaxiCode 인코드 모드를 설정합니다. |
| [setMaxiCodeStructuredAppendModeBarcodeId(int value)](#setMaxiCodeStructuredAppendModeBarcodeId-int-) | 구조적 추가 모드에서 MaxiCode 바코드 ID를 설정합니다. |
| [setMaxiCodeStructuredAppendModeBarcodesCount(int value)](#setMaxiCodeStructuredAppendModeBarcodesCount-int-) | 구조적 추가 모드에서 MaxiCode 바코드 수를 설정합니다. |
| [setMode(int value)](#setMode-int-) | MaxiCode 인코드 모드를 설정합니다. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | 구조적 추가 모드에서 MaxiCode 바코드 ID를 설정합니다. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | 구조적 추가 모드에서 MaxiCode 바코드 수를 설정합니다. |
| [toString()](#toString--) | 이 [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다. |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D BarCode 모듈의 높이/너비 비율.

**Returns:**
float
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


ECI 인코딩을 가져옵니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1

**Returns:**
int - ECI 인코딩.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


MaxiCode 인코드 모드를 가져옵니다. 기본값: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


MaxiCode 인코드 모드를 가져옵니다. 기본값: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeMode() {#getMaxiCodeMode--}
```
public final int getMaxiCodeMode()
```


MaxiCode 인코드 모드를 가져옵니다.

**Returns:**
int - MaxiCode 인코드 모드.
### getMaxiCodeStructuredAppendModeBarcodeId() {#getMaxiCodeStructuredAppendModeBarcodeId--}
```
public final int getMaxiCodeStructuredAppendModeBarcodeId()
```


구조적 추가 모드에서 MaxiCode 바코드 ID를 가져옵니다. ID는 1에서 8 사이의 값이어야 합니다. 기본값: 0

**Returns:**
int - 구조화된 추가 모드에서 MaxiCode 바코드 ID.
### getMaxiCodeStructuredAppendModeBarcodesCount() {#getMaxiCodeStructuredAppendModeBarcodesCount--}
```
public final int getMaxiCodeStructuredAppendModeBarcodesCount()
```


구조적 추가 모드에서 MaxiCode 바코드 수를 가져옵니다. 개수는 2에서 8 사이의 값이어야 합니다 (최대 바코드 수). 기본값: -1

**Returns:**
int - 구조화된 추가 모드에서 MaxiCode 바코드 수.
### getMode() {#getMode--}
```
public final int getMode()
```


MaxiCode 인코드 모드를 가져옵니다.

**Returns:**
int - MaxiCode 인코드 모드.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


구조적 추가 모드에서 MaxiCode 바코드 ID를 가져옵니다. ID는 1에서 8 사이의 값이어야 합니다. 기본값: 0

**Returns:**
int - 구조화된 추가 모드에서 MaxiCode 바코드 ID.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


구조적 추가 모드에서 MaxiCode 바코드 수를 가져옵니다. 개수는 2에서 8 사이의 값이어야 합니다 (최대 바코드 수). 기본값: -1

**Returns:**
int - 구조화된 추가 모드에서 MaxiCode 바코드 수.
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


2D BarCode 모듈의 높이/너비 비율.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI 인코딩을 설정합니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | ECI 인코딩. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCode 인코드 모드를 설정합니다. 기본값: Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | MaxiCode 인코드 모드. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCode 인코드 모드를 설정합니다. 기본값: Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | MaxiCode 인코드 모드. |

### setMaxiCodeMode(int value) {#setMaxiCodeMode-int-}
```
public final void setMaxiCodeMode(int value)
```


MaxiCode 인코드 모드를 설정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | MaxiCode 인코드 모드. |

### setMaxiCodeStructuredAppendModeBarcodeId(int value) {#setMaxiCodeStructuredAppendModeBarcodeId-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodeId(int value)
```


구조적 추가 모드에서 MaxiCode 바코드 ID를 설정합니다. ID는 1에서 8 사이의 값이어야 합니다. 기본값: 0

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | 구조적 추가 모드의 MaxiCode 바코드 ID. |

### setMaxiCodeStructuredAppendModeBarcodesCount(int value) {#setMaxiCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodesCount(int value)
```


구조적 추가 모드에서 MaxiCode 바코드 수를 설정합니다. 개수는 2에서 8 사이의 값이어야 합니다 (최대 바코드 수). 기본값: -1

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | 구조화된 추가 모드에서 MaxiCode 바코드 수. |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


MaxiCode 인코드 모드를 설정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | MaxiCode 인코드 모드. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


구조적 추가 모드에서 MaxiCode 바코드 ID를 설정합니다. ID는 1에서 8 사이의 값이어야 합니다. 기본값: 0

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | 구조적 추가 모드의 MaxiCode 바코드 ID. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


구조적 추가 모드에서 MaxiCode 바코드 수를 설정합니다. 개수는 2에서 8 사이의 값이어야 합니다 (최대 바코드 수). 기본값: -1

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | 구조화된 추가 모드에서 MaxiCode 바코드 수. |

### toString() {#toString--}
```
public String toString()
```


이 [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)를 나타내는 문자열.
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

