---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "QR 매개변수."
type: docs
weight: 830
url: /ko/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

QR 매개변수.

```js
new QrParameters()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D 바코드 모듈의 높이/너비 비율. |
| [getECIEncoding()](#geteciencoding) | Extended Channel Interpretation Identifiers(확장 채널 해석 식별자)입니다. 이는 바코드 리더에게 사용된 참조에 대한 자세한 정보를 알려주는 데 사용됩니다. |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [getEncodeMode()](#getencodemode) | 바코드 인코딩 모드의 QR 심볼 유형입니다. 기본값: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준입니다. 낮음에서 높음 순: LevelL, LevelM, LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | MicroQR 코드의 버전입니다. M1 버전부터 M4 버전까지. 기본값: MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers(확장 채널 해석 식별자)입니다. 이는 바코드 리더에게 사용된 참조에 대한 자세한 정보를 알려주는 데 사용됩니다. |
| [getQrEncodeMode()](#getqrencodemode) | 바코드 인코딩 모드의 QR 심볼 유형입니다. 기본값: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | QR / MicroQR 선택 모드입니다. 표준 QR 심볼에는 ForceQR을 선택하고, MicroQR에는 Auto를 선택합니다. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | QR 바코드에 대한 Reed-Solomon 오류 정정 수준입니다. 낮음에서 높음 순: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. QRError를 참조하십시오. |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | QR 코드의 버전입니다. QR 코드는 Version1부터 Version40까지, MicroQr은 M1부터 M4까지. 기본값: QRVersion.AUT |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | RectMicroQR 코드의 버전입니다. R7x59 버전부터 R17x139 버전까지. 기본값: RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | QR Structured Append 매개변수. |
| [getVersion()](#getversion) | QR 코드의 버전입니다. Version1부터 Version40까지. 기본값: QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | 2D 바코드 모듈의 높이/너비 비율. |
| [setECIEncoding()](#seteciencoding) | Extended Channel Interpretation Identifiers(확장 채널 해석 식별자)입니다. 이는 바코드 리더에게 사용된 참조에 대한 자세한 정보를 알려주는 데 사용됩니다. |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setEncodeMode()](#setencodemode) | 바코드 인코딩 모드의 QR 심볼 유형입니다. 기본값: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준입니다. 낮음에서 높음 순: LevelL, LevelM, LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | MicroQR 코드의 버전입니다. M1 버전부터 M4 버전까지. 기본값: MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers(확장 채널 해석 식별자)입니다. 이는 바코드 리더에게 사용된 참조에 대한 자세한 정보를 알려주는 데 사용됩니다. |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | 바코드 인코딩 모드의 QR 심볼 유형입니다. 기본값: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | QR / MicroQR 선택 모드입니다. 표준 QR 심볼에는 ForceQR을 선택하고, MicroQR에는 Auto를 선택합니다. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | QR 바코드에 대한 Reed-Solomon 오류 정정 수준입니다. 낮음에서 높음 순: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. QRError를 참조하십시오. |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | QR 코드의 버전입니다. QR 코드는 Version1부터 Version40까지, MicroQr은 M1부터 M4까지. 기본값: QRVersion.AUT |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | RectMicroQR 코드의 버전입니다. R7x59 버전부터 R17x139 버전까지. 기본값: RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | QR Structured Append 매개변수. |
| [setVersion()](#setversion) | QR 코드의 버전입니다. Version1부터 Version40까지. 기본값: QRVersion.Auto. |
| [toString()](#tostring) | 이 QrParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### getAspectRatio() {#getaspectratio}

2D 바코드 모듈의 높이/너비 비율.

### getECIEncoding() {#geteciencoding}

Extended Channel Interpretation Identifiers(확장 채널 해석 식별자)입니다. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더기에 전달하는 데 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩할지 여부를 나타내는 값을 가져오거나 설정합니다. false인 경우 QR 사양에 따라 GS1 구분 기호가 알파벳-숫자 모드에서 '%'로 인코딩될 수 있습니다. true인 경우 GS1 그룹 구분 기호가 0x1D 문자로 바이트 모드에 인코딩되고, '%' 문자도 데이터로 보존하기 위해 바이트 모드에 인코딩됩니다. 이 옵션은 바이트 수준의 GS1 그룹 구분 기호를 기대하는 디코더와의 호환성을 향상시키고, '%' 데이터 문자가 GS1 구분 기호로 해석되는 것을 방지할 수 있습니다.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

바코드 인코딩 모드의 QR 심볼 유형입니다. 기본값: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준입니다. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel을 참조하십시오.

### getMicroQRVersion() {#getmicroqrversion}

MicroQR 코드의 버전입니다. M1 버전부터 M4 버전까지. 기본값: MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. 기호에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더에게 전달하는 데 사용됩니다. 현재 구현은 알려진 모든 문자 집합 인코딩으로 구성됩니다.

### getQrEncodeMode() {#getqrencodemode}

바코드 인코딩 모드의 QR 심볼 유형입니다. 기본값: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR 선택 모드입니다. 표준 QR 심볼에는 ForceQR을 선택하고, MicroQR에는 Auto를 선택합니다.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

QR 바코드에 대한 Reed-Solomon 오류 정정 수준입니다. 낮음에서 높음 순: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. QRErrorLevel를 참조하십시오.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

QR 코드의 버전입니다. QR 코드는 Version1부터 Version40까지, MicroQr은 M1부터 M4까지. 기본값: QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

RectMicroQR 코드의 버전입니다. R7x59 버전부터 R17x139 버전까지. 기본값: RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

QR Structured Append 매개변수.

### getVersion() {#getversion}

QR 코드의 버전입니다. Version1부터 Version40까지. 기본값: QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

2D 바코드 모듈의 높이/너비 비율.

### setECIEncoding() {#seteciencoding}

Extended Channel Interpretation Identifiers(확장 채널 해석 식별자)입니다. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더기에 전달하는 데 사용됩니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. MicroQR에서는 지원되지 않습니다.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩할지 여부를 나타내는 값을 가져오거나 설정합니다. false인 경우 QR 사양에 따라 GS1 구분 기호가 알파벳-숫자 모드에서 '%'로 인코딩될 수 있습니다. true인 경우 GS1 그룹 구분 기호가 0x1D 문자로 바이트 모드에 인코딩되고, '%' 문자도 데이터로 보존하기 위해 바이트 모드에 인코딩됩니다. 이 옵션은 바이트 수준의 GS1 그룹 구분 기호를 기대하는 디코더와의 호환성을 향상시키고, '%' 데이터 문자가 GS1 구분 기호로 해석되는 것을 방지할 수 있습니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | QR 및 RectMicroQR 바코드에 대해 GS1 특수 문자를 바이트 모드로 인코딩할지 여부를 나타내는 값. |

### setEncodeMode() {#setencodemode}

바코드 인코딩 모드의 QR 심볼 유형입니다. 기본값: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

QR, MicroQR 및 RectMicroQR 바코드에 대한 Reed-Solomon 오류 정정 수준입니다. 낮음에서 높음 순: LevelL, LevelM, LevelQ, LevelH. QRErrorLevel을 참조하십시오.

### setMicroQRVersion() {#setmicroqrversion}

MicroQR 코드의 버전입니다. M1 버전부터 M4 버전까지. 기본값: MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. 기호에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더에게 전달하는 데 사용됩니다. 현재 구현은 알려진 모든 문자 집합 인코딩으로 구성됩니다.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

바코드 인코딩 모드의 QR 심볼 유형입니다. 기본값: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR 선택 모드입니다. 표준 QR 심볼에는 ForceQR을 선택하고, MicroQR에는 Auto를 선택합니다.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

QR 바코드에 대한 Reed-Solomon 오류 정정 수준입니다. 낮음에서 높음 순: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. QRErrorLevel를 참조하십시오.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

QR 코드의 버전입니다. QR 코드는 Version1부터 Version40까지, MicroQr은 M1부터 M4까지. 기본값: QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

RectMicroQR 코드의 버전입니다. R7x59 버전부터 R17x139 버전까지. 기본값: RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

QR Structured Append 매개변수.

### setVersion() {#setversion}

QR 코드의 버전입니다. Version1부터 Version40까지. 기본값: QRVersion.Auto.

### toString() {#tostring}

이 QrParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this QrParameters.
