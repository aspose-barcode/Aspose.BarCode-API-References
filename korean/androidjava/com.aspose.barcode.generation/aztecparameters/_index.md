---
title: AztecParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Aztec 매개변수.
type: docs
weight: 12
url: /ko/androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Aztec 매개변수.
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D BarCode 모듈의 높이/너비 비율. |
| [getAztecEncodeMode()](#getAztecEncodeMode--) | Aztec 인코드 모드를 가져옵니다. |
| [getAztecErrorLevel()](#getAztecErrorLevel--) | Aztec 유형 바코드의 오류 정정 수준. |
| [getAztecSymbolMode()](#getAztecSymbolMode--) | Aztec Symbol 모드를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI 인코딩을 가져옵니다. |
| [getEncodeMode()](#getEncodeMode--) | Aztec 인코드 모드를 가져옵니다. |
| [getErrorLevel()](#getErrorLevel--) | Aztec 유형 바코드의 오류 정정 수준. |
| [getLayersCount()](#getLayersCount--) | Aztec 심볼의 레이어 수를 가져옵니다. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Aztec 바코드의 Structured Append 모드에 대한 바코드 ID. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aztec 바코드의 Structured Append 모드에 대한 바코드 수. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Aztec 바코드의 Structured Append 모드에 대한 파일 ID (선택 필드). |
| [getSymbolMode()](#getSymbolMode--) | Aztec Symbol 모드를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D BarCode 모듈의 높이/너비 비율. |
| [setAztecEncodeMode(AztecEncodeMode value)](#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Aztec 인코드 모드를 설정합니다. |
| [setAztecErrorLevel(int value)](#setAztecErrorLevel-int-) | Aztec 유형 바코드의 오류 정정 수준. |
| [setAztecSymbolMode(AztecSymbolMode value)](#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Aztec 심볼 모드를 설정합니다. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI 인코딩을 설정합니다. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Aztec 인코드 모드를 설정합니다. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Aztec 유형 바코드의 오류 정정 수준. |
| [setLayersCount(int value)](#setLayersCount-int-) | Aztec 심볼의 레이어 수를 설정합니다. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Aztec 바코드의 Structured Append 모드에 대한 바코드 ID. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Aztec 바코드의 Structured Append 모드에 대한 바코드 수. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Aztec 바코드의 Structured Append 모드에 대한 파일 ID (선택 필드). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Aztec 심볼 모드를 설정합니다. |
| [toString()](#toString--) | 이 [AztecParameters](../../com.aspose.barcode.generation/aztecparameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다. |
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
### getAztecEncodeMode() {#getAztecEncodeMode--}
```
public final AztecEncodeMode getAztecEncodeMode()
```


Aztec 인코드 모드를 가져옵니다. 기본값: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - Aztec 인코드 모드.
### getAztecErrorLevel() {#getAztecErrorLevel--}
```
public final int getAztecErrorLevel()
```


Aztec 유형 바코드의 오류 정정 수준. 값은 5에서 95 사이여야 합니다.

**Returns:**
int
### getAztecSymbolMode() {#getAztecSymbolMode--}
```
public final AztecSymbolMode getAztecSymbolMode()
```


Aztec 심볼 모드를 가져옵니다. 기본값: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
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


ECI 인코딩을 가져옵니다. AztecEncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1

**Returns:**
int - ECI 인코딩.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Aztec 인코드 모드를 가져옵니다. 기본값: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - Aztec 인코드 모드.
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Aztec 유형 바코드의 오류 정정 수준. 값은 5에서 95 사이여야 합니다.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Aztec 심볼의 레이어 수를 가져옵니다. 레이어 수는 Compact 모드에서는 1~3, Full Range 모드에서는 1~32 범위여야 합니다. 기본값: 0 (자동).

**Returns:**
int - Aztec 심볼의 레이어 수.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Aztec 바코드의 Structured Append 모드에 대한 바코드 ID. 바코드 ID는 1에서 바코드 수 사이여야 합니다. 기본값: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Aztec 바코드의 Structured Append 모드에 대한 바코드 수. 바코드 수는 1에서 26 사이여야 합니다. 기본값: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Aztec 바코드의 Structured Append 모드에 대한 파일 ID (선택 필드). 파일 ID에 공백이 포함될 수 없습니다. 기본값: 빈 문자열

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Aztec 심볼 모드를 가져옵니다. 기본값: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.

**Returns:**
boolean
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

### setAztecEncodeMode(AztecEncodeMode value) {#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setAztecEncodeMode(AztecEncodeMode value)
```


Aztec 인코드 모드를 설정합니다. 기본값: Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | com.aspose.barcode.generation.AztecEncodeMode | Aztec 인코드 모드. |

### setAztecErrorLevel(int value) {#setAztecErrorLevel-int-}
```
public final void setAztecErrorLevel(int value)
```


Aztec 유형 바코드의 오류 정정 수준. 값은 5에서 95 사이여야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setAztecSymbolMode(AztecSymbolMode value) {#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setAztecSymbolMode(AztecSymbolMode value)
```


Aztec 심볼 모드를 설정합니다. 기본값: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | Aztec 심볼 모드. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI 인코딩을 설정합니다. AztecEncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | ECI 인코딩. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Aztec 인코드 모드를 설정합니다. 기본값: Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | com.aspose.barcode.generation.AztecEncodeMode | Aztec 인코드 모드. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Aztec 유형 바코드의 오류 정정 수준. 값은 5에서 95 사이여야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Aztec 심볼의 레이어 수를 설정합니다. 레이어 수는 Compact 모드에서는 1~3, Full Range 모드에서는 1~32 범위여야 합니다. 기본값: 0 (자동).

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | Aztec 심볼의 레이어 수. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Aztec 바코드의 Structured Append 모드에 대한 바코드 ID. 바코드 ID는 1에서 바코드 수 사이여야 합니다. 기본값: 0

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Aztec 바코드의 Structured Append 모드에 대한 바코드 수. 바코드 수는 1에서 26 사이여야 합니다. 기본값: 0

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Aztec 바코드의 Structured Append 모드에 대한 파일 ID (선택 필드). 파일 ID에 공백이 포함될 수 없습니다. 기본값: 빈 문자열

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Aztec 심볼 모드를 설정합니다. 기본값: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | Aztec 심볼 모드. |

### toString() {#toString--}
```
public String toString()
```


이 [AztecParameters](../../com.aspose.barcode.generation/aztecparameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [AztecParameters](../../com.aspose.barcode.generation/aztecparameters)를 나타내는 문자열입니다.
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

