---
title: Aspose::BarCode::Generation::QrParameters class
linktitle: QrParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::QrParameters class. QR parameters in C++.'
type: docs
weight: 4000
url: /cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


QR parameters.

```cpp
class QrParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() | Height/Width ratio of 2D [BarCode](../../aspose.barcode/) module. |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR. |
| [get_EncodeMode](./get_encodemode/)() const | QR symbology type of [BarCode](../../aspose.barcode/)'s encoding mode. Default value: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel. |
| [get_MicroQRVersion](./get_microqrversion/)() const | Version of MicroQR Code. From version M1 to version M4. Default value is [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_QrECIEncoding](./get_qreciencoding/)() | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR. |
| [get_QrEncodeMode](./get_qrencodemode/)() | QR symbology type of [BarCode](../../aspose.barcode/)'s encoding mode. Default value: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_QrEncodeType](./get_qrencodetype/)() const | QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. |
| [get_QrErrorLevel](./get_qrerrorlevel/)() | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel. |
| [get_QrVersion](./get_qrversion/)() | Version of QR Code.From Version1 to Version40. Default value is [QRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | QR structured append parameters. Structured append mode is not suppported by MicroQR and RectMicroQR barcodes. |
| [get_Version](./get_version/)() const | Version of QR Code.From Version1 to Version40. Default value is [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Height/Width ratio of 2D [BarCode](../../aspose.barcode/) module. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings. Not supported by MicroQR. |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | QR symbology type of [BarCode](../../aspose.barcode/)'s encoding mode. Default value: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | Level of Reed-Solomon error correction for QR, MicroQR and RectMicroQR barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. See QRErrorLevel. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | Version of MicroQR Code. From version M1 to version M4. Default value is [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_QrEncodeType](./set_qrencodetype/)(QREncodeType) | QR / MicroQR selector mode. Select ForceQR for standard QR symbols, Auto for MicroQR. |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | Version of RectMicroQR Code. From version R7x59 to version R17x139. Default value is [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | QR structured append parameters. Structured append mode is not suppported by MicroQR and RectMicroQR barcodes. |
| [set_Version](./set_version/)(QRVersion) | Version of QR Code.From Version1 to Version40. Default value is [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [QrParameters](./). |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
