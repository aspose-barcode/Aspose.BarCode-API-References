---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "Aztec 매개변수."
type: docs
weight: 70
url: /ko/nodejs/aspose.barcode/aztecparameters/
---

## AztecParameters class

Aztec 매개변수.

```js
new AztecParameters()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D 바코드 모듈의 높이/너비 비율. |
| [getAztecEncodeMode()](#getaztecencodemode) ~~(deprecated)~~ | Aztec 인코드 모드를 가져옵니다. 기본값: Auto. |
| [getAztecErrorLevel()](#getaztecerrorlevel) ~~(deprecated)~~ | Aztec 유형 바코드의 오류 정정 수준입니다. 값은 5에서 95 사이여야 합니다. |
| [getAztecSymbolMode()](#getaztecsymbolmode) ~~(deprecated)~~ | Aztec Symbol 모드를 가져옵니다. 기본값: AztecSymbolMode.Auto. |
| [getECIEncoding()](#geteciencoding) | ECI 인코딩을 가져옵니다. AztecEncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Aztec 인코드 모드를 가져옵니다. 기본값: Auto. |
| [getErrorLevel()](#geterrorlevel) | Aztec 유형 바코드의 오류 정정 수준입니다. 값은 5에서 95 사이여야 합니다. |
| [getLayersCount()](#getlayerscount) | Aztec 심볼의 레이어 수를 가져옵니다. Compact 모드에서는 레이어 수가 1에서 3 사이여야 하며, 일반 모드에서도 1에서 3 사이여야 합니다. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Aztec 바코드의 Structured Append 모드용 바코드 ID입니다. 바코드 ID는 1부터 바코드 수까지의 범위여야 합니다. 기본값 |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Aztec 바코드의 Structured Append 모드에 대한 바코드 수. 바코드 수는 1에서 26 사이여야 합니다. 기본값 |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Aztec 바코드의 Structured Append 모드에 대한 파일 ID(선택 필드). 파일 ID에는 공백이 포함될 수 없습니다. 기본값: |
| [getSymbolMode()](#getsymbolmode) | Aztec Symbol 모드를 가져옵니다. 기본값: AztecSymbolMode.Auto. |
| [isReaderInitialization()](#isreaderinitialization) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [setAspectRatio()](#setaspectratio) | 2D 바코드 모듈의 높이/너비 비율. |
| [setAztecEncodeMode()](#setaztecencodemode) ~~(deprecated)~~ | Aztec 인코드 모드를 설정합니다. 기본값: Auto. |
| [setAztecErrorLevel()](#setaztecerrorlevel) ~~(deprecated)~~ | Aztec 유형 바코드의 오류 정정 수준입니다. 값은 5에서 95 사이여야 합니다. |
| [setAztecSymbolMode()](#setaztecsymbolmode) ~~(deprecated)~~ | Aztec Symbol 모드를 설정합니다. 기본값: AztecSymbolMode.Auto. |
| [setECIEncoding()](#seteciencoding) | ECI 인코딩을 설정합니다. AztecEncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1 |
| [setEncodeMode(value)](#setencodemode) | Aztec 인코드 모드를 설정합니다. 기본값: Auto. |
| [setErrorLevel()](#seterrorlevel) | Aztec 유형 바코드의 오류 정정 수준입니다. 값은 5에서 95 사이여야 합니다. |
| [setLayersCount()](#setlayerscount) | Aztec 심볼의 레이어 수를 설정합니다. 레이어 수는 Compact 모드에서 1에서 3 사이여야 합니다. |
| [setReaderInitialization()](#setreaderinitialization) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | Aztec 바코드의 Structured Append 모드용 바코드 ID입니다. 바코드 ID는 1부터 바코드 수까지의 범위여야 합니다. 기본값 |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Aztec 바코드의 Structured Append 모드에 대한 바코드 수. 바코드 수는 1에서 26 사이여야 합니다. 기본값 |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Aztec 바코드의 Structured Append 모드에 대한 파일 ID(선택 필드). 파일 ID에는 공백이 포함될 수 없습니다. 기본값: |
| [setSymbolMode(value)](#setsymbolmode) | Aztec Symbol 모드를 설정합니다. 기본값: AztecSymbolMode.Auto. |
| [toString()](#tostring) | `AztecParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### getAspectRatio() {#getaspectratio}

