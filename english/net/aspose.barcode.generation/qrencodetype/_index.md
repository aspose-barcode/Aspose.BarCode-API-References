---
title: Enum QREncodeType
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.QREncodeType enum. QR / MicroQR selector mode. Select ForceQR for standard QR symbols Auto for MicroQR. ForceMicroQR is used for strongly MicroQR symbol generation if it is possible
type: docs
weight: 1520
url: /net/aspose.barcode.generation/qrencodetype/
---
## QREncodeType enumeration

QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. ForceMicroQR is used for strongly MicroQR symbol generation if it is possible.

```csharp
public enum QREncodeType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Mode starts barcode version negotiation from MicroQR V1 |
| ForceQR | `1` | Mode starts barcode version negotiation from QR V1 |
| ForceMicroQR | `2` | Mode starts barcode version negotiation from from MicroQR V1 to V4. If data cannot be encoded into MicroQR, exception is thrown. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


