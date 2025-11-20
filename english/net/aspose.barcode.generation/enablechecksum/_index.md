---
title: Enum EnableChecksum
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.EnableChecksum enum. Enable checksum during generation for 1D barcodes
type: docs
weight: 1180
url: /net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

Enable checksum during generation for 1D barcodes.

Default is treated as Yes for symbologies which must contain checksum, as No where checksum only possible.

Checksum never used: Codabar

Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum always used: Rest symbologies

```csharp
public enum EnableChecksum
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | `0` | If checksum is required by the specification - it will be attached. |
| Yes | `1` | Always use checksum if possible. |
| No | `2` | Do not use checksum. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


