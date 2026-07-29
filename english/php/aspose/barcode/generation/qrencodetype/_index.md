---
title: "QREncodeType Enum"
linktitle: "QREncodeType"
articleTitle: "QREncodeType"
second_title: "Aspose.BarCode for PHP via Java"
description: "QR / MicroQR selector mode. Select FORCE_QR for standard QR symbols, AUTO for MicroQR. FORCE_MICRO_QR is used for strongly MicroQR symbol generation if it is possible."
type: docs
weight: 10
url: /php/aspose/barcode/generation/qrencodetype/
---

## QREncodeType enum

**Namespace:** `Aspose.Barcode.Generation`


QR / MicroQR selector mode. Select FORCE_QR for standard QR symbols, AUTO for MicroQR. FORCE_MICRO_QR is used for strongly MicroQR symbol generation if it is possible.


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [AUTO](/php/aspose/barcode/generation/qrencodetype/auto/) | `"0"` | Mode starts barcode version negotiation from MicroQR V1 |
| [FORCE_MICRO_QR](/php/aspose/barcode/generation/qrencodetype/force_micro_qr/) | `"2"` | Mode starts barcode version negotiation from from MicroQR V1 to V4. If data cannot be encoded into MicroQR, exception is thrown. |
| [FORCE_QR](/php/aspose/barcode/generation/qrencodetype/force_qr/) | `"1"` | Mode starts barcode version negotiation from QR V1 |
