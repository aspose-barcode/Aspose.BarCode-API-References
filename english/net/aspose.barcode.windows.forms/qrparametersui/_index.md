---
title: Class QrParametersUI
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Windows.Forms.QrParametersUI class. UI wrapper for QrParameters class
type: docs
weight: 1750
url: /net/aspose.barcode.windows.forms/qrparametersui/
---
## QrParametersUI class

UI wrapper for [`QrParameters`](../../aspose.barcode.generation/qrparameters/) class.

```csharp
public class QrParametersUI
```

## Properties

| Name | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/qrparametersui/aspectratio/) { get; set; } | Height/Width ratio of 2D BarCode module. |
| [ECIEncoding](../../aspose.barcode.windows.forms/qrparametersui/eciencoding/) { get; set; } | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR. |
| [EncodeGS1SeparatorInByteMode](../../aspose.barcode.windows.forms/qrparametersui/encodegs1separatorinbytemode/) { get; set; } | Gets or sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. |
| [EncodeMode](../../aspose.barcode.windows.forms/qrparametersui/encodemode/) { get; set; } | QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.windows.forms/qrparametersui/errorlevel/) { get; set; } | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcodes. From low to high: LevelL, LevelM, LevelQ, LevelH. see QRErrorLevel. |
| [MicroQrVersion](../../aspose.barcode.windows.forms/qrparametersui/microqrversion/) { get; set; } | Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.Auto. |
| [RectMicroQrVersion](../../aspose.barcode.windows.forms/qrparametersui/rectmicroqrversion/) { get; set; } | Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto. |
| [Version](../../aspose.barcode.windows.forms/qrparametersui/version/) { get; set; } | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.Auto. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/qrparametersui/tostring/)() | Returns a human-readable string representation of this [`QrParameters`](../../aspose.barcode.generation/qrparameters/). |

### See Also

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


