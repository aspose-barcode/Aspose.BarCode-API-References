---
title: "ChecksumValidation Enum"
linktitle: "ChecksumValidation"
articleTitle: "ChecksumValidation"
second_title: "Aspose.BarCode for Python via Java"
description: "Enable checksum validation during recognition for 1D barcodes. Default is treated as Yes for symbologies which must contain checksum, as No where checksum only "
type: docs
weight: 10
url: /python-java/aspose_barcode.recognition/checksumvalidation/
---

## ChecksumValidation enum

**Module:** `aspose_barcode.recognition.checksum_validation`


Enable checksum validation during recognition for 1D barcodes. Default is treated as Yes for symbologies which must contain checksum, as No where checksum only possible. Checksum never used: Codabar Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Checksum always used: Rest symbologies This sample shows influence of ChecksumValidation on recognition quality and results


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [DEFAULT](./default/) | `0` | If checksum is required by the specification - it will be validated. |
| [OFF](./off/) | `2` | Do not validate checksum. |
| [ON](./on/) | `1` | Always validate checksum if possible. |
