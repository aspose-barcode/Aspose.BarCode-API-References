---
title: "QrParametersUI"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "UI 래퍼 for com.aspose.barcode.generation.QrParameters 클래스."
type: docs
weight: 17
url: /ko/java/com.aspose.barcode.barcodecontrol/qrparametersui/
---
**Inheritance:**
java.lang.Object
```
public class QrParametersUI
```

UI 래퍼 for com.aspose.barcode.generation.QrParameters 클래스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 바코드 모듈의 높이/너비 비율. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation 식별자. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) | QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getEncodeMode()](#getEncodeMode--) | BarCode 인코딩 모드의 QR 심볼 유형. |
| [getErrorLevel()](#getErrorLevel--) | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [getMicroQrVersion()](#getMicroQrVersion--) | MicroQR 코드 버전. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | RectMicroQR 코드 버전. |
| [getVersion()](#getVersion--) | QR 코드 버전. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 바코드 모듈의 높이/너비 비율. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation 식별자. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) | QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | BarCode 인코딩 모드의 QR 심볼 유형. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. |
| [setMicroQrVersion(MicroQRVersion value)](#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-) | MicroQR 코드 버전. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | RectMicroQR 코드 버전. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | QR 코드 버전. |
| [toString()](#toString--) | 이 [QrParameters](../../com.aspose.barcode.generation/qrparameters)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
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
public int getECIEncoding()
```


Extended Channel Interpretation Identifiers(확장 채널 해석 식별자). 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 자세한 정보를 바코드 리더에게 전달하는 데 사용됩니다. 현재 구현은 알려진 모든 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public boolean getEncodeGS1SeparatorInByteMode()
```


QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩할지 여부를 나타내는 값을 가져오거나 설정합니다.

false인 경우, QR 사양에 따라 GS1 구분자는 알파벳-숫자 모드에서 '%'로 인코딩될 수 있습니다.

true인 경우, GS1 그룹 구분자는 바이트 모드에서 0x1D 문자로 인코딩되며, '%' 문자도 데이터로 보존하기 위해 바이트 모드에서 인코딩됩니다.

이 옵션은 바이트 수준 GS1 그룹 구분자를 기대하는 디코더와의 호환성을 향상시킬 수 있으며, '%' 데이터 문자가 GS1 구분자로 해석되는 것을 방지합니다.

**Returns:**
boolean
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


BarCode 인코딩 모드의 QR 심볼 유형. 기본값: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮은 것부터 높은 것까지: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel을 참조하십시오.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQrVersion() {#getMicroQrVersion--}
```
public final MicroQRVersion getMicroQrVersion()
```


MicroQR 코드의 버전. M1 버전부터 M4 버전까지. 기본값은 MicroQRVersion.Auto입니다.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


RectMicroQR 코드의 버전. R7x59 버전부터 R17x139 버전까지. 기본값은 RectMicroQRVersion.Auto입니다.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


QR 코드의 버전. QR 코드는 Version1부터 Version40까지, MicroQr은 M1부터 M4까지. 기본값은 QRVersion.Auto입니다.

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


2D 바코드 모듈의 높이/너비 비율.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


Extended Channel Interpretation Identifiers(확장 채널 해석 식별자). 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 자세한 정보를 바코드 리더에게 전달하는 데 사용됩니다. 현재 구현은 알려진 모든 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public void setEncodeGS1SeparatorInByteMode(boolean value)
```


QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩할지 여부를 나타내는 값을 가져오거나 설정합니다.

false인 경우, QR 사양에 따라 GS1 구분자는 알파벳-숫자 모드에서 '%'로 인코딩될 수 있습니다.

true인 경우, GS1 그룹 구분자는 바이트 모드에서 0x1D 문자로 인코딩되며, '%' 문자도 데이터로 보존하기 위해 바이트 모드에서 인코딩됩니다.

이 옵션은 바이트 수준 GS1 그룹 구분자를 기대하는 디코더와의 호환성을 향상시킬 수 있으며, '%' 데이터 문자가 GS1 구분자로 해석되는 것을 방지합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


BarCode 인코딩 모드의 QR 심볼 유형. 기본값: QREncodeMode.Auto.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준. 낮은 것부터 높은 것까지: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel을 참조하십시오.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQrVersion(MicroQRVersion value) {#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQrVersion(MicroQRVersion value)
```


MicroQR 코드의 버전. M1 버전부터 M4 버전까지. 기본값은 MicroQRVersion.Auto입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


RectMicroQR 코드의 버전. R7x59 버전부터 R17x139 버전까지. 기본값은 RectMicroQRVersion.Auto입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


QR 코드의 버전. QR 코드는 Version1부터 Version40까지, MicroQr은 M1부터 M4까지. 기본값은 QRVersion.Auto입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


이 [QrParameters](../../com.aspose.barcode.generation/qrparameters)의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [QrParameters](../../com.aspose.barcode.generation/qrparameters)를 나타내는 문자열.
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

