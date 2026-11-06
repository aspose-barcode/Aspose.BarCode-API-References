---
title: "QrParameters"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "QR 매개변수."
type: docs
weight: 62
url: /ko/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR 매개변수.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 바코드 모듈의 높이/너비 비율. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 확장 채널 해석 식별자. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) |  |
| [getEncodeMode()](#getEncodeMode--) | QR 심볼 유형 (BarCode의 인코딩 모드). |
| [getErrorLevel()](#getErrorLevel--) | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [getMicroQRVersion()](#getMicroQRVersion--) | MicroQR Code 버전. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | RectMicroQR Code 버전. |
| [getStructuredAppend()](#getStructuredAppend--) | QR 구조적 추가 매개변수. |
| [getVersion()](#getVersion--) | QR 코드 버전. Version1부터 Version40까지. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 바코드 모듈의 높이/너비 비율. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 확장 채널 해석 식별자. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) |  |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | QR 심볼 유형 (BarCode의 인코딩 모드). |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | MicroQR Code 버전. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | RectMicroQR Code 버전. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR 구조적 추가 매개변수. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | QR 코드 버전. Version1부터 Version40까지. |
| [toString()](#toString--) | 이 [QrParameters](../../com.aspose.barcode.generation/qrparameters)의 사람 읽을 수 있는 문자열 표현을 반환합니다. |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D 바코드 모듈의 높이/너비 비율.

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


확장 채널 해석 식별자. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더에게 전달하는 데 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public final boolean getEncodeGS1SeparatorInByteMode()
```


QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

false인 경우, QR 사양에 따라 GS1 구분자는 영숫자 모드에서 '%'로 인코딩될 수 있습니다.

true인 경우, GS1 그룹 구분자는 바이트 모드에서 0x1D 문자로 인코딩되며, '%' 문자도 데이터로 보존하기 위해 바이트 모드에서 인코딩됩니다.

이 옵션은 바이트 수준 GS1 그룹 구분자를 기대하는 디코더와의 호환성을 향상시킬 수 있으며, '%' 데이터 문자가 GS1 구분자로 해석되는 것을 방지합니다.

**Returns:**
boolean - QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩해야 하는지 여부를 나타내는 값.
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


BarCode의 인코딩 모드에 대한 QR 심볼 유형. 기본값: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel을 참조하십시오.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


MicroQR 코드 버전. M1 버전부터 M4 버전까지. 기본값은 MicroQRVersion.Auto입니다.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


RectMicroQR 코드 버전. R7x59 버전부터 R17x139 버전까지. 기본값은 RectMicroQRVersion.Auto입니다.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


QR 구조적 추가 매개변수. 구조적 추가 모드는 MicroQR 및 RectMicroQR 바코드에서 지원되지 않습니다.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


QR 코드 버전. Version1부터 Version40까지. 기본값은 QRVersion.Auto입니다.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


2D 바코드 모듈의 높이/너비 비율.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


확장 채널 해석 식별자. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더에게 전달하는 데 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public final void setEncodeGS1SeparatorInByteMode(boolean value)
```


QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다.

false인 경우, QR 사양에 따라 GS1 구분자는 영숫자 모드에서 '%'로 인코딩될 수 있습니다.

true인 경우, GS1 그룹 구분자는 바이트 모드에서 0x1D 문자로 인코딩되며, '%' 문자도 데이터로 보존하기 위해 바이트 모드에서 인코딩됩니다.

이 옵션은 바이트 수준 GS1 그룹 구분자를 기대하는 디코더와의 호환성을 향상시킬 수 있으며, '%' 데이터 문자가 GS1 구분자로 해석되는 것을 방지합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩해야 하는지 여부를 나타내는 값. |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


BarCode의 인코딩 모드에 대한 QR 심볼 유형. 기본값: QREncodeMode.Auto.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel을 참조하십시오.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


MicroQR 코드 버전. M1 버전부터 M4 버전까지. 기본값은 MicroQRVersion.Auto입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


RectMicroQR 코드 버전. R7x59 버전부터 R17x139 버전까지. 기본값은 RectMicroQRVersion.Auto입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR 구조적 추가 매개변수. 구조적 추가 모드는 MicroQR 및 RectMicroQR 바코드에서 지원되지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


QR 코드 버전. Version1부터 Version40까지. 기본값은 QRVersion.Auto입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


이 [QrParameters](../../com.aspose.barcode.generation/qrparameters)의 사람 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [QrParameters](../../com.aspose.barcode.generation/qrparameters)를 나타내는 문자열.
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

