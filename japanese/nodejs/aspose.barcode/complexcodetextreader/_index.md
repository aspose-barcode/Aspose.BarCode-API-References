---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "ComplexCodetextReader は codetext を指定された複合バーコードタイプにデコードします。"
type: docs
weight: 290
url: /ja/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader は codetext を指定された複合バーコードタイプにデコードします。

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

## メソッド

| 名前 | 説明 |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | HIBC LIC コードテキストをデコードします。 |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | HIBC PAS コードテキストをデコードします。 |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Mailmark バーコード C と L のコードテキストをデコードします。 |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Royal Mail Mailmark 2D コードテキストをデコードします。 |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | MaxiCode コードテキストをデコードします。 |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | SwissQR コードテキストをデコードします。 |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | USADriveId コードテキストをデコードします。 |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

HIBC LIC コードテキストをデコードします。

| パラメータ | 説明 |
| --- | --- |
| encodedCodetext | エンコードされたコードテキスト |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

HIBC PAS コードテキストをデコードします。

| パラメータ | 説明 |
| --- | --- |
| encodedCodetext | エンコードされたコードテキスト |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Mailmark バーコード C と L のコードテキストをデコードします。

| パラメータ | 説明 |
| --- | --- |
| encodedCodetext | エンコードされたコードテキスト |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Royal Mail Mailmark 2D コードテキストをデコードします。

| パラメータ | 説明 |
| --- | --- |
| encodedCodetext | エンコードされたコードテキスト |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

MaxiCode コードテキストをデコードします。

| パラメータ | 説明 |
| --- | --- |
| maxiCodeMode | MaxiCode モード |
| encodedCodetext | エンコードされたコードテキスト |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

SwissQR コードテキストをデコードします。

| パラメータ | 説明 |
| --- | --- |
| encodedCodetext | エンコードされたコードテキスト |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

USADriveId コードテキストをデコードします。

| パラメータ | 説明 |
| --- | --- |
| encodedCodetext | エンコードされたコードテキスト |

**Returns:** Decoded USADriveId or null.
