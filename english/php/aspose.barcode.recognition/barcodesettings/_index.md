---
title: "BarcodeSettings Class"
linktitle: "BarcodeSettings"
articleTitle: "BarcodeSettings"
second_title: "Aspose.BarCode for PHP via Java"
description: "The main BarCode decoding parameters. Contains parameters which make influence on recognized data."
type: docs
weight: 10
url: /php/aspose.barcode.recognition/barcodesettings/
---

## BarcodeSettings class

**Namespace:** `Aspose.Barcode.Recognition`


The main BarCode decoding parameters. Contains parameters which make influence on recognized data.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](./barcodesettings/) | BarcodeSettings copy constructor |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AustraliaPost](./australiapost/) | Read-only | Gets AustraliaPost decoding parameters |
| [ChecksumValidation](./checksumvalidation/) | Read/Write | Enable checksum validation during recognition for 1D and Postal barcodes. Default is treated as Yes for symbologies which must contain checksum, as No where checksum only possible. Checksum never used: Codabar, PatchCode, Pharmacode, DataLogic2of5 Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Checksum always used: Rest symbologies |
| [DetectEncoding](./detectencoding/) | Read/Write | The flag which force engine to detect codetext encoding for Unicode codesets. Default value is true. |
| [StripFNC](./stripfnc/) | Read/Write | Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false. |
