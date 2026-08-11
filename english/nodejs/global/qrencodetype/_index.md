---
title: "QREncodeType"
linktitle: "QREncodeType"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "QR / MicroQR selector mode."
type: docs
weight: 490
url: /nodejs/global/qrencodetype/
---

## QREncodeType

QR / MicroQR selector mode. Select FORCE_QR for standard QR symbols, AUTO for MicroQR. FORCE_MICRO_QR is used for strongly MicroQR symbol generation if it is possible.

## Values

| Name | Description |
| --- | --- |
| AUTO | Mode starts barcode version negotiation from MicroQR V1 |
| FORCE_QR | Mode starts barcode version negotiation from QR V1 |
| FORCE_MICRO_QR | Mode starts barcode version negotiation from from MicroQR V1 to V4. If data cannot be encoded into MicroQR, exception is thrown. |
