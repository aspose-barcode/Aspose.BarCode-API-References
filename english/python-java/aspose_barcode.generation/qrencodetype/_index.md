---
title: "QREncodeType"
linktitle: "QREncodeType"
second_title: "Aspose.BarCode for Python via Java"
description: "QR / MicroQR selector mode. Select FORCE_QR for standard QR symbols, AUTO for MicroQR. FORCE_MICRO_QR is used for strongly MicroQR symbol generation if it is po"
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/qrencodetype/
---

## QREncodeType enum

**Module:** `aspose_barcode.generation.qr_encode_type`


QR / MicroQR selector mode. Select FORCE_QR for standard QR symbols, AUTO for MicroQR. FORCE_MICRO_QR is used for strongly MicroQR symbol generation if it is possible.


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [AUTO](#auto) | `0` | Mode starts barcode version negotiation from MicroQR V1. |
| [FORCE_MICRO_QR](#force_micro_qr) | `2` | Mode starts barcode version negotiation from from MicroQR V1 to V4. If data cannot be encoded into MicroQR, exception is thrown. |
| [FORCE_QR](#force_qr) | `1` | Mode starts barcode version negotiation from QR V1. |
### QREncodeType.AUTO {#auto}

**Type:** `int`

**Value:** `0`

Mode starts barcode version negotiation from MicroQR V1.

### QREncodeType.FORCE_MICRO_QR {#force_micro_qr}

**Type:** `int`

**Value:** `2`

Mode starts barcode version negotiation from from MicroQR V1 to V4. If data cannot be encoded into MicroQR, exception is thrown.

### QREncodeType.FORCE_QR {#force_qr}

**Type:** `int`

**Value:** `1`

Mode starts barcode version negotiation from QR V1.

