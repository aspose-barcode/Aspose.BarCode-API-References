---
title: Class QrParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.QrParameters class. QR parameters
type: docs
weight: 1330
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
| [QrECIEncoding](../../aspose.barcode.generation/qrparameters/qreciencoding/) { get; set; } | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. |
| [QrEncodeMode](../../aspose.barcode.generation/qrparameters/qrencodemode/) { get; set; } | QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto. |
| [QrEncodeType](../../aspose.barcode.generation/qrparameters/qrencodetype/) { get; set; } | QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. |
| [QrErrorLevel](../../aspose.barcode.generation/qrparameters/qrerrorlevel/) { get; set; } | Level of Reed-Solomon error correction for QR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. see QRErrorLevel. |
| [QrVersion](../../aspose.barcode.generation/qrparameters/qrversion/) { get; set; } | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.Auto. |
| [StructuredAppend](../../aspose.barcode.generation/qrparameters/structuredappend/) { get; set; } | QR structured append parameters. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/qrparameters/tostring/)() | Returns a human-readable string representation of this `QrParameters`. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


