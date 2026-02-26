---
title: QREncodeType Enum
linktitle: QREncodeType
articleTitle: QREncodeType
second_title: Aspose.BarCode for Node.js via Java
description: "QR / MicroQR selector mode. Select FORCE_QR for standard QR symbols, AUTO for MicroQR. FORCE_MICRO_QR is used for strongly MicroQR symbol generation if it is possible."
type: docs
weight: 970
url: /nodejs/qrencodetype/
---
## QREncodeType enumeration

QR / MicroQR selector mode. Select FORCE_QR for standard QR symbols, AUTO for MicroQR. FORCE_MICRO_QR is used for strongly MicroQR symbol generation if it is possible.

```javascript
public enum QREncodeType
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| AUTO | `0` | Mode starts barcode version negotiation from MicroQR V1 |
| FORCE_QR | `1` | Mode starts barcode version negotiation from QR V1 |
| FORCE_MICRO_QR | `2` | Mode starts barcode version negotiation from from MicroQR V1 to V4. If data cannot be encoded into MicroQR, exception is thrown. |

### See Also

* assembly [Aspose.BarCode](../)

