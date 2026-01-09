---
title:  enum
linktitle: QREncodeType
second_title: Aspose.BarCode for C++ API Reference
description: ' enum. QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. ForceMicroQR is used for strongly MicroQR symbol generation if it is possible in C++.'
type: docs
weight: 7700
url: /cpp/aspose.barcode.generation/qrencodetype/
---
## QREncodeType enum


QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. ForceMicroQR is used for strongly MicroQR symbol generation if it is possible.

```cpp
enum class QREncodeType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | Mode starts barcode version negotiation from MicroQR V1 |
| ForceQR | 1 | Mode starts barcode version negotiation from QR V1 |
| ForceMicroQR | 2 | Mode starts barcode version negotiation from from MicroQR V1 to V4. If data cannot be encoded into MicroQR, exception is thrown. |

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
