---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "ComplexCodetextReader 将 codetext 解码为指定的复杂条形码类型。"
type: docs
weight: 290
url: /zh/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader 将 codetext 解码为指定的复杂条形码类型。

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

## 方法

| 名称 | 描述 |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | 解码 HIBC LIC codetext。 |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | 解码 HIBC PAS codetext。 |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | 解码 Mailmark 条形码 C 和 L codetext。 |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | 解码 Royal Mail Mailmark 2D codetext。 |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | 解码 MaxiCode codetext。 |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | 解码 SwissQR codetext。 |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | 解码 USADriveId codetext。 |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

解码 HIBC LIC codetext。

| 参数 | 描述 |
| --- | --- |
| encodedCodetext | 已编码的 codetext |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

解码 HIBC PAS codetext。

| 参数 | 描述 |
| --- | --- |
| encodedCodetext | 已编码的 codetext |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

解码 Mailmark 条形码 C 和 L codetext。

| 参数 | 描述 |
| --- | --- |
| encodedCodetext | 已编码的 codetext |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

解码 Royal Mail Mailmark 2D codetext。

| 参数 | 描述 |
| --- | --- |
| encodedCodetext | 已编码的 codetext |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

解码 MaxiCode codetext。

| 参数 | 描述 |
| --- | --- |
| maxiCodeMode | MaxiCode 模式 |
| encodedCodetext | 已编码的 codetext |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

解码 SwissQR codetext。

| 参数 | 描述 |
| --- | --- |
| encodedCodetext | 已编码的 codetext |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

解码 USADriveId codetext。

| 参数 | 描述 |
| --- | --- |
| encodedCodetext | 已编码的 codetext |

**Returns:** Decoded USADriveId or null.
