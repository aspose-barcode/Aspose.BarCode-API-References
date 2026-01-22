---
title: Class QrParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.QrParameters class. QR parameters
type: docs
weight: 1560
url: /net/aspose.barcode.generation/qrparameters/
---
## QrParameters class

QR parameters.

```csharp
public class QrParameters
```

## Properties

| Name | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/qrparameters/aspectratio/) { get; set; } | Height/Width ratio of 2D BarCode module. |
| [ECIEncoding](../../aspose.barcode.generation/qrparameters/eciencoding/) { get; set; } | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR. |
| [EncodeMode](../../aspose.barcode.generation/qrparameters/encodemode/) { get; set; } | QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.generation/qrparameters/errorlevel/) { get; set; } | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel. |
| [MicroQRVersion](../../aspose.barcode.generation/qrparameters/microqrversion/) { get; set; } | Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.Auto. |
| [QrECIEncoding](../../aspose.barcode.generation/qrparameters/qreciencoding/) { get; } | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR. |
| [QrEncodeMode](../../aspose.barcode.generation/qrparameters/qrencodemode/) { get; } | QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto. |
| [QrEncodeType](../../aspose.barcode.generation/qrparameters/qrencodetype/) { get; set; } | QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. |
| [QrErrorLevel](../../aspose.barcode.generation/qrparameters/qrerrorlevel/) { get; } | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel. |
| [QrVersion](../../aspose.barcode.generation/qrparameters/qrversion/) { get; } | Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto. |
| [RectMicroQrVersion](../../aspose.barcode.generation/qrparameters/rectmicroqrversion/) { get; set; } | Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto. |
| [StructuredAppend](../../aspose.barcode.generation/qrparameters/structuredappend/) { get; set; } | QR structured append parameters. Structured append mode is not suppported by MicroQR and RectMicroQR barcodes. |
| [Version](../../aspose.barcode.generation/qrparameters/version/) { get; set; } | Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/qrparameters/tostring/)() | Returns a human-readable string representation of this `QrParameters`. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


