---
title: DotCodeParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: DotCode 매개변수.
type: docs
weight: 36
url: /ko/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode 매개변수.
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D BarCode 모듈의 높이/너비 비율. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Identifies columns count. |
| [getDotCodeEncodeMode()](#getDotCodeEncodeMode--) | Identifies DotCode encode mode. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [getECIEncoding()](#getECIEncoding--) | Identifies ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Identifies DotCode encode mode. |
| [getRows()](#getRows--) | Identifies rows count. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | 코드가 바코드 리더에게 초기화 또는 재프로그래밍 지시로 다음 데이터를 해석하도록 사용되는지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D BarCode 모듈의 높이/너비 비율. |
| [setColumns(int value)](#setColumns-int-) | Identifies columns count. |
| [setDotCodeEncodeMode(DotCodeEncodeMode value)](#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setDotCodeStructuredAppendModeBarcodeId(int value)](#setDotCodeStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setDotCodeStructuredAppendModeBarcodesCount(int value)](#setDotCodeStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifies ECI encoding. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | 코드가 바코드 리더에게 초기화 또는 재프로그래밍 지시로 다음 데이터를 해석하도록 사용되는지 여부를 나타냅니다. |
| [setRows(int value)](#setRows-int-) | Identifies rows count. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [toString()](#toString--) | Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters). |
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
### getColumns() {#getColumns--}
```
public final int getColumns()
```


열 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 열 수는 최소 5이어야 합니다. 기본값: -1

**Returns:**
int
### getDotCodeEncodeMode() {#getDotCodeEncodeMode--}
```
public final DotCodeEncodeMode getDotCodeEncodeMode()
```


DotCode 인코드 모드를 식별합니다. 기본값: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


DotCode 구조적 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

**Returns:**
int
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 수는 1에서 35 사이의 값이어야 합니다.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI 인코딩을 식별합니다. DotCodeEncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


DotCode 인코드 모드를 식별합니다. 기본값: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


행 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 행 수는 최소 5이어야 합니다. 기본값: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


DotCode 구조적 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 수는 1에서 35 사이의 값이어야 합니다.

**Returns:**
int
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


코드가 바코드 리더에게 초기화 또는 재프로그래밍 지시로 다음 데이터를 해석하도록 사용되는지 여부를 나타냅니다. 기본값은 false입니다.

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

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


열 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 열 수는 최소 5이어야 합니다. 기본값: -1

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDotCodeEncodeMode(DotCodeEncodeMode value) {#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setDotCodeEncodeMode(DotCodeEncodeMode value)
```


DotCode 인코드 모드를 식별합니다. 기본값: Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setDotCodeStructuredAppendModeBarcodeId(int value) {#setDotCodeStructuredAppendModeBarcodeId-int-}
```
public final void setDotCodeStructuredAppendModeBarcodeId(int value)
```


DotCode 구조적 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setDotCodeStructuredAppendModeBarcodesCount(int value) {#setDotCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setDotCodeStructuredAppendModeBarcodesCount(int value)
```


DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 수는 1에서 35 사이의 값이어야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI 인코딩을 식별합니다. DotCodeEncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


DotCode 인코드 모드를 식별합니다. 기본값: Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


코드가 바코드 리더에게 초기화 또는 재프로그래밍 지시로 다음 데이터를 해석하도록 사용되는지 여부를 나타냅니다. 기본값은 false입니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


행 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 행 수는 최소 5이어야 합니다. 기본값: -1

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


DotCode 구조적 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 수는 1에서 35 사이의 값이어야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).

**Returns:**
java.lang.String - 이 [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)를 나타내는 문자열입니다.
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

