---
title: "QRExtendedParameters"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "인식된 바코드의 QR Structured Append 정보를 저장합니다"
type: docs
weight: 38
url: /ko/java/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

인식된 바코드의 QR Structured Append 정보를 저장합니다

이 샘플은 QR Structured Append 데이터를 가져오는 방법을 보여줍니다.

```
{
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | 인식된 바코드의 Reed-Solomon 오류 정정 수준. |
| [getMicroQRVersion()](#getMicroQRVersion--) | 인식된 MicroQR 코드의 버전. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | 인식된 RectMicroQR 코드의 버전. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | QR 구조 추가 모드 바코드의 인덱스를 가져옵니다. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | QR 구조 추가 모드 바코드 수량을 가져옵니다. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | QR 구조 추가 모드 패리티 데이터를 가져옵니다. |
| [getVersion()](#getVersion--) | 인식된 QR 코드의 버전. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isEmpty()](#isEmpty--) | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 이 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 System.Object 값입니다. |

**Returns:**
boolean -  **true**  객체가 이 인스턴스와 동일한 값을 갖는 경우; 그렇지 않으면,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


인식된 바코드의 Reed-Solomon 오류 정정 수준. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


인식된 MicroQR 코드의 버전. M1부터 M4까지.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


인식된 RectMicroQR 코드의 버전. R7x43부터 R17x139까지.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


QR 구조 추가 모드 바코드의 인덱스를 가져옵니다. 인덱스는 0부터 시작합니다. 기본값은 -1입니다.

값: QR 구조 추가 모드 바코드의 수량.

**Returns:**
int - QR 구조 추가 모드 바코드의 인덱스.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


QR 구조 추가 모드 바코드 수량을 가져옵니다. 기본값은 -1입니다.

값: QR 구조 추가 모드 바코드의 수량.

**Returns:**
int - QR 구조 추가 모드 바코드 수량.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


QR 구조 추가 모드 패리티 데이터를 가져옵니다. 기본값은 -1입니다.

값: QR 구조 추가 모드 바코드의 인덱스.

**Returns:**
int - QR 구조 추가 모드 패리티 데이터.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


인식된 QR 코드의 버전. Version1부터 Version40까지.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


모든 매개변수가 기본값만 가지고 있는지 테스트합니다.

값: 모든 매개변수가 기본값만 가지고 있으면 **true** 를 반환하고, 그렇지 않으면 **false** 를 반환합니다.

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




### toString() {#toString--}
```
public String toString()
```


이 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)를 나타내는 문자열.
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

