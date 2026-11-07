---
title: "Aspose::BarCode::Generation::QrParameters Klasse"
linktitle: "QrParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::QrParameters Klasse. QR-Parameter in C++."
type: docs
weight: 4400
url: /de/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


QR-Parameter.

```cpp
class QrParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode-Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR. |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | QR‑Symbologie‑Typ des Kodierungsmodus von [BarCode](../../aspose.barcode/). Standardwert: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | Stufe der Reed‑Solomon-Fehlerkorrektur für QR-, MicroQR- und RectMicroQR‑Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. Siehe QRErrorLevel. |
| [get_MicroQRVersion](./get_microqrversion/)() const | Version des MicroQR-Codes. Von Version M1 bis Version M4. Standardwert ist [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | Version des RectMicroQR-Codes. Von Version R7x59 bis Version R17x139. Standardwert ist [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | QR Structured Append‑Parameter. Der Structured Append‑Modus wird von MicroQR‑ und RectMicroQR‑Barcodes nicht unterstützt. |
| [get_Version](./get_version/)() const | Version des QR‑Codes. Von Version1 bis Version40. Standardwert ist [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. Sie werden verwendet, um dem Barcode-Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR. |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | QR‑Symbologie‑Typ des Kodierungsmodus von [BarCode](../../aspose.barcode/). Standardwert: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | Stufe der Reed‑Solomon-Fehlerkorrektur für QR-, MicroQR- und RectMicroQR‑Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. Siehe QRErrorLevel. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | Version des MicroQR-Codes. Von Version M1 bis Version M4. Standardwert ist [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | Version des RectMicroQR-Codes. Von Version R7x59 bis Version R17x139. Standardwert ist [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | QR Structured Append‑Parameter. Der Structured Append‑Modus wird von MicroQR‑ und RectMicroQR‑Barcodes nicht unterstützt. |
| [set_Version](./set_version/)(QRVersion) | Version des QR‑Codes. Von Version1 bis Version40. Standardwert ist [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [QrParameters](./) zurück. |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
