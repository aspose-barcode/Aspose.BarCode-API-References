---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "MaxiCode 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스."
type: docs
weight: 600
url: /ko/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

MaxiCode 코드에 포함된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스입니다. 이 샘플은 원시 MaxiCode 코드텍스트를 MaxiCodeCodetext 인스턴스로 디코딩하는 방법을 보여줍니다.

```js
new MaxiCodeCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
     console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
     console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | 바코드 유형을 가져옵니다. |
| [getECIEncoding()](#geteciencoding) | ECI 인코딩을 가져옵니다. MaxiCodeEncodeMode가 AUTO인 경우에 사용됩니다. |
| [getEncodeMode()](#getencodemode) | MaxiCode 인코드 모드를 가져옵니다. 기본값: Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | MaxiCode 인코드 모드를 가져옵니다. |
| [getMode()](#getmode) | MaxiCode 모드를 가져옵니다. |
| [setECIEncoding()](#seteciencoding) | ECI 인코딩을 설정합니다. MaxiCodeEncodeMode가 AUTO인 경우에 사용됩니다. |
| [setEncodeMode(value)](#setencodemode) | MaxiCode 인코드 모드를 설정합니다. 기본값: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | MaxiCode 인코드 모드를 설정합니다. |

### getBarcodeType() {#getbarcodetype}

바코드 유형을 가져옵니다.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

ECI 인코딩을 가져옵니다. MaxiCodeEncodeMode가 AUTO인 경우에 사용됩니다.

### getEncodeMode() {#getencodemode}

MaxiCode 인코드 모드를 가져옵니다. 기본값: Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

MaxiCode 인코드 모드를 가져옵니다.

### getMode() {#getmode}

MaxiCode 모드를 가져옵니다.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

ECI 인코딩을 설정합니다. MaxiCodeEncodeMode가 AUTO인 경우에 사용됩니다.

### setEncodeMode(value) {#setencodemode}

MaxiCode 인코드 모드를 설정합니다. 기본값: Auto.

| 매개변수 | 설명 |
| --- | --- |
| 값 | MaxiCode 인코드 모드. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

MaxiCode 인코드 모드를 설정합니다.
