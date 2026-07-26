---
title: BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode
second_title: Aspose.BarCode for .NET API Reference
description: BarcodeGeneratorElement property. Gets or sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes
type: docs
weight: 1290
url: /net/aspose.barcode.wpf/barcodegeneratorelement/qrencodegs1separatorinbytemode/
---
## BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode property

Gets or sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

If false, GS1 separators may be encoded as '%' in Alphanumeric mode according to QR specification.

If true, GS1 group separators are encoded in Byte mode as the 0x1D character, and '%' characters are also encoded in Byte mode to preserve them as data.

This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '%' data characters from being interpreted as GS1 separators.

```csharp
public bool QREncodeGS1SeparatorInByteMode { get; set; }
```

### See Also

* class [BarcodeGeneratorElement](../)
* namespace [Aspose.BarCode.WPF](../../../aspose.barcode.wpf/)
* assembly [Aspose.BarCode](../../../)


