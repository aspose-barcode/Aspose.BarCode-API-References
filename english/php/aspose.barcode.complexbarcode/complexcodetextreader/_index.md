---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for PHP via Java"
description: "ComplexCodetextReader decodes codetext to specified complex barcode type. This sample shows how to recognize and decode SwissQR image."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/complexcodetextreader/
---

## ComplexCodetextReader class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


ComplexCodetextReader decodes codetext to specified complex barcode type. This sample shows how to recognize and decode SwissQR image.


## Methods

| Name | Static | Description |
| --- | --- | --- |
| [tryDecodeHIBCLIC](#trydecodehibclic) | Yes | Decodes HIBC LIC codetext. |
| [tryDecodeHIBCPAS](#trydecodehibcpas) | Yes | Decodes HIBC PAS codetext. |
| [tryDecodeMailmark](#trydecodemailmark) | Yes | Decodes Mailmark Barcode C and L codetext. |
| [tryDecodeMailmark2D](#trydecodemailmark2d) | Yes | Decodes Royal Mail Mailmark 2D codetext. |
| [tryDecodeMaxiCode](#trydecodemaxicode) | Yes | Decodes MaxiCode codetext. |
| [tryDecodeSwissQR](#trydecodeswissqr) | Yes | Decodes SwissQR codetext. |
| [tryDecodeUSADriveId](#trydecodeusadriveid) | Yes | Decodes USADriveId codetext. |
### tryDecodeHIBCLICtryDecodeHIBCLIC(?string $encodedCodetext) (static) {#trydecodehibclic}

Decodes HIBC LIC codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$encodedCodetext` | `?string` |  |

**Returns:** HIBCLICComplexCodetext|null Decoded HIBC LIC Complex Codetext or null

### tryDecodeHIBCPAStryDecodeHIBCPAS(string $encodedCodetext) (static) {#trydecodehibcpas}

Decodes HIBC PAS codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$encodedCodetext` | `string` |  |

**Returns:** ?HIBCPASCodetext decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmarktryDecodeMailmark(string $encodedCodetext) (static) {#trydecodemailmark}

Decodes Mailmark Barcode C and L codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$encodedCodetext` | `string` |  |

**Returns:** MailmarkCodetext|null Mailmark Barcode C and L or null.

### tryDecodeMailmark2DtryDecodeMailmark2D(string $encodedCodetext) (static) {#trydecodemailmark2d}

Decodes Royal Mail Mailmark 2D codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$encodedCodetext` | `string` |  |

**Returns:** Mailmark2DCodetext decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCodetryDecodeMaxiCode(int $maxiCodeMode, string $encodedCodetext) (static) {#trydecodemaxicode}

Decodes MaxiCode codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$maxiCodeMode` | `int` |  |
| `$encodedCodetext` | `string` |  |

**Returns:** MaxiCodeCodetext Decoded MaxiCode codetext.

### tryDecodeSwissQRtryDecodeSwissQR(string $encodedCodetext) (static) {#trydecodeswissqr}

Decodes SwissQR codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$encodedCodetext` | `string` |  |

**Returns:** SwissQRCodetext decoded SwissQRCodetext or null.

### tryDecodeUSADriveIdtryDecodeUSADriveId(string $encodedCodetext) (static) {#trydecodeusadriveid}

Decodes USADriveId codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$encodedCodetext` | `string` |  |

**Returns:** ?USADriveIdCodetext Decoded USADriveId or null.

