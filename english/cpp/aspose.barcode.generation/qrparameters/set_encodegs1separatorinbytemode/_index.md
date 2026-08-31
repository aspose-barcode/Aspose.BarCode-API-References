---
title:  method
linktitle: set_EncodeGS1SeparatorInByteMode
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use set_EncodeGS1SeparatorInByteMode method of Aspose::BarCode::Generation::QrParameters class in C++.'
type: docs
weight: 1800
url: /cpp/aspose.barcode.generation/qrparameters/set_encodegs1separatorinbytemode/
---
## QrParameters::set_EncodeGS1SeparatorInByteMode method




```cpp
void Aspose::BarCode::Generation::QrParameters::set_EncodeGS1SeparatorInByteMode(bool value)
```

## Remarks


Sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

If false, GS1 separators may be encoded as '' in Alphanumeric mode according to QR specification.

If true, GS1 group separators are encoded in Byte mode as the 0x1D character, and '' characters are also encoded in Byte mode to preserve them as data.

This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '' data characters from being interpreted as GS1 separators.
## See Also

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
