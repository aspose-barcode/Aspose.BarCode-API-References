---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for PHP via Java"
description: "QR parameters."
type: docs
weight: 10
url: /php/aspose.barcode.generation/qrparameters/
---

## QrParameters class

**Namespace:** `Aspose.Barcode.Generation`


QR parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AspectRatio](#aspectratio) | Read/Write | Height/Width ratio of 2D BarCode module. |
| [ECIEncoding](#eciencoding) | Read/Write | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR. |
| [EncodeMode](#encodemode) | Read/Write | QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto. |
| [ErrorLevel](#errorlevel) | Read/Write | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel. |
| [MicroQRVersion](#microqrversion) | Read/Write | Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.Auto. |
| [QrECIEncoding](#qreciencoding) | Read/Write | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. |
| [QrEncodeMode](#qrencodemode) | Read/Write | QR symbology type of BarCode's encoding mode. Default value: QREncodeMode::AUTO. |
| [QrEncodeType](#qrencodetype) | Read/Write | QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. |
| [QrErrorLevel](#qrerrorlevel) | Read/Write | Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. |
| [QrVersion](#qrversion) | Read/Write | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion::AUTO. |
| [RectMicroQrVersion](#rectmicroqrversion) | Read/Write | Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto. |
| [StructuredAppend](#structuredappend) | Read/Write | QR structured append parameters. |
| [Version](#version) | Read/Write | Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto. |

### QrParameters__construct(QrParametersDTO $qrParametersDto) {#constructor}

| Parameter | Type | Description |
| --- | --- | --- |
| `$qrParametersDto` | `QrParametersDTO` |  |

### AspectRatio {#aspectratio}

**Access:** Read/Write

Height/Width ratio of 2D BarCode module.

Height/Width ratio of 2D BarCode module.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `float` |  |

### ECIEncoding {#eciencoding}

**Access:** Read/Write

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR.

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### EncodeMode {#encodemode}

**Access:** Read/Write

QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto.

QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### ErrorLevel {#errorlevel}

**Access:** Read/Write

Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel.

Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### MicroQRVersion {#microqrversion}

**Access:** Read/Write

Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.Auto.

Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### QrECIEncoding {#qreciencoding}

**Access:** Read/Write

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### QrEncodeMode {#qrencodemode}

**Access:** Read/Write

QR symbology type of BarCode's encoding mode. Default value: QREncodeMode::AUTO.

QR symbology type of BarCode's encoding mode. Default value: QREncodeMode::AUTO.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### QrEncodeType {#qrencodetype}

**Access:** Read/Write

QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR.

QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### QrErrorLevel {#qrerrorlevel}

**Access:** Read/Write

Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H.

Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### QrVersion {#qrversion}

**Access:** Read/Write

Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion::AUTO.

Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion::AUTO.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### RectMicroQrVersion {#rectmicroqrversion}

**Access:** Read/Write

Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto.

Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### StructuredAppend {#structuredappend}

**Access:** Read/Write

QR structured append parameters.

QR structured append parameters.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `QrStructuredAppendParameters` |  |

### Version {#version}

**Access:** Read/Write

Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto.

Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

