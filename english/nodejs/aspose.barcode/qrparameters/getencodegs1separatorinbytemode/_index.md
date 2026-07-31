---
title: "QrParameters.getEncodeGS1SeparatorInByteMode"
linktitle: "getEncodeGS1SeparatorInByteMode"
articleTitle: "getEncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Gets or sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If false, GS1 separators may b..."
type: docs
weight: 30
url: /nodejs/aspose.barcode/qrparameters/getencodegs1separatorinbytemode/
---

## getEncodeGS1SeparatorInByteMode()

Gets or sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If false, GS1 separators may be encoded as '%' in Alphanumeric mode according to QR specification. If true, GS1 group separators are encoded in Byte mode as the 0x1D character, and '%' characters are also encoded in Byte mode to preserve them as data. This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '%' data characters from being interpreted as GS1 separators.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.
