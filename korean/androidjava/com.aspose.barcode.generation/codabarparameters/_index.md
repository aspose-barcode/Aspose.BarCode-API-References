---
title: "CodabarParameters"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "Codabar 매개변수."
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
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChecksumMode()](#getChecksumMode--) | Codabar 바코드의 체크섬 알고리즘을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getStartSymbol()](#getStartSymbol--) | Codabar 기호법의 시작 기호(문자)입니다. |
| [getStopSymbol()](#getStopSymbol--) | Codabar 기호법의 종료 기호(문자)입니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChecksumMode(CodabarChecksumMode value)](#setChecksumMode-com.aspose.barcode.generation.CodabarChecksumMode-) | Codabar 바코드의 체크섬 알고리즘을 설정합니다. |
| [setStartSymbol(CodabarSymbol value)](#setStartSymbol-com.aspose.barcode.generation.CodabarSymbol-) | Codabar 기호법의 시작 기호(문자)입니다. |
| [setStopSymbol(CodabarSymbol value)](#setStopSymbol-com.aspose.barcode.generation.CodabarSymbol-) | Codabar 기호법의 종료 기호(문자)입니다. |
| [toString()](#toString--) | 이 [CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getChecksumMode() {#getChecksumMode--}
```
public final CodabarChecksumMode getChecksumMode()
```


Codabar 바코드의 체크섬 알고리즘을 가져옵니다. 기본값: CodabarChecksumMode.Mod16. 체크섬 계산을 활성화하려면 EnableChecksum 속성에 EnableChecksum.Yes 값을 설정하십시오. ChecksumMode을 참조하십시오 (\#getChecksumMode.getChecksumMode/\#setChecksumMode.setChecksumMode).

**Returns:**
[CodabarChecksumMode](../../com.aspose.barcode.generation/codabarchecksummode) - the checksum algorithm for Codabar barcodes.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getStartSymbol() {#getStartSymbol--}
```
public final CodabarSymbol getStartSymbol()
```


Codabar 기호법의 시작 기호(문자). 기본값: CodabarSymbol.A

**Returns:**
[CodabarSymbol](../../com.aspose.barcode.generation/codabarsymbol)
### getStopSymbol() {#getStopSymbol--}
```
public final CodabarSymbol getStopSymbol()
```


Codabar 기호법의 종료 기호(문자). 기본값: CodabarSymbol.A

**Returns:**
[CodabarSymbol](../../com.aspose.barcode.generation/codabarsymbol)
### hashCode() {#hashCode--}
```
public final int hashCode()
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


Codabar 바코드의 체크섬 알고리즘을 설정합니다. 기본값: CodabarChecksumMode.Mod16. 체크섬 계산을 활성화하려면 EnableChecksum 속성에 EnableChecksum.Yes 값을 설정하십시오. ChecksumMode을 참조하십시오 (\#getChecksumMode.getChecksumMode/\#setChecksumMode.setChecksumMode).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [CodabarChecksumMode](../../com.aspose.barcode.generation/codabarchecksummode) | Codabar 바코드의 체크섬 알고리즘. |

### setStartSymbol(CodabarSymbol value) {#setStartSymbol-com.aspose.barcode.generation.CodabarSymbol-}
```
public final void setStartSymbol(CodabarSymbol value)
```


Codabar 기호법의 시작 기호(문자). 기본값: CodabarSymbol.A

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [CodabarSymbol](../../com.aspose.barcode.generation/codabarsymbol) |  |

### setStopSymbol(CodabarSymbol value) {#setStopSymbol-com.aspose.barcode.generation.CodabarSymbol-}
```
public final void setStopSymbol(CodabarSymbol value)
```


Codabar 기호법의 종료 기호(문자). 기본값: CodabarSymbol.A

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [CodabarSymbol](../../com.aspose.barcode.generation/codabarsymbol) |  |

### toString() {#toString--}
```
public String toString()
```


이 [CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)을 나타내는 문자열입니다.
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

