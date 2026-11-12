---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "ComplexCodetextReader가 코드텍스트를 지정된 복합 바코드 유형으로 디코딩합니다."
type: docs
weight: 290
url: /ko/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader가 코드텍스트를 지정된 복합 바코드 유형으로 디코딩합니다.

```js
new ComplexCodetextReader()
```

**Example:**

```js
This sample shows how to recognize and decode SwissQR image.

 let cr = new BarCodeReader("SwissQRCodetext.png", null, DecodeType.QR);
 cr.read();
 let result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText(false));
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | HIBC LIC 코드 텍스트를 디코딩합니다. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | HIBC PAS 코드 텍스트를 디코딩합니다. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Mailmark 바코드 C 및 L 코드 텍스트를 디코딩합니다. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Royal Mail Mailmark 2D 코드 텍스트를 디코딩합니다. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | MaxiCode 코드 텍스트를 디코딩합니다. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | SwissQR 코드 텍스트를 디코딩합니다. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | USADriveId 코드 텍스트를 디코딩합니다. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

HIBC LIC 코드 텍스트를 디코딩합니다.

| 매개변수 | 설명 |
| --- | --- |
| encodedCodetext | 인코딩된 코드 텍스트 |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

HIBC PAS 코드 텍스트를 디코딩합니다.

| 매개변수 | 설명 |
| --- | --- |
| encodedCodetext | 인코딩된 코드 텍스트 |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Mailmark 바코드 C 및 L 코드 텍스트를 디코딩합니다.

| 매개변수 | 설명 |
| --- | --- |
| encodedCodetext | 인코딩된 코드 텍스트 |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Royal Mail Mailmark 2D 코드 텍스트를 디코딩합니다.

| 매개변수 | 설명 |
| --- | --- |
| encodedCodetext | 인코딩된 코드 텍스트 |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

MaxiCode 코드 텍스트를 디코딩합니다.

| 매개변수 | 설명 |
| --- | --- |
| maxiCodeMode | MaxiCode 모드 |
| encodedCodetext | 인코딩된 코드 텍스트 |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

SwissQR 코드 텍스트를 디코딩합니다.

| 매개변수 | 설명 |
| --- | --- |
| encodedCodetext | 인코딩된 코드 텍스트 |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

USADriveId 코드 텍스트를 디코딩합니다.

| 매개변수 | 설명 |
| --- | --- |
| encodedCodetext | 인코딩된 코드 텍스트 |

**Returns:** Decoded USADriveId or null.
