---
title: ChecksumValidation Enum
linktitle: ChecksumValidation
articleTitle: ChecksumValidation
second_title: Aspose.BarCode for Node.js via Java
description: Enable checksum validation during recognition for 1D barcodes. Default is treated as Yes for symbologies which must contain checksum, as No where checksum only possible. Checksum never used: Codabar Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5...
type: docs
weight: 1510
url: /nodejs/checksumvalidation/
---
## ChecksumValidation enumeration

Enable checksum validation during recognition for 1D barcodes. Default is treated as Yes for symbologies which must contain checksum, as No where checksum only possible. Checksum never used: Codabar Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Checksum always used: Rest symbologies This sample shows influence of ChecksumValidation on recognition quality and results

```javascript
public enum ChecksumValidation
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| DEFAULT | `0` | If checksum is required by the specification - it will be validated. |
| ON | `1` | Always validate checksum if possible. |
| OFF | `2` | Do not validate checksum |

### See Also

* assembly [Aspose.BarCode](../)

