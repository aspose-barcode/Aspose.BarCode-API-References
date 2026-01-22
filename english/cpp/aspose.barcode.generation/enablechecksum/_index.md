---
title:  enum
linktitle: EnableChecksum
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use  enum in C++.'
type: docs
weight: 6200
url: /cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | If checksum is required by the specification - it will be attached. |
| Yes | 1 | Always use checksum if possible. |
| No | 2 | Do not use checksum. |

## Remarks


Enable checksum during generation for 1D barcodes.

Default is treated as Yes for symbologies which must contain checksum, as No where checksum only possible.

Checksum never used: Codabar

Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum always used: Rest symbologies
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
