---
title: "DotCodeParameters"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "DotCode 매개변수."
type: docs
weight: 390
url: /ko/nodejs/aspose.barcode/dotcodeparameters/
---

## DotCodeParameters class

DotCode 매개변수.

```js
new DotCodeParameters()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D 바코드 모듈의 높이/너비 비율. |
| [getColumns()](#getcolumns) | 열 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 숫자 o |
| [getDotCodeEncodeMode()](#getdotcodeencodemode) ~~(deprecated)~~ | DotCode 인코드 모드를 식별합니다. 기본값: Auto. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | DotCode 구조화된 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 카운트는 1에서 35 사이의 값이어야 합니다. |
| [getECIEncoding()](#geteciencoding) | ECI 인코딩을 식별합니다. DotCodeEncodeMode가 AUTO일 때 사용됩니다. 기본값: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | DotCode 인코드 모드를 식별합니다. 기본값: Auto. |
| [getRows()](#getrows) | 행 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 행의 수 r |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | DotCode 구조화된 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 카운트는 1에서 35 사이의 값이어야 합니다. |
| [isReaderInitialization()](#isreaderinitialization) | 코드가 다음 데이터를 초기화 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다 또는 |
| [setAspectRatio()](#setaspectratio) | 2D 바코드 모듈의 높이/너비 비율. |
| [setColumns()](#setcolumns) | 열 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 숫자 o |
| [setDotCodeEncodeMode()](#setdotcodeencodemode) ~~(deprecated)~~ | DotCode 인코드 모드를 식별합니다. 기본값: Auto. |
| [setDotCodeStructuredAppendModeBarcodeId()](#setdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | DotCode 구조화된 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. |
| [setDotCodeStructuredAppendModeBarcodesCount()](#setdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 카운트는 1에서 35 사이의 값이어야 합니다. |
| [setECIEncoding()](#seteciencoding) | ECI 인코딩을 식별합니다. DotCodeEncodeMode가 AUTO일 때 사용됩니다. 기본값: ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | DotCode 인코드 모드를 식별합니다. 기본값: Auto. |
| [setReaderInitialization()](#setreaderinitialization) | 코드가 다음 데이터를 초기화 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다 또는 |
| [setRows()](#setrows) | 행 수를 식별합니다. DotCode 심볼의 행 수와 열 수의 합은 홀수여야 합니다. 행의 수 r |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | DotCode 구조화된 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. |
| [setStructuredAppendModeBarcodesCount()](#setstructuredappendmodebarcodescount) | DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 카운트는 1에서 35 사이의 값이어야 합니다. |
| [toString()](#tostring) | 이 DotCodeParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### getAspectRatio() {#getaspectratio}

2D 바코드 모듈의 높이/너비 비율.

### getColumns() {#getcolumns}

열 수를 식별합니다. DotCode 기호의 행 수와 열 수의 합은 홀수여야 합니다. 열 수는 최소 5이어야 합니다. 기본값: -1

### getDotCodeEncodeMode() {#getdotcodeencodemode}

> **Deprecated.** See method description for replacement.

DotCode 인코드 모드를 식별합니다. 기본값: Auto.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

DotCode 구조적 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 카운트는 1에서 35 사이의 값이어야 합니다.

### getECIEncoding() {#geteciencoding}

ECI 인코딩을 식별합니다. DotCodeEncodeMode가 AUTO일 때 사용됩니다. 기본값: ISO-8859-1

### getEncodeMode() {#getencodemode}

DotCode 인코드 모드를 식별합니다. 기본값: Auto.

### getRows() {#getrows}

행 수를 식별합니다. DotCode 기호의 행 수와 열 수의 합은 홀수여야 합니다. 행 수는 최소 5이어야 합니다. 기본값: -1

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

DotCode 구조적 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 카운트는 1에서 35 사이의 값이어야 합니다.

### isReaderInitialization() {#isreaderinitialization}

코드가 다음 데이터를 초기화 또는 바코드 판독기 재프로그램 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다. 기본값은 false입니다.

### setAspectRatio() {#setaspectratio}

2D 바코드 모듈의 높이/너비 비율.

### setColumns() {#setcolumns}

열 수를 식별합니다. DotCode 기호의 행 수와 열 수의 합은 홀수여야 합니다. 열 수는 최소 5이어야 합니다. 기본값: -1

### setDotCodeEncodeMode() {#setdotcodeencodemode}

> **Deprecated.** See method description for replacement.

DotCode 인코드 모드를 식별합니다. 기본값: Auto.

### setDotCodeStructuredAppendModeBarcodeId() {#setdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

DotCode 구조적 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

### setDotCodeStructuredAppendModeBarcodesCount() {#setdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 카운트는 1에서 35 사이의 값이어야 합니다.

### setECIEncoding() {#seteciencoding}

ECI 인코딩을 식별합니다. DotCodeEncodeMode가 AUTO일 때 사용됩니다. 기본값: ISO-8859-1

### setEncodeMode() {#setencodemode}

DotCode 인코드 모드를 식별합니다. 기본값: Auto.

### setReaderInitialization() {#setreaderinitialization}

코드가 다음 데이터를 초기화 또는 바코드 판독기 재프로그램 지시로 해석하도록 판독기를 지시하는 데 사용되는지 여부를 나타냅니다. 기본값은 false입니다.

### setRows() {#setrows}

행 수를 식별합니다. DotCode 기호의 행 수와 열 수의 합은 홀수여야 합니다. 행 수는 최소 5이어야 합니다. 기본값: -1

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

DotCode 구조적 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

### setStructuredAppendModeBarcodesCount() {#setstructuredappendmodebarcodescount}

DotCode 구조적 추가 모드 바코드 수를 식별합니다. 기본값은 -1입니다. 카운트는 1에서 35 사이의 값이어야 합니다.

### toString() {#tostring}

이 DotCodeParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this DotCodeParameters.
