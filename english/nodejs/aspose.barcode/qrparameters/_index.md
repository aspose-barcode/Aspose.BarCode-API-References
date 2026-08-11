---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "QR parameters."
type: docs
weight: 830
url: /nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

QR parameters.

```js
new QrParameters()
```

## Methods

| Name | Description |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Height/Width ratio of 2D BarCode module. |
| [getECIEncoding()](#geteciencoding) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | Gets or sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR bar |
| [getEncodeMode()](#getencodemode) | QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [getQrEncodeMode()](#getqrencodemode) | QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. see QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.AUT |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | QR structured append parameters. |
| [getVersion()](#getversion) | Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | Height/Width ratio of 2D BarCode module. |
| [setECIEncoding()](#seteciencoding) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | Gets or sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR bar |
| [setEncodeMode()](#setencodemode) | QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. see QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.AUT |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | QR structured append parameters. |
| [setVersion()](#setversion) | Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto. |
| [toString()](#tostring) | Returns a human-readable string representation of this QrParameters. |

### getAspectRatio() {#getaspectratio}

Height/Width ratio of 2D BarCode module.

### getECIEncoding() {#geteciencoding}

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

Gets or sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If false, GS1 separators may be encoded as '%' in Alphanumeric mode according to QR specification. If true, GS1 group separators are encoded in Byte mode as the 0x1D character, and '%' characters are also encoded in Byte mode to preserve them as data. This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '%' data characters from being interpreted as GS1 separators.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

### getQrEncodeMode() {#getqrencodemode}

QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. see QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

QR structured append parameters.

### getVersion() {#getversion}

Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

Height/Width ratio of 2D BarCode module.

### setECIEncoding() {#seteciencoding}

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

Gets or sets a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. If false, GS1 separators may be encoded as '%' in Alphanumeric mode according to QR specification. If true, GS1 group separators are encoded in Byte mode as the 0x1D character, and '%' characters are also encoded in Byte mode to preserve them as data. This option may improve compatibility with decoders that expect byte-level GS1 group separators and prevents '%' data characters from being interpreted as GS1 separators.

| Parameter | Description |
| --- | --- |
| value | a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes. |

### setEncodeMode() {#setencodemode}

QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

Version of MicroQR Code. From version M1 to version M4. Default value is MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

QR symbology type of BarCode's encoding mode. Default value: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

Level of Reed-Solomon error correction for QR barcode. From low to high: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. see QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

Version of QR Code. From Version1 to Version40 for QR code and from M1 to M4 for MicroQr. Default value is QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

QR structured append parameters.

### setVersion() {#setversion}

Version of QR Code.From Version1 to Version40. Default value is QRVersion.Auto.

### toString() {#tostring}

Returns a human-readable string representation of this QrParameters.

**Returns:** A string that represents this QrParameters.
