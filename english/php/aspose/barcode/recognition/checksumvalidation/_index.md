---
title: "ChecksumValidation Enum"
linktitle: "ChecksumValidation"
articleTitle: "ChecksumValidation"
second_title: "Aspose.BarCode for PHP via Java"
description: "Enable checksum validation during recognition for 1D barcodes. Default is treated as Yes for symbologies which must contain checksum, as No where checksum only possible. Checksum never used: Codabar C"
type: docs
weight: 10
url: /php/aspose/barcode/recognition/checksumvalidation/
---

## ChecksumValidation enum

**Namespace:** `Aspose.Barcode.Recognition`


Enable checksum validation during recognition for 1D barcodes. Default is treated as Yes for symbologies which must contain checksum, as No where checksum only possible. Checksum never used: Codabar Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Checksum always used: Rest symbologies This sample shows influence of ChecksumValidation on recognition quality and results


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [DEFAULT](/php/aspose/barcode/recognition/checksumvalidation/default/) | `0` | If checksum is required by the specification - it will be validated. |
| [OFF](/php/aspose/barcode/recognition/checksumvalidation/off/) | `2` | Do not validate checksum. |
| [ON](/php/aspose/barcode/recognition/checksumvalidation/on/) | `1` | Always validate checksum if possible. |
