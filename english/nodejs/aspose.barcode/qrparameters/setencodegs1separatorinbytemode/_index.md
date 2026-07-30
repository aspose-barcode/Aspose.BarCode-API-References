---
title: "QrParameters.setEncodeGS1SeparatorInByteMode"
linktitle: "setEncodeGS1SeparatorInByteMode"
articleTitle: "setEncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Gets or sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If false, GS1 separators may b..."
type: docs
weight: 170
url: /nodejs/aspose.barcode/qrparameters/setencodegs1separatorinbytemode/
---

## setEncodeGS1SeparatorInByteMode(value)

Gets or sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If false, GS1 separators may be encoded as '%' in Alphanumeric mode according to QR specification. If true, GS1 group separators are encoded in Byte mode as the 0x1D character, and '%' characters are also encoded in Byte mode to preserve them as data. This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '%' data characters from being interpreted as GS1 separators.

| Parameter | Description |
| --- | --- |
| value | a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. |
