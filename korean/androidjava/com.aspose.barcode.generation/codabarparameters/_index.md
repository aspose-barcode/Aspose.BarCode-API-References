---
title: CodabarParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Codabar 매개변수.
type: docs
weight: 22
url: /ko/androidjava/com.aspose.barcode.generation/codabarparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodabarParameters
```

Codabar 매개변수.
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChecksumMode()](#getChecksumMode--) | Codabar 바코드의 체크섬 알고리즘을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCodabarChecksumMode()](#getCodabarChecksumMode--) | Codabar 바코드의 체크섬 알고리즘을 가져옵니다. |
| [getCodabarStartSymbol()](#getCodabarStartSymbol--) | Codabar 기호법의 시작 심볼(문자)입니다. |
| [getCodabarStopSymbol()](#getCodabarStopSymbol--) | Codabar 기호법의 종료 심볼(문자)입니다. |
| [getStartSymbol()](#getStartSymbol--) | Codabar 기호법의 시작 심볼(문자)입니다. |
| [getStopSymbol()](#getStopSymbol--) | Codabar 기호법의 종료 심볼(문자)입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChecksumMode(CodabarChecksumMode value)](#setChecksumMode-com.aspose.barcode.generation.CodabarChecksumMode-) | Codabar 바코드의 체크섬 알고리즘을 설정합니다. |
| [setCodabarChecksumMode(CodabarChecksumMode value)](#setCodabarChecksumMode-com.aspose.barcode.generation.CodabarChecksumMode-) | Codabar 바코드의 체크섬 알고리즘을 설정합니다. |
| [setCodabarStartSymbol(short value)](#setCodabarStartSymbol-short-) | Codabar 기호법의 시작 심볼(문자)입니다. |
| [setCodabarStopSymbol(short value)](#setCodabarStopSymbol-short-) | Codabar 기호법의 종료 심볼(문자)입니다. |
| [setStartSymbol(short value)](#setStartSymbol-short-) | Codabar 기호법의 시작 심볼(문자)입니다. |
| [setStopSymbol(short value)](#setStopSymbol-short-) | Codabar 기호법의 종료 심볼(문자)입니다. |
| [toString()](#toString--) | 이 [CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)의 사람 친화적인 문자열 표현을 반환합니다. |
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
### getChecksumMode() {#getChecksumMode--}
```
public final CodabarChecksumMode getChecksumMode()
```


Codabar 바코드의 체크섬 알고리즘을 가져옵니다. 기본값: CodabarChecksumMode.Mod16. 체크섬 계산을 활성화하려면 EnableChecksum 속성에 EnableChecksum.Yes 값을 설정하십시오. 자세한 내용은 ChecksumMode(\#getChecksumMode.getChecksumMode/\#setChecksumMode.setChecksumMode)를 참조하세요.

**Returns:**
[CodabarChecksumMode](../../com.aspose.barcode.generation/codabarchecksummode) - the checksum algorithm for Codabar barcodes.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodabarChecksumMode() {#getCodabarChecksumMode--}
```
public final CodabarChecksumMode getCodabarChecksumMode()
```


Codabar 바코드의 체크섬 알고리즘을 가져옵니다. 기본값: CodabarChecksumMode.Mod16. 체크섬 계산을 활성화하려면 EnableChecksum 속성에 EnableChecksum.Yes 값을 설정하십시오. 자세한 내용은 ChecksumMode(\#getChecksumMode.getChecksumMode/\#setChecksumMode.setChecksumMode)를 참조하세요.

**Returns:**
[CodabarChecksumMode](../../com.aspose.barcode.generation/codabarchecksummode) - the checksum algorithm for Codabar barcodes.
### getCodabarStartSymbol() {#getCodabarStartSymbol--}
```
public final short getCodabarStartSymbol()
```


Codabar 기호법의 시작 심볼(문자)입니다. 기본값: CodabarSymbol.A

**Returns:**
short
### getCodabarStopSymbol() {#getCodabarStopSymbol--}
```
public final short getCodabarStopSymbol()
```


Codabar 기호법의 종료 심볼(문자)입니다. 기본값: CodabarSymbol.A

**Returns:**
short
### getStartSymbol() {#getStartSymbol--}
```
public final short getStartSymbol()
```


Codabar 기호법의 시작 심볼(문자)입니다. 기본값: CodabarSymbol.A

**Returns:**
short
### getStopSymbol() {#getStopSymbol--}
```
public final short getStopSymbol()
```


Codabar 기호법의 종료 심볼(문자)입니다. 기본값: CodabarSymbol.A

**Returns:**
short
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




### setChecksumMode(CodabarChecksumMode value) {#setChecksumMode-com.aspose.barcode.generation.CodabarChecksumMode-}
```
public final void setChecksumMode(CodabarChecksumMode value)
```


Codabar 바코드의 체크섬 알고리즘을 설정합니다. 기본값: CodabarChecksumMode.Mod16. 체크섬 계산을 활성화하려면 EnableChecksum 속성에 EnableChecksum.Yes 값을 설정하십시오. 자세한 내용은 ChecksumMode(\#getChecksumMode.getChecksumMode/\#setChecksumMode.setChecksumMode)를 참조하세요.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [CodabarChecksumMode](../../com.aspose.barcode.generation/codabarchecksummode) | Codabar 바코드의 체크섬 알고리즘. |

### setCodabarChecksumMode(CodabarChecksumMode value) {#setCodabarChecksumMode-com.aspose.barcode.generation.CodabarChecksumMode-}
```
public final void setCodabarChecksumMode(CodabarChecksumMode value)
```


Codabar 바코드의 체크섬 알고리즘을 설정합니다. 기본값: CodabarChecksumMode.Mod16. 체크섬 계산을 활성화하려면 EnableChecksum 속성에 EnableChecksum.Yes 값을 설정하십시오. 자세한 내용은 ChecksumMode(\#getChecksumMode.getChecksumMode/\#setChecksumMode.setChecksumMode)를 참조하세요.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [CodabarChecksumMode](../../com.aspose.barcode.generation/codabarchecksummode) | Codabar 바코드의 체크섬 알고리즘. |

### setCodabarStartSymbol(short value) {#setCodabarStartSymbol-short-}
```
public final void setCodabarStartSymbol(short value)
```


Codabar 기호법의 시작 심볼(문자)입니다. 기본값: CodabarSymbol.A

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setCodabarStopSymbol(short value) {#setCodabarStopSymbol-short-}
```
public final void setCodabarStopSymbol(short value)
```


Codabar 기호법의 종료 심볼(문자)입니다. 기본값: CodabarSymbol.A

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setStartSymbol(short value) {#setStartSymbol-short-}
```
public final void setStartSymbol(short value)
```


Codabar 기호법의 시작 심볼(문자)입니다. 기본값: CodabarSymbol.A

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setStopSymbol(short value) {#setStopSymbol-short-}
```
public final void setStopSymbol(short value)
```


Codabar 기호법의 종료 심볼(문자)입니다. 기본값: CodabarSymbol.A

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | short |  |

### toString() {#toString--}
```
public String toString()
```


이 [CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)의 사람 친화적인 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)를 나타내는 문자열입니다.
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