2D 바코드 모듈의 높이/너비 비율.

### getAztecEncodeMode() {#getaztecencodemode}

> **Deprecated.** See method description for replacement.

Aztec 인코드 모드를 가져옵니다. 기본값: Auto.

### getAztecErrorLevel() {#getaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Aztec 유형 바코드의 오류 정정 수준입니다. 값은 5에서 95 사이여야 합니다.

### getAztecSymbolMode() {#getaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Aztec Symbol 모드를 가져옵니다. 기본값: AztecSymbolMode.Auto.

### getECIEncoding() {#geteciencoding}

ECI 인코딩을 가져옵니다. AztecEncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1

### getEncodeMode() {#getencodemode}

Aztec 인코드 모드를 가져옵니다. 기본값: Auto.

**Returns:** a Aztec encode mode.

### getErrorLevel() {#geterrorlevel}

Aztec 유형 바코드의 오류 정정 수준입니다. 값은 5에서 95 사이여야 합니다.

### getLayersCount() {#getlayerscount}

Aztec 심볼의 레이어 수를 가져옵니다. 레이어 수는 Compact 모드에서는 1에서 3 사이, Full Range 모드에서는 1에서 32 사이여야 합니다. 기본값: 0 (auto).

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Aztec 바코드의 Structured Append 모드에 대한 바코드 ID. 바코드 ID는 1에서 바코드 수 사이여야 합니다. 기본값: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Aztec 바코드의 Structured Append 모드에 대한 바코드 수. 바코드 수는 1에서 26 사이여야 합니다. 기본값: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

Aztec 바코드의 Structured Append 모드에 대한 파일 ID(선택 필드). 파일 ID에는 공백이 포함될 수 없습니다. 기본값: 빈 문자열

### getSymbolMode() {#getsymbolmode}

Aztec Symbol 모드를 가져옵니다. 기본값: AztecSymbolMode.Auto.

**Returns:** a Aztec Symbol mode.

### isReaderInitialization() {#isreaderinitialization}

리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.

### setAspectRatio() {#setaspectratio}

2D 바코드 모듈의 높이/너비 비율.

### setAztecEncodeMode() {#setaztecencodemode}

> **Deprecated.** See method description for replacement.

Aztec 인코드 모드를 설정합니다. 기본값: Auto.

### setAztecErrorLevel() {#setaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Aztec 유형 바코드의 오류 정정 수준입니다. 값은 5에서 95 사이여야 합니다.

### setAztecSymbolMode() {#setaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Aztec Symbol 모드를 설정합니다. 기본값: AztecSymbolMode.Auto.

### setECIEncoding() {#seteciencoding}

ECI 인코딩을 설정합니다. AztecEncodeMode가 Auto일 때 사용됩니다. 기본값: ISO-8859-1

### setEncodeMode(value) {#setencodemode}

Aztec 인코드 모드를 설정합니다. 기본값: Auto.

| 매개변수 | 설명 |
| --- | --- |
| 값 | Aztec 인코드 모드. |

### setErrorLevel() {#seterrorlevel}

Aztec 유형 바코드의 오류 정정 수준입니다. 값은 5에서 95 사이여야 합니다.

### setLayersCount() {#setlayerscount}

Aztec 심볼의 레이어 수를 설정합니다. 레이어 수는 Compact 모드에서는 1에서 3 사이, Full Range 모드에서는 1에서 32 사이여야 합니다. 기본값: 0 (auto).

### setReaderInitialization() {#setreaderinitialization}

리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Aztec 바코드의 Structured Append 모드에 대한 바코드 ID. 바코드 ID는 1에서 바코드 수 사이여야 합니다. 기본값: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Aztec 바코드의 Structured Append 모드에 대한 바코드 수. 바코드 수는 1에서 26 사이여야 합니다. 기본값: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

Aztec 바코드의 Structured Append 모드에 대한 파일 ID(선택 필드). 파일 ID에는 공백이 포함될 수 없습니다. 기본값: 빈 문자열

### setSymbolMode(value) {#setsymbolmode}

Aztec Symbol 모드를 설정합니다. 기본값: AztecSymbolMode.Auto.

| 매개변수 | 설명 |
| --- | --- |
| 값 | Aztec Symbol 모드. |

### toString() {#tostring}

`AztecParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this `AztecParameters`.
