---
title: QrParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: QR 매개변수.
type: docs
weight: 64
url: /ko/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR 매개변수.
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D BarCode 모듈의 높이/너비 비율. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 확장 채널 해석 식별자. |
| [getEncodeMode()](#getEncodeMode--) | BarCode의 인코딩 모드에 대한 QR 심볼 유형. |
| [getErrorLevel()](#getErrorLevel--) | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [getMicroQRVersion()](#getMicroQRVersion--) | MicroQR Code 버전. |
| [getQrECIEncoding()](#getQrECIEncoding--) | 확장 채널 해석 식별자. |
| [getQrEncodeMode()](#getQrEncodeMode--) | BarCode의 인코딩 모드에 대한 QR 심볼 유형. |
| [getQrEncodeType()](#getQrEncodeType--) | QR / MicroQR 선택자 모드. |
| [getQrErrorLevel()](#getQrErrorLevel--) | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [getQrVersion()](#getQrVersion--) | QR 코드 버전. Version1부터 Version40까지. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | RectMicroQR Code 버전. |
| [getStructuredAppend()](#getStructuredAppend--) | QR 구조적 추가 매개변수. |
| [getVersion()](#getVersion--) | QR 코드 버전. Version1부터 Version40까지. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D BarCode 모듈의 높이/너비 비율. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 확장 채널 해석 식별자. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | BarCode의 인코딩 모드에 대한 QR 심볼 유형. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | MicroQR Code 버전. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | QR / MicroQR 선택자 모드. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | RectMicroQR Code 버전. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR 구조적 추가 매개변수. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | QR 코드 버전. Version1부터 Version40까지. |
| [toString()](#toString--) | 이 [QrParameters](../../com.aspose.barcode.generation/qrparameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다. |
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


Extended Channel Interpretation 식별자. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 자세한 정보를 바코드 리더에게 알려주기 위해 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다.

**Returns:**
int
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


QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮은 것부터 높은 것까지: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel를 참조하십시오.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


MicroQR 코드의 버전. M1 버전부터 M4 버전까지. 기본값은 MicroQRVersion.Auto입니다.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


Extended Channel Interpretation 식별자. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 자세한 정보를 바코드 리더에게 알려주기 위해 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


BarCode의 인코딩 모드에 대한 QR 심볼 유형. 기본값: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


QR / MicroQR 선택 모드. 표준 QR 기호에는 ForceQR을 선택하고, MicroQR에는 Auto를 선택하십시오.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮은 것부터 높은 것까지: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel를 참조하십시오.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


QR 코드의 버전. Version1부터 Version40까지. 기본값은 QRVersion.Auto입니다.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


RectMicroQR 코드의 버전. R7x59 버전부터 R17x139 버전까지. 기본값은 RectMicroQRVersion.Auto입니다.

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


QR 코드의 버전. Version1부터 Version40까지. 기본값은 QRVersion.Auto입니다.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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


Extended Channel Interpretation 식별자. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 자세한 정보를 바코드 리더에게 알려주기 위해 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


BarCode의 인코딩 모드에 대한 QR 심볼 유형. 기본값: QREncodeMode.Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮은 것부터 높은 것까지: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel를 참조하십시오.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


MicroQR 코드의 버전. M1 버전부터 M4 버전까지. 기본값은 MicroQRVersion.Auto입니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


QR / MicroQR 선택 모드. 표준 QR 기호에는 ForceQR을 선택하고, MicroQR에는 Auto를 선택하십시오.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


RectMicroQR 코드의 버전. R7x59 버전부터 R17x139 버전까지. 기본값은 RectMicroQRVersion.Auto입니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR 구조적 추가 매개변수. 구조적 추가 모드는 MicroQR 및 RectMicroQR 바코드에서 지원되지 않습니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


QR 코드의 버전. Version1부터 Version40까지. 기본값은 QRVersion.Auto입니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


이 [QrParameters](../../com.aspose.barcode.generation/qrparameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [QrParameters](../../com.aspose.barcode.generation/qrparameters)를 나타내는 문자열입니다.
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

